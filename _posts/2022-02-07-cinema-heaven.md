---
title: Cinema Heaven
layout: post
post-image: "https://ifh.cc/g/t7w15M.png"
description: 추억을 상영하다.
tags:
- first experience
- 시작
- 백엔드 개발자
author-git-url: https://github.com/MoonKristal/jotajotajo
---

식을 줄 알았던 레트로 바람은 아직도 식지 않고 진행중입니다.
MZ세대에게는 재미와 신선함을, 중장년층에게는 추억을 소환하여 일부세대에게만 국한된 것이 아니라 전세대를 어우르고 있습니다.
본 프로젝트는 레트로를 영화의 영역으로 가져와 신선함과 추억을 가져와 이미 상영이 끝난 추억의 영화를 영화관에서 큰 화면과 서라운드한 음향으로 다시 감상할 수 있는 영화예매시스템을 제공합니다.

---


##### #기술 스택
Java / JavaScript / jQuery / Oracle / 
Servlet / Jsp / Tomcat / HTML / CSS / Bootstrap

##### #팀원
백엔드 5명

##### #담당기능
공통 - 로그인, 아이디 / 비밀번호 찾기 <br>
사용자 - 영화관 조회 <br>
관리자 - 영화관 등록, 수정, 삭제 

##### #ERD
<img src="https://ifh.cc/g/4X5ONj.jpg" width="1000px" height="500px" alt="erd">

#### #주요기능 설명
1. 비밀번호 찾기 : 아이디를 입력받아 가입된 회원인지 확인 후, 임시비밀번호를 이메일로 발송한다.<br>
<img src="https://ifh.cc/g/ctCs8S.png" width="300px" height="400px" title="px(픽셀) 크기 설정" alt="ui">
<img src="https://ifh.cc/g/y7LPNL.png" width="600px" height="600px" title="px(픽셀) 크기 설정" alt="code"><br><br>

2. 영화관 수정 : 기존의 있던 정보를 가져와 보여주고 관리자가 정보를 변경하면 변경한 정보로 업데이트한다. <br> 
<img src="https://ifh.cc/g/QVdfgn.png" width="400px" height="500px" title="px(픽셀) 크기 설정" alt="ui">
<img src="https://ifh.cc/g/ZZBFL2.jpg" width="400px" height="500px" title="px(픽셀) 크기 설정" alt="ui"><br>

* Controller <br>
<img src="https://ifh.cc/g/p58HzJ.png" width="600px" height="650px" title="px(픽셀) 크기 설정" alt="code">
<img src="https://ifh.cc/g/wqy7Kk.png" width="600px" height="650px" title="px(픽셀) 크기 설정" alt="code"><br>

* Service <br>
<img src="https://ifh.cc/g/w3ZRCa.png" width="600px" height="650px" title="px(픽셀) 크기 설정" alt="code"><br>
<img src="https://ifh.cc/g/oZ9jPK.png" width="600px" height="900px" title="px(픽셀) 크기 설정" alt="code"><br>
<img src="https://ifh.cc/g/2M42Mk.png" width="600px" height="650px" title="px(픽셀) 크기 설정" alt="code"><br><br>

3. 영화관 삭제 : 관리자가 삭제하고 싶은 영화관의 체크박스를 선택한 후, 해당 영화관을 삭제한다. (다중선택 가능) <br>
<img src="" width="300px" height="350px" title="px(픽셀) 크기 설정" alt="ui">
<img src="" width="600px" height="550px" title="px(픽셀) 크기 설정" alt="code"><br><br>


##### #후기
이번 프로젝트는 저의 첫 프로젝트이자 저에게 있어서 가장 기억에 남는 프로젝트라고 할 수 있습니다. <br>
어떻게 보면 저의 백엔드 개발자로서의 첫 발판과 같은 프로젝트이기도 합니다.<br>
논리적으로 어떤 데이터를 가져오려면 어떠한 코드를 짜야 하는지에 대해 생각하는 과정이 너무나 즐거웠습니다.<br>
이번 프로젝트는 제가 공부했던 기술들을 활용할 수 있었고 부족함을 알 수 있었던 값진 시간이었습니다.<br>

다음은 제가 프로젝트를 진행하면서 느낀것입니다.
* 사람의 생각은 결국 거기서 거기다.
이 세상에는 내가 최초로 생각할 수 있는 아이디어는 극히 드물다.
why? 이 아이디어는 너무나 참신하다 이와 같은 아이디어를 가지고 만든 프로젝트는 없겠지? 라는 생각을 가지고 구글링을 해보면 반드시 같은 생각을 한 사람을 찾을 수 있다.

* 결국 중요한 것은 나만의 차별성을 가져오는 것이다.
비슷한 주제를 가지고 프로젝트를 하는 것이면 무조건 남들과는 다른 차별성을 두어야 한다.
같은 주제를 가지고 있지만 다른 차별성을 두어 성공한 예는 우리 주변에서 쉽게 찾을 수 있다.
예를 들면, 당근마켓이 있다.
아주 오래전부터 중고판매업계의 선두 주자는 중고나라이다. 중고나라는 현재 1,800만명이상의 회원을 보유하고 있는 거대한 카페이며 당근마켓이 나오기 전까지 중고물품을 사려는 사람들은 필수적으로 중고나라에 가입했다고 해도 과언이 아닐 정도이다.
당근마켓은 이런 중고업계의 큰 바람을 일으켰다.
중고나라와 당근마켓, 모두 중고물품을 사고 팔수 있는 하나의 플랫폼이지만, 당근마켓은 지역 커뮤니티의 활성화를 기반으로 하여 중고나라와의 차별성을 두어 큰 성공을 이루어냈다.



