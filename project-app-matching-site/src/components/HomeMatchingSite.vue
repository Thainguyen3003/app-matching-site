<template>
  <body>
    <div class="app">
      <header class="header">
        <div class="top-nav">
          <ul class="header__navbar-list">
            <li class="header__navbar-item"><a href="#" class="header__navbar-item-link">Tinder</a></li>
            <li class="header__navbar-item">
              <a href="#" class="header__navbar-item-link">Sản phẩm</a>
              <ul class="sub-nav">
                <li><a href="#" class="header__navbar-item-link">Tính năng cao cấp</a></li>
                <li><a href="#" class="header__navbar-item-link">Gói Thuê bao đăng kí</a></li>
                <li><a href="#" class="header__navbar-item-link">Tinder Plus</a></li>
                <li><a href="#" class="header__navbar-item-link">Tinder Gold</a></li>
                <li><a href="#" class="header__navbar-item-link">Tinder Platinum</a></li>
              </ul>
            </li>
            <li class="header__navbar-item"><a href="#" class="header__navbar-item-link">Tìm hiểu</a></li>
            <li class="header__navbar-item">
              <a href="#" class="header__navbar-item-link">An toàn</a>
              <ul class="sub-nav">
                <li><a href="#" class="header__navbar-item-link">Quy tắc cộng đồng</a></li>
                <li><a href="#" class="header__navbar-item-link">Một vài lời khuyên về an toàn</a></li>
                <li><a href="#" class="header__navbar-item-link">An toàn và chính sách</a></li>
                <li><a href="#" class="header__navbar-item-link">An toàn và trình báo</a></li>
                <li><a href="#" class="header__navbar-item-link">Bảo mật</a></li>
              </ul>
            </li>
            <li class="header__navbar-item"><a href="#" class="header__navbar-item-link">Hỗ trợ</a></li>
          </ul>

          <ul class="header__navbar-list">
            <li>
              Ngôn ngữ
            </li>
            <li>
              Đăng nhập
            </li>
          </ul>
          
        </div>
      </header>
      <div class="background-header"></div>
    </div>
  </body>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.header {
  width: 100%;
  height: 86.15px;
}

.top-nav {
  height: 100%;
  display: flex;
  justify-content: space-between;
}

.header__navbar-list {
  list-style: none;
  padding-left: 0;
  display: flex;

}

.header__navbar-item {
  text-align: left;
  margin-right: 40px;
  font-size: 20px;
}

.sub-nav {
  list-style: none;
  padding-left: 0;
}

.header__navbar-item-link {
  text-decoration: none;
}
</style>
