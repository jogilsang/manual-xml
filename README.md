# manual-xml

아이콘 애셋 assets 만들기 :  
http://romannurik.github.io/AndroidAssetStudio/index.html  

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

### 아이콘 metarial degisn icon
사이트 :  
https://material.io/tools/icons/  

### 파워영어 가로로 recyclerview 3개  
```

            <LinearLayout
                android:visibility="gone"
                android:orientation="vertical"
                android:id="@+id/tab3_upper_recycler_2_layout"
                android:layout_width="match_parent"
                android:layout_height="match_parent">

                <RelativeLayout
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content">

                    <TextView
                        android:layout_marginLeft="10dp"
                        android:layout_marginTop="20dp"
                        android:textSize="@dimen/text_large"
                        android:id="@+id/tab3_upper_menu_2_text_2"
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:text="@string/tab_3_upper_2_menu_2"
                        android:textColor="@color/white"
                        android:layout_alignParentTop="true"
                        />

                    <android.support.v7.widget.RecyclerView
                        android:layout_below="@+id/tab3_upper_menu_2_text_2"
                        android:id="@+id/tab3_upper_menu_2_recycler_2"
                        android:layout_width="match_parent"
                        android:layout_height="wrap_content" />

                </RelativeLayout>

            <RelativeLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content">

                <TextView
                    android:layout_marginLeft="10dp"
                    android:layout_marginTop="20dp"
                    android:textSize="@dimen/text_large"
                    android:id="@+id/tab3_upper_menu_2_text_3"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:text="@string/tab_3_upper_2_menu_3"
                    android:textColor="@color/white"
                    android:layout_alignParentTop="true"
                    />

                <android.support.v7.widget.RecyclerView
                    android:id="@+id/tab3_upper_menu_2_recycler_3"
                    android:layout_below="@+id/tab3_upper_menu_2_text_3"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content" />

            </RelativeLayout>

            <RelativeLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"

                >

                <TextView
                    android:layout_marginLeft="10dp"
                    android:layout_marginTop="20dp"
                    android:textSize="@dimen/text_large"
                    android:id="@+id/tab3_upper_menu_2_text_4"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:text="@string/tab_3_upper_2_menu_4"
                    android:textColor="@color/white"
                    android:layout_alignParentTop="true"
                    />

                <android.support.v7.widget.RecyclerView
                    android:id="@+id/tab3_upper_menu_2_recycler_4"
                    android:layout_below="@+id/tab3_upper_menu_2_text_4"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content" />

            </RelativeLayout>


            </LinearLayout>
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
