# android-cocos-headers
Cocos headers for Android GD Modding. Taken from iAndyHD3's [repo](https://github.com/iAndyHD3/gd-mod-example-android) and made a separate repo for convenience. The original headers seem to belong to [IAD](https://github.com/ItalianApkDownloader) but I'm not sure.

## Usage
1. It's recommended to add this as a submodule like this:<br>`git submodule add https://github.com/JaanDev/android-cocos-headers.git libs/cocos2d`
3. Then in your `CMakeLists.txt`:<br>`add_subdirectory(libs/cocos2d)`<br>and<br>`target_link_libraries(your_project_name cocos2d)`
4. Copy the game's `.so` file (`libcocos2dcpp.so`) to the parent directory of where you cloned the submodule (for example, if you cloned to `libs/cocos2d` as in my example, you should copy the `libcocos2dcpp.so` to the `libs` directory). This is done to not to distribute the game's binary.

## Contacts
My Discord: jaan2897
