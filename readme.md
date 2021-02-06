#### Simple Example android app with accessibility ids
#### Clone repo:
```
git clone https://github.com/vsshk/java-android-app-with-accessibility-ids.git
cd java-android-app-with-accessibility
```
In order to update accessibility id of element:
1. open res/values/strings.xml
2. add new string
```
<string name="testLocatorButton">down</string>
```
3. open res/lauout/activity_main.xml
4. update property with contentDescription
```
android:id="@+id/fab"
android:contentDescription="@string/testLocatorButton"
```
5. You also able to update it from java/
(https://www.deque.com/blog/android-imageviews-accessible-content-descriptions/)
#### You can find apk in the repo
```
testApp.apk
```
* Please give it a star if it helped you.
