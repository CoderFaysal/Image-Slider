# Image Slider


### [1] For Gradle.Properties

```
android.enableJetifier=true
```


### [2] For Settings.Gradle(Module)

```
maven { url = uri("https://www.jitpack.io" ) }
```


### [3] For Build.Gradle(Module)

```
implementation ("com.github.denzcoskun:ImageSlideshow:0.1.0")
```

### [4] For XML

```
<com.denzcoskun.imageslider.ImageSlider
        android:id="@+id/image_slider"
        android:layout_width="match_parent"
        android:layout_height="200dp"
        app:iss_auto_cycle="true"
        app:iss_period="1000"
        app:iss_placeholder="@drawable/ic_launcher_foreground"
        app:iss_error_image="@drawable/ic_launcher_background"
        app:iss_delay="0"
        />
```

### [5] For JAVA

```
ImageSlider imageSlider;


        imageSlider =findViewById(R.id.image_slider);

        ArrayList<SlideModel> imageList = new ArrayList<>();


        imageList.add(new SlideModel(R.drawable.ic_launcher_background,null));
        imageList.add(new SlideModel(R.drawable.ic_launcher_background,null));
        imageList.add(new SlideModel(R.drawable.ic_launcher_background,null));

        imageSlider.setImageList(imageList);
        
```



### Official Github Link
```
https://github.com/denzcoskun/ImageSlideshow
```


_© All Right Reserved by Innovative Programmer ❤️_












