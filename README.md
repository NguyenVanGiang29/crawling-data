HƯỚNG DẪN CÀI ĐẶT VÀ SỬ DỤNG CRAWLING DATA TỪ FACEBOOK

**CÀI ĐẶT**

B1: Pull Repositories Crawling-data

B2: Cài đặt môi trường lập trình python (Nếu cài python rồi thì bỏ qua bước này)
1. Cài Python trên window
  - Bạn hãy vào trang https://www.python.org/downloads/ để download phiên bản Python mà bạn muốn cài. Các bạn sử dụng Python phiên bản mới nhất.
2. Cài Python trên linux
  -  Thực hiện theo các thứ tự sau:
      sudo apt-get update
      sudo apt-get -y upgrade
      sudo apt-get install -y python3-pip
      sudo apt-get install build-essential libssl-dev libffi-dev python-dev
- Sau khi cài xong, để kiểm tra xem trong máy mình đã cài thành công chưa thực hiện lệnh:
      python -V
 
 B3: Cài đặt môi trường sử dụng Selenium
- Selenium là một trình duyệt cho phép bạn thực hiện các công việc tự động hóa ở trên đó. Hầu hết các thao tác trên trình duyệt mà bạn làm được thì Selenium đều có thể làm được và cho phép bạn dùng code để điều khiển trình duyệt này.
Đây là trang chủ của Selenium: https://www.seleniumhq.org/
- Cài đặt Selenium với Python
Cài đặt Selenium với ngôn ngữ Python chạy command sau:
      pip install selenium
- Tải selenium WebDriver: Có rất nhiều loại WebDriver với các trình duyệt khác nhau: FireFox, Chrome,...
Các bạn tải WebDriver với trình duyệt bạn hay sử dụng, ở đây mình dùng Webdriver Chrome.
  B1: Các bạn vào https://chromedriver.chromium.org/downloads. Tải phiên bản tương ứng với phiên bản Chrome hiện tại bạn đang dùng.
  B2: Giải nén file. Copy file chromedrive.exe
  B3: Tạo một thư mục trong ổ đĩa bất kỳ đặt tên: ChromeDriver -> Paste file chromedrive.exe vào trong thư mục -> Copy đường đường dẫn (1)  file vừa được paste vào 
  B4: Cài property trong Environment Variable
    + Tìm kiếm mục và chọn
    
      ![image](https://user-images.githubusercontent.com/58686853/154920441-2385f35c-07f8-4414-9129-67176a69844b.png)
    + Tìm và chọn:
    
      ![image](https://user-images.githubusercontent.com/58686853/154920724-ee33737c-bd2c-4422-aa4d-1ca68db0698e.png)
    + Tìm và chọn:
    
      ![image](https://user-images.githubusercontent.com/58686853/154921211-002e829f-0b81-4c97-86f3-6820e214fab1.png)
    + Tìm và chọn:
    
      ![image](https://user-images.githubusercontent.com/58686853/154921427-c4845518-df11-4b33-9f1d-ff6f1b7fe4f4.png)
    + Paste đường dẫn (1) vào trong và chọn Ok:
    
      ![image](https://user-images.githubusercontent.com/58686853/154921955-79b72bde-7af9-40eb-8496-ec5ba3e23809.png)

Hoàn thành xong toàn bộ việc cài đặt

**SỬ DỤNG**
Bật chương code và chạy thư file crawler.py bằng lệch: 
  **python crawler.py**




