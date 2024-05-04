---
title: CabinetKey와 Vue
author: Jaeyeon
date: 2024-05-01 00:00:00 +0800
categories: [달달한, CabinetKey]
tags: [프론트, vue, NodeJS, CabinetKey]
render_with_liquid: false
---

# Cabinetkey(캐비닛키)

**캐비닛키를 node.js 기반의 프로젝트로 전환했습니다.** 본래 캐비닛키는 HTML, CSS, JS 만을 기반으로 Github Pages에 단순히 deploy해서 사용할 수 있도록 만들어졌습니다. 대략 90퍼센트 이상 완성되어 있었고, 지금도 잘 쓰고 있고, 이미 사람들이 쓸 수 있도록 릴리즈까지 해 둔 상황이었어요.

![이미지](https://peachtart2.s3.ap-northeast-1.amazonaws.com/tart/thumbnail-d6407855-7ade-4a06-bbfe-c46442566c8f.webp)
_jsdelivr 의 인증서가 만료되어 모든 폰트와 모듈이 불러와지지 않았던 상황._

그러나 이번 jsdelivr 인증서 만료 사태로 인해, 제가 지금까지 이런저런 웹사이트를 개발해온 방향성이 과연 맞는 것인가, 구체적으로는 요즘 대세와, 사용자의 사용감과, 그리고 저의 성장과 연결해서 생각해 보았을 때 이 방향성이 맞는 건가 고민해보게 되었습니다.

