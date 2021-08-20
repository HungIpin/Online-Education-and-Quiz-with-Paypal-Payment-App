## Đồ án cuối kỳ CyberSoft
# Đề tài: Xây dựng ứng dụng Mobile dạy học và thi trực tuyến có hỗ trợ thanh toán Paypal
### Các công nghệ và bên thứ 3:
 <img src="https://img.stackshare.io/service/11331/asp.net-core.png"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRPw7e1oXI5SnkykpcQkyJR2ymbSMs0XS4dDuZojsvzV0rNP6k6nLkrLpMD0PMXVltIMxk&usqp=CAU"><img src="https://blog.sqlauthority.com/wp-content/uploads/2008/12/ssms.png">
 <img src="https://cdn.tgdd.vn/Files/2019/07/16/1179841/636629240000820088-760x367.jpg">
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
## Em xin cảm ơn trung tâm CyberSoft, đặc biệt là anh Đạt đã nhiệt tình hỗ trợ lúc em gặp khó khăn. Đây là project em làm từ không biết gì đến khi có thành phẩm và đã bảo vệ thành công ở trường( mục tiêu ban đầu khi đăng ký học ở trung tâm)
 
