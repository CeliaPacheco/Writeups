# Task 1
For task one we are given a .pcapng file. This file contains 
the TerrorTime Android Package(APK). We will need to open the file in
some pcap reader like Wireshark. Once we have the apk file we will need 
to analyze it. Android Studio has an apk analyzer built in.

## Things you'll need
* Wireshark

## Getting Started
Open the *terrortime.pcapgn* file in Wireshark.

**Insert screenshot here**

Looking though the packets we can see there are some "GET" requests, this is 
most likely where the apk file is being downloaded.

We can export this by selecting the export HTTP

**Insert other screenshot here**

Now that we have the apk file, it's a matter of looking at the README and
running `sha256sum` to get the answers.


