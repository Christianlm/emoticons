# Emoticons #

* Authors: Chris Leo, Noelia Ruiz Martínez, Mesar Hameed, Francisco Javier
  Estrada Martínez

Під час використання цього додатка символи смайликів у тексті, що
промовляється, будуть замінені на їх більш зрозумілі описи.

Наприклад: «:)» промовлятиметься як «усміхнений смайлик», а емодзі
читатимуться словами, зрозумілими користувачеві.

Ви можете скористатися такими можливостями:

## Вставити смайлик ##

Sometimes an image is worth a 1000 words: use the new emoji to liven up your
instant message and to let your friends know how you’re feeling.

Якщо ви не знаєте символів для певного смайлика, цей додаток допоможе вам
вибрати його і вставити у ваш текст, наприклад у чат.

Натисніть NVDA+I, або оберіть у меню NVDA -> Інструменти пункт «Вставити емодзі» для вибору емодзі чи смайлика.

У цьому вікні ви зможете вибрати смайлик чи емодзі та переглянути смайлики,
які вас цікавлять:

*	Вікно редагування дозволяє фільтрувати пошук потрібного смайлика серед
  наявних смайликів.
*	За допомогою радіокнопок ви можете вибрати, які смайлики хочете
  переглянути: лише емодзі (alt+E), лише стандартні смайлики (alt + s) або
  всі доступні смайлики (alt + A).
*	У списку смайликів та емодзі (alt+L) відображаються три стовпці: назва
  смайлика, тип смайлика (стандартний смайлик чи емодзі), і символи, які
  йому відповідають.

Після натискання «Гаразд» смайлик чи емодзі скопіюється в буфер обміну і
його можна буде вставити у потрібний вам текст.

## Вставити символ ##

This dialog allows you to choose one of the symbols available in the
Punctuation/symbol pronunciation dialog of NVDA. You can use the Filter edit
box or the arrow keys to select an item from the symbols list.

Якщо ви хочете скопіювати різні символи, скористайтеся кнопкою Додати, щоб
додати їх до поля редагування Символи для копіювання.

Then, press OK and the selected emoji or symbol, or the symbols contained in
the mentioned edit box, will be copied to your clipboard, ready for pasting.

## Призначити жести на символи ##

From NVDA's menu, Preferences submenu, Input gestures dialog, category
Insert symbols or Copy symbols, you can configure NVDA to type symbols
through associated gestures.

Ви можете зменшити кількість представлених символів у полі редагування, щоб
швидше розгортати цю категорію.

## Словник смайликів ##

Додаток Emoticons дозволяє мати різні словники для кожного окремого
конфігураційного профіля.

Це означає, що ви можете створити або відредагувати певний словник для
кожного окремого профілю.

У меню NVDA -> «Параметри» -> «Мовленнєві словники» -> «Словники смайликів та емодзі» ви можете додавати нові смайлики чи емодзі або змінювати наявні.

Після збереження змін читання смайликів, вони будуть застосовані лише до
того профілю, який ви зараз редагуєте.

Наприклад, ви можете захотіти, щоб NVDA промовляла користувацькі смайлики
лише в програмі XxChat, але не в інших програмах обміну повідомленнями: ви
можете це зробити, створивши профіль для програми XxChat та призначити для
неї мовленнєвий словник із меню «Мовленнєві словники» -> «Словник
Emoticons». Див. Нижче параметри смайликів для профілів конфігурації.

Натиснення кнопки "Зберегти і експортувати словник" збереже файл словника з
іменем emoticons.dic у вашу папку користувацької конфігурації, у вкладену
папку speechDicts.

Ім’я та місце розташування файла словника базуватиметься на імені
редагованого конфігураційного профіля, і буде відображено у заголовку
діалогового вікна «Словники Emoticons».

## Налаштування Emoticons ##

У меню NVDA -> «Налаштування» -> «Налаштування Emoticons» ви можете налаштувати поведінку додатка для поточного конфігураційного профіля.

На панелі налаштувань додатка Emoticons ви можете вибрати, чи повинен словник автоматично вмикатись при переході на профіль, який ви зараз редагуєте. Типово цей параметр відключений у нормальній конфігурації NVDA і у всіх нових профілях.

Можна також вказати, чи промовляти емодзі так, як вони прописані у
додатку. Це може знадобитися, якщо ви хочете, аби NVDA промовляла емодзі
так, як вони прописані в її типовій конфігурації.

If symbols inserted using associated gestures aren't spoken in your system,
even when NVDA is configured to speak typed characters, you can try to
enable a checkbox to ensure the speaking of inserted symbols.


У цьому діалоговому вікні можна також обрати, чи будуть видалені з додатка
словники, які не використовуються, наприклад, пов’язані з неіснуючими
профілями, при його деактивації.

## Клавіатурні команди: ##

Це типові ключові команди, ви можете їх редагувати або додавати нові, щоб
відкрити панель налаштувань додатка Emoticons або словники Emoticons:

* NVDA+E: перемкнути між промовлянням тексту як написано, або з заміненими
  зрозумілими описами.
