ok my resolve on this error at layout activity_main_xml

<?xml version="1.0" encoding="utf-8"?>
<ScrollView xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical">

        <FrameLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content">

            <ImageView
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:adjustViewBounds="true"
                android:scaleType="fitXY"
                android:src="@drawable/pixel_google" />

            <TextView
                style="@style/TextContent.BodyMedium.White.MarginAll"
                android:layout_gravity="bottom"
                android:background="#4D000000"
                android:drawablePadding="4dp"
                android:gravity="center_vertical"
                android:padding="8dp"
                android:text="@string/dummy_photos"
                android:drawableStart="@drawable/ic_collections_white_18dp" />
        </FrameLayout>

        <TextView
            style="@style/TextContent.HeadlineMedium.Bold"
            android:layout_marginTop="16dp"
            android:layout_marginBottom="8dp"
            android:text="@string/dummy_value" />

        <TextView
            style="@style/TextContent.TitleMedium.Bold.MarginLeftRight"
            android:layout_marginBottom="16dp"
            android:text="@string/title"
            android:textSize="18sp"/>

        <TextView
            style="@style/TextContent.BodyMedium.Gray.MarginLeftRight"
            android:layout_marginBottom="16dp"
            android:lineSpacingMultiplier="1"
            android:text="@string/content_text" />

        <TextView
            style="@style/TextContent.TitleMedium.Bold.MarginLeftRight"
            android:layout_marginBottom="8dp"
            android:text="@string/specification" />

        <TableLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginLeft="16dp"
            android:layout_marginRight="16dp"
            android:layout_marginBottom="16dp">

            <TableRow
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginBottom="8dp">

                <TextView
                    style="@style/TextContent.BodyMedium.Bold"
                    android:layout_marginEnd="16dp"
                    android:text="@string/display" />

                <TextView
                    style="@style/TextContent.BodyMedium.Gray"
                    android:layout_weight="1"
                    android:text="@string/content_specs_display" />
            </TableRow>

            <TableRow
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginBottom="8dp">

                <TextView
                    style="@style/TextContent.BodyMedium.Bold"
                    android:layout_marginEnd="16dp"
                    android:text="@string/size" />

                <TextView
                    style="@style/TextContent.BodyMedium.Gray"
                    android:layout_weight="1"
                    android:text="@string/content_specs_size" />
            </TableRow>

            <TableRow
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginBottom="8dp">

                <TextView
                    style="@style/TextContent.BodyMedium.Bold"
                    android:layout_marginEnd="16dp"
                    android:text="@string/battery" />

                <TextView
                    style="@style/TextContent.BodyMedium.Gray"
                    android:layout_weight="1"
                    android:text="@string/content_specs_battery" />
            </TableRow>
        </TableLayout>

        <TextView
            style="@style/TextContent.TitleMedium.Bold.MarginLeftRight"
            android:layout_marginBottom="8dp"
            android:text="@string/seller" />

        <RelativeLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginLeft="16dp"
            android:layout_marginRight="16dp"
            android:layout_marginBottom="16dp">

            <ImageView
                android:id="@+id/profile_image"
                android:layout_width="56dp"
                android:layout_height="56dp"
                android:layout_centerVertical="true"
                android:layout_marginEnd="16dp"
                android:src="@drawable/photo_2" />

            <TextView
                style="@style/TextContent.BodyMedium.Gray"
                android:layout_centerVertical="true"
                android:layout_toEndOf="@+id/profile_image"
                android:text="@string/my_name" />
        </RelativeLayout>

        <Button
            android:text="@string/buy"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginLeft="16dp"
            android:layout_marginRight="16dp"
            android:layout_marginBottom="16dp" />
    </LinearLayout>
</ScrollView>

