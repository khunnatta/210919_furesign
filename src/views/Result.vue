<template>
  <div class="resultList">
    <div class="container">
      <img src="../assets/item0.jpeg" alt="item0" />
      <div class="container__text">
        <h1 style="margin-top: 10px">ชื่อสินค้า</h1>
        <h1>ชื่อร้านค้า</h1>
        <h1>ราคา</h1>
        <div class="container__text__star">
          <span class="fa fa-star checked"></span>
          <span class="fa fa-star checked"></span>
          <span class="fa fa-star checked"></span>
          <span class="fa fa-star checked"></span>
          <span class="fa fa-star unchecked"></span>
        </div>
        <hr />
        <p>
          Lorem ipsum dolor sit, amet consectetur adipisicing elit. Earum
          voluptates voluptatem unde qui debitis obcaecati dolorum, libero
          dolorem officia quo accusamus sunt possimus quos reiciendis. Quo eum
          laboriosam deleniti totam.
        </p>
        <button class="btn">
          Go Shopping <i class="fa fa-arrow-right"></i>
        </button>
      </div>
    </div>
    <div class="container">
      <img src="../assets/item0.jpeg" alt="item0" />
      <div class="container__text">
        <h1 style="margin-top: 10px">ชื่อสินค้า</h1>
        <h1>ชื่อร้านค้า</h1>
        <h1>ราคา</h1>
        <div class="container__text__star">
          <span class="fa fa-star checked"></span>
          <span class="fa fa-star checked"></span>
          <span class="fa fa-star checked"></span>
          <span class="fa fa-star checked"></span>
          <span class="fa fa-star unchecked"></span>
        </div>
        <hr />
        <p>
          Lorem ipsum dolor sit, amet consectetur adipisicing elit. Earum
          voluptates voluptatem unde qui debitis obcaecati dolorum, libero
          dolorem officia quo accusamus sunt possimus quos reiciendis. Quo eum
          laboriosam deleniti totam.
        </p>
        <button class="btn">
          Go Shopping <i class="fa fa-arrow-right"></i>
        </button>
      </div>
    </div>
    <div class="container">
      <img src="../assets/item0.jpeg" alt="item0" />
      <div class="container__text">
        <h1 style="margin-top: 10px">ชื่อสินค้า</h1>
        <h1>ชื่อร้านค้า</h1>
        <h1>ราคา</h1>
        <div class="container__text__star">
          <span class="fa fa-star checked"></span>
          <span class="fa fa-star checked"></span>
          <span class="fa fa-star checked"></span>
          <span class="fa fa-star checked"></span>
          <span class="fa fa-star unchecked"></span>
        </div>
        <hr />
        <p>
          Lorem ipsum dolor sit, amet consectetur adipisicing elit. Earum
          voluptates voluptatem unde qui debitis obcaecati dolorum, libero
          dolorem officia quo accusamus sunt possimus quos reiciendis. Quo eum
          laboriosam deleniti totam.
        </p>
        <button class="btn">
          Go Shopping <i class="fa fa-arrow-right"></i>
        </button>
      </div>
    </div>
    <div class="container">
      <img src="../assets/item0.jpeg" alt="item0" />
      <div class="container__text">
        <h1 style="margin-top: 10px">ชื่อสินค้า</h1>
        <h1>ชื่อร้านค้า</h1>
        <h1>ราคา</h1>
        <div class="container__text__star">
          <span class="fa fa-star checked"></span>
          <span class="fa fa-star checked"></span>
          <span class="fa fa-star checked"></span>
          <span class="fa fa-star checked"></span>
          <span class="fa fa-star unchecked"></span>
        </div>
        <hr />
        <p>
          Lorem ipsum dolor sit, amet consectetur adipisicing elit. Earum
          voluptates voluptatem unde qui debitis obcaecati dolorum, libero
          dolorem officia quo accusamus sunt possimus quos reiciendis. Quo eum
          laboriosam deleniti totam.
        </p>
        <button class="btn">
          Go Shopping <i class="fa fa-arrow-right"></i>
        </button>
      </div>
    </div>
    <div class="container">
      <img src="../assets/item0.jpeg" alt="item0" />
      <div class="container__text">
        <h1 style="margin-top: 10px">ชื่อสินค้า</h1>
        <h1>ชื่อร้านค้า</h1>
        <h1>ราคา</h1>
        <div class="container__text__star">
          <span class="fa fa-star checked"></span>
          <span class="fa fa-star checked"></span>
          <span class="fa fa-star checked"></span>
          <span class="fa fa-star checked"></span>
          <span class="fa fa-star unchecked"></span>
        </div>
        <hr />
        <p>
          Lorem ipsum dolor sit, amet consectetur adipisicing elit. Earum
          voluptates voluptatem unde qui debitis obcaecati dolorum, libero
          dolorem officia quo accusamus sunt possimus quos reiciendis. Quo eum
          laboriosam deleniti totam.
        </p>
        <button class="btn">
          Go Shopping <i class="fa fa-arrow-right"></i>
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "result",
};
</script>

<style scoped>
.resultList {
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  align-content: center;
  justify-content: center;
  padding-left: 3.5vw;
  padding-right: 3.5vw;
  margin: 1vw 1.5vw;
  font-family: "Prompt", sans-serif;
}

.container {
  background-color: whitesmoke;
  display: grid;
  grid-template-columns: min(20vw, 350px) auto 10vw;
  border-radius: 5px;
  box-shadow: 0 15px 20px rgba(0, 0, 0, 0.356);
  margin-bottom: 2.5vh;
}
img {
  width: min(17.5vw, 320px);
  height: min(17.5vw, 320px);
  border-radius: 5px 0 0 5px;
}

.btn {
  position: absolute;
  bottom: -30px;
  right: 30px;
  border: none;
  outline: none;
  display: flex;
  align-items: center;
  background-color: #fc9400;
  color: whitesmoke;
  padding: 22px 45px;
  font-size: 1rem;
  text-transform: uppercase;
  border-radius: 5px;
  cursor: pointer;
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.294);
}

.btn i {
  margin-left: 20px;
  font-size: 1.5rem;
}

.container__text {
  padding: 0px 0px 0;
  text-align: left;
  margin-left: 5px;
}
.container__text h1 {
  color: #351897;
  font-weight: 400;
  margin: 0 0 0 0;
  font-size: max(1.5vw, 12px);
  color: #a26854;
}

.container__text__star span {
  font-size: 0.8rem;
  color: #ffa800;
  margin: -5px 0 5px;
}

p {
  font-size: 0.9rem;
}

.container__text__timing {
  display: flex;
  margin: 20px 0 10px;
}
.container__text__timing_time {
  margin-right: 40px;
}
h2 {
  margin-bottom: 5px;
  font-size: 1rem;
  color: #818189;
}
p {
  color: rgb(127, 127, 127);
  font-size: max(1.25vw, 10px);
  margin: 2.5px 0 0 0;
}
</style>