* NVDA+I: викликає діалог для вибору смайлика, який ви хочете вставити.
* Не призначено: викликає діалог вибору бажаного для копіювання символа з
  доступних в NVDA.
* Не призначено: відкрийте для перегляду повідомлення з символом у позиції
  переглядового курсора, щоб весь опис можна було переглянути в режимі
  огляду.
* Не призначено: відкрийте для перегляду повідомлення з символом у позиції
  системної каретки, щоб весь опис можна було переглянути в режимі огляду.

Note: On Windows 10 and higher, it's also possible to use the built-in emoji
panel.

## Changes for 34.0.0

* Added ability to copy to clipboard, and paste individual symbols, useful
  when gestures associated with Insert symbols scripts don't work.


## Changes for 33.0.0

* Fixed bug in Save and export dictionaries.
* Added copy and close buttons to messages presented in browse mode.
* When using commands to insert symbols, they may be spoken according to the
  speak typed characters option.

## Changes for 22.0.0 ##

* Requires NVDA 2023.2 or later.

## Changes for 17.0 ##

* Додано можливість призначити жести на введенняя символів.
* Додано можливість одночасного копіювання різних символів.

## Changes for 16.0 ##

* Compatible with NVDA 2023.1.

## Changes for 15.0 ##

* Requires NVDA 2022.1 or later.
* Неможливо використовувати на захищених екранах.

## Зміни у версії 14.0 ##

* Додаток тепер сумісний з NVDA 2021.1.

## Зміни у версії 13.0 ##

* Виправлено помилки у діалозі вставки емодзі.
* Додано можливість вибирати для вставки символи, доступні в діалозі «Вимова
  символів і знаків пунктуації» NVDA.

## Зміни у версії 12.0 ##

* Вимагає NVDA 2019.3 чи новішу.

## Зміни у версії 11.0 ##

* Після оновлення додатка словники, збережені в попередній його версії,
  будуть автоматично скопійовані в нову версію, якщо ви не віддасте перевагу
  імпортуванню словників, збережених у головній папці словників NVDA.
* Коли відображається символ, де розташована системна каретка або
  переглядовий курсор, слова «Символ» та «Заміна» використовуються для
  розмежування самого символа та його опису в режимі перегляду.

## Зміни у версії 10.0 ##

* Додано команди для перегляду символа в позиції системної каретки чи
  переглядового курсора. Жести на ці команди можна призначити у меню NVDA ->
  «Параметри» -> «Жести вводу», у категорії «Перегляд тексту».

## Зміни у версії 9.0 ##

* Додано можливість вибору вимови емодзі так, як вони прописані у додатку.
* Використовується відповідне кодування для імен словників, виправлення
  помилок, коли вони містять певні символи.
* Перекладені зведення про додаток належним чином відображаються в заголовку
  довідкового розділу менеджера додатків.
* Додано примітку, де згадується панель емодзі, яка доступна у Windows 10.

## Зміни у версії 8.0 ##

* Сумісний з NVDA 2018.3 або новішою (необхідно).

## Зміни у версії 7.0 ##

* Діалогове вікно налаштувань додатка переміщено на панель в налаштуваннях
  NVDA, там також відображено назву поточного конфігураційного профілю.
* Меню керування смайликами було видалено: тепер Вставити смайлик можна з
  меню NVDA -> «Інструменти», а Налаштувати смайлики можна у мовленнєвих
  словниках -> «Словники смайликів та емодзі».
* Вимагає NVDA 2018.2 або новішої.

## Зміни у версії 6.0 ##

* Додано підтримку конфігураційних профілів.
* У NVDA 2017.4 або новіших версіях налаштування конфігурації та
  користувацькі словники автоматично змінюватимуться відповідно до обраних
  профілів. У 2017.3 або старіших версіях ви можете застосувати зміни,
  перезавантаживши плагіни (натискання клавіш control+NVDA+f3).
* Якщо ви вирішите імпортувати налаштування під час оновлення додатка,
  застарілі файли (emoticons.ini та emoticons.dic) будуть видалені або
  адаптовані до цієї версії.

## Зміни у версії 5.0 ##

* Додано підтримку емодзі.
* У діалог «Вставити смайлик чи емодзі» додано поле для фільтрування та
  перемикачі, які дозволяють вибрати типи смайлів для відображення.
* Використовується guiHelper для активації налаштувань і вставки смайлів:
  необхідна NVDA 2016.4 або новіші версії

## Зміни у версії 4.0 ##

* Якщо діалог вставки смайлів відкритий коли активне інше вікно з
  налаштуваннями, NVDA видасть відповідне повідомлення про помилку.


## Зміни у версії 3.0 ##

* В діалозі налаштувань смайликів тепер можна вказати, що зразок
  відповідатиме смайлику, якщо він - лише ціле слово, згідно з мовленнєвими
  словниками NVDA 2014.4.


## Зміни у версії 2.0 ##

* Довідка додатка доступна у менеджері додатків.


## Зміни у версії 1.1 ##

* Видалено смайлики, які дублювалися.
* Додано деякі смайлики.

## Зміни у версії 1.0 ##

* Перша версія.

[[!tag dev stable]]

