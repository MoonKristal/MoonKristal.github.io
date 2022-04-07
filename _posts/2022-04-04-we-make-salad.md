---
title: We Make Salad 위메샐
layout: post
post-image: https://ifh.cc/g/hJsRNQ.png
description: Customize Your Salad.
tags:
- Spring Framework
- 백엔드 개발자
- 파이널 프로젝트
- 준비 끝
author-git-url: https://github.com/MoonKristal/SOSOBUTSTRONG
---

> 코로나 시국에 배달 음식에 길들여져 있는 입맛을 나만의 DIY 샐러드를 통해 건강을 개선하는 계기를 제공하며 나만의 샐러드 레시피를 다른 사용자와 공유할 수 있는 공간을 제공합니다. 사용자는 샐러드 구매 또는 판매 서비스를 이용할 수 있는 플랫폼을 제공받습니다.&emsp;&emsp;&emsp;

---

##### #기술 스택
Java / Spring Framework / MyBatis / JavaScript / jQuery / Oracle / Jsp / Tomcat / HTML / CSS / Bootstrap / Github

##### #팀원
백엔드 5명

##### #담당기능
공통 - 메인페이지, 커뮤니티(레시피 공유) 게시판 조회 <br>
판매자, 구매자 - 커뮤니티 게시판 등록, 수정, 삭제, 신고, 좋아요, 댓글 작성, 댓글 신고 <br>
관리자 - 메인페이지 사진 등록, 신고처리 <br>

##### #ERD
<img src="https://ifh.cc/g/pWGcsg.jpg" width="1000px" height="500px" alt="erd">

##### #주요기능
1. 게시글 상세정보 조회 : 사용자가 등록한 게시글을 조회할 수 있다.<br>
<img src="https://ifh.cc/g/mLdc2D.jpg" width="400px" height="600px" alt="ui">
<img src="https://ifh.cc/g/Kojw0Q.png" width="800px" height="700px" alt="code"><br><br>
2. 좋아요 : 다른 사용자가 공유한 게시글의 좋아요를 표시할 수 있다.<br>
<img src="https://ifh.cc/g/CNt82A.jpg" style="width: 400px; height: 600px;" alt="ui"><br>
    - JSP <br>
<img src="https://ifh.cc/g/PknCLt.png" style="width: 1200px; height: 200px;" alt="code"><br>
    - jQuery <br>
<img src="https://ifh.cc/g/oqN7HQ.png" style="width: 500px; height: 300px;"  alt="code"><br>
    - Controller <br>
<img src="https://ifh.cc/g/xnFoNW.png" style="width: 1200px; height: 350px;" alt="code"><br>
    - jQuery <br>
<img src="https://ifh.cc/g/q0XODX.png" style="width: 700px; height: 350px;" alt="code"><br><br>
3. 신고 : 게시글 또는 게시글에 달린 댓글을 사용자가 신고할 수 있다. <br>
<img src="https://ifh.cc/g/VYZFNP.png" style="width: 400px; height: 400px;" alt="ui"><br>
    - JSP <br>
<img src="https://ifh.cc/g/AZtdHW.png" style="width: 1200px; height: 450px;" alt="code"><br>
    - Controller <br>
<img src="https://ifh.cc/g/ZVW1P1.png" style="width: 600px; height: 300px;" alt="code"><br>
4. 신고처리 : 신고가 들어온 게시글 또는 댓글을 관리자가 삭제 또는 반려처리할 수 있다. <br>
<img src="https://ifh.cc/g/zFlvcM.png" style="width: 700px; height: 300px;" alt="ui"><br>
<img src="https://ifh.cc/g/QJS2yp.png" style="width: 500px; height: 800px;" alt="ui"><br>
    - SQL문 : 삭제할 경우 STATUS를 D로, 반려할 경우 R로 변경한 후, 처리상태(COMPLETION)를 N에서 Y로 변경한다. <br>
    (report_rep, user_no, report_com을 복합키로 두고 게시글 신고 처리를 할때는 report_rep를 기본값(0)으로 준다. 여기서 report_rep = 0인 댓글은 참조를 위해 더미데이터로 관리자가 넣어둠)<br>
<img src="https://ifh.cc/g/yPfz3t.png" style="width: 850px; height: 500px;" alt="code"><br>

##### #후기
6개월 전 시작한 국비교육이 이번 파이널 프로젝트와 함께 끝이 났다. 
이번 프로젝트에서 팀장을 맡아, 전체적인 일정을 짜는 방법과 팀원들 간의 의견을 조율하는 방법을 배울 수 있었다.
프로젝트를 하면서 나태해지는 순간들이 있었지만 같은 팀원들의 열정 있는 모습이 나를 다시 일깨워줬다.
아무것도 모르는 채로 시작한 내가 작은 프로젝트들을 하면서 하나둘씩 감을 잡아가며 하나의 웹페이지들을 만든 게 실감이 잘 나지 않는다.
하지만 앞으로 배울 많은 것들이 더욱 기다려지며 그 배운 것들을 활용해 새로운 무언가를 만들어낼 내가 기대된다. 




