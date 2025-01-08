# Real-World Evidence: Considerations Regarding Non-Interventional Studies for Drug and Biological Products Guidance for Industry
- 작성자: [정현우](https://www.linkedin.com/in/vvoo/)

### 목차
---
1. [Introduction](#introduction)
2. [Background](#background)
3. [Consierations for Non-Interventional Studies](#considerations-for-non-interventional-studies)
4. [Reference](#reference)

## Introduction
본 가이드라인은 약물의 효과에 대한 실질적 증거 및(또는) 안정성에 대한 증거를 입증하고자 FDA에 Non-Interventional Study (혹은 Observational Study)를 제출하는 것을 고려하는 Sponsor와 Reseacher가 Non-Interventional Study를 제안할 때 고려해야 할 설계 및 분석과 관련된 속성을 설명함.

### Non-Interventional Study?
> 환자가 정해진 프로토콜에 따라 특정 중재(처치)를 할당받는 것이 아니라, 일상적인 의료 관행에서 시장에 출시된 관심 약물을 투여받는 유형의 연구  

예시)
- Observational Cohort studies
- Case-control studies
- Self-controlled studies

※ 참고: [Reflection Paper on Use of Real World Data in Non-Interventional Studies to Generate Real-World Evidence](https://causalinferencelab.github.io/Bridging-Causal-Inference-and-Real-World-Evidence-A-Study-of-FDA-and-Other-Regulatory-Guidelines/docs/Reflection_Paper_on_Use_of_Real_World_Data_in_Non-Interventional_Studies_to_Generate_Real-World%20Evidence.html)

### Non-Interventional Study에 사용되는 Real-World Data의 신뢰성과 관련성
- 신뢰성(reliability)
    - 정확성(accuracy)
    - 완전성(completeness)
    - 추적성(traceability): the method that allows for knowledge of data provenance
- 관련성(relevance)
    - 주요 연구 변수(노출, 결과, 공변량)에 대한 데이터의 가용성
    - 연구를 위한 충분한 수의 대표 환자(representative patients)

이 두 가지 요소들은
- 적절한 인과 추론을 만드는데 중요함.
- Label Change를 지원하거나 안전 문제를 해결하기 위해 Real-World Evidence를 생성하는데 사용할 수 있는 데이터의 적합성을 확립하는데 필수적임.


### Non-Interventional Study의 설계 단계의 이슈
>  FDA는 앞서 다음과 같은 가이드라인들을 제시했었음.
- 전자 건강 기록(EHR) 및 의료 청구 데이터와 레지스트리의 데이터를 사용하여 규제 의사 결정을 지원할 때의 사용 적합성(신뢰성 및 관련성)과 관련된 해당 이슈들 다루는 지침을 발표함.
    - 참고)
        - [Real-World Data: Assessing Electronic Health Records and Medical Claims Data To Support Regulatory Decision-Making for Drug and Biological Products](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/real-world-data-assessing-electronic-health-records-and-medical-claims-data-support-regulatory)
        - [Real-World Data: Assessing Registries To Support Regulatory Decision-Making for Drug and Biological Products](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/real-world-data-assessing-registries-support-regulatory-decision-making-drug-and-biological-products)
- RWD 소스에서 파생된 연구 데이터를 포함하는 applicable drug submission에서 현재 FDA가 지원하는 데이터 표준을 사용하기 위한 고려사항에 대한 지침을 발표함.
    - 참고) [Data Standards for Drug and Biological Product Submissions Containing Real-World Data](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/data-standards-drug-and-biological-product-submissions-containing-real-world-data)
- RWD access을 포함한 RWD 사용, study monitoring, safety reporting 및 other sponsor responsibilities을 포함하여 Non-interventional study에 대한 규제 고려 사항을 설명하는 지침을 발표함.
    - 참고) [Considerations for the Use of Real-World Data and Real-World Evidence To Support Regulatory Decision-Making for Drug and Biological Products](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/considerations-use-real-world-data-and-real-world-evidence-support-regulatory-decision-making-drug)

> 제시된 가이드라인들에서 논의된 2가지 이슈
1. 연구 설계 및 수행의 prespecification
2. FDA와 조기에 협력하는 것
- 이 2가지 이슈는 제안된 적응증(indication)에 대한 연구 질문을 다루기 위해 Non-Interventional Study 설계를 사용하는 것이 적절한지 여부를 판단하는데 중요함.
    
### 유의사항
- 일반적으로 FDA 지침 문서는 법적으로 집행 가능한 책임을 설정하지 않음.
- 주제에 대한 기관의 현재 생각을 설명하며 특정 규제 또는 법적 요구 사항이 인용되지 않는 한 권장사항으로만 간주되어야 함.
- 기관 지침에서 '해야 한다'(should)는 단어의 사용은 무언가를 제안하거나 권장하지만 요구 사항은 아니라는 것을 의미함.

## Background
- 약물에 대한 임상 연구를 수행하는 목적  
    : 다른 영향 요소(질병 과정에서의 자발적인 변화, 플라시보 효과, 편향된 관찰 등)로부터 약물의 효과를 구별하는 것
- Non-interventional Study에 의존할 때, 다음 두 경우에 영향을 받는 추정치를 기반으로 하는 경우 도출된 추론이 부정확할 수 있음.
    1. confounding (교란 요인)  
        예시)
        - 비교할 수 없는 치료 그룹
    2. other forms of bias  
        예시)
        - 연구 대상 환자를 선정하는 방법
        - 결과를 평가하기 위한 추적 기간이 잘못된 경우
        - 노출 환자와 노출되지 않은 환자에서 결과를 측정하는 정확도가 다른 경우
        - 주요 변수에 대한 데이터가 무작위로 누락된 경우  
        
    ※ 참고: [Bias and Confounding](https://causalinferencelab.github.io/Bridging-Causal-Inference-and-Real-World-Evidence-A-Study-of-FDA-and-Other-Regulatory-Guidelines/docs/Reflection_Paper_on_Use_of_Real_World_Data_in_Non-Interventional_Studies_to_Generate_Real-World%20Evidence.html#bias-and-confounding)  
- 이러한 두 요소의 존재를 식별하고 해결하는 것은 Non-Interventional Study를 계획하고 수행할 때 중요함.  
$\rightarrow$ 제품의 안전성과 효율성에 따라 규제 결정을 뒷받침하는 연구를 위한 Non-Interventional Study를 선택하기 전에 sponsor와 researcher는 연구 설계와 수행을 통해 진실된 치료 효과와 다른 영향을 구별할 수 있는 가능성이 얼마나 되는지를 고려해야 함.

※ 본 지침의 나머지 부분은 후원자가 규제 의사 결정을 위해 Non-Interventional Study를 사용할 때 일반적으로 발생하는 과제를 식별하고 해결하는 데 도움을 주며, 후원자가 사전 지정된 프로토콜 및 통계 분석 계획(SAP)을 개발하기 전에 고려해야 할 주제를 포함함.

## Considerations for Non-Interventional Studies
### Overview
- Sponsor가 이러한 유형의 연구를 사용하여 효과에 대한 실질적 증거 및/또는 안전성에 대한 증거를 입증할 때 고려해야 하는 Non-Interventional Study를 설계 및 분석의 중요한 속성을 설명함.
- 이 지침에 언급되지 않은 다른 속성도 특정 연구에 중요할 수 있음.
- FDA는 Sponsor가 Non-Interventional Study를 설계하는 초기 단계에서 기관과 협력하고 연구의 설계 및 제안된 수행과 관련된 기대치를 명확히 하는 데 필요한 충분한 정보를 제공할 것을 강력히 권장함.
- 설명된 모든 속성에 대한 자세한 정보를 FDA와 조기에 협력할 때 사용할 수 없거나 포함하는 것이 실행 가능하지 않을 수 있지만, Non-Interventional Study 설계에 대한 성공적인 제안서는 해당되는 경우 아래에 나열된 각 요소를 만족스럽게 다루어야 함.
- 사용 가능한 데이터 소스가 이러한 각 속성을 만족스럽게 다룰 수 있는 제안을 지원하지 않는 경우 대체 연구 설계를 고려해야 함.

### Summary of the Proposed Approach
- Sponsor는
    - 연구 수행을 시작하기 전에 관심 있는 연구 질문 및 연구 설계의 근거를 포함하여 연구 프로토콜을 마무리해야 함.
    - 제안된 접근 방식을 결정하기 전에 고려한 대체 연구 접근 방식과 후보 데이터 소스를 간략히 요약해야 함.
    - 대체 접근 방식(예: 무작위 시험, 단일군 시험)이 특정 연구 질문에 답하는 데 왜 실행 가능하지 않았는지 논의해야 함.
        - 이때, 관심 있는 약물의 사용과 관심있는 결과에 대한 심층적인 이해와 제안된 연구 모집단에서 exposure, outcome과 relevant covariates(관련 공변량)의 체계적이고 정확하게 수집하는 과정을 반영해야 함.

> FDA가 Non-Interventional Study에 대한 제안을 평가할 수 있도록 하기 위해 Sponsor는 아래에 나열된 각 연구 속성에 대한 정보를 제공해야 함.

- 연구 질문(연구 목적) 및 가설
- 제안된 Non-Interventional Study 설계를 사용하는 근거
- 연구 설계 선택  
(예: 코호트, 사례 대조, 자기 통제)
- 연구 목적 및 가설을 다루기 위한 데이터 소스 선택 제안, 고려된 대체 데이터 소스
- 제기된 연구 질문을 다루고 치료군의 결과의 평가 없이 잠재적 연구의 통계적 Precision를 추정하기 위해 수행된 예비 또는 타당성 연구 결과
- 인과 추론을 뒷받침하고 confounding 및 other forms of bias를 해결하기 위한 제안된 접근 방식  
(예: 대상 시험 에뮬레이션 또는 기타 개념적 접근 방식)
- 윤리적 고려 사항(예: 인간 피험자 보호와 관련된 문제)을 해결하는 방법에 대한 설명

### Study Design
지정된 연구 질문을 기반으로 Sponsor는 연구 설계 요소를 개발해야 함.

> 각 프로토콜은 아래에 나열된 각 중요 요소를 간결하게 설명해야 함.

- 전반적인 연구 설계를 설명하는 스키마와 이론화된 인과 관계를 명시하는 인과 관계 다이어그램  
(예: 방향성 비순환 그래프(DAG), 단일 세계 개입 그래프(SWIG))
- 출처 모집단 (Source Population, 연구 모집단이 추출될 모집단)
- 적격 기준 및 연구 모집단 (분석이 수행될 모집단)
- 주요 관심 변수에 대한 개념적 및 운영적 정의(Conceptual and operational definitions)와 관련 운영적 정의에 대한 검증 노력의 상태 (해당하는 경우)
    - Conceptual Definitions: 연구 구성 요소(예: 노출, 결과, 공변량) 또는 특징을 일반적 또는 질적 용어를 설명
    - Operational Definitions: 연구자가 특정 연구에서 구성 요소를 측정하기 위해 따르는 데이터별 작업 또는 절차
- 관련 공변량(Relevant covariates, 예: 수반 치료) 및 잠재적 편향을 해결하기 위한 대응 전략
- 모든 연구군에 대한 index date (time zero) 및 immortal time과 관련된 문제로 인해 도입된 잠재적 편향을 해결하기 위한 전략을 포함한 index date 할당 접근 방식
    - Index Date (time zero): 적격 기준을 충족하고 의도된 치료 전략에 배정되는 시간이며, 여기에는 치료가 전혀 없을 수도 있음.
    - Immortal Time: 참가자가 결과 사건에 대한 평가를 받기 위해 "생존"해야 하는 연구의 후속 시간
- 추적(follow-up) (위험) 기간의 시작 및 종료, 검열에 대한 계획된 접근 방식 및 추적에 대한 예상 손실(감염성 환자의 고갈 포함)

### Data Sources
- Sponsor는 
    - 제안된 데이터 소스가 특정 가설 및 연구 질문을 해결하는 데 적절함을 입증해야 함.
    - Non-Interventional Study 설계에 사용된 데이터 소스는 종종 연구 이외의 목적으로 생성되기 때문에 이러한 데이터 소스의 잠재적 한계를 이해하고 해당 한계를 해결할 수 있는지 또는 다른 데이터 소스를 활용해야 하는지 여부를 판단하는 것이 중요함.

> 각 프로토콜 또는 수반 문서는 아래 나열된 각 요소를 간략하게 설명해야 함.
- 제안된 데이터 소스에 대한 설명, 원래 데이터 수집 방법 포함
- 데이터 소스 선택의 근거
- 관심 있는 약물-결과 연관성에 대한 데이터의 관련성
- 관련 교란 요인(confounding factors)에 대한 정보의 적절성
- 데이터 신뢰성에 대한 사용 가능한 정보(소스 데이터에서 수집하는 방법 포함)
- 다양한 소스에서 데이터를 공유하기 위한 표준 구조를 제공하는 데 사용되는 일반적인 데이터 모델에 대한 설명과 특정 모델을 선택한 이유
- 주요 데이터 요소에 대한 평가 시기와 이러한 주요 데이터 요소의 완전성(completeness)에 대한 사용 가능한 정보
- 주요 변수의 운영적 정의에 따라 제안된 코딩이 적절한 이유에 대한 설명
- 대상 환자 집단에 대한 데이터의 적절성
- 추출된 원래 소스 데이터에서 수행될 품질 보증 활동
- 해당되는 경우 다른 데이터 소스에 대한 기존 또는 잠재적 링크  
(예: EHR 및 청구 데이터베이스의 데이터 병합, 결과를 확인하기 위해 RWD 소스를 사망률 데이터베이스에 연결)
- 해당되는 경우 추가 데이터 수집 계획

### Analytic Apporach
> 사전 지정된 SAP(Statistical Analysis Plan)는 특정 연구 목표를 다루고 1차 분석과 2차 분석을 자세히 설명해야 함.

- 표본 크기 계산 및 예상 운영 특성(예: 통계적 검정력)을 포함한 실행 가능성 평가
- 추정치의 지정(specification of estimand, 예: 동시 사건 처리 및 검열 규칙)을 포함한 치료 효과를 평가하는 데 사용된 통계적 접근 방식 또는 방법
    - estimand: 연구 목표에 의해 제기된 관심 과학적 질문을 해결하기 위한 추정 대상
- 측정되지 않은 교란 요인의 평가를 포함하여 잠재적 교란 요인을 설명하기 위한 특정 접근 방식
- 인과 경로에서 중간 변수의 잠재적 과조정 평가
- (해당되는 경우) 하위 그룹 분석에 대한 접근 방식 및 근거
- 비교된 그룹 간 결과의 불평등한 탐지 가능성을 해결하기 위한 접근 방식  
(예: 차등 감시 또는 차등 오분류)
- 노출을 유발하는 결과의 조기 발현 가능성을 평가하기 위한 접근 방식  
(예: 역인과성)
- 누락 또는 오분류된 데이터 처리 접근 방식
- 다중성 처리 접근 방식  
(예: 다중 노출 또는 다중 노출 분석을 포함한 다중 통계적 검정으로 인한 type 1 error의 가능한 인플레이션)
- 계획된 민감도 분석에 대한 설명, 변경이 제안된 요인과 그러한 변경의 근거에 대한 세부 정보 포함

## Reference
- [Real-World Evidence: Considerations Regarding Non-Interventional Studies for Drug and Biological Products](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/real-world-evidence-considerations-regarding-non-interventional-studies-drug-and-biological-products)