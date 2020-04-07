# AR-Foundation-Examples

[AR Foundation | 3.0.1 Documentation](https://docs.unity3d.com/Packages/com.unity.xr.arfoundation@3.0/manual/index.html)

**Packages**

To add a package to a Unity project: _Window > Package Manager_; Locate correct version and click Install. Use the latest version of each package. 

| Package           | Version                   |
|-------------------|---------------------------|
| AR Foundation     | 3.0.1 - December 03, 2019 |
| ARKit XR Plugin   | 3.0.1 - December 03, 2019 |

**Build Settings**

Switch platform to iOS and proceed. Change the following build settings under _File > Build Settings > Player Settings...Player > Other Settings_. Be sure to give each app a unique bundle identifier string in Unity or in Xcode before building.

| Setting               | Value                   |
|-----------------------|---------------------------|
| Bundle Identifier     | studio.cmci.make.ARFoundation |
| Automatically Sign    | Checked |
| Target minimum iOS version   | 13.1 |
| Architecture          | ARM64 |
| Camera Usage Description | Enable to use AR Foundation |

**Development Environment**

* macOS 10.15 (Catalina)
* Unity 2019.3.X
* Xcode 11.4
* iOS 13.4 (ARKit 3.5)
* A recent iOS device supporting ARKit 3.5



