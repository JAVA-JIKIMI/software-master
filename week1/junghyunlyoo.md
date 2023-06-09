# 1장 21세기의 소프트웨어 개발

### 이 책을 읽게된 이유
 아마 3년 전쯤으로 기억하는데, 한창 이직 준비할 때 많은 개발 서적들을 사서 공부했었다. 이번 '소프트웨어 장인'이라는 책은 그 서적들 중 하나였다. 그런데 당시 읽었던 내용들이 하나도 기억나지 않는다. 워낙 여러 책을 정신없이 보느라 제대로 보질 못했기 때문인 것 같다. 또한 당시에는 개발 경험이 적어서 책 내용에 대해 크게 공감하지 못했던 것 같기도 하다. 더군다나 `당시에 재직했던 회사의 조직 구조는 이 책에서 중요하게 다루는 '애자일 조직'과는 거리가 멀었기 때문에, 머리로는 읽었지만 몸으로는 읽지 못했기 때문`이 아니었을까 싶다. 그러던 중 이번 스터디 주제로 이 책이 선정되어 다시 읽어보게 됐다.

### 시대 변화에 따른 소프트웨어 개발자의 변화
 1장에서는 '시대의 흐름에 따라 변화하는 소프트웨어 개발자에 대한 정의'가 가장 기억에 남는다. 1990~2000년대 초에는 소프트웨어 사용자들이 소프트웨어에 사용에 대해 그렇게 민감하게 반응하지 않았을 것 같다. 기존에 없었던 새로운 산업이기도 하고 소프트웨어들 사이에서의 대체재가 많지 않았기 때문에, 당시의 IT 기업들은 고객을 붙잡는 것에 (지금보다) 그렇게 필사적이지 않아도 안정적인 회사 유지가 가능했을 것이다. 그래서 IT 기업들은 현재 상태를 유지하는 성격의 의사 결정들을 했을 것이다. 이에 따라 그 당시의 소프트웨어 개발자들에게는 변화 무쌍한 모습보다는 현재 서비스들을 안정적으로 유지하는 능력이 요구되었을 것 같다.

 

 그러나 이제 `시대가 바뀌었다.` 소프트웨어 사용자들은 소프트웨어 사용에 대해 이전보다 훨씬 민감하게 반응한다. 특정 소프트웨어의 사용에 대해 조금이라도 문제가 있으면 쉽게 다른 소프트웨어를 사용한다. 시장이 커지고 경쟁 회사들도 많아졌기 때문이다. IT 기업들은 긴장하기 시작했고 이 상황에 대응해야 했다. IT 기업들은 이전처럼 현재 상태를 유지하는 것만으로는 시장에서 살아남을 수 없게 되었고 소비자를 위해 무언가라도 더 변화하고 더 개선해야 했다. 이러지 못하는 기업들은 경쟁에서 도태되어 시장에서 사라지고 있다. 기업들은 변화에 유연해야 했고 시장 상황에 맞춰 기민하게 조직을 바꾸기 시작했다. 자연스럽게 기업 내 각 구성원 개개인들의 서비스에 대한 영향력이 커지게 되었다. 이는 소프트웨어 개발자에게도 마찬가지였다. 기업은 큰 흐름의 변화를 주도할 뿐 세세한 변화들까지는 가이드하기 힘들기 때문에, 소프트웨어 개발 실무자들은 이전처럼 단순히 개발만을 담당할 순 없었다. 기업의 변화에 맞춰서 본인들도 변화해야 했고 서비스에 대한 더 큰 영향력이 요구되었다. 소프트웨어 개발자를 보는 IT 기업들의 눈도 높아지고 있다. `낮은 비용의 가성비가 높은 개발자보다는 높은 비용을 지불해야 하더라도 변화에 능숙하고 서비스에 대해 높은 영향력을 펼칠 수 있는 개발자를 선호하고 있다.`

 

 지금 내가 재직중인 회사는 능숙한 변화와 서비스에 대한 높은 영향력을 요구하는 스타트업이다. 이번 1장을 읽고, 시장 흐름에서 내가 어떠한 위치에 있는지를 그리고 어떤 능력을 길러야 하는지를 다시 한번 상기할 수 있었다.
 
