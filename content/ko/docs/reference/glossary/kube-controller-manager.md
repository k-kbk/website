---
title: kube-controller-manager
id: kube-controller-manager
date: 2018-04-12
full_link: /docs/reference/command-line-tools-reference/kube-controller-manager/
short_description: >
  컨트롤러 프로세스를 실행하는 컨트롤 플레인 컴포넌트.

aka:
tags:
- architecture
- fundamental
---
kube-controller-manager는 {{< glossary_tooltip text="컨트롤러" term_id="controller" >}} 프로세스를 실행하는 컨트롤 플레인 컴포넌트이다.

<!--more-->

논리적으로 각 {{< glossary_tooltip text="컨트롤러" term_id="controller" >}}는 분리된 프로세스이지만, 복잡성을 낮추기 위해 하나의 바이너리로 컴파일되어 단일 프로세스 내에서 함께 실행된다.
