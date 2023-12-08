


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



# Simple MPR
## How to set up
### 1. Clone master brand

```
git clone https://github.com/godwindk3/Parallel.git
```

### 2.Install packages
## Back-End
- Truy cập vào thư mục: “..\dicom_loader\Parallel\backend”
- Dùng lệnh
```
pip install -r requirement.txt
```
###### (file requirement.txt chứa các thư viện cần thiết bao gồm: fastapi, numpy, Pillow, pydicom, uvicorn, python, pyton.dotenv)

## Front-End:
- Truy cập vào thư mục: “..\dicom_loader\Parallel\front-end”
- Dùng lệnh
```
npm install
```
### 3.Cài đặt biến môi trường 
- Chỉnh sửa file user.env
 ![image](https://github.com/hausura/show_read_me/blob/main/1.png)


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

     





## Introduction
- Môn: **Parallel Computing** 
- Khoa: [Khoa Toán Cơ Tin học](http://mim.hus.vnu.edu.vn/en)
- Trường: [Đại học Khoa học Tự nhiên, Đại học Quốc gia Hà Nội](http://hus.vnu.edu.vn/)

## How to set up

- a

--c



## Chạy chương trình 
Để có thể chạy được các file của repo, trước tiên bạn cần clone repo về máy tính:

```
git clone https://github.com/QuyAnh2005/Data-Structures-and-Algorithms.git
```

Để bạn đọc dễ dàng theo dõi nội dung thì khi upload lên github, mình đã thay đổi tên các package cho phù hợp. Vì thế, sau khi clone về, bạn cần đổi lại tên folder cho giống với tên package chứa trong file tương ứng của folder đó bằng cách xóa hết dấu cách, số và kí tự '-' có trong tên. Dưới đây là ví dụ:

- `1 - JavaReview` -> `JavaReview` 
- `2 - Sorting` -> `Sorting` 
- `3 - Abstract Data Type and List ADT` -> `AbstractDataTypeandListADT`
- `4 - Stack and Queue` -> `StackAndQueue`  
-  ...

Với các folder còn lại, cũng thay đổi tương tự. Sau khi các folder đã được đổi tên thì bạn mở trình biên dịch java, import các folder vừa xong như package và chạy chương trình. 

