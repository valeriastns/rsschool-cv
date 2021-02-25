# Valeria Sharybina

***

## **Contacts**

* e-mail: valeriastanis@gmail.com

* phone: +31687574589

### **About**

I am a self-taught beginner  web-developer with a strong aim to evolve towards front-end development. I always love to create something, especially something beatiful and useful. My hobbies are all about creating things. That is why I decided to bond myself with frontend-development.

### **Skills**

* HTML5, semantic markup,BEM
* CSS3,flexbox,grid,responsive design
* SASS/SCSS
* JS basics
* Gulp
* GIT,GitHUB
* SQL basics
* CMS Wordpress
* Avocode,Figma

### **Code example**

```javascript
'use strict';

window.addEventListener('DOMContentLoaded', function () {
    
    const images = [
        'https://cdn.pixabay.com/photo/2014/04/13/20/49/cat-323262_1280.jpg',
        'https://cdn.pixabay.com/photo/2017/07/25/01/22/cat-2536662_1280.jpg',
        'https://cdn.pixabay.com/photo/2017/11/14/13/06/kitty-2948404_1280.jpg',
        'https://cdn.pixabay.com/photo/2016/03/28/10/05/kitten-1285341_1280.jpg',
        'https://cdn.pixabay.com/photo/2016/12/30/17/27/cat-1941089_1280.jpg'];

    const slides = document.querySelector('.slides');

    let currentIndex = images.length -1 ;
    showNextslide();

    function showNextslide () {
        if (currentIndex == images.length -1) {
            currentIndex = 0;
        } else {
            currentIndex++;
        }
        slides.style.backgroundImage = "url('" + images[currentIndex] + "')";
    }

    slides.addEventListener('click', function () {
        showNextslide();
    });
});
```

### **Experience**

Course projects:
<https://github.com/valeriastns>

Freelance projects(based on cms wordpress):

* <https://anothersweets.com.ua/>
  (<https://github.com/valeriastns/another_cake>);

* <http://chrisnesterova.com/>
  (<https://github.com/valeriastns/christinanesterova-portfolio>);

### **Education**

* learn.javascript.ru

* codewars,ebabit

[Web-developer course](https://www.udemy.com/certificate/UC-6793e1d0-69ff-4940-8c68-ae342d48892a/)

[CMS Wordpress course](https://www.udemy.com/certificate/UC-c093f1bd-58f0-4ef9-a2f1-1ace40c21525/)

[JavaScript basics course](https://www.udemy.com/certificate/UC-913507af-846e-4646-a07f-518bdb7d658b/)

### **English level**

I estimate my english level as **intermidiate**/**upper-intermidiate**. Currently I'm living in Amsterdam so I always have practice around. Furthermore I mostly watch tv-shows or youtube channels in English.
