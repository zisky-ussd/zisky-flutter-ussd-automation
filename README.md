# zisky-flutter-ussd-automation

An example to automate android ussd session using zisky sdk

[Zisky latest versions](https://pub.dev/packages/zisky/versions)

##  Configs

-Manifest must have the following config

```java
<meta-data
                 android:name="co.zisky.ApiKey"
                 android:value="your_api_key"/>
```
## Initialize Zisky sdk in main method

```java
void main() {
  runApp(MyApp());
  Zisky.init();
}
```