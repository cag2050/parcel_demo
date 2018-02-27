* 英文文档：https://parceljs.org/
* 中文文档：https://www.parceljs.cn/

* ParcelJS 本身是 0 配置的，但 HTML、JS 和 CSS 分别是通过 posthtml、babel 和 postcss 处理的，所以我们得分别配 .posthtmlrc、.babelrc 和 .postcssrc。

### 执行
1. 命令行运行：parcel src/index.html
1. 访问默认地址：http://localhost:1234/
1. 查看控制台输出结果

### parcel 命令参数：
1. -p xxxx：指定打开端口