## Holla Project

[데모 영상]

### [팀명] : Holla (홀라)

- 오디오북 구매 서비스 윌라(https://www.welaaa.com/) 클론 프로젝트
- 짧은 프로젝트 기간동안 개발에 집중해야 하므로 디자인/기획 부분만 클론했습니다.
- 개발은 초기 세팅부터 전부 직접 구현했으며, 위 데모 영상에서 보이는 부분은 모두 백앤드와 연결하여 실제 사용할 수 있는 서비스 수준으로 개발한 것입니다.

### 개발 인원 및 기간

- 개발기간 : 2021/11/15~2021/11/26
- 개발 인원 : 프론트엔드 4명, 백엔드 2명
- 팀원 : 김봉철, 유병문, 설혜린, 이수경, 장세영, 정지후

### 프로젝트 선정이유

- 기본적인 이커머스 사이트에 필요한 핵심 기능들을 구현해 볼 수 있어서 선택하게 되었습니다.

<br>

## 적용 기술 및 구현 기능

### 적용 기술 및 협업 툴

> - Front-End : JavaScript, React.js, sass, React-router-dom, React-icons
> - Back-End : Django, Python, MySQL, jwt, AWS(EC2, RDS)
> - Common : Git, Github, Slack, Trello

### 구현 기능

#### 필수 기능 구현 목록

1. Navbar - 햄버거 Nav 기능 구현, 메뉴바 기능 구현, 장바구니 기능 구현
2. 메인 페이지 (오디오북) - 슬라이드 기능 구현
3. 상세 페이지 - 별점 및 댓글 기능 구현
4. 로그인 , 회원가입 페이지 - 소셜 로그인 기능 구현


#### 담당한 페이지 목록 및 설명

##### [상세 페이지]

- mockdata 파일 생성 후 상세 페이지 정보 화면 구현
- 오디오북 및 작가 소개 컴포넌트화
- ref를 이용하여 modal 창 외부영역 클릭 시 모달창에서 빠져나가는 기능 구현
- 메인 페이지에서 받은 id 값을 Path Parameter를 이용하여 장바구니 화면 이동 시 id 값을 함께 넘기는 기능 구현
- fetch 의 headers의 token을 통해 로그인으로 인증된 유저만 장바구니 페이지 이동, 별점 및 댓글을 작성할 수 있도록 기능 구현
- 서버와 POST/GET/DELETE 방식으로 API 통신하여 오디오북 정보, 별점과 댓글 정보를 가져오고 페이지 이동, 별점 및 댓글을 작성 및 삭제하는 기능 구현

<br>

_아래 Reference 부분은 README.md에 꼭 포함되어야 하는 내용입니다_

## Reference
- 이 프로젝트는 [윌라](https://www.welaaa.com/) 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
- 이 프로젝트에서 사용하고 있는 사진 대부분은 위코드에서 구매한 것이므로 해당 프로젝트 외부인이 사용할 수 없습니다.
