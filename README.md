# iOS-Permissions
Building advanced or intermediate apps sometimes requires accessing what is considered to be private information from the device. We consider information like `user location`,`device microphone`, `device contacts` and so on to be private information, and it is required that the developer asks for permission from the device owner to access such information. This is a list of permissions that the app may require from the user. 

## Add permissions to ``info.list`` file XCode 8.x
![alt text](https://github.com/MMolieleng/iOS-Permissions/blob/master/info_image.png)

### v1.3.0

## NSCameraUsageDescription

```xml
<key>NSCameraUsageDescription</key>
<string>$(PRODUCT_NAME) camera use.</string>
```

### NSContactsUsageDescription
```xml
<key>NSContactsUsageDescription</key>
<string>$(PRODUCT_NAME) contacts use.</string>
```

### NSPhotoLibraryUsageDescription
```xml
	<key>NSPhotoLibraryUsageDescription</key>
	<string>$(PRODUCT_NAME) photos and video use.</string>
```

### NSBluetoothPeripheralUsageDescription
```xml
<key>NSBluetoothPeripheralUsageDescription</key>
<string>$(PRODUCT_NAME) bluetooth use.</string>
```

### NSMicrophoneUsageDescription
```xml
<key>NSMicrophoneUsageDescription</key>
<string>$(PRODUCT_NAME) microphone use.</string>
```

### NSMotionUsageDescription
```xml
<key>NSMotionUsageDescription</key>
<string>$(PRODUCT_NAME) motion use.</string>
```

### NSLocationAlwaysUsageDescription
```xml
<key>NSLocationAlwaysUsageDescription</key>
<string>$(PRODUCT_NAME) location use.</string>
```

### NSLocationUsageDescription
```xml
<key>NSLocationUsageDescription</key>
<string>$(PRODUCT_NAME) location use.</string>
```

### NSLocationWhenInUseUsageDescription
```xml
<key>NSLocationWhenInUseUsageDescription</key>
<string>$(PRODUCT_NAME) location use.</string>
```

### NSRemindersUsageDescription
```xml
<key>NSRemindersUsageDescription</key>
<string>$(PRODUCT_NAME) reminders use.</string>
```

### NSSiriUsageDescription
```xml
<key>NSSiriUsageDescription</key>
<string>$(PRODUCT_NAME) siri use.</string>
```

### NSVideoSubscriberAccountUsageDescription
```xml
<key>NSVideoSubscriberAccountUsageDescription</key>
<string>$(PRODUCT_NAME) video use.</string>
```

### NSSpeechRecognitionUsageDescription
```xml
<key>NSSpeechRecognitionUsageDescription</key>
<string>$(PRODUCT_NAME) speech recognition use.</string>
```

### NSCalendarsUsageDescription
```xml
<key>NSCalendarsUsageDescription</key>
<string>$(PRODUCT_NAME) user your calendar.</string>
```

