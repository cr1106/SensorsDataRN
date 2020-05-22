# sensorsdata-react-native-test

# 安装 React Native 模块

## npm 安装 sensorsdata-react-native-test 模块

```sh
npm install sensorsdata-react-native-test
```

## `link` sensorsdata-react-native-test 模块(0.60 以下版本)

```sh
react-native link sensorsdata-react-native-test
```
## 配置 package.json
在 package.json 文件增加如下配置:
```sh
"scripts": {
      "postinstall": "node node_modules/sensorsdata-react-native-test/SensorsDataRNHook.js -run"
}
```
## 执行 npm install 命令
```sh
npm install
```