---
title: MAIN
type: docs
---

# KR LEGAL DONG

## 소개

대한민국 법정동 데이터 및 API를 제공합니다.


## 구현 방식

[행정표준코드관리시스템](https://www.code.go.kr/stdcode/regCodeL.do) 에서 제공하는 데이터를 [kr-legal-dong-scraper](https://github.com/kr-legal-dong/kr-legal-dong-scraper) 를 통해 수집합니다.

최종적으로 [kr-legal-dong](https://github.com/kr-legal-dong/kr-legal-dong) 리포지토리에 저장됩니다.

수집 주기는 매달 짝수일 0시 0분 (0 0 */2 * *) 입니다.


## 제공 방식

JSON, HTTP API 로 제공합니다. 