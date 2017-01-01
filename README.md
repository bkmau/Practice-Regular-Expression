# Practice-Regular-Expression
==============================
Reference:  
------------------------------
(原文) oreilly, Mastering Regular Expressions, 3rd Edition | [http://shop.oreilly.com/product/9780596528126.do](http://shop.oreilly.com/product/9780596528126.do)  
(中文) 精通正規表達式, 3/e (Mastering Regular Expressions, 3/e) | [https://www.tenlong.com.tw/items/9862764406?item_id=451238](https://www.tenlong.com.tw/items/9862764406?item_id=451238)

Content
-----------------------------
* 使用工具: Sublime Text 3
* 第一個regular expression  
  % egrep '^Hello word$' test.txt # 使用egrep在test.txt中尋找以H為開頭, 接著是"e", "l", "l", "o", " ", "w", "o", "r", 然後"d"為結尾的字串  
* whitespace and space  
  whitespace -> 指空白字元, 例如," ", Tab, 換行符號  
  space      -> 特指空格字元, " "  
* metacharacter and character  
  以第一個來說regular expression, Hello Word就是character, ^和$便是metecharacter  
  metecharacter有點像是其他程式語言的[保留字(reserved word)](https://en.wikipedia.org/wiki/Reserved_word) 
