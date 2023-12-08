# show_read_me



# Nhom4_ParallelComputing_TSP

Project tìm hiểu về cách triển khai thuật toán genetic song song cho bài toán traveling salesman

Từ đó áp dụng bài toán để xây dựng một bản đồ giúp tìm ra lộ trình tối ưu từ một kho hàng đến các

địa điểm cần giao hàng.

## Hướng dẫn cài đặt

Cài đặt Node.js

Link: [Download | Node.js (nodejs.org)](https://nodejs.org/en/download)

Clone source code từ github	

      git clone https://github.com/NguyenThang1501/Nhom4_ParallelComputing_TSP.git
              
Install các thư viện cần thiết
      
Di chuyển vào thư mục frontend, cài đặt npm


      cd frontend

      npm install

Numpy: 

      pip install numpy

Mpi4py: 

      pip install mpi4py

Flask: 

      pip install flask

Flask Cors: 

      pip install flask_cors

Chạy chương trình:

Trong thư mục backend, chạy lệnh: 

      python tsp_para.py

Mở một terminal khác, chuyển sang thư mục tsp, chạy lệnh: 

      npm start
      
  Lưu ý: Khi chạy lệnh: **`python tsp_para.py`** có thể gặp lỗi:

 ![image](https://github.com/NguyenThang1501/Nhom4_ParallelComputing_TSP/assets/109154036/57b96ad9-3f3e-448c-9930-b688ff7e00dd)

Khi đó, chúng ta cần chạy lệnh:

      pip install --upgrade watchdog

Và chạy lại:

      python tsp_para.py

## Giao diện chính của ứng dụng:
![image](https://github.com/NguyenThang1501/Nhom4_ParallelComputing_TSP/assets/109154036/7e561353-3984-4759-9dfa-261be993abc6)


![image](https://github.com/NguyenThang1501/Nhom4_ParallelComputing_TSP/assets/109154036/94bb4ec0-7872-4fbd-b01b-c27f9f5551f2)



# Simple MPR
## How to set up
Clone master brand: 

https://github.com/godwindk3/Parallel.git

Backend
requirement 
-fastapi
-numpy
-Pillow
-pydicom
-uvicorn
-python-dotenv
Simple MPR <br/>
  1. Paste the path to dicom files in the .env file in backend folder
  2. Configure the port in the .env for the server to run
  3. Use git clone to clone the project
  4. Npm install
  5. fastApi install
  6. in front-end folder use npm start
  7. in backend folder use uvicorn main:app --reload
## How to use 
After the user interface show up, you can interact with three components 

     