# 2장 애자일
 
### 애자일(agile)의 사전적 의미
 애자일이라는 단어가 특정한 업무 방식을 정의하기 위해 탄생한 단어인 줄 알고 있었다. 하지만 `애자일은 원래 존재하던 단어`였고, 특정한 업무 방식을 잘 설명하는 단어이기 때문에 차용되었을 뿐이었다. 이 책을 읽어보면서 애자일의 사전적 의미를 찾아봤는데, 이 의미를 이해하고 있다면 애자일 방법론을 더 정확하고 깊이 이해할 수 있을 것이다.

<img width="293" alt="image" src="https://github.com/JAVA-JIKIMI/software-master/assets/47667821/0b052d36-2bef-44a9-93d9-b1b95a64b890">


### 애자일 방법론은 '서비스를 유연하고 빠르게 변화시키는 업무 방법론'
 나름대로 애자일의 정의를 내려봤다. 1장에서는 '기업들은 변화에 유연해야 했고 시장 상황에 맞춰 기민하게 조직을 바꾸기 시작했다.'라고 했었는데, 이러한 변화에 맞춰서 업무 방식도 '유연하고 빠른 서비스의 변화'에 초점이 맞춰진 것 같다. 그래서 실무자들은 `서비스를 유연하고 빠르게 변화시킬 수 있는 업무 방식`을 익혀야 했다. 이러한 업무 방식을 애자일 형태의 업무 방식이라고 한다. 이 방식을 자세하게 설명한 것이 애자일 방법론이다.

### 애자일은 실천하는 것이 중요
 마치 게임 캐릭터가 좋은 무기를 장착해서 공격력이 상승하는 것처럼, 애자일을 적용하는 것만으로도 쉽게 업무 능력이 상승하면 좋을 텐데 아쉽게도 그렇진 않다. '영어를 잘 하려면 많이 말하고 많이 들어야 한다'라는 것은 누구나 다 안다. 하지만 실천이 어렵다. 애자일도 마찬가지다. 애자일에 대해 깊게 이해하는 것도 좋지만 `조금씩이라도 애자일을 실천하는 것이 중요`하다. 영어를 잘 하기 위해서는 '말하고 듣는 방법을 많이 아는 것'보다 '많이 말하고 많이 듣는 것'이 더 중요할 것이다.

### 애자일은 문제 자체를 해결해주지는 않는다.  다만 애자일은 문제를 드러나게 한다.
 아쉽게도 애자일을 잘 실천하는 것만으론 서비스가 민첩하게 변화하지 않는다. 애자일은 서비스를 민첩하게 변화시키는 것을 결정적으로 도와줄 뿐 직접 변화시키지는 않는다. 변화시키는 것은 우리의 몫이다. 애자일을 잘 실천하면 현재 서비스의 문제점들이 드러나게 되는데 이 드러난 `문제점들을 해결하는 것까지 마쳐야 비로소 서비스가 민첩하게 변화`할 수 있다.

### 테스트 코드의 중요성
 이 특징은 개발자 한정으로 적용될 것 같은데, 애자일을 실천하기 위해서는 테스트 코드가 더욱 중요한 것 같다. 테스트 코드는 어떤 업무 방식에서도 중요하다. 그런데 애자일 방법론에서는 특히 더 중요하다. 이는 애자일의 '빠른 피드백과 빠른 검증'이라는 특징 때문인데, 서비스가 실행되고 있는 코드를 대상으로도 빠른 수정이 필요하기 때문이다. 코드를 빠르게 수정하는 방식은 아무래도 상대적으로 안전성이 낮을 확률이 높을 것이다. 애자일이 안전성이 낮은 방식이라는 의미가 아니다. 코드를 여유롭게 수정하는 방식보다는 상대적으로 안정성이 낮다는 의미이다. `이 낮은 안정성을 보완해 줄 수 있는 것이 테스트 코드이기 때문에 애자일에서는 특히 테스트 코드가 중요`한 것 같다.

