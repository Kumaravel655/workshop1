
## AIM:
To create a Welcome should be in Center Alignment Font Color: blue, in Android Studio.

## EQUIPMENTS REQUIRED: 
Android Studio(Min. required Artic Fox)

## ALGORITHM: 
Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as “ex.no.2″ and click Next.

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in activity_main.xml.

Step 6: open google page using Implicit Intents and display factorial number using Explicit Intents in MainActivity file.

Step 7: Save and run the application.

## PROGRAM:

### main activity.java
```java
package com.example.myapplication;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;

public class MainActivity extends AppCompatActivity{
    @Override
    protected void onCreate(Bundle savedInstanceState){
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
    }
}
```
### activity_main.xml
```xml
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="welcome"
        android:textAlignment="center"
        android:textColor="#87CEEB"
        android:textSize="48sp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent"></TextView>



</androidx.constraintlayout.widget.ConstraintLayout>
```
### output
![Screenshot (5)](https://user-images.githubusercontent.com/75235334/165219375-081973ed-cf1b-4f3a-b321-988cb546cc9b.png)

### result
hus a Simple Android Application Welcome should be in Center Alignment, Font Color: blue,using Android Studio is developed and executed successfully.
