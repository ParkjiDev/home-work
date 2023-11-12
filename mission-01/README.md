# mission-01

---

![mission-01-결과](https://github.com/ParkjiDev/make-up-class/assets/148675654/2eb5cf45-14c6-4d32-8728-16357bd6bb4d)

**(문제가 되는 버튼 부분에 빨간색 상자로 표시했습니다.)**

---
![mission-01](https://github.com/ParkjiDev/make-up-class/assets/148675654/a46d4907-06e3-4b15-ae0e-b178463f2125)
---

- 공통
    1. figma 시안에 적용되어 있는 글꼴을 사용하기 위해 구글폰트의 Noto Sans를 사용했습니다.
    2. 화면상 가운데 배치를 위해 `margin: 0 auto` 설정을 했습니다.
    3. 각 구역의 테두리 설정을 위해`border: 1px solid #c4c4c4` 선언했습니다.
- 상단부
    1. 상단 영역을 `div.product-main` 으로 선언했습니다. 상단 영역 내에서 로고와 텍스트를 `div.product-main-wrap`로 묶어 `float: left`속성을 주고, 제품 이미지에 `float: right` 속성을 주어 각각 좌우로 배치했습니다.
    2. `div.product-main` 에 `padding`을 설정했고, 내부 제품 이미지에도 `padding-top`과 `padding-left` 값을 설정하여 이미지를 배치했습니다.
    3. 텍스트 속성은 figma 시안에 나온 속성 그대로 사용했습니다.
- 하단부
    1. 하단 영역은 `div.product-sub` 로 선언했습니다. 내부에서 하단 왼쪽 영역을 `div.product-sub-left` , 오른쪽 영역을 `div.product-sub-right` 로 선언하여 각각  `float: left` , `float: right` 속성을 주어 좌우 배치했습니다.
    2. `product-sub-right` `product-sub-left` 의 `padding` 설정과 `text-align: center` 를 설정하여 요소들을 배치했습니다.
    3. 텍스트 속성은 figma 시안에 나온 속성 그대로 사용했습니다.

(호버 기능은 구현하지 못한채로 제출합니다.)

---

- 문제점
    1. 위의 사진에서 빨간색 상자로 표시한 버튼의 이동이 제 예상과 다르게 되고 있습니다.
    각 버튼들에 `position: absolute` 값을 주고, `div.product-main`, `div.product-sub-left`, `div.product-sub-right`에 `position: relative` 값을 주어 위치 이동을 하려 했으나 다음과 같이 배치가됩니다. 어느 부분에서 문제가 된건지 궁금합니다.
        
        ![mission-01-버튼배치코드](https://github.com/ParkjiDev/make-up-class/assets/148675654/3264a5be-c641-4dd2-a5e7-cb4c585fb6a0)
        
        ![mission-01-버튼배치오류](https://github.com/ParkjiDev/make-up-class/assets/148675654/810d3af5-1ade-49e2-a9f2-8936e9b0db8d)
        
    
    1. 로고를 배치하다 보니 미~세한 틈이 보이는데 없애는 방법이 있는지요. 로고 bottom쪽엔 padding이나 margin은 없는 상태입니다.
    
    ![mission-01-로고밑공간](https://github.com/ParkjiDev/make-up-class/assets/148675654/b3fb0c35-82d9-49a2-9f69-5e9e170caf64)
    

그리고 과제를 하다 궁금한 점이 생길 경우 노션의 질의응답에 남겨도 되는지 궁금합니다! 아무래도 과제이다 보니 과제 기간중 질문을 남기는 것은 지양해야 하는건가 싶기도 해서요.

마지막으로.. 월요일 수업 시간에 선생님께서 과제 관련해서 수강생들에게 질문하신다고 하셨는데 기회가 된다면 그때 이부분에 대한 설명을 해주실수 있는지요.
