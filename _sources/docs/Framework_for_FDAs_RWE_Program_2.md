## Framework for FDA's Real-World Evidence Program2

작성자 : [전인영](https://www.linkedin.com/in/inyoungjun/)
## Information
- Source
	- https://www.fda.gov/media/120060/download?attachment
  - Information from the professional development course at JSM 2024 (Freda Cooner and Laura Fernandes).

- Topic
	- US FDA
	- Regulation
	- RWE

## Summary

### Using Trials or Studies with RWD/RWE for Effectiveness Decisions

- 기존에는 Clinical Trials “Efficiency” 를 향상하는데 RWD를 주로 사용했으며, “효과성” 결정에는 제한적으로 사용해왔음.
  - Ex) RCT로 테스팅할 연구 가설을 생성, 베이지안 방법 사용시 필요한 사전확률 계산, 지리적으로 퍼져있는 연구 코호트들을 결합 할 때 등
- 이제 약물 제품의 “Effectiveness”에 대한 규제 결정을 지원하기 위해 RWD를 사용하려는 관심이 큼
  - Ex) RWE를 사용하여 새로운 적응증을 추가하기 (i.e., purpose of treatment), 환자군, 용량, 용법, 투여 경로 변경 하기
- 고려해야할 중요한 사항
	- RWD를 사용하는 것이 적합한 지
	- 본 연구 설계가 규제 절차에 필요한 질문에 답할 수 있는 충분한 과학적 증거를 제공할 수 있는 실험 설계인지
	- 연구 수행 방식이  FDA 규제 요구 사항을 충족하는지 (ex. 연구와 데이터 수집에 대해 적절한 관리 감독이 되는지)
	
#### Assessing Fitness of RWD for Use in Regulatory Decisions

- Assessing Data Reliability (Data Accrual and Data Assurance) and Relevance
	- FDA는 어느 한 종류의 RWD를 선호하는 것은 아니며, 각 규제 조건에 맞는 적합성을 기준으로 RWD를 선정하는 것이 필요함  
  Ex) 약물 안정성의 경우, electronic health records를 사용하는 것에 대한 가이드라인은 존재함
	- FDA는 claim data, EHR, Registries, 및 international dataset의 신뢰성 및 적합성 평가에 대한 지침을 발행할 계획임
- Addressing gaps in RWD sources
  - EHR 및 의료 청구 데이터의 한계:
		- 관심 질문에 필요한 모든 데이터 요소를 포착하지 못할 수 있음
		- 주요 사건등은 기록되지만, 우울증 악화,  관절 통증 증가, 피부 상태 변화, 천식 악화 등과 같은 사건은 일관되게 문서화되지 않을 수 있음
    - 환자 증상은 비정형 데이터로 기록될 수 있어 접근성이 제한될 수 있음
    - 만성 질환의 중증도 변화 데이터는 의료 청구 데이터에서 쉽게 이용할 수 없음
  - RWE 개발 및 사용 개선 필요:
    - EHR의 정보 접근성과 연결성 향상 필요
    - 환자 경험은 임상 사건으로 기록되지 않으면 포착되지 않을 수 있음
    - EHR 시스템 간의 형식 차이로 데이터 수집이 어려움
    - 의료 시스템의 상호 운용성 부족으로 데이터 통합이 어려움

 #### Potential for Study Designs Using RWD to Support Effectiveness

- Randomized designs using RWD
  - FDA가 RWD를 활용한 pragmatic*한 연구를 평가할 때 고려사항:

  *pragmatic: does this intervention work under usual conditions?

- Non-Randomized, Single Arm Trials with Eternal RWD Control
  - 외부대조군External Control Arm (ECA): 과거의 전통적인 임상시험 데이터를 사용하거나 RWD로 만들어진 대조군으로 comparative effectiveness를 측정하는데 사용됨
  - 특히 rare disease거나 pediatric disease 또는 치료 방법이 제한적인  life-threatening cancer의 경우 대조군을 기존의 완료된 RCT에서 사용하는 경우가 있었음
  - Propensity-score matching을 사용해 RWD ECA를 구성할 수 있음
  - ECA의 장점으로는 patient centric (i.e., 더 적은 환자들이 standard-of-care나 placebo-control arm에 할당되기 때문), cost effective, accelerated clinical development 등이 있음
- Observational Studies
  - FDA가 RWD를 활용한 retrospective observational 한 연구를 평가할 때 고려해야 하는 중요한 부분은 다음과 같음:
    - 도움이 되는 ‘데이터’인지 (적절한 endpoint가 있는지, 문서가 일관되는지, 누락데이터가 없는지)
    - 도움이 되는 ‘연구 설계와 분석 방법’인지
    - 사전에 고려해 볼 sensitivity analyses나 statistical diagnostics는 무엇인지?
  - 연구 설계 및 분석의 투명성 확보가 결과에 대한 신뢰를 보장하는데 중요함

####  Regulatory Considerations for Study Designs Using RWD
	- Use of Electronic Source Data
  	- Electronic Source Data in Clinical Investigations (2013)
    - Use of EHR in Clinical Investigations (2018)
    - Use of Electronic Records and Electronic Signatures in Clinical Investigations under 21 CFR Q&A (2017)
  - Regulatory Considerations for Clinical Studies generating RWE
    - FDA는 RCT에서 생성된 데이터가 RWE 생성에 사용될 경우 어떻게 다룰 것인지도 평가 할 것

#### Data Standards – Appropriate Data Standards for Integration and Submission to FDA
- FDA는 RWD/RWE를 활용하기 위해 필요한 데이터 표준 및 구현 전략을 평가하고 FDA 규제의 필수적인 부분이 되도록 보장하기 위한 노력을 할 것

## Regulatory Example: rGBM
#### MEDICENNA Case
  - Background: Glioblastoma is a type of cancer that starts as a growth of cells in the brain or spinal cord. Glioblastoma is one of the most aggressive forms of cancer with very limited treatment options. Patients typically survive less than 15 months after first diagnosis and only 6-9 months following relapse. There's no cure for glioblastoma. Treatments might slow cancer growth and reduce symptoms. The nature of rGBM makes it extremely difficult to recruit and retain patients for study in a clinical setting.
  - Original Phase2 Design: The company originally designed a single-arm study. All patients will receive active treatment (i.e., bizaxofusp). No randomization will be performed, and no blinding procedures are employed.
  - Revised Phase2 Design: The company selected ‘Medidata AI’ company to create SCA to re-analyze their Phase 2 trial to better understand the treatment effect. They compared overall survival with contemporaneous eligibility-matched and propensity score based external control arm (presented 2024 May)
    - Bizaxofusp Arm(ITT N=47, PPP N=44) vs. ECA (N=81)
    - ECA was not part of the original study design, the trial was under-powered.
    - From the P2b analysis, the knowledge supported sample size calculations for the hybrid phase 3 design.
  - Phase3 Design: Then the company design P3 registrational trial that could successfully recruit and retain patients to demonstrate the effects of MDNA55 for registration. The P3 study with bizaxofusp vs hybrid control arm
  - Source: Medicenna phase2b study silde - ASCO Annual Meeting 2024; professional development course at JSM 2024 (Freda Cooner and Laura Fernandes)



