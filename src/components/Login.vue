<template>
    <div class="login-container">
      <div class="login-box">
        <div class="avatar-box">
          <img src="../assets/img/logo.png" alt="" />
        </div>
      </div>
    </div>
</template>

<script>
export default {
}
</script>

<style lang="less" scoped>
.login-container{
  height:100%;
  background-color: #2b4b6b;
  overflow: hidden;
  .login-box{
    width:450px;
    height:304px;
    background-color:#fff;
    border-radius: 4px;
    position:absolute;
    left:50%;
    top:50%;
    transform: translate(-50%,-50%);
    .avatar-box{
      width:130px;
      height:130px;
      border:1px solid #eee;
      border-radius: 50%;
      padding:8px;
      box-shadow: 0 0 10px #eee;
      position:absolute;
      left:50%;
      transform: translate(-50%,-50%);
      background-color:#fff;
      img{
        width:100%; height:100%;
        border-radius: 50%;
        background-color:#eee;
      }
    }
  }
}
</style>
