# Firebase v4 Authentication User Interface + Google Material Components

##### [LIVE DEMO](https://abracadabra-8012b.firebaseapp.com/)

### Synopsis

A [Firebase Authentication (v4)](https://firebase.google.com/products/auth/) with [Material Components](//material.io/components) user interface, UI. Sign in with a token from your favorite social media platform or via email. 

<img src="https://github.com/rhroyston/rhroyston.github.io/blob/master/firebase-v4-auth-screenshots.png" alt="screenshot" style="max-width:80%">

#### Features

 - Single page app implementation
 - Single HTML file
   - Paste in your firebase project parameters and go
 - Account changes require email verification
 - Mobile First User Interface
   - Material Components UI
   - photoURL resolution upgrades
   - Account deletion safeguard switch
   - Simple standard CSS flexbox layout
   - X-axis scroll suppression on phone viewports
 - [Gravatar](//gravatar.com) fallback for all accounts with an email address
 - Vanilla, easy-to-read JavaScript / ECMA Script
   - Promise based functions aligned with Firebase documentation
   - Plain id based event listeners

### Installation

The public folder contains the single index.html file. 
From the Firebase console, create a Firebase project. 
Under the Overview section click on "Add Firebase to your web app".
From the Firebase console, go to Authentication > Templates tab and remove `/__/auth/action` from the Action URL - we don't need it. 
Keep the query parameters in the Action URL (the text after the ?).

### Contribute

If you found a bug, have any questions or want to contribute or collaborate please let me know, [ron@rack.pub](mailto:ron@rack.pub).

### License

Copyright 2017 Ron Royston, [https://rack.pub](https://rack.pub) All rights reserved.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

  https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License