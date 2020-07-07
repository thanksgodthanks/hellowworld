# hellowworld
###website front end 
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>repl.it</title>
    <link href="style.css" rel="stylesheet" type="text/css" />
    <style>
      .nav{
        height: 70px;
        border-bottom:1px solid black;
        display: flex;
        align-items: center;
      }
      .nav-rightitems{
        display: flex;
        margin-left:auto;
      }
      .navitem{
        margin-left: 10px;
      }
      .myname{
        margin-left: 120px;
      }
      .title{
        font-size: 60px;
        font-weight: bold;
        text-align: center;
      }
      .subtitle{
        font-size: 50px;
        font-weight: 300;
        text-align: center;
      }
      .main{
        width: 800px;
        margin: 0 auto;
        margin-top: 60px;
      }
      .prices{
        display: flex;
      } 
      .price_value{
        width: 400px;
        height: 150px;
        border: 2px solid black;
        border-radius: 4px;
        margin-left: 100px;
        background-color: rgba(0,0,0,.03);
      }
      .pric_value_title{
        font-size: 30px;
        background-color: rgba(0,0,.03,.03);
        text-align: center;
        border-bottom: solid black 1px;
      }
      .price_vlaue_num{
        color: red ;
        font-size: 30px;
      }
      .price-item-button{
        color: #007bff;
        background-color: transparent;
        background-image: none;
        border-color: #007bff;
      }
      .price_active_button{
        color: #FF7F50;
      }
    </style>
  </head>
  <body>
    <div class="nav">
      <div class="myname">
        지종현
      </div>
      <div class="nav-rightitems">
        <div class="navitem">메뉴2</div>
        <div class="navitem">메뉴3</div>
        <div class="navitem">메뉴4</div>
      </div>
    </div>
    <div class="main">
      <div class="title">
        pricing
      </div>
      <div class="subtitle">
        welcome
      </div>
      <div class="prices">
        <div class="price_value">
          <div class="pric_value_title">
            free
          </div>
          <div class="price_vlaue_num">
            0$
          </div>
          <div class="price_detail">
            10 users first 
          </div>
          <button class="price-item-button">
            click me 
          </button>
        </div>
        <div class="price_value">
          <div class="pric_value_title">
            premium
          </div>
          <div class="price_vlaue_num">
            15$
          </div>
          <div class="price_detail">
            200 users first 
          </div>
          <button class="price-item-button price_active_button">
            click me 
          </button>
        </div>
        <div class="price_value">
          <div class="pric_value_title">
            gold
          </div>
          <div class="price_vlaue_num">
            30$
          </div>
          <div class="price_detail">
            300 users first 
          </div>
          <button class="price-item-button price_active_button">
            click me 
          </button> 
        </div>
      </div>
    </div>
    
    <script src="script.js"></script>
  </body>
</html>
