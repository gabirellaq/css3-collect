# css3-collect

## CSS3 @keyframes 规则
```
@keyframes name {
    from {
      width: 0;
    }
    to {
      width: 100px;
    }
}

// 等同于
@keyframes name {
    0% {
      width: 0;
    }
    100% {
      width: 100px;
    }
}

div {
    width: 0;
    height: 20px;
    background: #f00;
    animation: name 4s;
}

// 等同于
div {
    animation-name: name;
    animation-duration: 4s;
}
```
