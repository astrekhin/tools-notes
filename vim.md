# Основные команды, используемые в редакторе vim
Для корректного ввода команд в редакторе vim должна быть включена раскладка клавиатуры на латинице.
```bash
# Запуск встроенного обучения vim
$ vimtutor
$ vimtutor ru

# Создать новый файл в редакторе vim
# vim filename <ENTER>
$ vim text.txt
$ vim hello.py
```
  |   Команда   |                 Описание                        |
  |-------------|-------------------------------------------------|
  |    ESC      | Обычный режим (Normal Mode)                     |
  |    :w       | Сохранить редактируемый файл                    |
  |  :w <name>  | Сохранить файл под новым именем                 |
  |     :wq     | Сохранить файл под новым именем                 |
  |     :q      | Выйти из редактора, если не было изменений      |
  |     :q!     | Выйти из редактора без сохранения изменений     |
  | h, j, k, l  | Перемещение                                     |
  |      d      | Удалить выделенный блок                         |
  |      y      | Скопировать выделенный блок                     |
  |      p      | Вставить скопированный текст (после курсора)    |
  |      P      | Вставить скопированный текст (до курсора)       |
  |      x      | Удалить символ под курсором                     |
  |      w      | Перейти к следующему слову                      |
  |      b      | Возвратиться к предыущему слову                 |
  |      e      | Переместиться в конец слова                     |
  |      i      | Вставка текста под курсором (Insert Mode)       | 
  |      A      | Вставка текста в конце строки                   |
  |      dw     | Удалить слово до первого символа следующего     |
  |      de     | Удалить символы до конца слова                  |
  |      d$     | Удалить до конца строки                         |
  |      0      | Переход в начало строки                         |
  |      3w     | Переход на три слова вперед                     |
  |      5b     | Переход на пять слов назад                      |
  |      d3w    | Удалить 3 последующих слова                     |
  |      dd     | Удалить всю строку                              |
  |      3dd    | Удалить три последующие строки                  |
  |      r      | Замена символа                                  |
  