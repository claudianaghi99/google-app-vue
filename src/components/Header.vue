<template>
    <header class="header">
        <ul>
            <li>
                <a href="https:mail.google.com">Gmail</a>    
            </li>
            <li>
                <a href="https://images.google.com/">Images</a>    
            </li>

            <!--Images header-->
            <li>
                <div class="dropdown-apps">
                    <img src="../assets/google-apps.png" alt="google apps" class="appimg">
                   
                    <!-- <div class="dropdown-content-apps">
                        <p>Google apps</p>
                    </div> -->
                </div>
            </li>
            <li>
                <img src="../assets/account-image.png" alt="account image" class="accimg">
            </li>
        </ul>
    </header>
</template>
<script></script>

<style scoped>

.appimg{
    max-height: 32px;
}

.appimg:hover{
    background-color: #dadce0;
    border-radius: 50%;
} 

.accimg{
    max-width: 75%;
    max-height: 75%;
}

.accimg:hover{
    background-color: #dadce0;
    border-radius: 50%
}

body{
    height: 100vh;
    overflow: hidden;
    font-family: sans-serif;
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
.header{
    display: flex;
    justify-content: flex-end;
    padding: 12px 0;
}

.header ul{
    display: flex;
    align-items:center;
}

.header ul img{
    border-radius: 50%;
}

.header ul li{
    margin: 0 12px;
    display: flex;
    align-items:center;
    justify-content: space-evenly;
}


</style>