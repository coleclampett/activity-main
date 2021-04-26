<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:scrollbarTrackVertical="@color/purple_700"
    tools:context=".MainActivity">

    <ImageButton
        android:id="@+id/HR"
        android:layout_width="415dp"
        android:layout_height="250dp"
        android:adjustViewBounds="true"
        android:background="#2196F3"
        android:contentDescription="TODO"
        android:padding="20dp"
        android:scaleType="fitCenter"
        android:src="@drawable/pulse"
        tools:layout_editor_absoluteX="-14dp"
        tools:layout_editor_absoluteY="-2dp" />

    <fragment
        android:id="@+id/map"
        android:name="com.google.android.gms.maps.SupportMapFragment"
        android:layout_width="802dp"
        android:layout_height="612dp"
        app:layout_constraintStart_toStartOf="parent"
        tools:layout_editor_absoluteY="557dp" />

    <ImageButton
        android:id="@+id/Alerts"
        android:layout_width="800dp"
        android:layout_height="318dp"
        android:adjustViewBounds="true"
        android:background="#F44336"
        android:contentDescription="TODO"
        android:padding="20dp"
        android:scaleType="fitCenter"
        android:src="@drawable/capture1"
        tools:layout_editor_absoluteX="0dp"
        tools:layout_editor_absoluteY="244dp" />

    <ImageButton
        android:id="@+id/imageButton"
        android:layout_width="400dp"
        android:layout_height="246dp"
        android:background="#2196F3"
        android:src="@drawable/weather"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toEndOf="@+id/HR"
        tools:layout_editor_absoluteY="-4dp" />

    <View
        android:id="@+id/view"
        android:layout_width="390dp"
        android:layout_height="100dp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/map"
        app:layout_constraintVertical_bias="0.0" />

</androidx.constraintlayout.widget.ConstraintLayout>
