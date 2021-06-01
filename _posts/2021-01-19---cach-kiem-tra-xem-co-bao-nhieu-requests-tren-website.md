---
layout: post
title:  "Cách Kiểm Tra Xem Có Bao Nhiêu Requests Trên Website"
author: tuanducdesign
categories: [ Website ]
tags: [Requests, Tăng tốc]
image: static/media/cach-kiem-tra-xem-co-bao-nhieu-requests-tren-website.jpg
description: "Về vấn đề dùng nhiều scripts bên ba thì bạn sẽ không tránh khỏi được có nhiều requests được tải cùng website."
toc: true
---

Về vấn đề dùng nhiều scripts bên ba thì bạn sẽ không tránh khỏi được có nhiều requests được tải cùng website, Bài viết ngày hôm nay mình sẽ hướng dẫn các bạn cách kiểm tra xem có bao nhiêu requests trên Website.

{% include image.html src="cach-kiem-tra-xem-co-bao-nhieu-requests-tren-website.jpg" webp="cach-kiem-tra-xem-co-bao-nhieu-requests-tren-website.webp" type="jpg" alt="Cách Kiểm Tra Xem Có Bao Nhiêu Requests Trên Website" %}

## Requests là gì

Request có thể hiểu nhanh là thông tin gửi từ client lên server. Khi bạn lên trình duyệt browser gõ một địa chỉ nào đó, ví dụ bạn gõ là [{{ site.url }}/]({{ site.url }}/) thì ngay lập tức trình duyệt sẽ dựa vào tên domain để gửi yêu cầu truy cập đến địa chỉ IP mà domain này đang trỏ tới, lúc này phía server sẽ phân tích yêu cầu và sẽ gửi luồng xử lý tới vị trí vị trí lưu trữ của mã nguồn và nhiệm vụ của các mã nguồn là tiếp nhận yêu cầu, phân tích request đó và trả kết quả lại cho client.

## Cách kiểm tra xem có bao nhiêu requests đang hoạt động

Để kiểm tra xem có bao nhiêu requests đang hoạt động thì bạn ra trang chủ.

Sau đó bấm chuột phải chọn kiểm tra phần tử, tiếp theo chuyển qua tab Network.

Kế tiếp bạn reload lại trang để trình duyệt có thể load lại được một số thông tin.

Sau khi trang load lại xong thì sẽ có một đoạn text tương tự như sau ở phía dưới bên trái :

```text
272 requests
1.9 MB transferred
10.1 MB resources
Finish: 7.63 s
DOMContentLoaded: 1.12 s
```

{% include image.html src="so-requests-tren-website.jpg" webp="so-requests-tren-website.webp" type="jpg" alt="Số requests trên website" %}

## Tìm kiếm và tối ưu các requests

Bên trên có khung Fillter bạn gõ vào đó tên domain hoặc đuôi mở rộng mà bạn cần check để kiểm tra.

{% include image.html src="so-requests-tren-website.jpg" webp="so-requests-tren-website.webp" type="jpg" alt="Số requests trên website" %}

Bây giờ chúng ta tiến hành áp dụng các kiến thức từ bài {% include internal-link.html href="2021/01/tang-toc-website-tu-preload.html" title="Tăng Tốc Website Từ Preload" %} để áp dụng vào bài này.

Cú pháp quen thuộc mà mình muốn nhắc đến đó chính là:

``` <link rel="preload" ``` kèm với cú pháp ``` as="font" ```

Để tìm cú pháp phù hợp với ``` as= ``` thì bạn đọc nội dung sau:

{% include external-link.html href="https://developer.mozilla.org/en-US/docs/Web/HTML/Preloading_content#what_types_of_content_can_be_preloaded" title="https://developer.mozilla.org/en-US/docs/Web/HTML/Preloading_content#what_types_of_content_can_be_preloaded" %}

Chúc các bạn thành công.
