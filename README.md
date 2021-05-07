# NoNonsense Notes
Link to [Google Play](https://play.google.com/store/apps/details?id=com.nononsenseapps.notepad)

Latest updates posted on [http://www.nononsenseapps.com](http://www.nononsenseapps.com)

<img src="tablet.png" alt="Tablet UI" />

<img src="phone.png" alt="Phone UI" height="720" />

# Getting sync to work
The app should work fine but sync will display an error message. To get it working you will need to put an API key in this file here:
https://github.com/spacecowboy/NotePad/blob/master/NoNonsenseNotes/src/com/nononsenseapps/build/Config.java

<h1>The a href attribute</h1>

<p>An absolute URL: <a href="https://demo.citycarrier.com:5000">W3Schools</a></p>
<p>A relative URL: <a href="https://demo.citycarrier.com:5000/">The a tag</a></p>


You need to replace this line:

```java
public final static String GTASKS_API_KEY = "Put your key here";
```

But first you will of course need to get yourself a key. Follow the instructions on this page:
https://developers.google.com/google-apps/tasks/firstapp

Scroll to the section named __Register your project__.

Once you have put your key in the variable mention above, sync should work fine.

# License
     Copyright (C) 2013 Jonas Kalderstam

     Licensed under the Apache License, Version 2.0 (the "License");
     you may not use this file except in compliance with the License.
     You may obtain a copy of the License at

          http://www.apache.org/licenses/LICENSE-2.0

     Unless required by applicable law or agreed to in writing, software
     distributed under the License is distributed on an "AS IS" BASIS,
     WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
     See the License for the specific language governing permissions and
     limitations under the License.
