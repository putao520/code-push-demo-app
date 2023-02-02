# 新增例子
```
;增加 app add 规则文件支持
code-push app add CodePushReactNativeDemo-android android react-native "D:\code\anywhere\rn-code-push\code-push-server\testScript\MyGroup.js"

;增加 release-react 区域支持
release-react CodePushReactNativeDemo-android android -d Production -n testRegion

release-react CodePushReactNativeDemo-android android -d Production

;增加 rollback 区域支持
rollback CodePushReactNativeDemo-android Production -r v3 -n testRegion

;增加 patch 规则文件支持
patch CodePushReactNativeDemo-android Production -s "c:\fake\script.js"
```
