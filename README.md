# rslang

| Deadline         | Repo name | Repo  |
| ---------------- | ----------- | ----------- |
| 24.05.2020 23:59 | rslang   |  created by students themselves   |

**rslang** – приложение для изучения иностранных слов с методикой интервального повторения, отслеживанием индивидуального прогресса и мини-играми.

## Особенности приложения

- большое количество настроек, благодаря которым пользователь может изменять внешний вид и некоторые детали работы приложения в соответствии с собственными предпочтениями
- для заучивания иностранных слов используется методика интервального повторения
- собирается и предоставляется пользователю статистика изучения слов, как краткосрочная – по результатам каждой тренировки, так и долгосрочная – за весь период обучения
- для отслеживания прогресса и геймификации обучения используются мини-игры

## Особенности задания

- задание творческое. Оно не сводится к написанию кода, но также предполагает аналитическую работу по поиску механизмов и путей решения поставленных задач, достижения ожидаемых результатов. 
- работа ведётся в группах. Во-первых, потому что задач много, а времени мало, и чтобы всё успеть, нужно действовать сообща. Во-вторых, потому что современная разработка ведётся в командах, и необходимо учиться взаимодействовать с другими разработчиками, распределять обязанности, нести ответственность за свой участок работы.
-  частью задания является создание промо-страницы приложения, в которой презентуются реализованные вашей командой особенности приложения и размещается короткое (5-7 минут) видео с демонстрацией его работы.

## Прототипы приложения

- заучивание иностранных слов и сбор статистики – приложение  Lingvist. Ознакомиться с его работой можно на сайте `https://lingvist.com/`, бесплатный ознакомительный период – 14 дней.
  <details><summary>Интересные факты про Lingvist</summary>

  <p></p><p>История появления приложения Lingvist довольно занимательная.</p>
  <p>Все началось с того, что доктор физических наук Майт Мюнтель перевёлся в Европейский центр ядерных исследований (CERN) и оказался во франкоязычном коллективе. Срочно понадобилось знание языка, и он придумал и создал для себя программу, которая выполняла бы роль персонального репетитора. За два месяца он достиг своей цели. Но на этом история созданного им приложения не заканчивается.</p>
  <p>Lingvist был назван лучшим стартапом 2014 года и получил премию в 1 млн евро от инвестиционного фонда ЕС. Считается, что приложение позволяет значительно ускорить изучение языка благодаря тому, что постоянно отслеживает прогресс и не заставляет учить уже известные пользователю слова. Сейчас это большой сложный высоконагруженный проект с многомиллионными инвестициями. А началось всё с небольшого приложения, которое создал один человек, даже не программист, чтобы решить возникшую перед ним проблему.</p>
  </details>

- методика интервального повторения – программа Anki `https://ankiweb.net/shared/info/317970103`
- мини-игры – приложение Lingualeo `https://lingualeo.com/ru/training`. Вам понадобится доступ к Lingualeo Premium. Бесплатный доступ к Lingualeo Premium на один день откроется после 5 дней тренировки с выполнением дневной нормы по набранным баллам.

## Исходные данные
Коллекция "4000 essential english words". Коллекция состоит из 3600 часто употребляемых английских слов, изучение которых вам необходимо организовать. Слова в коллекции отсортированные от более простых и известных до более сложных. Первые 400 наиболее часто употребляемых слов в коллекцию не вошли. Считается, что это базовый запас взрослого человека, оставшийся от школы/вуза или предыдущих попыток изучения языка.  Слова разделены на группы по 20 слов. Вся коллекция разбита на шесть частей по 600 слов в каждой. Перевода слов и предложений в коллекции нет. Для их получения необходимо будет использовать подходящее бесплатное translation API. 
- визуальное представление коллекции: `https://rslang-data.netlify.com/`
- пример файла с данными: `https://github.com/irinainina/rslang/blob/master/data/book1.json`

