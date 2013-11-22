<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:paddingBottom="@dimen/activity_vertical_margin"
    android:paddingLeft="@dimen/activity_horizontal_margin"
    android:paddingRight="@dimen/activity_horizontal_margin"
    android:paddingTop="@dimen/activity_vertical_margin"
    tools:context=".MainActivity" >


<TextView
    android:id="@+id/header"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content" 
    android:layout_centerHorizontal="true"
    android:layout_marginLeft="10dp"
    android:layout_marginTop="20dp"
    android:textStyle="bold"
    android:text="College Trip Planner"
    />
<Button
    android:id="@+id/start"
    android:layout_below="@+id/header"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content" 
    android:layout_centerHorizontal="true"
    android:text="Start"
    />
<Button
    android:id="@+id/help"
    android:layout_below="@+id/start"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content" 
    android:layout_centerHorizontal="true"
    android:text="Help"
    />
    
</RelativeLayout>
