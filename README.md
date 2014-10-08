gradle-plugin-mvn-push
======================

Equivalent to Chris Banes' [gradle-mvn-push](https://github.com/chrisbanes/gradle-mvn-push)
script but for Gradle custom plugins written in Groovy.

[Instructions](https://github.com/chrisbanes/gradle-mvn-push/blob/master/README.md)
are pretty much the same than `gradle-mvn-push`, the only difference being *step 5*,
in which you should [download](https://raw.github.com/lucasr/gradle-plugin-mvn-push/master/gradle-plugin-mvn-push.gradle) the `gradle-plugin-mvn-push` script into your source tree and add the following to the end of
the `build.gradle` that you wish to upload.

```groovy
apply from: 'gradle-plugin-mvn-push.gradle'
```

## License

    Copyright (C) 2014 Lucas Rocha

    This code is largely based on Chris Banes' gradle-mvn-push script.

    Copyright (C) 2013 Chris Banes

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
