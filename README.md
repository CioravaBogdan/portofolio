# portofolio
My sites Portofolio
<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context="com.newjob.android.newjobwelcome.HappyBirthday">

    <RelativeLayout
        android:id="@+id/masterlayout"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:background="@drawable/a318868birthdayackground920x108ndroid">


        <LinearLayout
            android:id="@+id/firstlayout"
            android:layout_width="match_parent"
            android:layout_height="100dp"
            android:layout_alignParentTop="true">

            <ImageView
                android:id="@+id/hapykids"
                android:layout_width="match_parent"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:scaleType="centerCrop"
                android:src="@drawable/happykids1" />

            <ImageView
                android:id="@+id/hapykids1"
                android:src="@drawable/small"
                android:layout_width="match_parent"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:scaleType="centerCrop" />

            <ImageView
            android:id="@+id/download1"
            android:src="@drawable/download"
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:scaleType="centerCrop" />
        </LinearLayout>
        <LinearLayout
            android:id="@+id/linearbott"
            android:layout_width="match_parent"
            android:layout_height="100dp"
            android:layout_alignParentBottom="true">
            <ImageView
                android:id="@+id/original1"
                android:layout_width="match_parent"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:scaleType="centerCrop"
                android:src="@drawable/original" />

            <ImageView
                android:id="@+id/imagesss1"
                android:src="@drawable/imagesssss"
                android:layout_width="match_parent"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:scaleType="centerCrop" />

            <ImageView
                android:id="@+id/qadw1"
                android:src="@drawable/qadw"
                android:layout_width="match_parent"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:scaleType="centerCrop" />

        </LinearLayout>

        <LinearLayout
            android:id="@+id/linearandroid"
            android:layout_width="match_parent"
            android:layout_height="300dp"
            android:orientation="horizontal"
            android:layout_centerInParent="true"
            >
            <ImageView
                android:id="@+id/androidleft"
                android:layout_width="wrap_content"
                android:layout_height="match_parent"
                android:layout_marginLeft="8dp"
                android:layout_weight="1"
                android:scaleType="fitCenter"
                android:src="@drawable/baloons" />

            <TextView
                android:id="@+id/texthappy"
                android:layout_width="match_parent"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:layout_margin="5dp"
                android:paddingTop="10dp"
                android:paddingBottom="5dp"
                android:text="Happy Birthday To  You ALL!"
                android:textStyle="bold"
                android:autoSizeTextType="uniform"
                android:textColor="#FF9800"
                />

            <ImageView
                android:id="@+id/androidleft2"
                android:layout_width="wrap_content"
                android:layout_height="match_parent"
                android:layout_marginRight="8dp"
                android:layout_weight="1"
                android:scaleType="fitCenter"
                android:src="@drawable/baloons" />


        </LinearLayout>


    </RelativeLayout>

</android.support.constraint.ConstraintLayout>
