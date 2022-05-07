# food-delivery-app
[예제](https://github.com/ZeroCho/food-delivery-app/blob/master/README.md)



## typescript template



### 설치
```c
react-native init FoodDeliveryApp --template react-native-template-typescript
```




### typescript template 오류
```c
error This module isn't specified in a package.json file.
```




### typescript template 해결방법
react-native-cli 의 버전 문제로 인해 삭제후 재설치
```c
npm uninstall -g react-native-cli
```
```c
npm i -g @react-native-community/cli
```





## react-native Flipper
React Native0.62 이후 버전에서는 설치만으로 사용가능
openssl 미설치시 설치 후 진행
[Flipper 설치 사이트...](https://fbflipper.com/)





## App 이름 변경
경로 : FoodDeliveryApp\app.json (현재 세팅상 한글로 변경시 App 꺼짐 현상발생)
```c
{
  "name": "FoodDeliveryApp",
  "displayName": "BongbongRiders"
}
```

경로 : FoodDeliveryApp\android\app\src\main\res\values\strings.xml
```c
<resources>
    <string name="app_name">BongbongRiders</string>
</resources>

```

경로 : FoodDeliveryApp\ios\FoodDeliveryApp\Info.plist
```c
	<key>CFBundleDevelopmentRegion</key>
	<string>en</string>
	<key>CFBundleDisplayName</key>
	<string>BongbongRiders</string>

```

