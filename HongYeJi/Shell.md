์ธ์ ๊ธฐ๋ฅ
-------
๐ ์ธ์ ์ฌ์ฉ์์ ๋ฆฌ๋์ค ์ปค๋ ์ฌ์ด์์ ์ค๊ฐ์ ์ญํ ์ ์ํํจ
1. ๋ช๋ น์ด ํด์๊ธฐ ๊ธฐ๋ฅ
2. ํ๋ก๊ทธ๋๋ฐ ๊ธฐ๋ฅ
3. ์ฌ์ฉ์ ํ๊ฒฝ ์ค์  ๊ธฐ๋ฅ

์ธ์ ์ข๋ฅ
-------
โญ๏ธ chsh : ์ค์ฉ์ ๋ก๊ทธ์ธ ์ธ์ ๋ฐ๊พธ๋ ๋ช๋ น์ด   
1. ๋ณธ ์ธ(์ฒ์ ๋ฑ์ฅํ ์ธ๋ก, ๋ณธ ์ธ์ ๋ช๋ น ์ด๋ฆ์ sh)   
2. C ์ธ(๋ณธ ์ธ์๋ ์๋ ์์ผ๋ฆฌ์ด์ค๋ ํ์คํ ๋ฆฌ ๊ฐ์ ์ฌ์ฉ์ ํธ์ ๊ธฐ๋ฅ์ ํฌํจ, ๋ช๋ น ์ด๋ฆ์ csh)  
3. ์ฝ ์ธ(๋ณธ ์ธ๊ณผ์ ํธํ์ฑ์ ์ ์งํ  ๋ฟ๋ง ์๋๋ผ C ์ธ์ ํน์ง๋ ๋ชจ๋ ์ ๊ณตํ๋ฉด์ ์ฒ๋ฆฌ ์๋๋ ๋น ๋ฆ, ๋ช๋ น ์ด๋ฆ์ ksh)
4. ๋ฐฐ์ ์ธ(๊ณต๊ฐ ์ํํธ์จ์ด๋ก์ ๋ฆฌ๋์ค์ ๊ธฐ๋ณธ ์ธ๋ก ์ ๊ณต๋์ด ๋ฆฌ๋์ค ์ธ๋ก๋ ๋ง์ด ์๋ ค์ง, ๋ช๋ น ์ด๋ฆ์ bash)
5. ๋์ ์ธ(๋ถํ ์ ์ธ ์คํฌ๋ฆฝํธ๋ฅผ ๋น ๋ฅด๊ฒ ์คํ์ํค๊ณ  ํ์ผ ํฌ๊ธฐ๊ฐ ์์ผ๋ฉฐ ์ ๋ขฐ์ฑ์ด ๋์, ๋ช๋ น ์ด๋ฆ์ dash)     

์ธ ํน์๋ฌธ์
--------
<img src="https://ifh.cc/g/3u6Gpt.jpg" width="50%" ></img>   
์ฌ์ง : ์ฐ๋ถํฌ ๋ฆฌ๋์ค p.156 (์ ์ : ์ด์ข์)

์ถ๋ ฅ ๋ฆฌ๋ค์ด๋ ์
-----------
ํ์ผ ๋ฎ์ด์ฐ๊ธฐ : >   
ํ์ผ์ ๋ด์ฉ ์ถ๊ฐํ๊ธฐ : >>   

์ค๋ฅ ๋ฆฌ๋ค์ด๋ ์
-----------
ํ์ค ์ค๋ฅ ๋ฉ์์ง๋ฅผ ํ์ผ์ ์ ์ฅ : 2>

์๋ ฅ ๋ฆฌ๋ค์ด๋ ์
-----------
ํ์ค ์๋ ฅ ๋ฐ๊พธ๊ธฐ : <

์ธ ๋ณ์์ ํ๊ฒฝ ๋ณ์
---------------
(1) ๋ณ์ ์ ์   
๐ ์ธ ๋ณ์ : ๋ณ์๋ช=๋ฌธ์์ด   
๐ ํ๊ฒฝ ๋ณ์ : export ๋ณ์๋ช=๋ฌธ์์ด, export ๋ณ์๋ช=์ธ ๋ณ์๋ช   
(2) ๋ณ์ ์ ์ ํด์    
: unset ๋ณ์   
(3) ์ ์ฒด ๋ณ์ ์ถ๋ ฅ   
: set, env   
(4) ํน์  ๋ณ์ ์ถ๋ ฅ   
: echo $๋ณ์   

์ฃผ์ ํ๊ฒฝ ๋ณ์
----------
+ HISTSIZE : ํ์คํ ๋ฆฌ ์ ์ฅ ํฌ๊ธฐ
+ HOME : ์ฌ์ฉ์ ํ ๋๋ ํฐ๋ฆฌ์ ์ ๋ ๊ฒฝ๋ก
+ LANG : ์ฌ์ฉํ๋ ์ธ์ด
+ LOGNAME : ์ฌ์ฉ์ ๊ณ์  ์ด๋ฆ
+ PATH : ๋ช๋ น์ ํ์ํ  ๊ฒฝ๋ก
+ PWD : ์์ ๋๋ ํ ๋ฆฌ์ ์ ๋ ๊ฒฝ๋ก
+ SHELL : ๋ก๊ทธ์ธ ์ธ

์์ผ๋ฆฌ์ด์ค
-------
: ๋ช๋ น์ ๋ค๋ฅธ ๋ณ์นญ์ ๋ถ์ด๋ ๊ฒ   
+ ์์ผ๋ฆฌ์ด์ค ์์ฑ : alias ์ด๋ฆ='๋ช๋ น'   
+ ์์ผ๋ฆฌ์ด์ค ์ญ์  : unalias ์ค์ ํ ์์ผ๋ฆฌ์ด์ค

์ถ์ฒ : ์ฐ๋ถํฌ ๋ฆฌ๋์ค - ์์คํ & ๋คํธ์ํฌ (์ ์ : ์ด์ข์)
