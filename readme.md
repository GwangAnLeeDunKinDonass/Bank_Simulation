# 🏦 시뮬레이션 모델을 활용한 은행 고객 대기시간 최적화

**IBK 기업은행 고객 대기시간을 최적화하기 위한 시뮬레이션 모델입니다.**  
이 프로젝트는 Arena를 활용해 창구 업무의 비율 불균형과 점심시간 동안의 Capacity 감소 문제를 해결하고, 다양한 개선안을 통해 대기 시간을 줄이는 것을 목표로 합니다.

> 📊 **프로젝트 구성:** 데이터 수집, 모델 생성, 애니메이션화, 개선안 도출 및 검증

---

## 📋 데이터 수집
**직접 방문을 통해 수집한 데이터:**
- 방문 시간대: 오전 (09-11), 점심 (11-13), 오후 (13-16)  
- 수집 항목: 방문 고객 수, 대기 시간, 상담 시간  
- **수집 방법:** 직접 내방해 목적별 데이터를 체크하고, 지수 분포 및 통계 검정을 통해 데이터의 적합성을 검토

---

## 🛠 사용 프로그램
- **Arena:** 공정 시뮬레이션 및 분석 도구  
  - 설치 링크: [Arena 다운로드](https://www.arenasimulation.com/academic/students)  
  - **주요 기능:** Resource와 Schedule을 활용한 업무 시간 및 인원 배치 최적화

---

## 🖥️ 간단한 프로세스 설명
![프로세스 영상](./img/model_video.gif)
- **모델 생성:**
  - 각 Resource와 Schedule을 활용해 은행 창구 직원의 업무 (예금, 대출) 및 출퇴근 시간, 점심 시간을 표현
- **특징:**
  - 창구 직원의 교대 시간 및 업무량 분배를 통해 현실적인 시뮬레이션 구현

---

## 🌀 애니메이션화
![애니메이션 영상](./img/animation.gif)
- **애니메이션 설명:** 실제 은행 창구와 유사하게 고객 흐름 및 대기 상황을 시각화

---

## 📄 참고자료
- [PPT 자료](./img/ppt.pdf)
- **참고 링크:**
  - [Arena 공식 홈페이지](https://www.arenasimulation.com/)

---

## ❓ 문의사항
**Issue**로 남겨주세요! 🙌
