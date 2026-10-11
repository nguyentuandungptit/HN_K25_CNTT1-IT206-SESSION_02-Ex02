# Bài làm: Phân định lại 3 vai trò trong đội RikkeiGo

## Phần 1: Phân tích

| Quy ước | Đúng/Sai | Quyết định này thuộc về vai trò nào & vì sao | Triệu chứng ở Bối cảnh do quy ước gây ra (nếu có) |
| :--- | :---: | :--- | :--- |
| **QU1.** Đức duyệt từng đoạn code và tự chọn thư viện bản đồ cho tính năng đặt xe. | **Sai** | **Developers.** Nhóm phát triển tự quản lý và chịu trách nhiệm toàn bộ về giải pháp kỹ thuật, lựa chọn công nghệ và cấu trúc mã nguồn. Product Owner chỉ xác định sản phẩm cần có tính năng gì để đạt giá trị nghiệp vụ, không can thiệp vào chuyên môn lập trình. | Gây ra cả hai triệu chứng: Đức bị quá tải vì phải duyệt code và chọn thư viện thay cho đội; lập trình viên phàn nàn vì bị ép dùng giải pháp kỹ thuật do người ngoài chuyên môn chỉ định. |
| **QU2.** Để đội làm nhanh hơn, trong buổi Daily Scrum mỗi sáng, Lan giao cụ thể ai làm thẻ việc nào trong ngày. | **Sai** | **Developers.** Nhóm phát triển là một tập thể tự quản lý, các thành viên tự thỏa thuận và chủ động nhận thẻ việc trong Sprint Backlog. Scrum Master là người hỗ trợ đội tháo gỡ khó khăn và duy trì sự kiện Scrum, không có quyền phân công công việc như quản lý dự án. | Gây ra triệu chứng lập trình viên phàn nàn bị bắt làm theo cách kém hiệu quả, vì việc bị áp đặt làm mất tính chủ động và khả năng phối hợp của nhóm. |
| **QU3.** Đức sắp xếp thứ tự ưu tiên Product Backlog dựa trên giá trị mang lại cho người đặt xe. | **Đúng** | **Product Owner (Đức).** Product Owner sở hữu Product Backlog và chịu trách nhiệm tối ưu hóa giá trị của sản phẩm. Việc sắp xếp thứ tự các hạng mục theo giá trị mang lại cho người dùng là đúng quyền hạn và trách nhiệm chuẩn của vai trò này. | Không gây ra triệu chứng nào (quy ước đúng nghiệp vụ Scrum). |
| **QU4.** Developers tự đổi thứ tự hạng mục trong Product Backlog khi thấy một tính năng khác dễ làm hơn. | **Sai** | **Product Owner (Đức).** Chỉ có Product Owner mới có quyền quyết định và thay đổi thứ tự ưu tiên trên Product Backlog theo mục tiêu kinh doanh. Developers có thể ước lượng độ phức tạp để góp ý, nhưng không được tự ý đổi thứ tự vì lý do dễ làm. | Gián tiếp gây ra triệu chứng Đức bị quá tải, vì anh phải mất công rà soát lại Backlog và xử lý độ lệch giữa mục tiêu sản phẩm với phần việc đội tự ý đổi. |

---

## Phần 2: Vá lỗi

1. **QU1 (Quyết định kỹ thuật và kiểm duyệt code):** Đức làm rõ yêu cầu nghiệp vụ của tính năng đặt xe, còn Developers tự chọn thư viện bản đồ và tự tổ chức đánh giá chất lượng mã nguồn.
2. **QU2 (Phân chia công việc trong Daily Scrum):** Trong buổi Daily Scrum, Developers tự theo dõi tiến độ và chủ động nhận các thẻ việc trong ngày, còn Lan chỉ hỗ trợ điều phối và tháo gỡ vướng mắc phát sinh.
3. **QU4 (Thứ tự ưu tiên Product Backlog):** Developers thực hiện công việc theo đúng thứ tự ưu tiên trên Product Backlog do Đức sắp xếp, và chủ động trao đổi với Đức nếu phát hiện tính năng có trở ngại kỹ thuật cần cân nhắc lại.
