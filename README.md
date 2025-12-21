
- **Project Manager**: 심서진(Sim SeoJin)
- **Contributor**: 이재민(Lee jaemin)

---

## 🚀 구현된 기능 (Main Features)

이슈(Issue)를 정의하고 PR을 통해 추가된 기능들입니다.

### 1. 깃발 색 변경 (#1)
- **기능 설명**: 게임 전/중 상관없이 체크박스를 통해 원하는 색상을 고를 수 있는 기능 추가했습니다. 
- **상세**: 총 색상은 왼쪽부터 빨간색, 주황색, 노란색, 파란색으로 총 4개가 있습니다.
- **스크린샷**:
<img width="569" height="311" alt="image" src="https://github.com/user-attachments/assets/25979705-f511-480c-a256-9a5f652a68ec" />
<img width="569" height="270" alt="image" src="https://github.com/user-attachments/assets/a617c53b-d163-47a4-a926-990b0a6a7db0" />

### 2. 게임 정지 기능 추가 (#2)
- **기능 설명**: 게임 시작 후 게임을 정지하는 기능을 추가했습니다..
- **상세**: ESC를 누르게 되면 게임이 저징되고 좌클릭을 누를 시 멈춰있던 게임이 시작됩니다. 
- **스크린샷**: 
<img width="470" height="377" alt="image" src="https://github.com/user-attachments/assets/cb44f377-0cb2-4549-9513-5d6952293265" />
<img width="486" height="355" alt="image" src="https://github.com/user-attachments/assets/bccbbf97-7dfd-45a1-aabb-5cf21b87997a" />

### 3. 셀 하이라이트 기능 추가. (#5)
- **기능 설명**: 닫힌 셀에 마우스 커서가 위치하면 셀이 강조되는 기능을 추가했습니다. 
- **상세**: 열린 셀에선 강조되지 않고 오로지 닫힌 셀에서만 강조가 됩니다.
- **스크린샷**: 
<img width="569" height="322" alt="image" src="https://github.com/user-attachments/assets/05495745-fdd3-4cb8-ac83-d165e1a1a895" />


### 4. 지뢰 찾기 힌트 제공 (#6)
- **기능 설명**: 사용자가 막혔을 때 지뢰가 없는 안전한 칸을 한 곳 알려주는 기능을 구현했습니다.
- **상세**: 게임 화면의 힌트 버튼을 누르면 닫힌 셀에 하이라이트가 됩니다. 
- **스크린샷**: 
 <img width="569" height="616" alt="image" src="https://github.com/user-attachments/assets/95fc337f-014e-45d7-b61f-d97457263d66" />


### 5. 하이 스코어(기록) 시스템 (#7)
- **기능 설명**: 가장 빠르게 게임을 클리어한 최단 시간을 저장하고 메인 화면에 출력합니다.
- **상세**: 로컬 파일 또는 메모리에 저장되어 최고 기록을 갱신합니다. 
- **스크린샷**:
<img width="569" height="439" alt="image" src="https://github.com/user-attachments/assets/79d0854b-f16a-43f5-b27b-ca04f8cf8a66" />


---

## 🛠 협업 프로세스 (Collaboration Process)
본 프로젝트는 GitHub의 **Issue, Fork, Pull Request(PR), Code Review** 과정을 거쳐 완성되었습니다.

1. **Issue 생성**: PM이 추가 기능 5개를 Issue로 정의함.
2. **Fork & Work**: Contributor가 PM의 저장소를 Fork하여 각 기능을 구현함.
3. **Pull Request**: 기능별로 총 5개의 PR을 생성하고 Commit 메시지에 Issue 번호를 명시함.
4. **Code Review**: PM이 PR에 대해 코드 스타일, 에러 처리 등을 리뷰하고 피드백을 전달함. ( PR을 수행하고 난 뒤 일부 코드 수정. )
5. **Merge**: 피드백 반영 후 최종적으로 코드를 메인 저장소에 반영함.

---

## 💻 설치 및 실행 (Setup)
```bash
# 1. 라이브러리 설치
pip install pygame

# 2. 실행
python run.py
