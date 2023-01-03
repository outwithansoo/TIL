# TIL

### 프로그래머 역량 매트릭스
> 각 레벨의 지식은 누적된다는 점에 유의하십시오. n수준 에 있다는 것은 n 보다 낮은 수준 의 모든 것을 알고 있음을 의미합니다 .
> 

| 컴퓨터 과학 |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
|  | 2n(레벨 0) | n2(레벨 1) | n (레벨 2) | log(n)(레벨 3) | 코멘트 |
| 데이터 구조 | Array와 LinkedList의 차이점을 모릅니다. | 실용적인 프로그래밍 작업에서 배열, LinkedList, 사전 등을 설명하고 사용할 수 있습니다. | 기본 데이터 구조, 배열 대 LinkedLists의 공간 및 시간 트레이드오프를 알고 있습니다. 해시 테이블을 구현하는 방법과 충돌을 처리할 수 있는 방법, 우선 순위 큐 및 이를 구현하는 방법 등을 설명할 수 있습니다. | B-트리, 이항 및 피보나치 힙, AVL/레드 블랙 트리, 스플레이 트리, 건너뛰기 목록, 시도 등과 같은 고급 데이터 구조에 대한 지식 |  |
| 알고리즘 | 배열에서 숫자의 평균을 찾을 수 없습니다(믿기 어렵지만 그런 후보자를 인터뷰했습니다) | 기본 정렬, 검색 및 데이터 구조 순회 및 검색 알고리즘 | 트리, 그래프, 간단한 탐욕 및 분할 및 정복 알고리즘은 이 행렬 수준의 관련성을 이해할 수 있습니다. | 동적 프로그래밍 솔루션을 인식하고 코딩할 수 있고, 그래프 알고리즘에 대한 좋은 지식, 수치 계산 알고리즘에 대한 좋은 지식, NP 문제를 식별할 수 있는 등 |  |
| 시스템 프로그래밍 | 컴파일러, 링커 또는 인터프리터가 무엇인지 모릅니다. | 컴파일러, 링커 및 인터프리터에 대한 기본적인 이해. 어셈블리 코드가 무엇이며 하드웨어 수준에서 작동하는 방식을 이해합니다. 가상 메모리 및 페이징에 대한 약간의 지식. | 커널 모드 대 사용자 모드, 멀티스레딩, 동기화 프리미티브 및 구현 방법을 이해하고 어셈블리 코드를 읽을 수 있습니다. 네트워크 작동 방식, 네트워크 프로토콜 및 소켓 수준 프로그래밍에 대한 이해를 이해합니다. | 전체 프로그래밍 스택, 하드웨어(CPU + 메모리 + 캐시 + 인터럽트 + 마이크로코드), 바이너리 코드, 어셈블리, 정적 및 동적 링크, 컴파일, 해석, JIT 컴파일, 가비지 수집, 힙, 스택, 메모리 주소 지정… |  |
| 소프트웨어 공학 |  |  |  |  |  |
|  | 2n(레벨 0) | n2(레벨 1) | n (레벨 2) | log(n)(레벨 3) | 코멘트 |
| 소스 코드 버전 제어 | 날짜별 폴더 백업 | VSS 및 시작 CVS/SVN 사용자 | CVS 및 SVN 기능 사용에 능숙합니다. 분기 및 병합 방법, 패치 설정 저장소 속성 등을 사용하는 방법을 알고 있습니다. | 분산 VCS 시스템에 대한 지식. Bzr/Mercurial/Darcs/Git을 사용해 보았습니다. |  |
| 빌드 자동화 | IDE에서 빌드하는 방법만 알고 있음 | 명령줄에서 시스템을 구축하는 방법을 알고 있습니다. | 기본 시스템 구축을 위한 스크립트 설정 가능 | 시스템 및 설명서, 설치 프로그램을 빌드하고 릴리스 정보를 생성하고 소스 제어에서 코드에 태그를 지정하는 스크립트를 설정할 수 있습니다. |  |
| 자동화된 테스트 | 모든 테스트는 테스터의 일이라고 생각합니다. | 자동화된 단위 테스트를 작성했으며 작성 중인 코드에 대한 좋은 단위 테스트 사례를 제공합니다. | TDD 방식으로 코드를 작성했습니다. | 자동화된 기능, 로드/성능 및 UI 테스트를 이해하고 설정할 수 있습니다. |  |
| 프로그램 작성 |  |  |  |  |  |
|  | 2n(레벨 0) | n2(레벨 1) | n (레벨 2) | log(n)(레벨 3) | 코멘트 |
| 문제 분해 | 재사용을 위해 복사 붙여넣기가 있는 직선 코드만 | 문제를 여러 기능으로 분해할 수 있음 | 전반적인 문제를 해결하는 재사용 가능한 기능/객체를 제시할 수 있습니다. | 적절한 데이터 구조 및 알고리즘을 사용하고 변경될 수 있는 문제의 측면을 캡슐화하는 일반/객체 지향 코드를 제시합니다. |  |
| 시스템 분해 | 단일 파일/클래스 수준 이상으로 생각할 수 없음 | 동일한 플랫폼/기술 내에 있는 한 문제 공간과 설계 솔루션을 분할할 수 있습니다. | 여러 기술/플랫폼에 걸친 시스템을 설계할 수 있습니다. | 여러 제품 라인 및 외부 시스템과의 통합으로 복잡한 시스템을 시각화하고 설계할 수 있습니다. 또한 모니터링, 보고, 장애 조치 등과 같은 운영 지원 시스템을 설계할 수 있어야 합니다. |  |
| 의사소통 | 동료에게 생각/아이디어를 표현할 수 없습니다. 잘못된 철자와 문법. | 동료들은 말하는 내용을 이해할 수 있습니다. 철자와 문법이 좋습니다. | 동료들과 효과적으로 의사소통할 수 있다 | 생각/디자인/아이디어/사양을 명확하게 이해하고 전달할 수 있으며 상황에 따라 커뮤니케이션을 조정할 수 있습니다. | 이것은 종종 과소 평가되지만 프로그래머를 판단하는 매우 중요한 기준입니다. 영어가 모국어가 아닌 곳으로 프로그래밍 작업을 아웃소싱하는 것이 증가함에 따라 이 문제는 더욱 두드러졌습니다. 프로그래머가 커뮤니케이션의 의도를 이해할 수 없었기 때문에 실패한 여러 프로젝트를 알고 있습니다. |
| 파일 내의 코드 구성 | 파일 내 조직의 증거 없음 | 메서드는 논리적으로 또는 접근성별로 그룹화됩니다. | 코드는 영역으로 그룹화되며 다른 소스 파일에 대한 참조로 잘 설명되어 있습니다. | 파일에는 라이센스 헤더, 요약, 주석이 잘 달려 있고 일관된 공백 사용이 있습니다. 파일이 아름답게 보일 것입니다. |  |
| 파일 간 코드 구성 | 파일 간 코드 구성에 대한 생각 없음 | 관련 파일은 폴더로 그룹화됩니다. | 각 실제 파일에는 하나의 클래스 정의, 하나의 기능 구현 등과 같은 고유한 용도가 있습니다. | 물리적 수준의 코드 구성은 디자인과 밀접하게 일치하며 파일 이름 및 폴더 분포를 보면 디자인에 대한 통찰력을 제공합니다. |  |
| 소스 트리 구성 | 하나의 폴더에 모든 것 | 코드를 논리 폴더로 기본 분리합니다. | 순환 종속성, 바이너리, 라이브러리, 문서, 빌드, 타사 코드가 모두 적절한 폴더에 정리되지 않음 | 소스 트리의 물리적 레이아웃은 논리적 계층 및 조직과 일치합니다. 디렉토리 이름과 조직은 시스템 설계에 대한 통찰력을 제공합니다. | 이 항목과 이전 항목의 차이점은 구성 규모에 있으며 소스 트리 구성은 시스템을 정의하는 전체 아티팩트 집합과 관련됩니다. |
| 코드 가독성 | 단음절 이름 | 파일, 변수 클래스, 메서드 등에 대한 좋은 이름입니다. | 긴 함수, 비정상적인 코드를 설명하는 주석, 버그 수정, 코드 가정 없음 | 코드 가정은 어설션을 사용하여 검증되며 코드 흐름은 자연스럽게 진행됩니다. 조건문이나 메서드가 깊게 중첩되지 않습니다. |  |
| 방어적 코딩 | 개념을 이해하지 못한다 | 모든 인수를 확인하고 코드에서 중요한 가정을 주장합니다. | 반환 값을 확인하고 실패할 수 있는 코드 주변의 예외를 확인합니다. | 방어 코딩에 도움이 되는 자체 라이브러리가 있으며 결함을 시뮬레이트하는 단위 테스트를 작성합니다. |  |
| 오류 처리 | 해피 케이스만 코딩 | 예외를 발생시키거나 오류를 생성할 수 있는 코드 주변의 기본 오류 처리 | 오류/예외로 인해 프로그램이 양호한 상태로 유지되고 리소스, 연결 및 메모리가 모두 적절하게 정리되도록 합니다. | 가능한 예외를 사전에 감지하는 코드, 코드의 모든 계층에서 일관된 예외 처리 전략을 유지하고 전체 시스템에 대한 예외 처리에 대한 지침을 제공합니다. |  |
| IDE | 주로 텍스트 편집을 위해 IDE를 사용합니다. | 메뉴를 사용하여 IDE를 효과적으로 사용할 수 있는 인터페이스 사용 방법을 알고 있습니다. | 가장 많이 사용되는 작업에 대한 키보드 단축키를 알고 있습니다. | 맞춤 매크로를 작성했습니다. |  |
| API | 문서를 자주 찾아봐야 함 | 가장 자주 사용되는 API를 메모리에 보유 | API에 대한 방대하고 심층적인 지식 | 자주 사용하는 작업을 단순화하고 API의 공백을 메우기 위해 API 위에 있는 작성된 라이브러리가 있습니다. | 예를 들어 API는 Java 라이브러리, .net 프레임워크 또는 애플리케이션용 사용자 지정 API일 수 있습니다. |
| 프레임워크 | 핵심 플랫폼 외부의 프레임워크를 사용하지 않았습니다. | 플랫폼에서 사용할 수 있는 인기 있는 프레임워크에 대해 들었지만 사용하지는 않았습니다. | 전문적인 능력으로 하나 이상의 프레임워크를 사용했으며 프레임워크의 관용구에 정통합니다. | 프레임워크 작성자 |  |
| 요구 사항 | 주어진 요구 사항 및 코드를 사양으로 가져옵니다. | 사양에서 누락된 사례에 대한 질문을 제시합니다. | 전체 그림을 이해하고 지정해야 하는 전체 영역을 제시합니다. | 경험을 바탕으로 주어진 요구 사항에 대한 더 나은 대안 및 흐름을 제안할 수 있습니다. |  |
| 스크립팅 | 스크립팅 도구에 대한 지식 없음 | 배치 파일/쉘 스크립트 | 펄/파이썬/루비/VBScript/파워쉘 | 재사용 가능한 코드 작성 및 게시 |  |
| 데이터 베이스 | Excel이 데이터베이스라고 생각 | 기본 데이터베이스 개념, 정규화, ACID, 트랜잭션을 알고 간단한 선택을 작성할 수 있습니다. | 실행해야 할 쿼리를 염두에 두고 훌륭하고 정규화된 데이터베이스 스키마를 설계할 수 있고 뷰, 저장 프로시저, 트리거 및 사용자 정의 유형을 능숙하게 사용할 수 있습니다. 클러스터형 인덱스와 비클러스터형 인덱스의 차이점을 알고 있습니다. ORM 도구 사용에 능숙합니다. | 기본 데이터베이스 관리, 성능 최적화, 인덱스 최적화, 고급 선택 쿼리 작성, 커서 사용을 관계형 SQL로 대체할 수 있음, 데이터가 내부적으로 저장되는 방식 이해, 인덱스가 내부적으로 저장되는 방식 이해, 데이터베이스 미러링, 복제 등을 수행할 수 있는 방법 이해 2단계 커밋이 작동하는 방식을 이해합니다. |  |
| 경험 |  |  |  |  |  |
|  | 2n(레벨 0) | n2(레벨 1) | n (레벨 2) | log(n)(레벨 3) | 코멘트 |
| 전문적인 경험을 가진 언어 | 명령형 또는 객체 지향 | 명령형, 객체 지향 및 선언적(SQL), 정적 유형 대 동적 유형, 약한 유형 대 강력한 유형 및 정적 유추 유형을 이해하는 경우 추가 보너스 | 게으른 평가, 커링, 컨티뉴에이션을 이해하는 경우 기능적 추가 보너스 | 동시(Erlang, Oz) 및 논리(Prolog) |  |
| 전문적인 경험을 가진 플랫폼 | 1 | 2-3 | 4-5 | 6+ |  |
| 수년간의 전문적인 경험 | 1 | 2-5 | 6-9 | 10+ |  |
| 도메인 지식 | 도메인에 대한 지식 없음 | 도메인에서 하나 이상의 제품에 대해 작업했습니다. | 동일한 도메인에서 여러 제품을 작업했습니다. | 도메인 전문가. 도메인에서 여러 제품/솔루션을 설계하고 구현했습니다. 표준 용어, 도메인에서 사용되는 프로토콜에 정통합니다. |  |
| 지식 |  |  |  |  |  |
| 도구 지식 | 기본 IDE로 제한됨(VS.Net, Eclipse 등) | 널리 사용되는 표준 도구에 대한 몇 가지 대안에 대해 알고 있습니다. | 편집기, 디버거, IDE, 오픈 소스 대안 등에 대한 좋은 지식. 예를 들어 Scott Hanselman의 강력한 도구 목록에 있는 대부분의 도구를 아는 사람. ORM 도구를 사용했습니다. | 실제로 도구와 스크립트를 작성했으며 게시된 경우 보너스를 추가했습니다. |  |
| 노출된 언어 | 명령형 또는 객체 지향 | 명령형, 객체 지향 및 선언적(SQL), 정적 유형 대 동적 유형, 약한 유형 대 강력한 유형 및 정적 유추 유형을 이해하는 경우 추가 보너스 | 게으른 평가, 커링, 컨티뉴에이션을 이해하는 경우 기능적 추가 보너스 | 동시(Erlang, Oz) 및 논리(Prolog) |  |
| 코드베이스 지식 | 코드베이스를 본 적이 없음 | 코드 레이아웃 및 시스템 구축 방법에 대한 기본 지식 | 코드 베이스에 대한 훌륭한 작업 지식, 몇 가지 버그 수정 및 일부 작은 기능을 구현했습니다. | 코드베이스에 여러 가지 큰 기능을 구현했으며 대부분의 기능 또는 버그 수정에 필요한 변경 사항을 쉽게 시각화할 수 있습니다. |  |
| 다가오는 기술에 대한 지식 | 다가오는 기술에 대해 들어 본 적이 없습니다. | 해당 분야의 향후 기술에 대해 들었습니다. | 알파 프리뷰/CTP/베타를 다운로드하고 일부 기사/매뉴얼을 읽었습니다. | 프리뷰를 가지고 놀았고 실제로 그것으로 무언가를 만들었고 보너스로 그것을 다른 모든 사람들과 공유했습니다. |  |
| 플랫폼 내부 | 플랫폼 내부 지식 제로 | 플랫폼이 내부적으로 작동하는 방식에 대한 기본 지식 보유 | 플랫폼 내부에 대한 깊은 지식과 플랫폼이 프로그램을 실행 가능한 코드로 변환하는 방법을 시각화할 수 있습니다. | 플랫폼 내부에 대한 정보를 향상하거나 제공하는 서면 도구가 있습니다. 예를 들어 디스어셈블러, 디컴파일러, 디버거 등 |  |
| 서적 | 해방 시리즈, 21일 시리즈, 24시간 시리즈, 인형 시리즈… | 코드 완성, 생각하게 만들지 마세요, 정규식 마스터하기 | 디자인 패턴, 피플웨어, 프로그래밍 펄, 알고리즘 디자인 매뉴얼, 실용 프로그래머, Mythical Manmonth | 컴퓨터 프로그램의 구조와 해석, 개념 기술, 컴퓨터 프로그래밍 모델, 컴퓨터 프로그래밍 기술, 데이터베이스 시스템, by C. J Date, Thinking Forth, Little Schemer |  |
| 블로그 | 그들에 대해 들었지만 시간이 없었습니다. | 기술/프로그래밍/소프트웨어 엔지니어링 블로그를 읽고 정기적으로 팟캐스트를 듣습니다. | 자신이 수집한 유용한 기사 및 도구 모음이 포함된 링크 블로그를 유지합니다. | 프로그래밍에 대한 개인적인 통찰력과 생각을 공유하는 블로그를 유지합니다. |  |
