<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@drawable/background"
    tools:context=".MainActivity">

    <Space
        android:id="@+id/space1"
        android:layout_width="match_parent"
        android:layout_height="50dp" />
    <ImageView
        android:id="@+id/logo"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_margin="40dp"
        android:layout_below="@id/space1"
        android:src="@drawable/logo"/>
    <Space
        android:id="@+id/space"
        android:layout_width="match_parent"
        android:layout_height="20dp"
        android:layout_below="@id/logo"
        />




    <TextView
        android:id="@+id/signin"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_below="@id/space"
        android:gravity="center"
        android:text="Sign In"
        android:textColor="@color/white"
        android:textSize="35dp"
        android:textStyle="bold" />
    <EditText
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/username"
        android:layout_below="@id/signin"
        android:background="#30ffffff"
        android:hint="Username"
        android:textColorHint="@color/white"
        android:layout_margin="10dp"
        android:padding="20dp"
        android:drawableLeft="@drawable/ic_baseline_person_24"
        android:drawablePadding="20dp"
        />

    <EditText
        android:id="@+id/password"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_below="@id/username"
        android:layout_marginTop="20dp"
        android:layout_marginBottom="10dp"
        android:background="#30ffffff"
        android:drawableLeft="@drawable/ic_baseline_person_24"
        android:drawablePadding="20dp"
        android:hint="Password"
        android:inputType="textPassword"
        android:padding="20dp"
        android:textColorHint="@color/white" />

    <com.google.android.material.button.MaterialButton
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:id="@+id/loginbtn"
        android:layout_below="@id/password"
        android:text="LOGIN"
        android:backgroundTint="@color/teal_200"
        android:layout_centerHorizontal="true"
        android:layout_margin="20dp"
        />
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:id="@+id/forgotpass"
        android:layout_below="@id/loginbtn"
        android:text="Forgot password?"
        android:textColor="@color/white"
        android:layout_centerHorizontal="true"
        android:layout_margin="10dp"
        />
<TextView
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:id="@+id/others"
    android:layout_above="@id/socialicons"
    android:text="find us on"
    android:layout_centerHorizontal="true"
    />
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/socialicons"
        android:layout_alignParentBottom="true"
       android:gravity="center" >
        <ImageView
            android:layout_width="48dp"
            android:layout_height="48dp"
            android:layout_margin="20dp"
            android:src="@drawable/google"/>

        <ImageView
            android:layout_width="48dp"
            android:layout_height="48dp"
            android:layout_margin="20dp"
            android:src="@drawable/fb"/>
        <ImageView
            android:layout_width="48dp"
            android:layout_height="48dp"
            android:layout_margin="20dp"
            android:src="@drawable/tw"/>

    </LinearLayout>

</RelativeLayout>
