# Teck-News
 Teck News   is an application that fetch news from https://newsapi.org. To run this application you need to Register here and get 32 digit API key.

# Features
 * Show Top-Headlines
* View Single News in detail
* Handled Internet connectivity
 
# Requirement
Android 5.1 or later (Minimum SDK level 22)
Android Studio (to compile and use)
# Library Used
     //Design
    implementation 'com.google.android.material:material:1.0.0'

    //Retrofit
    implementation 'com.squareup.retrofit2:retrofit:2.4.0'
    implementation 'com.squareup.retrofit2:converter-gson:2.2.0'

    //Date/Time
    implementation 'org.ocpsoft.prettytime:prettytime:4.0.1.Final'

    //Picaso for image url
    implementation 'com.squareup.picasso:picasso:2.5.0'
  # String.xml
``` sh
<resources>
   <string name="api_key">Your API key</string>
 </resources>
 ```
# License
* Licensed under the Apache License, Version 2.0 (the "License"); You may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0
