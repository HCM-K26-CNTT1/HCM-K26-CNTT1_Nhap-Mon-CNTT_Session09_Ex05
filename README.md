# Kết quả AI: Tìm hiểu về Mảng (Array)

## 1. Mảng là gì?

**Mảng (Array)** là một cấu trúc dữ liệu dùng để lưu trữ nhiều giá trị trong cùng một nhóm. Mỗi giá trị được gọi là một **phần tử**.

Ví dụ, danh sách điểm của một sinh viên qua 4 bài kiểm tra có thể là:

`[8, 7, 9, 6]`

Trong ví dụ này, dữ liệu gồm 4 phần tử lần lượt là `8`, `7`, `9` và `6`.

## 2. Mảng được sử dụng để làm gì?

Mảng giúp chúng ta:

- Lưu trữ nhiều dữ liệu có liên quan với nhau.
- Truy cập từng phần tử thông qua vị trí.
- Thuận tiện khi tính toán, tìm kiếm và xử lý dữ liệu.

**Ví dụ thực tế:** Giáo viên cần lưu điểm kiểm tra của nhiều sinh viên. Thay vì tạo một biến riêng cho mỗi điểm, giáo viên có thể sử dụng một cấu trúc dữ liệu để quản lý danh sách điểm.

## 3. Ví dụ bằng Python

```python
scores = [8, 7, 9, 6]

print(scores[0])
print(scores[2])
```

### Giải thích từng dòng

- `scores = [8, 7, 9, 6]`: Tạo một danh sách chứa 4 điểm.
- `print(scores[0])`: In ra phần tử đầu tiên, có giá trị là `8`.
- `print(scores[2])`: In ra phần tử thứ ba, có giá trị là `9`.

**Kết quả:**

```text
8
9
```

**Lưu ý:** Trong Python, `list` (danh sách) thường được dùng để minh họa cách lưu trữ nhiều giá trị tương tự ý tưởng về mảng. Chỉ số của danh sách bắt đầu từ `0`, không phải `1`.

## 4. Cách hoạt động

Với danh sách `scores = [8, 7, 9, 6]`:

1. Chương trình tạo danh sách gồm 4 phần tử.
2. Khi truy cập `scores[0]`, chương trình lấy giá trị `8`.
3. Khi truy cập `scores[2]`, chương trình lấy giá trị `9`.
4. Lệnh `print()` hiển thị giá trị được yêu cầu lên màn hình.

## 5. Tổng kết

- Mảng là cấu trúc dữ liệu dùng để tổ chức nhiều phần tử.
- Các phần tử có thể được truy cập thông qua chỉ số.
- Mảng hữu ích khi cần quản lý một nhóm dữ liệu liên quan.
- Trong Python, `list` có thể dùng để minh họa ý tưởng về mảng.
- Chỉ số của danh sách trong Python bắt đầu từ `0`.

## 6. Câu hỏi luyện tập

**Câu 1 – Dễ:** Mảng hoặc danh sách có ích gì khi lưu điểm của nhiều sinh viên?

**Câu 2 – Trung bình:** Với `numbers = [10, 20, 30, 40]`, giá trị của `numbers[1]` là bao nhiêu?

**Câu 3 – Khó hơn:** Viết một đoạn code Python ngắn để tạo danh sách gồm ba số và in ra phần tử đầu tiên.

---

*Tài liệu được tạo theo Prompt gia sư AI dành cho sinh viên năm nhất mới học Cấu trúc dữ liệu.*
