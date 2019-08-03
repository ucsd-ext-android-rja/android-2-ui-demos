UI Demos
===================

 ![Image](grid_item_1.png)

 ```xml
 <?xml version="1.0" encoding="utf-8"?>
 <androidx.cardview.widget.CardView
     xmlns:android="http://schemas.android.com/apk/res/android"
     xmlns:app="http://schemas.android.com/apk/res-auto"
     xmlns:tools="http://schemas.android.com/tools"
     android:layout_width="match_parent"
     android:layout_height="wrap_content"
     android:layout_margin="4dp"
     app:cardCornerRadius="24dp"
     app:cardElevation="2dp">

     <ImageView
         android:id="@+id/vh_image"
         android:layout_width="match_parent"
         android:layout_height="match_parent"
         android:scaleType="centerCrop"/>

     <LinearLayout
         android:layout_width="match_parent"
         android:layout_height="wrap_content"
         android:orientation="vertical"
         android:padding="16dp"
         android:layout_gravity="bottom"
         android:background="#8B000000">

         <TextView
             android:id="@+id/vh_title"
             android:layout_width="wrap_content"
             android:layout_height="wrap_content"
             android:textStyle="bold"
             android:textSize="24dp"
             android:layout_marginBottom="4dp"
             android:textColor="@android:color/white"
             tools:text="Title"/>

         <TextView
             android:id="@+id/vh_text"
             android:layout_marginTop="4dp"
             android:layout_width="wrap_content"
             android:layout_height="wrap_content"
             android:textColor="@android:color/white"
             android:textSize="20dp"
             tools:text="text goes here"/>

     </LinearLayout>

 </androidx.cardview.widget.CardView>
 ```



 
