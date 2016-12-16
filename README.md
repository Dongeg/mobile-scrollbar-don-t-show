# mobile-scrollbar-don-t-show
移动端div内滚动条不显示问题

在需要的页面加下面的css样式
```css
        ::-webkit-scrollbar {
            -webkit-appearance: none;
        }
        ::-webkit-scrollbar:vertical {
            width: 0.8em;/*滚动条多粗*/
        }
        ::-webkit-scrollbar:horizontal {
            height: 10em;/*滚动条多长*/
        }
        ::-webkit-scrollbar-thumb {
            background-color: rgba(0, 0, 0, .5);
            border-radius: 10px;
            border: 2px solid #ffffff;
        }
        ::-webkit-scrollbar-track {
            border-radius: 10px;
            background-color: #ffffff;
        }
```
