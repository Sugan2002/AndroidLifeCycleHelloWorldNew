# Ex.No:1 To create a HelloWorld Activity using all lifecycles methods to display messages.


## AIM:

To create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio.

## EQUIPMENTS REQUIRED:

Android Studio(Min. required Artic Fox)

## ALGORITHM:

Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as “ex.no.1″ and click Next. 

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in activity_main.xml.

Step 6: Display message give in MainActivity file.

Step 7: Save and run the application.

## PROGRAM:
```java
/*
Program to print the text “Hello World”.
Developed by:
Registeration Number :
*/

MainActivity.java

package com.example.exnol;
import androidx.appcompat.app.AppCompatActivity; import android.os.Bundle;
import android.widget.Toast;
public class MainActivity extends AppCompatActivity { @Override
protected void onCreate(Bundle savedinstanceState) {
super.onCreate(savedinstanceState); setContentView(R.layout.activity_main);
Toast toast=Toast.mak eText(getApplictaionContext(),"OnCrea te Executed",Toast.LENGTH_LONG); toast.show();
}

protected void onStart(){ super.onStart();
Toast toast=Toast.makeText(getApplicationContext(),"OnStart Executed",Toast.LENGTH_LONG); toast.show();
}

protected void onResume(){ super.onResume();
Toast toast=Toast.makeText(getApplicationContext(),"OnResume Executed",Toast.LENGTH_LONG);
 
toast.show();
}

protected void onPause(){ super.onPause();
Toast toast=Toast.makeText(getApplicationContext(),"OnPause Executed",Toast.LENGTH_LONG); toast.show();
}

protected void onStop(){ super.onStop();
Toast toast=Toast.makeText(getApplicationContext(),"OnStop Executed",Toast.LENGTH_LONG); toast.show();
}

protected void onRestart(){ super.onRestart();
Toast toast=Toast.makeText(getApplicationContext(),"OnRestart Executed",Toast.LENGTH_LONG); toast.show();
}

protected void onDestroy(){ super.onDestroy();
Toast toast=Toast.makeText(getApplicationContext(),"OnDestroy Executed",Toast.LENGTH_LONG); toast.show();
}
}


activity_main.xml

<?xml version=" 1. 0" encoding=" utf-8"? >
<androidx.constraintlayout.widget.Constraintlayout xmlns:android="http://schemas.android.com/apk/res/android" xmlns:app="http://schemas.android.com/apk/res-auto"
xmlns:tools="http://schemas.android.com/tools" android:layout_width="match_parent"
 
android:layout_height="match_parent" tools:context=".MainActivity">

<TextView
android:layout_width="wrap_content" android:layout_height="wrap_content" android:text="Hello World!" app:layout_constraintBottom_toBottomOf="parent" app:layout_constraintLeft_toLeftOf="parent" app:layout_constraintRight_toRightOf="parent" app:layout_constraintTop_toTopOf="parent" />

</androidx.constraintlayout.widget.ConstraintLayout>


```

## OUTPUT

![o1](https://user-images.githubusercontent.com/77089743/165437932-57d9ff7b-69fa-4d71-86eb-1a33334cc26a.png)
![o2](https://user-images.githubusercontent.com/77089743/165438083-c11605f7-c756-436b-b9ae-950468eb63f0.png)
![o3](https://user-images.githubusercontent.com/77089743/165438060-ccd9eed5-504e-4322-8011-e4b9724c4ec8.png)
![o4](https://user-images.githubusercontent.com/77089743/165438050-baec5c6d-6612-45e9-840c-6764915d2dd5.png)
![o5](https://user-images.githubusercontent.com/77089743/165438037-9139fa33-6514-4ce1-81a4-4944ebc6d08c.png)

![o6](https://user-images.githubusercontent.com/77089743/165437990-1e2dc91f-11ea-4e07-a68a-a9f2a6262a1b.png)


![o7](https://user-images.githubusercontent.com/77089743/165438022-6fd35b81-bf1f-4e96-a3c9-66c8c6a05372.png)

## RESULT
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.
