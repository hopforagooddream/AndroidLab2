# 主要代码

linearlayout.xml

<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content">


        <TextView
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_margin="5dp"
            android:layout_weight="1.5"
            android:text="One,One" />

        <TextView
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_margin="5dp"
            android:layout_weight="2"
            android:text="One,Two" />

        <TextView
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_margin="5dp"
            android:layout_weight="1.5"
            android:text="One,Three" />

        <TextView
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_margin="5dp"
            android:layout_weight="1.5"
            android:text="One,Four" />
    </LinearLayout>
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content">


        <TextView
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_margin="5dp"
            android:layout_weight="1.5"
            android:text="Two,One" />

        <TextView
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_margin="5dp"
            android:layout_weight="2"
            android:text="Two,Two" />

        <TextView
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_margin="5dp"
            android:layout_weight="1.5"
            android:text="Two,Three" />

        <TextView
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_margin="5dp"
            android:layout_weight="1.5"
            android:text="Two,Four" />
    </LinearLayout>
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content">


        <TextView
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_margin="5dp"
            android:layout_weight="1"
            android:text="Three,One" />

        <TextView
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_margin="5dp"
            android:layout_weight="1"
            android:text="Three,Two" />

        <TextView
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_margin="5dp"
            android:layout_weight="1"
            android:text="Three,Three" />

        <TextView
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_margin="5dp"
            android:layout_weight="1"
            android:text="Three,Four" />
    </LinearLayout>
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content">


        <TextView
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_margin="5dp"
            android:layout_weight="1.6"
            android:text="Four,One" />

        <TextView
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_margin="5dp"
            android:layout_weight="2"
            android:text="Four,Two" />

        <TextView
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_margin="5dp"
            android:layout_weight="1.6"
            android:text="Four,Three" />

        <TextView
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_margin="5dp"
            android:layout_weight="1.6"
            android:text="Four,Four" />
    </LinearLayout>


</LinearLayout>

consrtaintlayout.xml

<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent">


    <TextView
        android:text="RED"
        android:id="@+id/TextView1"
        android:layout_height="wrap_content"
        android:background="#f00"
        android:gravity="center"
        android:textColor="#000"
        android:layout_width="wrap_content"
        android:padding="30sp"></TextView>
    <TextView
        android:text="ORANGE"
        android:layout_height="wrap_content"
        android:background="#ffa500"
        android:gravity="center"
        android:textColor="#000"
        android:id="@+id/TextView2"
        android:layout_width="wrap_content"
        android:layout_centerHorizontal="true"
        android:padding="30sp"></TextView>




    <TextView
        android:text="YELLOW"
        android:layout_height="wrap_content"
        android:background="#ffff00"
        android:gravity="center"
        android:textColor="#000"
        android:id="@+id/TextView3"
        android:layout_width="wrap_content"
        android:layout_alignParentRight="true"
        android:padding="25dp"></TextView>
    <TextView
        android:text="GREEN"
        android:layout_height="wrap_content"
        android:background="#0f0"
        android:gravity="center"
        android:textColor="#000"
        android:id="@+id/TextView4"
        android:layout_width="wrap_content"
        android:layout_toLeftOf="@+id/TextView5"
        android:padding="25dp"
        android:layout_centerVertical="true"></TextView>

    <TextView
        android:text="BLUE"
        android:id="@+id/TextView5"
        android:layout_height="wrap_content"
        android:background="#00f"
        android:gravity="center"
        android:textColor="#fff"
        android:layout_width="wrap_content"
        android:layout_centerInParent="true"
        android:layout_margin="10dp"
        android:padding="25dp"></TextView>

    <TextView
        android:text="INDIGO"
        android:id="@+id/TextView6"
        android:layout_height="wrap_content"
        android:background="#4b0082"
        android:gravity="center"
        android:textColor="#fff"
        android:layout_width="wrap_content"
        android:layout_toRightOf="@id/TextView5"
        android:layout_centerVertical="true"
        android:layout_margin="10dp"
        android:padding="25dp"></TextView>

    <TextView
        android:text="VIOLET"
        android:id="@+id/TextView7"
        android:layout_width="fill_parent"
        android:layout_height="wrap_content"
        android:background="#a573ce"
        android:gravity="center"
        android:textColor="#fff"
        android:padding="25dp"
        android:layout_alignParentBottom="true"
        ></TextView>
</RelativeLayout>

tablelayout.xml
<?xml version="1.0" encoding="utf-8"?>
<TableLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:stretchColumns="1">

    <TableRow>

        <TextView
            android:text="Open..."
            android:layout_column="1"
            android:padding="5dp"/>

        <TextView
            android:text="Ctrl-O"
            android:gravity="right"
            android:padding="5dp"/>
    </TableRow>

    <TableRow>

        <TextView
            android:text="Save..."
            android:layout_column="1"
            android:padding="5dp"/>

        <TextView
            android:text="Ctrl-S"
            android:gravity="right"
            android:padding="5dp"/>
    </TableRow>

    <TableRow>

        <TextView
            android:text="Save As..."
            android:layout_column="1"
            android:padding="5dp"/>

        <TextView
            android:text="Ctrl-Shift-S"
            android:gravity="right"
            android:padding="5dp"/>
    </TableRow>

    <View
        android:layout_height="1dp"
        android:background="#FF909090" />

    <TableRow>

        <TextView
            android:padding="5dp"
            android:text="x" />

        <TextView
            android:text="Import..."
            android:layout_column="1"
            android:padding="5dp"/>

    </TableRow>

    <TableRow>

        <TextView
            android:text="x"
            android:padding="5dp"/>


        <TextView
            android:text="Export..."
            android:layout_column="1"
            android:padding="5dp"/>

        <TextView
            android:text="Ctrl-E"
            android:gravity="right"
            android:padding="5dp" />

    </TableRow>

    <View
        android:layout_height="1dp"
        android:background="#FF909090" />

    <TableRow>

        <TextView
            android:text="Quit"
            android:layout_column="1"
            android:padding="5dp" />
    </TableRow>
</TableLayout>

