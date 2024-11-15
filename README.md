# python-practice
--------------------------------------------------------------------------
python basicc practice source freecodecamp\
Syntax
--------------------------------------------------------------------------
variable = value\
string 用單引號或雙引號框起來\
print() output your code\
index 從0開始算 用中括號框起來(bracket notation) -1代表最後一個字元 -2是倒數第二 以此類推\
len() 計算字元個數\
type() 變數的data type\
變數名稱限制：
1. 不能用for while True等特別字元
2. 不能從數字開始，只能包含字母、數字跟底線
3. 大小寫視為不同字 ex: my_var跟my_Var兩個為不同變數
4. 變數宣告習慣 空格由底線代替 單字用小寫

.find() 找字母的位置 如果找不到會返回-1的值\
.lower() 轉換成小寫\
迴圈loop :\
for i in text: \
i : 變數 text : 按照順序從text拿出 用有意義的變數名稱來命名i\
將要執行的code放在:後面 且需要縮排(indented) 通常是4個空格 冒號(colon)指的是有一個block的code 所以需要縮排\
Strings are immutable 字串是不可改變的 被宣告後就不能 但變數是可以重新被宣告的\
a = a + b 等價於 a += b\
Comparison operators 回傳布林值True or False:
1. Equal : ==
2. Not equal : !=
3. Greater than : >
4. Less than : <
5. Greater than or equal to : >=
6. Less than or equal to : <=

條件語句:\
if x != 0: 換行縮排加code\
modulo operator % ex: 5 % 2 = 1 取餘數\
定義函數\
def function_name():\

In Python the scope of a variable determines where that variable can be accessed:\
變數定義在function外面稱為global scope可以被任意存取\
定義在function裡面稱為local scope不能被外面存取\
call(invoke)function 使用語法 function_name()
functions can be declared with parameters to introduce versatility and customization\
can be declared with different number of parameters\
ex: def function_name(param_1, param_2):\
程式可讀性很重要\
return value 會回傳value的值\
function參數可以先預有預設值 當那個參數沒有被指定時即為預設值\
,isalpha() 如果全部字元為string or letters會回傳True\
ex: 'okay'.isalpha() --> True\
not operator : True --> False 也可相反\
pass :對程式碼沒有影響  但可以避免程式碼在不完整的時候發生錯誤\
可以用+來串接兩個字串 ex: 'hello' + 'okay' --> 'hello okay'\
In Python, there's a way to easily format strings. f-strings enable you to interpolate values in your strings\
For example, you can get the same result of 'Encrypted text: ' + text with f'Encrypted text: {text}'
