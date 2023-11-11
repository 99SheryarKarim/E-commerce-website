<template>
  <div>
    <div class="header-1">
      <a href="">
        <div class="icon"><img src="public/person.svg" alt="" /></div>
        <p>My profile</p>
      </a>
      <a href="">
        <div class="icon"><img src="public/shope.svg" alt="" /></div>
        <p>Items</p>
      </a>
      <a href="">
        <div class="icon"><img src="public/search.svg" alt="" /></div>
        <p>0.00$</p>
      </a>
    </div>
    <div class="header-2">
      <div class="header-prt1">
        <img src="public/FOOTER.png" alt="" />
      </div>

      <div class="header-list">
        <a id="home" href="">Home</a>
        <a href="components/Bags.vue">Bags</a>
        <a href="">phone</a>
        <a href="">Sneakers</a>
        <a href="">ContactUs</a>
      </div>
    </div>

    <section class="main">
      <img id="img1" src="public/Group 525.png" alt="" />
      <img id="img2" src="public/Group 526.png" alt="" />
      <img id="img3" src="public/Group 525.png" alt="" />
    </section>
    <section class="sneaker">
      <div class="sneaker-heading">
        <H2>Best Seller</H2>
        <p>
          "Elevate your style with our premium sneakers. Quality, comfort, and
          fashion meet in every step. Explore our curated collection today."
        </p>
      </div>
      <div class="sneaker-row1">
        <div class="first">
          <img src="public/Group 543.png" alt="" />
        </div>
        <div class="second">
          <img src="public/Group 542.png" alt="" />
        </div>
        <div class="third">
          <img src="public/Group 544.png" alt="" />
        </div>
        <div class="fourth">
          <img src="public/Group 545.png" alt="" />
        </div>
      </div>

      <div class="sneaker-row2">
        <div class="firsts">
          <img src="public/Group 544.png" alt="" />
        </div>
        <div class="seconds">
          <img src="public/Group 542.png" alt="" />
        </div>
        <div class="thirds">
          <img src="public/Group 543.png" alt="" />
        </div>
        <div class="fourths">
          <img src="public/Group 545.png" alt="" />
        </div>
      </div>
    </section>
    <section class="Addidas">
      <div class="addidas-prt1">
        <h1>
          Addidas Men Running <br />
          Sneakers
        </h1>
        <p>Performance and design. Taken right to the edge.</p>
        <a href="">Shop now</a>
      </div>
      <div class="addidas-prt2">
        <img style="margin: 60px" src="public/blue-shoe.png" alt="" />
      </div>
    </section>

    <section class="whyus">
      <div class="whyus-1">
        <img src="public/Group 13.png" alt="" />
        <p>
          Lorem Ipsum is simply <br />
          dummy text of the <br />
          printing and typesetting <br />
          industry.
        </p>
      </div>
      <div class="whyus-2">
        <img src="public/Group 14.png" alt="" />
        <p>
          Lorem Ipsum is simply <br />
          dummy text of the <br />
          printing and typesetting <br />
          industry.
        </p>
      </div>
      <div class="whyus-2">
        <img src="public/Group 15.png" alt="" />
        <p>
          Lorem Ipsum is simply <br />
          dummy text of the <br />
          printing and typesetting <br />
          industry.
        </p>
      </div>
    </section>
    <section class="latestnews">
      <div class="news-header">
        <h1>LATEST NEWS</h1>
      </div>

      <div class="news-parent">
        <div class="news-prt1">
          <h1>FASHION INDUSTRY</h1>
          <img src="public/Group 530.png" alt="" />
        </div>
        <div class="news-prt2">
          <h1>Best Design Tools</h1>
          <img src="public/Group 534.png" alt="" />
        </div>
        <div class="news-prt3">
          <h1>HR Community</h1>
          <div class="prt3-imgs">
            <img id="imgkrono" src="public/Group 541.png" alt="" />
            <img id="img2" src="public/Group 535.png" alt="" />
          </div>
        </div>
      </div>
    </section>
    <section class="featured">
      <div class="featured-1">
        <img src="public/shoe-text.png" alt="" />
      </div>
      <div class="featured-2">
        <img src="public/shoe-text.png" alt="" />
      </div>
      <div class="featured-3">
        <img src="public/shoe-text.png" alt="" />
      </div>
    </section>
    <div class="search-container">
      <input type="text" class="search-input" placeholder="Search..." />
      <button class="search-button">Search</button>
    </div>
    <section class="footer">
      <div class="footer-1">
        <img src="public/Group 551.png" alt="" />
      </div>
      <div class="footer-2">
        <img src="public/Group 547.png" alt="" />
      </div>
      <div class="footer-3">
        <img src="public/Group 485.png" alt="" />
      </div>
    </section>
  </div>
