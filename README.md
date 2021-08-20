## Đồ án cuối kỳ CyberSoft
# Đề tài: Xây dựng ứng dụng Mobile dạy học và thi trực tuyến có hỗ trợ thanh toán Paypal
### Môi trường cần cài đặt 
 - [Npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
 - [NodeJS](https://nodejs.org/en/)
 - [React Native CLI](https://reactnative.dev/docs/environment-setup)
 - [Nodemon](https://nodemon.io/)
### Ứng dụng cần cài đặt
 - [Visual Studio](https://visualstudio.microsoft.com/downloads/)
 - [MS SQLServer](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
 - [Android Studio](https://developer.android.com/studio)
 - [Code Editor(Visual Studio Code,Notepad++,Sublime Text,etc)](https://codelearn.io/sharing/top-10-code-editor-chat-cho-coder-nam-2020)
### Lưu ý cài đặt
 - Cần cài đặt **Nodejs** và **npm** đầu tiên để install các package cho project, kiểm tra lần lượt các dịch vụ này thông qua các lệnh ```node -v```, ```npm -v``` tại cửa sổ command prompt (hoặc PowerShell)
 - Với các project Angular và React Native khi mở lần đầu tiên cần sử dụng lệnh ```npm install``` để đảm bảo cài đặt đầy đủ dependencies, kiểm tra xem file nodemodule đã tồn tại hay chưa
 - Backend cần chú ý thay đổi tại file **appsettings.json**: ```"ConnectionStrings": {
    "DatabaseConnection": "Server=(localhost);Database=CourseDB3;Trusted_Connection=True;MultipleActiveResultSets=True;"
  }```
 với Server là tên Server name tại SSMS, thực hiện lệnh ```EntityFrameworkCore\Add-Migration``` và ```EntityFrameworkCore\Update-Database``` tại cửa sổ Package Manager Console để cập nhật cơ sở dữ liệu.
 
