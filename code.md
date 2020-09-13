# Android-App
# Simple Calculator
# activity_main.xml

<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/relative1"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <EditText
        android:id="@+id/edt1"
        android:layout_width="match_parent"
        android:layout_height="wrap_content" />


    <Button
        android:id="@+id/button1"
        style="?android:attr/buttonStyleSmall"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignEnd="@+id/button4"
        android:layout_alignRight="@+id/button4"
        android:layout_below="@+id/edt1"
        android:layout_marginTop="94dp"
        android:text="1" />

    <Button
        android:id="@+id/button2"
        style="?android:attr/buttonStyleSmall"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignTop="@+id/button1"
        android:layout_toLeftOf="@+id/button3"
        android:layout_toStartOf="@+id/button3"
        android:text="2" />

    <Button
        android:id="@+id/button3"
        style="?android:attr/buttonStyleSmall"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignTop="@+id/button2"
        android:layout_centerHorizontal="true"
        android:text="3" />

    <Button
        android:id="@+id/button4"
        style="?android:attr/buttonStyleSmall"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@+id/button1"
        android:layout_toLeftOf="@+id/button2"
        android:text="4" />

    <Button
        android:id="@+id/button5"
        style="?android:attr/buttonStyleSmall"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignBottom="@+id/button4"
        android:layout_alignLeft="@+id/button2"
        android:layout_alignStart="@+id/button2"
        android:text="5" />

    <Button
        android:id="@+id/button6"
        style="?android:attr/buttonStyleSmall"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignLeft="@+id/button3"
        android:layout_alignStart="@+id/button3"
        android:layout_below="@+id/button3"
        android:text="6" />

    <Button
        android:id="@+id/button7"
        style="?android:attr/buttonStyleSmall"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@+id/button4"
        android:layout_toLeftOf="@+id/button2"
        android:text="7" />

    <Button
        android:id="@+id/button8"
        style="?android:attr/buttonStyleSmall"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignLeft="@+id/button5"
        android:layout_alignStart="@+id/button5"
        android:layout_below="@+id/button5"
        android:text="8" />

    <Button
        android:id="@+id/button9"
        style="?android:attr/buttonStyleSmall"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignLeft="@+id/button6"
        android:layout_alignStart="@+id/button6"
        android:layout_below="@+id/button6"
        android:text="9" />

    <Button
        android:id="@+id/buttonadd"
        style="?android:attr/buttonStyleSmall"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignEnd="@+id/edt1"
        android:layout_alignRight="@+id/edt1"
        android:layout_alignTop="@+id/button3"
        android:layout_marginLeft="46dp"
        android:layout_marginStart="46dp"
        android:layout_toRightOf="@+id/button3"
        android:text="+" />

    <Button
        android:id="@+id/buttonsub"
        style="?android:attr/buttonStyleSmall"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignEnd="@+id/buttonadd"
        android:layout_alignLeft="@+id/buttonadd"
        android:layout_alignRight="@+id/buttonadd"
        android:layout_alignStart="@+id/buttonadd"
        android:layout_below="@+id/buttonadd"
        android:text="-" />

    <Button
        android:id="@+id/buttonmul"
        style="?android:attr/buttonStyleSmall"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignLeft="@+id/buttonsub"
        android:layout_alignParentEnd="true"
        android:layout_alignParentRight="true"
        android:layout_alignStart="@+id/buttonsub"
        android:layout_below="@+id/buttonsub"
        android:text="*" />

    <Button
        android:id="@+id/button10"
        style="?android:attr/buttonStyleSmall"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@+id/button7"
        android:layout_toLeftOf="@+id/button2"
        android:text="." />

    <Button
        android:id="@+id/button0"
        style="?android:attr/buttonStyleSmall"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignLeft="@+id/button8"
        android:layout_alignStart="@+id/button8"
        android:layout_below="@+id/button8"
        android:text="0" />

    <Button
        android:id="@+id/buttonC"
        style="?android:attr/buttonStyleSmall"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignLeft="@+id/button9"
        android:layout_alignStart="@+id/button9"
        android:layout_below="@+id/button9"
        android:text="C" />

    <Button
        android:id="@+id/buttondiv"
        style="?android:attr/buttonStyleSmall"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignEnd="@+id/buttonmul"
        android:layout_alignLeft="@+id/buttonmul"
        android:layout_alignRight="@+id/buttonmul"
        android:layout_alignStart="@+id/buttonmul"
        android:layout_below="@+id/buttonmul"
        android:text="/" />

    <Button
        android:id="@+id/buttoneql"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignEnd="@+id/buttondiv"
        android:layout_alignLeft="@+id/button10"
        android:layout_alignRight="@+id/buttondiv"
        android:layout_alignStart="@+id/button10"
        android:layout_below="@+id/button0"
        android:layout_marginTop="37dp"
        android:text="=" />


# maimActivity.java File
package com.example.mycalculator;

import android.os.Bundle;
import android.view.View;
import android.widget.Button;
import android.widget.EditText;

