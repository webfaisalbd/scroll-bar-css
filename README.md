### scroll-bar-css

`style.css`

```javascript
::-webkit-scrollbar {
    width: 20px;
}

::-webkit-scrollbar-track {
    background-color: black;
    /* background: red; */
}

::-webkit-scrollbar-thumb {
    background-color: skyblue;
    border-radius: 5px;
    border: .5px solid transparent;
    background-clip: content-box;

}

::-webkit-scrollbar-thumb:hover {
    background-color: goldenrod;

}



```