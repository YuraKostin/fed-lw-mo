# Калькулятор. Часть 4. Хранение дополнительных данных в html

Да, мы смогли прочитать текстовые значения с кнопок, но чаще всего нам нужно
выводить одни данные, а хранить в памяти(или ещё где-то) совершенно другие.

И хотя в данном случае данные у нас будут практически идентичны, с техникой
хранения данных в html имеет смысл познакомиться.
 
> Не знаю как вы, а я для кнопок использовал `<button>`.
> В случае, если вы использовали `<input type="button" value="1">`, 
то суть не особенно меняется. Разве что вместо `textContent` вы использовали
`value` для получения значения кнопки. 

## Хранение дополнительных данных в html
В атрибутах html можно задавать практически что угодно, но есть атрибут,
с помощью которого мы на первых порах будем решать поставленную задачу - 
[data attributes](https://developer.mozilla.org/ru/docs/Web/Guide/HTML/Using_data_attributes)


## Задача

Вместо получения данных из `textContent` или `value` читать 
`операции` и `цифры` из data атрибутов.