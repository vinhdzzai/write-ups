| Analysis |
|-----------|
| SOP không ngăn cản việc gửi request sang domain khác. Chỉ việc đọc response mới bị chặn. |

<details>
<summary><b>Phân tích tại sao exploit hoạt động</b></summary>

Khi admin bot truy cập note chứa Stored XSS:

1. Payload được thực thi.
2. Browser gửi request với cookie của admin.
3. Request thành công.
4. Dữ liệu được gửi về webhook attacker.

</details>
