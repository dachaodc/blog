##利用border实现三角形

####第一步，先实现一个正方形

 .shape {
    width: 50px;
    height: 50px;         
 }

####第二步，给正方形添加边框

.shape {
    width: 50px;
    height: 50px;   
    border-top: 100px solid red;
    border-right: 100px solid green;
    border-bottom: 100px solid blue;
    border-left: 100px solid yellow;     
 }

####第三步，将正方的宽高设置为0px,仅留下边框，然后将不需要的边框的透明度置为0

 .shape {
    width: 0;
    height: 0;
    margin: 50px auto;
    border-top: 100px solid rgba(0, 0, 0, 0);
    border-right: 100px solid rgba(0, 0, 0, 0);
    border-bottom: 100px solid blue;
    border-left: 100px solid rgba(0, 0, 0, 0);
 }

