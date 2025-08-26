# 단어 맞추기 게임 🧩
Word2Vec을 활용한 단어 유사도 기반 단어 맞추기 게임!

---

## 📂 활용 데이터셋
- 출처: AI_HUB / **"지식검색기반 데이터"**  
- 카테고리: **배움과 학문**  
- 파일: **14,622개**  
- 크기: **(행 301,959, 열 3)**  
- 링크: [AI Hub 데이터 바로가기](https://www.aihub.or.kr/aihubdata/data/view.do?pageIndex=5&currMenu=115&topMenu=100&srchOptnCnd=OPTNCND001&searchKeyword=&srchDetailCnd=DETAILCND001&srchOrder=ORDER001&srchPagePer=20&srchDataRealmCode=REALM002&aihubDataSe=data&dataSetSn=71304)

---

## ⚙️ 과정
### 1. 데이터 로드  
### 2. 데이터 전처리  
  1) 문장부호, 공백 삭제  
  2) 불용어 제거  
  3) 토큰화  
  4) 품사 태깅  
  5) 명사만 추출  
  6) 길이 1 이하 단어 제거  
  7) 추가 불용어 제거  
### 3. 데이터셋 학습  
  - Word2Vec  
### 4. 단어 유사도 기반 게임 함수  
  1) A, B 계산  
  2) 유사도 계산  

---

## 🎮 실행결과
- `?` → 단어를 유추해서 입력  
- 입력한 단어가 **단어 사전에 없다면** → `!!!retry!!!` 출력  
- 입력한 단어가 **단어 사전에 있는데, 정답이 아니라면** → **유사도 출력**  
- `포기` 입력 → 정답 출력  
- `n` 입력 → 종료  
- 사용자가 종료할 때까지 **무한 반복**  

<br>

<p align="center">
  <img width="600" src="https://github.com/user-attachments/assets/1353da29-ea60-4dd4-a08e-a7bd874f0289" />
</p>
