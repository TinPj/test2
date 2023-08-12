<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <link rel="stylesheet" href="./style.css" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link
      rel="stylesheet"
      href="./fontawesome-free-6.4.0-web/css/all.min.css"
    />
    <link
      rel="shortcut icon"
      href="./images/logosapo.webp"
      type="image/x-icon"
    />
  </head>
  <body>
    <header class="header">
      <div class="header_TopBar" style="width: 100%">
        <div class="header_TopBar_Container">
          <div class="header_TopBar_Container_Logo">
            <a href="/">
              <img src="./images/logo.webp" alt="" />
            </a>
          </div>
          <div class="header_TopBar_Container_Search">
            <form action="">
              <div class="search-Item header_TopBar_Container_Search-text">
                Tất cả
              </div>
              <div
                class="search-Item header_TopBar_Container_Search-input"
                style="width: 100%"
              >
                <input type="text" placeholder="Tìm sản phẩm bạn mong muốn" />
              </div>
              <div class="search-Item header_TopBar_Container_Search-icon">
                <i class="fa-solid fa-magnifying-glass"></i>
              </div>
            </form>
          </div>
          <div class="header_TopBar_Container_User">
            <div class="header_TopBar_Container_User_Account">
              <a href="#"><i class="fa-solid fa-user"></i></a>
              <a href="/login">Đăng Nhập</a>
              <span style="color: aliceblue; margin: 0 3px; font-size: 18px"
                >/</span
              >
              <a href="/resign">Đăng Ký</a>
            </div>
            <div
              style="
                width: 1px;
                height: 24px;
                background-color: #fff;
                margin: -5px 30px;
              "
            ></div>
            <div class="header_TopBar_Container_User-LogoCart">
              <a href="/cart">
                <i class="fa-sharp fa-solid fa-cart-shopping"></i>
              </a>
            </div>
          </div>
        </div>
      </div>
    </header>
    <div class="headerMenu">
      <div class="headerMenu_container" style="width: 75%; line-height: 60px">
        <div class="headerMenu_container_Menu">
          <ul>
            <li class="headerMenu_container_Menu--item activate">
              <a class="" href="/">Trang Chủ</a>
            </li>
            <li class="headerMenu_container_Menu--item">
              <a href="#">Thời trang nam</a>
            </li>
            <li class="headerMenu_container_Menu--item">
              <a href="#">Sản phẩm</a>
            </li>
            <li class="headerMenu_container_Menu--item">
              <a href="#">Bé trai</a>
            </li>
            <li class="headerMenu_container_Menu--item">
              <a href="#">Bé gái</a>
            </li>
            <li class="headerMenu_container_Menu--item">
              <a href="#">Tin tức</a>
            </li>
            <li class="headerMenu_container_Menu--item">
              <a href="#">Liên hệ</a>
            </li>
          </ul>
        </div>
        <div class="headerMenu_container_Hotline">
          <label for="">Hotline :</label>
          <a href="tel:19006750">1900 6750</a>
        </div>
      </div>
    </div>
    <div class="bodywrap">
      <div class="bodywrap_container" style="width: 100%">
        <img style="width: 100%" src="./images/slider_1.webp" alt="alena" />
      </div>
    </div>
    <section
      class="service"
      style="background-color: #fe9614; margin-top: -5px"
    >
      <div class="container_service">
        <div class="container_service--item">
          <img src="./images/ship.webp" alt="" />
          <h3>Miễn Phí Giao Hàng</h3>
          <p style="color: #fff">Miễn phí ship với đơn hàng > 498k</p>
        </div>
        <div class="container_service--item">
          <img src="./images/thanhtoan.webp" alt="" />
          <h3>Miễn Phí Giao Hàng</h3>
          <p style="color: #fff">Miễn phí ship với đơn hàng > 498k</p>
        </div>
        <div class="container_service--item">
          <img src="./images/vip.webp" alt="" />
          <h3>Miễn Phí Giao Hàng</h3>
          <p style="color: #fff">Miễn phí ship với đơn hàng > 498k</p>
        </div>
        <div class="container_service--item">
          <img src="./images/baohanh.webp" alt="" />
          <h3>Miễn Phí Giao Hàng</h3>
          <p style="color: #fff">Miễn phí ship với đơn hàng > 498k</p>
        </div>
      </div>
    </section>
    <section class="product_hot" style="background-color: #FFFAF0;">
      <div class="container_product_hot">
        <div style="display: flex; justify-content: space-between">
          <div class="product_hot-title">
            <h1>SẢN PHẨM HOT</h1>
          </div>
          <div class="product_hot_menu">
            <ul>
              <i class="fa-solid fa-arrow-left"></i>
              <li class="hot_activate">Quần áo</li>
              <li>Phụ kiện</li>
              <li>Giày dép</li>
              <li>Bé gái</li>
              <li>Bé trai</li>
              <i class="fa-sharp fa-solid fa-arrow-right"></i>
            </ul>
          </div>
        </div>
        <div class="list_product_hot" id="list_product_hot">
          
          </div>
          <div class="a_product_hot">
            <a href="/quan-ao">Xem tất cả</a>
          </div>
        </div>
      </div>
    </section>
    <section class="product_hot" style="background-color: #FFFAF0;">
    <div class="container_product_hot">
        <div style="display: flex; justify-content: space-between">
          <div class="product_hot-title">
            <h1>SẢN PHẨM MỚI</h1>
          </div>
          <div class="product_hot_menu">
            <ul>
              <i class="fa-solid fa-arrow-left"></i>
              <li class="hot_activate">Quần áo</li>
              <li>Phụ kiện</li>
              <li>Giày dép</li>
              <li>Bé gái</li>
              <li>Bé trai</li>
              <i class="fa-sharp fa-solid fa-arrow-right"></i>
            </ul>
          </div>
        </div>
        <div>
          <img src="./images/logoSanPhamMoi.webp" alt="" style="width: 445px;height: 100%;border-radius: 10px;">
        </div>
        <div class="list_product_hot" id="list_product_hot">
          
          </div>
          <div class="a_product_hot">
            <a href="/quan-ao">Xem tất cả</a>
          </div>
        </div>
      </div>
    </section>
    <script src="./main.js">
    </script>
  </body>
</html>
