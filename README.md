
# gitPython
Example for xivol

## Нагорский Артём и Меньшикова Екатерина

Предыстория - родители Кати были в США, где в одном из заведений давали игру-головоломку, пока те ждут свой заказ. Им она показалась увлекательной, и они решили купили себе такую же домой, чтобы играть здесь. Учитывая прежде сказанное, а также то, что эта игра-головоломка отсутствует в интернет-пространстве, как вирутальная игра, мы решили создать ее компьютерную версию. Мы имеем треугольник с 15-ю отверстиями (в вершине 1 отверстие, во 2 строке 2 отверстия, в 3 - 3 и т.д.) и 14 "гвоздиков", которые помещаются во все отверстия, кроме одного в вершине, перед началом игры. За 1 ход игрок перепрыгивает через 1 соседний "гвоздик", если за ним нет еще одного, тем самым "гвоздь", через который перепрыгнули, убирается с поля. Суть игры заключается в том, что бы в треугольнике остался лишь 1 "гвоздик". При первом прочтении условий игры кажется, что игра лёкая, однако подвох заключается в том, что без обдумывания каждого вашего хода, вы придёте в тупик уже после 2-го хода! Также хотим заметить, что эта игра-головоломка имеет огромное количество исходов событий (Существует 6816 решений этой головоломки), поэтому не волнуйтесь об "одноразовости" игры.

## Барашев Владимир 

