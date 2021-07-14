---
layout: post
title:  "Bộ Ba Thư Viện Thần Thánh Giúp Website Tối Ưu"
author: tuanducdesign
categories: [ Library ]
tags: [Tối ưu, PageSpeed, Preload, Lazyload]
image: static/media/bo-ba-thu-vien-than-thanh-giup-website-toi-uu.jpg
webp: static/webp/bo-ba-thu-vien-than-thanh-giup-website-toi-uu.webp
description: "Bài viết ngày hôm nay mình sẽ tổng hợp bộ ba thư viện thần thánh giúp website của bạn tối ưu hơn."
toc: true
---

Bài viết ngày hôm nay mình sẽ tổng hợp bộ ba thư viện thần thành giúp website của bạn tối ưu hơn. Vậy các công cụ mà mình muốn nhắc đến là gì? Hãy cùng mình theo dõi hết bài viết ngày hôm nay nhé.

{% include image.html src="bo-ba-thu-vien-than-thanh-giup-website-toi-uu.jpg" webp="bo-ba-thu-vien-than-thanh-giup-website-toi-uu.webp" type="jpg" alt="Bộ Ba Thư Viện Thần Thánh Giúp Website Tối Ưu" %}

## DeferJS của tác giả Mai Nhựt Tân

### Vài dòng về thư viện DeferJS

Trong cuộc sống thực, nhiều tài nguyên và tập lệnh của bên thứ ba, chẳng hạn như jQuery, được sử dụng để cải thiện trang web của chúng tôi nhằm thêm tương tác bổ sung, hoạt ảnh và các hiệu ứng khác.

Thật không may, tập lệnh của bên thứ ba thường chặn hiển thị trang và tải xuống thêm tài nguyên của trang.

Có một kiến thức chung rằng bạn nên sử dụng ```<script src=".." async>``` (hoặc ```<script src=".." defer>```) hoặc đặt các tập lệnh của bạn ở cuối trang, sao cho càng nhiều trang được tải và hiển thị cho người dùng càng nhanh càng tốt.

Nhưng trong nhiều trường hợp khác nhau, việc sử dụng thuộc tính async hoặc defer không mang lại tốc độ trang nhanh hơn defer.js. Hơn nữa defer.js cũng cung cấp cho bạn những cách rất đơn giản để tối ưu hóa linh hoạt các tài nguyên khác trong trang web của bạn.

### Cách sử dụng thư viện DeferJS

Mình đã có một bài viết đầy đủ hướng dẫn sử dụng thư viện này. Bạn có thể đọc bài viết sau để biết cách sử dụng nhé!

{% include internal-link.html href="2021/01/huong-dan-su-dung-thu-vien-deferjs-cua-mai-nhut-tan" title="Hướng Dẫn Sử Dụng Thư Viện DeferJS của Mai Nhựt Tân" %}

## Lazysizes của tác giả aFarkas

### Vài dòng về thư viện Lazysizes

Lazysizes là một trình tải lười nhanh (miễn phí), thân thiện với SEO và tự khởi tạo cho hình ảnh (bao gồm hình ảnh đáp ứng picture / srcset), iframe, script / widget và hơn thế nữa. Nó cũng ưu tiên các nguồn lực bằng cách phân biệt giữa các yếu tố quan trọng trong chế độ xem và gần xem để làm cho hiệu suất cảm nhận thậm chí còn nhanh hơn.

Nó cũng có thể trở thành công cụ số một của bạn để tích hợp hình ảnh đáp ứng. Nó có thể tự động tính toán thuộc tính kích thước cho hình ảnh đáp ứng của bạn, cho phép bạn chia sẻ các truy vấn phương tiện cho các thuộc tính phương tiện với CSS của bạn, giúp tách bố cục (CSS) khỏi nội dung / cấu trúc (HTML) và nó giúp tích hợp hình ảnh đáp ứng vào bất kỳ môi trường nào thực sự đơn giản. Nó cũng bao gồm một tập hợp các plugin tùy chọn để mở rộng thêm chức năng của nó.

### Cách sử dụng thư viện Lazysizes

Mình đã có một bài viết đầy đủ hướng dẫn sử dụng thư viện này. Bạn có thể đọc bài viết sau để biết cách sử dụng nhé!

{% include internal-link.html href="2021/01/lazyload-image-va-iframe" title="Lazyload Image Và Iframe" %}

## Thư viện hỗ trợ Lazyload các script của mình

### Vài dòng về thư viện hỗ trợ Lazyload các script của mình

Khi nói đến việc tối ưu hóa tốc độ trang, theo nguyên tắc chung, bạn nên loại bỏ tất cả các Javascript mà các trang web của bạn không cần tải một cách rõ ràng. Khi bạn cần một cái cho một khía cạnh nào đó có thể được thay thế bằng CSS (như hiệu ứng hình ảnh), bạn nên thử thay thế hiệu ứng hoặc chức năng mà Javascript giúp bạn bằng CSS.

### Cách sử dụng thư viện hỗ trợ lazyload các script của mình

Mình đã có một số bài viết hướng dẫn sử dụng thư viện này. Bạn có thể đọc các bài viết sau để biết cách sử dụng nhé!

- {% include internal-link.html href="2021/01/lazyload-facebook-customize-chat" title="Lazyload Facebook Customize Chat" %}
- {% include internal-link.html href="2021/01/lazyload-twitter-publish" title="Lazyload Twitter Publish" %}
- {% include internal-link.html href="2021/01/lazyload-zalo-plugins" title="Lazyload Zalo Plugins" %}
- {% include internal-link.html href="2021/01/lazyload-google-fonts" title="Lazyload Google Fonts" %}
- {% include internal-link.html href="2021/01/lazyload-image-va-iframe" title="Lazyload Image Và Iframe" %}

Chúc các bạn thành công
