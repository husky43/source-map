## 文章

- [《脚本错误量极致优化-监控上报与Script error》](https://github.com/joeyguo/blog/issues/13)

- [《脚本错误量极致优化-让脚本错误一目了然》](https://github.com/joeyguo/blog/issues/14)

- [  noerror ](https://github.com/joeyguo/noerror)

## 运行示例

* 修改map文件

  - 项目开启 devtool: 'source-map', 本地打包生成对应错误js的 map文件 
  - 复制替换src/source-map/main.min.js.map 文件内容

* 启动 noerror 脚本错误监控

  - bash: npm start
  - open: http://localhost:8055/

* 运行example（上报错误, 修改参数：row 压缩文件行号 col 列号 msg 错误描述）

  - open: http://localhost:8055/report?msg=error&row=3&col=9600 
  - 刷新 http://localhost:8055/

## 示例效果

![sourcemap-noerror](https://cloud.githubusercontent.com/assets/10385585/25645140/056626d6-2fde-11e7-9163-38e6621ec1a4.gif)
