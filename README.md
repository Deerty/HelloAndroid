<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@android:color/white"
    tools:context=".MainActivity"
    tools:ignore="ContentDescription">

    <ImageView
        android:id="@+id/logo"
        android:layout_width="match_parent"
        android:layout_height="250dp"
        android:src="@drawable/udacitylogo" />

    <TextView
        android:id="@+id/verse"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@+id/logo"
        android:layout_centerHorizontal="true"
        android:layout_marginTop="16dp"
        android:text="@string/the_better_way_of_education"
        android:textAllCaps="true"
        android:textAppearance="?android:textAppearanceLarge" />

    <TextView
        android:id="@+id/name"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@+id/verse"
        android:layout_centerHorizontal="true"
        android:layout_margin="16dp"
        android:text="@string/udacity"
        android:textAppearance="?android:textAppearanceMedium"
        android:textStyle="bold" />

    <TextView
        android:id="@+id/adress"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@+id/name"
        android:layout_marginLeft="16dp"
        android:layout_marginStart="16dp"
        android:text="@string/_2465_latham_st"
        android:textAppearance="?android:textAppearanceMedium" />

    <TextView
        android:id="@+id/adress2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@+id/adress"
        android:layout_marginLeft="16dp"
        android:layout_marginStart="16dp"
        android:layout_marginTop="4dp"
        android:text="@string/mountain_view"
        android:textAppearance="?android:textAppearanceMedium" />

    <TextView
        android:id="@+id/adress3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@+id/adress2"
        android:layout_marginLeft="16dp"
        android:layout_marginStart="16dp"
        android:layout_marginTop="4dp"
        android:text="@string/ca_94043"
        android:textAppearance="?android:textAppearanceMedium" />

    <TextView
        android:id="@+id/adress4"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@+id/adress3"
        android:layout_marginLeft="16dp"
        android:layout_marginStart="16dp"
        android:layout_marginTop="4dp"
        android:autoLink="phone"
        android:text="@string/_1_650_555_5555"
        android:textAppearance="?android:textAppearanceMedium" />

    <TextView
        android:id="@+id/web"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@+id/adress4"
        android:layout_marginLeft="16dp"
        android:layout_marginStart="16dp"
        android:layout_marginTop="4dp"
        android:autoLink="web"
        android:linksClickable="true"
        android:text="@string/www.udacity.com"
        android:textAppearance="?android:textAppearanceMedium" />

</RelativeLayout>
