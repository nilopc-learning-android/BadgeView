# BadgeView
a BadeView  base on android
<img src="https://github.com/nilopc-learning-android/BadgeView/blob/master/library/gif.png" width="320"/>

include:

      compile 'com.allenliu.badgeview:library:1.0.4'
bind like this:

    BadgeFactory.create(this)
    .setTextColor(Color.White)
    .setWidthAndHeight(25,25)
    .setBadgeBackground(Color.Red)
    .setTextSize(10)
    .setBadgeGravity(Gravity.Right|Gravity.Top)
    .setBadgeCount(20)
    .setShape(BadgeView.SHAPE_CIRCLE)
    .bind(view);
    
There are some other constructer methods and you can be easy to create your own shape :

    BadgeFactory.createDot(this).setBadgeCount(20).bind(imageView);
    BadgeFactory.createCircle(this).setBadgeCount(20).bind(imageView);
    BadgeFactory.createRectangle(this).setBadgeCount(20).bind(imageView);
    BadgeFactory.createOval(this).setBadgeCount(20).bind(imageView);
    BadgeFactory.createSquare(this).setBadgeCount(20).bind(imageView);
    BadgeFactory.createRoundRect(this).setBadgeCount(20).bind(imageView);
unbind view just use `unbind` method.
   
     badgeView.unbind();
     
 if you like,welcome  to star.thank you
