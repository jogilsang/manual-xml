# manual-xml

### border_bottom.xml
```
<?xml version="1.0" encoding="utf-8"?>
<layer-list xmlns:android="http://schemas.android.com/apk/res/android" >

    <item
        android:bottom="1dp"
        android:left="-2dp"
        android:right="-2dp"
        android:top="-2dp">
        <shape android:shape="rectangle" >
            <stroke
                android:width="1dp"
                android:color="@color/black" />

            <solid android:color="#FFF" />
        </shape>
    </item>

</layer-list>

```

### emptyview

```
       <LinearLayout
                    android:id="@+id/view_empty"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:layout_centerInParent="true"
                    android:orientation="vertical"
                 
                    >

                        <ProgressBar
                            android:layout_width="100dp"
                            android:layout_height="100dp" 
                            android:layout_gravity="center"
                            />

                        <TextView
                            android:layout_width="wrap_content"
                            android:layout_height="wrap_content"
                            android:gravity="center"
                            android:text="로딩중..."
                            android:textSize="@dimen/text_tablet_medium"
                            android:textColor="@color/white" />

                </LinearLayout>
```


### 특수문자
\

### copyright intro 
```
    <RelativeLayout
        android:id="@+id/intro_layout_bottom"
        android:layout_alignParentBottom="true"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginBottom="20dp"
        >

        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginBottom="30dp"
            android:layout_marginLeft="20dp"
            android:layout_marginRight="20dp"
            android:layout_centerInParent="true"
            android:text="@string/intro_copyright"
            android:textColor="@color/white"
            android:textSize="@dimen/text_small"
            android:gravity="center"
            />

    </RelativeLayout>
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
