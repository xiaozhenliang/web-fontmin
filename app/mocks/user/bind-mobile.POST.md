# 修改用户手机

### Api url

/users/:userId/mobile

### request

```js
//<request>
{
  type: 'bind-mobile',
  requestSystem: 'sdkportal',
  ts: '20150723150028',
  accessToken: 'xxxxx',
  mobile: '15723345890',
  captcha: '12324'
  sign: 'xxxx'
}

```

### response with 200

```js
//<response=200>
// 返回200
}

```

### response with 400

```js
//<response=400>
{
  code: 101,
  msg: '签名错误',
  description: '签名不对'
}

```
