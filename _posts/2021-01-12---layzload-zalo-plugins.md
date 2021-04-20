---
layout: post
title:  "Lazyload Zalo Plugins"
author: tuanducdesign
categories: [ Javascript ]
tags: [Lazyload, Zalo]
image: static/media/lazyload-zalo-plugins.jpg
description: "Trong bài viết tiếp theo của ngày hôm nay mình sẽ hướng dẫn các bạn cách Lazyload script của Zalo để tải trang nhanh hơn."
---

Trong bài viết tiếp theo của ngày hôm nay mình sẽ hướng dẫn các bạn cách Lazyload script của Zalo để tải trang nhanh hơn.

![Lazyload Zalo Plugins]({{ site.url }}/static/media/lazyload-zalo-plugins.jpg)

Đầu tiên các bạn truy cập vào trang : [https://developers.zalo.me/docs/social/share](https://developers.zalo.me/docs/social/share)

Tiếp theo các bạn chọn plugins mà mình cần chèn vào website.

![Zalo Plugins Share]({{ site.url }}/static/media/zalo-plugins-share.jpg)

Sau đó chọn loại bố cục và màu sắc mà bạn cần dùng sau đó lấy mã.

![Zalo Layout Share]({{ site.url }}/static/media/zalo-layout-share.jpg)

![Zalo Color Share]({{ site.url }}/static/media/zalo-color-share.jpg)

Rồi bây giờ chúng ta cùng xem cấu trúc đoạn code nó như nào nhé!

```html
<div class="zalo-share-button" data-href="" data-oaid="579745863508352884" data-layout="2" data-color="blue" data-customize=false></div>
<script src="https://sp.zalo.me/plugins/sdk.js"></script>
```

Đoạn đầu là thành phần chính nơi sẽ trả ra các thuộc tính và giá trị sau khi script load xong, đoạn tiếp theo là các script của Zalo. Đây sẽ là đoạn mà chúng ta cần quan tâm nhất để có thể tải trang được nhanh.

Tiếp theo chúng ta cùng xem đoạn Javascript của Zalo đã được rút ngắn lại để load trang nhanh hơn.

```javascript
function td_zaloplugins(){var t=document.createElement("script");t.async=!0,t.defer=!0,t.src="https://sp.zalo.me/plugins/sdk.js",document.body.appendChild(t)}window.addEventListener?window.addEventListener("load",td_zaloplugins,!1):window.attachEvent?window.attachEvent("onload",td_zaloplugins):window.onload=td_zaloplugins;
```

Chúc các bạn thành công.
