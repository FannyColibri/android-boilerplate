Android Boilerplate  
===  

![Hosted on Jitpack.io](https://img.shields.io/jitpack/v/github/quentin7b/android-boilerplate?label=android-boilerplate)    

_TL;DR A set of code bunches I don't want to write anymore !_
 
 ## Elements  
 
 
- [Network](network/README.md) A `NetworkResponse` item for safe network call (no more try catch)  
- [Network-Retrofit-Converter](network_retrofit_converter/README.md) A helper for [Retrofit](https://square.github.io/retrofit/) usage with [Network](network/README.md)  
- [Network-Okhttp3-Interceptor](network_okhttp3_interceptors/README.md) A helper for the interceptors for [okhttp3](https://square.github.io/okhttp/) (like to set headers)
 
- [Recycler_View](recyclerview/README.md) Helpers for [recyclerview](https://square.github.io/okhttp/) (like simple adapter)
 
- [UseCase](usecase/README.md) A simple `UseCase` interface  

  
## Install    

Add it over [jitpack.io](https://jitpack.io/docs/ANDROID/)    
    
In the *project* `build.gradle`    
 ```gradle    
allprojects {    
    repositories {    
        jcenter()    
        // Maybe google()    
        maven { url "https://jitpack.io" }    
    }    
}    
```    
    
In the *module* `build.gradle`    
 ```gradle    
dependencies {    
    implementation 'com.github.quentin7b.android-boilerplate:1.1.0'    
}    
``` 
  
## License    

 Project is under [Apache 2](LICENSE)    
Feel free to improve by opening an issue or a pull request