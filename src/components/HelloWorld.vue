<template>
  <div>
    <h1>이것은 메뉴입니다.</h1>
    <ul>
      <li>첫화면</li>
      <li>소개</li>
      <li>게시판</li>
      <li>문의</li>
    </ul>
  </div>
</template>

<script>

export default {
  prompt : {
    abc : String,
  }
}
</script>

<style>
  *{
    margin: 0;
    padding: 0;
    text-align: center;
  }
  div{
    margin: 20px;
  }
  ul > li{
    float: left;
    margin: 30px 30px 30px 30px;
  }
</style>