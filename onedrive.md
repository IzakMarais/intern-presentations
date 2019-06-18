# Save to OneDrive 
#### Use public APIs to enrich a web app 

---

# Existing App

----

### Paperless patient consent

* New dental patients need to sign consent from
* Replace paper consent form with all digital one
* Small open source web application
* Capture signature on web page
* Generate and serve PDF file

----

<iframe frameborder="0" width="100%" height="500pt" src="http://dinodent-forms.appspot.com/new-patient.html"></iframe>

note: embed page?

----

### Current workflow
* Patients use Android tablet to sign
* Android _Share_ file to Google Drive app
* Practice moved to Microsoft OneDrive
* OneDrive Android app not supported 

---

# Proposed extensions

----

### Save to cloud storage

* Add _Save to OneDrive_ button
* Prompt user to sign in
* Save file to drive
* Optionally allow user to choose location

----

### Tasks
* Research Microsoft OneDrive API documentation
* Authenticate user - get access token
* Store token as cookie in client browser
* Use token to access API functions
* Investigate [OneDrive file picker](https://docs.microsoft.com/en-us/onedrive/developer/controls/file-pickers/js-v72/?view=odsp-graph-online)

---

# Technology exposure

----

NOte:  ### OAuth2
<!-- .slide: data-background="./oauth_l.png" -->
----

### HTTP Cookies

----
<!-- .slide: data-background="./gcp_l.png" -->
NOte:  ### Google Cloud Platform

----

<!-- .slide: data-background="./go_l.png" -->
NOte:  ### Golang

----

### Web presentation 
* Html
* CSS (Bootstrap)
* Javascript

----

### Rest APIs
* Call From client-side code
* Serve custom API on server-side app
* Research public api documentation


----

<!-- .slide: data-background="./OneDrive.png" -->
NOte: ### Microsoft OneDrive API
