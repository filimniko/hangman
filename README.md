   # "Виселица" – игра в слова.
   
   Принцип игры:  
   Игроку загадывается слово, которое он должен угадать, используя буквы алфавита и возможность совершить семь ошибок. Если игрок угадал слово до истечения всех 
   попыток, то он выиграл! (основана на игре ["Виселица"](https://ru.wikipedia.org/wiki/%D0%92%D0%B8%D1%81%D0%B5%D0%BB%D0%B8%D1%86%D0%B0_(%D0%B8%D0%B3%D1%80%D0%B0)#%D0%9F%D1%80%D0%B8%D0%BD%D1%86%D0%B8%D0%BF_%D0%B8%D0%B3%D1%80%D1%8B)).
   
   Данная консольная программа написана на высокоуровневом объектно-ориентированном языке программирования [Ruby](https://ru.wikipedia.org/wiki/Ruby).
   
   Для ее запуска потребуется установить:
   1. [интерпретатор Ruby](https://www.ruby-lang.org/ru/documentation/installation/) 
   2. менеджер для управления gem'ами - [Bundler](https://habr.com/ru/post/85201/)
   
   После установки всех необходимых утилит, необходимо набрать в консоли следующие комманды:
   1. Комманда для установки необходимых gem-файлов
   
   ```bundler instal``` 
   
   2. Запуск игры

   ```bundler exec ruby hangman.rb```
    
   Для добавления или изменения загадываемых слов нужно отредактировать файл `data/words.txt`.   