</template>
  
  <style scoped>
.header-1 {
  width: 100%;
  height: 7vh;
  display: flex;
  justify-content: flex-end;
  gap: 40px;
  background-color: whitesmoke;
  margin-right: 20px;
}

.header-1 a {
  display: flex;
  align-items: center;
  text-decoration: none;
  font-size: 12px;
  text-decoration: none;
}
.header-1 img {
  width: 17px;
  height: 17px;
}

.icon {
  margin-right: 8px; /* Adjust the spacing between the icon and text */
}

.icon img {
  width: 30px;
}
.header-2 {
  width: 100%;
  height: 12vh;
  list-style: none;

  display: flex;
}
.header-list {
  width: 60%;
  list-style: none;
  display: flex;

  justify-content: center;
  align-items: center;
  gap: 60px;
}
.header-list a {
  font-size: 18px;
  text-decoration: none;
  font-family: "Trebuchet MS", "Lucida Sans Unicode", "Lucida Grande",
    "Lucida Sans", Arial, sans-serif;
  font-size: 17px;
  color: black;
}
.header-list a:hover {
  color: rgb(230, 12, 12);
}
.header-prt1 {
  width: 40%;
}
.header-prt1 img {
  margin: 15px;
}
/* main */
.main {
  width: 100%;
  height: 90vh;
  background: url("public/Offer Banner.png") no-repeat center center/cover;
  display: flex;
}
.main img {
  width: 300px;
  height: 300px;
  position: relative;
  top: 400px;
  left: 200px;
  display: flex;
  gap: 20px;
}

/* sneaker-section */
.sneaker {
  width: 100%;
  height: 150vh;
  background-color: rgb(245, 242, 238);
}
.sneaker-heading {
  width: 100%;
  height: 20vh;
  /* border: 1px solid red; */
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  position: relative;
  top: 140px;
  line-height: 8px;
  font-family: "Trebuchet MS", "Lucida Sans Unicode", "Lucida Grande",
    "Lucida Sans", Arial, sans-serif;
}
.Addidas {
  width: 100%;
  height: 70vh;
  display: flex;
  background: #40bfff;
}
.addidas-prt1 {
  /* border: 1px solid red;s */
  width: 50%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  font-family: "Trebuchet MS", "Lucida Sans Unicode", "Lucida Grande",
    "Lucida Sans", Arial, sans-serif;
  height: 70vh;
}
.addidas-prt2 {
  /* border: 1px solid red; */
  width: 50%;
  height: 70vh;
}
.addidas-prt1 h1 {
  color: white;

  font-size: 40px;
}
.addidas-prt1 p {
  color: white;

  font-size: 16px;
}
.addidas-prt1 a {
  color: white;
}
.addidas-prt1 h1 {
  display: flex;
  text-align: center;
}
.whyus {
  width: 100%;
  display: flex;
  height: 70vh;
  /* border: 1px solid red; */
}
.whyus-1 {
  width: 34%;
  height: 70vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  /* border: 1px solid red; */
}
.whyus-2 {
  width: 33%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 70vh;
  /* border: 1px solid red; */
}
.whyus-3 {
  width: 33%;
  height: 70vh;
  border: 1px solid rgb(54, 164, 74);
}
.whyus p {
  text-align: center;
  color: rgb(63, 89, 49);
}

.sneaker-row1 {
  display: flex;
  justify-content: center;
  align-items: center;
}

.sneaker-row1 img {
  width: 280px;
  height: 300px;
  transition: opacity 0.3s ease-in-out; /* Add transition property for opacity */
}

.sneaker-row1 img:hover {
  opacity: 0.7; /* Change the opacity on hover */
}
.sneaker-row2 img {
  width: 280px;
  height: 300px;
  transition: opacity 0.3s ease-in-out; /* Add transition property for opacity */
}

.sneaker-row2 img:hover {
  opacity: 0.7; /* Change the opacity on hover */
}
.sneaker-row1 img {
  width: 280px;
  height: 300px;
  transition: transform 0.3s ease-in-out, opacity 0.3s ease-in-out; /* Add transition properties for transform and opacity */
}

