## Ім'я
Dmytry Kyshnir

## Контакти
Email: dmytry_dev@outlook.com

## Коротка інформація про мене
Я працюю бухгалтером в сільськогосподарській компанії, але хочу змінити своє життя і спробувати щось нове.

## Навички
- HTML
- CSS
- SCSS
- JavaScript

## Приклад коду
```javascript
function firstNonRepeatingLetter(s) {
  let result = "";
  let ls = s.toLowerCase();
  for (let i = 0; i < ls.length; i++) {
    const char = ls.charAt(i);
    if (ls.indexOf(char) === ls.lastIndexOf(char)) {
      result = s.charAt(i);
      break;
    } else result = "";
  }
  return result;
}

## Мови
- Українська (native)
- Англійська (B1)
- Російська (С1)
