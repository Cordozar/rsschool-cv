1. Yury Samsonenko


![My foto](https://i.ibb.co/QrqtgxH/5-Y6r-KPvl402g-J6-PVS6-Od-NXIf-Hha-W56-Nd-LQs-H-8-H5-PCBz-Tqn-N1-CCy-Qy6-Yw-Nwkchledvi-BO-2.jpg)


2. Contacts:

   [ВКонтакте](https://vk.com/samson9797 'ВКонтакте')

   [Instagram](https://www.instagram.com/yura_samsonenko/ 'Telegram')

   [Telegram](https://t.me/YurySamsonenko 'Telegram')

   [Discord](https://discord.com/users/924872041981689878/ 'Discord')


3. My goal is to gain new knowledge, learn a new profession, change jobs. My strengths: the desire to understand the topic in detail, purposefulness and discipline.


4. Skills: I have some knowledge of html, css.


5. Task: Напишите функицию, которая принимает в качестве параметра текст (строку) и анализирует ее на количество символов без     пробелов, количество слов и определяет характер предложения (вопросительное, отрицательное, утвердительное). Характер предложения можно определить исходя из заключительного знака препинания. Если тип предлоежния не удалось пределить,присвоить свойству значение null. Собранные данные возвращаются в виде объекта следующего формата:

```
{
 allSymbols: 123,
 symbolsWithoutSpaces: 105,
 quantityOfWords: 23,
 sentenceType: 'question'
}
```
Solution:
```
function fun(str) {
let allSymbols = str.length; //всего символов

let symbolsWithoutSpaces = str.replace(/ /g, '').length; //символов без пробелов

function coutnWordsFun(str1) {
let a = str1.split(' ');
let b = a.filter((item) => item.length > 0);
let c = b.length;
return c;
}
let quantityOfWords = coutnWordsFun(str); //количество слов

function sentence(str2) {
if (str2[str2.length - 1] === '!') {
return 'восклицательное';
} else if (str2[str2.length - 1] === '?') {
return 'вопросительное';
} else if (str2[str2.length - 1] === '.') {
return 'утвердительное';
} else {
return 'null';
}
}
let sentenceType = sentence(str); //характер предложения

return {
allSymbols: allSymbols,
symbolsWithoutSpaces: symbolsWithoutSpaces,
quantityOfWords: quantityOfWords,
sentenceType: sentenceType,
};
}
console.log(fun('Сегодня на улице я видел собаку, которая бежала за котом!'));
```


6. No work experience


7. Completed higher technical education, front-end cours 2 months, self-study 4 months.


8. B1
