# My-Theme-Project
&lt;manifest xmlns:android="http://schemas.android.com/apk/res/android" package="theme.abohani.applicationname" android:versionCode="1" android:versionName="1.0" >  &lt;uses-sdk android:minSdkVersion="21" android:targetSdkVersion="22" />  &lt;uses-permission android:name="com.sonymobile.permission.RUNTIME_SK IN" />  &lt;runtime-skin version="1"> &lt;asset path="assetname.zip" target="app.package"> &lt;laf-version-filter from="1" to="1" /> &lt;/asset> &lt;/runtime-skin> &lt;application  android:label="@string/semc_theme_title"  android:icon="@drawable/semc_theme_preview">  &lt;uses-library android:name="com.sonymobile.runtimeskinning" />   &lt;meta-data  android:name="com.sonymobile.runtimeskinning.core. image_wallpaper"  android:resource="@drawable/semc_theme_wallpaper" />  &lt;meta-data  android:name="com.sonymobile.runtimeskinning.core. lockscreen_background"  android:resource="@drawable/semc_theme_lockscreen_wallpaper" />  &lt;uses-library android:name="com.sonymobile.runtimeskinning_2"/>  &lt;meta-data android:name="com.sonymobile.runtimeskinning.core. SKIN_PREVIEW"  android:resource="@array/previews"/>  &lt;/application>  &lt;/manifest>
