```html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Fit-boi Repacks</title>
    <!-- For the social media icons -->
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"
    />
    <style>
      * {
        box-sizing: border-box;
      }

      body {
        margin: 0;
        font-family: Arial, Helvetica, sans-serif;
      }

      .topnav {
        position: fixed;
        top: 0%;
        width: 100%;
        overflow: hidden;
        background-color: #333;
      }

      .topnav a {
        float: left;
        display: block;
        color: lightgray;
        text-align: center;
        padding: 14px 30px;
        text-decoration: none;
        font-size: 17px;
        border-right: 1px solid #bbb;
      }

      .topnav a:hover {
        background-color: black;
        color: lightgray;
      }

      .topnav a.active {
        background-color: green;
        color: white;
        font-family: "Times New Roman", Times, serif;
        font-style: oblique;
      }

      .topnav .search-container {
        float: right;
      }
      .bhoot img {
        max-width: 100%;
        padding-bottom: 0;
        height: auto;
      }
      .bhoot1 img {
        width: 1000px;
        height: 300px;
      }
      .topnav input[type="text"] {
        margin-top: 6px;
        width: 200px;
        height: 35px;
        font-size: 17px;
        border-radius: 10px;
        background-color: rgb(255, 240, 240);
      }

      .topnav .search-container button {
        float: right;

        margin-top: 6px;
        margin-right: 6px;
        height: 35px;
        background: rgb(100, 98, 98);
        font-size: 17px;
        color: darkgray;
        border-radius: 5px;
        cursor: pointer;
      }

      /* .topnav .search-container button:hover {
        background: lightgray;
      } */

      @media screen and (max-width: 600px) {
        .topnav .search-container {
          float: none;
        }
        .topnav a,
        .topnav input[type="text"],
        .topnav .search-container button {
          float: none;
          display: block;
          text-align: left;
          width: 100%;
          margin: 0;
          padding: 14px;
        }
        .topnav input[type="text"] {
          border: 1px solid #ccc;
        }
      }
      * {
        margin: 0;
        box-sizing: border-box;
      }
      .row {
        margin: 0;
      }

      .column {
        margin: 0;
        float: left;
        width: 33.33%;
        padding: 10px;
        height: 300px;
      }

      .row:after {
        margin: 0;
        content: "";
        display: table;
        clear: both;
      }
      .column .hello {
        margin: 0;
        color: rgb(122, 114, 114);
        width: 350px;
        text-align: left;
      }
      .bada {
        margin: 0;
        color: green;
      }
      .hello1 {
        background-color: black;
        color: green;
        padding: 0px;
        margin: 0;
      }
      .column1 {
        float: left;

        width: 25%;
        padding: 5px;
      }
      .column1 img {
        width: 100%;
        height: 200px;
      }

      .row1::after {
        content: "";
        clear: both;
        display: table;
      }
      .holakero {
        background-color: rgb(22, 21, 21);
      }
      .holakero h1 {
        color: green;
        text-align: center;
        font-style: normal;
      }
      .holakero p {
        color: #666;
        text-align: center;
      }
      .fa {
        font-size: 20px;
        padding-right: 40px;
        padding-left: 30px;
        padding-top: 15px;
        padding-bottom: 15px;
        width: 30px;
        margin: 0;
        text-align: center;
        text-decoration: none;
      }

      .fa:hover {
        opacity: 0.7;
      }

      .fa-facebook {
        background: #3b5998;
        color: white;
      }

      .fa-twitter {
        background: #55acee;
        color: white;
      }

      .fa-google {
        background: #dd4b39;
        color: white;
      }

      .fa-linkedin {
        background: #007bb5;
        color: white;
      }

      .fa-youtube {
        background: #bb0000;
        color: white;
      }

      .fa-instagram {
        background: #125688;
        color: white;
      }

      .fa-pinterest {
        background: #cb2027;
        color: white;
      }
      .newnewnew {
        display: block;

        max-width: 100%;

        background-color: black;
      }
      .newnewnew h1 {
        color: gray;
        float: left;
        padding-left: 40px;
        padding-right: 300px;
        font-size: 40px;
      }
      .newnewnew h2 {
        color: gray;
      }
      .column3 {
        float: left;
        width: 20%;
        padding: 10px;
        height: 300px;
      }

      .row3:after {
        content: "";
        display: table;
        clear: both;
      }
      ul {
        list-style: none;
      }

      ul li::before {
        content: "\2022";
        color: green;
      }

      .row1 a {
        display: block;
        color: #aaa;
        text-align: center;
        /* padding: 14px 10px; */
        text-decoration: none;
        font-size: 17px;
        /* border-right: 1px solid #bbb; */
      }
    </style>
  </head>
  <body>
    <div class="topnav">
      <a class="active" href="#edwal">Fit-Boi Repacks</a>
      <a href="#home">Home</a>
      <a href="#action">Action</a>
      <a href="#adventure">Adventure</a>
      <a href="#shooting">Shooting</a>
      <a href="#strategy">Strategy</a>
      <a href="#rpg">RPG</a>
      <a href="#stealth">Stealth</a>

      <div class="search-container">
        <form action="/action_page.php">
          <input type="text" placeholder="Search" name="search" />
          <button type="submit">Submit</button>
        </form>
      </div>
    </div>

    <div class="bhoot" style="background-color: black">
      <img src="images/use3.jpg" alt="photo hai" />
    </div>
    <div class="row" style="margin: 0">
      <div class="column" style="background-color: rgb(26, 24, 24)">
        <h2 class="bada">Random Big Heading Number One</h2>
        <br />
        <p class="hello">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Incidunt quam
          reiciendis excepturi accusantium dolor? Officia, praesentium ab
          veniam, odio atque distinctio voluptatem assumenda vero porro
          blanditiis asperiores eum dolorum voluptas quisquam perspiciatis animi
          illum aliquam repudiandae. Exercitationem illo repudiandae, iste
          repellendus est, corporis at culpa eaque maiores, iure amet ducimus?
        </p>
      </div>
      <div class="column" style="background-color: rgb(48, 43, 43)">
        <h2 class="bada">Random Big Heading Number Two</h2>
        <br />
        <p class="hello">
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Mollitia qui
          consequatur facere modi vitae optio, quas facilis atque aperiam eius
          necessitatibus veritatis eaque? Laborum ad adipisci aut rem, ea
          impedit obcaecati pariatur quibusdam voluptates voluptatum? Quia
          deserunt odit veniam dolore amet officiis perferendis quam? Eum harum
          quos explicabo ipsum assumenda!
        </p>
      </div>
      <div class="column" style="background-color: rgb(26, 24, 24)">
        <h2 class="bada">Random Big Heading Number Three</h2>
        <br />
        <p class="hello">
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Mollitia qui
          consequatur facere modi vitae optio, quas facilis atque aperiam eius
          necessitatibus veritatis eaque? Laborum ad adipisci aut rem, ea
          impedit obcaecati pariatur quibusdam voluptates voluptatum? Quia
          deserunt odit veniam dolore amet officiis perferendis quam? Eum harum
          quos explicabo ipsum assumenda!
        </p>
      </div>
    </div>
    <div class="holakero">
      <br />

      <h1>Top games this week!</h1>
      <br />

      <div class="row1">
        <div class="column1">
          <img src="images/dmcnew.jpg" alt="Snow" />
          <br />
          <br />

          <a href="#DevilMayCry">Devil May Cry</a>
          <p>Downloads : 69696</p>
          <p>Category : Action , RPG , Adventure</p>
        </div>
        <div class="column1">
          <img src="images/titanfall.jpg" alt="Forest" />
          <br />
          <br />
          <a href="#Titanfall">Titanfall 2</a>
          <p>Downloads : 69420</p>
          <p>Category : Shooting , Adventure</p>
        </div>
        <div class="column1">
          <img src="images/raji.jpg" alt="Mountains" />
          <br />
          <br />
          <a href="#Raji">Raji : An Ancient Epic</a>
          <p>Downloads : 42069</p>
          <p>Category : RPG , Adventure</p>
        </div>
        <div class="column1">
          <img src="images/batllefield.jpg" alt="Mountains" />
          <br />
          <br />
          <a href="#bf">Battlefield 1</a>
          <p>Downloads : 64920</p>
          <p>Category : Shooting</p>
        </div>
      </div>
    </div>
    <div class="newnewnew">
      <br />
      <br />
      <h1 style="color: green">Lorem ipsum dolor sit amet.</h1>

      <a href="#" class="fa fa-facebook"></a>
      <a href="#" class="fa fa-twitter"></a>
      <a href="#" class="fa fa-google"></a>
      <a href="#" class="fa fa-linkedin"></a>
      <a href="#" class="fa fa-youtube"></a>
      <a href="#" class="fa fa-instagram"></a>
      <a href="#" class="fa fa-pinterest"></a>
      <br />
      <br />
      <br />
    </div>
    <div class="row3">
      <div class="column3" style="background-color: black">
        <!-- <h2 style="text-align: center; color: black">About us</h2> -->

        <ul>
          <li style="color: gray">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus!
          </li>
          <br />
          <li style="color: gray">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit.
          </li>
          <br />
          <li style="color: gray">
            Lorem ipsum dolor sit amet consectetur adipisicing.
          </li>
          <br />
        </ul>
        <!-- <p style="color: gray; margin-left: 50px"></p> -->
      </div>
      <div class="column3" style="background-color: black">
        <ul>
          <li style="color: gray">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. At,
            assumenda ullam? Sequi.
          </li>
          <br />
          <li style="color: gray">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Id, ea
            numquam?
          </li>
          <br />
          <li style="color: gray">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquam.
          </li>
          <br />
        </ul>
      </div>
      <div class="column3" style="background-color: black">
        <h2 style="text-align: left; color: gray">Big Heading Part 2(a)</h2>
        <br />
        <p style="color: gray; text-align: centre; width: 200px">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium
          numquam nam beatae consequatur repudiandae nisi esse recusandae ipsam
          possimus. Perspiciatis unde voluptas ratione hic beatae ad, tempora
          quod nam laboriosam.
        </p>
      </div>
      <div class="column3" style="background-color: black">
        <h2 style="text-align: left; color: gray">Big Heading Part 2(b)</h2>
        <br />
        <p style="color: gray; text-align: centre; width: 200px">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Cumque quia
          neque nobis non aspernatur eius. Odit deleniti ullam possimus iusto
          error ratione eius culpa tenetur, esse eveniet adipisci. Ipsum, illo.
        </p>
      </div>
      <div class="column3" style="background-color: black">
        <h2 style="text-align: left; color: gray">Big Heading Part 2(c)</h2>
        <br />
        <p style="color: gray; text-align: centre; width: 200px">
          Lorem ipsum dolor sit, amet consectetur adipisicing elit. Autem,
          assumenda ullam dolores, nulla repellendus a, minus necessitatibus
          eaque quibusdam fugiat expedita consequuntur dolor. Laudantium
          cupiditate molestias exercitationem blanditiis dolorum libero?
        </p>
      </div>
    </div>
  </body>
</html>
```