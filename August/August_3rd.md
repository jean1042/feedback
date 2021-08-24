---
title: "KPT Retrospective" 
date: 2021-08-17 ~ 2021-08-20 (1.8.2, 1/2)
description: "KPT Retrospective of this week"
---

## Issues this week
- [x] [Refactoring] Grafana webhook study, create grafana test dashboards and set the environment to stack raw data from grafana. I1
- [x] [Refactoring] Grafana Webhook legacy code review. I2
- [ ] [Documentation] Azure `Active Directory` documentation -> BLOCKED I3 
- [ ] [New Feature] Azure `Active Directory` modeling. I4 -> BLOCKED 
- [x] [CI/CD] Rename github plugin repositories, build latest docker images by running github actions. I5
- [x] [CI/CD] Build CI/CD pipelines for private repositories,update CI pipelines to change dockerhub repository's name as git repos. I6
- [x] [Refactoring] Grafana json raw data case study, alert & query study. I7

## KPT of issues this week
|Title|Description|
|-----|------------------|
|Keep|- K1: 인수인계처럼 업무 설명 받을 때 자료 잘 작성해서 개발 전 확실하게 개념 파악함 <br> - K2: 팀에 급하게 생긴 문제에 대응하면서 멘붕 안오고 원래 업무에도 시간분배를 잘함 <br> -K3: Learned how to refactor code from the other developer.|
|Problem|- P1: Azure new feature API scope 선분석 안해서 개발할 item인지 아닌지 개발 직전에 알아 버림. Item 변경 필요하게 됨 <br> -P2: 고질적인 기존 code refactoring(Exception처리)에 시간을 못냄|
|Try|- P1: Azure new featuers API 아이템 선조사 <br> -P2: 업무분배 시 issue IN PROGRESS로 바꾸고 cloud service 1주에 N개 확실히 할당해보기.|

## Retrospective based on Flow Theory(Csikszentmihalyi)
|Level|Description|Issue|
|-----|-------|------|
|A|난이도 > 실력|I2, I7|
|B|난이도 =\= 실력|I1, I6|
|C|난이도 < 실력|I5|

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