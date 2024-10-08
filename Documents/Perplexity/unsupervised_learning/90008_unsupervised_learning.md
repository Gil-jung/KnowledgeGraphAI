### 비지도 학습 (Unsupervised Learning)

비지도 학습은 레이블이 없는 데이터에서 패턴이나 구조를 발견하는 기계 학습의 한 분야입니다. 이 방법은 데이터의 내재된 특성을 이해하고 유용한 표현을 학습하는 데 중점을 둡니다.

주요 기법:

1. **클러스터링 (Clustering)**:
   - 데이터를 유사한 그룹으로 나누는 기법입니다.
   - 예: K-means, 계층적 클러스터링, DBSCAN

2. **차원 축소 (Dimensionality Reduction)**:
   - 고차원 데이터를 저차원으로 변환하여 중요한 특성을 추출합니다.
   - 예: 주성분 분석(PCA), t-SNE, UMAP

3. **이상치 탐지 (Anomaly Detection)**:
   - 정상적인 패턴에서 벗어난 데이터 포인트를 식별합니다.
   - 예: One-class SVM, Isolation Forest

4. **잠재 변수 모델 (Latent Variable Models)**:
   - 관측되지 않은 변수를 사용하여 데이터의 구조를 모델링합니다.
   - 예: 가우시안 혼합 모델(GMM), 잠재 디리클레 할당(LDA)

5. **자기 지도 학습 (Self-Supervised Learning)**:
   - 데이터 자체에서 지도 신호를 생성하여 학습합니다.
   - 예: 컨텍스트 예측, 회전 예측

응용 분야:
- 고객 세분화
- 추천 시스템
- 이미지 압축
- 유전자 발현 분석
- 네트워크 침입 탐지

비지도 학습의 장점:
- 레이블이 필요 없어 데이터 수집이 용이함
- 숨겨진 패턴을 발견할 수 있음
- 데이터에 대한 새로운 통찰을 제공함

비지도 학습은 데이터의 복잡한 구조를 이해하고 유용한 특징을 추출하는 데 강력한 도구로, 다양한 분야에서 활용되고 있습니다. 특히 빅데이터 시대에 레이블이 없는 대량의 데이터를 분석하는 데 중요한 역할을 합니다.