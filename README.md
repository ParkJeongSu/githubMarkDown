# How to use markdown

github에서 READEME.md 사용법을 알아보고자 한다.

------------------
# Header 사용법

```
"=" 를 사용하는 방법
헤더를 원하는 글자아래에 "=" 를 넣어준다

This is an H1
=============
```

> 실행결과

This is an H1
========

------------------

```
"#" 를 사용하는 방법
헤더를 원하는 글자앞에 "#" 를 넣어준다

# This is an H1
## This is an H2
### This is an H3
#### This is an H4
##### This is an H5
###### This is an H6
```

> 실행결과

# This is an H1
## This is an H2
### This is an H3
#### This is an H4
##### This is an H5
###### This is an H6

------------------

# styling text

------------------

```
bold : **This is bold Text**
ltalic : *This Text is italicized*
Strikethrough : ~~This was mistaken text~~
Bold and nested italic : **This text is _extremely_ important**
All bold and italic : ***All this text is important***
```
> 실행결과

**This is bold Text**

*This Text is italicized*

~~This was mistaken text~~

**This text is _extremely_ important**

***All this text is important***

------------------

# BlockQuote 인용문구

------------------
```
> This is a first blockqute.
>	> This is a second blockqute.
>	>	> This is a third blockqute.
```

> This is a first blockqute.
>	> This is a second blockqute.
>	>	> This is a third blockqute.

------------------

# Code 사용법

* ("```")을 사용하는 방법

<pre>
<code>
```
This is code Block.
```
</code>
</pre>

> 실행결과

```
This is code Block.
```

* pre 와 code 태그를 사용하는 방법
```
<pre>
<code>
This is code Block.
</code>
</pre>
```

<pre>
<code>
This is code Block.
</code>
</pre>

* 문법 강조기능
<pre>
<code>
```sql
SELECT
*
FROM
DUAL
WHERE
1=1
```
</code>
</pre>

```sql
SELECT
*
FROM
DUAL
WHERE
1=1
```

# github api 사용하기

```
출처 : https://github.com/anuraghazra/github-readme-stats


![jeongsu github stats](https://github-readme-stats.vercel.app/api?username=ParkJeongSu&show_icons=true&theme=merko)


[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=ParkJeongSu&layout=compact&exclude_repo=ParkJeongSu.github.io,Yun-Blog,intellij-settings)](https://github.com/anuraghazra/github-readme-stats)


```

![jeongsu github stats](https://github-readme-stats.vercel.app/api?username=ParkJeongSu&show_icons=true&theme=merko)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=ParkJeongSu&layout=compact&exclude_repo=ParkJeongSu.github.io,Yun-Blog,intellij-settings)](https://github.com/anuraghazra/github-readme-stats)