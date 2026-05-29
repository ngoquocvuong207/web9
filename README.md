# Editor 1: Trang Phân Tích URL

## Mô tả

Trang HTML tĩnh hiển thị cấu trúc phân tích của một URL mẫu, bao gồm 5 thành phần:
**Protocol**, **Domain**, **Path**, **Query String**, và **Fragment**.

## Cấu trúc file

```
project/
└── index.html
```

> Bài này chỉ yêu cầu 1 file duy nhất. CSS được viết nội bộ trong thẻ `<style>`.

## URL mẫu sử dụng

```
https://example.com/products/list?page=2#top
```

| Thành phần | Giá trị | Ý nghĩa |
|---|---|---|
| Protocol | `https://` | Giao thức bảo mật HTTPS |
| Domain | `example.com` | Tên miền máy chủ |
| Path | `/products/list` | Đường dẫn tài nguyên |
| Query | `?page=2` | Tham số truy vấn |
| Fragment | `#top` | Neo đến phần tử trong trang |

## Cách chạy

1. Lưu file `index.html` vào máy tính
2. Mở bằng trình duyệt (Chrome, Firefox, Edge…) — nhấp đôi vào file hoặc kéo vào trình duyệt
3. Hoặc dán nội dung vào [CodePen](https://codepen.io) / [JSFiddle](https://jsfiddle.net) để xem trực tiếp online

## Đẩy lên GitHub Pages

```bash
# 1. Tạo repo mới trên GitHub (đặt tên tùy ý, ví dụ: url-analysis)
# 2. Clone về máy
git clone https://github.com/<username>/url-analysis.git

# 3. Copy file index.html vào thư mục repo
# 4. Commit và push
git add index.html
git commit -m "Add URL analysis page"
git push origin main

# 5. Vào Settings > Pages > chọn branch main, thư mục root > Save
# Link sẽ có dạng: https://<username>.github.io/url-analysis/
```

## Yêu cầu đã đáp ứng

- [x] Có tiêu đề trang (`<title>` và heading hiển thị)
- [x] Có URL mẫu hiển thị trên trang
- [x] Liệt kê đầy đủ 5 thành phần: protocol, domain, path, query, fragment
- [x] Giải thích ý nghĩa từng thành phần
- [x] File duy nhất `index.html`, không phụ thuộc file ngoài
