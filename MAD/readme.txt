1. While creating new project:
For all ex - use min SDK 21 Lollipop 5.0 and All updated Meerkat version
For ex 5 - use min SDK 27


2. If java null pointer error in your version:
Go to Gradle Scripts -> build.gradle (Module)

dependencies {    
implementation 'androidx.appcompat:appcompat:1.4.1'    
implementation 'com.google.android.material:material:1.5.0'    
implementation 'androidx.constraintlayout:constraintlayout:2.1.3'    
testImplementation 'junit:junit:4.13.2'    
androidTestImplementation 'androidx.test.ext:junit:1.1.3'    
androidTestImplementation 'androidx.test.espresso:espresso-core:3.4.0'
}

Add this dependencies, change the original

3. For ex 5 (Notification), add the three images(sample_photo.png, bg.png, index.png) into the res -> drawable folder