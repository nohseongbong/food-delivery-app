# food-delivery-app

##typescrip template 세팅

###설치
```c
react-native init FoodDeliveryApp --template react-native-template-typescript
```

###ypescrip template 오류
```c
error This module isn't specified in a package.json file.
```

###ypescrip template 해결방법
#### react-native-cli 의 버전 문제로 인해 삭제후 재설치
```c
npm uninstall -g react-native-cli
```
```c
npm i -g @react-native-community/cli
```
