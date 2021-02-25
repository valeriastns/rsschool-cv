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
