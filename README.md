# AR-Foundation-Examples

[AR Foundation | 3.0.1 Documentation](https://docs.unity3d.com/Packages/com.unity.xr.arfoundation@3.0/manual/index.html)

**Packages**

To add a package to a Unity project: _Window > Package Manager_; Locate correct version and click Install. Use the latest version of each package. 

| Package           | Version                   |
|-------------------|---------------------------|
| AR Foundation     | 3.0.1 - December 03, 2019 |
| ARKit XR Plugin   | 3.0.1 - December 03, 2019 |

**Build Settings**

Change the following build settings under _Player > Other Settings_. These won't vary much but be sure to give each app a unique bundle identifier string in Unity or in Xcode before building.

| Package               | Version                   |
|-----------------------|---------------------------|
| Bundle Identifier     | studio.cmci.make.ARFoundation |
| Automatically Sign    | Checked |
| Target minimum iOS version   | 13.1 |
| Architecture          | ARM64 |
| Camera Usage Description | Enable to use AR Foundation |






