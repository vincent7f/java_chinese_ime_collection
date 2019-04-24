# java_chinese_ime_collection
Collection of Chinese Input Methods implemented by Java

#### List of Java Chinese IME

##### Java Chinese Ime (hosted on Sourceforge)
  * Support Pinyin, Wubi, CJ(TW).
  * site: https://sourceforge.net/projects/javachinaime/
  * Release with source code download: [javachineseime1.01.src.zip from github.com]( https://github.com/vincent7f/java_chinese_ime_collection/blob/master/javachineseime1.01.src.zip)

##### NeoeIME
  * Support Pinyin, Japanese.
  * site: https://github.com/neoedmund/neoeime

#### Others

#####  How to use the Java IME extension
There are 2 ways to use the Java IME extension
* Copy the IME *.jar file to folder %JAVA_HOME%/jre/lib/ext/
* Use -Djava.ext.dirs to import the IME file:
```
java -Djava.ext.dirs=c:\mylib\ime.jar -jar app.jar
```

##### IME Java App
It's input box for entering Chinese with Java IME.