### 애자일을 실천하기 위해서는 구성원들이 뛰어나야 한다
 위에 적어둔 `애자일의 특징들을 잘 실천하고 발현시키기 위해서는 고성능(?)의 실무자들이 필요`하다. 이 세상에는 애자일을 포함해서 많은 업무 방법론이 존재할 것이다. 그리고 이 업무 방법론들이 효과적으로 작동할 수 있는 환경도 제각기 다를 것이다. 이 책에서도 비슷하게 설명하고 있는데, 애자일을 잘 실천하면 경쟁에서 우위를 점할 수 있겠지만 `매우 섬세하고 까다로운 방법론이기 때문에 실천하기가 힘들다. 과실이 크지만 따먹기가 어렵다.` 그래서 실무자들의 능력이 탁월하지 않다면 오히려 애자일을 실천하지 않는 것이 더 좋을 수 있다고 생각한다. 실무자들의 능력이 탁월하지 않은 상황에서는 오히려 강력한 탑다운 방식의 업무 방식이 더 효과를 발휘할 수 있는 것 같다. `축구에 비교`해 보자면, 선수들의 능력이 평균적으로 뛰어나면 이 능력들이 더 잘 발휘될 수 있도록 자율성을 부여하는 것이 좋겠지만 그렇지 않다면 강력한 조직력으로 선수들의 플레이를 통제하는 것이 승률을 높일 수 있을 것이다. 아무튼 애자일이 만능은 아니라는 말을 하고 싶었다.

### 작가에게 하고싶은 질문 두 가지
 45 페이지를 보면, '처음부터 애자일로 시작한 프로젝트임에도 기술적 부채가 쌓인 경우도 있다.'라고 적힌 문장이 있다. 이 부분에서 `'애자일은 기술적 부채를 쌓지 않는 방법론인가?'`라는 궁금증이 생겼다. 애자일을 잘 실천하는 조직이라도 시간이 부족하거나 순간적으로 인력이 부족하는 등 예상치 못할 `다양한 원인으로 인해 기술적인 부채를 만들게 될 수 있지 않을까?` 어느 방법론이라도 기술적인 부채를 만들려고 하진 않을 텐데? 혹시 작가는 '애자일은 기술적 부채를 쌓지 않을 확률이 낮다'라는 말을 하고 싶었던 것이 아닌가 싶다.

 

 또한 이 챕터에서는 애자일을 실천하기 위해 기술적인 뛰어남을 계속 강조한다. 그런데 시간은 한정되어 있고 기술적인 부분에만 계속 시간을 투자할 순 없을 텐데 그러면 `비즈니스는 조금 후순위로 둘 수도 있음을 전제하고 있는 걸까?`

### 생활에서 실천할 수 있는 애자일
 이렇게 애자일에 대해 깊게 고민해 보니 애자일을 실천하기 위해 생활 속에서 애자일을 실천해 보고 싶어졌다. 우선 `개발 공부를 애자일스럽게` 해봐야겠다. 내가 공부하고 있는 방향과 내용이 맞는지 타인의 시각으로 피드백을 받아보자. 그리고 고칠 건 고치고 유지할 건 유지해 보자. 개발적인 부분 말고도 생활하는 데에 많이 활용해 볼 수 있을 것 같기도 하다.
 
# 3장 소프트웨어 장인정신

### '소프트웨어 장인 정신'의 등장
 1장에서는 it 산업의 변화와 그것에 알맞은 소프트웨어 개발자의 태도를 설명했고 2장에서는 그 태도를 잘 발휘하기 위한 업무 방식인 애자일에 대해 설명했다. 애자일을 잘 실천하고 활용할 수 있으려면 업무적인 능력과 책임감이 뛰어나야 한다. 업무적인 능력과 책임감이 뛰어난 사람을 장인이라고 칭한다. 이번 장에서는 애자일을 잘 실천하고 활용할 수 있는 '소프트웨어 장인의 정의'에 대해 이야기한다.

 

 `소프트웨어 장인 정신은 간단히 말하면 프로 정신`이라고 할 수 있다. 고객(고용주)의 요구에 일정한 수준의 결과물을 만들어 내고 스스로 더 발전하고자 한다면 그 사람을 프로라고 칭할 수 있을 것이다.

