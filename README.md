[barter.li Android App][1]
=====================

1. Download our Repo.

2. Add the other projects as library projects.

3. Remember to update your [SDK and build tools][2] to the latest versions. We use the Renderscript Support Library, which always gets updated to the latest build tools.

4. You'll need to register a Google Maps Api Keys v2 and add it in a file called api_keys.xml in the res/values folder. Make sure this is not pushed to your repo and keep it local on your machine.

```xml
<resources>

    <!-- Facebook app Id -->
    <string name="app_id">123456</string>

    <!-- Google API Keys -->
    <string name="ga_tracking_id">GOOGLE_ANALYTICS_TRACKING_ID</string>
    <string name="google_maps_v2_api_key">GOOGLE_MAPS_API_KEY</string>

    <!--Foursquare API Keys -->
    <string name="foursquare_client_id">FOURSQUARE_CLIENT_ID</string>
    <string name="foursquare_client_secret">FOURSQUARE_CLIENT_SECRET</string>

    <!--    CrashLytics ID-->
    <string name="crashlytics_id">YOUR_CRASHLYTICS_ID</string>
</resources>
```

5. You are good to go!

6. If you do something cool, and you think we can benefit, feel free to send a pull request our way. We'll be updating our contribution guidelines very soon once the stable version of the app is out. The current target is April 13, 2014 for the 1st Alpha Release.

## License

Copyright (C) 2014 barter.li

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

[1]: https://play.google.com/store/apps/details?id=li.barter
[2]: https://developer.android.com/tools/sdk/tools-notes.html