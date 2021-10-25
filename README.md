# GofoSpesialStyle
 
<p align="center">
  <img src="https://github.com/gzeinnumer/BaseUtils/blob/master/preview/bg.jpg"/>
</p>

- [themes.xml](https://github.com/gzeinnumer/GofoSpesialStyle/blob/master/app/src/main/res/values/themes.xml)
- [colors.xml](https://github.com/gzeinnumer/GofoSpesialStyle/blob/master/app/src/main/res/values/colors.xml)
- [background_filled_white_radius_v2.xml](https://github.com/gzeinnumer/GofoSpesialStyle/blob/master/app/src/main/res/drawable/background_filled_white_radius_v2.xml)

```gradle

    implementation 'com.github.gzeinnumer:SimpleMaterialStyle:2.2.3'
```

```xml
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout
    tools:context=".MainActivity">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_weight="1"
        android:gravity="center"
        android:orientation="vertical">

        <TextView
            style="@style/MyTextContent.Background.GreenLow"
            android:text="Verified"
            android:textStyle="bold" />

        <TextView
            style="@style/MyTextContent.Background.RedLow"
            android:layout_marginTop="@dimen/def_margin"
            android:text="Denied"
            android:textStyle="bold" />
    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_weight="1"
        android:background="@color/gree_low_gofo"
        android:gravity="center_vertical"
        android:orientation="vertical">

        <LinearLayout
            style="@style/MyLinearLayout.White.Rounded"
            android:layout_marginHorizontal="@dimen/def_margin"
            android:layout_marginBottom="@dimen/def_margin">

            <TextView
                style="@style/MyTextContent"
                tools:text="MyTextContent" />

        </LinearLayout>

        <LinearLayout
            style="@style/MyLinearLayout.White">

            <TextView
                style="@style/MyTextContent"
                tools:text="MyTextContent" />

        </LinearLayout>

        <TextView
            style="@style/MyTextHeader"
            android:layout_marginHorizontal="@dimen/def_margin"
            android:text="Balasan dari Admin" />

        <EditText
            android:id="@+id/ed_response"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginHorizontal="@dimen/def_margin"
            android:layout_marginTop="@dimen/def_margin_half"
            android:background="@drawable/background_filled_white_radius_v2"
            android:gravity="start"
            android:hint="Tulis Disini"
            android:minLines="5"
            android:padding="@dimen/def_margin"
            android:text="dummy_3 dummy_3 dummy_3 dummy_3 "
            android:textAlignment="textStart"
            android:textSize="@dimen/h4" />

    </LinearLayout>
</LinearLayout>
```

---

```
Copyright 2021 M. Fadli Zein
```