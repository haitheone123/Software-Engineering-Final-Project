![Hình ảnh](https://raw.githubusercontent.com/kurtjd/chesscorpy/master/chesscorpy/static/img/screenshot.png)

ChessCorPy
====================
Bài tập lớn bộ môn Kỹ thuật phần mềm.
Sinh viên thực hiện:
* Nguyễn Đức Hải
* Nguyễn Văn Thành
* Nguyễn Trần Hùng
  
Phần mềm web-based đơn giản cho trò chơi cờ vua bằng ngôn ngữ Python và framework Flask + SQLite. 

Chức năng

* Khởi tạo tài khoản
* Tạo ra các phòng chơi public / private
* Màn hình giao tiếp giữa các người chơi
* Gửi mail tự động cho người chơi (đang phát triển)
* Kiểm tra input và lỗi
* Mô phỏng trò chơi cờ vua


Yêu cầu
============
* Python 3+
* Các package trong file requirements.txt

Cài đặt 
============
```pip install -r requirements.txt```

Khởi chạy phần mềm
===
Ở trong folder chứa package chesscorpy (ưu tiên môi trường ảo)
Trước hết kích hoạt môi trường ảo
```

set FLASK_APP=./chesscorpy/app.py
$env FLASK_APP="./chesscorpy/app.py"
flask run
```

Nhận xét
=======
Các chức năng chưa thực sự hoàn chỉnh, một số chức năng xung đột và gây ra lỗi
Giao diện chưa đẹp
Chỉ chạy được trên một máy


File tham khảo từ các repository khác
================
* Chris Oakman (chessboard.js)
* Jeff Hlywa (chess.js)