## Требования к репозиторию
- для разработки приложения создайте и используйте публичный репозиторий, коллаборантами в который добавьте всех участников своей группы
- название репозитория: **rslang**, название ветки, в которой ведётся разработка - **develop**, ветка **master** пустая, содержит только README.md
- история коммитов должна отображать процесс разработки приложения. [Требования к коммитам](https://docs.rs.school/#/git-convention)
- демо-версия приложения размещается на `https://www.netlify.com/`, либо на другом подобном хостинге
- после окончания разработки или при наступлении дедлайна, создайте и замержите pull request из ветки develop в ветку master. [Требования к pull request](https://docs.rs.school/#/stage2?id=Описание-pull-request-должно-содержать-следующую-информацию). 

## Технические требования
- работа приложения проверяется в браузере Google Chrome последней версии
- использование jQuery не допускается
- нельзя использовать Angular/React/Vue 
- можно использовать bootstrap и css фреймворки
- можно использовать html и css препроцессоры

## Критерии оценивания
**Максимальный балл за задание ≈380**

- **Вёрстка, дизайн, UI +30**
  - вёрстка адаптивная, приложение корректно отображается и работает как на компьютерах, так и на мобильных устройствах +10
  - минималистичный дизайн, продуманность элементов, логичная и понятная структура приложения, ничего лишнего и всё под рукой +10
  - меню и информационные панели выдвижные, удобная  навигация, интуитивно понятные настройки +10

- **Изучение новых слов +110**
  - в настройках приложения пользователь может [указать](https://s8.hostingkartinok.com/uploads/images/2020/03/d0abe3023033e625754fcfbae5368dbf.png) количество новых слов, которые планирует выучивать за день а также максимальное количество карточек на день. Это число не будет превышено, даже если ещё есть карточки, ожидающие повторения. Когда дневная норма выполнена, об этом выводится [уведомление](https://s8.hostingkartinok.com/uploads/images/2020/03/6d81d7286f579309cea93842a746182f.png) +10
  - в настройках приложения пользователь может указать какая информация о слове выводится на странице, выбирая из следующих пунктов: перевод слова, предложение с объяснением значения слова, предложение с примером использования изучаемого словом. Хотя бы один пункт должен быть отмечен. Также в настройках можно выбирать показывать ли на странице картинку-ассоциацию к изучаемому слову  +10
  - когда открывается [карточка с новым словом](https://s8.hostingkartinok.com/uploads/images/2020/03/5b65107b58b3d117f32a81c90a5e12ee.png), курсор находится в поле ввода, ширина поля ввода соответствует длинне изучаемого слова. Когда слово набрано, ввести его можно нажав на клавишу Enter или нажав на кнопку Дальше +10
  - после ввода слова звучит его произношение на английском языке, а также произношение предложений с объяснением слова и с примером использования слова, если они выбраны в настройках и отображаются на странице. Воспроизведение звука можно отключать и включать на странице приложения +10 
  - после ввода слова под текстом предложений с объяснением слова и с примером использования слова, если они выбраны в настройках и отображаются на странице, появляется их перевод. Перевод предложений можно отключать и включать на странице приложения +10   
  - если слово набрано без ошибок, происходит переход к следующей карточке с новым словом. Если слово было набрано с ошибками, в окне для ввода слова [отображается](https://s8.hostingkartinok.com/uploads/images/2020/03/48b74723066a49f0614a044c6b161b6a.png) изучаемое слово, в котором совпадающие буквы подсвечиваются зелёным, а несовпадающие красным или оранжевым цветом, в зависимости от количества ошибок. Затем изучаемое слово становится полупрозрачным, когда пользователь снова начинает вводить ответ, изучаемое слово исчезает с поля ввода +20
  - переходить к следующей карточке можно и не набирая изучаемое слово в поле ввода, просто нажимая на кнопку "Показать ответ" под изучаемым словом. Наличие этой кнопки на странице регулируется настройками приложения +10
  - слово можно исключить из изучения, нажав на кнопку "Удалить". Наличие этой кнопки на странице регулируется настройками приложения. Удалённые слова сохраняются на странице "Словарь", там их можно просмотреть. Возле каждого удалённого слова есть кнопка "Восстановить", которая возвращает его в перечень изучаемых слов +10
  - слово можно поместить в группу "Сложные". Наличие на странице кнопки, помещающей слово в группу "Сложные" регулируется настройками приложения. Помещённые в эту группу слова можно изучать отдельно от остальных.  Сложные слова сохраняются на странице "Словарь". Возле каждого сложного слова есть кнопка "Удалить из сложных", которая возвращает его в общий перечень изучаемых слов +10
  - на странице приложения присутствует шкала на которой отображается общее количество слов на сегодня и количество выученных слов. Цветом на шкале отображается прогресс изучения +10
  - общее количество слов на сегодня состоит из новых слов и слов, которые нужно повторить. У пользователя есть возможность изучать их не вперемешку, а выбрать для изучения только новые слова или только те слова, которые нужно повторить +10 
- **Сбор и визуальное представление статистики +40**
  - после выполнения дневной нормы выводится краткосрочная [статистика](https://s8.hostingkartinok.com/uploads/images/2020/03/3271a9fc3eea9cf97240187852a65bb9.png), в которой указывается количество пройденных карточек со словами, процент правильных ответов, количество новых слов, самая длинная серия правильных ответов +10
  - долгосрочная статистика представляет собой на котором отображается общее количество изученных слов за весь период и некоторые другие данные [пример](https://s8.hostingkartinok.com/uploads/images/2020/03/969d46f4636dfd1bfda1916e33117de7.png)  +10
  - для отображения графика использован canvas +10
  - на графике при наведении отображаются данные за каждый день изучения - дата и количество изученных слов +10
- **Реализация методики интервального повторения +60**  
  Ключевой элемент вашего приложения, определяющий насколько эффективным и полезным оно окажется. При определении интервалов повторения можно ориентироваться на настройки карточек Anki, внося в них свои коррективы. Методика интервального повторения должна учитывать как общие закономерности запоминания, так и результаты изучения слов пользователем, результаты мини-игр, определение пользователем индивидуальной сложности изучаемого слова. К сожалению, оценить возможно только некоторые формальные критерии.
  - под каждым изучаемым словом, после того, как оно угадано, появляются [кнопки](https://s8.hostingkartinok.com/uploads/images/2020/03/8a6b00541edb27415ec3974d96b35ba2.png) "Снова", "Трудно", "Хорошо", "Легко" или аналогичные, при помощи которых пользователь может указать индивидуальную сложность изучаемого слова. Наличие этих кнопок на странице регулируется настройками приложения +10 
  - если при изучении слова была допущена ошибка, или пользователь нажал на кнопку "Снова", карточка с ним вновь появится для изучения на текущей тренировке. Если в изучаемом слове была допущена ошибка в ходе мини-игры, карточка с ним появится на ближайшей тренировке +10
  - на промо-странице приложения присутствует описание набора правил, по которым определяется интервал, через который будет вновь показана карточка с изучаемым словом. Правила интервального повторения выглядят разумными и логичными, в ходе проверки не выявлено расхождения работы приложения с указанными правиламм +10
  - на странице "Словарь" есть [список](https://s8.hostingkartinok.com/uploads/images/2020/03/6eff90373dc1d7c7ea7fa06860f7a250.png) всех выученных слов с примером звучания слова, переводом, а также примерами предложений с объяснением значения слова, примером использования слова, картинкой-ассоциацией, если последние указаны в настройках +10
  - на странице "Словарь" возле каждого изучаемого слова указывается [прогресс изучения](https://s8.hostingkartinok.com/uploads/images/2020/03/b91fc43629f2d03a9d55fb388176a668.png), сколько раз это слово повторялось, когда повторялось в последний раз и когда будет повторяться снова +20
- **Мини-игры +110**
  - по умолчанию в мини-играх задействованы все выученные пользователем слова или первые 100 слов коллекции "4000 essential english words". Пользователь может изменять сложность мини-игр. Всего шесть уровней сложности, которым соответствуют шесть частей коллекции +10
  - ведётся статистика мини-игр, можно посмотреть сколько раз в какую мини-игру играли и с каким результатом +10
  - **"Саванна"** `https://lingualeo.com/ru/training/savannah`
    - игра в целом соответствует предложенному примеру, слова можно угадывають выбирая их как кликами мышкой, так и нажатием кнопок клавиатуры, ведётся учёт количества ошибок +10
    - слова, из которых выбирается нужное, относятся к одной части речи, имеют схожее написание (например, начинаются на одну и ту же букву) +10
    - игра практически точно воспроизводит указанный пример, по мере прохождения игры плавно изменяется цвет фона, анимации примера копируются или заменены аналогичными +10  
 
## Штрафные баллы
- не выполняются требования к pull request, репозиторию, названиям коммитов: -30 баллов 
- меньше 5 коммитов от каждого активного участника команды -30 баллов

## Материалы

## Информационные ресурсы
- Метод интервального повторения https://habr.com/ru/post/196448/
- Настройки программы Anki https://englishteacup.org/slovarnyj_zapas/programma-anki-nastrojka-kolod

## Cross-check
- инструкция по проведению cross-check: https://docs.rs.school/#/cross-check-flow

## Документ для вопросов
- документ для вопросов, связанных с выполнением задания: 
