<!DOCTYPE html>
<html lang="tu">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>google templet ödevi </title>
    <style>
    
    *{
  margin: 0;
 padding: 0;}

 section {
    position: relative;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;}
  section header{
     position: absolute; 
     top:0;
     width: 100%;
     display: flex;
     justify-content: flex-end;
     padding: 20px;
    height: 10px;
  background: white;}
  section .about {
       position: absolute;
       top: 20px;
       display: flex;
       justify-content: flex-end;
       left: 0;
    }
     
  section header ul { 
    display: flex;
    justify-content: center;
    align-items: center;}

  section header ul li {
    list-style: none;
    margin-left: 30px ;}
  section header ul li a {
    color: black;
    text-decoration: none;
    font-size: 16px;}
  section header ul li button {
    background:  #4584ef;
    border: none;
    outline: none;
    padding: 8px 14px ;
    color: white;
    font-size: 14px;
    font-weight: 700;
    border-radius: 3px;
    cursor: pointer;}
  section .main{
   width: 580px ;
   display: flex;
   flex-direction: column;
   align-items: center;
   justify-content: center;
}


section .main .searchBox{
position: relative;
width: 100%;
margin-top: 20px;

}
section .main .searchBox .search{
width: 100%;
padding: 13px;
padding-left: 30px;
padding-right: 0;
border-radius: 30px;
border: 1PX solid #CCC;
outline: none;
font-size: 16px;

}
section .main .searchBox .icons{
position: absolute;
top: 0;
border: 0;
width: 100%;
display: flex;
padding: 13px 15px;
justify-content: space-between;
align-items: center;
pointer-events: none;

}
section .main .buttons{
margin-top: 20px;
position: absolute;
justify-content: space-between;
}
section .main .buttons button {
margin: 5px 72px;
padding: 12px 20px;
color: #555;
font-size: 14px;
border: none;
cursor: pointer;
border-radius: 10px;
border: 1px solid transparent;
outline: none;
justify-content: space-around;
}
section .main .buttons button:hover{
border: 1px solid #ccc;
}
section header ul li a:hover{

text-decoration: underline;
}
section header ul li button:hover{
text-decoration: underline;
}
section .main .searchBox .search:hover{
background:#C3C9CA;
}

.dark{
align-items: center;
justify-content: center;
display:flex;
width: 100%;
position:absolute ;
top: 475px;
padding: 20px;
left: -25px;
}
body {

background-color: white;
color: black;

}

.dark-mode {
background-color: black;
color: white;
}
.footer{
background: #D0D3D4;
height: 10px;
position: absolute;
display: flex;
justify-content: space-between;
top: -60px;
width: 100%;
align-items: center;
text-decoration: dashed;
border: 10px;
padding: 20px;

}
.footer .bir ul{
display: flex;
justify-content: center;
align-items: center;
width: 100%;
}
.footer .bir ul li{
list-style: none;
margin-left: 20px;
text-decoration: none;

}
.footer.bir ul li a {
color: black;
text-decoration: none;
font-size: 20px;


}
.footer .iki ul{
display: flex;
justify-content: center;
align-items: center;
}
.footer .iki ul li {
list-style: none;
margin-left: 20px;
text-decoration: none;

}.footer.iki ul li a {
color: black;
text-decoration: none;
font-size: 20px;
}
</style>
</head>

<body>
    <section>
      <header> 
        <ul class="about">
          <li><a href="">About</a></li>
          <li><a href="">Store</a></li>
        </ul>
        <ul>
         <li> <a href="https://www.google.com/gmail/"> Gmail</a></li>
         <li> <a href="https://www.google.com/search?q=images&hl=ar&tbm=isch&sxsrf=APq-WBs7t29ElHXFWWJG6P_6gOp6JfjORw%3A1645229449414&source=hp&biw=1366&bih=600&ei=iTUQYraeFvCRxc8P2IGdoAg&iflsig=AHkkrS4AAAAAYhBDmT2M5Biv-LJhaTUH3rNnHXh_-y-8&ved=0ahUKEwj2hp2nvYr2AhXwSPEDHdhAB4QQ4dUDCAY&uact=5&oq=images&gs_lcp=CgNpbWcQAzIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQ6BwgjEO8DECc6BAgAEB5QAFi6N2DFSWgCcAB4AIABlAGIAecIkgEDMC44mAEAoAEBqgELZ3dzLXdpei1pbWc&sclient=img">Images</a></li>
         <li> <a href=""><img src="img/bars.png"></a></li>
         <li> <a href="https://accounts.google.com/servicelogin"><button> sign in</button> </a></li>
        </ul>
      </header>

      <div class="main">
         <img src="img/google.png">
         
         <div class="searchBox" >
           <input type="text" class=" search">
           <div class="icons">
             <div> <img src="img/search.png" alt=""></div>
             <div> <img src="img/mic.png" alt=""></div>
           </div>
         <div/>
         <div class="buttons">
           <button>Google Search </button>
           <button>I'm Feeling Lucky </button>
         </div>
         
      </div>
    </section>
<div class="dark">
  <button onclick="myFunction()">Toggle dark mode</button>
</div>

    <section>
      <div class="footer">

         <div class="bir">
          <ul>
            <li><a href="">Advertising</a></li>
            <li><a href="">Business</a></li>
            <li><a href="">How Search works</a></li>
          </ul>
         </div>
         <div class="iki">
          <ul>
            <li><a href="">Privacy</a></li>
            <li><a href="">Terms</a></li>
            <li><a href="">Settings</a></li>

          </ul>
        </div>
        
        </div>
    </section>
    <script>
      function myFunction() {
         var element = document.body;
         element.classList.toggle("dark-mode");
      }
      </script>
</body>
</html>
