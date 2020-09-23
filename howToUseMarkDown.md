# **Markdown 語法介紹**

# **<標題>**
## **markdown 語法：**
```
# 這是 h1
## 然後這是 h2 
### 接著這是 h3，以此類推給予六個#可以得到 h6 如下
###### 我是 h6
```
## **顯示：**
___

# 這是 h1
## 然後這是 h2 
### 接著這是 h3，以此類推給予六個#可以得到 h6 如下
###### 我是 h6
___
</br>

# **<文字強調>**
## **markdown 語法：**
```
*這是斜體字*  
_也是斜體字_

**這是粗體字**  
__也是粗體字__

_斜體字和粗體字也可以**搭配使用**_

~~刪除線就這樣使用~~
```
## **顯示：**
___
*這是斜體字*  
_也是斜體字_

**這是粗體字**  
__也是粗體字__

_斜體字和粗體字也可以**搭配使用**_

~~刪除線就這樣使用~~
___
</br>

# **\<Lists>**
## **markdown 語法：**
```
### 無序1

* Item 1
* Item 2
  * Item 2a
  * Item 2b

### 無序2：用+號
+ Item 1

### 無序3：用-號
- Item 1

### 有序1

1. Item 1
1. Item 2
   1. Item 2a
   1. Item 2b

### 有序2：任意數字皆可
1. Item 1
2. Item 2
1. Item 3
    1. Item 3a
    5. Item 3b
```
## **顯示：**
___
### 無序1

* Item 1
* Item 2
  * Item 2a
  * Item 2b

### 無序2：用+號
+ Item 1

### 無序3：用-號
- Item 1

### 有序1

1. Item 1
1. Item 2
   1. Item 2a
   1. Item 2b

### 有序2：任意數字皆可
1. Item 1
2. Item 2
1. Item 3
    1. Item 3a
    5. Item 3b
___
</br>

# **\<Links>**
## **markdown 語法：**
```
[點我進入google.com](https://www.google.com)  
[試試游標停在我上面( hover on me ! )](https://www.google.com "點我進入google.com")  
[你也可以用 reference-style link][谷哥網址]  
[也能這樣使用]

[谷哥網址]: https://www.google.com
[也能這樣使用]: https://www.google.com
```
## **顯示：**
___
[點我進入google.com](https://www.google.com)  
[試試游標停在我上面( hover on me ! )](https://www.google.com "點我進入google.com")  
[你也可以用 reference-style link][谷哥網址]  
[也能這樣使用]

[谷哥網址]: https://www.google.com
[也能這樣使用]: https://www.google.com
___
</br>

# **<圖片>**
## **markdown 語法：**
```
![當圖片出問題而無法顯示時會出現這串字](https://ipetgroup.com/photo/92085_0_620.jpeg "猜猜這是甚麼貓？")

![當圖片出問題而無法顯示時會出現這串字][打錯字網址]

[打錯字網址]:https://ipetgroup.com/打錯字/92085_0_620.jpeg "猜猜這是甚麼貓？"
```
## **顯示：**
___
![當圖片出問題而無法顯示時會出現這串字](https://ipetgroup.com/photo/92085_0_620.jpeg "猜猜這是甚麼貓？")

![當圖片出問題而無法顯示時會出現這串字][打錯字網址]

[打錯字網址]:https://ipetgroup.com/打錯字/92085_0_620.jpeg "猜猜這是甚麼貓？"
___
</br>

# **\<Blockquotes>**
## **markdown 語法：**
```
>> Mobile01User wrote:  
>請問上圖到底是甚麼貓啊？我查了很...(怒刪)
>
>答案是：一種貓！哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈
```
## **顯示：**
___
>> Mobile01User wrote:  
>請問上圖到底是甚麼貓啊？我查了很...(怒刪)
>
>答案是：一種貓！哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈
___
</br>

# **\<Code>**
## **markdown 語法：**
````md
以下是`code`

```javascript
const str = "JavaScript";
alert(str);
```

```python
str = "Python"
print(s)
```

```json
{
  "firstName": "Tom",
  "lastName": "Liu",
  "age": 28
}
```

```
HTML tag在這裡不會被轉換：
<b>bold</b>
```
````
## **顯示：**
___
以下是`code`

```javascript
const str = "JavaScript";
alert(str);
```

```python
str = "Python"
print(s)
```

```json
{
  "firstName": "Tom",
  "lastName": "Liu",
  "age": 28
}
```

```
HTML tag在這裡不會被轉換：
<b>bold</b>
```
___
</br>

# **<表格>**
## **markdown 語法：**
```
| 姓    | 名    | 簽到  |
| ----- |:-----:| -----:|
| 許    | 阿進  |   O    |
| 置左  | 置中  |   置右  |
| 楊    | 瓜瓜  |       |
```
## **顯示：**
___
| 姓    | 名    | 簽到  |
| ----- |:-----:| -----:|
| 許    | 阿進  |   O    |
| 置左  | 置中  |   置右  |
| 楊    | 瓜瓜  |       |
___
</br>

# **\<inline HTML>**
## **markdown 語法：**
```
<p>
    <div>試打一個 <b>粗體字 Bold</b></div>
</p>

```
## **顯示：**
___
<p>
    <div>試打一個 <b>粗體字 Bold</b></div>
</p>

___
</br>

# **<水平線>**
## **markdown 語法：**
```
第一種：

___

第二種：

***

第三種：

---
```
## **顯示：**
___

第一種：

___

第二種：

***

第三種：

---
___
</br>

# **<附註>**
## **markdown 語法：**
```
這是附註[^1]，這也是附註[^附註2]
[^1]:第一個附註。
[^附註2]:# 這是附註2
```
## **顯示：**
___
這是附註[^1]，這也是附註[^附註2]
[^1]:第一個附註。
[^附註2]:# 這是附註2
___
</br>



