# ๐1.1.8 MVC ํจํด
## MVCํจํด

: ๋ชจ๋ธ(Model), ๋ทฐ(View), ์ปจํธ๋กค๋ฌ(Controller)๋ก ์ด๋ค์ง ๋์์ธ ํจํด์ด๋ค

![img_3.png](img_3.png)



### ๋์์์
1. ๋ชจ๋  ์๋ ฅ(Input)๋ค์ Controller๋ก ์ ๋ฌ
2. Controller๋ ์๋ ฅ์ ํด๋นํ๋ Model์ ์๋ฐ์ดํธ
3. ์๋ฐ์ดํธ ๊ฒฐ๊ณผ์ ๋ฐ๋ผ View๋ฅผ ์ ํ(ํ๋์ Controller๋ View๋ฅผ ์ ํํ  ์ ์๊ธฐ ๋๋ฌธ์ ์ฌ๋ฌ ๊ฐ์ View๋ฅผ ๊ด๋ฆฌ)
4. Controller๋ View๋ฅผ ์ ํํ  ๋ฟ, ์ง์  ์๋ฐ์ดํธ๋ฅผ ํ์ง ์๋๋ค


### ์ฅ์ 

- ๊ฐ๋ฐ ํ๋ก์ธ์ค์์ ๊ฐ๊ฐ์ ๊ตฌ์ฑ์์์๋ง ์ง์ค ๊ฐ๋ฐ ๊ฐ๋ฅ

- ์ฌ์ฌ์ฉ์ฑ๊ณผ ํ์ฅ์ฑ์ด ์ฉ์ด



### ๋จ์ 

- ์ ํ๋ฆฌ์ผ์ด์์ด ๋ณต์กํด์ง์๋ก ๋ชจ๋ธ๊ณผ ๋ทฐ์ ๊ด๊ณ๊ฐ ๋ณต์กํด์ง


<br>


### ๋ชจ๋ธ(Model)
: ์ ํ๋ฆฌ์ผ์ด์์ ๋ฐ์ดํฐ์ธ ๋ฐ์ดํฐ๋ฒ ์ด์ค, ์์, ๋ณ์ ๋ฑ์ ๋ปํ๋ค

๋ทฐ์์ ๋ฐ์ดํฐ๋ฅผ ์์ฑํ๊ฑฐ๋ ์์ ํ๋ฉด ์ปจํธ๋กค๋ฌ๋ฅผ ํตํด ๋ชจ๋ธ์ ์์ฑํ๊ฑฐ๋ ๊ฐฑ์ 



### ๋ทฐ(View)
: inputbox, checkbox, textarea ๋ฑ ์ฌ์ฉ์ ์ธํฐํ์ด์ค ์์๋ฅผ ๋ํ๋ธ๋ค.

 ์ฆ, ๋ชจ๋ธ์ ๊ธฐ๋ฐ์ผ๋ก ์ฌ์ฉ์๊ฐ ๋ณผ ์ ์๋ ํ๋ฉด

     - ๋ชจ๋ธ์ด ๊ฐ์ง ์ ๋ณด๋ฅผ ๋ฐ๋ก ์ ์ฅํ์ง ์์์ผ ํ๋ฉฐ ํ๋ฉด์ ํ์ํ๋ ์ ๋ณด๋ง ์์ด์ผํจ

     - ๋ณ๊ฒฝ์ด ์ผ์ด๋๋ฉด ์ปจํธ๋กค๋ฌ์ ์ด๋ฅผ ์ ๋ฌํด์ผํจ



### ์ปจํธ๋กค๋ฌ(Controller)
: ํ๋ ์ด์์ ๋ชจ๋ธ๊ณผ ํ๋ ์ด์์ ๋ทฐ๋ฅผ ์๋ ๋ค๋ฆฌ ์ญํ ์ ํ๋ฉฐ ์ด๋ฒคํธ ๋ฑ ๋ฉ์ธ ๋ก์ง์ ๋ด๋น

๋ํ, ๋ชจ๋ธ๊ณผ ๋ทฐ์ ๋ณ๊ฒฝ ํต์ง๋ฅผ ๋ฐ์ผ๋ฉฐ ์ด๋ฅผ ํด์ํ์ฌ ๊ฐ๊ฐ์ ๊ตฌ์ฑ ์์์ ํด๋น ๋ด์ฉ์ ๋ํด ์๋ฆฐ๋ค





### MVC ํจํด์ ์ ๋ฆฌ์กํธ
๋ํ ๋ผ์ด๋ธ๋ฌ๋ฆฌ๋ ์ ์  ์ธํฐํ์ด์ค๋ฅผ ๊ตฌ์ถํ๊ธฐ ์ํ ๋ฆฌ์กํธ๊ฐ ์๋ค.

