<template>
  <div class="footer-container">
    <p>© 1998–2018 DRA.io</p>
    <div class="footer-name">
      <ul>
        <li><a href="#">Showcase</a></li>
        <li><a href="#">Develope</a></li>
        <li><a href="#">Tutorial</a></li>
        <li><a href="#">Get Involved</a></li>
        <li><a href="#">Docs</a></li>
      </ul>
    </div>
  </div>
</template>

<style>
.footer-container {
  background-color: #2b3741;
  height: 100px;
  display: flex;
  align-items: center;
  width: 100%;
  justify-content: space-between;
}
.footer-container p {
  color: #fff;
  padding-left: 20px;
}
.footer-container .footer-name ul {
  list-style-type: none;
  display: flex;
}
.footer-container .footer-name ul li a {
  color: #fff;
  padding-left: 20px;
  padding-right: 20px;
  text-decoration: none;
}
</style>
