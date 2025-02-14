# Virtual 3D Model Conference Room
https://user-images.githubusercontent.com/14248281/153253874-ff56a275-439c-405d-a5a6-bf9f7817312a.mp4

## Virtual 3D Model Conference Room
### A Virtual 3D Model Conferene Room for making calls and meetings and show 3D models to participators

  - Voice Call (WebRTC)
  - Real time change model inside room for everyone
  - Chat service
  - Room based conferenced like Zoom app
  - Ask permission for accept or reject new members
  - Show presenter's pointer to members

### Demo
Link: https://vebko.org:8080

### Installation

```sh
$ npm install
```

### Running
For running all services:
```sh
$ npm run start
```

If you want to run services separately
For socket server:
```sh
$ npm run server
```
For running client and serv front:
```sh
$ npm run client
```

### Tips
  - WebRTC needs HTTPS and SSL certificate, so you need generate self-signed SSL cert on your local to use call and some other features.
  - You can change socket IP and TURN server IP in index.html file before running.
  

### Issues
Feel free to submit issues and enhancement requests.

### Contributing
Please refer to each project's style and contribution guidelines for submitting patches and additions. In general, we follow the "fork-and-pull" Git workflow.

 1. **Fork** the repo on GitHub
 2. **Clone** the project to your own machine
 4. **Commit** changes to your own branch
 5. **Push** your work back up to your fork
 6. Submit a **Pull request** so that we can review your changes

NOTE: Be sure to merge the latest from "upstream" before making a pull request!


### Credit
Special thanks to
[@kovacsv](https://github.com/kovacsv): For developing this service so we can improve it.


### LICENSE
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
