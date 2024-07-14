# 12.position-z-index-
## program :
```
<!DOCTYPE html>
<html>
  <head>
    <title>position example</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <h1>position</h1>
    
    <h4>Relative</h4>
    <div class="container-relative">
      <div class=item6>1</div>
      <div class=item7>2</div>
      <div class=item8>3</div>
      <div class=item9>4</div>
      <div class=item10>5</div>
    </div>
    
     </body>
</html>
.body{
  background-color:#f0f0f0;
  font-family: Arial;
  margin:0;
  padding:0;
}
h1{
  background-color:tomato;
  text-align:center;
  color:white;
  margin-top:0;
}
h4{
  color:#f34345;
}
.container-relative
{
  background-color:#ccc;
  border-radius:4px;
  box-sizing:border-box;
  display:flex;
  margin:10px;
  
}
.container-relative >div
{
  background-color:white;
  height: 50px;
  width: 50px;
  border-radius:5px;
  display:grid;
  place-items:center;
  background-color:yellow ;
  border:2px solid #ccc;
}


.item7{
  position:relative;
  top:20px;
  right:20px;

}
.item6{
  position:absolute;
  z-index:1;
}
```
## output:
![WhatsApp Image 2024-07-14 at 22 44 30_2c90cf32](https://github.com/user-attachments/assets/f4314eae-5bef-4df9-8cb7-e29527e99512)