๋ฆฌ์กํธ๋ ์ ์  ์ธํฐํ์ด์ค ๊ตฌ์ถ์ ์ํ ๋ผ์ด๋ธ๋ฌ๋ฆฌ์ด๋ค.

'๊ฐ์ DOM'์ ํตํด ์ค์  DOM์ ์กฐ์ํ๋ ๊ฒ์ ์ถ์ํํด์ ์ฑ๋ฅ์ ๋์๋ค.



๋ํ์ ์ธ ํน์ฑ์ผ๋ก๋ ๋ถ๋ณ์ฑ(immutable)์ด ์๋ค

๋จ๋ฐฉํฅ ๋ฐ์ธ๋ฉ์ด ์ ์ฉ๋์ด ์๊ณ , ์์ ๋๊ฐ ๋๊ณ , ๋จ๋ฐฉํฅ ๋ฐ์ธ๋ฉ์ด ์ ์ฉ๋์ด ์๊ณ , ์์ ๋๊ฐ ๋๊ณ , ๋ฉํ(ํ์ด์ค๋ถ)์ด ์ด์ ์ค์ด๋ฉฐ, ๋ทํ๋ฆญ์ค,ํธ์ํฐ, ์ฐ๋ฒ, MS ๋ฑ์์ ์ฌ์ฉ



## ๐1.1.9 MVP ํจํด

MVC์์ C์ ํด๋นํ๋ ์ปจํธ๋กค๋ฌ๊ฐ ํ๋ ์  ํฐ๋ก ๊ต์ฒด๋ ํจํด

MVC ํจํด์ผ๋ก๋ถํฐ ํ์๋์๋ค

๋ทฐ์ ํ๋ ์  ํฐ๋ ์ผ๋์ผ ๊ด๊ณ์ด๊ธฐ ๋๋ฌธ์ MVCํจํด๋ณด๋ค ๋ ๊ฐํ ๊ฒฐํฉ์ ์ง๋ ๋์์ธ ํจํด
![img_4.png](img_4.png)



Presenter
: View์์ ์์ฒญํ ์ ๋ณด๋ก Model์ ๊ฐ๊ณตํ์ฌ View์ ์ ๋ฌํด ์ฃผ๋ ๋ถ๋ถ



๋์์์
1. ๋ชจ๋  ์๋ ฅ(Input)๋ค์ View๋ก ์ ๋ฌ
2. Presenter๋ ์๋ ฅ์ ํด๋นํ๋ Model์ ์๋ฐ์ดํธ
3. Model ์๋ฐ์ดํธ ๊ฒฐ๊ณผ๋ฅผ ๊ธฐ๋ฐ์ผ๋ก View๋ฅผ ์๋ฐ์ดํธ
4. Presenter๋ ํด๋น View๋ฅผ ์ฐธ์กฐ(View์ Presenter๋ 1:1 ๊ด๊ณ์๋๋ค.)
5. Presenter๋ View์ Model ์ธ์คํด์ค๋ฅผ ๊ฐ์ง๊ณ , Model๊ณผ View ์ฌ์ด์ ๋งค๊ฐ์ฒด ์ญํ ์ ํ๋ค



## ๐1.1.10 MVVM ํจํด
MVC์ C์ ํด๋นํ๋ ์ปจํธ๋กค๋ฌ๊ฐ ๋ทฐ๋ชจ๋ธ๋ก ๋ฐ๋ ํจํด

๋ทฐ๋ชจ๋ธ์ ๋ทฐ๋ฅผ ๋ ์ถ์ํํ ๊ณ์ธต, MVCํจํด๊ณผ๋ ๋ค๋ฅด๊ฒ ์ปค๋งจ๋์ ๋ฐ์ดํฐ ๋ฐ์ธ๋ฉ์ ๊ฐ์ง๋ ๊ฒ์ด ํน์ง

๋ทฐ์ ๋ทฐ๋ชจ๋ธ ์ฌ์ด์ ์๋ฐฉํฅ ๋ฐ์ดํฐ ๋ฐ์ธ๋ฉ์ ์ง์, UI๋ฅผ ๋ณ๋์ ์ฝ๋ ์์ ์์ด ์ฌ์ฌ์ฉํ  ์ ์๊ณ  ๋จ์ ํ์คํํ๊ธฐ ์ฝ๋ค
![img_5.png](img_5.png)

