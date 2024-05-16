[![Build status](https://ci.appveyor.com/api/projects/status/00ktpuhnoo06fjhg?svg=true)](https://ci.appveyor.com/project/ajoq/image-manager)

https://ajoq.github.io/js-image-manager/

### Галерея изображений с проверкой URL

Приложение, которое разрешает пользователю вводить "Название изображения" и "URL" к нему:

![](./pic/gallery.png)

Функциональность:
1. Добавлять можно как по кнопке "Добавить" так и по клавише Enter
1. Если URL картинки валидный должно происходить создание блока для добавленной картинки. Соответственно, в блоке - картинка и элемент для удаления картинки
1. Если URL картинки не валидный, добавления происходить не должно, вместо этого под полем "Ссылка на изображение" должна появляться надпись "Неверный URL изображения"
1. После добавления поля должны очищаться
