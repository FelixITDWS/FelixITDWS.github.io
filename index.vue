<script lang = "ts">
    import 'assets/style.css'
</script>

<template>
    <title>Getsuka 玥華非官方網站</title>
    <link href = "site.ico" rel = "shortcut icon" type = "image/x-icon"/>
    <meta content = "玥華Getsuka" property = "title"/>
    <meta content = "玥華Getsuka" property = "og:title"/>

    <meta content = "玥華非官方網站" property = "og:site_name"/>

    <meta content = "玥華Getsuka小檔案" property = "description"/>
    <meta content = "玥華Getsuka小檔案" property = "og:description"/>
    <meta content = "玥華Getsuka小檔案" property = "twitter:description"/>
    <meta content = "https://getsuka.itdws.net" property = "og:url"/>

    <div id = "out-tab" class = "d-flex justify-content-between">
        <img src = "images/Logo.png" height = "80"/>
        <div class = "d-flex justfy-content-center">
            <dropdown label = "官方連結" :options = "[
                {href: 'httsp://www.youtube.com/@GetsukaCh', text: 'Youtube'},
                {href: 'https://www.twitch.tv/getsuka1008', text: 'Twitch'},
                {href: 'https://x.com/GetsukaV', text: 'X'},
                {href: 'https://discord.com/invite/bDNTsjnKDq', text: '官方DC群'},
                {href: 'https://www.instagram.com/getsukav', text: 'Instagram'},
                {href: 'https://p.ecpay.com.tw/5AB9B96', text: '綠界'}]"/>
            <dropdown label = "其他連結" :options = "[
                {href: 'https://github.com/FelixITDWS', text: 'Github'},
                {href: 'https://x.com/Felix_ITDWS', text: 'X'}]"/>
        </div>
    </div>

    <div class = "d-flex justify-content-center">
        <div id = "board">
            <h1>玥華Getsuka</h1>
            <div class = "d-flex justify-content-center">
                <img src = "images/Getsuka.jpg">
                <div style = "min-width: 800px; max-width: 50vw; padding: 0px 100px;">
                    <p><br><br>
                        玥華です！<br>
                        是隻世界上最聰明的金魚！<br>
                        為了尋找同類離開了家鄉，來到了這裡 ✦<br>
                        願意成為我的朋友嗎 ( ^ω^)<br>
                    </p>
                </div>
            </div>
        </div>
    </div>
</template>


<style lang = "scss">
    body {
    font-family: 'SetoFont', 'Noto Serif TC', sans-serif;
    background-size: cover;
    background-attachment: fixed;
    background-position: center;
    background-image: url();
    }
    
    #bg-opacity {
    background-color: #ffffffa0;
    min-height: 100vh;
    }
    
    #out-tab {
    background-color: bisque;
    position: relative;
    padding: 3px 1vw;
    }
    
    #broad {
    padding: 50px;
    margin: 10px;
    background-color: #ff8e8ea0;
    border-radius: 5rem;
    font-size: 36px;
    text-align: center;
    }
</style>