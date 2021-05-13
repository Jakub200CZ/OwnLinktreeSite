# Your own linktr.ee site

Thanks to this ready-made project, you can create a page similar to linktr.ee on your own page with 100% you can modify it.

- All you have to do is add a folder named ASSETS and put your image there and point it in the code (the folder is not needed)

## Installation

Download project or copy/paste by this code.

---

### HTML

```html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <link rel="icon" href="assets/profile-picture.png">
    <title>Jakub200 - Links</title>
</head>
<body>


    <img src="assets/profile-picture.png" class="profile-picture">

    <div class="profile-name">Jakub200 - Link's</div>


        <a href="https://www.instagram.com/jakub200_cz/" class="links" target="_blank">📸 Instagram 📸</a>
        <a href="https://www.youtube.com/jakub200cz" class="links" target="_blank">📹 YouTube 📹</a>
        <a href="https://www.twitch.tv/jakub200cz" class="links" target="_blank">🔴 Twitch 🔴</a>
        <a href="https://twitter.com/sympy_js" class="links" target="_blank">📝 Twitter 📝</a>
        <a href="https://github.com/Jakub200CZ" class="links" target="_blank">🎇 Github 🎇</a>

    <div class="bottom-text"><a href="https://www.sympy.xyz">sympy.xyz</a></div>
 
    <hr>

</body>
</html>
```

---

### CSS

```
@import url('https://fonts.googleapis.com/css2?family=Nunito:wght@300&display=swap');
@import url('https://fonts.googleapis.com/css2?family=KoHo:wght@300&display=swap');
* {
  user-select: none;
  font-family: 'Nunito', sans-serif;
}

body {
    background: #121212;
    color: #fff;
    font-size: 15px;
    letter-spacing: 2px;
}

img {
  border-radius: 50%;
  border: 3px solid #fff;
}


.profile-picture {
    display: block;
    margin-left: auto;
    margin-right: auto;
    margin-top: 5%;
    height: auto;
    max-width: 200px;
  }

.profile-name {
      font-family: 'KoHo', sans-serif;
      text-align: center;
      padding: 30px;
  }

.links {
      text-align: center;
      margin-top: 20px;
      padding: 20px;
      border: 1px solid white;
      border-width: 2px;
      width: 290px;
      display: block;
      margin-left: auto;
      margin-right: auto;
      border-radius: 40px;
  }

a {
    text-decoration: none;
    color: white;
    transition: color 1s; 
}

.bottom-text {
    text-align: center;
    margin-top: 40px;
    font-size: 20px;
    font-weight: bold;
    text-decoration: underline;
}

a:hover {
    color: #000;
    background: #fff;
    transition: 0.5s;
}




```

---

## Support 

I will be happy if you support me follow on the mem instagram where I give you the regular content regarding WEB Development 
[CLICK HERE --> @jakub200_cz](https://www.instagram.com/jakub200_cz/)