import androidx.appcompat.app.AppCompatActivity;

    public class MainActivity extends AppCompatActivity {

        Button button0, button1, button2, button3, button4, button5, button6,
                button7, button8, button9, buttonAdd, buttonSub, buttonDivision,
                buttonMul, button10, buttonC, buttonEqual;
        EditText crunchifyEditText;

        float mValueOne, mValueTwo;

        boolean crunchifyAddition, mSubtract, crunchifyMultiplication, crunchifyDivision;

        @Override
        protected void onCreate(Bundle savedInstanceState) {
            super.onCreate(savedInstanceState);
            setContentView(R.layout.activity_main);

            button0 = (Button) findViewById(R.id.button0);
            button1 = (Button) findViewById(R.id.button1);
            button2 = (Button) findViewById(R.id.button2);
            button3 = (Button) findViewById(R.id.button3);
            button4 = (Button) findViewById(R.id.button4);
            button5 = (Button) findViewById(R.id.button5);
            button6 = (Button) findViewById(R.id.button6);
            button7 = (Button) findViewById(R.id.button7);
            button8 = (Button) findViewById(R.id.button8);
            button9 = (Button) findViewById(R.id.button9);
            button10 = (Button) findViewById(R.id.button10);
            buttonAdd = (Button) findViewById(R.id.buttonadd);
            buttonSub = (Button) findViewById(R.id.buttonsub);
            buttonMul = (Button) findViewById(R.id.buttonmul);
            buttonDivision = (Button) findViewById(R.id.buttondiv);
            buttonC = (Button) findViewById(R.id.buttonC);
            buttonEqual = (Button) findViewById(R.id.buttoneql);
            crunchifyEditText = (EditText) findViewById(R.id.edt1);


            button1.setOnClickListener(new View.OnClickListener() {
                @Override
                public void onClick(View v) {
                    crunchifyEditText.setText(crunchifyEditText.getText() + "1");
                }
            });

            button2.setOnClickListener(new View.OnClickListener() {
                @Override
                public void onClick(View v) {
                    crunchifyEditText.setText(crunchifyEditText.getText() + "2");
                }
            });

            button3.setOnClickListener(new View.OnClickListener() {
                @Override
                public void onClick(View v) {
                    crunchifyEditText.setText(crunchifyEditText.getText() + "3");
                }
            });

            button4.setOnClickListener(new View.OnClickListener() {
                @Override
                public void onClick(View v) {
                    crunchifyEditText.setText(crunchifyEditText.getText() + "4");
                }
            });

            button5.setOnClickListener(new View.OnClickListener() {
                @Override
                public void onClick(View v) {
                    crunchifyEditText.setText(crunchifyEditText.getText() + "5");
                }
            });

            button6.setOnClickListener(new View.OnClickListener() {
                @Override
                public void onClick(View v) {
                    crunchifyEditText.setText(crunchifyEditText.getText() + "6");
                }
            });

            button7.setOnClickListener(new View.OnClickListener() {
                @Override
                public void onClick(View v) {
                    crunchifyEditText.setText(crunchifyEditText.getText() + "7");
                }
            });

            button8.setOnClickListener(new View.OnClickListener() {
                @Override
                public void onClick(View v) {
                    crunchifyEditText.setText(crunchifyEditText.getText() + "8");
                }
            });

            button9.setOnClickListener(new View.OnClickListener() {
                @Override
                public void onClick(View v) {
                    crunchifyEditText.setText(crunchifyEditText.getText() + "9");
                }
            });

            button0.setOnClickListener(new View.OnClickListener() {
                @Override
                public void onClick(View v) {
                    crunchifyEditText.setText(crunchifyEditText.getText() + "0");
                }
            });

            buttonAdd.setOnClickListener(new View.OnClickListener() {
                @Override
                public void onClick(View v) {

                    if (crunchifyEditText == null) {
                        crunchifyEditText.setText("");
                    } else {
                        mValueOne = Float.parseFloat(crunchifyEditText.getText() + "");
                        crunchifyAddition = true;
                        crunchifyEditText.setText(null);
                    }
                }
            });

            buttonSub.setOnClickListener(new View.OnClickListener() {
                @Override
                public void onClick(View v) {
                    mValueOne = Float.parseFloat(crunchifyEditText.getText() + "");
                    mSubtract = true;
                    crunchifyEditText.setText(null);
                }
            });

            buttonMul.setOnClickListener(new View.OnClickListener() {
                @Override
                public void onClick(View v) {
                    mValueOne = Float.parseFloat(crunchifyEditText.getText() + "");
                    crunchifyMultiplication = true;
                    crunchifyEditText.setText(null);
                }
            });

            buttonDivision.setOnClickListener(new View.OnClickListener() {
                @Override
                public void onClick(View v) {
                    mValueOne = Float.parseFloat(crunchifyEditText.getText() + "");
                    crunchifyDivision = true;
                    crunchifyEditText.setText(null);
                }
            });

            buttonEqual.setOnClickListener(new View.OnClickListener() {
                @Override
                public void onClick(View v) {
                    mValueTwo = Float.parseFloat(crunchifyEditText.getText() + "");

                    if (crunchifyAddition == true) {
                        crunchifyEditText.setText(mValueOne + mValueTwo + "");
                        crunchifyAddition = false;
                    }

                    if (mSubtract == true) {
                        crunchifyEditText.setText(mValueOne - mValueTwo + "");
                        mSubtract = false;
                    }

                    if (crunchifyMultiplication == true) {
                        crunchifyEditText.setText(mValueOne * mValueTwo + "");
                        crunchifyMultiplication = false;
                    }

                    if (crunchifyDivision == true) {
                        crunchifyEditText.setText(mValueOne / mValueTwo + "");
                        crunchifyDivision = false;
                    }
                }
            });

            buttonC.setOnClickListener(new View.OnClickListener() {
                @Override
                public void onClick(View v) {
                    crunchifyEditText.setText("");
                }
            });

            button10.setOnClickListener(new View.OnClickListener() {
                @Override
                public void onClick(View v) {
                    crunchifyEditText.setText(crunchifyEditText.getText() + ".");
                }
            });
        }
