# deneme #
## deneme ##

### Step 1. Add the JitPack repository to your build file ###

```gradle
	dependencyResolutionManagement {
		repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
		repositories {
			mavenCentral()
			maven { url 'https://jitpack.io' }
		}
	}

```
 ### Add it in your root build.gradle at the end of repositories: ###

 ```gradle 
 maven(url  = "https://jitpack.io")
 ```

 ### Step 2. Add the dependency ###

 ```gradle

 dependencies {
	        implementation 'com.github.hilalgunes:MyLibrary:1.1'
	}
 
 ```

 ### other ###
 ```gradle
 	 implementation("com.github.hilalgunes:MyLibrary:1.1")

```
