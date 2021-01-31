
#### Bước 1: Tải Ubuntu của Microsoft Store và cài đặt <br>
https://ubuntu.com/wsl <br>
Để tìm thư mục chính trên Windows Subsystem của Linux: \\\wsl$\Ubuntu\home <br>
#### Bước 2: Cài đặt OpenJDK và Apache Maven trên Ubuntu <br>
**Cài đặt Apache Maven trên Ubuntu**
  Bước 1: Cập nhật package <br>
  ```
  $ sudo apt update
  ```
  Bước 2: Cài đặt <br>
  ```
  $ sudo apt install maven
  ```
  Bước 3: Kiểm tra <br>
  ```
  $ mvn -version
  ```

#### Bước 3: Tải file: apache-pinot-incubating-0.6.0-bin.tar <br>
http://pinot.apache.org/download <br>
#### Bước 4: Giải nén file  apache-pinot-incubating-0.6.0-bin.tar và di chuyển đến thư mục chính trên Windows Subsystem của Linux <br>
#### Bước 5: Chạy Pinot sử dụng Ubuntu của Microsoft Store <br>
https://docs.pinot.apache.org/basics/getting-started/running-pinot-locally <br>


