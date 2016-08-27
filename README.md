# Learning RxJava2 for Android by example

RxJava 2.0 has been completely rewritten from scratch on top of the Reactive-Streams specification. The specification itself has evolved out of RxJava 1.x and provides a common baseline for reactive systems and libraries.

Because Reactive-Streams has a different architecture, it mandates changes to some well known RxJava types.


# Migration From RxJava 1 to RxJava2

Using RxJava 2.0 Library in your application

Add this in your build.gradle
```groovy
compile 'io.reactivex.rxjava2:rxjava:2.0.0-RC1'
```
If you are using RxAndroid also, then add the following
```groovy
compile 'io.reactivex.rxjava2:rxandroid:2.0.0-RC1'
```

# RxJava2 Tutorials present in this sample project

Example using CompositeDisposable as CompositeSubscription and Subscription have
been removed.

Example using RxJava2 operators such as:

* MAP
* ZIP
* TAKE
* FLATMAP 
* and much more.

Example using Function as Func1 has been removed.

Example using BiFunction as Func2 has been removed.

# Quick Look on few changes done in RxJava2 over RxJava1

RxJava1 -> RxJava2

* onCompleted -> onComplete - without the trailing d
* Func1 -> Function
* Func2 -> BiFunction
* CompositeSubscription -> CompositeDisposable
* limit operator has been removed - Use take in RxJava2
* merge operator has been added overloads with prefetch 
* mergeDelayError operator has been added overloads with prefetch 
* switchOnNext operator has been added overloads with prefetch 
* switchOnNextDelayError operator has been added overloads with prefetch 
* and much more.

# Highlights of the examples :

* [DisposableExampleActivity](https://github.com/amitshekhariitbhu/RxJava2-Android-Samples/blob/master/app/src/main/java/com/rxjava2/android/samples/DisposableExampleActivity.java) - Using CompositeDisposable
* [MapExampleActivity](https://github.com/amitshekhariitbhu/RxJava2-Android-Samples/blob/master/app/src/main/java/com/rxjava2/android/samples/MapExampleActivity.java) - Using Map Operator
* [ZipExampleActivity](https://github.com/amitshekhariitbhu/RxJava2-Android-Samples/blob/master/app/src/main/java/com/rxjava2/android/samples/ZipExampleActivity.java) - Using Zip Operator
* [TakeExampleActivity](https://github.com/amitshekhariitbhu/RxJava2-Android-Samples/blob/master/app/src/main/java/com/rxjava2/android/samples/TakeExampleActivity.java) - Using Take Operator
* [IntervalExampleActivity](https://github.com/amitshekhariitbhu/RxJava2-Android-Samples/blob/master/app/src/main/java/com/rxjava2/android/samples/IntervalExampleActivity.java) - Using Interval

  

### Show some :heart:
* Be sure to click the :star: button in the upper right of this page. :v:

### Contact - Let's become friend
- [Twitter](https://twitter.com/amitiitbhu)
- [Github](https://github.com/amitshekhariitbhu)
- [Medium](https://medium.com/@amitshekhar)
- [Facebook](https://www.facebook.com/amit.shekhar.iitbhu)

### License
```
   Copyright (C) 2016 Amit Shekhar
   Copyright (C) 2011 Android Open Source Project

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```

### Contributing to RxJava2 Android Samples
Just make pull request. You are in!

 