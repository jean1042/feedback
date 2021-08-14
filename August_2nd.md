---
title: "KPT Retrospective" 
date: 2021-08-09 ~ 2021-08-14
description: "KPT Retrospective of this week"
---

## Issues this week
- [x] [New Feature] Azure cloud services `storage account` modeling. I1
- [x] [Deployment] Deploy `storage account` feature. I2
- [x] [New Feature] Finish `Telegram Bot` development. I3
- [x] [Deployment] Deploy `Telegram Bot plugin` to K8S cluster as a pod. I4
- [ ] [QA] Azure cloud services `storage account` integration test I5
- [x] [Documentation] Write user guide of Telegram feature and integrate to Hugo I6 docs system.

## KPT of issues this week
|Title|Description|
|-----|------------------|
|Keep|- K1: minikube로 구동되는 local cluster 구축 후 integration test 시도해봄 |
|Problem|- P1: Azure가 제공해주는 API에서 storage account 기능에 대한 이해 없이 Copy&Paste에 기반한 모델링(1) <br> - P2: 개발하는 기능의 Secret / Channel / Protocol 개념 이해 부족 (2)<br> - P3: Sprint마감에 쫓겨 개발하는 등 시간분배 실패|
|Try|- P1: Modeling 전에 documentation 먼저 하기 (Documentation을 통해 C영역의 bored -> B영역으로 끌어올리는 과정이 필요함) <br> - P3: Sprint 시작 전에 TODO list 미리 정하기<br> - K1: minikube cluster에 plugin 설치도 해보기<br>|

## Retrospective based on Flow Theory(Csikszentmihalyi)
|Level|Description|Issue|
|-----|-------|------|
|A|난이도 > 실력|K1|
|B|난이도 =\= 실력|I3, I4, I6|
|C|난이도 < 실력|I1, I2|

### What is Flow Theory by Csikszentmihalyi?
몰입(flow)이란 무언가에 흠뻑 빠져 심취해 있는 무아지경의 상태를 말한다. 
![image](https://user-images.githubusercontent.com/25656426/129442292-ba926ff9-1886-4434-b432-c6c4f091bb6a.png)


### What is KPT?
- Keep, Problem, Try 세 부분으로 나눈다.
- **Keep**
좋았던 점을 기반으로 도출되며 앞으로 프로젝트를 진행할 때, 계속 유지해야할 사항
- **Problem**
아쉬웠던 점을 기반으로 도출되며 앞으로 프로젝트를 진행할 때, 개선되어야 할 사항.
일어난 사건 자체 뿐만 아니라 좋았거나 나빴던 일에 이르는 과정에 대해 쓰는 것이 좋다.
- **Try**
도출된 problem의 원인을 파악하여 이를 기반으로 어떠한 시도들을 해볼 수 있는지에 대한 내용.
Try을 고려할 때 포인트는 구체적인 액션에까지 구체화 시키는 것이 중요

## Any Feedback in comments! 😊