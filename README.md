# dataset

> ๐ ๋จธ์ ๋ฌ๋ ํ์ต์ฉ ๋ฐ์ดํฐ์

```
* PyTorch๋ฅผ ํตํ ์ฐ๋ ๊ธฐ ์ด๋ฏธ์ง ๋ถ๋ฅ AI ๊ฐ๋ฐ์ ์ํด ์์๋ ํ๋ก์ ํธ์๋๋ค.
```

<br>

[_waste-datasets-review_](https://github.com/AgaMiko/waste-datasets-review)๋ฅผ ๋ฐํ์ผ๋ก ์ ๋ฆฌ๋ ๋ถ๋ฅ์ฉ ์ฐ๋ ๊ธฐ ์ด๋ฏธ์ง ๋ฐ์ดํฐ์ ์ค๋ช์๋๋ค. ๋ฐ์ดํฐ์์ ๊ถํ ์น์ธ ํ์ ์ฌ๋ถ ๋ฐ ๊ฐ ํด๋์ค๋ณ ๋ฐ์ดํฐ ์ ๋ฑ์ ์ ๋ณด๋ฅผ ์ ๊ณตํฉ๋๋ค.

<br>

TACO๋ฅผ ํฌํจํ 9๊ฐ์ ๋ฐ์ดํฐ์ ๋ชฉ๋ก์ JSON ํํ๋ก ์ ๋ฆฌํ์์ต๋๋ค.

```js
[
    {
        "name": "TrashNet", // ๋ฐ์ดํฐ์ ์ด๋ฆ
        "url": "https://github.com/garythung/trashnet", // URL
        "purpose": ["classification"], // ๋ฐ์ดํฐ์ ๋ชฉ์  (detection, classification)
        "requestRequired": false, // ๊ถํ ์น์ธ ํ์ ์ฌ๋ถ
        "classes": { // ๊ฐ ํด๋์ค๋ณ ๋ฐ์ดํฐ ์
            "glass": 501,
            "paper": 594,
            "cardboard": 403,
            "plastic": 482,
            "metal": 410,
            "trash": 137
        }
    },
    ...
]
```
