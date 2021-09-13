<template>
    
    <!--Footer-->
    <footer class="footer">
        <div>
            <h3>Romania</h3>
        </div>
        <div class="footer-a">
             <ul>
                <li>About</li>
                <li>Advertising</li>
                <li>Bussines</li>
                <li>How Search Works</li>
            </ul>
            <ul>
                <li>Privacy</li>
                <li>Terms</li>
                <li>Settings</li>
            </ul>
        </div>
    </footer>
</template>

<script>
</script>

<style>

.footer{
    position:absolute;
    width:100%;
    bottom: 0;
    left: 0;
    padding: 7px 1px;
    background-color: #f2f2f2;
    font-size: 13px;
}

footer h3{
    color:#70757A;
    font-weight: 400;
    padding: 5px 30px 15px;
    border-bottom: 1px solid #dadce0;
    font-size: 15px;
    padding-right: 100%;
}

.footer .footer-a{
    padding: 5px 30px 0px 19px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    font-size: 14px;
}

.footer .footer-a ul{
    display: flex;
    padding: 10px 0;
}

.footer .footer-a ul li{
    margin: 0 10px;
    font-size: 15px;
    color: #70757A;
}

  @media (min-width: 768px) {
    .logo img {
        width: 110%;
    }
  
    .logo .search-container form input{
        width: 580px;
    }

    .footer .footer-a {
      flex-direction: row;
      justify-content: space-around;
    }
  }
  
  @media (min-width: 1280px) {
    .footer .footer-a {
      justify-content: space-between;
      padding: 0 30px;
    }
  }

  body{
    height: 100vh;
    overflow: hidden;
    font-family: sans-serif;
}
*{
    margin: 0;
    padding:0;
    box-sizing: border-box;
} 

ul{
    list-style-type: none;
}

li:hover{
    cursor: pointer;
    text-decoration: underline;
}

a{
    text-decoration: none;
    color: #000000DE;
    font-size: 13px;
}
</style>