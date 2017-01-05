# CleanUI
Clean UI Android theme based on Theme.Holo.NoActionBar

##Usage:<br>
### 1. Add to root build.gradle:
```gradle
allprojects {
    repositories {
        jcenter()
        maven { url 'https://jitpack.io' }
    }
}
```

### 2. Add to app/build.gradle:
```gradle
dependencies {
    compile fileTree(include: ['*.jar'], dir: 'libs')
    compile 'com.github.luna-park:CleanUI:1.2'
}
```
### 3. Add theme to styles.xml
```xml
<resources>

    <!-- Base application theme. -->
    <!--<style name="AppTheme" parent="android:Theme.Light.NoTitleBar" />-->
    <style name="AppTheme" parent="@style/CleanTheme">

    </style>

</resources>
```

