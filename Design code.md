<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#C5BAB9"
    tools:context=".MainActivity">


    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="108dp"
        android:text="Calculator"
        android:textColor="#3998A5"
        android:textSize="60sp"
        app:layout_constraintBottom_toTopOf="@+id/edittext1"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <EditText
        android:id="@+id/edittext1"
        android:layout_width="229dp"
        android:layout_height="52dp"
        android:layout_marginBottom="12dp"
        android:ems="10"
        android:inputType="textPersonName"
        android:text="First Number"
        android:textColor="#C33406"
        app:layout_constraintBottom_toTopOf="@+id/edittext2"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent" />

    <EditText
        android:id="@+id/edittext2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:ems="10"
        android:inputType="textPersonName"
        android:minHeight="48dp"
        android:text="Second Number"
        android:textColor="#C33406"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.452"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <Button
        android:id="@+id/button"
        android:layout_width="184dp"
        android:layout_height="100dp"
        android:text="Calculate"
        android:textSize="24sp"
        app:layout_constraintBottom_toTopOf="@+id/total"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.4"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/edittext2" />

    <TextView
        android:id="@+id/total"
        android:layout_width="195dp"
        android:layout_height="63dp"
        android:text="Total"
        android:textSize="48sp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.421"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/edittext2" />

</androidx.constraintlayout.widget.ConstraintLayout>