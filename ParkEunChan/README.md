# SUMMARY

<br>

## VIM

<br>

### Cursor Movements:
| funtion | command |
| - | - |
| move left | `h` |
| move down | `j` |
| move up | `k`|`
| move right | `l` |
| move to the top of the screen | `H` |
| move to the middle of the screen | `M` |
| move to the bottom of the screen | `L` |
| move to very top of the code | `gg` |
| go to line 50 | `50gg` |
| move to the beginning of the current line | `0` |
| move to the end of the curremt line | `$` |

<br>

### Insert Mode:
| funtion | command |
| - | - |
| insert before cursor | `i` |
| insert at the beginning of the current line | `I`|
| insert after the cursor | `a` |
| insert at the end of the current line | `A` |
| append a new line below the current line and insert | `o` |
| append a new line above the current line and insert  | `O` |
| exit insert mode |`Esc` |
| delete word before the cursor during insert mode | `Ctrl + w` |

<br>

### Editing Mmode:
| function | command |
| - | - |
| replace single char | `r -> a character` |
| replace single char util Esc pressed | `R -> characters` |
| undo | `u` |
| restore lastly changed line | `U` |
| redo | `Ctrl + r` |
| repeat last command | `.` |
| delete a character | `x` |
| copy a line | `yy` |
| copy two lines | `2yy` | 
| copy from cursor to the end of the word | `yw` | 
| copy the word | `yiw` |
| copy until the end of the line | `y$` |
| paste | `p` |
| paste before cursor | `P` |
| cut a line | `dd` |
| cut two lines | `2dd` |
| cut from cursor until the end of the word | `dw` |
| cut the word | `diw` |
| cut until the end of the line | `D` or `d$` | 

<br>

### Visual Mode: 
| funtion | command |
| - | - | 
| start visual mode | `v` |
| start visual block mode | `Ctrl + v` |

<br>

### Exiting:
| funtion | command |
| - | - |
| save (or write) | `:w` |
| save and quit | `wq` or `:x` or `ZZ` |
| quit | `:q` |]
| quit regardless of the changes | `:q!` or `ZQ` |
| save and quit on all tabs | `:wqa` |

<br>

### Searching :
| funtion | command |
| - | - |
| search "keyword" | `/keyword` |
| search "keyword" backwards | `?keyword` |
| search for next keyword | `n` |
| search for next keyword backwards | `N` |
| replace "old" with "new" throughout the file | `:%s/old/new/g` |
| replace "old" with "new" throughout the file with confirmations | `:%s/old/new/gc` |

<br>


### Plus Alpha: 
| funtion | command |
| - | - |
| show line number | `:set number` |
| show no line number | `:set nonumber` |


<br>

---

<br>

## MARKDOWN
| funtion | syntax |
| - | - |
| heading | # h1 <br> # h2 <br> # h3|
| bold | \*\*text** |
| italic | \*text* |
| block quote | >text|
| block quote within block quote | >>text |
| ordered list | 1. first <br> 2. second <br> 3. third |
| unordered list | - first <br> - second <br> -third |
| code | \` code ` |
| code block | \``` <br> codes <br>\``` |
| horizontal lien | --- |
| link | \[title](https://www.hello.com) |
| image | \!\[image](image.png) |
| new line | \<br> or \ or space key twice|
| table | \| functions \| descriptions \| <br> \| - \| - \| <br> \| function1 \| description1 \| <br> \| function2 \| description2 \|
| strikethrough | \~\~ text ~~ |
| task list | - [x] task1 <br>- [ ] task2 |
