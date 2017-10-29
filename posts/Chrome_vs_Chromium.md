# Difference between Chrome and Chromium:

# Automatic Updates

Chrome uses GoogleUpdate on Windows (GoogleSoftwareUpdateAgent and GoogleSoftwareUpdateDaemon on Mac) to automatically update to the latest version. It is not available for Chromium. On some Linux distributions, updates are made available via package repositories. Google Update is also used for other applications like Google Earth.

# Usage tracking and crash reporting

Unlike Chromium, Google has added the crash reporting and send usage statistics options. Chrome sends data to Google servers. It includes general data like information about your device and OS, Chrome settings, visited websites having malware, search queries, etc. This allows Google to suggestions, results, and ads that are relevant to you.

Crash reporting and usage tracking can be disabled from Chrome’s settings.

# Chrome Web Store

On Google Chrome, the functionality to add extensions outside the Chrome Web Store is disabled on all Windows and Mac Channels. However, the extensions can be added via developer mode.

# Media Codec support

Chromium’s HTML5 audio/video codec support is limited to what is available as non-proprietary codecs like Theora, Vorbis, WebM, VP9, etc. In the case of Chrome, it adds support for some non-free stuff like AAC, MP3, and H.264 (now free).

# Non-optional tracking

Google Chrome installer includes a randomly generated token. The token is sent to Google after the installation completes in order to measure the success rate.

Google also uses the RLZ identifier to track a user while Google search and using the address bar. The RLZ identifier stores information – in the form of encoded strings – like the source of chrome download and installation week. It doesn’t include any personal information and it’s used to measure the effectiveness of a promotional campaign. Chrome downloaded from Google’s website doesn’t have the RLZ identifier. The source code to decode the strings is made open by Google.

#Sandbox

Both Chrome and Chromium have Sandbox support. It is always enabled in the case of Google Chrome. For Chromium, some Linux distributions may disable the Sandbox feature.
Adobe Flash Plugin

Although, this difference between Chrome and Chromium doesn’t matter much as Adobe Flash is being phased out for the newer HTML5. Google Chrome supports a Pepper API version of Adobe Flash which gets updated automatically with Chrome. Since it’s not open source, Chromium doesn’t support it out of the box like Google Chrome.

- Author: devaman
- GitHub: [devaman](https://github.com/devaman)