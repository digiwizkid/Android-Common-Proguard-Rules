# Android-Common-Proguard-Rules
List of most common ProGuard rules for android

ProGuard is most popular optimizer for java.

## All rules are not tested by me, please add rules you know.

-keep class com.synnapps.carouselview.** { *; }

-keep public class org.jsoup.** {
public *;
}

-dontwarn com.squareup.picasso.**

-dontwarn org.joda.convert.FromString

-dontwarn org.joda.convert.ToString

-dontwarn com.roughike.bottombar.**
