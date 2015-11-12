# YahooNewsOnboarding
    
## Overview
This demo emulates the cool animations that be seen in the on-boarding screens of [Yahoo News Digest App](https://play.google.com/store/apps/details?id=com.yahoo.mobile.client.android.atom).Yahoo News Digest
is a perfect example of some very good UI and the animations spread throughout the app further supplements this.
Among those, i tried my hands on the on-boarding animtions which looked the coolest.

## Demo
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ![](https://s3-us-west-2.amazonaws.com/helptestbucket/yahoo-news-demo.gif)

[Here](https://www.youtube.com/watch?v=L8U1ykwiHm8) is the video for a more detailed and fine animation.

## How are these animations made?
I wrote a blog about this about the process and techniques i followed to make these animations. [Here](http://rahulrj.github.io/android/yahoo-animation/) is the post.


# By jayden self.
One Activity, three Fragements.  Init these Fragements use getItem.
First Fragment:
  1. Icon setAlpha 0 to be transparent. Then 
getOriginalXValues ???  Record the orignal X values 用来给下次滑动的时候取值调用。
  2. ViewPager 会初始化当前的Page和下一个Page，如果当前的Page已经初始化，就会直接初始化下一个Page.
