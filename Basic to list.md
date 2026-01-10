# Python Cơ Bản – Tổng Hợp

Nội dung dưới đây chỉ bao gồm **kiến thức cơ bản**, không có kỹ thuật nâng cao hay tối ưu.

---

## 1. MẢNG 1 CHIỀU & 2 CHIỀU

### 1.1. Mảng 1 chiều (list)

```python
a = [1, 2, 3]
```

**Hàm & thao tác cơ bản**

```python
len(a)          # độ dài
a.append(4)     # thêm phần tử
a.remove(2)     # xóa phần tử
a.pop()         # xóa phần tử cuối
a[0]            # truy cập phần tử
```

**Duyệt mảng**

```python
for x in a:
    print(x)
```

---

### 1.2. Mảng 2 chiều

```python
b = [
    [1, 2],
    [3, 4]
]
```

**Truy cập**

```python
b[0][1]
len(b)      # số dòng
```

**Duyệt mảng 2 chiều**

```python
for i in range(len(b)):
    for j in range(len(b[i])):
        print(b[i][j])
```

---

## 2. TOÁN HỌC

### 2.1. Phép toán cơ bản

```python
+   # cộng
-   # trừ
*   # nhân
/   # chia
```

```python
//  # chia lấy nguyên
%   # chia lấy dư
**  # lũy thừa
```

### 2.2. Hàm toán học cơ bản

```python
abs(x)
round(x)
pow(a, b)
```

---

## 3. CHUỖI (STRING)

### 3.1. Khai báo

```python
s = "hello"
```

### 3.2. Thao tác cơ bản

```python
len(s)
s[0]
s.lower()
s.upper()
s.strip()
```

### 3.3. Nối chuỗi

```python
a = "hi"
b = "there"
c = a + b
```

### 3.4. Duyệt chuỗi

```python
for c in s:
    print(c)
```

---

## 4. CÀI ĐẶT CƠ BẢN

### 4.1. In và nhập dữ liệu

```python
print("Hello")
x = input()
```

### 4.2. Ép kiểu

```python
int(x)
float(x)
str(x)
```

### 4.3. Điều kiện

```python
if x > 0:
    print("dương")
else:
    print("không dương")
```

### 4.4. Vòng lặp

```python
for i in range(5):
    print(i)

while x > 0:
    x -= 1
```

### 4.5. Hàm

```python
def add(a, b):
    return a + b
```

### 4.6. Kiểu dữ liệu cơ bản

```python
int
float
str
bool
list
```

---

**Ghi chú:** Tài liệu này phù hợp cho người mới bắt đầu hoặc ôn tập kiến thức Python cơ bản.
