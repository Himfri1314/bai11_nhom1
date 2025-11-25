<html lang="vi">
  <head>
    <meta charset = "UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  </head>
  <body>
     <!-- Banner -->
    <div class="banner">
        <h1 style="text-align:center;text-decorating: none; color: white; padding: 0 30px;">Bài 11: CHÈN TỆP ĐA PHƯƠNG TIỆN VÀ KHUNG NỘI TUYẾN VÀO TRANG WEB</h1>
    </div>
  </body>
    <style>
      body {
    margin: 0;
    font-family: 'Times New Roman';
    background-color: #f2f2f2;
}
      /* Banner nền ảnh */
.banner {
    width: 100%;
    height: 300px;
    background-image: url('hoa.jpg');
    background-size: cover;
    background-position: center;
    display: flex;
    justify-content: center;
    align-items: center;
}
.banner h1 {
    color: white;
    font-size: 40px;
    letter-spacing: 5px;
    font-weight: bold;
}
</style>
   <div id="wp-products">
    <h1 style="text-align:center;text-decorating: none; color: #243b9a; padding: 0 30px;">LUYỆN TẬP</h1>
  </div>
  <div style="background-color: #FFFFFF; padding: 10px;">
  		<h2>Luyện tập 1: Cho ảnh có kích thước gốc là 720x 450 Pixel chèn ảnh vào trang web bằng câu lệnh: < img src= “images/1.png” alt = “ chiếc lá” width 600>. Hỏi ảnh trong trang web có kích thước bao nhiêu?</h2> 
  </div>
  		<p>Kích thước của ảnh trong trang web sau khi chèn sẽ được xác định bởi câu lệnh <img> và thuộc tính width mà bạn đã chỉ định. Trong trường hợp này, bạn đã chỉ định width="600", nghĩa là bạn muốn ảnh có chiều rộng là 600 pixels.</p>
      <p>Tuy nhiên, do không đã chỉ định chiều cao, vì vậy trình duyệt sẽ tự động điều chỉnh chiều cao một cách tự nhiên dựa trên tỉ lệ kích thước gốc của ảnh. Vì vậy, để tính toán chiều cao của ảnh, bạn có thể sử dụng tỉ lệ giữa chiều rộng và chiều cao của ảnh gốc.</p>
      <p>Tỉ lệ giữa chiều rộng và chiều cao của ảnh gốc là: 720450450720​</p>
      <p>Vậy chiều cao của ảnh trong trang web sẽ là: 600720450=375450720​600​=375 pixels.</p>
      <p>Do đó, ảnh trong trang web sẽ có kích thước là 600 pixels chiều rộng và 375 pixels chiều cao.</p>
   <div style="background-color: #FFFFFF; padding: 10px;">
  		<h2>Luyện tập 2: Chèn thêm một số ảnh của mình vào trang web giới thiệu bản thân (em đã tạo ở phần luyện tập, Bài 10.</h2> 
  </div>
      <p>< !DOCTYPE html></p>
      <p>< html lang="en"></p>
      <p>< head></p>
      <p>< meta charset="UTF-8"></p>
      <p>< title>Giới thiệu bản thân< /title></p>
      <p>< /head></p>
      <p>< body></p>
      <p>< h1>Giới thiệu bản thân< /h1></p>
      <p>< p>Xin chào! Tôi là [Tên của bạn], đây là một trang web giới thiệu về bản thân tôi.< /p></p>
      <p>< !-- Chèn ảnh của bạn --></p>
      <p>< h2>Ảnh của tôi< /h2></p>
      <p>< img src="path_to_your_image/image1.jpg" alt="Ảnh của bạn"></p>
      <p>< img src="path_to_your_image/image2.jpg" alt="Ảnh của bạn"></p>
      <p>< img src="path_to_your_image/image3.jpg" alt="Ảnh của bạn"></p>
      <p>< !-- Bạn cùng lớp --></p>
      <p>< h2>Bạn cùng lớp< /h2></p>
      <p>< /ul></p>
      <p>< li>< ahref="https://www.facebook.com/friend1" target="_blank">Facebook của Bạn 1< /a>< /li></p>
      <p>< li>< ahref="https://www.facebook.com/friend2" target="_blank">Facebook của Bạn 2< /a>< /li></p>
      <p>< li>< ahref="https://www.facebook.com/friend3" target="_blank">Facebook của Bạn 3< /a>< /li></p>
      <p>< /ul></p>
      <p>< p>Cảm ơn bạn đã ghé thăm!< /p></p>
      <p>< /body></p>
      <p>< /html></p>
        <div id="wp-products">
    <h1 style="text-align:center;text-decorating: none; color: #243b9a; padding: 0 30px;">VẬN DỤNG</h1>
  </div>
          <div style="background-color: #FFFFFF; padding: 10px;">
        <h2>Tạo một khung nội tuyến và liên kết đến bài hát em yêu thích (ví dụ trên YouTube) vào trang web giới thiệu bản thân.</h2>
          </div>
      <p>< !DOCTYPE html></p>
      <p>< html lang="en"></p>
      <p>< head></p> 
      <p>< meta charset="UTF-8"></p>
      <p>< title>Giới thiệu bản thân< /title></p> 
      <p>< /head></p>
      <p>< body></p>
      <p>< h1>Giới thiệu bản thân< /h1></p>
      <p>< p>Xin chào! Tôi là [Tên của bạn], đây là một trang web giới thiệu về bản thân tôi.< /p></p>
      <p>< !-- Khung nội tuyến chứa video yêu thích từ YouTube --></p>
      <p>< h2>Bài hát yêu thích của tôi< /h2></p>
      <p>< iframe width="560" height="315" src="https://www.youtube.com/embed/video_id"frameborder="0" allowfullscreen>< /iframe></p>
      <p>< !-- Bạn cùng lớp --></p>
      <p>< ul></p>
      <p>< li>< ahref="https://www.facebook.com/friend1" target="_blank">Facebook của Bạn 1< /a>< /li></p>
      <p>< li>< ahref="https://www.facebook.com/friend2" target="_blank">Facebook của Bạn 2< /a>< /li></p>
      <p>< li>< ahref="https://www.facebook.com/friend3" target="_blank">Facebook của Bạn 3< /a>< /li></p>
      <p>< /ul></p>
      <p>< p>Cảm ơn bạn đã ghé thăm!< /p></p>
      <p>< /body></p>
      <p>< /html></p>
