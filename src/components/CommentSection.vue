<template>
  <div class="comment__section mt-4">
    <img
      class="comment__user rounded-circle"
      src="../assets/slider-img.png"
      alt=""
    />
    <div class="comment__info">
      <p class="user__name">crowdpoint</p>
      <div class="user__state d-flex mt-1">
        <img src="../assets/stateFlag.png" alt="" />
        <span class="ml-2">United State</span>
      </div>
      <p class="mt-3">Very fast development and very professional</p>
      <div class="profile__user d-flex mt-2">
        <img src="../assets/replyUser.png" alt="" />
        <div class="profile__userinfo mt-1 ms-3">
          <p class="user__name">Elizabeth Keen</p>
          <p class="mt-2">India</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.comment__section {
  margin-left: 48px;
  padding-top: 25px;
  border-top: 1.2px solid #979393;
  display: flex;
}
.comment__user {
  width: 32px;
  height: 32px;
}
.comment__info {
  margin-left: 15px;
  margin-top: 4px;
}
.user__name {
  margin: 0;
  padding: 0;
  font-weight: 700;
  font-size: 16px;
}
.user__state {
  align-items: center;
}
.user__state > span {
  color: #62646a;
  font-size: 14px;
}
.user__state > img {
  width: 20px;
  height: 20px;
}
.profile__user > img {
  width: 32px;
  height: 32px;
  border-radius: 50px;
}
</style>
