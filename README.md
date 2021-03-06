Robin
--------------

Standalone bundling of classes from rx.android.schedulers.* which provide Schedulers with Android specific functionality.


Usage
-----

```java
observable.observeOn(AndroidSchedulers.mainThread())
        .subscribeOn(AndroidSchedulers.handlerThread(handler));
```

Download
--------

Download [the latest JAR][2] or grab via Maven:

```xml
<dependency>
  <groupId>com.f2prateek.robin</groupId>
  <artifactId>robin</artifactId>
  <version>1.0.0</version>
</dependency>
```
or Gradle:
```groovy
compile 'com.f2prateek.robin:robin:1.0.0'
```


License
-------

    Copyright 2015 Prateek Srivastava

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.



 [1]: http://github.com/f2prateek/robin
 [2]: http://repository.sonatype.org/service/local/artifact/maven/redirect?r=central-proxy&g=rx.android.schedulers&a=robin&v=LATEST
