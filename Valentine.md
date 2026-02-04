# Valentine   
```

<!DOCTYPE html>
<
```
```
html lang="en">

```
```
<head>
  <
```
```
meta charset="UTF-8">

```
```
  <
```
```
title>Will You Be My Valentine? 💖</title>

```
```
  <
```
```
style>

```
```
    
```
```
body {

```
```
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
      font-family: 'Arial', sans-serif;
      
```
```
height: 100vh;

```
```
      
```
```
display: flex;

```
```
      
```
```
justify-content: center;

```
```
      align-items: center;
      margin: 0;
    }

    
```
```
.card {

```
```
      background: white;
      
```
```
padding: 30px;

```
```
      
```
```
border-radius: 20px;

```
```
      text-align: center;
      
```
```
box-shadow: 0 10px 25px rgba(0,0,0,0.2);

```
```
      
```
```
width: 320px;

```
```
    }

    h1 {
      color: #ff4d6d;
    }

    
```
```
button {

```
```
      
```
```
padding: 12px 25px;

```
```
      
```
```
font-size: 18px;

```
```
      
```
```
border: none;

```
```
      border-radius: 25px;
      
```
```
cursor: pointer;

```
```
      margin: 15px;
    }

    
```
```
#yesBtn {

```
```
      background: #ff4d6d;
      color: white;
    }

    #noBtn {
      
```
```
background: #ccc;

```
```
      position: absolute;
    }

    
```
```
#result {

```
```
      display: none;
      margin-top: 20px;
    }

    
```
```
#result img {

```
```
      width: 150px;
      margin-top: 15px;
    }
  </
```
```
style>

```
```
</head>
<
```
```
body>

```
```

<
```
```
div class="card">

```
```
  <
```
```
h1>Will you be my Valentine? 💘</h1>

```
```
  <
```
```
button id="yesBtn">YES 😍</button>

```
```
  <
```
```
button id="noBtn">NO 🙄</button>

```
```

  <
```
```
div id="result">

```
```
    <h2>Ohhhh 😍 So it’s a SUPER YES! 💖</h2>
    <p>See you on Valentine’s Day baby ❤️</p>
    <
```
```
img src="https://media.giphy.com/media/l0MYt5jPR6QX5pnqM/giphy.gif" alt="Love">

```
```
  </
```
```
div>

```
```
</div>

<
```
```
script>

```
```
  const noBtn = document.getElementById("noBtn");
  const yesBtn = document.getElementById("yesBtn");
  
```
```
const result = document.getElementById("result");

```
```

  noBtn.addEventListener("mouseover", () => {
    
```
```
const x = Math.random() * (window.innerWidth - 100);

```
```
    
```
```
const y = Math.random() * (window.innerHeight - 50);

```
```
    noBtn.style.left = x + 
```
```
"px";

```
```
    noBtn.style.top = y + 
```
```
"px";

```
```
  });

  yesBtn.addEventListener(
```
```
"click", () => {

```
```
    setTimeout(() => {
      result.style.display = 
```
```
"block";

```
```
      yesBtn.style.display = 
```
```
"none";

```
```
      noBtn.style.display = 
```
```
"none";

```
```
    }, 
```
```
5000);

```
```
  });
</script>

</body>
</
```
```
html>
```
```


```
