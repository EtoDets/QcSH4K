<div style="text-align: center;">
    <h1>Скриншотер ShareX</h1>
    <a href="https://getsharex.com/" target="_blank" style="display: inline-block; padding: 10px 20px; background-color: #007BFF; color: white; text-decoration: none; border-radius: 5px;">Скачать</a>
</div>

---

::: details v2ray | добавить `ru` пресеты {close}
1. Settings
2. Regional presets setting
3. Выбрать `Russia`
4. Дождаться загрузки
::: tip
   - Загрузка может начатся не сразу
::: warning
   - Если нихуя нет то возможно поможет добавить сервер и повторить
:::


::: details v2ray | `ru` на прямую {close}
Добавить домен `'.ru'` в правило **`'RUv1-Всё, кроме РФ'`**
1. Settings
2. Routing settings
3. Открыть `'RUv1-Всё, кроме РФ'` 
4. Найти `'Доступные только в России напрямую'` и открыть
5. Первая Колонка `'Domain'`
6. Вписать туда след. правила ->

``` 
geosite:category-gov-ru,
regexp:.*\.ru$,
geoip:ru
```
7. Сохранить и нажать `'Reload'`
:::

---

<details>
  <summary>test</summary>
  Это скрытый текст.
</details>



<span style="filter: blur(5px);">Этот текст заблюрен.</span>
<button onclick="this.previousElementSibling.style.filter='none'; this.style.display='none';">тык</button>


