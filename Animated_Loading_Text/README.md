# Animated Loading Text
A simple, yet attractive loading page text animation

<div style="text-align:center; margin:10px">Watch the <a href="https://youtube.com/shorts/FlbAGWebADY" target="_blank">Animated CSS Loading Text</a> Youtube Video</div>
<div><br/></div>

```
<div class="gt">loading...</div>
<style>
    body {
        background-color: #000;
        padding-top: 50px;
    }

    .gt {
        height: 150px;
        text-align: center;
        font: bold 120px Calibri;
        background-image: linear-gradient(135deg,
        white 25%,red 25%,red 50%,
        white 50%,white 75%,red 75%);
        background-size: 50px 50px;
        animation: bganim 2s linear 2s infinite;
        background-clip: text;
        -webkit-background-clip: text;
        -webkit-text-stroke: 1px #fff;
        color: transparent;
    }

    @keyframes bganim {
        to { background-position: 50px; }
    }
</style>
```
