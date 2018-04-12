# TestUntity3D
存档，Android调用U3Ddemo

注意事项：</br>
1.新建assert文件夹在app\src\main路径下，放入U3D生成的assert文件夹</br>
2.在app的build.gradle文件中加入如下代码：
```Groovy
sourceSets {
        main {
            jniLibs.srcDirs = ['libs']
        }
    }
```
注意加在
```Groovy
android {
//
}
```
内部  
否则可能会报错"your hardware does not support this application"
