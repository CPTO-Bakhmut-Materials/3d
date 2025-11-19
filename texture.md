### Мета заняття
Навчитися додавати текстури

### Виконання
1. Відкрити проектний файл **donut.blend** з яким ми працювали попереднього разу


1. В **Outline** панелі обрати **Glaze**

    ![outline](assets/texture/outline.png)


1. Перемкнутися в панелі властивостей на **Material** додати новий матеріал 

    ![props](assets/texture/properties.png)


1. Виберіть новий колір для Glaze змінивши **Base Color**

    ![base](assets/texture/base-color.png)


1. Виконайте заміну кольору і для об'єкту **Donut**

    ![donut](assets/texture/base-donut.png)


1. Додати площину до сцени **[Shift + A]** (Mesh -> Plane)

    ![plane](assets/texture/add-plane.png)


1. Відмаштабувати площину зробивши її більшою **[S + Mouse]**

    ![scale](assets/texture/scale.png)


1. Для зручності роботи з об'єктами потрібно згрупувати **Donut** та **Glaze** разом. Для цього в **Outline** потрібно виділити **Donut**, затиснувши **[Shift]** клікнути на **Glaze** та не знімаючи виділення натиснути комбінацію **[Ctrl + P]**. Результат повинен виглядати як на картинці

    ![outline-parent](assets/texture/outline-parent.png)


1. Виділити **Donut** і перетягнути його по Z осі так щоб він знаходився на площині

    ![move-object](assets/texture/move-object.png)


1. Скачати з онлайн ресурсу текстуру мармуру - [посилання](https://ambientcg.com/view?id=Marble012). Розархівувати все.

    ![tex](assets/texture/marble.png)


1. Перемикаємося на вкладку **Shading**

    ![sha](assets/texture/shading-button.png)


1. В **Outline** виділяємо Plane та натискаємо **+ New** кнопку в редакторі шейдера

    ![sha](assets/texture/shader-plane.png)



1. Тепер під'єднаємо текстури до шейдера. Якщо затиснути кнопку миші і відтягнути кружечок(на прямокутниках з правої сторони) то у нас з'явиться контестне меню в якому ми зможемо обрати **Image Texture**

    ![](assets/texture/img-tex.png)


1. Модифікуємо новий блок який ми додали - натискаємо **Open** і знаходимо в видобутому архіві - **Marble012_4K-PNG_Color.png** 

    ![](assets/texture/open-img.png)

1. Додаємо ще блоки для Roughness Normal і підключаємо відповідні файли. Повинно вийти так як на малюнку.

    ![shader](assets/texture/shader.png)

1. Перемкніть **Color Space** в **Non-Color** для Roughness та NormalGL

    ![color](assets/texture/color.png)

1. Змінемо текстуру самого бублика додавши трохи деталей. В **Properties** знову переходимо на Material і знаходимо **Base Color**. Клікаємо на цяточку біля і обираємо **Image Texture**. Натискаємо на **New**

    ![base color](assets/texture/basecolor.png)

1. В меню змінюємо Name на Base та Color на оранжевий

1. Переключитися на "Texture Paint", змінити колір пензля на білий

    ![brush](assets/texture/texture-paint.png)

1. Провести пензликом по текстурі

    ![texture-final](assets/texture/texture-final.png)

1. Зберегти текстуру **Image** -> **Save**

    ![save](assets/texture/save.png)

### Результат
Зберегти все. Обов'язково зберегти текстуру бублика(ту яку малювали вручну)