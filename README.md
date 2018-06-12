# For iOS

iOS 12 NOOTA: [Download](https://raw.githubusercontent.com/Jwhite077/NOOTA/master/tvOS_12_Beta_Profile.mobileconfig)

**>>iOS 12 Certificates will replace the current iOS 11 Certificates upon release<<**

Just install the profile and hit reboot. Enjoy!

(This profile also blocks ota on 32bit devices on 8.4.1 from the 9.4.5 OTA.)

# For AppleTV

There are two different ways to install the **iOS_11_Beta_Profile.mobileconfig** to block AppleTV updates, you can select one.
## - If you have a macOS
1. Download *Apple Configure 2* from Mac App Store 
2. Download this mobileconfig file: [CLICK HERE](https://raw.githubusercontent.com/Jwhite077/NOOTA/master/iOS_12_Beta_Profile.mobileconfig)
3. Use a USB-C type cable to Connect to your AppleTV
4. Import the file via *Apple Configure 2*

## - If you don't have macOS

1. Open *Settings* in your AppleTV
2. Click "General"
3. Click "Privacy"
4. Slip the Highlight cursor on "share  Apple TV ",**BUT Do Not Touch OR Click**
5. Then Press the "Play and Pause" Button on your Apple TV Remote !
6. Add the file with a URL

# About This File

It was created by Apple Inc. for tvOS beta and iOS beta.

The reason this works is because the profile you just installed actually enrolls your device into another platform's beta program. Your device will now go looking for a compatible version of let's say iOS but your device now can only find tvOS betas, it will assume no update is available and as such, not offer one. It’s a workaround of sorts, and it’s very effective. Should you want to update iOS at a later date, simply removing the profile and restarting should do the trick, so it’s a completely reversible process, too.
