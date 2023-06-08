---
layout: post
title: Domain Name System
date: 2023-06-04 00:00:00 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: domain.jpg # Add image post (optional)
tags: [Productivity, Software] # add tag
---
* * *
## DNS의 개념
DNS(Domain Name System, DNS) 시스템은 인터넷에서 도메인 이름을 IP 주소로 변환하거나 그 반대의 변환을 수행 할 수 있도록 개발되었다. IP 주소는 이진수로 표시되기에 그 주소를 기억하는것은 어려운 일이다. 따라서 사용자가 기억하기 어려운 이진수 표현을 대신하여 심볼화 된 이름, 즉 '도메인 이름'을 사용하게 되었다. 'naver.com' , 'google.com' 과 같이 문자와 .으로 표현한 주소를 도메인 이름(Domain Name) 이라고 한다.

 * * *
## DNS 동작 원리
1. Local DNS Server
사용자가 가장 먼저 접근하는 DNS 서버. 
DNS 쿼리를 통해 얻은 데이터를 일정 기간 캐시로 저장해둔다.
일반적으로 KT, LG, SK 등의 ISP DNS 서버를 사용한다.
※인터넷 서비스 제공자(Internet Service Provider)



2. Root DNS Server
- ICANN(국제인터넷주소관리기구) TLD DNS 서버 IP 관리

- 인터넷상의 모든 TLD DNS 서버 IP 주소를 저장해두고 전 세계에 13개 만이 존재한다.



3. TLD DNS Server
- ICANN의 지사인 인터넷 할당 번호 관리기관(IANA)에서 관리하는 서버
-  Authoritative Name Server의 주소를 저장해둔다.



4. Authoritative DNS Server (Authoritative DNS Server )
- 실제 도메인과 IP 주소를 매칭한 정보가 저장/변경되는 서버
- 도메인 호스팅 업체, 개인 서버가 여기에 포함됨
 * * *
