# Android-Common-Proguard-Rules

ProGuard is most popular optimizer for java bytecode.

List of most common ProGuard rules for android.


## All rules are not tested by me, please test and add rules you know.

// Carouselview

-keep class com.synnapps.carouselview.** { *; }

//jsoup

-keep public class org.jsoup.** {
public *;
}

//Picasso

-dontwarn com.squareup.picasso.**

//Joda

-dontwarn org.joda.convert.FromString

-dontwarn org.joda.convert.ToString

-dontwarn org.joda.convert.**

//Bottombar

-dontwarn com.roughike.bottombar.**
