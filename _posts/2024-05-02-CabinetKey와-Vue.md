---
title: CabinetKey와 Vue
author: Jaeyeon
date: 2024-05-01 00:00:00 +0800
categories: [달달한, CabinetKey]
tags: [프론트, vue, NodeJS, CabinetKey]
render_with_liquid: false
---

# Cabinetkey(캐비닛키)

**캐비닛키를 node.js 기반의 프로젝트로 전환했습니다.** 본래 캐비닛키는 HTML, CSS, JS 만을 기반으로 Github Pages에 단순히 deploy해서 사용할 수 있도록 만들어졌습니다. 

대략 90퍼센트 이상 완성되어 있었고, 지금도 잘 쓰고 있고, 이미 사람들이 쓸 수 있도록 릴리즈까지 해 둔 상황이었어요.

![이미지](https://peachtart2.s3.ap-northeast-1.amazonaws.com/tart/thumbnail-d6407855-7ade-4a06-bbfe-c46442566c8f.webp)
_jsdelivr 의 인증서가 만료되어 모든 폰트와 모듈이 불러와지지 않았던 상황._

그러나 이번 jsdelivr 인증서 만료 사태로 인해, 제가 지금까지 이런저런 웹사이트를 개발해온 방향성이 과연 맞는 것인가, 구체적으로는 요즘 대세와, 사용자의 사용감과, 그리고 저의 성장과 연결해서 생각해 보았을 때 이 방향성이 맞는 건가 고민해보게 되었습니다.

텍스트 치환이나 파일 렌더링이나 하여튼... [영인본 생성기](https://hiyuno.peacht.art/younginbon/) 같은 단순한 물건이 아닌 이상에야 이 정도 되는 규모의 프로젝트는 뒤에 DB를 붙이지 않더라도 Node.js로 개발하고, 유저가 설치과정이나 코드를 건드리는 과정을 거치지 않도록 서버를 굴리는 것이 더 나을 거라고 생각하게 되었어요.

# Vue

노드를 거의 처음 만져보긴 하는데, 그래도 마지막으로 찔끔찔끔 만져본 것이 뷰여서 우선 뷰를 깔게 되었어요.

뷰는 처음부터 가이드를 찾아볼 필요가 없고, 처음에 주는 소스를 기반으로 약간씩 편집해나가다가 필요에 의해 문서를 읽어가며 작업하면 되어서 수월하게 진행했습니다.

# JSON 렌더링 완성

![이미지](https://peachtart2.s3.ap-northeast-1.amazonaws.com/tart/abcd1b2a-2207-4338-aef0-6fd4c35f1dca.webp)
_캐비닛키에 로그인하면 메인으로 보일 화면. 배경 사진은 없애거나 변경할 수 있습니다._

![이미지](https://peachtart2.s3.ap-northeast-1.amazonaws.com/tart/9b1d16eb-c513-463c-b1ce-3076a93d5e44.webp)
_캐릭터 세부사항 조회 페이지입니다._

# 이후 개발계획

미스키 Auth 기능으로 로그인하고, 노트를 조회하는 기능을 먼저 추가할 예정입니다.

본격적인 내용의 추가, 수정, 삭제 기능은 천천히 만들어 나갈 거예요.

이전보다 캐비닛키에 투자할 수 있는 시간이 그리 많지 않기도 하고, 모든 것을 처음부터 다시 개발하는 수준이라 목록을 새로 만들고 채워나가는 것을 감당해야만 해요.