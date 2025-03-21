# 🌱 스프링 DB 2편 - 데이터 접근 활용 기술

이 리포지토리는 인프런에서 제공하는 김영한 님의 "스프링 DB 2편 - 데이터 접근 활용 기술" 강의를 학습하고 실습하는 공간입니다.

## 📚 강의 개요
- 강사: 김영한
- 플랫폼: 인프런
- 주제: 스프링 데이터 접근 기술과 트랜잭션

## 🎯 학습 목표
- 다양한 데이터 접근 기술(JdbcTemplate, MyBatis, JPA, 스프링 데이터 JPA, Querydsl) 이해하기
- 각 기술의 장단점과 실무 활용 방안 학습
- 스프링 트랜잭션의 동작 원리와 전파 속성 이해하기
- 테스트 DB 구성 및 데이터베이스 연동 테스트 방법 습득
- 실무에 적합한 데이터 접근 계층 설계 방법 익히기

## 📋 커리큘럼 및 학습 진행 상황
### 섹션 1: 강의 소개
- [x] 강의 소개
- [x] 수업 자료
- [x] 강의 소스 코드
- [x] PPT 자료

### 섹션 2: 데이터 접근 기술 - 시작
- [x] 데이터 접근 기술 진행 방식 소개
- [x] 프로젝트 설정과 메모리 저장소
- [x] 프로젝트 구조 설명1 - 기본
- [x] 프로젝트 구조 설명2 - 설정
- [x] 프로젝트 구조 설명3 - 테스트
- [x] 데이터베이스 테이블 생성
- [x] 정리

### 섹션 3: 데이터 접근 기술 - 스프링 JdbcTemplate
- [x] JdbcTemplate 소개와 설정
- [x] JdbcTemplate 적용1 - 기본
- [x] JdbcTemplate 적용2 - 동적 쿼리 문제
- [x] JdbcTemplate 적용3 - 구성과 실행
- [x] JdbcTemplate - 이름 지정 파라미터 1
- [ ] JdbcTemplate - 이름 지정 파라미터 2
- [ ] JdbcTemplate - 이름 지정 파라미터 3
- [ ] JdbcTemplate - SimpleJdbcInsert
- [ ] JdbcTemplate 기능 정리
- [ ] 정리

### 섹션 4: 데이터 접근 기술 - 테스트
- [ ] 테스트 - 데이터베이스 연동
- [ ] 테스트 - 데이터베이스 분리
- [ ] 테스트 - 데이터 롤백
- [ ] 테스트 - @Transactional
- [ ] 테스트 - 임베디드 모드 DB
- [ ] 테스트 - 스프링 부트와 임베디드 모드
- [ ] 정리

### 섹션 5: 데이터 접근 기술 - MyBatis
- [ ] MyBatis 소개
- [ ] MyBatis 설정
- [ ] MyBatis 적용1 - 기본
- [ ] MyBatis 적용2 - 설정과 실행
- [ ] MyBatis 적용3 - 분석
- [ ] MyBatis 기능 정리1 - 동적 쿼리
- [ ] MyBatis 기능 정리2 - 기타 기능
- [ ] 정리

### 섹션 6: 데이터 접근 기술 - JPA
- [ ] JPA 시작
- [ ] ORM 개념1 - SQL 중심적인 개발의 문제점
- [ ] ORM 개념2 - JPA 소개
- [ ] JPA 설정
- [ ] JPA 적용1 - 개발
- [ ] JPA 적용2 - 리포지토리 분석
- [ ] JPA 적용3 - 예외 변환
- [ ] 정리

### 섹션 7: 데이터 접근 기술 - 스프링 데이터 JPA
- [ ] 스프링 데이터 JPA 소개1 - 등장 이유
- [ ] 스프링 데이터 JPA 소개2 - 기능
- [ ] 스프링 데이터 JPA 주요 기능
- [ ] 스프링 데이터 JPA 적용1
- [ ] 스프링 데이터 JPA 적용2
- [ ] 정리

### 섹션 8: 데이터 접근 기술 - Querydsl
- [ ] Querydsl 소개1 - 기존 방식의 문제점
- [ ] Querydsl 소개2 - 해결
- [ ] Querydsl 설정
- [ ] Querydsl 적용
- [ ] 정리

