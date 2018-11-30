## wepyRequest说明
wepyRequest文档地址 [wepyReques](https://tencent.github.io/wepy/document.html)

## 调用方式

```
// 引入httpRequest
import { RequestService } from './util/httpRequest'
// 调用方式
RequestService.sendRequest().url('url').header({
  'content-type': 'application/x-www-form-urlencoded; charset=UTF-8'
}).method('POST').data({
}).success(res => {
  console.log(res)
}).send()
```


