# KB 헬스케어

건강 검진 데이터를 기반으로 한 건강 점수 차트를 확인할 수 있습니다.

<br />

## 🎉 **배포 주소**

- [https://kb-7.netlify.app/](https://kb-7.netlify.app/)

<br />

## 👬 **팀원**

- 프론트엔드 9명

<br>

## 📅 **개발 기간**

- 2022년 5월 26일 ~ 2022년 5월 27일

<br />

## 🔧 **기술스택**

- Typescript, React, Sass

<br />

## 💻 **설치 및 실행 방법**

1. yarn 설치

```
 npm i yarn
```

2. repository 클론

```
git clone https://github.com/Yu-jae-min/POB_KB-Healthy-Care.git
```

3. dependencies 설치

```
yarn install
```

4. 실행

```
yarn start
```

## 📒 **구현 목록**

|나의 건강점수|나의 10년 후 건강 예측|맞춤 건강관리|
|:-:|:-:|:-:|
|![KB1](https://user-images.githubusercontent.com/69314161/170706846-b0f709b9-7618-4ac5-86f6-a2345b0b672a.png)|![KB2](https://user-images.githubusercontent.com/69314161/170707159-5fa01938-ec2e-47e3-a016-aced314ac74f.png)|![KB3](https://user-images.githubusercontent.com/69314161/170706892-369c1c13-92ce-458a-884f-ab25ddfa645b.png)|

<br />

### # 나의 건강점수

- [x] 건강점수 차트

    - [x] 개인 건강 점수 VictoryPie를 활용한 원형 차트로 노출

    - [x] 데이터 기준 날짜 표시

- [x] 사용자 기본 정보 표시

    - [x] 성별/나이/키 박스 형태로 표시

- [x] 건강점수 연도별 변화 차트

    - [x] 최근 4개의 연도별 건강점수 막대 + 라인 그래프. 값도 표시

    - [x] 텍스트는 별도 장표로 설명

    - [x] 가장 최근 데이터에 색깔 표시

    - [x] 값 1개만 있는 경우 노랑색으로 그리고 ‘YYYY년 건강 점수는 000점 입니다.’ 텍스트 표시

    - [x] 검진결과 상세 화면으로 이동 (UI만 표시)

<br>

### # 나의 10년 후 건강 예측 (담당 기능)

- [x] 상위 퍼센테이지를 나타내는 타이틀 노출

- [x] victory js 차트 라이브러리를 활용하여 건강 점수 비교 차트 구현

    - [x] 현재 점수와 예측 점수 및 평균 점수와 비교하는 차트 구현

    - [x] 점수 비교 후 결과에 따라 조건부 타이틀 노출

    - [x] VictoryGroup, VictoryLinem, VictoryScatter를 활용한 차트 라인 추가

    - [x] toLocaleString 메소드를 활용한 콤마 지정

<br>

### # 맞춤 건강관리

- [x] 맞춤 건강관리 페이지

    - [x] 맞춤 건강관리 안내 텍스트

    - [x] 개선가능한 점수 표기

    - [x] 맞춤 건강관리 카드

        - [x] 현재 수치 + 웰시콘 평가 분류값 노출

        - [x] 정상 범위 안내

        - [x] 태그 – 추천 키워드 항목 최대 3개 노출

        - [x] 웰시콘 건강가이드 ‘행동 목표＇노출 (행동 목표가 없는 경우 비노출)

<br>
