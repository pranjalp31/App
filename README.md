# App
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <ImageView
        android:id="@+id/imageView"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_alignParentStart="true"
        android:layout_alignParentTop="true"
        android:layout_alignParentEnd="true"
        android:layout_alignParentBottom="true"
        android:layout_marginStart="-1dp"
        android:layout_marginTop="2dp"
        android:layout_marginEnd="1dp"
        android:layout_marginBottom="-2dp"
        android:scaleType="fitXY"
        app:srcCompat="@drawable/download" />

    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/signin"
        android:text="Sign in"
        android:textColor="@color/black"
        android:textSize="35dp"
        android:textStyle="bold"
        android:layout_margin="50dp"
        android:gravity="center"/>
    <EditText
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/username"
        android:layout_below="@id/signin"
        android:background="#30ffffff"
        android:hint="Username"
        android:textColorHint="@color/black"
        android:textColor="@color/black"
        android:layout_margin="10dp"
        android:padding="20dp"
        android:drawableLeft="@drawable/ic_baseline_person_outline_24"
        android:drawablePadding="20dp"/>
    <EditText
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/password"
        android:layout_below="@id/username"
        android:background="#30ffffff"
        android:hint="Password"
        android:textColorHint="@color/black"
        android:textColor="@color/black"
        android:layout_margin="10dp"
        android:padding="20dp"
        android:drawableLeft="@drawable/ic_baseline_info_24"
        android:drawablePadding="20dp"
        android:inputType="textPassword"/>
    <com.google.android.material.button.MaterialButton
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:id="@+id/loginbtn"
        android:layout_below="@id/password"
        android:text="LOGIN"
        android:backgroundTint="@color/design_default_color_secondary"
    android:layout_centerHorizontal="true"
    android:layout_margin="20dp"
        />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:id="@+id/forgotpass"
        android:layout_below="@id/loginbtn"
        android:text="Forgot password?"
        android:textColor="@color/black"
        android:layout_centerHorizontal="true"
        android:layout_margin="20dp"/>

    <TextView
        android:id="@+id/others"
        android:layout_width="wrap_content"
        android:layout_height="57dp"
        android:layout_above="@+id/socialicons"
        android:layout_alignParentEnd="true"
        android:layout_marginEnd="122dp"
        android:layout_marginBottom="149dp"
        android:text="or sign in with"
        android:textSize="28sp" />

    <LinearLayout
        android:id="@+id/socialicons"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:gravity="center" />

    <ImageView
        android:id="@+id/imageView3"
        android:layout_width="98dp"
        android:layout_height="133dp"
        android:layout_alignParentStart="true"
        android:layout_alignParentTop="true"
        android:layout_alignParentEnd="true"
        android:layout_alignParentBottom="true"
        android:layout_marginStart="153dp"
        android:layout_marginTop="583dp"
        android:layout_marginEnd="138dp"
        android:layout_marginBottom="17dp"
        app:srcCompat="@drawable/google" />

    <ImageView
        android:id="@+id/imageView4"
        android:layout_width="98dp"
        android:layout_height="113dp"
        android:layout_alignParentTop="true"
        android:layout_alignParentEnd="true"
        android:layout_alignParentBottom="true"
        android:layout_marginTop="586dp"
        android:layout_marginEnd="293dp"
        android:layout_marginBottom="30dp"
        app:srcCompat="@drawable/maang" />

    <ImageView
        android:id="@+id/imageView5"
        android:layout_width="134dp"
        android:layout_height="78dp"
        android:layout_alignParentTop="true"
        android:layout_alignParentEnd="true"
        android:layout_alignParentBottom="true"
        android:layout_marginTop="607dp"
        android:layout_marginEnd="-9dp"
        android:layout_marginBottom="46dp"
        app:srcCompat="@drawable/twi" />


</RelativeLayout>
