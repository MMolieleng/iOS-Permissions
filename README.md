# iOS-Permissions
Building advanced or intermediate apps sometimes requires accessing what is considered to be private information from the device. We consider information like `user location`,`device microphone`, `device contacts` and so on to be private information, and it is required that the developer asks for permission from the device owner to access such information. This is a list of permissions that the app may require from the user. 

![alt text](https://github.com/MMolieleng/iOS-Permissions/blob/master/info_image.png)

## NSCameraUsageDescription

```xml
<key>NSCameraUsageDescription</key>
<string>$(PRODUCT_NAME) camera use.</string>
```