.sneaker-row1 img:hover {
  transform: scale(1.1); /* Apply a scale transform on hover to make the image 10% larger */
  opacity: 0.7;
}
.sneaker-row2 img {
  width: 280px;
  height: 300px;
  transition: transform 0.3s ease-in-out, opacity 0.3s ease-in-out; /* Add transition properties for transform and opacity */
}

.sneaker-row2 img:hover {
  transform: scale(1.1); /* Apply a scale transform on hover to make the image 10% larger */
  opacity: 0.7;
}













.news-header {
  width: 100%;
  height: 10vh;
  display: flex;
  justify-content: center;
  align-items: center;
  font-family: "Trebuchet MS", "Lucida Sans Unicode", "Lucida Grande",
    "Lucida Sans", Arial, sans-serif;
  /* border: 1px solid red; */
}
.news-parent {
  width: 100%;
  height: 60vh;
  font-family: "Trebuchet MS", "Lucida Sans Unicode", "Lucida Grande",
    "Lucida Sans", Arial, sans-serif;
  display: flex;
  /* border: 1px solid red; */
}

.news-prt1 {
  width: 34%;
  height: 60vh;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  /* border: 1px solid red; */
}
.news-prt2 {
  width: 34%;
  height: 60vh;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;

  /* border: 1px solid red; */
}
.news-prt3 {
  width: 34%;
  height: 60vh;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  /* border: 1px solid red; */
}
.prt3-imgs {
  display: flex;
  gap: 12px;
}
#img1 {
  width: 317px;
  height: 300px;
}
.featured {
  width: 100%;
  height: 50vh;
  display: flex;
}
.featured-1 {
  width: 34%;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 50vh;
  /* border: 1px solid red; */
}
.featured-2 {
  width: 34%;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 50vh;
  /* border: 1px solid red; */
}
.featured-3 {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 34%;
  height: 50vh;
  /* border: 1px solid red; */
}
.featured img {
  width: 420px;
  height: 250px;
  /* border: 1px solid red; */
}
#home {
  color: red;
}
.search-container {
  display: flex;
  width: 50%;
  height: 10vh;
  position: relative;
  left: 260px;
  justify-content: center;
  align-content: center;
  margin: 90px;
}

.search-input {
  flex: 1;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 4px 0 0 4px;
  
  font-size: 16px;
}

.search-button {
  padding: 10px 20px;
  background-color: #40bfff;
  color: #fff;
  border: 1px solid #007bff;
  border-radius: 0 4px 4px 0;
  font-size: 16px;
  cursor: pointer;
}

.search-button:hover {
  background-color: #0056b3;
}

/* sneaker-row */
.sneaker-row1 {
  justify-content: center;
  align-content: center;
  display: flex;
}
.sneaker-row1 img {
  width: 280px;
  height: 300px;
}
.first,
.second,
.third,
.fourth {
  margin-top: 170px;
}
.sneaker-row2 {
  justify-content: center;
  align-content: center;
  display: flex;
}
.sneaker-row2 img {
  width: 280px;
  height: 300px;
}


/* footer */
.footer {
  width: 100%;
  display: flex;
  height: 90vh;
  background-color: #bcddfe;
}
.footer-1 {
  width: 40%;
  height: 50vh;
  /* border: 1px solid red; */
  display: flex;

  align-items: flex-end;
}
.footer-2 {
  width: 30%;
  /* border: 1px solid red; */
  height: 50vh;
  display: flex;

  align-items: flex-end;
}
.footer-3 {
  display: flex;
  width: 30%;
  align-items: flex-end;
  height: 50vh;
}
.footer-3 img {
  width: 160px;
  height: 140px;
}
.footer-2 img {
  width: 240px;
  height: 160px;
}
.footer-1 img {
  width: 260px;
  height: 170px;
}

/* responsive section */


@media screen and (max-width:948px){
#img1{
  display: none;
}
#img2{
  display: none;
}
#img3{
  display: none;
}
.sneaker-heading{
  position: relative;
  top: 60px;
}
.sneaker-heading p{
line-height: 20px;
}
.sneaker{
  height: 401vh;
}.sneaker-row1 {
  display: none; /* Hide .sneaker-row1 */
}

.sneaker-row2 {
  display: flex; /* Display .sneaker-row2 as a flex container */
  flex-wrap: wrap;
}


}

.addidas-prt1{
  width: 100%;
}






</style>
