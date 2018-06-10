---
layout: post
title: Retrofit2를 이용한 새주소 검색 앱 만들기 실습
subtitle: 개발자 NAS ubuntu
categories: devlog
tags: android
date: '2018-06-10 14:00:00 +0900'
published: true
---
Retrofit2를 이용한 새주소 검색 앱 만들기 실습

본 포스팅에서는 소스코드를 공개하지 않습니다.

개인 취미로 작업하는 프로젝트를 뭐를 하나 더 할까 하다가
OgameClient앱에서 사용한 retrofit2 에 더 익숙해지기 위해 뭔가 하나 얻어 골랐다.

우선 도로명주소 모바일 웹페이지 팝업이 아닌 통신을 이용한 검색 결과 주고받기를 목적으로 하므로,
도로명 주소 개발자센터에서 API 키를 발급받는다.
https://www.juso.go.kr/addrlink/devAddrLinkRequestWrite.do?returnFn=write&cntcMenu=URL

