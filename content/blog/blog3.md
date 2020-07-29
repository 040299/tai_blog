---
title: เก็บของใส่กระเป๋า นั่งรถไฟไปเมืองกาญ
description: 'ทริบสั้นๆแบบไปเช้าเย็นกลับ ที่จุดเริ่มต้นมาจากการอยากไปเที่ยว'
---

```js{1,3-5}[server.js]
const http = require('http')
const bodyParser = require('body-parser')

http.createServer((req, res) => {
  bodyParser.parse(req, (error, body) => {
    res.end(body)
  })
}).listen(3000)
```
