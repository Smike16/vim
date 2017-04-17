# VIM

# Command Mode

Чтобы войти в комманд мод нужно нажать `ESC`. лучше забиндить
Чтобы вернуться в режим вставки - нажать `i` или `a`

#### Движение

| Shortcut | Description |
| ------ | ------ |
| `h`, `j`, `k`, `l` | Перемещение |
| `w` | в начало следующего слова (shift optional) |
| `e` | в конец следующего слова (shift optional) |
| `b` | в начало предыдущего слова (shift optional) |
| `$` | переместиться в конец строки |
| `^` | переместиться в начало строки |
| `uu` | переместиться в начало файла |
| `U` | переместиться в конец файла |
| `u20` | переместиться на нужную строку |
| `10j` | переместиться на 10 строк вниз |
| `5k` | переместиться на 5 строк вверх |

#### Вставка
| Shortcut | Description |
| ------ | ------ |
| `Shift + i` | вставить текст в начало строки |
| `Shift + a` | вставить текст в конец строки |
| `o` | вставить строчку под строчкой, на которой находится курсор |
| `O` | вставить строчку над строчкой, на которой находится курсор |

#### Удаление
| Shortcut | Description |
| ------ | ------ |
| `d` | клавиша для удаления, ждет движения |
| `x` | удаляет символ под курсором, не ждет движения |
| `c` | удаляет и сразу переходит в режим вставки |
| `d + g` + `(`, `'`, `"`, `[`, `{` | Удаляет символы внутри символов |

#### Поиск
| Shortcut | Description |
| ------ | ------ |
| `f + symbol` | ищет символ в строке вправо |
| `F + symbol` | ищет символ в строке влево |
| `[` | поиск по тексту |

# Visual Mode
| Shortcut | Description |
| ------ | ------ |
| `v` | войти в режим |

# Visual Line Mode
| Shortcut | Description |
| ------ | ------ |
| `V` | войти в режим |
| `y` | скопирвать текст |
| `p` | вставить текст |

