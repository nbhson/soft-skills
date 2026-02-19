# Chương 2: Phê bình một cách gián tiếp

> **Nguyên Tắc Cốt Lõi:** Góp ý sai lầm của người khác một cách gián tiếp.

### Phân tích chiều sâu (Deep Analysis)
Carnegie cảnh báo về từ nguy hiểm nhất trong giao tiếp: **"NHƯNG"**.
- **Cơ chế:** Từ "Nhưng" là một cục tẩy. Nó xóa sạch mọi điều tốt đẹp bạn vừa nói trước đó. "Anh rất tốt nhưng..." có nghĩa là "Anh không tốt".
- **Chìa khóa:** Hãy thay từ "Nhưng" bằng từ "Và". Từ "Và" là cầu nối. Nó cộng thêm giá trị chứ không trừ đi.
- **Gợi ý gián tiếp:** Đôi khi không cần nói gì cả, chỉ cần hành động gương mẫu hoặc gợi ý nhẹ nhàng là đủ. Người thông minh tự khắc hiểu, và họ biết ơn bạn vì đã không vạch áo cho người xem lưng.

---

## 1. Từ "Nhưng" chết chóc
Rất nhiều người bắt đầu lời khen rất hay, nhưng lại phá hỏng tất cả bằng từ "NHƯNG".
Ví dụ: *"Con học kỳ này tiến bộ lắm, NHƯNG môn Toán còn kém quá."*
Từ "nhưng" làm cho lời khen trước đó trở nên giả tạo. Đứa trẻ sẽ nghĩ: "Hóa ra mẹ khen mình chỉ để mắng mình thôi."

## 2. Thay "Nhưng" bằng "Và"
Hãy sửa lại: *"Con học kỳ này tiến bộ lắm, VÀ nếu con chăm chỉ hơn một chút nữa thì môn Toán cũng sẽ tốt như các môn khác."*
Chỉ thay một từ, ý nghĩa thay đổi hoàn toàn. Lời khen được giữ nguyên giá trị, và lời góp ý trở thành một sự khích lệ hướng tới tương lai.

## 3. Câu chuyện thực tế
- **Charles Schwab:** Đi ngang qua xưởng, thấy công nhân hút thuốc ngay dưới biển "Cấm hút thuốc". Ông không chỉ tay vào biển báo và quát: "Các anh không biết đọc à?".
  Ông bước lại, mời họ mỗi người một điếu xì gà và nói: *"Tôi sẽ rất cảm kích nếu các anh hút những điếu này ở bên ngoài."*
  Các công nhân hiểu ý ngay. Họ không bị mất mặt, họ được tặng quà, và họ tự giác tuân thủ quy định. Họ yêu mến Schwab vì cách xử lý quá tinh tế. Ông đã phê bình họ mà không nói một lời phê bình nào.

## 🚫 Những kẻ ngốc thường làm gì?
- Sử dụng mô hình "Khen -> NHƯNG -> Chê" một cách máy móc và thô thiển.
- Chỉ trích trực diện, vạch trần lỗi lầm của người khác một cách trần trụi.
- Nghĩ rằng nói bóng gió là hèn nhát, cần phải "thẳng thắn" (thực ra là thô lỗ).
- Không quan tâm đến cảm xúc của người nghe, chỉ muốn xả cơn bực tức của mình.

## 4. Hành động áp dụng
1. **Tránh chỉ trích trực diện:** Thay vì nói "Anh làm sai rồi", hãy kể một câu chuyện tương tự hoặc gợi ý nhẹ nhàng.
2. **Dùng hành động thay lời nói:** Như Schwab, đôi khi một cử chỉ nhỏ (tặng xì gà, làm gương) hiệu quả hơn ngàn lời nói.
3. **Kiểm soát từ ngữ:** Tập thói quen thay "Nhưng" bằng "Và" hoặc ngắt câu và bắt đầu ý mới.

## 👨‍💻 Áp dụng cho Senior Developer
1. **Automated Linter/Formatter:** Thay vì đi soi mói từng dòng code của Junior và comment: *"Sai thụt đầu dòng rồi"*, *"Thiếu dấu trấm phẩy"*, *"Tên biến sai quy tắc"*. Hãy im lặng setup **Linter/Formatter** (ESLint, Prettier) vào CI/CD pipeline. Khi họ push code lên, hệ thống sẽ tự động báo lỗi hoặc tự động sửa. Họ sẽ tự hiểu và tuân thủ mà không cảm thấy bị soi mói. Bạn phê bình họ gián tiếp qua công cụ.
2. **Thói quen đi làm (Leading by Example):** Nhân viên hay đi trễ. Thay vì họp và mắng *"Tại sao mọi người hay đi trễ thể?"*. Sếp hãy đi sớm mỗi ngày và đứng lên chào to vui vẻ *"Chào buổi sáng cả team! Hôm nay trời đẹp nhỉ!"* lúc 8:30 sáng. Ai đi trễ bước vào sau sẽ tự cảm thấy ngại và điều chỉnh hành vi.
3. **"We" instead of "You" (Dùng "Chúng ta"):** Khi tìm thấy bug, đừng nói: *"Ê, **em** vừa tạo ra bug này"*. Hãy nói: *"Có vẻ **chúng ta** đang gặp một vấn đề nhỏ ở module này. **Chúng ta** cùng xem log nhé"*. Chuyển từ "You" (Đối đầu) sang "We" (Đồng hành) giúp giảm sự đổ lỗi.
4. **Automated Tests:** Tương tự Linter, hãy viết Unit Test để bắt lỗi logic. Khi test đỏ, máy tính là kẻ báo tin xấu, không phải bạn. Dev dễ dàng chấp nhận việc máy tính báo sai hơn là đồng nghiệp chê bai.
5. **Questioning Approach (Hỏi để họ tự nhận ra):** *"Đoạn code này liệu có handle được 1 triệu request cùng lúc không nhỉ?"* (Gián tiếp nói: Code này chậm lắm, sửa đi). Câu hỏi này nhẹ nhàng hơn câu khẳng định *"Code này sẽ sập khi high load"*.
6. **User Stories as Critique:** Đừng chê UI xấu. Hãy nói: *"User mới vào app có thể sẽ hơi khó tìm nút này vì màu nó hơi chìm"*. Criticism được bọc dưới dạng quan tâm đến User, không phải tấn công Designer/Frontend Dev.

---
## Trích dẫn hay từ tác giả
> *"Chỉ cần thay đổi một từ 'nhưng' thành từ 'và', bạn có thể biến một lời chỉ trích thành một lời động viên."*

> *"Những người nhạy cảm rất biết ơn khi bạn chỉ ra lỗi lầm của họ một cách gián tiếp và giữ thể diện cho họ."*

> *"Hãy cố gắng đừng bao giờ nói 'Bạn sai rồi'. Hãy dùng những cách tế nhị hơn."*