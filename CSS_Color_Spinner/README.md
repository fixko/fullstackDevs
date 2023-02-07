# CSS-Color-Spinner
Colorful Pure CSS Spinner

<div style="text-align:center; margin:10px">Watch the <a href="https://youtube.com/shorts/PcI_NDH5Q7k" target="_blank">Colorful CSS Spinner</a> Youtube Video</div>
<div><br/></div>

```
<div class="spinner"></div>
<style>
    .spinner {
        width: 11em;
        height: 12em;
        border-radius: 49%;
        margin: 6em auto;
        box-shadow: -0em -0em green,
                    -0em 0em blue,
                    0em 0em red,
                    0em -0em yellow;
        animation: spin 0.3s infinite linear;
    }
    @keyframes spin {
        0%  { transform: rotate(1turn); }
        50% { box-shadow: -1em -1em green,
                    -1em 1em blue,
                    1em 1em red,
                    1em -1em yellow;
        }
    }
</style>
```
