<div align="center">
  <br/>
  <br/>
  <div>
    <img src="https://github.com/mgkkm/meerkats-frontend/assets/58460131/c0740a1f-afa9-4a1f-b77e-effcf8841731" width="90%" />
  </div>
  <br />
  <div align="center">
  <p> 
  <br />
    
  ### 🌟🎥 서비스 기획 ; 영화 예고편을 감상하며, 다양한 영화 정보와 소식을 공유하는 커뮤니티 플랫폼 🎥🌟
  ### 🗓️ 기간 ; 2023.04.10 ~ 2023.05.10 (1개월) 🗓️
    
  <br />
  </div>
  <br/>
  <br/>
  <h1 align="center">👋🏻 Team</h1>
  <br />
  <table>
    <thead>
      <tr align="center">
        <th colspan=3>FE</th>
        <th colspan=2>BE</th>
      </tr>
    </thead>
    <tbody>
      <tr align="center">
        <td>강서윤
        <br/><a href="https://github.com/seoyunfleuve">
        <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white"/></a></td>
        <td>오현주
        <br/><a href="https://github.com/hyunjoo1130">
        <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white"/></a></td>
        <td>이진경
        <br/><a href="https://github.com/ijinkyung">
        <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white"/></a></td>
        <td>김광휘
        <br/><a href="https://github.com/Hwi227">
        <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white"/></a></td>
        <td>김승기
        <br/><a href="https://github.com/seuungkei">
        <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white"/></a></td>
      </tr>
    </tbody>
  </table>
  <br />
  <br />
  <br />
  <br />
  <h1 align="center">🛠️ My Tech Stacks</h1>
  <br />
  <div align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white">
 <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black">
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
 <img src="https://img.shields.io/badge/Tailwind CSS-06B6D4?style=for-the-badge&logo=Tailwind css&logoColor=white">
 <img src="https://img.shields.io/badge/Daisy UI-5A0EF8?style=for-the-badge&logo=daisyui&logoColor=white">
  <img src="https://img.shields.io/badge/Amazon AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white">
    <img src="https://img.shields.io/badge/Amazon S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white">
</div>
<br />
<div align="center">
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white">
<img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white">
<img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white">
<img src="https://img.shields.io/badge/adobe photoshop-31A8FF?style=for-the-badge&logo=adobe photoshop&logoColor=white">
 </div>
</div>
  <br />
  <br />
  <br />
  <br />

  <h1 align="center">🖥️ 내가 구현한 기능</h1>
  
  <p>기능별로 나누어서 쓰기</p>
  
    <br />
  <h2>❶ 회원가입</h2>
  <p>- 기본적으로 meerkats만의 자체 회원가입을 구현했습니다.</p>
  <p>- 이메일 입력 시, 해당 이메일의 존재 여부를 미리 확인할 수 있도록, 중복체크 기능을 구현했습니다. (에러핸들링 처리)</p>
  <p>- 등록 가능한 이메일이라면, 해당 이메일에 인증번호를 보내 정확한 본인 확인이 되도록 구현했습니다. (에러핸들링 처리)</p>
  <p>- 비밀번호에 필수적으로 들어가야 하는 여러 조건에 유저가 즉시 맞출 수 있도록, input 에 정규식 표현 조건을 걸고, 스타일 색상을 다르게 주어 직관적으로 인식할 수 있게 구현했습니다.</p>
  <p>- 유저의 효율적인 회원가입을 위해 이메일, 비밀번호, 닉네임 3개의 input 에 조건에 맞게 모두 값이 들어갔을 때 회원가입 버튼이 활성화되도록 구현했습니다.</p>
    <br />
  <h2>❷ 로그인</h2>
  <p>- 유저의 빠른 로그인을 위해 대중적으로 많이 사용하는 카카오 API를 연동했습니다.</p>
  <p>- 카카오에서 인가 코드를 받아, 카카오로 전달하면 토큰을 발급받고, 해당 토큰을 백엔드에 보냅니다. 백엔드에서 JWT 토큰을 발급하고, 해당 토큰이 'meerkats' 플랫폼 전용 토큰으로서 sessionStorage 에 저장되도록 구현했습니다.</p>
  <p>- 자체 로그인은 이메일과 패스워드 input 의 값이 기본적인 조건을 만족했을 때 로그인 버튼이 활성화 되도록 구현했습니다. (에러핸들링 처리)</p>
  <p>- 자체 로그인은 jwt 토큰을 백에서 전달받고, 유저를 토큰으로 구별하여 사이트를 이용할 수 있도록 구현했습니다.</p>
  <p>- 보안을 고려하여 패스워드 input 에 복사/붙여넣기/자르기 기능을 방지했습니다.</p>
    <br />
  <h2>❺ 블로그 메인 페이지</h2>
  <p>- Intersection Observer API 를 통해 무한 스크롤 기능을 구현했습니다. (observer div 박스와 viewport의 교차점을 이용한 무한 스크롤 API)</p>
  <p>- 원하는 블로그를 쉽게 찾아볼 수 있도록 검색 기능을 구현했습니다.</p>
  <p>- 영화라는 특성을 고려해 스포일러가 포함된 블로그와, 스포일러가 포함되지 않은 블로그를 선택하여 볼 수 있도록 스포일러 토글에 따른 렌더링을 구현했습니다.</p>
  <p>- 장르별로 블로그를 모아볼 수 있도록 장르 카테고리 드롭다운을 구현했습니다.</p>
  <p>- 내가 쓴 블로그를 모아볼 수 있도록 My Blog 탭 페이지를 생성했습니다.</p>
  <p>- 반복되는 레이아웃을 컴포넌트로 분리하고, 변동되는 데이터는 props로 관리했습니다.</p>
    <br />
  <h2>❺ 검색 기능</h2>
    <br />
    <br />

---

  <br />
  <div align="center">
    <a href="https://github.com/mgkkm/meerkats-frontend" alt="meerkats FE repo">👉🏻 FE Team Repository로 이동하고 싶다면 클릭해주세요! 👈🏻</a>
  </div>