### ๋์์์
1. ๋ชจ๋  ์๋ ฅ(Input)๋ค์ View๋ก ์ ๋ฌ
2. ViewModel์ ์๋ ฅ์ ํด๋นํ๋ Presentation Logic์ ์ฒ๋ฆฌํ์ฌ View์ ๋ฐ์ดํฐ๋ฅผ ์ ๋ฌ
3. ViewModel์ View๋ฅผ ์ฐธ์กฐํ์ง ์๊ธฐ ๋๋ฌธ์ ๋๋ฆฝ์ ์๋๋ค. ๋ฐ๋ผ์ View๋ ์์ ์ด ์ด์ฉํ  ViewModel์ ์ ํํด ๋ฐ์ธ๋ฉํ์ฌ ์๋ฐ์ดํธ ๋ฐ๊ฒ๋จ  (Command ํจํด์ด๋ Data Binding์ ์ด์ฉํ์ฌ V-VM ๊ฐ ์์กด์ฑ์ ์์จ ์ ์์ต๋๋ค. ๊ทธ๋ฆฌ๊ณ  View Model๊ณผ View๋ 1:n ๊ด๊ณ์ด๋ค.)
4. Model์ด ๋ณ๊ฒฝ๋๋ฉด ํด๋นํ๋ ViewModel์ ์ด์ฉํ๋ View๊ฐ ์๋์ผ๋ก ์๋ฐ์ดํธ๋๋ค.
5. ViewModel์ View๋ฅผ ๋ํ๋ด ์ฃผ๊ธฐ ์ํ Model์ด์, View์ Presentation Logic์ ์ฒ๋ฆฌํ๋ค


### MVVM ํจํด์ ์ : ๋ทฐ
๋ํ ํ๋ ์์ํฌ๋ก๋ ๋ทฐ(Vue.js)๊ฐ ์๋ค. Vue.js๋ ๋ฐ์ํ(reactivity)์ด ํน์ง์ธ ํ๋ก ํธ์๋ ํ๋ ์์ํฌ์ด๋ค.

ex) watch,computed ๋ฑ์ผ๋ก ์ฝ๊ฒ ๋ฐ์ํ์ ์ธ ๊ฐ๋ค์ ๊ตฌ์ถ๊ฐ๋ฅ



### ํน์ง
- ํจ์ ์ฌ์ฉ์์ด ๊ฐ ๋์๋ง์ผ๋ก ๋ณ์๊ฐ ๋ณ๊ฒฝ

- ์๋ฐฉํฅ ๋ฐ์ธ๋ฉ,html์ ํ ๋๋ก ์ปดํฌ๋ํธ๋ฅผ ๊ตฌ์ถํ  ์ ์๋ค๋ ๊ฒ์ด ํน์ง

- ์ฌ์ฌ์ฉ ์ปดํฌ๋ํธ ๊ธฐ๋ฐ์ผ๋ก UI๋ฅผ ๊ตฌ์ถ ๊ฐ๋ฅ





#### - ์ปค๋งจ๋

: ์ฌ๋ฌ ๊ฐ์ง ์์์ ๋ํ ์ฒ๋ฆฌ๋ฅผ ํ๋์ ์ก์์ผ๋ก ์ฒ๋ฆฌํ  ์ ์๊ฒ ํ๋ ๊ธฐ๋ฒ



#### - ๋ฐ์ดํฐ ๋ฐ์ธ๋ฉ

: ํ๋ฉด์ ๋ณด์ด๋ ๋ฐ์ดํฐ์ ์น ๋ธ๋ผ์ฐ์ ์ ๋ฉ๋ชจ๋ฆฌ ๋ฐ์ดํฐ๋ฅผ ์ผ์น์ํค๋ ๊ธฐ๋ฒ์ผ๋ก, ๋ทฐ๋ชจ๋ธ์ ๋ณ๊ฒฝํ๋ฉด ๋ทฐ๊ฐ ๋ณ๊ฒฝ ๋๋ค



## โํ๋ก๊ทธ๋๋ฐ ํจ๋ฌ๋ค์
:  ํ๋ก๊ทธ๋๋จธ์๊ฒ ํ๋ก๊ทธ๋๋ฐ์ ๊ด์ ์ ๊ฐ๊ฒ ํด์ฃผ๋ ์ญํ ์ ํ๋ ๊ฐ๋ฐ ๋ฐฉ๋ฒ๋ก 



####ํ๋ก๊ทธ๋๋ฐ ํจ๋ฌ๋ค์์ ๋ถ๋ฅ

![img_6.png](img_6.png)



