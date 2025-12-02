Опис проєкту
Цей проєкт демонструє базову роботу Android на Java з використанням ViewPager2 та трьох свайпових екранів.
На кожному екрані показаний текст із власним шрифтом (montserrat_semibold.ttf), а також встановлені кольори фону для сторінок.
Проєкт адаптований для запуску на Mac M2 та сучасному Android SDK.
Використані технології
Java 17
Android Gradle Plugin 8.6.0
Gradle 8.9
AndroidX (ViewPager2, Material, AppCompat, ConstraintLayout)
Custom Font (montserrat_semibold.ttf)
Runtime permission для камери (як приклад)
Структура проєкту
app/
 ├─ src/main/java/com/example/myapplication1/
 │    ├─ MainActivity.java
 │    ├─ PageAdapter.java
 │    └─ PageFragment.java
 ├─ src/main/res/layout/
 │    ├─ activity_main.xml
 │    └─ fragment_page.xml
 └─ src/main/res/font/
      └─ montserrat_semibold.ttf
Інструкція зі збірки та запуску
Клонування проєкту з GitHub
git clone <URL репозиторію>
Відкрити у Android Studio
File → Open → оберіть кореневу папку проєкту
Sync Gradle
Android Studio запропонує натиснути Sync Now після відкриття
Запуск на емуляторі або фізичному пристрої
Для емулятора: Tools → AVD Manager → створіть Pixel девайс
Для фізичного пристрою: увімкніть Developer options → USB debugging
Права доступу
Проєкт приклад роботи з камерою, запит дозволу відбувається у MainActivity
Що змінювали у проєкті (для GitHub-версії)
Оновлено Gradle Wrapper до 8.9
Оновлено Android Gradle Plugin до 8.6.0
Встановлено JDK 17
Встановлено compileSdk/targetSdk/minSdk на сучасні значення
Перевірено сумісність із AndroidX
Додано власний шрифт та три екранні фрагменти з ViewPager2
Результат
Три екранні сторінки зі свайпом ліво/право
Кожна сторінка має свій колір та текст
Текст відображається власним шрифтом
Приклад runtime permission для камери
