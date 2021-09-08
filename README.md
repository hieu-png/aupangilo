# aupangilo
OpenGL repo

Link trello nhóm: https://trello.com/b/BmO1XXT9/project

**Cách cài OpenGL trên Visual studio code:**
1. Cài VSCode
2. Tải Extension "C/C++ extension for VS Code", mở extension view Ctrl+Shift+X
3. Tải MinGW về. Đưa nó vào Path theo các bước:

-Link MinGW: https://drive.google.com/file/d/1UpQWw1fAfXrz7nK9K9poSrAzKYcHlob2/view. Tải về và giải nén ra

-Tìm _Edit environment variables for your account_ ở thanh search

-Chọn _Path_ Cột _variable_ ở _User variable for ..._

-Thêm một cái bằng cách ấn _New_ rồi thêm vào địa chỉ đến chỗ giải nén cái kia: _%Chỗ_giải_nén%/MinGW/bin_. VD: _D:\Document\MinGW\bin_

-Ấn OK để lưu

4.Chỉnh sửa các file config launch ở trong .vscode
- Ở c_cpp_properties.json sửa compilerPath Thay _D:\\Document\\MinGW\\bin\\gcc.exe_ thành _%Chỗ_giải_nén%\\MinGW\\bin\\gcc.exe_

K làm đc ăn cốc