### 섹션 9: 데이터 접근 기술 - 활용 방안
- [ ] 스프링 데이터 JPA 예제와 트레이드 오프
- [ ] 실용적인 구조
- [ ] 다양한 데이터 접근 기술 조합
- [ ] 정리

### 섹션 10: 스프링 트랜잭션 이해
- [ ] 스프링 트랜잭션 소개
- [ ] 프로젝트 생성
- [ ] 트랜잭션 적용 확인
- [ ] 트랜잭션 적용 위치
- [ ] 트랜잭션 AOP 주의 사항 - 프록시 내부 호출1
- [ ] 트랜잭션 AOP 주의 사항 - 프록시 내부 호출2
- [ ] 트랜잭션 AOP 주의 사항 - 초기화 시점
- [ ] 트랜잭션 옵션 소개
- [ ] 예외와 트랜잭션 커밋, 롤백 - 기본
- [ ] 예외와 트랜잭션 커밋, 롤백 - 활용
- [ ] 정리

### 섹션 11: 스프링 트랜잭션 전파1 - 기본
- [ ] 스프링 트랜잭션 전파1 - 커밋, 롤백
- [ ] 스프링 트랜잭션 전파2 - 트랜잭션 두 번 사용
- [ ] 스프링 트랜잭션 전파3 - 전파 기본
- [ ] 스프링 트랜잭션 전파4 - 전파 예제
- [ ] 스프링 트랜잭션 전파5 - 외부 롤백
- [ ] 스프링 트랜잭션 전파6 - 내부 롤백
- [ ] 스프링 트랜잭션 전파7 - REQUIRES_NEW
- [ ] 스프링 트랜잭션 전파8 - 다양한 전파 옵션
- [ ] 정리

### 섹션 12: 스프링 트랜잭션 전파2 - 활용
- [ ] 트랜잭션 전파 활용1 - 예제 프로젝트 시작
- [ ] 트랜잭션 전파 활용2 - 커밋, 롤백
- [ ] 트랜잭션 전파 활용3 - 단일 트랜잭션
- [ ] 트랜잭션 전파 활용4 - 전파 커밋
- [ ] 트랜잭션 전파 활용5 - 전파 롤백
- [ ] 트랜잭션 전파 활용6 - 복구 REQUIRED
- [ ] 트랜잭션 전파 활용7 - 복구 REQUIRES_NEW
- [ ] 정리

### 섹션 13: 다음으로
- [ ] 다음으로

## 💻 주요 실습 프로젝트
- [ ] 다양한 데이터 접근 기술 적용 및 비교
- [ ] 스프링 JdbcTemplate을 활용한 데이터 접근 구현
- [ ] MyBatis를 활용한 SQL 매핑
- [ ] JPA와 ORM을 활용한 객체 중심 데이터 접근
- [ ] 스프링 데이터 JPA와 Querydsl 활용
- [ ] 스프링 트랜잭션 동작 원리와 전파 속성 실습

## 🔗 링크
- [스프링 DB 2편 강의 링크](https://www.inflearn.com/course/스프링-db-2)

## ⚠️ 주의사항
이 리포지토리의 코드는 학습 목적으로 작성되었으며, 실제 프로덕션 환경에서는 추가적인 고려사항이 필요할 수 있습니다.

## 📌 Commit 메시지 규칙
```
[섹션번호] 주제: 상세 내용
- 학습한 주요 개념
- 실습한 내용
- 특이사항 또는 주의점
```

예시:
```
[섹션3] JdbcTemplate 활용: 기본 CRUD 구현
- JdbcTemplate 기본 개념 이해
- 이름 지정 파라미터 방식 적용
- SimpleJdbcInsert를 통한 등록 기능 구현
- 동적 쿼리 문제 해결 방법 학습
```

## 📅 학습 일지
| 날짜         | 학습 내용                  | 비고                                   |
|------------|------------------------|--------------------------------------|
| 2025-03-14 | 리포지토리 생성 및 학습 계획 수립    | 스프링 DB 2편 학습 시작!                    |
| 2025-03-14 | 섹션 1, 2 진행 중          | 강의 소개 및 프로젝트 기본 구조 이해              |

🌱 다양한 데이터 접근 기술을 비교하고, 실무에 적합한 활용 방안을 습득하자!