В планах сделать игру на основе "Space Invaders" с улучшениями.
Есть представление реализации и некоторых интересных механик.
команды нет(
Если есть возможность хотелбы делать один.
В команде Илья

## Савченко Михаил
### Городской бой

Это 2D-игра с видом сверху, где игрок управляет героем, защищающим город от волн преступников. Герой сражается на разных уровнях города, используя оружие и укрытия. Главная цель — выжить как можно дольше, сражаясь с преступниками, спасая заложников и собирая ресурсы.

Управление: Герой движется по карте (WASD) и стреляет (мышь или отдельная клавиша).
Цели уровня: Защитить заложников. Убить всех врагов. Собрать ресурсы (аптечки, патроны, деньги). Игрок может взаимодействовать с объектами: прятаться за укрытиями, открывать двери, разминировать бомбы.
Противники:

Бандиты: Обычные враги с пистолетами.
Снайперы: Укрываются и стреляют на расстоянии.
Боссы: Главари банд с уникальными атаками и большим количеством здоровья.
Герой: Выбирай персонажа с разными навыками: Например, снайпер (точный урон на расстоянии), танк (выдерживает больше урона), инженер (может ставить ловушки). Возможность прокачки: улучшение оружия, брони и скорости.

Уровни:
Городские улицы, парки, склады, офисы.
Каждый уровень содержит уникальные задачи, например:
Заложники: Спасти людей до истечения времени.
Бомбы: Обезвредить до взрыва.
Оборона: Удерживать позицию против волн врагов.
Бонусы:

Аптечки для восстановления здоровья.
Патроны и улучшение оружия.
Бронежилеты, увеличивающие защиту.

Механики:

Патроны: Ограниченный запас, который нужно пополнять.
Тактика: Используй укрытия, чтобы избежать урона.
Ловушки: Возможность расставлять мины или активировать ловушки на карте.
Графика и звуки:
Простая графика с видом сверху.
Реалистичные звуки выстрелов, шагов и взрывов.

## Илья Любавский, Роман Мельниченко

Хочу сделать игру аналог doodle jump
суть такова нужно ~~грабить корованы~~ прыгать по платформам вверх и набирать счет
еще будут различные враги и возможность их уничтожать
еще будут различные способности немного сюжета и тд
- работаю в команде с Романом Мельниченко

## Валиева Ева, Борисов Антон

Игра в жанре аркады с элементами стратегии, где игрок управляет маленьким рыцарем на клетчатом поле, сражаясь с врагами, избегая ловушек и преодолевая уровни, чтобы спасти своё королевство. Каждый уровень сложнее предыдущего, с новыми врагами, загадками и механиками.

## Шарков Владимир

Проект «Крестики-нолики»
Проект предполагает создание игры «Крестики-нолики» для двух игроков или для одиночной игры против бота.
Я хочу сделать так, чтобы пользователь мог менять цвета крестиков и ноликов, а также игрового поля.
Также хочу сделать возможность просмотра статистики матчей против бота (победы, поражения и винрейт).
Для бота будут прописаны несколько уровней сложности, вероятнее всего их будет 3.
Будут использоваться библиотеки Pygame, random, sqlite3, и, возможно, другие.
Также, чтобы хранить настройки кастомизации и статистику игрока, будут использованы файлы и БД.

Общий вид игры будет примерно таким: при запуске появляется окно с 3 кнопками: «Играть», «Кастомизация», «Статистика».
При нажатии на кнопку «Играть» в окне появятся 2 кнопки: «С ботом» и «2 игрока», и далее при нажатии на любую из кнопок
начинается игра с ботом или 1 на 1 в зависимости от того, что вы выбрали.
При нажатии на кнопку «Кастомизация» будет доступно меню выбора цветов для крестиков, ноликов и доски
(над его дизайном я подумаю чуть позже).
При нажатии на кнопку «Статистика» будет выведена таблица (над дизайном которой я также подумаю чуть позже) с данными
игр против бота каждого уровня сложности. Также будет предусмотрена кнопка «Сбросить данные».

## Коноплева Анжелика, Кечуткин Игорь, Кривоногов Андрей

сюжетная игра с элементами хоррора. Команда: Андрей и Игорь


## Гончарова Вера, Варницкая Мария

**Описание игры**

**Сюжет игры:**

Шизофреник видит галлюцинации перед смертью. Он думает что он попал в город, где взорвалась АЭС. Всех эвакуировали кроме него. Он пытается выжить и дойти до спасателей или просто безопасной зоны. В игре есть отсылки, которые намекают нам на состояние персонажа и на то, что все происходящее только в голове больного. В конце он просто умирает.

Первая локация - лес

Состоит из деревьев и кабинки общественного туалета.
 
Ходишь по лесу и находишь общественный туалет,  нажимаешь на него и оказываешься в метро.

Спрайты:
Небо дневного светло-голубого цвета.
Деревья с листьями(время года-лето)
Кабинка туалета деревянная с дверью с сердечком.

**Вторая локация - метро**

Состоит из большого туннеля и разными рисунками на стенах, которые являются частями головоломок. 

Игрок должен идти вперед, пока не найдет дверь, для открытия которой нужно решить головоломку. 

-Если гг слишком долго находиться на одном месте, появляется картинка монстра, которая не может нанести урон игроку. Задача монстра напугать гг, чтобы тот продолжил играть

Спрайты:
В конце локации метро должна быть лестница.
Туннель состоит из рельс и железных стен с деталями(болтики, пластины)
Двери железные 

**Третья локация - переулок в городе**

Состоит из домов, дорогой.

Гг решает головоломку и идет дальше

Спрайты:
Небо темного грозного цвета.
Дома серые с черными окнами и с заколоченными дверьми.
Дорога состоит из плиток. 

**Четвертая локация - пиксельная комната**

Головоломок в этой локации нет

Гг сталкивается с монстром, который гонится за ним. Появляется надпись RUN. Игрок должен бежать вперед пока не появится белый свет. Игра заканчивается.
[головоломки.pdf](golovolomka_goncharova.pdf)
-
## Тимофей Кадченко
Описание: игра напоминает Space Shooter. Суть в управлении космическим кораблем и уничтожении врагов на пути. Создается иллюзия движения корабля. Несколько уровней сложности(пока не определился по кол-ву). Будет возможность улучшения/усиления корабля(нпр скорость пуль и урон). С возрастанием уровня увеличивается хп у обьектов. Возможно будет 3 жизни в течение всего раунда. При задевании врага будет сниматься 1 жизнь.

Спрайт: скорее будет генерация рандомного космического спрайта в разных цветах и контрастах

жаль одному низя(
