# manual-xml

### 특수문자
```

 결과값

요소 이름

요소 번호

 &

 &amp;

 &#38;

 <

 &lt;

 &#60;

 >

 &gt;

 &#62;

 '

 &apos;

 &#39;

 "

 &quot;

 &#34; 
```

### border.xml 사각테두리 
```
<?xml version="1.0" encoding="utf-8"?>
<layer-list xmlns:android="http://schemas.android.com/apk/res/android" >
 
    <item
        android:bottom="1dp"
        android:left="1dp"
        android:right="1dp"
        android:top="1dp">
        <shape android:shape="rectangle" >
            <stroke
                android:width="1dp"
                android:color="#dcdcdc" />
 
            <solid android:color="#FFF" />
        </shape>
    </item>
 
</layer-list>


출처: https://wimir-dev.tistory.com/44 [[위미르 개발팀] Android, iOS , Web 제작]
```

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

사이트 :
https://uigradients.com/#Flare  

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