### ๊ฐ์ฒด์งํฅ ํ๋ก๊ทธ๋๋ฐ
: ํ๋ก๊ทธ๋๋จธ๋ค์ด ํ๋ก๊ทธ๋จ์ ์ํธ ์์ฉํ๋ ๊ฐ์ฒด๋ค์ ์งํฉ์ผ๋ก ๋ณผ ์ ์๊ฒ ํ๋ค

### ํจ์ํ ํ๋ก๊ทธ๋๋ฐ
: ์ํ ๊ฐ์ ์ง๋์ง ์๋ ํจ์ ๊ฐ๋ค์ ์ฐ์์ผ๋ก ์๊ฐํ  ์ ์๊ฒ ํด์ค๋ค



์ด๋ค ์ธ์ด๋ ํน์ ํ ํจ๋ฌ๋ค์์ ์ง์,  jdk 1.8 ์ด์ ์ ์๋ฐ๋ ๊ฐ์ฒด์งํฅ ํ๋ก๊ทธ๋๋ฐ์ ์ง์ํ๋,
ํ์ค์ผ์ ํจ์ํ ํ๋ก๊ทธ๋๋ฐ์ ์ง์

<br>

์ฌ๋ฌ ํจ๋ฌ๋ค์์ ์ง์ํ๋ ์ธ์ด : C++, ํ์ด์ , ์๋ฐ์คํฌ๋ฆฝํธ

JAVA์ ๊ฒฝ์ฐ jdk 1.8๋ถํฐ ํจ์ํ ํ๋ก๊ทธ๋๋ฐ ํจ๋ฌ๋ค์์ ์ง์ํ๊ธฐ ์ํด ๋๋ค์, ์์ฑ์ ๋ ํผ๋ฐ์ค, ๋ฉ์๋ ๋ ํผ๋ฐ์ค๋ฅผ ๋์

์ ์ธํ ํ๋ก๊ทธ๋๋ฐ์ ์ํด ์คํธ๋ฆผ(stream) ๊ฐ์ ํ์ค API ๋ฑ๋ ์ถ๊ฐ



<br>

## ๐1.2.1 ์ ์ธํ๊ณผ ํจ์ํ ํ๋ก๊ทธ๋๋ฐ
### โ ์ ์ธํ ํ๋ก๊ทธ๋๋ฐ(declarative programming)
: ๋ฌด์์ ํ์ด๋ด๋๊ฐ์ ์ง์คํ๋ ํจ๋ฌ๋ค์

ํ๋ก๊ทธ๋จ์ ํจ์๋ก ์ด๋ฃจ์ด์ง ๊ฒ์ด๋ค.๋ผ๋ ๋ช์ ๊ฐ ๋ด๊ธด ํจ๋ฌ๋ค์

### โ ํจ์ํ ํ๋ก๊ทธ๋๋ฐ(functional programming)
: ์ ์ธํ ํจ๋ฌ๋ค์์ ์ผ์ข



<br>

#### ์์ฐ์๋ก ์ด๋ค์ง ๋ฐฐ์ด์์ ์ต๋๊ฐ์ ์ฐพ๋ ๋ก์ง

<details>
<summary>์ฝ๋ ํ ๊ธ</summary>
<div markdown="1">

```javascript

const ret = [1, 2, 3, 4, 5, 11, 12]
.reduce((max, num) => num > max ? num : max, 0)
console.log(ret) //12

// num>max ์กฐ๊ฑด๋ฌธ์ ํตํด true๋ฉด num์ false๋ฉด max๋ฅผ ๋ฐํํด์ฃผ๊ณ  0์ ์ด๊น๊ฐ์ผ๋ก ๋๋ค

```
</div>
</details>

reduce()๋ '๋ฐฐ์ด'๋ง ๋ฐ์์ ๋์ ํ ๊ฒฐ๊ด๊ฐ์ ๋ฐํํ๋ ์์ ํจ์



### ํจ์ํ ํ๋ก๊ทธ๋๋ฐ

 -   '์์ ํจ์'๋ค์ ๋ธ๋ก์ฒ๋ผ ์์ ๋ก์ง์ ๊ตฌํํ๊ณ  '๊ณ ์ฐจ ํจ์'๋ฅผ ํตํด ์ฌ์ฌ์ฉ์ฑ์ ๋์ธ ํ๋ก๊ทธ๋๋ฐ ํจ๋ฌ๋ค์

### ์๋ฐ์คํฌ๋ฆฝํธ

 -   ๋จ์ํ๊ณ  ์ ์ฐํ ์ธ์ด์ด๋ฉฐ, ํจ์๊ฐ ์ผ๊ธ ๊ฐ์ฒด์ด๊ธฐ ๋๋ฌธ์ ๊ฐ์ฒด์งํฅ ํ๋ก๊ทธ๋๋ฐ๋ณด๋จ ํจ์ํ ํ๋ก๊ทธ๋๋ฐ ๋ฐฉ์ ์ ํธ



