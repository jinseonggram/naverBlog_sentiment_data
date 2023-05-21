# Naver Blog Sentiment Corpus 3 Class

This is sentiment dataset in Korean Language.

The source of dataset is naver blog.

have 3 class (positive, negative, neutral)

## Description

- The dataset consists of 2 Parts (sentence, label):
    - sentence : One sentence of blog content
    - label : The sentiment class of sentence (-1: negative, 0: neutral, 1: positive)

- 95K sentences

## Characteristics
- Number of each class
  - Number of Positive class rows (50K)
  - Number of Negative class row (8K)
  - Number of Neutral class rows (40K)
- Raw Real Life Natural Language

## Example

```angular2html
$ head sentiment.csv

밑반찬의 종류도 한두가지가 아니라 많은 편이라서 더 좋았어요.    1
매콤해 보이는 모습이지만 그리 자극적이지 않았고 살결도 연하니 술술 넘어가게 되더라고요. 1
바다쪽으로 내려 가보려고 내려왔는데.. 손가락만 한 바다 바퀴벌레 진짜 많았음.. 여태 본 바다바퀴벌레는 그냥 애기 수준?    -1
카운터 쪽에는 눈으로만 봐도 존맛탱 포스 제대로 뿜뿜하는 케이크들이 우리부부를 반기는듯한 느낌이 딱! 당연히 케이크랑 함께 마실 음료를 주문해봤지욤 부산 광안리 카페 차선책 메뉴판입니다. 1
날치알과 치즈가 적당히 어우러져서 너무나 맛있더라고요.  1
저희는 미리 KKday 로 예약을 해서 할인 받을 수 있었는데요.       0
카드 현금결제 가능 주차하고 등선폭포를 향해 걸어올라가다보면 매표소가 나와요!   0
쫀득한 어육은 씹을수록 부드러워졌고 특제양념에 찍어먹으면 더욱 진한 어향을 느낄 수 있어 중독성이 상당했어요.    1
존맛이었던 에그드랍 여태 한번도 먹어본적 없었는데 호텔 1층에 있길래 부산에서만 두 번을 사 먹음 유럽에 살고 있으니 반대로 한국에서의 여행이 더 재미있게 느껴지네..       1
```

## License

<p xmlns:dct="http://purl.org/dc/terms/">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
</p>

______

made by @redJunBro , @jinseonggram
