# 装机工坊 · 组装电脑买卖站（简洁版）

## 文件

- `index.html` — 网站
- `images/` — 产品图（hero / 三档 / 配件）

## 打开

```bash
open ~/Projects/pc-build-shop/index.html
```

## 必改：联系方式

打开 `index.html` 最上面：

```js
window.SHOP = {
  name: "装机工坊",
  wechat: "你的微信号",
  phone: "你的电话",
  facebook: "https://www.facebook.com/你的主页",
  messenger: "https://m.me/你的主页",
  hours: "每天 10:00–22:00",
  city: "同城可面交 / 可快递"
};
```

改完刷新页面，顶栏、联系区、按钮会一起更新。

## 上线

整个文件夹上传 Cloudflare Pages / Netlify / GitHub Pages（保留 `images` 目录）。