### ์์ ํจ์
์ถ๋ ฅ์ด ์๋ ฅ์๋ง ์์กดํ๋ ๊ฒ


<details>
<summary>์ฝ๋ ํ ๊ธ</summary>
<div markdown="1">

```javascript

const pure = (a, b) => {
return a+b
}

```
</div>
</details>

pure ํจ์๋ ๋งค๊ฐ๋ณ์ a,b์๋ง ์ํฅ์ ๋ฐ๋๋ค.

๋ง์ฝ a,b ๋ง๊ณ  ๋ค๋ฅธ ์ ์ญ ๋ณ์ c ๋ฑ์ด ์ด ์ถ๋ ฅ์ ์ํฅ์ ์ฃผ๋ฉด ์์ ํจ์๊ฐ ์๋๋๋ค.

<br>

### ๊ณ ์ฐจํจ์
ํจ์๊ฐ ํจ์๋ฅผ ๊ฐ์ฒ๋ผ ๋งค๊ฐ๋ณ์๋ก ๋ฐ์ ๋ก์ง์ ์์ฑํ  ์ ์๋ ๊ฒ



### โ ์ผ๊ธ ๊ฐ์ฒด
: ๋ค๋ฅธ ๊ฐ์ฒด๋ค์ ์ผ๋ฐ์ ์ผ๋ก ์ ์ฉ ๊ฐ๋ฅํ ์ฐ์ฐ์ ๋ชจ๋ ์ง์ํ๋ ๊ฐ์ฒด

์ด๋ ๊ณ ์ฐจ ํจ์๋ฅผ ์ฐ๊ธฐ ์ํด์๋ ํด๋น ์ธ์ด๊ฐ ์ผ๊ธ ๊ฐ์ฒด๋ผ๋ ํน์ง์ ๊ฐ์ ธ์ผ ํ๋ฉฐ ๊ทธ ํน์ง์ ๋ค์๊ณผ ๊ฐ๋ค

- ๋ณ์๋ ๋ฉ์๋์ ํจ์๋ฅผ ํ ๋น๊ฐ๋ฅ

- ํจ์ ์์ ํจ์๋ฅผ ๋งค๊ฐ๋ณ์๋ก ๋ด์ ์ ์๋ค

- ํจ์๊ฐ ํจ์๋ฅผ ๋ฐํ ๊ฐ๋ฅ

์ด์ธ์๋ ์ปค๋ง, ๋ถ๋ณ์ฑ ๋ฑ ๋ง์ ํน์ง์ด ์๋ค


<br>


## ๐1.2.2 ๊ฐ์ฒด์งํฅ ํ๋ก๊ทธ๋๋ฐ
### ๊ฐ์ฒด์งํฅ ํ๋ก๊ทธ๋๋ฐ(OOP, Object-Oriented Programming)
: ๊ฐ์ฒด๋ค์ ์งํฉ์ผ๋ก ํ๋ก๊ทธ๋จ์ ์ํธ ์์ฉ์ ํํํ๋ฉฐ ๋ฐ์ดํฐ๋ฅผ ๊ฐ์ฒด๋ก ์ทจ๊ธํ์ฌ ๊ฐ์ฒด ๋ด๋ถ์ ์ ์ธ๋ ๋ฉ์๋๋ฅผ ํ์ฉ

์ค๊ณ์ ๋ง์ ์๊ฐ์ด ์์, ์ฒ๋ฆฌ ์๋๊ฐ ๋ค๋ฅธ ํ๋ก๊ทธ๋๋ฐ ํจ๋ฌ๋ค์์ ๋นํด ์๋์ ์ผ๋ก ๋๋ฆฌ๋ค

<details>
<summary>์ฝ๋ ํ ๊ธ</summary>
<div markdown="1">

```javascript

const ret = [1,2,3,4,5,11,12]
class List{
constructor(list){
this.list = list
this.mx = list.reduce((max, num) => num > max ? num : max,0)
}
getMax(){
return this.mx
}
}
const a = new List(ret)
console.log(a.getMax()) //12

```
</div>
</details>

List๋ผ๋ ํด๋์ค๋ฅผ ๋ง๋ค๊ณ  a๋ผ๋ ๊ฐ์ฒด๋ฅผ ๋ง๋ค ๋ ์ต๋๊ฐ์ ์ถ์ถํด๋ด๋ ๋ฉ์๋๋ฅผ ๋ง๋  ์์ 


<br>


