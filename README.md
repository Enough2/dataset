# dataset

> 📑 머신러닝 학습용 데이터셋

```
* PyTorch를 통한 쓰레기 이미지 분류 AI 개발을 위해 시작된 프로젝트입니다.
```

<br>

[_waste-datasets-review_](https://github.com/AgaMiko/waste-datasets-review)를 바탕으로 정리된 분류용 쓰레기 이미지 데이터셋 설명입니다. 데이터셋의 권한 승인 필요 여부 및 각 클래스별 데이터 수 등의 정보를 제공합니다.

<br>

TACO를 포함한 9개의 데이터셋 목록을 JSON 형태로 정리하였습니다.

```js
[
    {
        "name": "TrashNet", // 데이터셋 이름
        "url": "https://github.com/garythung/trashnet", // URL
        "purpose": ["classification"], // 데이터셋 목적 (detection, classification)
        "requestRequired": false, // 권한 승인 필요 여부
        "classes": { // 각 클래스별 데이터 수
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
