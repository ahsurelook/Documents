
Import library
---------------------------------------
1- download JAR
2- File > New > New Module > JAR >Find it & add
3- Right CLick -
Open your project in Android Studio
Download the library (using Git, or a zip archive to unzip)
Go to File > Import Module and import the library as a module
Right-click your app in project view and select "Open Module Settings"
Click the "Dependencies" tab and then the '+' button
Select "Module Dependency"
Select "Freemium Library" (not Freemium Library Project)
Modify your App Activities to extend AdsFragmentActivity instead of Activity.
Modify the library if you want to use it with ActionBarCompat
