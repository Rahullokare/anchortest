<template>
  <div class="container-fluid">
    <div class="top__header bg-dark d-flex justify-content-end">
      <div class="right__navigation">
        <a href="#">Home</a>
        <a href="#">Help</a>
        <a href="#">Teach</a>
        <a href="#">Login</a>
        <button class="btn btn-primary">Join for Free</button>
      </div>
    </div>
    <div class="sujession__bar p-2 d-flex justify-content-between">
      <a href="#">Graphic And Design</a>
      <a href="#">Digital Marketing</a>
      <a href="#">Music And Video</a>
      <a href="#">Writing and Translation</a>
      <a href="#">Music and Videos</a>
      <a href="#">Programming</a>
      <a href="#">Tech</a>
    </div>
    <hr />
    <div
      class="search__bar p-1 d-flex align-items-center justify-content-between"
    >
      <div class="search__bar--left">
        <a href="#">Overview</a>
        <a href="#">Description</a>
        <a href="#">About the Seller</a>
        <a href="#">Compare Packages</a>
        <a href="#">Reviews</a>
      </div>
      <div class="search__bar--center">
        <i class="fas fa-search"></i>
        <input
          type="text"
          placeholder="Find Services"
          class="search__bar--input"
        />
        <button class="search__bar--btn">Search</button>
      </div>
      <div class="search__bar--right"></div>
    </div>
    <hr />
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.container-fluid {
  margin: 0;
  padding: 0;
}
.top__header {
  padding: 0.75rem 0 0.75rem 0 !important;
}
hr {
  margin: 0;
  padding: 0;
}
.right__navigation {
  margin-right: 65px;
}
.right__navigation > a {
  text-decoration: none;
  color: white;
  margin-right: 25px;
}
.sujession__bar {
  margin-left: 45px;
  /* border-bottom: 1px solid #62646a; */
}
.sujession__bar > a {
  text-decoration: none;
  color: #62646a;
  font-size: 18px;
}
.sujession__bar > a:last-child {
  margin-right: 2rem;
}
/* SEARCH BAR */

.search__bar {
  /* background-color: rgb(218, 218, 218); */
}
.search__bar--left > a {
  margin-left: 45px;
  text-decoration: none;
  color: #62646a;
}
.search__bar--left > a:not(:first-child) {
  margin-left: 1rem;
}
.search__bar--center {
  background-color: white;
  margin-left: 1.5rem;
  padding: 5px 5px 5px 10px;
  display: flex;
  align-items: center;
  border: 1px solid rgb(114, 113, 113);
}
.search__bar--center > i {
  color: #62646a;
  font-size: 16px;
}
.search__bar--input {
  border: none;
  padding: 4px;
  outline: none;
}
.search__bar--btn {
  background-color: #1dbf73;
  color: white;
  padding: 5px 10px 5px 10px;
  font-weight: bold;
  border: none;
  outline: none;
}
/* SEARCH BAR RIGHT */
.search__bar--right {
  margin-right: 20px;
}
</style>
