# Машина Тюринга

Одноименный симулятор на консоле. Альфа версия (возможно очень забагованная).
Что он умеет:
- загружать команды с консоли, CSV и JSON файлов
- Симулировать работу машины

# Гайд
## 0. Скачайте
Скачайте или скопируйте turing_machine.py сверху

## 1. Заполните таблицу

Самый простейший способ:

Создайте какой-нибудь csv файл (например commands.csv), откройте и напишите туда таблицу из вашего задания

Пример заполнения .csv файла (слева задание, справа таблица которую вы заполняете):

<p float="left">
  <img src="https://user-images.githubusercontent.com/72970300/209151891-3a066463-26b7-431e-8cf8-6a7e01c49cbc.png" width="400" />
  <img src="https://user-images.githubusercontent.com/72970300/209152595-feec5be8-7862-486d-a320-d4d2a610af52.png" width="400" /> 
</p>

### Правила заполнения
- П (право), Л (лево) должны заменяться на right и left соотвественно
- Пустые ячейки и команды q0 должны быть заменены на stop так как это где программа останавливается
- Данные в команде должны разделятся запятыми, как показано на рисунке справа
## 2. Запустите файл
Запустите файл turing_machine.py (csv файл должен находится в той же папке). Если вы чайник который и это не умеет, то посмотрите [как перейти в директорию где ваш файл](https://ru.wikihow.com/%D0%BF%D0%B5%D1%80%D0%B5%D0%BC%D0%B5%D1%89%D0%B0%D1%82%D1%8C%D1%81%D1%8F-%D0%BF%D0%BE-%D0%BA%D0%B0%D1%82%D0%B0%D0%BB%D0%BE%D0%B3%D0%B0%D0%BC-%D0%BF%D0%BE%D1%81%D1%80%D0%B5%D0%B4%D1%81%D1%82%D0%B2%D0%BE%D0%BC-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D0%BD%D0%BE%D0%B9-%D1%81%D1%82%D1%80%D0%BE%D0%BA%D0%B8) и [как запустить](https://otus.ru/nest/post/1744/#:~:text=%D0%9A%D0%B0%D0%BA%20%D0%B7%D0%B0%D0%BF%D1%83%D1%81%D1%82%D0%B8%D1%82%D1%8C%20%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5%20Python%20%D0%B2%20%D0%BF%D0%B0%D0%BA%D0%B5%D1%82%D0%BD%D0%BE%D0%BC%20%D1%80%D0%B5%D0%B6%D0%B8%D0%BC%D0%B5%3F)

При запуске появится:
```
        Выберите откуда загрузить данные

        1)Из консоли
        2)Из JSON
        3)Из CSV
        
        Номер вашего выбора: 
 ```
Наберите 3 и Enter

после напишите имя CSV файла (который вы создали)

Потом напишите начальную ленту, начальной лентой может быть 001110110, 10111111 или 111\*1110\*1 

**a0 считается как два отдельных знака! Используйте 0**

Потом напише с какой вы хотите начать (считая слева)

Нажмите Enter и машина сработает

# Проблемы?
Если у вас проблемы напишите в whatsapp (возможно отвечу)


