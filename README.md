# Country-code-picker by Arun Android
Pick country code even sim not exist.


## Add it in your root build.gradle at the end of repositories:

```java
allprojects {
		repositories {
			
			maven { url 'https://jitpack.io' }
		}
	}

```


Add a file named `.dependencies` at the root of your project:

```java

	dependencies {
	 	 implementation 'com.github.arundidauli:Country-code-picker:1.0.1'
	}

```



Example 

```java

       	Log.e(TAG, "Country Code : "+ PhoneUtil.GetCountryZipCode(this));
        Log.e(TAG, "Country Code : +"+ PhoneUtil.GetCountryZipCode(this));
	
	output:
	
	E/MainActivity: Country Code : 91
	E/MainActivity: Country Code : +91

```

