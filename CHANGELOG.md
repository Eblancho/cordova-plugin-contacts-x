# Changelog

# 3.1.2
- complie -> implementation in build.gradle for compatibiliyy

# 3.1.1
- Merge for edit company data
- Merge from original repo

# 3.0.0
- Merge for adding company data

# 2.0.3
- Rename definition File to work on case-sensitive file system [#11](https://github.com/EinfachHans/cordova-plugin-contacts-x/pull/11)

# 2.0.2
- Fix typo

# 2.0.1
- Fix iOS Phone Type (closes [#9](https://github.com/EinfachHans/cordova-plugin-contacts-x/issues/9))

## 2.0.0
- `rawId` added to contact object on android
- `pick` Method added
- `save` Method added
- `delete` Method added
- `requestWritePermission` Method added (android only)
- `hasPermission` now also return result for `write` permission (same like read on iOS)

### Breaking Changes:

- PhoneNumber's now returns an array of objects (see [here](readme.md#contactxphonenumber))

## 1.1.0
- Fields can be specified (**Breaking**: phoneNumbers disabled by default)
- emails field added 

## 1.0.0
- Initial Release
