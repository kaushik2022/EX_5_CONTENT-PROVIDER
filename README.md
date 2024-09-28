# Ex.No:5 Create Your Own Content Providers to get Contacts details.
## Activitymain.XML:
```
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <Button
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Load Contacts"
        android:layout_centerHorizontal="true"
        android:backgroundTint="#2196F3"
        android:layout_marginTop="50dp"/>


</RelativeLayout>
```
## AndroidMainfest.XML:
```
<?xml version="1.0" encoding="utf-8"?>
<manifest xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    package="com.example.ex5">

    <application
        android:allowBackup="true"
        android:dataExtractionRules="@xml/data_extraction_rules"
        android:fullBackupContent="@xml/backup_rules"
        android:icon="@mipmap/ic_launcher"
        android:label="@string/app_name"
        android:roundIcon="@mipmap/ic_launcher_round"
        android:supportsRtl="true"
        android:theme="@style/Theme.Ex5"
        tools:targetApi="31">
        <activity
            android:name=".MainActivity"
            android:exported="true">
            <intent-filter>
                <action android:name="android.intent.action.MAIN" />

                <category android:name="android.intent.category.LAUNCHER" />
            </intent-filter>
        </activity>
    </application>

</manifest>![Screenshot 2024-09-17 194637](https://github.com/user-attachments/assets/3e17ead9-eb04-43f3-b6e5-10ddd1dae911)


```
## OUTPUT
![image](https://github.com/user-attachments/assets/6cd103f5-da84-44a6-911c-9bff7ce34d97)

![image](https://github.com/user-attachments/assets/7d03651c-9ec9-4a70-9deb-445bd0023a04)


## RESULT
Thus a Simple Android Application create your own content providers to get contacts details using Android Studio is developed and executed successfully.
