<!DOCTYPE html>

<html>

  <head>
    <title>Пример формы HTML</title>
  </head>
</head>

  
<body>

    
<h1>Задание 1</h1>
<ol>
<li><p><a target="_blank" href="http://moodle.kubsu.ru/">Moodle.kubsu.ru-главная!></a></p></li>
<li><p><a target="_blank" href="https://moodle.kubsu.ru/">Moodle.kubsu.ru-главная!(https)></a></p></li>
<li><p><a target="_blank" href="ftp://example.com/exec.txt">Без авторизации></a></p></li>
<li><p><a target="_blank" href="ftp://example:1234@example.com/exec.txt">C авторизацией></a></p></li>
<li><p><a target="_blank" href="https://moodle.kubsu.ru/#:~:text=%D0%A4%D0%B0%D0%BA%D1%83%D0%BB%D1%8C%D1%82%D0%B5%D1%82%20%D0%9A%D0%BE%D0%BC%D0%BF%D1%8C%D1%8E%D1%82%D0%B5%D1%80%D0%BD%D1%8B%D1%85%20%D1%82%D0%B5%D1%85%D0%BD%D0%BE%D0%BB%D0%BE%D0%B3%D0%B8%D0%B9%20%D0%B8%20%D0%BF%D1%80%D0%B8%D0%BA%D0%BB%D0%B0%D0%B4%D0%BD%D0%BE%D0%B9%20%D0%BC%D0%B0%D1%82%D0%B5%D0%BC%D0%B0%D1%82%D0%B8%D0%BA%D0%B8">Ссылка на сайт moodle.kubsu.ru на Факультет Компьютерных технологий и прикладной математики ></a></p></li>
<li><p><a target="_blank" href="file:///C:/Users/%D0%94%D0%B8%D0%BC%D0%B0/Desktop/1/form.html#:~:text=2%20%D1%81%D1%82%D1%80%D0%B0%D0%BD%D0%B8%D1%86%D0%B0-,%D0%97%D0%B0%D0%BF%D0%BE%D0%BB%D0%BD%D0%B8!,-%D0%92%D0%B2%D0%B5%D0%B4%D0%B8%D1%82%D0%B5%20%D0%B8%D0%BC%D1%8F%3A">Начало форума></a></p></li>
<li><p><a target="_blank" href="https://www.google.com/search?q=kubsu.ru&tbm=isch&ved=2ahUKEwjF4urCufzyAhUWvCoKHf4tCOoQ2-cCegQIABAA&oq=kubsu.ru&gs_lcp=CgNpbWcQDDIECAAQGDIECAAQGDIECAAQGDIECAAQGDoFCAAQgAQ6BAgAEB46BggAEAoQGDoECAAQAlDBclj3fGD9wQJoAHAAeACAAe8BiAGqBpIBBTIuNC4xmAEAoAEBqgELZ3dzLXdpei1pbWfAAQE&sclient=img&ei=6YY_YYXKJ5b4qgH-26DQDg&bih=694&biw=1137?width=10&color=black">С двумя параметрами в URL></a></p></li>
<li><p><a target="_blank" href="https://www.kubsu.ru/ru"><img src="C:\Users\Дима\Desktop\1\тест.jpg"alt="КУБГУ" width="200"></a></p></li>
<li>
<ul>
<li><a href="https://www.kubsu.ru/ru" title="Официальный сайт КубГУ">КубГУ</a></li>
<li><a href="https://www.kubsu.ru/ru/sveden" title="Сведения об образовательной организации">Немного о КубГУ</a></li>
<li><a href="https://www.kubsu.ru/ru/university/history-tradition" title="Интересные факты">История и традиции</a></li>
</ul>
    <li><a title="Оу">без href</a></li>
    <li><a href=" ">с пустым href</a></li>
<li><a href="https://example.com/" rel="nofollow">   запрещен переход поисковикам;</a></li>
<li><a href="http://example.com/"><noindex>  запрещенная для индексации поисковиками</noindex></a></li>
<li><p>Испанский теннисист Рафаэль Надаль получил премию лучшему спортсмену 2020 года по версии<a href="https://tass.ru/sport/11319897"> Laureus World Sports Academy</a>  (Мировая академия спорта "Лауреус"). Церемония вручения премии состоялась в четверг в испанской Севилье
</p></li>
<li><img src="map.png"width="200" usemap="#figure">
 <map name="figure">
<area shape ="rect" coords= "25,25,125,125" href="https://en.wikipedia.org/wiki/Square">
<area shape= "circle" coords = "200,75,50" href="https://en.wikipedia.org/wiki/Circle">
</map>
<li><a href="/about">Относительная ссылка на страницу в текущем каталоге</a> </li>
        <li><a href="/about/contacts">  Относительная ссылка в каталоге about  </a> </li>
        <li><a href="../page.html">  Относительная в каталоге уровнем выше текущего  </a></li>
        <li><a href="../../page.html">  Относительная в каталоге уровнем выше текущего  </a></li>
<li><a href="https://vk.cc/c5SIn1">Сокращенная ссылка на главную страницу moodle.kubsu.ru</a></li>
<li><a href="https://vk.cc/c5SIoy">Сокращенная ссылка на внутреннюю страницу moodle.kubsu.ru</a> </li>
</li>


    
  </ol>
  <body>

    <h1>Заполни!</h1>

    <form action="/"
      method="POST">

      <label>
        Введите имя:<br />
        <input name="field-name-1"
          value="" />
      </label><br />

      <label>
        Текстовое поле email:<br />
        <input name="field-email"
          value=""
          type="email" />
      </label><br />

      <label>
        Дата рождения:<br />
        <input name="field-date"
          value="19.02.2003"
          type="date" />
      </label><br />
  Пол : <br />
      <label><input type="radio" checked="checked"
        name="radio-group-1" value="Значение1" />
        Мужской</label>
      <label><input type="radio"
        name="radio-group-1" value="Значение2" />
        Женский</label><br />
 Количество конечностей : <br />
      <label><input type="radio" checked="checked"
        name="radio-group-2" value="Значение1" />
        4</label>
      <label><input type="radio"
        name="radio-group-2" value="Значение2" />
        6</label><br />
        

      <label>

      <label>
        Сверхспособности :
        <br />
        <select name="field-name-4[]"
          multiple="multiple">
          <option value="Значение1">Бессмертие</option>
          <option value="Значение2" selected="selected">Прохождение сквозь стены</option>
          <option value="Значение3" selected="selected">Левитация</option>
        </select>
      </label><br />
<label>
        Биография :<br />
        <textarea name="field-name-2">:)</textarea>
      </label><br />

      

      С контрактом ознакомлен(а) :<br />
      <label><input type="checkbox" checked="checked"
        name="check-1" />
         </label><br />

      
      <input type="submit" value="Отправить" />
    </form>

  </body>

</html> 