## ๊ฐ์ฒด์งํฅ ํ๋ก๊ทธ๋๋ฐ์ ํน์ง
: ์ถ์ํ, ์บก์ํ, ์์์ฑ, ๋คํ์ฑ์ด๋ผ๋ ํน์ง



### - ์ถ์ํ(abstraction)

๋ณต์กํ ์์คํ์ผ๋ก๋ถํฐ ํต์ฌ ๊ฐ๋ ๋๋ ๊ธฐ๋ฅ์ ๊ฐ์ถ๋ ค๋ด๋ ๊ฒ



### - ์บก์ํ(encapsulation)

๊ฐ์ฒด์ ์์ฑ๊ณผ ๋ฉ์๋๋ฅผ ํ๋๋ก ๋ฌถ์ด ์ผ๋ถ๋ฅผ ์ธ๋ถ์ ๊ฐ์ถฐ ์๋ํ๋ ๊ฒ



### - ์์์ฑ(inheritance)

์์ ํด๋์ค์ ํน์ฑ์ ํ์ ํด๋์ค๊ฐ ์ด์ด๋ฐ์ ์ฌ์ฌ์ฉํ๊ฑฐ๋ ์ถ๊ฐ, ํ์ฅํ๋ ๊ฒ

์ฝ๋์ ์ฌ์ฌ์ฉ ์ธก๋ฉด, ๊ณ์ธต์ ์ธ ๊ด๊ณ ์์ฑ, ์ ์ง ๋ณด์์ฑ ์ธก๋ฉด์์ ์ค์



### - ๋คํ์ฑ(polymorphism)

ํ๋์ ๋ฉ์๋๋ ํด๋์ค๊ฐ ๋ค์ํ ๋ฐฉ๋ฒ์ผ๋ก ๋์ํ๋ ๊ฒ

ex)์ค๋ฒ๋ก๋ฉ, ์ค๋ฒ๋ผ์ด๋ฉ์ด ๋ํ์ ์ด๋ค

<br>

## ์ค๋ฒ๋ก๋ฉ(overloading)
๊ฐ์ ์ด๋ฆ์ ๊ฐ์ง ๋ฉ์๋๋ฅผ ์ฌ๋ฌ ๊ฐ ๋๋ ๊ฒ
๋งค๊ฐ๋ณ์์ ์ ํ, ๊ฐ์ ๋ฑ์ผ๋ก ์ฌ๋ฌ ๊ฐ๋ฅผ ๋ ์ ์๊ณ  ์ปดํ์ผ ์ค ๋ฐ์ํ๋ '์ ์ ' ๋คํ์ฑ

<details>
<summary>์ฝ๋ ํ ๊ธ</summary>
<div markdown="1">

```java

class Person{

	public void eat(String a){
              System.out.println("I eat " + a);
         }
    
    public void eat(String a, String b){
              System.out.println("I eat " + a + " and " + b);
         }
}

public class CalculateArea{

		public static void main(String[] args){
        	Person a = new Person();
            a.eat("apple");
            a.eat("tomato","phodo");
     }
}
/*
I eat apple
I eat tomato and phodo
*/

```
</div>
</details>

์ ์ฝ๋์ฒ๋ผ ๋งค๊ฐ๋ณ์์ ๊ฐ์์ ๋ฐ๋ผ ๋ค๋ฅธ ํจ์๊ฐ ํธ์ถ๋๋ ๊ฒ์ ์ ์ ์๋ค
<br>
### ์ค๋ฒ๋ผ์ด๋ฉ(overriding)
์ฃผ๋ก ๋ฉ์๋ ์ค๋ฒ๋ผ์ด๋ฉ(method overriding)์ ๋งํ๋ฉฐ ์์ ํด๋์ค๋ก๋ถํฐ ์์๋ฐ์ ๋ฉ์๋๋ฅผ ํ์ ํด๋์ค๊ฐ ์ฌ์ ์ํ๋ ๊ฒ์ ์๋ฏธ
๋ฐํ์ ์ค์ ๋ฐ์ํ๋ '๋์ ' ๋คํ์ฑ

<details>
<summary>์ฝ๋ ํ ๊ธ</summary>
<div markdown="1">

```java

class Animal{
public void brak(){
System.out.prinltn("mumu! mumu!");
}
}

class Dog extends Animal{
@Override
public void bark(){
System.out.println("wal!!! wal!!!");
}
}

public class Main{
public static void main(String[] args){
Dog d = new Dog();
d.bark();
}
}

/*
wal!!! wal!!!
*/

```
</div>
</details>
๋ถ๋ชจ ํด๋์ค์์ ์ ์ํด๋ ์์ ํด๋์ค์์ ์ฌ์ฑ์ํ๋ฉด ์์ ํด๋์ค ๊ธฐ๋ฐ์ผ๋ก ๋ฉ์๋๊ฐ ์ฌ์ ์๋๋ค.



