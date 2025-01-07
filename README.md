my_lambda_project/
│
├── src/                        # Mã nguồn chính của Lambda
│   ├── __init__.py              # Khởi tạo thư mục (nếu cần thiết)
│   ├── lambda_function.py       # Tệp Python chứa hàm Lambda chính
│   └── utils.py                 # Các hàm phụ trợ khác (nếu có)
│
├── requirements.txt            # Các thư viện cần thiết cho dự án
├── .gitignore                  # Các tệp và thư mục không muốn đưa vào git
├── README.md                   # Tài liệu hướng dẫn, mô tả dự án
├── test/                        # Thư mục chứa các bài kiểm tra
│   ├── __init__.py              # Khởi tạo thư mục (nếu cần thiết)
│   └── test_lambda_function.py  # Các bài kiểm tra cho Lambda Function
│
└── .env                        # Các cấu hình cho Lambda, các biến môi trường (ví dụ: thông tin API, DB, v.v.)

