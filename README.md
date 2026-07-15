<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@color/cardview_shadow_start_color"
    tools:context=".MainActivity">

<TextView
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:id="@+id/total_question"
    android:text="Total Questions"
    android:textStyle="bold"
    android:layout_centerHorizontal="true"
    android:textSize="20sp"
    tools:ignore="HardcodedText" />

    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/question"
        android:gravity="center_horizontal"
        android:textStyle="bold"
        android:text="This will be the question"
        android:textColor="@color/white"
        android:textSize="24dp"
        android:textAlignment="center"
        android:layout_margin="20dp"
        android:layout_above="@id/choices_layout"
        tools:ignore="HardcodedText,,SpUsage" />

    <LinearLayout
        android:id="@+id/choices_layout"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_alignBottom="@+id/ans_A"
        android:layout_centerInParent="true"
        android:layout_marginBottom="-169dp"
        android:orientation="vertical"
        tools:ignore="NotSibling,UselessLeaf">


        <Button
            android:id="@+id/ans_A"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_margin="5dp"
            android:backgroundTint="@color/white"
            android:text="Ans A"
            android:textColor="@color/black"
            tools:ignore="HardcodedText"
            tools:targetApi="21" />


        <Button
            android:id="@+id/ans_B"
            android:layout_width="401dp"
            android:layout_height="wrap_content"
            android:layout_margin="5dp"
            android:backgroundTint="@color/white"
            android:text="Ans B"
            android:textColor="@color/black"
            tools:ignore="HardcodedText"
            tools:targetApi="21" />

        <Button
            android:id="@+id/ans_C"
            android:layout_width="400dp"
            android:layout_height="38dp"
            android:layout_marginStart="5dp"
            android:layout_marginLeft="5dp"
            android:layout_marginTop="5dp"
            android:layout_marginEnd="5dp"
            android:layout_marginRight="5dp"
            android:layout_marginBottom="5dp"
            android:backgroundTint="@color/white"
            android:text="Ans C"
            android:textColor="@color/black"
            tools:ignore="HardcodedText"
            tools:targetApi="21" />


        <Button
            android:id="@+id/ans_D"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_below="@+id/linearLayout"
            android:layout_alignBottom="@+id/linearLayout"
            android:layout_margin="5dp"
            android:layout_marginStart="5dp"
            android:layout_marginLeft="5dp"
            android:layout_marginTop="213dp"
            android:layout_marginEnd="5dp"
            android:layout_marginRight="5dp"
            android:layout_marginBottom="-261dp"
            android:backgroundTint="@color/white"
            android:baselineAligned="false"
            android:text="Ans D"
            android:textColor="@color/black"
            tools:ignore="HardcodedText,ObsoleteLayoutParam"
            tools:targetApi="21" />

        <Button
            android:id="@+id/submit_btn"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="submit"
            android:layout_marginTop="40dp"/>

    </LinearLayout>

</RelativeLayout>