## ๐์ค๊ณ ์์น
๊ฐ์ฒด์งํฅ ํ๋ก๊ทธ๋๋ฐ์ ์ค๊ณํ  ๋๋ SOLID ์์น์ ์ง์ผ์ค์ผํ๋ค.

S๋ ๋จ์ผ ์ฑ์ ์์น, O๋ ๊ฐ๋ฐฉ-ํ์ ์์น, L์ ๋ฆฌ์ค์ฝํ ์นํ ์์น, I๋ ์ธํฐํ์ด์ค ๋ถ๋ฆฌ ์์น, D๋ ์์กด ์ญ์  ์์น ์๋ฏธ



### ๋จ์ผ ์ฑ์ ์์น (SRP, Single Responsibility Principle)
: ๋ชจ๋  ํด๋์ค๋ ๊ฐ๊ฐ ํ๋์ ์ฑ์๋ง ๊ฐ์ ธ์ผ ํ๋ ์์น

ex) a๋ผ๋ ๋ก์ง์ด ์กด์ฌํ๋ฉด ์ด๋ค ํด๋์ค๋ a์ ๊ดํ ํด๋์ค์ฌ์ผ ํ๊ณ  ์ด๋ฅผ ์์ ํด๋ a์ ๊ด๋ จ๋ ์์ ์ด์ด์ผ ํ๋ค





### ๊ฐ๋ฐฉ - ํ์ ์์น (OCP, Open Closed Principle)
: ์ ์ง ๋ณด์ ์ฌํญ์ด ์๊ธฐ๋ฉด ์ฝ๋๋ฅผ ์ฝ๊ฒ ํ์ฅํ  ์ ์๊ฒ ํ๊ณ   ์์ ํ  ๋๋ ๋ซํ ์์ด์ผ ํ๋ ์์น

๊ธฐ์กด์ ์ฝ๋๋ ์ ๋ณ๊ฒฝํ์ง ์์ผ๋ฉด์ ํ์ฅ์ ์ฝ๊ฒ ํ  ์ ์์ด์ผ ํ๋ค





### ๋ฆฌ์ค์ฝํ ์นํ ์์น(LSP, Liskov Substitution Principle)
: ํ๋ก๊ทธ๋จ์ ๊ฐ์ฒด๋ ํ๋ก๊ทธ๋จ์ ์ ํ์ฑ์ ๊นจ๋จ๋ฆฌ์ง ์์ผ๋ฉด์ ํ์ ํ์์ ์ธ์คํด์ค๋ก ๋ฐ๊ฟ ์ ์์ด์ผ ํ๋ ๊ฒ์ ์๋ฐ

ํด๋์ค๋ ์์์ด ๋๊ธฐ ๋ง๋ จ์ด๊ณ  ๋ถ๋ชจ, ์์์ด๋ผ๋ ๊ณ์ธต ๊ด๊ณ๊ฐ ๋ง๋ค์ด์ง๋๋ฐ,  ๋ถ๋ชจ ๊ฐ์ฒด์ ์์ ๊ฐ์ฒด๋ฅผ ๋ฃ์ด๋ ์์คํ์ด ๋ฌธ์ ์์ด ๋์๊ฐ๊ฒ ๋ง๋๋ ๊ฒ

์ฆ, ๋ถ๋ชจ ๊ฐ์ฒด์ ์์ ๊ฐ์ฒด๋ฅผ ๋ฐ๊ฟ๋ ๋ฌธ์ ๊ฐ ์์ด์ผ ํ๋ค.  


  


### ์ธํฐํ์ด์ค ๋ถ๋ฆฌ ์์น(ISP, Interface Segregation Principle)
: ํ๋์ ์ผ๋ฐ์ ์ธ ์ธํฐํ์ด์ค๋ณด๋ค ๊ตฌ์ฒด์ ์ธ ์ฌ๋ฌ ๊ฐ์ ์ธํฐํ์ด์ค๋ฅผ ๋ง๋ค์ด์ผ ํ๋ ์์น

  



### ์์กด ์ญ์  ์์น(DIP, Dependency Inversion Principle)
: ์์ ๋ณด๋ค ๋ณํ๊ธฐ ์ฌ์ด ๊ฒ์ ์์กดํ๋ ๊ฒ์ ์ถ์ํ๋ ์ธํฐํ์ด์ค๋ ์์ํด๋์ค๋ฅผ ๋์ด ๋ณํ๊ธฐ ์ฌ์ด ๊ฒ์ ๋ณํ์ ์ํฅ๋ฐ์ง ์๊ฒ ํ๋ ์์น

