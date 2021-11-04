# GofoSpesialStyle
 
<p align="center">
  <img src="https://github.com/gzeinnumer/GofoSpesialStyle/blob/master/preview/preview_2.PNG"/>
</p>

- [themes.xml](https://github.com/gzeinnumer/GofoSpesialStyle/blob/master/app/src/main/res/values/themes.xml)
- [colors.xml](https://github.com/gzeinnumer/GofoSpesialStyle/blob/master/app/src/main/res/values/colors.xml)

```gradle
    //maven { url 'https://jitpack.io' }
    implementation 'com.github.gzeinnumer:SimpleMaterialStyle:2.2.x'
```

- [activty_main.xml](https://github.com/gzeinnumer/GofoSpesialStyle/blob/master/app/src/main/res/layout/activity_main.xml)
```xml
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout ...>

    <LinearLayout ...>

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

    <LinearLayout ...>

        <LinearLayout
            style="@style/MyLinearLayout.White.Rounded">

            <TextView
                style="@style/MyTextContent"
                tools:text="MyTextContent" />

        </LinearLayout>

        <LinearLayout style="@style/MyLinearLayout.White">

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
            style="@style/MyTextEditText.Shape.Disable" />

    </LinearLayout>

    <LinearLayout ...>

        <com.google.android.material.textfield.TextInputLayout
            style="@style/MyTextInputLayoutOutlinedBox.Spesial.V2"
            android:hint="Alamat_toko_man">

            <com.google.android.material.textfield.TextInputEditText
                style="@style/MyTextInputEditText.Spesial.V2"
                android:maxLength="255" />

        </com.google.android.material.textfield.TextInputLayout>

        <com.google.android.material.textfield.TextInputLayout
            style="@style/MyAutoCompleteTextViewFilledBox.V2"
            android:hint="Provinsi_man">

            <AutoCompleteTextView
                style="@style/MyAutoCompleteTextView.V2" />
        </com.google.android.material.textfield.TextInputLayout>
    </LinearLayout>
</LinearLayout>
```

- [themes.xml](https://github.com/gzeinnumer/GofoSpesialStyle/blob/master/app/src/main/res/values/themes.xml)
```xml
    <!--spesial for gofo-->
    <style name="MyAutoCompleteTextViewFilledBox.V2">
        <item name="android:background">@drawable/mygzn_text_input_edittext_3d_bot</item>
        <item name="boxStrokeWidth">0dp</item>
        <item name="boxStrokeWidthFocused">0dp</item>
        <item name="android:textColorHint">@color/mygzn_indicator_text_color</item>
        <item name="hintTextColor">@color/colorAccent</item>
    </style>

    <style name="MyTextInputEditText.Spesial.V2">
        <item name="android:background">@drawable/mygzn_text_input_edittext_3d_bot</item>
        <item name="android:layout_width">match_parent</item>
        <item name="android:layout_height">wrap_content</item>
    </style>
    <!--spesial for gofo-->
```
- res->color
  - [my_mtrl_indicator_text_color.xml](https://github.com/gzeinnumer/GofoSpesialStyle/blob/master/app/src/main/res/color/my_mtrl_indicator_text_color.xml)
  - [mygzn_indicator_text_color.xml](https://github.com/gzeinnumer/GofoSpesialStyle/blob/master/app/src/main/res/color/mygzn_indicator_text_color.xml)

- res->drawable
  - [mygzn_text_input_edittext_3d_bot.xml](https://github.com/gzeinnumer/GofoSpesialStyle/blob/master/app/src/main/res/drawable/mygzn_text_input_edittext_3d_bot.xml)

---

```
Copyright 2021 M. Fadli Zein
```