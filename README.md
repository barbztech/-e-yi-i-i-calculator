<?xml version="1.0" encoding="utf-8"?>
<ScrollView xmlns:android="http://schemas.android.com/apk/res/android"
    android:id="@+id/main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:fillViewport="true">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical"
        android:padding="16dp">

        <TextView
            android:id="@+id/displayScreen"
            android:layout_width="match_parent"
            android:layout_height="120dp"
            android:background="#F0F0F0"
            android:gravity="bottom|end"
            android:padding="16dp"
            android:text="0"
            android:textColor="#000000"
            android:textSize="36sp"
            android:layout_marginBottom="16dp" />

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="horizontal"
            android:weightSum="3">
            <Button android:id="@+id/btnSin" android:layout_width="0dp" android:layout_height="wrap_content" android:layout_weight="1" android:text="sin" />
            <Button android:id="@+id/btnCos" android:layout_width="0dp" android:layout_height="wrap_content" android:layout_weight="1" android:text="cos" />
            <Button android:id="@+id/btnTan" android:layout_width="0dp" android:layout_height="wrap_content" android:layout_weight="1" android:text="tan" />
        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="horizontal"
            android:weightSum="3">
            <Button android:id="@+id/btnSinh" android:layout_width="0dp" android:layout_height="wrap_content" android:layout_weight="1" android:text="sinh" />
            <Button android:id="@+id/btnCosh" android:layout_width="0dp" android:layout_height="wrap_content" android:layout_weight="1" android:text="cosh" />
            <Button android:id="@+id/btnTanh" android:layout_width="0dp" android:layout_height="wrap_content" android:layout_weight="1" android:text="tanh" />
        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="horizontal"
            android:weightSum="4">
            <Button android:id="@+id/btnClear" android:layout_width="0dp" android:layout_height="wrap_content" android:layout_weight="1" android:text="C" />
            <Button android:id="@+id/btnPerm" android:layout_width="0dp" android:layout_height="wrap_content" android:layout_weight="1" android:text="nPr" />
            <Button android:id="@+id/btnComb" android:layout_width="0dp" android:layout_height="wrap_content" android:layout_weight="1" android:text="nCr" />
            <Button android:id="@+id/btnDiv" android:layout_width="0dp" android:layout_height="wrap_content" android:layout_weight="1" android:text="/" />
        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="horizontal"
            android:weightSum="4">
            <Button android:id="@+id/btn7" android:layout_width="0dp" android:layout_height="wrap_content" android:layout_weight="1" android:text="7" />
            <Button android:id="@+id/btn8" android:layout_width="0dp" android:layout_height="wrap_content" android:layout_weight="1" android:text="8" />
            <Button android:id="@+id/btn9" android:layout_width="0dp" android:layout_height="wrap_content" android:layout_weight="1" android:text="9" />
            <Button android:id="@+id/btnMul" android:layout_width="0dp" android:layout_height="wrap_content" android:layout_weight="1" android:text="*" />
        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="horizontal"
            android:weightSum="4">
            <Button android:id="@+id/btn4" android:layout_width="0dp" android:layout_height="wrap_content" android:layout_weight="1" android:text="4" />
            <Button android:id="@+id/btn5" android:layout_width="0dp" android:layout_height="wrap_content" android:layout_weight="1" android:text="5" />
            <Button android:id="@+id/btn6" android:layout_width="0dp" android:layout_height="wrap_content" android:layout_weight="1" android:text="6" />
            <Button android:id="@+id/btnSub" android:layout_width="0dp" android:layout_height="wrap_content" android:layout_weight="1" android:text="-" />
        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="horizontal"
            android:weightSum="4">
            <Button android:id="@+id/btn1" android:layout_width="0dp" android:layout_height="wrap_content" android:layout_weight="1" android:text="1" />
            <Button android:id="@+id/btn2" android:layout_width="0dp" android:layout_height="wrap_content" android:layout_weight="1" android:text="2" />
            <Button android:id="@+id/btn3" android:layout_width="0dp" android:layout_height="wrap_content" android:layout_weight="1" android:text="3" />
            <Button android:id="@+id/btnAdd" android:layout_width="0dp" android:layout_height="wrap_content" android:layout_weight="1" android:text="+" />
        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:orientation="horizontal"
            android:weightSum="4">
            <Button android:id="@+id/btn0" android:layout_width="0dp" android:layout_height="wrap_content" android:layout_weight="2" android:text="0" />
            <Button android:id="@+id/btnEqual" android:layout_width="0dp" android:layout_height="wrap_content" android:layout_weight="2" android:text="=" />
        </LinearLayout>

    </LinearLayout>
