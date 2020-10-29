# responsiveWebdesignTemplate
RESPONSIVE FOOTER TEMPLATE
 <footer>
        <div class="main-content">
<div class="box">DIVISION 1</div>
<div class="box"> DIVISION2</div>
<div class="box"> DIVISION 3</div>
<div class="box">DIVISION 4</div>
<div class="box">DIVISION 5</div>
        </div>
    </footer>
    
    
       *{
        box-sizing: border-box;
       }
       footer{
           width:100%;
           color:blanchedalmond;
           position:fixed;
           bottom:0;
       }
       .main-content{
       display:flex;
       @media screen and (max-width: 900px) {
  footer{
    position: relative;
    bottom: 0px;
  }
  .main-content{
    flex-wrap: wrap;
    flex-direction: column;
  }
  .main-content .box{
    margin: 5px 0;
  }
}
