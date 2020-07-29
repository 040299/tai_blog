---
title: บันทึกสหกิจศึกษา
description: 'ในระยะเวลา 7 เดือน นับตั้งแต่เดือนมกราคม จนถึงเดือนกรกฎาคมนี้ นี่เป็นบันทึกที่จะเล่าเรื่องราวเกี่ยวกับการฝึกงานสหกิจศึกษาตั้งแต่วันแรกจนถึงวันสุดท้าย ที่บริษัท Agentone'
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
