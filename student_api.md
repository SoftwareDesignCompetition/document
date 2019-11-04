## 注册
Request URL
```javascript
    /v1/student/Register
```
POST
```golang
    signal:88bb8a881a33ba8c790bd2ada982b812d2be16102abd82a0fdfd2418480141d9
    phone:15874732244
    name:465489
    address:65497
    subject:751679
    appkey:s9QY7ZYad6Xm
    timestamp:1570975456
    grade:31234
```
Response
```javascript
   {
        result: 0,
        message: "success",
   }
```

## 增加评价
Request URL
```javascript
    /v1/student/AddEvaluate
```
POST
```golang
    signal:212ffc1a0cf3336e72c8a79066ba04ccbdf6366558c0da9d2bf6396d935a0e1b
    phone:15874732245
    appkey:s9QY7ZYad6Xm
    timestamp:1572877664
    evaluate:True
```
Response
```javascript
    {
        "message": "success",
        "result": 0
    }
```


## 查找
Request URL
```javascript
    /v1/student/GetStudent
```
POST
```golang
    signal:974c47045ab5b3fd141b64e705f61876f214f76a29b670a2664b268846a3647f
    phone:15874732244
    appkey:s9QY7ZYad6Xm
    timestamp:1570975456
```
Response
```javascript
    {
        "data": "{15874732244 465489 751679 65497 31234}",
        "message": "success",
        "result": 0
    }
```
Response
```javascript
    {
        "data": "",
        "message": "success",
        "result": 0
    }
```

## 修改手机号
Request URL
```javascript
    /v1/student/ChangePhone
```
POST
```golang
    signal:d6b3c9800c9d73c5c5fd40255f07c3a9bc7adb2b4dbf0125fb33aecb4d35c2f9
    phone:15874732244
    appkey:s9QY7ZYad6Xm
    timestamp:1570975456
    new_phone:11111111111
```
Response
```javascript
    {
        "message": "success",
        "result": 0
    }
```

## 修改地址
Request URL
```javascript
    /v1/student/ChangeAddress
```
POST
```golang
    signal:cec37d163cb60f2216a6912282fe440a0a01f90215c707eba2d35c6be55b48ee
    phone:15874732245
    appkey:s9QY7ZYad6Xm
    timestamp:1570975456
    address:11111111111
```
Response
```javascript
    {
        "message": "success",
        "result": 0
    }
```

## 修改学科
Request URL
```javascript
    /v1/student/ChangeSubject
```
POST
```golang
    signal:37c6f29855726f62fccce47015f7cb3350cc7ea1108a2206b87f53cb3d89a96f
    phone:15874732245
    appkey:s9QY7ZYad6Xm
    timestamp:1570975456
    subject:11111111111
```
Response
```javascript
    {
        "message": "success",
        "result": 0
    }
```

## 修改年级
Request URL
```javascript
    /v1/student/ChangeGrade
```
POST
```golang
    signal:ca6e49e3333b4969d50827f28b9ab6afce661a9309ba1cca3dc0f8ce0e17fe68
    phone:15874732245
    appkey:s9QY7ZYad6Xm
    timestamp:1570975456
    grade:11111111111
```
Response
```javascript
    {
        "message": "success",
        "result": 0
    }
```

## 修改姓名
Request URL
```javascript
    /v1/student/ChangeName
```
POST
```golang
    signal:31bf092d39be559cd4cc7f42057c59f9e91a2892e70c5bdfb8861acfce376015
    phone:15874732245
    appkey:s9QY7ZYad6Xm
    timestamp:1570975456
    name:11111111111
```
Response
```javascript
    {
        "message": "success",
        "result": 0
    }
```
