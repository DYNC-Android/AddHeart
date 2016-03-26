# AddHeart
点赞爱心往上漂浮效果


How to use?

So easy~

Imported the File into Your Project~

then 
  XML:
  
  
   <com.dync.addheart.Heart
        android:id="@+id/heart"
        android:layout_width="match_parent"
        android:layout_height="match_parent">
    </com.dync.addheart.Heart>
    
    
  Activity:
  
    Heart heart= (Heart) findViewById(R.id.heart);
        findViewById(R.id.btn).setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                heart.addHeart();
            }
        });

