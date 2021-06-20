# Проект
## 1. Старт проекта
В начале проекта по команде чата **start** - телепортировать игрока в стартовую точку и вывести на экран информацию об игре. При этом при самостоятельной команде чата **about** также выводить информацию об игре.
<img src = "./img/Minecraft Education Edition.jpg">  
<img src = "./img/Minecraft Education Edition2.jpg">

### Несколько экранов информации
При необходимости вывода информации на более чем 1-м экране необходимо поставить задержку более чем 8000 мс.
<img src = "./img/Minecraft Education Edition3.jpg">  

<img src = "./img/Minecraft Education Edition4.jpg">  
<img src = "./img/Minecraft Education Edition5.jpg">  

## 2. Создание NPC
### Создание NPC
Добавляем неигровой персонаж
<img src = "./img/Minecraft Education Edition6.jpg">  

Меняем настройки мира (устанавливаем параметр World builder в значение true). Для этого в чате пишем команду 
`/wb`
<img src = "./img/Minecraft Education Edition7.jpg">  
<img src = "./img/Minecraft Education Edition8.jpg">  

### Настройка NPC
Кликнем правой клавишей мыши на созданного неигрового персонажа.
<img src = "./img/Minecraft Education Edition9.jpg">  
И войдем в настройки диалогового окна.
<img src = "./img/Minecraft Education Edition10.jpg">  
Введем текст, который будет сообщать NPC игроку при обращении к нему.
<img src = "./img/Minecraft Education Edition11.jpg">  

Для того, чтобы вернуться к стандартному режиму - заменим параметр world builder на false, введя в чат команду `/wb`  
<img src = "./img/Minecraft Education Edition12.jpg">  
<img src = "./img/Minecraft Education Edition13.jpg">  

При выключении режима изменения мира (world builder - false) при нажатии правой клавишей мыши на неигрового персонажа будет отображаться запланированный текст.
<img src = "./img/Minecraft Education Edition14.jpg">  
 Данный текст также можно включить на автоматическое чтение.
<img src = "./img/reading.gif">  

### 3. Квест
Необходимо создать механизм из кнопок, липких поршней и алмазных блоков
<img src = "./img/Minecraft Education Edition16.jpg">  
<img src = "./img/Minecraft Education Edition17.jpg">  
<img src = "./img/Minecraft Education Edition15.jpg">  
И добавить код, который фиксирует наличие алмазного блока в определенной позиции
<img src = "./img/Minecraft Education Edition18.jpg">  
В результате &mdash; получем под каждую кнопку &mdash; различный ответ.
<img src = "./img/question.gif">  

<a href = "https://github.com/mikh-maksi/minecraft-code/blob/main/quest_questions.js">Код проверки вопросов</a>  

#### Игрок получает вещи
За различные ответы игроку можно выдавать различные вещи. Для этого - при различных ответах передавать игроку различные вещи:  
<img src = "./img/Minecraft Education Edition22.jpg">  

#### Телепортирование
Когда игрок дает правильный ответ - необходимо телепортировать его (либо в точку следующего вопроса, либо в точку начала RPG).
<img src = "./img/Minecraft Education Edition19.jpg">  

#### Обратный отсчет
Перед стартом RPG-части важно дать игроку время на то, чтобы он подготовился к атаке (взял желаемое оружие, одел амуницию).  
<img src = "./img/Minecraft Education Edition20.jpg">  
<img src = "./img/Minecraft Education Edition21.jpg">  
  
<a href = "https://github.com/mikh-maksi/minecraft-code/blob/main/time_back.js">JavaScript</a>  

<img src = "./img/teleport.gif">  