## 实现一个提醒

#### 第一步，观察正方形的border，发现四个边是由梯形组成的


```html
.shape {
            width: 80px;
            height: 80px;
            background-color: transparent;

            border-top: 20px solid red;
            border-right: 20px solid green;
            border-bottom: 20px solid blue;
            border-left: 20px solid yellow;
            margin: 50px auto;
        }
```


### 第二步，隐藏掉三个边框，剩余一个就是想要的效果了



```html
.shape {
    width: 80px;
    height: 80px;
    background-color: transparent;

    border-top: 20px solid transparent;
    border-right: 20px solid transparent;
    border-bottom: 20px solid blue;
    border-left: 20px solid transparent;
    margin: 50px auto;
}
```

