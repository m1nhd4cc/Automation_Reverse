# Automation_Reverse

Nơi lưu trữ các tệp plugin, script và tài liệu hướng dẫn để tích hợp AI (Cursor) với các công cụ reverse engineering phổ biến. Mục tiêu là tự động hóa các tác vụ phân tích bằng cách sử dụng Giao thức Ngữ cảnh Mô hình (Model Context Protocol - MCP).


### Hướng dẫn Cài đặt (Báo cáo)

Đây là các tài liệu `.docx` chứa hướng dẫn cài đặt, cấu hình và khắc phục sự cố chi tiết cho từng công cụ:

* **`autoreverse_ghidra.docx`**: Báo cáo chi tiết về cách thiết lập **Ghidra** với MCP, bao gồm cài đặt extension và chạy script "cầu nối" (bridge script).
* **`autoreverse_idapro.docx`**: Báo cáo chi tiết về cách thiết lập **IDA Pro** với MCP, bao gồm cài đặt plugin `ida-mcp-server.py` và các lỗi thường gặp 
* **`autoreverse_x64dbg.docx`**: Báo cáo chi tiết về cách thiết lập **x64dbg** với MCP, bao gồm cài đặt plugin `.dp64` và cấu hình script 

### Tệp Plugin & Script

Đây là các tệp nén chứa plugin và script cần thiết được đề cập trong báo cáo.

* **`GhidraMCP-release-1-4.zip`**: Tệp extension (plugin) cho **Ghidra**. Bạn sẽ cài đặt tệp này qua mục `File -> Install Extensions...` trong Ghidra.
* **`idapro_mcp.rar`**: Chứa script `ida-mcp-server.py` cho **IDA Pro**. Bạn cần giải nén và sao chép tệp `.py` vào thư mục `plugins` của IDA Pro.
* **`x64dbg_mcp.rar`**: Chứa plugin (`.dp64`/`.dp32`) và script "cầu nối" (`.py`) cho **x64dbg**. Bạn cần cài plugin vào thư mục `plugins` của x64dbg và dùng tệp `.py` để cấu hình trong Claude/Cursor.


## Sử dụng

1.  Chọn công cụ bạn muốn tích hợp (Ghidra, IDA Pro, hoặc x64dbg).
2.  Mở tệp `.docx` báo cáo tương ứng để đọc kỹ hướng dẫn.
3.  Sử dụng tệp `.zip` hoặc `.rar` tương ứng để lấy các tệp plugin/script và cài đặt theo các bước trong báo cáo.
