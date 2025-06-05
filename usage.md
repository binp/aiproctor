# Install the Google Meeting Add-On for Interview Proctor.

Click the install after find our add-on in the Google Workspace Marketplace.

The add-on require you to sign in. Currently, we only support Google sign in. Plan to support Micrsoft, Facebook and Zoon soon.

After sign in, you need to select: I'm Interviewer, or I'm Candidate.

## Interviewer Mode

No need to install any more software. There is a button "Collect Data" to click when the candidate sign in.


## Candidate Mode

You are required to install the client software: Interview Proctor (Systray app). There is download page to download the packages for different platforms.

### Install MacOS package:

Because we have not code signing the install pakcage, you need to use the following command to install:

```bash
  sudo installer -pkg InterviewProctor-arm64.pkg -target /
```

or

```bash
  sudo installer -pkg InterviewProctor-amd64.pkg -target /
```

#### Screenshot permission

This is required.

### Windows

After you download, double click the installation package: `InterviewProctor-amd64-setup.exe`.

### Launch Systray App

After the systray app is installed, there is a button to click to "Launch the Systray App". This will sign in the Systray app with the current signed in account.

### Close

You just need to close the Google Meet Add-on. The systray app will close itself if the Google Meet Add-on has stopped.
