# mission-03 (Netflix)

## tree
![tree](https://github.com/ParkjiDev/test/assets/148675654/87d101cd-6edf-47f6-a02f-1fc86f3b83f5)
- 컴포넌트 단위로 나누어 개발
- 최종 완성된 페이지는 home.html에 작성

## 결과 화면
1. desktop 버전 전체화면
![full-desktop-normal](https://github.com/ParkjiDev/test/assets/148675654/71f0cbf9-2b5a-46fc-94af-8104aea3b351)
2. desktop 버전 상황별 form style<br/>
![desktop-합본](https://github.com/ParkjiDev/test/assets/148675654/22c4bb24-90cd-45ea-b14c-61e0a6947f9b)
3. mobile 버전 전체화면<br/>
![full-mobile-normal](https://github.com/ParkjiDev/test/assets/148675654/1b047828-3ac6-4d0d-986e-399e36eaaf02)
4. mobile 버전 상황별 form style<br/>
![mobile-합본](https://github.com/ParkjiDev/test/assets/148675654/74c71d11-ecdf-4df3-b026-b0ea3f9b40c1)
5. 다크모드 style 변경<br/>
![darkmode](https://github.com/ParkjiDev/test/assets/148675654/71c1dae3-a50d-4d4a-aec8-827348b39259)

## 코드
1. 다크모드 style 변경 코드<br/>
![code-1](https://github.com/ParkjiDev/test/assets/148675654/0ccac0bd-4166-4a89-bde8-4aae8e8eda68)
2. 해상도와 크기에 따라 logo파일을 선택하도록 개발<br/>
![code-2](https://github.com/ParkjiDev/test/assets/148675654/4e412414-4584-4178-bed2-459aae4b88b2)
3. select box style 변경을 위한 css 코드<br/>
![code-3](https://github.com/ParkjiDev/test/assets/148675654/54c48ea6-a9b8-4811-b98d-b83fda1e476b)

## 궁금한점
1. form안에 desktop 상황의 태그와 mobile 상황의 태그를 모두 작성한 상태입니다. home.css 파일에서 미디어쿼리를 사용하여 상황에 맞게 둘 중 하나는 display: none 처리를 하고 있는데, 이 경우 문제가 생기는지 궁금합니다.
   같은 마크업에서 미디어쿼리를 사용하여 style만 변경하도록 코드를 작성해야 하나요?
2. '30일 무료 이용'과 같이 다른 페이지에서 재사용 가능성이 낮은 버튼의 경우 컴포넌트로 나눠 작업하는 것은 비효율적일까요?
3. logo.html에서 이미지를 불러올때 수업에서 진행한 것과 동일하게 figure를 사용하였으나 왜 단순히 img태그를 사용하는 것이 아닌 figure 태그를 사용하였는지 잘 모르겠습니다..
4. 웹접근성을 고려한 마크업 작성이 아직은 굉장히 어렵네요..
