1.引用
  + 对所有引用都是用const,不使用var
  + 如果引用是可变动的，则使用let

2.对象
+ 使用字面量值创建对象

**推荐**
``` javascript
const a = {}
```

**不推荐**
``` javascript
const a = new Object()
```

3.数组
+ 使用字面量值创建数组

**推荐**
``` javascript
const items = []
```

**不推荐**
``` javascript
const items = new Array()
```

4.字符串
+ 字符串统一使用单引号的形式`''`
+ 字符串太长的时候，不要使用字符串连接符换行`\`，而是使用`+`
  
**推荐**
``` javascript
const str = '测试字符串 测试字符串 测试字符串' +
  '测试字符串 测试字符串 测试字符串' +
  '测试字符串 测试字符串'
```

5.遵循 Standard 的规范，不使用分号

6.比较判断
+ 使用精准的类型判断 如 `===`, `!==`
  
