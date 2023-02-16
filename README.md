# Тестовое задание <a href="https://dev1.onecell.ru/"><img width="20%" href title="OneCell" src="img/logo/onecell.svg"></a>

* <a href="#description">Тестовое задание</a>
* <a href="#stack">Инструменты</a>
* <a href="#Sheets">Решение</a>
* <a href="#Checklist">Чек-лист проверок</a>
* <a href="#Add">Дополнительные проверки</a>
* <a href="#End">Заключение</a>
    + <a href="#gradle">Gradle</a>
    + <a href="#jenkins">Jenkins</a>
* <a href="#allure">Отчет о результатах тестирования</a>
    + <a href="#allure">Allure Report</a>
    + <a href="#alluretestops">Интеграция с Allure TestOps</a>
* <a href="#jira">Интеграция с Jira</a>
* <a href="#telegram">Уведомления в Telegram</a>

# <a id="description">Тестовое задание</a>

> Тестирование модуля `авторизации` и `аутентификации`

<details>
    <summary><h4>Полный текст тестового задания</h4></summary>

* > Необходимо протестировать внедрение нового функционала на страницу входа в систему [https://dev1.onecell.ru/login](https://dev1.onecell.ru/login), а также написать тест-кейсы и провести тестирование этой страницы (модуль авторизации и аутентификации).
    Для этого у вас будет два существующих в системе пользователя (две пары логин\пароль)
    По найденным багам оформить баг-репорт с обязательными артефактами (как если бы вы заводили баг для разработчика)
    Тестовую документцию и баг-репорт предоставить в любом удобном для этого виде (гугл-таблицы или гугл-документ, ссылка на страницу в ноушен, текстовый файл, qase.io, testRail). 
    >* Можно выбрать формат тест-кейсов или чек-листа (в зависимости от того, что больше подходит под определенные вами сценарии тестирования)
    
    >Сейчас платформа не защищена от ботов. Можно сделать сколько угодно попыток ввода пароля. </br>
    В качестве способа решения проблемы выбрано внедрение на платформу механизма Yandex SmartCaptcha. На стартовой странице логина в Платформе OneCell [https://dev1.onecell.ru/login](https://dev1.onecell.ru/login) кнопка “Я не робот” отсутствует.
    Окно с капчой (галочкой или заданием в зависимости от выбранного уровня сложности настроек капчи) увидят только те пользователи, которые не смогли авторизоваться определенное количество раз в соответствии с ниже описанными требованиями:
  > 
      1. Если совершено 5 не успешных попыток авторизации в течение 5 минут - показывается галочка «я не робот» (либо задание для пользователя). Капча выключается 1 раз в 15 минут или при совершении успешной авторизации.
      2. Если совершено 10 не успешных попыток авторизации в течение 3 минут с одного IP - появляется галочка «я не робот», либо задание для всех пользователей, в рамках IP.
         Капча в рамках IP выключается через 10 мин.

</details>

# <a id="stack">Инструменты</a>

<p  align="center">
  <code><img width="5%" title="Chrome" src="img/logo/chrome.png"></code>
  <code><img width="3.5%" title="Google Sheets" src="img/logo/google_sheets.png"></code>
  <code><img width="5.5%" title="Brain" src="img/logo/brain.png"></code>
</p>

# <a id="Sheets">Решение</a>

> Решение доступно в [Google Sheets](https://docs.google.com/spreadsheets/d/121ekFlx99Qs6NY9MyzqWRxpv_489Qrb1gMzEWK9RGps/edit?usp=sharing)

# <a id="Sheets">Чек-лист проверок</a>

# <a id="stack">Заключение</a>

<p  align="center">
  <code><img width="5%" title="Chrome" src="img/logo/chrome.png"></code>
  <code><img width="3.5%" title="Google Sheets" src="img/logo/google_sheets.png"></code>
  <code><img width="5%" title="Brain" src="img/logo/brain.png"></code>
</p>

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Rubik+Bubbles&pause=1000&color=8F59F7&width=435&height=40&lines=Спасибо+за+внимание!)](https://git.io/typing-svg)