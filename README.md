# Notes

## Useful Links

### Soong Build System
[Soong Modules Reference](https://ci.android.com/builds/submitted/11337780/linux/latest/view/soong_build.html)

### Privileged Permissions
[Privileged Permission Allowlist](https://source.android.com/docs/core/permissions/perms-allowlist)

### PermissionLog injection GrapheneOS
[Settings Log](https://github.com/GrapheneOS/platform_packages_modules_Permission/blob/14/PermissionController/src/com/android/permissioncontroller/permission/ui/model/AppPermissionViewModel.kt#L1142)  
[Popup Log](https://github.com/GrapheneOS/platform_packages_modules_Permission/blob/14/PermissionController/src/com/android/permissioncontroller/permission/ui/model/GrantPermissionsViewModel.kt#L1240)

### Android Code Search
[Android Code Search](https://cs.android.com)

### Disable Factory Reset
[Disable wipe data factory reset](https://stackoverflow.com/questions/46071323/disable-wipe-data-factory-reset)

## Concept

### Provider
[Service vs. Provider](https://stackoverflow.com/questions/3523453/difference-between-android-service-and-content-provider) -> Provider

#### Content Provider
[Overview](https://developer.android.com/guide/topics/providers/content-providers)  
[Reference](https://developer.android.com/reference/android/content/ContentProvider)  
[Manifest](https://developer.android.com/guide/topics/manifest/provider-element)

#### Example Providers
[CallLogProvider](https://android.googlesource.com/platform/packages/providers/CallLogProvider)  

### Database

#### Room
[Overview](https://developer.android.com/training/data-storage/room)  
[Reference](https://developer.android.com/reference/androidx/room/package-summary) -> Unable to change storage location

-> Room builder needs to be touched.

#### SQLite
TODO

#### OpenFile
TODO

#### ...
TODO
