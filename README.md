# EmotionDiary
React를 사용하여 일기장 프로젝트를 진해하였습니다. 일기 목록 페이지, 일기 수정 페이지, 일기 추가 페이지, 일기 상세 페이지로 구성되어있으며 react-router-dom의 BrowserRouter 통해 페이지 전환이 이뤄 지도록 하였고 변화되는 일기의 정보들은 useReducer를 사용하여 상태를 관리하였습니다. 이로 인해 상태들이 복잡해 졌을 때 useState보다 코드의 크기를 줄이고 가독성을 향상시켰다. 이러한 일기 정보들은 Context를 사용하여 여러 컴포넌트들에게 한번에 내려줌으로써 단순 props를 사용하였을 때보다 번거로움을 줄어들었습니다. 이 외에도 useEffect, useCallback hooks를 사용하여 페이지 랜더링 최적화를 진행하였다.
<br><br>
RELEASE - https://emotion-diary-psi.vercel.app/
<br><br>
일기 목록 페이지
<br>
<img src="https://github.com/hyeokii/EmotionDiary/assets/92020565/cdbe1769-a5fc-4f55-a46d-b2de4a787c87" width="500" height="500"/>

일기 추가 페이지
<br>
<img src="https://github.com/hyeokii/EmotionDiary/assets/92020565/d013f8b8-2fa5-4208-a12e-ad4f28689304" width="500" height="500"/>

일기 수정 페이지
<br>
<img src="https://github.com/hyeokii/EmotionDiary/assets/92020565/4ad41dba-7b08-49be-b36c-322f5e1940e9" width="500" height="500"/>

일기 상세 페이지
<br>
<img src="https://github.com/hyeokii/EmotionDiary/assets/92020565/626e468d-146d-40c0-8a3a-187703fa8667" width="500" height="500"/>

