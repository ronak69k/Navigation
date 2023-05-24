# Navigation
I don't have time to maintain this anymore. I basically wrote the whole library in a rush, without tests, while being a serious expert beginner at the time. As a result, there's a lot of unpredictable moving parts and the tests probably aren't that great either. Don't really know, since I haven't touched this in ages.
![Screenshot_202](https://github.com/ronak69k/Navigation/assets/116078869/f537d06d-5ffa-4635-bd80-b048b17697f9)


activity_main.xml:



<RelativeLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Home"
        android:textColor="@color/lavender"
        android:layout_centerInParent="true"
        android:textSize="36sp" />

    <com.google.android.material.bottomnavigation.BottomNavigationView
        android:id="@+id/bottomNavigation"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:layout_marginEnd="20dp"
        android:layout_marginStart="20dp"
        android:layout_marginBottom="30dp"
        android:layout_marginTop="30dp"
        android:background="@drawable/bottom_background"
        android:elevation="2dp"
        app:itemIconSize="30dp"
        app:itemIconTint="@drawable/item_selector"
        app:itemRippleColor="@android:color/transparent"
        app:labelVisibilityMode="unlabeled"
        app:menu="@menu/bottom_menu" />

</RelativeLayout>
