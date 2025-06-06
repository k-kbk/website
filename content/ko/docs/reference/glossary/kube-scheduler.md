---
title: kube-scheduler
id: kube-scheduler
date: 2018-04-12
full_link: /docs/reference/command-line-tools-reference/kube-scheduler/
short_description: >
  노드가 배정되지 않은 새로 생성된 파드를 감지하고, 해당 파드를 실행할 노드를 선택하는 컨트롤 플레인 컴포넌트.

aka: 
tags:
- architecture
---
kube-scheduler는 {{< glossary_tooltip term_id="node" text="노드" >}}가 배정되지 않은 새로 생성된 {{< glossary_tooltip term_id="pod" text="파드" >}}를 감지하고, 해당 파드를 실행할 적절한 노드를 선택하는 컨트롤 플레인 컴포넌트이다.

<!--more--> 

스케줄링을 결정하기 위해서는 리소스에 대한 개별 및 총체적 요구 사항, 하드웨어/소프트웨어/정책적 제약, 어피니티(affinity) 및 안티-어피니티(anti-affinity) 명세, 데이터 지역성, 워크로드 간 간섭, 데드라인이 고려된다.
