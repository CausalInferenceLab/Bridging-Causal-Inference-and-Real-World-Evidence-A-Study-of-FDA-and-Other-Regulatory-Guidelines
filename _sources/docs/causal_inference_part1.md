# 작성 중 (24.10.2 발표)
작성자 : [박상호](https://www.linkedin.com/in/shstat1729/)
## 우리가 하고 싶은 것
우리는 대상에게 어떤 처치를 했을 때 어떤 효과를 나타내는지 알고 싶어 합니다. 예를 들어, 암을 치료하는 신약을 암환자에게 투여했을 때 환자의 생존 기간이 얼마나 늘어날까? 라는 물음을 가지지요. 혹은 1인당 초콜릿 소비량이 국가의 노벨상 수상자 수에 어떤 영향을 미치는지 궁금할 것입니다. 다음은 NEJM(New England Journal of Medicine)이라는 논문에 출판된 그림입니다.

![](../pics/Chapter1-01.png)

1인당 초콜릿 소비량이 클수록 국가의 노벨상 수상자 수가 커진다고 나타내고 있습니다. 이 논문에서는 아마도 초콜릿 소비가 증가하면 congitive function에 영향을 주어 노벨상 수상자 수가 증가한다고 이야기합니다. 그런데 정말 그렇게 이야기할 수 있을까요? 국가의 GDP나 1인당 소득이 초콜릿 소비량과 노벨상 수상자 수에 모두 영향을 미치지 않았을까요?

우리는 위와 같은 경우를 "연관관계가 있다"고 표현합니다. 하지만 "인과관계"가 있다고 쉽게 이야기하지 못합니다. 그럼 언제 그렇게 이야기할 수 있을까요? 이 물음이 오늘 나눌 이야기의 핵심입니다.

## Notation
$T_i$는 실험대상 i에 대한 처치여부를 나타냅니다.

$T_i=
\begin{cases}
1 \ \text{: 실험대상 i가 Treatment를 받은 경우}\\\\
0 \ \text{: 실험대상 i가 Treatment를 받지 않은 경우}\\\\
\end{cases}$

Unit i에 대해 관찰된 결과 변수(Outcome variable)를 $Y_i$라고 정의합니다.

인과적 추론의 근본적인 문제(Fundamental problem of causal inference)는 Treatment가 있든 없든 같은 실험 대상에 대해 동시에 관찰할 수 없다는 것입니다. 이와 관련된 개념이 잠재적 결과(Potential Outcomes)입니다.

$Y_{0i}$ : 실험대상 i가 Treatment를 받지 않은 잠재적 결과를 의미합니다.
$Y_{1i}$ : 같은 실험대상 i가 Treatment를 받은 잠재적 결과를 의미합니다.

때로는 여러분들이 잠재적 결과를 함수 $Y_i(t)$로 보실 수 있는데요, 이 부분을 주의해주세요. $Y_{0i}$가 $Y_i(0)$로 표기될 수 있고 $Y_{1i}$는 $Y_i(1)$일 수 있습니다. $Y_{1i}$는 태블릿이 있는 교실에 있는 경우 학생 i에 대한 학업 성취도를 나타냅니다. 만약 학생 i가 태블릿을 받았다면, $Y_{1i}$를 관찰할 수 있어요. 만약 태블릿을 받지 못한 경우는 $Y_{0i}$를 관찰 할 수 있겠죠? 태블릿을 받지 못한 경우, $Y_{1i}$가 여전히 정의되어 있지만 우리가 관측할 수 없어요. 이는 반사실적 잠재적 결과입니다.

잠재적 결과를 통해, 개별 처치 효과(ITE, Individual Treatment Effect)를 정의할 수 있게 됩니다.

$Y_{1i} - Y_{0i}$

물론, 인과추론의 근본적인 문제로 인해 잠재적 결과 중 하나만 관찰할 수 있습니다. 그렇기 때문에 ITE를 알 수 없습니다. 그래서 당분간은 ITE를 추정하는 것 대신, 추정하기 더 쉬운 **평균 처치 효과 (ATE, Average Treatment Effect)**에 대해 알아보도록 해요.

$ATE = E[Y_1 - Y_0]$

조금 더 추정하기 쉬운 값은 **처치받은 그룹에 대한 평균 처치 효과(ATET/ATT, average treatment effect on the treated)** 입니다.

$ATT = E[Y_1 - Y_0 | T=1]$


참고문헌 : [https://causalinferencelab.github.io/Causal-Inference-with-Python/01-Introduction-To-Causality.html](https://causalinferencelab.github.io/Causal-Inference-with-Python/01-Introduction-To-Causality.html)
[Messerli, F. H. (2012). Chocolate consumption, cognitive function, and Nobel laureates. N Engl J Med, 367(16), 1562-1564.](https://cbb.sjtu.edu.cn/~jingli/courses/2018fall/bi372/files/NEJM.pdf)