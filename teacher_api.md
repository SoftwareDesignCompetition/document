## 注册
Request URL
```javascript
    /v1/teacher/Register
```
POST
```golang
    signal:11318c8acf9d0aca6b1af696abb9184a6f5f26724153e5a97638b72179b48074
    phone:15874732245
    appkey:s9QY7ZYad6Xm
    timestamp:1572877664
    name:111
    subject:6
    teGrade:8
    address:321
    grade:321
    school:321
    gender:0
    times:321
    salary:200
    major:321
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
    /v1/teacher/AddEvaluate
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
        result: 0,
        message: "success",
   }
```

## 获取教师
Request URL
```javascript
    /v1/teacher/GetTeacher
```
POST
```golang
    signal:118c0f4511486c6a89f68f56061bd4901fe264bbcec98269b5f86ba6a54b418f
    newGrade:2
    appkey:s9QY7ZYad6Xm
    timestamp:1572877664
    newSubject:2
    newMoney:300
    newSex:2
```
Response
```javascript
    {
        "data": [
            {
                "Phone": "15874732245",
                "Name": "111",
                "Gender": "0",
                "School": "321",
                "Grade": "321",
                "Major": "321",
                "Salary": "200",
                "Address": "321",
                "Times": "321",
                "Subject": "6",
                "TeGrade": "8",
                "Status": 0,
                "Good": 0,
                "Own": 1
            }
        ],
        "message": "success",
        "result": 0
    }
```

## 修改手机号
Request URL
```javascript
    /v1/teacher/ChangePhone
```
POST
```golang
    signal:87ded7574200dd1a6dca76e946841ef8b1c70dbb9169d26f272b277ac3528752
    phone:15874732245
    appkey:s9QY7ZYad6Xm
    timestamp:1572877664
    new_phone:15874732244
```
Response
```javascript
   {
        result: 0,
        message: "success",
   }
```

## 修改地址
Request URL
```javascript
    /v1/teacher/ChangeAddress
```
POST
```golang
    signal:bbbc36567db333f10bf95fcefed4de56663745db5696d34fd1dc5f067d692f9b
    phone:15874732244
    appkey:s9QY7ZYad6Xm
    timestamp:1572877664
    address:15874732244
```
Response
```javascript
   {
        result: 0,
        message: "success",
   }
```


## 修改教师自身年级
Request URL
```javascript
    /v1/teacher/ChangeGrade
```
POST
```golang
    signal:8164cc0b4829dec9b6822733f02aaecdeefce9d281dbc09a63fc79bf4f2e7a96
    phone:15874732244
    appkey:s9QY7ZYad6Xm
    timestamp:1572877664
    grade:15874732244
```
Response
```javascript
   {
        result: 0,
        message: "success",
   }
```

## 修改教授年级
Request URL
```javascript
    /v1/teacher/ChangeTeGrade
```
POST
```golang
    signal:f98c93bf4e5f3ef72d7ee80dbfee2a6a562762f5e703462ca12d1b6789ccb49c
    phone:15874732244
    appkey:s9QY7ZYad6Xm
    timestamp:1572877664
    teGrade:15874732244
```
Response
```javascript
   {
        result: 0,
        message: "success",
   }
```

## 修改姓名
Request URL
```javascript
    /v1/teacher/ChangeName
```
POST
```golang
    signal:9db0563e88ab5394aa95a1108c611d38e5ee6dd341b0fb9a0e313f89dddfe939
    phone:15874732244
    appkey:s9QY7ZYad6Xm
    timestamp:1572877664
    name:15874732244
```
Response
```javascript
   {
        result: 0,
        message: "success",
   }
```

## 修改学校
Request URL
```javascript
    /v1/teacher/ChangeSchool
```
POST
```golang
    signal:17fe5b1e54015dbd2ac69e467fcef2a0b684e282bd5ba92fb84d5484fc75f001
    phone:15874732244
    appkey:s9QY7ZYad6Xm
    timestamp:1572877664
    school:15874732244
```
Response
```javascript
   {
        result: 0,
        message: "success",
   }
```

## 修改性别
Request URL
```javascript
    /v1/teacher/ChangeGender
```
POST
```golang
    signal:e02f45350fa9115a603920251d2f5b8c57438c215834ea49f5ef7517af5f5409
    phone:15874732244
    appkey:s9QY7ZYad6Xm
    timestamp:1572877664
    gender:15874732244
```
Response
```javascript
   {
        result: 0,
        message: "success",
   }
```

## 修改空闲时间
Request URL
```javascript
    /v1/teacher/ChangeTimes
```
POST
```golang
    signal:bc27f928339267a00be71b600bfb1098b02a983c36bef423e231711cdb546911
    phone:15874732244
    appkey:s9QY7ZYad6Xm
    timestamp:1572877664
    times:15874732244
```
Response
```javascript
   {
        result: 0,
        message: "success",
   }
```

## 修改期望薪资
Request URL
```javascript
    /v1/teacher/ChangeSalary
```
POST
```golang
    signal:c98aee88c002bd64b14ad174603c0f41ed31ebb5f5f32a2bcd9ddb70529542ce
    phone:15874732244
    appkey:s9QY7ZYad6Xm
    timestamp:1572877664
    salary:15874732244
```
Response
```javascript
   {
        result: 0,
        message: "success",
   }
```


## 修改教师专业
Request URL
```javascript
    /v1/teacher/ChangeMajor
```
POST
```golang
    signal:dba096e9d9186a3a3ba9dfd12e6e5c4632f7110309768c8cd49e51864a792eb7
    phone:15874732244
    appkey:s9QY7ZYad6Xm
    timestamp:1572877664
    major:15874732244
```
Response
```javascript
   {
        result: 0,
        message: "success",
   }
```

## 修改教师状态
Request URL
```javascript
    /v1/teacher/ChangeStatus
```
POST
```golang
    signal:be8b0b0001619c62cab8110a865caf31f0fbf500130ab4d8d968cbb85e9e5a7d
    phone:15874732244
    appkey:s9QY7ZYad6Xm
    timestamp:1572877664
```
Response
```javascript
   {
        result: 0,
        message: "success",
   }
```


## 修改科目
Request URL
```javascript
    /v1/teacher/ChangeSubject
```
POST
```golang
    signal:04fb7a46a35109dde38279db84ab36230adb78a668ad416b5b93592477c451d8
    phone:15874732244
    appkey:s9QY7ZYad6Xm
    timestamp:1572877664
    subject:15874732244
```
Response
```javascript
   {
        result: 0,
        message: "success",
   }
```
