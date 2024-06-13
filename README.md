# Android-program-code
My code documents

package com.example.test

import android.os.Bundle
import androidx.appcompat.app.AppCompatActivity
import com.example.testbutton.databinding.ActivityMainBinding

class MainActivity : AppCompatActivity() {

    private lateinit var binding: ActivityMainBinding

    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        binding = ActivityMainBinding.inflate(layoutInflater)
        setContentView(binding.root)

The code on this page omits the above code.
