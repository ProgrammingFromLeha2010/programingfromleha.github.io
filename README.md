<!DOCTYPE html>
<html style="color: #012500;">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link href=""
</head>
<body>
  <h1>РЕГИСТРАЦИЯ</h1>
  <form name="sign up" action="#" method="post">
    <div>
      <label>Введите логин:</label>
      <input type="text" name="username" placeholder="Макс.32символ"/>
    </div>
    <div>
      <label>Введите E-mail:</label>
      <input type="email" name="email" value="@gmail.com"/>
    </div>
     <div>
      <label>Введите пароль:</label>
      <input type="password" name="password" placeholder="Пароль" />
    </div>
    <div >
      <label>Укажите пол</label>
      <input type="radio" name="sex" value="Man"/>Man
      <input type="radio" name="sex" value="Woman"/>Woman
    </div> 
     <div>
      <label>Укажите год:</label>
      <select name="year">
        <option value="2001">2001</option>
        <option value="2002">2002</option>
        <option value="2003">2003</option>
        <option value="2004">2004</option>
      </select>
      <div>
      <div>
        <label>Вставьте фото файл:</label>
        <input type="file" name="Фото"/>
      </div>
      <div>
      <a href="new.hot.gaxet.txt.jpg"></a>
      </div>
      <div>
        <textarea placeholder="Введите текст" ></textarea>
      </div>
       <input type="submit" name="sign up" value="Регистрация"/>
      </div>
    </div> 
  </form>
</body>
</html>
