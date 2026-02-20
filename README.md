# HTML_elements
### Проект на тему: разработка элементов html
### студент группы 25ИС11-Д Жуков Вадим
### Stack: HTML, CSS, VS Code

<img src="https://github.com/Arlecchino77/HTML_elements/blob/main/screen.png?raw=true" alt=Screen>

HTML
```
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="view.css">
    <title>NEWMESSAGE</title>
</head>
<header>
    Студент группы 25ИС11-Д Жуков Вадим
</header>
<body style="background-color: #DCDCDC;">
    <div class="chat-card">
        <img src="../images/soprano.jpg" alt="Avatar" class="avatar">
            <div class="content">
                <div class="name">Тони Cопрано</div>
                <div class="message">
                    <span class="text">Вы: Спасибо, звучит заманчиво!</span>
                    <span class="time">. 8ч</span>
                </div>
            </div>
        <div class="status">
            <img src="../images/carmela.jpg" alt="Seen" class="seen-img">
        </div>
    </div>
</body>
</html>
```
CSS
```
body {
    margin: 0;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background-color: #DCDCDC;
    font-family: sans-serif;
}

header {
    margin-bottom: 40px;
    font-size: 18px;
    color: #444;
}

.chat-card {
    display: flex;
    align-items: center;
    padding: 16px 20px;
    background: #ffffff;
    border-radius: 15px;
    width: 450px;
    box-shadow: 0 12px 30px rgba(0, 0, 0, 0.12);
    box-sizing: border-box;
}

.avatar {
    width: 55px;
    height: 55px;
    border-radius: 50%;
    object-fit: cover;
    margin-right: 15px;
    flex-shrink: 0;
}

.content {
    flex-grow: 1;
    display: flex;
    flex-direction: column;
    overflow: hidden;
}

.name {
    font-weight: 600;
    font-size: 18px;
    color: #050505;
    margin-bottom: 4px;
}

.message {
    color: #65676b;
    font-size: 15px;
}

.time {
    color: #8a8d91;
    margin-left: 5px;
}

.status {
    display: flex;
    align-items: center;
    margin-left: 15px;
    flex-shrink: 0;
}

.seen-img {
    width: 18px;
    height: 18px;
    border-radius: 50%;
    object-fit: cover;
}

```
