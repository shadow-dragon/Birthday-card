# Birthday-card
It's just a simple birthday card app. [No User Input]

This is the code that I've used for Android Studio

<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context="org.example.android.birthdaycard.MainActivity">

    <TextView
        android:id="@+id/text1"
        android:text="Happy Birthday to You! Happy Birthday to You! Happy Birthday Dear Person! Happy Birthday to You!!"
        android:textSize="13sp"
        android:typeface="serif"
        android:paddingLeft="10dp"
        android:paddingRight="2dp"
        android:paddingTop="10dp"
        android:paddingBottom="5dp"
        android:background="#00796B"
        android:textColor="#FFFFFF"
        android:textStyle="bold"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent"

        />

    <ImageView
        android:id="@+id/cake1"
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:layout_alignParentLeft="true"
        android:layout_alignParentRight="false"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        android:src="@drawable/cake1" />

    <TextView
        android:id="@+id/text2"
        android:text="From Mayur"
        android:textSize="13sp"
        android:typeface="serif"
        android:paddingLeft="10dp"
        android:paddingRight="2dp"
        android:paddingTop="10dp"
        android:paddingBottom="5dp"
        android:background="#00796B"
        android:textColor="#FFFFFF"
        android:textStyle="bold"
        android:layout_width="100dp"
        android:layout_height="wrap_content"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintBottom_toBottomOf="parent" />
</android.support.constraint.ConstraintLayout>

