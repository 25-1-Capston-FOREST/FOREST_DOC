## Team-Info

| 항목 | 내용 |
|:---|:---|
| **(1) 과제명** | 빠른 여가 선택을 도와주는 1:1 맞춤형 영화/공연/전시 추천 서비스 |
| **(2) 팀 번호 / 팀 이름** | 29-컴세마리 |
| **(3) 팀 구성원** | 김민수(2130005): 리더, 프론트엔드  <br> 문지현(2276108): 팀원, 백엔드 <br> 서혜지(2171019): 팀원, AI |
| **(4) 팀 지도교수** | 심재형 교수님 |
| **(5) 과제 분류** | 산학 |
| **(6) 과제 키워드** | AI, 공공 데이터, 맞춤형 여가 추천 |
| **(7) 과제 내용 요약** | 사용자의 취향을 분석하여 최적의 여가 활동을 제안하는 1:1 맞춤형 영화/공연/전시 추천 서비스입니다. 최신 영화, 공연, 전시의 다양한 정보를 한 곳에서 조회할 수 있는 기능을 제공합니다. 사용자와 챗봇 간의 대화를 통해 사용자의 취향 데이터를 수집하고, 추천 알고리즘을 통해 해당 서비스 내에서 핵심 기능인 사용자 맞춤형 여가 추천 기능을 수행합니다. 추천 알고리즘은 사용자들이 경험한 여가에 남긴 평점 데이터가 축적될수록 더욱 정교해집니다. |

## Project-Summary

| 항목 | 내용 |
|:---|:---|
| **(1) 문제 정의** | 1. 여가 정보들이 흩어져 있다 <br> 2. 여가 정보를 찾을 시간이 없다 <br> 3. 내 일정에 맞는 여가를 찾기가 어렵다 <br> 4. 여가 선택지가 많아서 결정하기 어렵다 <br> 5. 자신의 니즈에 맞는 여가를 모른다 |
| **(2) 기존 연구와의 비교** | *유사한 과제/연구/서비스/시스템의 예를 들고, 각각의 장단점을 기술할 것. 특히, 본 과제가 유사과제에 대하여 갖는 장점을 부각할 것* |
| **(3) 제안 내용** | 1. 한 번에 모아볼 수 있는 통합 플랫폼 <br> 2. 내 일정에 맞는 여가를 검색할 수 있는 서비스 <br> 3. 내 취향에 맞는 여가를 추천해주는 서비스 <br> 4. 내가 예약할만한 여가를 빠르게 추천해주는 서비스 |
| **(4) 기대효과 및 의의** | 영화/공연/전시 관람자가 증가하고 해당 산업의 규모가 확장되어, 더욱 다채로운 관람형 문화 생활을 경험할 수 있는 기회를 제공할 것입니다. 사용자의 취향에 따라 추천하기 때문에, 주류 중심의 문화 산업에서 비주류도 알려지는 기회를 제공하여 다양한 문화 형성에 기여합니다. 또한, 많은 사람들이 자신에게 맞는 여가 활동을 즐기면서 스트레스를 해소하여 삶의 질을 높이게 되고, 정신 건강 개선에 따른 사회적 비용 절감과 같은 효과도 기대할 수 있습니다. 경제적 관점에서는 영화/공연/전시 배급사와의 협력을 통해 홍보와 수수료 기반의 수익 구조를 구축함으로써 사업적 가치를 창출할 수 있습니다. |
| **(5) 주요 기능 리스트** | 1. 맞춤형 여가 추천 리스트 <br> - 영화/공연/전시 API에서 받아온 데이터 중 추천 알고리즘에 의해 선정된 여가 리스트를 반환 <br> - 카테고리별, 거리순, 리뷰순 정렬 <br> 2. 여가 통합 검색 <br> - 영화/공연/전시 API에서 받아온 데이터 중 사용자가 검색한 키워드에 해당되는 여가 리스트를 반환 <br> 3. 챗봇을 통해 취향 파악 <br> - 이전에 경험했던 여가와 좋아하는 키워드를 중심으로 대화를 통해 사용자의 취향 데이터 수집 <br> 4. 리뷰, 평점 작성 <br> - 경험한 여가에 대해 리뷰와 평점을 등록 <br> 5. 작성한 리뷰를 기반으로 취향 데이터 반영 <br> - 리뷰가 축적되며 사용자 추천 알고리즘 정교화 <br> 6. 여가 찜하기 <br> - 마음에 드는 여가를 찜하고 한 곳에서 모아볼 수 있는 기능 <br> 7. 여가 예약 등록 <br> - 예매한 여가를 한 곳에서 모아볼 수 있도록 날짜 등록 <br> 8. 소셜 로그인 <br> - 구글 캘린더 연동 <br> - 사용자의 일정을 불러와 겹치는 시간의 여가를 제외 |

## Project-Design & Implementation

| 항목 | 내용 |
|:---|:---|
| **(1) 요구사항 정의** | *프로젝트를 완성하기 위해 필요한 요구사항을 설명하기에 가장 적합한 방법을 선택하여 기술* <br> 예) <br> - 기능별 상세 요구사항(또는 유스케이스) <br> - 설계 모델(클래스 다이어그램, 클래스 및 모듈 명세서) <br> - UI 분석/설계 모델 <br> - E-R 다이어그램/DB 설계 모델(테이블 구조) |
| **(2) 전체 시스템 구성** | *프로젝트를 위하여, SW 전체 시스템의 구조를 보인다. (가능하다면, 사용자도 포함) <br> 주요 SW 모듈을 보이고, 각각의 역할을 기술한다. <br> 만약, 오픈소스 혹은 외부 모듈을 사용한다면 이 또한 기술한다.* |
| **(3) 주요 엔진 및 기능 설계** | *프로젝트의 주요 기능 혹은 모듈의 설계내용에 대하여 기술한다 <br> SW 구조 그림에 있는 각 Module의 상세 구현내용을 자세히 기술한다.* |
| **(4) 주요 기능의 구현** | *<주요 기능 리스트>에 정의된 기능 중 최소 2개 이상에 대한 상세 구현내용을 기술한다.* |
| **(5) 기타** | *기타 사항을 기술* |