### 개발자 유난과의 거리두기를 그만 둬도 될 것 같다.
 평소 개발자라고 유난(?) 떠는 것에 대해 `경계심`을 갖고 있었다. 요즘 타 직군에 비해 개발자라는 직군에 더 높은 가치가 매겨지고 있다는 느낌을 종종 받는다. 그럴 때마다 스스로에게 약간의 '개발자 후려치기'를 하고 있었다. '자만심을 갖지 말자'라는 의도도 있었고 '그래봤자 돈 벌기 위한 수단 중에 하나지 뭐'라고 냉소적으로 생각했기 때문이기도 했다. 그런데 생각해 보니 굳이 지레 `그런 생각을 할 필요까진 없었던 것` 같았다. 남을 무시하는 태도를 지양해야 하는 것이지 나의 가치를 후려칠 필요는 없었다.

 이제는 개발자라는 직군에 `자부심`을 가져보고자 한다. 개발자는 세상의 비효율을 해결하는 데에 아주 큰 기여를 할 수 있는 직군이 아닌가! 내가 실력이 뛰어난 개발자이든 그렇지 못한 개발자이든, 세상의 비효율을 해결하는 데에 참여할 수 있다는 기회가 있는 것만으로도 자부심을 가져볼만할 것 같다.

### 공장 노동자도 장인이 될 수 있을텐데?
> 소프트웨어 장인은 공장 노동자가 아니다. 적극적으로 프로젝트의 성공에 기여해야 한다. 요구사항에 질문하고, 비즈니스를 이해하고, 개선사항을 제안하며, 고객 또는 고용주와 생상적인 동반자 관계를 맺어야 한다.
 

 3장의 73p에는 위 문장이 등장한다. `이건 잘못된 말인 것 같다.` 공장 일을 해보진 않았지만, 공장 노동자도 충분히 공장 일의 성공에 적극적으로 기여할 수 있을 것 같다고 생각한다. 노동에 대한 요구사항도 적극적으로 질문하고 왜 이 노동이 필요한지 이해하고 업무 방식에 대한 개선도 제안할 수 있으며 고용주와 동반자 관계를 맺을 수 있지 않을까 싶다. 물론 현실이 이렇게 이상적이지만은 않겠지만, 공장 노동자와 고용주의 성향에 따라 충분히 적용할 수 있을 것 같다. 요즘은 공장 노동자의 공급이 너무 과잉되어 있기 때문에, 정말 뛰어난 노동자가 아닌 이상 이렇게 하긴 쉽지 않을 것 같긴 하다. 아무튼 저 문장은 바로 위에 내가 썼던 `'개발자 유난'에 해당하는 문장 같아서 태클`을 좀 걸고 싶었다.
 
### 요즘의 이력서 작성 트렌드
 요즘의 이력서에는 '어떤 문제를 해결하기 위해 최선을 다했던 경험'을 서술하라는 문항이 자주 등장한다. 이력서를 처음 쓸 때는 이 문장이 잘 이해되지 않았다. '어떤 개발을 할 줄 알고 어떤 기여를 할 수 있는지 만을 어필하면 되는 것 아닌가?'라는 생각을 하기도 했다. 하지만 이제는 이해가 된다. 이런 경험을 서술하라고 요구하는 회사들은 `장인 정신이 있는 개발자를 뽑고 싶은 것`이다. 그래서 장인 정신을 발휘했던 경험을 요구하는 것이다. 앞으로도 개발자로써 커리어를 계속 이어나가기 위해, 고객들의 위 니즈를 잘 이해하고 있으면 좋을 것 같다.
 
### 고용주를 선별하는 능력
 이 책에서는 프로정신을 갖춰야 한다고 마냥 일침만 하지는 않는다. 현실적인 내용도 서술하고 있는데, 개발자들이 본인의 직무에 대한 `프로정신을 가져야 하는 만큼 고용주를 잘 선별하는 능력도 같이 가져야 한다`고 한다. 내가 가치 있는 사람이라고 생각한다면, 부당한 대우를 받는다거나 내 가치를 활용할 수 없는 환경이라고 판단될 땐 굳이 계속 관계를 지속할 필요가 없을 것이다. 과감히 다른 회사를 찾아보자!
 
 
