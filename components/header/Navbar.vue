<template>
  <div class="header-container">
    <img
      src="../../assets/images/Logo.png"
      alt="Logo-Company"
      class="image"/>
    <div class="menu-container">
      <ul>
        <li><a href="#">Showcase</a></li>
        <li><a href="#">Develope</a></li>
        <li><a href="#">Tutorial</a></li>
        <li><a href="#">Get Involved</a></li>
        <li><a href="#">Docs</a></li>
        <li class="button-start"><a href="#">Getting started</a></li>
      </ul>
    </div>
  </div>
</template>

<style>
.header-container {
  background-color: #2b3741;
  height: 50px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 100%;
}
.header-container .image {
  width: 150px;
  height: 40px;
  padding-left: 10px;
}
.header-container .menu-container ul {
  display: flex;
}
.header-container .menu-container ul li {
  list-style-type: none;
  padding: 0 10px;
  border: 1px solid grey;
  height: 50px;
  align-items: center;
}
.header-container .menu-container ul li a {
  color: #fff;
  text-decoration: none;
  font-size: 15px;
  padding-top: 25px;
  line-height: 50px;
}
.header-container .menu-container ul .button-start {
  background-color: #0080ff;
}
</style>
