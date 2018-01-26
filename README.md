<img src="https://github.com/utkarshmttl/whatsapp-ImagePicker/blob/master/screen_shot.jpg?raw=true" align="right" width ="180px" height ="auto"/>  

# Whatsapp ImagePicker  
Whatsapp application's inbuilt camera has a full-length band to scroll through user media while displaying a simplistic design for using the camera.  
This repository is an Android library which can directly be imported to your Android projects and enjoy the same goodness of Whatsapp's sleek camera design within your app.  
  
Android app developers can use this repository as a library to integrate such a camera feature within their applications.
  
# Usage

Surround your EditText by a MaterialTextField

```xml
<com.github.utkarshmttl.whatsappIimagePicker.imagepicker
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        app:show_gallery="true"
        />

```
  
# Installation

In your build.gradle file, add this dependency:  
```groovy
compile 'com.github.utkarshmttl:whatsapp-imagepicker:1.0.0'
```
