## Android工程自动编译

###依赖环境

1. Android SDK  配置环境变量  ANDROID_HOME
2. Gradle  配置环境变量  GRADLE_HOME
3. jarsigner JDK 配置好即可，用于签名apk (jks)


### 配置项

文本配置

| 配置项 | Key | 默认值 | 位置  |
| ---- |:----:|:---:|:-------:|
| 应用标识 | AppId | com.bingoweex.template | ./gradle.properties |
| 版本名称 | AppVersionName | 1.0 | ./gradle.properties |
| 版本编号 | AppVersionName | 1 | ./gradle.properties |
| 应用名称 | app_name | app | ./app/src/main/res/values/strings.xml |



图片配置