์ฆ, ์์ ๊ณ์ธต์ ํ์ ๊ณ์ธต์ ๋ณํ์ ๋ํ ๊ตฌํ์ผ๋ก๋ถํฐ ๋๋ฆฝํด์ผ ํ๋ค







## ๐1.2.3 ์ ์ฐจํ ํ๋ก๊ทธ๋๋ฐ
๋ก์ง์ด ์ํ๋์ด์ผ ํ  ์ฐ์์ ์ธ ๊ณ์ฐ ๊ณผ์ ์ผ๋ก ์ด๋ค์ง

์ผ์ด ์งํ๋๋ ๋ฐฉ์์ผ๋ก ๊ทธ์  ์ฝ๋๋ฅผ ๊ตฌํํ๊ธฐ๋ง ํ๋ฉด ๋์ด ์ฝ๋์ ๊ฐ๋์ฑ์ด ์ข์ผ๋ฉฐ ์คํ ์๋๊ฐ ๋น ๋ฅด๋ค=> ๊ณ์ฐ์ด ๋ง์ ์์ ๋ฑ์ ์ฐ์



ex) ํฌํธ๋(fortran)์ ์ด์ฉํ ๋๊ธฐ ๊ณผํ ๊ด๋ จ ์ฐ์ฐ ์์,๋จธ์  ๋ฌ๋์ ๋ฐฐ์น ์์

 ๋จ์  : ๋ชจ๋ํ๊ฐ ์ด๋ ต๊ณ  ์ ์ง ๋ณด์์ฑ์ด ๋จ์ด์ง๋ค



์์ฐ์๋ก ์ด๋ค์ง ๋ฐฐ์ด์์ ์ต๋๊ฐ์ ์ฐพ์ผ๋ผ ํ๋ค๋ฉด ๋ค์๊ณผ ๊ฐ์ด ๋ก์ง์ ๊ตฌ์


<details>
<summary>์ฝ๋ ํ ๊ธ</summary>
<div markdown="1">

```javascript

const ret = [1, 2, 3, 4, 5, 11, 12]
let a = 0
for (let i =0;i < ret.length; i++){
a = Math.max(ret[i], a)
}
console.log(a) //12

```
</div>
</details>

ret.length ๊ธธ์ด๋งํผ ๋ฐ๋ณตํด์ฃผ๊ณ  i๋ฅผ 1์ฉ ์ฆ๊ฐ์ํค๋ฉฐ ret[i]์ a๋ฅผ ๋น๊ตํ์ฌ ํฐ ๊ฐ์ a์ ๋์ํ๋ค 

## ๐1.2.4 ํจ๋ฌ๋ค์์ ํผํฉ
๊ฐ์ฅ ์ข์ ํจ๋ฌ๋ค์์ด๋ผ๋ ๊ฒ์ ์๋ค. ๋น์ฆ๋์ค ๋ก์ง์ด๋ ์๋น์ค์ ํน์ง์ ๊ณ ๋ คํ์ฌ ํจ๋ฌ๋ค์์ ์ ํ๋ ๊ฒ์ด ์ข๋ค

ํ๋์ ํจ๋ฌ๋ค์ ๊ธฐ๋ฐ์ผ๋ก ํต์ผํ์ฌ ์๋น์ค๋ฅผ ๊ตฌ์ถํ๋ ๊ฒ๋ ์ข์ง๋ง ์ฌ๋ฌ ํจ๋ฌ๋ค์์ ์กฐํฉํด ์ํฉ,๋งฅ๋ฝ์ ๋ฐ๋ผ ํจ๋ฌ๋ค์ ๊ฐ์ ์ฅ์ ๋ง ์ทจํด ๊ฐ๋ฐํ๋ ๊ฒ์ด ์ข๋ค.

์๋ฅผ ๋ค์ด ๋ฐฑ์๋์ ๋จธ์  ๋ฌ๋ ํ์ดํ๋ผ์ธ๊ณผ ๊ฑฐ๋ ๊ด๋ จ ๋ก์ง์ด ์๋ค๋ฉด ๋จธ์  ๋ฌ๋ ํ์ดํ๋ผ์ธ์ ์ ์ฐจ์งํฅํ ํจ๋ฌ๋ค์, ๊ฑฐ๋ ๊ด๋ จ ๋ก์ง์ ํจ์ํ ํ๋ก๊ทธ๋๋ฐ์ ์ ์ฉํ๋ ๊ฒ์ด ์ข๋ค