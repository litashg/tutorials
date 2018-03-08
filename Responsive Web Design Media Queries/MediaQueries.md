# Медіа запити в Bootstrap 3. Media queries Bootstrap 3.

У Bootstrap зміна позиціонування елементів відбувається у момент перетину контрольної точки.

## Система сітки
У Bootstrap 3 система сітки має чотири класи:

- **xs** (для смартфонів - екрани шириною менше за 768px)
- **sm** (для планшетів - екрани від 768px шириною включно)
- **md** (для невеликих ноутбуків - екрани від 992px шириною включно)
- **lg** (для ноутбуків та стаціонарних пк - екрани від 1200px шириною включно )

## Медіа запити
У випадку, якщо нам недостатньо класів стандартної сітки ми використовуємо медіа запити.

Додаю список медіа запитів для Bootstrap 3, як для людей, що дотримуються принципу **"Мобільність на першому місці"(Mobile First)**, так і для тих, хто цього не робить. 

Властивість **@media** дозволяє вказати точки які обмежуватимуть використання стилів.

**Min-Width**: За допомогою цієї властивості ми примінятимемо стилі тільки у випадку, коли розмір екрану більший або тотожний вказаному.  


```
/*==================================================
=            Bootstrap 3 Media Queries             =
==================================================*/

    /*==========  Mobile First Method  ==========*/

    /* Custom, iPhone Retina */ 
    @media only screen and (min-width : 320px) {

    }

    /* Extra Small Devices, Phones */ 
    @media only screen and (min-width : 480px) {

    }

    /* Small Devices, Tablets */
    @media only screen and (min-width : 768px) {

    }

    /* Medium Devices, Desktops */
    @media only screen and (min-width : 992px) {

    }

    /* Large Devices, Wide Screens */
    @media only screen and (min-width : 1200px) {

    }

    /*==========  Non-Mobile First Method  ==========*/

    /* Large Devices, Wide Screens */
    @media only screen and (max-width : 1200px) {

    }

    /* Medium Devices, Desktops */
    @media only screen and (max-width : 992px) {

    }

    /* Small Devices, Tablets */
    @media only screen and (max-width : 768px) {

    }

    /* Extra Small Devices, Phones */ 
    @media only screen and (max-width : 480px) {

    }

    /* Custom, iPhone Retina */ 
    @media only screen and (max-width : 320px) {

    }
```
