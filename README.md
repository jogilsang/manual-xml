# manual-xml

### rounded_border.xml (라운디드 버튼 보더)
```
<selector xmlns:android="http://schemas.android.com/apk/res/android">
    <item>
        <shape android:shape="rectangle">
            <solid android:color="@color/white"/>
            <corners android:radius="10dp" />
            <stroke
                android:width="2dp"
                android:color="@color/colorPrimary"
                />
        </shape>
    </item>
</selector>
```

### gradient_bg1.xml (그레디언트, 그래디언트)
```
<?xml version="1.0" encoding="utf-8"?>
<shape xmlns:android="http://schemas.android.com/apk/res/android"
    android:shape="rectangle"
    >

    <gradient
        android:startColor="#00c6ff"
        android:endColor="#0072ff"
        android:angle="270"
        android:type="linear"
        ></gradient>
</shape>
```
