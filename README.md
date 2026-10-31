# Ex.No:2 To create a HelloWorld Activity using all lifecycles methods to display messages.


## AIM:

To create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio.

## EQUIPMENTS REQUIRED:

Latest Version Android Studio

## ALGORITHM:

Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as HelloWorld and click Next. 

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in activity_main.xml.

Step 6: Display message give in MainActivity file.

Step 7: Save and run the application.

## PROGRAM:
```
Program to print the text “Hello World”.
Developed by: PARTHIPAN M
Registeration Number : 212225040294

package com.example.lifecyclemethods;

import android.os.Bundle;
import android.widget.Toast;

import androidx.activity.EdgeToEdge;
import androidx.appcompat.app.AppCompatActivity;
import androidx.core.graphics.Insets;
import androidx.core.view.ViewCompat;
import androidx.core.view.WindowInsetsCompat;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Toast toast= Toast.makeText(getApplicationContext(), "onCreate Called",Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onStart() {
        super.onStart();
        Toast toast = Toast.makeText(getApplicationContext(), "onStart Called", Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onRestart(){
        super.onRestart();
        Toast toast= Toast.makeText(getApplicationContext(), "onRestart Called",Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onPause(){
        super.onPause();
        Toast toast= Toast.makeText(getApplicationContext(), "onPause Called",Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onStop(){
        super.onStop();
        Toast toast= Toast.makeText(getApplicationContext(), "onStop Called",Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onResume(){
        super.onResume();
        Toast toast= Toast.makeText(getApplicationContext(), "onResume Called",Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onDestroy(){
        super.onDestroy();
        Toast toast= Toast.makeText(getApplicationContext(), "onDestroy Called",Toast.LENGTH_LONG);
        toast.show();
    }
}
```

## OUTPUT

<img width="1920" height="1080" alt="Screenshot (140)" src="https://github.com/user-attachments/assets/6de39443-c1d2-41a4-b36e-d8cdf013bd09" />

<img width="1920" height="1080" alt="Screenshot (141)" src="https://github.com/user-attachments/assets/025d0a2c-5215-4128-9e5b-5b61142a24b0" />

<img width="1920" height="1080" alt="Screenshot (142)" src="https://github.com/user-attachments/assets/8cebf519-ff4c-4b5b-aed2-5b1fbf2125c7" />

<img width="1920" height="1080" alt="Screenshot (143)" src="https://github.com/user-attachments/assets/75c7d365-d916-4f18-9a81-24c631c1b5b7" />

## RESULT
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.
