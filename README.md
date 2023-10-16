# MA1

activity_main.xml
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#B697EE"
    tools:context=".MainActivity">
    <Button
        android:id="@+id/bper"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Personal"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.207"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.439" />
    <Button
        android:id="@+id/baca"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Academic"
        android:onClick="send"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.699"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.439"
        tools:ignore="HardcodedText,OnClick,UsingOnClickInXml" />
    <ImageView
        android:id="@+id/imageView"
        android:layout_width="96dp"
        android:layout_height="148dp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.104"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.073"
        app:srcCompat="@drawable/sowmya" />
    <TextView
        android:id="@+id/textView"
        android:layout_width="155dp"
        android:layout_height="118dp"
        android:textSize="22dp"
        android:text="Name \n Sem \nDept of MCA \n NMIT"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.742"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.089" />
</androidx.constraintlayout.widget.ConstraintLayout>



academic_layout.xml

<?xml version="1.0" encoding="utf-8"?>
<TableLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#03A9F4"
    tools:context=".academic">
    <TableRow>
        <TextView
            android:textAllCaps="true"
            android:textSize="20dp"
            android:textStyle="bold"
            android:layout_width="match_parent"
            android:layout_height="100dp"
            android:text="Academic"
            />
    </TableRow>
    <TableRow>
        <TextView
            android:textAllCaps="true"
            android:textSize="18dp"
            android:textStyle="bold"
            android:layout_width="wrap_content"
            android:layout_height="100dp"
            android:text="Qualification"
            />
        <TextView
            android:textSize="18dp"
            android:layout_width="wrap_content"
            android:layout_height="100dp"
            android:text="M.C.A"
            />
    </TableRow>
    <TableRow>
        <TextView
            android:textAllCaps="true"
            android:textSize="18dp"
            android:textStyle="bold"
            android:layout_width="wrap_content"
            android:layout_height="100dp"
            android:text="Grade"
            />
        <TextView
            android:textSize="18dp"
            android:layout_width="wrap_content"
            android:layout_height="100dp"
            android:text="Distinction"
            />
    </TableRow>
    <TableRow>
        <TextView
            android:textAllCaps="true"
            android:textSize="18dp"
            android:textStyle="bold"
            android:layout_width="wrap_content"
            android:layout_height="100dp"
            android:text="Technical \nSkills"
            />
        <TextView
            android:textSize="18dp"
            android:layout_width="wrap_content"
            android:layout_height="100dp"
            android:text="Java,Python,C++"
            />
    </TableRow>
    <TableRow>
        <Button
            android:id="@+id/bahome"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Home" />
    </TableRow>
</TableLayout>


activity_personal

<?xml version="1.0" encoding="utf-8"?>
<TableLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#F3C9D8"
    tools:context=".personal">
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="50dp"
        android:layout_gravity="center"
        android:text=" Personal Details"
        android:textAllCaps="true"
        android:textAppearance="@style/TextAppearance.AppCompat.Body1"
        android:textSize="34sp" />
    <TableRow>
        <TextView
            android:layout_width="104dp"
            android:layout_height="51dp"
            android:text="Age"
            android:textAllCaps="true"
            android:textSize="18dp"
            android:textStyle="bold" />
        <TextView
            android:layout_width="165dp"
            android:layout_height="match_parent"
            android:text="30"
            android:textSize="18dp" />
    </TableRow>
    <TableRow>
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="40dp"
            android:text="Nationality"
            android:textAllCaps="true"
            android:textSize="18dp"
            android:textStyle="bold" />
        <TextView
            android:layout_width="157dp"
            android:layout_height="match_parent"
            android:text="Indian"
            android:textSize="18dp" />
    </TableRow>
    <TableRow>
        <TextView
            android:textAllCaps="true"
            android:textSize="18dp"
            android:textStyle="bold"
            android:layout_width="wrap_content"
            android:layout_height="100dp"
            android:text="Languages\n Known"
            />
        <TextView
            android:layout_width="168dp"
            android:layout_height="100dp"
            android:text="English, Hindi"
            android:textSize="18dp" />
    </TableRow>
    <TableRow>
        <TextView
            android:textAllCaps="true"
            android:textSize="18dp"
            android:textStyle="bold"
            android:layout_width="wrap_content"
            android:layout_height="100dp"
            android:text="Hobbies"
            />
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="100dp"
            android:text="Listening Music, Gardening"
            android:textSize="18dp"
            />
    </TableRow>
    <Button
        android:id="@+id/bphome"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="center"
        android:text="Home" />
</TableLayout>

MAINACTIVITY.java

package com.example.a3ui;
import androidx.appcompat.app.AppCompatActivity;
import android.content.Intent;
import android.os.Bundle;
import android.view.View;
import android.widget.Button;
import android.widget.Toast;
public class MainActivity extends AppCompatActivity {
    Button bp, ba;
    Intent personal, academic;
    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        bp = findViewById(R.id.bper);
        ba = findViewById(R.id.baca);
        bp.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                // Toast.makeText(getApplicationContext(),"HelloMCA",Toast.LENGTH_SHORT).show();
                personal = new Intent(getBaseContext(), personal.class);
                startActivity(personal);
            }
        });
        ba.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                academic = new Intent(getBaseContext(), academic.class);
                startActivity(academic);
            }
        });
    }
}


academic.java

package com.example.a3ui;
import androidx.appcompat.app.AppCompatActivity;
import android.content.Intent;
import android.os.Bundle;
import android.view.View;
import android.widget.Button;
public class academic extends AppCompatActivity {
    Button b;
    Intent main;
    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.academic_layout);
        b=(Button)findViewById(R.id.bahome);
        b.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                main = new Intent(getBaseContext(), MainActivity.class);
                startActivity(main);
            }
        });
    }
}


personal.java

package com.example.a3ui;
import androidx.appcompat.app.AppCompatActivity;
import android.content.Intent;
import android.os.Bundle;
import android.view.View;
import android.widget.Button;
public class personal extends AppCompatActivity {
    Button b;
    Intent main;
    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_personal);
        b = (Button) findViewById(R.id.bphome);
        b.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                main = new Intent(getBaseContext(), MainActivity.class);
                startActivity(main);
            }
        });
    }
}