# 4장 소프트웨어 장인의 태도

### 커리어와 관련하여 남탓하지 말기
 내 커리어의 주인공은 나다. 내 커리어의 성장은 내 책임이다. 내 커리어는 내가 가꿔야 한다. 간혹 어떤 회사에서 일하는 것이 나에게 별로 도움이 되지 않는다는 불만이 생길 수 있다. 그러면 다른 곳으로 이직을 하면 된다. 혹은 그 회사에서 일하는 것이 나에게 도움이 되도록 고객(고용주)에게 건의를 하면 된다. 그런데 이도 저도 아니고 그저 불만만 늘어놓는 것은, 냉정한 말일 수 있겠지만, 본인은 그런 회사에 어울리는 근로자이자 장인까지는 못 되는 개발자인 것이다. 해야 할 것은 하고 요구할 것은 요구하고 아닌 것은 아니라고 말하는 책임 있는 프로의 모습이 바로 장인의 모습이다. `환경에 의존하지 말고 스스로에게 의존하자.`
 
 
### 자기 계발하기(페어 프로그래밍)
 이 책에는 '소프트웨어 장인은 끊임없이 자기 계발해야 한다'라는 내용이 나온다. 그리고 자기계발을 하는 방법을 몇 가지 소개한다. 책, 블로그, 기술 웹사이트 등을 이용할 수도 있고 트위터, 카타(다양한 환경으로 구현하고 연습해 볼 수 있는 간단한 기능을 카타라고 한다), 토이 프로젝트를 해보는 방법도 있다. 또한 페어 프로그래밍에 대한 내용도 나온다.

> 페어 프로그래밍에 대한 불편함과 두려움의 근원이 나의 한계가 드러날 수 있다는 걱정에서 온다는 것을 깨달았다.
> 물론 개발자들은 상당 수준의 지적 역량이 있기 때문에 혼자 배우고 싶다면 무엇이든 배울 수 있다.
> 문제는 시간이다. 페어 프로그래밍을 이용하면 새로운 내용을 빨리 배울 수 있다.
> 나 자신이 그렇게 훌륭하지 않을 수도 있음을 받아들여야 한다.
> 페어 프로그래밍을 할 때는 다른 사람의 생각에 마음을 여는 것이 중요하다.
> 어떤 때는 배우고, 어떤 때는 가르치고, 어떤 때는 두 가지 모두 하기도 한다.
 

평소에 '감정을 잘 조절하면 돈을 번다, 감정을 잘 조절하면 평화가 찾아온다'라고 생각하곤 한다. 그래서 위 말들이 더욱 공감됐다. 이제는 '감정을 잘 조절하면 성장할 수 있다'도 같이 떠올려야겠다. 감정이 문제인 경우가 참 많은 것 같다. `회사에서도 페어 프로그래밍을 더욱 많이 해야겠다.`

### 시간 잘 관리하기
 개발자에게는 여가시간에도 학습이 요구된다. 그래서 개발자가 `소프트웨어 장인이 되려면 시간을 잘 관리해야만 한다.` 시간은 모두에게 유한하기 때문에 시간을 잘 관리하는 것이 성공을 판가름한다. 나도 `시간을 잘 관리하려고 노력하고 있는데 이것이 참 어렵다.` 포기해야 하는 것들이 생긴다. 나도 밖에 돌아다니거나 아내와 놀러 다니고 싶은데 공부에 밀리는 경우가 일쑤다. 차라리 이 정도라면 감사하다. 회사일이 바쁜 기간에는 공부조차 못한다. 이럴 때 현타가 온다. 다른 직군과 비교해서 피곤한 직군이라는 생각이 든다. 다행인 건 회사 일만 어느 정도 괜찮다면 여가 시간에 공부하는 건 문제 될 것 같지 않다. 그나저나 1~2년 뒤 아이가 태어날 것에 대비해서도 시간 계획을 잘 세워야 할 것 같다.
