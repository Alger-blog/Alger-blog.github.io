# By类定位

~~~python
#driver.find_element(By.ID,"userA")
~~~

# JS定位并操作元素

## 一.怎么定位JS元素

### id定位

~~~python
#document.getElementById(id 属性).value=你要输入的值 //输入某元素
#document.getElementById(id 属性).click() //点击某元素
~~~

### Class定位

~~~python
#document.getElementsByClassName(class 属性的值)[下标].value=你要输入的值 //输入某元素
#document.getElementsByClassName(class 属性的值)[下标].click() //点击某元素
~~~

### Name定位

~~~python
#document.getElementsByName(name 属性的值)[下标].value=你要输入的值 //输入某元素
#document.getElementsByName(name 属性的值)[下标].click() //点击某元素	
~~~

### tagName定位

~~~python
#document.getElementsByTagName(标签名)[下标].value=你要输入的值 //输入某元素
#document.getElementsByTagName(标签名)[下标].click() //点击某元素
~~~

### CSS选择器

~~~python
#document.querySelectorAll(CSS 选择器)[下标].value=你要输入的值 //输入某元素
#document.querySelectorAll(CSS 选择器)[下标].click() //点击某元素
~~~



## 二.定位JS元素后怎么操作元素

### 1	输入文本内容

~~~python
JSEle.vlaue='你要输入的文本内容'
~~~

### 2	点击元素

~~~python
JSEle.click()
~~~

### 3	修改某属性的值/新增一个新属性

~~~python
JSEle.setAttribute("属性名","属性值")
~~~

### 4	删除某属性

~~~python
JSEle.removeAttribute("属性名")
~~~

### 5	修改CSS样式表

~~~python
JSEle.style.样式名称="样式值"
~~~

## 三.怎么执行JS代码

~~~python
js="xxxx"
drive.execute_scroipt()
~~~

