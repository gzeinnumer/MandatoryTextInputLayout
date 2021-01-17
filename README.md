# MandatoryTextInputLayout

- gradle
```gradle
dependencies {
  ...
  //maven { url 'https://jitpack.io' }
  implementation 'com.github.gzeinnumer:MyLibStyle:0.1.3'
  implementation 'com.google.android.material:material:1.2.1'
}
```

- View
```xml
<com.google.android.material.textfield.TextInputLayout
    android:id="@+id/ed_password_p"
    style="@style/MyTextInputLayoutOutlinedBox.Man">

    <com.google.android.material.textfield.TextInputEditText
        android:id="@+id/ed_password"
        style="@style/MyTextInputEditText"
        android:hint="Password" />

</com.google.android.material.textfield.TextInputLayout>
```

- Style
```xml
<style name="MyTextInputLayoutOutlinedBox.Man">
    <item name="helperText">*Required</item>
    <item name="android:textColorHint">@color/my_mtrl_indicator_text_color</item>
    <item name="boxStrokeColor">@color/my_mtrl_outlined_stroke_color</item>
    <item name="helperTextTextColor">@color/my_mtrl_indicator_helper_text_color</item>
</style>
```

- [res/color/my_mtrl_indicator_text_color](https://github.com/gzeinnumer/MandatoryTextInputLayout/blob/master/app/src/main/res/color/my_mtrl_indicator_helper_text_color.xml)
- [res/color/my_mtrl_outlined_stroke_color](https://github.com/gzeinnumer/MandatoryTextInputLayout/blob/master/app/src/main/res/color/my_mtrl_outlined_stroke_color.xml)
- [res/color/my_mtrl_indicator_helper_text_color](https://github.com/gzeinnumer/MandatoryTextInputLayout/blob/master/app/src/main/res/color/my_mtrl_indicator_helper_text_color.xml)

---

```
Copyright 2021 M. Fadli Zein
```
