# 🧓 보자마자 케어 (Bojamaja Care)

<img src="https://github.com/JISUSAMA/JISUSAMA/assets/38304918/4feeabf0-0fde-4766-a336-5c74ae619f4c" width="100%">

> 터치, 손동작, 전신 인식을 통합한 **시니어 맞춤형 인지훈련 및 건강관리 시스템**

---

## 📌 프로젝트 개요

**보자마자 케어**는 터치 기반 뇌훈련, Leap Motion 기반 손동작 게임, Kinect 기반 전신 체조 콘텐츠로 구성된 시니어 인지훈련 프로그램입니다.  
안면 인식 기반 사용자 구분 및 스케줄 관리 기능을 통해 헬스케어 자동화에 기여합니다.

---

## 📅 개발 기간

**2022.06 ~ 2022.12 (7개월)**

---

## 🛠️ 기술 스택

- `Unity3D`
- `Leap Motion Controller`
- `Microsoft Kinect`
- `C#`
- `OpenCV (얼굴 인식)`

---

## 📂 주요 기능 구성

### 📌 공통 시스템

| 파일명 | 기능 |
|--------|------|
| `GameAppManager.cs` | 전체 게임 흐름 및 상태 제어 |
| `CSVReader.cs`, `CSVFile.cs` | 게임 데이터 로딩 (CSV 기반) |
| `ExerciseReportManager.cs` | 게임 결과 리포트 생성 |
| `ChooseGame_UIManager.cs` | 게임 선택 메뉴 UI 제어 |
| `SoundSetting.cs` | 효과음 및 배경음 설정 |

---

### ✋ Leap Motion 손 게임

| 대표 스크립트 | 설명 |
|----------------|------|
| `GestureManager.cs` | 손 제스처 인식 제어 |
| `FlagUpChecker.cs`, `FlagDownChecker.cs` | 청기백기 손 방향 판별 |
| `StartButton.cs`, `AppManager.cs` | 게임 시작/관리 로직 |

---

### 🧠 치매예방 & 뇌훈련 (터치 기반)

- 경로: `Touch/Dementia_Game/`, `Touch/Brain_Game/`
- 각 게임별 `*_UIManager.cs`, `*_DataManager.cs` 구성

#### 예시 게임 목록
- 단어 색 맞추기
- 사물-글자 연결
- 미로 찾기
- 음식값 계산
- 틀린 그림 찾기
- 숫자판 순서대로 터치하기

---

### 🕺 Kinect 체조 콘텐츠

- 경로: `Gymnastics/Gymnasics_UIManager.cs`
- 전신 동작 인식 기반 체조 미션 제공

---

## 🎮 콘텐츠 구성 요약

### 뇌훈련 (7종)

- 표 단어 터치 / 색상 매칭 / 숫자판 순서 / 반전 글자 등

### 치매예방 (8종)

- 속담-그림 연결 / 낱말 완성 / 숨은 그림 찾기 / 연속 숫자 계산 등

### 손 게임 (5종)

- 가위바위보(이기기/지기), 손가락 셈하기, 청기백기 등

---

## 📷 사용자 메뉴얼

<details>
<summary>📘 메뉴얼 이미지 보기</summary>

<img src="https://github.com/JISUSAMA/JISUSAMA/assets/38304918/672ef65a-786e-449b-ad47-57f96883d19f">
<img src="https://github.com/JISUSAMA/JISUSAMA/assets/38304918/5f96ec77-a999-4d98-b035-f47f8ef6cf38">
<img src="https://github.com/JISUSAMA/JISUSAMA/assets/38304918/33d1f8ad-3880-471a-a894-a878a716a393">
<img src="https://github.com/JISUSAMA/JISUSAMA/assets/38304918/dbc6a1b1-3f4f-4f04-9332-69e5b58802b5">
<img src="https://github.com/JISUSAMA/JISUSAMA/assets/38304918/d115da00-af71-459b-b2a9-a683ebfdea2b">
<img src="https://github.com/JISUSAMA/JISUSAMA/assets/38304918/17edcfd0-d2c2-4bad-bd43-98e5a2778c10">
<img src="https://github.com/JISUSAMA/JISUSAMA/assets/38304918/d95e6e9a-eeb9-49f2-9aaf-e12ac6cad191">
<img src="https://github.com/JISUSAMA/JISUSAMA/assets/38304918/d98243e8-3917-4ce5-8466-27c0d81b9f47">
<img src="https://github.com/JISUSAMA/JISUSAMA/assets/38304918/efc56528-6574-4e89-a572-354698c7a246">

</details>

---

## 👨‍💻 기여 내용

- 전체 콘텐츠 UX 설계 및 시스템 구현
- Kinect/Leap Motion 모듈 연동 및 최적화
- CSV 기반 다국어 콘텐츠 구조화
- 사용자 메뉴얼 UI 흐름 제작

---

## 📩 문의

프로젝트 관련 문의: **[j2su0218@gmail.com](mailto:j2su0218@gmail.com)**
