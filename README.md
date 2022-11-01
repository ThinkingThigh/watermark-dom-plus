# watermark-dom-plus

由于watermark-dom作者不维护issue和pr，修改一些bug发包使用。

## 如何使用

### 安装
```
npm i watermark-dom-plus
```

### 使用

```
import watermark from 'watermark-dom-plus'
// ...
// 启用水印
watermark.load({
      watermark_txt: "水印内容",
      watermark_alpha: 0.1,
      watermark_fontsize: "12px"
    });
// ...
// 删除水印
watermark.remove();
// ...
```

## 感谢原插件作者及贡献者，传送门

https://github.com/saucxs/watermark-dom
