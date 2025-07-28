# TailWindCSS


--- 
## 개요
<span style="font-size: 18px;">유틸리티 퍼스트 CSS 프레임 우커 </span>


### 장점
- 미리 정의된 작은 스타일 클래스를 조합하여 원하는 디자인 생성
- HTML을 벗어나지 않고도 구축가능
- CSS 파일을 별도로 작성하지 않고 HTML 안에서 빠르게 스타일링이 가능
- 성능 최적화 &rarr; 작은 파일 크기
- 유지보수 &uarr;, 개발속도 &uarr;



### 기본 설치 시 유의 사항(Tailwind CSS Intellisence)
---
- CDN 설치 시 config 파일이 없으니 TailwindCLI의 절차를 따라 config 파일을 생성해야함
- 확인 결과 4.x.x 버전은 intellisence가 잘 안됨 &rarr; 방법이 있다면 찾아봐야겠지만 애초에 3.4.0버전으로 설치하는게 좋을 것 같음
- 코드

   - ``` npm install tailwindcss@^3.4.0 ```
   - ``` npx tailwindcss init ```

- 그리고 config 파일 설정해주면 됨

- ![Warning](https://img.shields.io/badge/⚠️-Warning-red) <span style="font-weight:bold">prettier는 확인하고 사용!</span>
   - 반드시 팀규칙을 확인하고 .prettierrc파일을 확인하고 사용
- 스니펫 또한 팀규칙을 확인한 이후 설정
  - snippet generator를 활용하면 생성가능!

---

### 내용 정리

- [기초 사용](01_tailwind-basic/기초.md)
- [레이아웃](02_layout/레이아웃.md)
- [반응형](03_responsive/반응형.md)
- [트랜지션/애니메이션](04_transition-animation/트랜지션-애니메이션.md)
