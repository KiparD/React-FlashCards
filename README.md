## React Flash Card App

This simple react application is used for basic flashcard memorization.

![skreenshot](https://github.com/KiparD/React-FlashCards/blob/master/src/img/preview.jpg)

## Getting started

Demo JSON available in `src/Data/cards.json`. This app requires a Firebase database containing structured data for any card you would like to study. The format the application expects out of the box is, as an example:

```
{
  "cards": [
    {
      "id": 1,
      "title": "CSS: margin",
      "val": "Свойство CSS, Внешний отступ от элемента.",
      "prop": ["margin-top: ", "margin-right: ", "margin-bottom: ", "margin-left: "]
    },
    {
      "id": 2,
      "title": "CSS: padding",
      "val": "Свойство CSS, Отступ от контента до крайней граници элемента.",
      "prop": ["padding-top: ", "padding-right: ", "padding-bottom: ", "padding-left: "]
    },
    {
      "id": 3,
      "title": "CSS: cursor",
      "val": "Свойство CSS, Вид курсора при наведении на объект.",
      "prop": ["cursor: pointer; ", "cursor: auto; ", "cursor: none; ", "cursor: wait; ",
               "cursor: no-drop; ", "cursor: w-resize; ", "cursor: help; ", "..."]
    }, 
        ...

```
Place firebase connection data in `src/Config/Firebase/db_config.js` in the following format:
```
export const DB_CONFIG = {
    apiKey: YOUR_API_KEY,
    authDomain: YOUR_AUTH_DOMAIN,
    ...etc.
}
```
![skreenshot](https://github.com/KiparD/React-FlashCards/blob/master/src/img/preview-back.jpg)

## Author
This project was created by video Wes Doyle to learn React. 
