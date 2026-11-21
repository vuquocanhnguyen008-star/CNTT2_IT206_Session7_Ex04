# Bài thực hành 4: Dùng Feynman Prompt để học kiến thức lập trình (OOP)

**Họ tên:** ........  **MSSV:** ........  **Ngôn ngữ chọn:** Java  **Mô hình AI dùng:** ........

## 1. Mục tiêu
Nhờ AI làm gia sư hỏi mình về 5 khái niệm OOP: Class, Object, Attribute, Method, Constructor. Mình là người giải thích, AI chỉ hỏi và đánh giá, không giảng trước.

## 2. Prompt của mình

```
# VAI TRÒ
Bạn là gia sư OOP (Java), dùng phương pháp Feynman. Tôi là sinh viên vừa học xong OOP.

# LUẬT
- Không giải thích toàn bộ kiến thức ngay từ đầu.
- Mỗi lượt chỉ đặt MỘT câu hỏi.
- Nếu tôi trả lời sai, không đưa đáp án ngay; yêu cầu tôi giải thích lại bằng ngôn ngữ đơn giản hơn.

# QUY TRÌNH
Hỏi lần lượt: Class → Object → Attribute → Method → Constructor.
Với mỗi khái niệm:
1. Hỏi và yêu cầu tôi giải thích bằng lời của mình.
2. Đánh giá mức hiểu, chỉ ra chỗ chưa chính xác.
3. Nếu tôi chưa hiểu: đưa ví dụ đời thường rồi yêu cầu tôi giải thích lại.
4. Sau Class thì yêu cầu tôi giải thích lại, rồi mới sang khái niệm tiếp theo.
Phiên học có ít nhất 5 câu hỏi.

# KẾT THÚC
Lập bảng tổng kết: Khái niệm | Mức hiểu | Điểm chưa chính xác.
Bắt đầu bằng câu hỏi đầu tiên về Class.
```

## 3. Hội thoại với AI
*(Dán toàn bộ hội thoại thật, tối thiểu 5 cặp hỏi - đáp, hoặc ảnh chụp)*

| Lượt | AI hỏi | Mình trả lời |
|---|---|---|
| 1 | (Class) | (dán) |
| 2 | (Object) | (dán) |
| 3 | (Attribute) | (dán) |
| 4 | (Method) | (dán) |
| 5 | (Constructor) | (dán) |

**Gợi ý khi trả lời (nói bằng lời của mình, không cần thuật ngữ):**
- Class: bản thiết kế/khuôn mẫu để tạo ra đối tượng.
- Object: sản phẩm làm ra từ khuôn đó.
- Attribute: thông tin mô tả đối tượng (tên, tuổi...).
- Method: việc đối tượng làm được (học, chạy...).
- Constructor: hàm chạy lúc tạo đối tượng để gán giá trị ban đầu.

*Mẹo kiểm tra AI:* có một lượt mình cố ý trả lời mơ hồ để xem AI có chịu không đưa đáp án ngay không.

## 4. Bảng mức độ hiểu
*(Dán bảng AI tổng kết)*

| Khái niệm | Mức hiểu | Điểm chưa chính xác |
|---|---|---|
| Class | | |
| Object | | |
| Attribute | | |
| Method | | |
| Constructor | | |

## 5. Ví dụ minh họa Class và Object

```java
class SinhVien {                          // Class: khuôn mẫu
    String ten;                           // Attribute
    String maSV;                          // Attribute

    SinhVien(String ten, String maSV) {   // Constructor
        this.ten = ten;
        this.maSV = maSV;
    }

    void inThongTin() {                   // Method
        System.out.println(ten + " - " + maSV);
    }
}

SinhVien sv1 = new SinhVien("An", "01");  // Object: sv1 tạo từ class SinhVien
sv1.inThongTin();                         // In ra: An - 01
```

Hiểu đơn giản: `SinhVien` là mẫu hồ sơ trống, `sv1` là hồ sơ đã điền thông tin của bạn An.

## 6. Mình tự viết lại sau buổi học
*(Viết 5-7 câu bằng lời của mình, ví dụ:)*
"Class giống như cái khuôn làm bánh, còn Object là từng cái bánh làm ra. Mỗi cái bánh có thông tin riêng (Attribute) như nhân, màu. Bánh làm được việc gì đó là Method. Constructor là lúc đổ bột vào khuôn, gán sẵn nhân và màu cho cái bánh..."

## 7. Checklist
- [ ] Prompt hoàn chỉnh
- [ ] Hội thoại ≥ 5 câu hỏi
- [ ] Bảng mức độ hiểu
- [ ] Ví dụ Class và Object
- [ ] Phần tự viết lại

## 8. Nhận xét
- Cách này khiến mình phải tự nói ra nên nhớ lâu hơn là đọc sách.
- Luật "không đưa đáp án ngay" giúp mình thấy rõ chỗ mình chưa chắc.
- Chỗ chưa tốt: (viết theo thực tế, ví dụ AI có lỡ giảng dài không).
