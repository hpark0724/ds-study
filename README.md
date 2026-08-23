# ds-study

Python EDA and TensorFlow prediction practice notebooks, following a data science course curriculum.

---

## Python EDA

### Sephora 화장품 데이터 EDA
> seaborn 내장 mpg 데이터로 배운 단변량 EDA 기법을, Sephora 데이터셋에 적용

- [x] price, rating, loves_count 분포 확인
- [x] skew/kurt로 치우침 비교
- [x] mpg와 차이점 분석

**다룬 내용**
- `price_usd`, `rating`, `loves_count` 분포 시각화 (histplot, displot, kdeplot, rugplot)
- 도수분포표 직접 구성 (`pd.cut` + `value_counts`)
- 왜도(skew), 첨도(kurt)로 분포 특성 정량화
- z-score 표준화를 통한 첨도(K) 비교
- boxplot, violinplot으로 사분위수 및 이상치 확인

데이터 출처: [Sephora Products and Skincare Reviews](https://www.kaggle.com/datasets/nadyinky/sephora-products-and-skincare-reviews) (Kaggle)
강의 출처: 부스트코스 [모두를 위한 데이터 사이언스](https://www.boostcourse.org/) — 5.3 수치형 변수의 탐색적 데이터 분석

---

## TensorFlow

(추가 예정)

---

## 사용 도구

Python, pandas, seaborn, matplotlib, scipy
