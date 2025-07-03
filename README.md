### 🔄 2. CÁC CHẾ ĐỘ TRONG VIM

| Chế độ         | Mục đích                                 | Cách chuyển đổi              |
|----------------|-------------------------------------------|------------------------------|
| **Normal mode**| Di chuyển, xóa, sao chép, dán             | Mặc định khi mở file         |
| **Insert mode**| Gõ/chỉnh sửa nội dung                     | Nhấn `i`, `a`, `o`, `I`, `A` |
| **Command mode**| Thực hiện lệnh như `:w`, `:q`, v.v.       | Từ Normal mode, gõ `:`       |

---

### 📝 3. CHUYỂN ĐỔI GIỮA CÁC CHẾ ĐỘ

| Phím           | Mô tả                              |
|----------------|-------------------------------------|
| `i`            | Chèn trước con trỏ (insert)         |
| `a`            | Chèn sau con trỏ                    |
| `I`            | Chèn ở đầu dòng                     |
| `A`            | Chèn ở cuối dòng                    |
| `o`            | Tạo dòng mới bên dưới và chèn       |
| `Esc`          | Quay về Normal mode                 |

---

### 🧭 4. DI CHUYỂN CON TRỎ

| Phím           | Mô tả                               |
|----------------|--------------------------------------|
| `h`, `l`       | Sang trái, phải                      |
| `j`, `k`       | Xuống, lên                           |
| `w`, `b`       | Tới từ tiếp theo, lùi về từ trước    |
| `0`, `^`, `$`  | Đầu dòng, ký tự đầu tiên, cuối dòng  |
| `gg`, `G`      | Đầu file, cuối file                  |
| `:n`           | Nhảy đến dòng số `n`                 |

---

### ✂️ 5. CHỈNH SỬA VĂN BẢN

| Phím/Lệnh      | Mô tả                                   |
|----------------|------------------------------------------|
| `x`            | Xoá 1 ký tự                              |
| `dd`           | Xoá dòng hiện tại                        |
| `yy`           | Sao chép dòng hiện tại                   |
| `p`            | Dán sau con trỏ                          |
| `u`            | Hoàn tác thao tác trước (undo)           |
| `Ctrl + r`     | Làm lại thao tác đã undo (redo)          |
| `cw`           | Thay thế 1 từ (change word)              |
| `cc`           | Thay thế cả dòng                         |

---

### 💾 6. LƯU FILE & THOÁT

| Lệnh           | Mô tả                                 |
|----------------|----------------------------------------|
| `:w`           | Lưu file                              |
| `:q`           | Thoát                                 |
| `:wq` hoặc `ZZ`| Lưu và thoát                          |
| `:q!`          | Thoát mà không lưu                     |

---

### 🔍 7. TÌM KIẾM TRONG FILE

| Lệnh / Phím    | Mô tả                                  |
|----------------|-----------------------------------------|
| `/chuỗi`       | Tìm từ `chuỗi` từ trên xuống dưới       |
| `?chuỗi`       | Tìm từ `chuỗi` từ dưới lên              |
| `n`            | Tới kết quả tìm kiếm tiếp theo          |
| `N`            | Tới kết quả tìm kiếm trước đó           |
