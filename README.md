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
    
  ### 🌟🎥 서비스 기획 ? 영화 예고편을 감상하며, 다양한 영화 정보와 소식을 공유하는 커뮤니티 플랫폼 🎥🌟
  ### 🗓️ 기간 ? 2023.04.10 ~ 2023.05.10 (1개월) 🗓️
    
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
  <br />
  <h1>❶ 회원가입</h1>
  <h3>⭐️ 이메일 인증기능 구현</h3>
  <p><strong>🎯 유저가 자신의 정보로 정확하고 안전하게 가입할 수 있도록, 보다 더 직관적이고 편리하게 구현하기</strong></p>
  <p><strong>🎯 회원가입의 flow가 애매하거나 헷갈리지 않도록 구현하고, 빠르고 심플한 회원가입을 만들기</strong></p>
  <p>- 서버에 해당 이메일이 등록되어 있는지, 이메일의 유무를 먼저 확인하기 위해 이메일 중복체크 기능 구현</p>
  <p>- 중복체크를 통과해야, 인증버튼이 활성화 되도록 구현</p>
  <p>- 인증 버튼을 누르면, 인증번호 입력하는 Input 창 생성 + 해당 이메일에 인증번호메일이 발송되도록 구현</p>
  <p>- 인증번호 input 창에 인증번호를 입력 (type=number)</p>
  <p>- 인증번호 input 창에 입력되는 숫자의 length가 6이 되는 순간, axios.post 로 유효한 인증번호인지 자동 통신</p>
  <p>- 인증번호가 일치하면, 이메일 input 창 + 인증버튼 + 인증번호 input창 모두 disabled 처리</p>
  <p>- 인증번호의 일치유무는, 인증번호 Input 창 placeholder 텍스트가 '인증에 성공했습니다. 비밀번호를 설정해주세요.' 로 자동 변경되도록 구현하여, 유저에게 여부정보를 확실히 알려주어 다음 단계를 원활히 진행하도록 함</p>
  <p>- 전반적인 에러핸들링 디테일하게 처리 (사용가능한 이메일인지, 인증이 제대로 성공했는지 등 회원가입 시 필요한 여러 여부정보들을 유저가 즉시 알 수 있도록, state 들로 상태들을 관리하여 조건에 따라 상황에 알맞는 텍스트로 자동변경되도록 구현)</p>
    <br />
  <h3>⭐️ 정규식 표현을 사용한 비밀번호 유효성 검사 기능</h3>
  <p>- 설정해놓은 정규식 조건과 테스트에 일치하기 전까지, 비밀번호 input 창의 테두리가 빨갛게 유지 / 일치하는 순간 검정 스타일로 돌아오게하여(+ 회원가입 버튼 활성화) 사용가능한 비밀번호의 여부를 즉각적으로 유저에게 알려주게끔 구현</p>
  <p>- 회원가입 성공 시, 메인으로 이동하며 알림(sweetAlert2 라이브러리 활용)모달창을 띄워 회원가입 후 flow를 원활하고 자연스럽게 유도</p>
  <p> + 불필요한 렌더링을 줄이기 위해, 컴포넌트 memo 처리</p>
    <br />
    <br />
  <h1>❷ 로그인</h1>
  <h3>⭐️ 소셜 로그인</h3>
  <p><strong>🎯 카카오 로그인 구현</strong></p>
  <p>- 카카오 로그인에 필요한 정보들을 .env 에 추가 + KakaoConfig.tsx 에서 일괄 관리하여 유지보수 용이</p>
  <p>- 카카오 로그인 통신 시, 인가코드를 받기 위한 redirect uri page 생성 (KakaoLogin.tsx)</p>
  <p>- redirect page 가 렌더링 될 때, useEffect 를 사용 (받은 인가코드를 카카오 토큰 서버에 보냄 -> 서버에서 인가코드를 체크하고 access-token 을 다시 내게 보내줌 -> 받은 access-token을 백엔드에 전달 -> jwt 토큰으로 프론트에게 발급 -> 로그인 완료로 유저를 main 으로 이동시킴)</p>
  <p>- token 을 sessionStorage에 저장 -> 로그아웃 시 token remove (* cookie 로 관리하여 보안성 높여야 할 필요성)</p>
  <p><strong>🎯 구글 로그인 구현</strong></p>
  <p>- @react-oauth/google 라이브러리를 활용</p>
  <p>- 구글 로그인 통신을 위해 라이브러리가 제공하는 useGoogleLogin() 함수를 사용하여, 구글 서버로부터 access-token을 받아 백엔드에 넘겨주면 jwt 토큰을 발급받게 됨 => sessionStorage에 저장</p>
  <p><strong>🎯 자체 로그인 구현</strong></p>
  <p>- 이메일과 패스워드의 필수조건에 부합하지 않으면, 로그인 버튼 비활성화 (부합하면 버튼 활성화)</p>
  <p>- 동일한 Input 레이아웃이 중복되므로, 컴포넌트화(UserInput) 재활용 (props 로 데이터 관리)</p>
  <p>- Form 태그로 로그인 코드를 짰으나, 버튼 type이 submit 일 경우 통신이 2번가는 에러가 뜨게 되어 type을 button 으로 변경</p>
  <p>- 로그인 버튼 클릭 시, 이메일과 패스워드가 서버DB로 보내고, 회원인 경우 토큰을 보내주게 된다. 해당 토큰은 sessionStorage로 저장
  <p>- 회원이 아닐 경우, 알림(sweetAlert2 라이브러리 활용)모달창을 띄워 유저가 재로그인 혹은 회원가입을 하도록 한다.</p>
  <p>- 보안을 고려하여 패스워드 input 에 복사/붙여넣기/자르기 방지 기능 구현</p>
    <br />
    <br />
  <h1>❸ 블로그 메인 페이지</h1>
  <h3>⭐️ 무한 스크롤 기능 구현</h3>
  <p>- Intersection Observer API 을 활용 (useRef 로 target 잡은 요소와 viewport 의 교차점을 감지해, 다음 데이터를 통신하여 받아온다.)</p>
  <p>- 더 추가하기</p>
    <br />
  <h3>⭐️ 조건부 렌더링</h3>
  <h3>🎯 스포/미스포 토글</h3>
  <p>- toggle 기능을 사용하여, 스포일러 포함 포스트/스포일러 미포함 포스트 각자 해당되는 데이터로 렌더링되도록 구현</p>
  <p>- 서버가 보내주는 UTC 날짜시간과, 현재 날짜 시간의 오차일을 구하여 블로그 포스트 작성일이 자동계산 되도록 구현</p>
  <h3>🎯 My blog 토글</h3>
  <p>- 상단 탭의 이름이 'My blog'로 변할 때에(==클릭할때에) 백엔드에서 POST 로 데이터 통신</p>
  <p>- 회원가입 되어있는 회원만, 블로그 글을 쓸 수 있으므로 로그인 한(token을 가진)회원인지 구별하기 위해 통신 headers 에 token을 넣어 보내줌</p>
  <p>- 백엔드에서는 해당 토큰으로 고유한 유저를 찾아, 그 유저가 가지고있는 id가 작성한 블로그 데이터를 선별하여 담아 보내줌</p>
  <p>- 조건에 따라 알맞는 데이터 렌더링 구현</p>
  <p>- My blog 렌더링 시, 스포/논스포 를 관리하지 않는 기획을 따라, style 을 hidden으로 주어 숨김</p>
    <br />
  <h3>⭐️ 검색 기능</h3>
  <p>- 검색을 담당하는 레이아웃과 기능을 컴포넌트로 분리 (Search.tsx)</p>
  <p>- 검색 input 창에 검색어를 입력하고, 추가한 돋보기 모양 버튼을 클릭할 시 -> axios.post 로 통신</p>
  <p>- 검색어는 postTitle 데이터 기준으로 검색하여 데이터를 받게 됨</p>
  <p>- 검색 데이터를 관리할 컴포넌트 생성(BlogSearchArticle.tsx), 받은 데이터를 조건에 알맞게 렌더링 시켜줌 </p>
    <br />
    <br />

---

    <br />
  <div align="center">
    <a href="https://github.com/mgkkm/meerkats-frontend" alt="meerkats FE repo">👉🏻 FE Team Repository로 이동하고 싶다면 클릭해주세요! 👈🏻</a>
  </div>
    <br />
    <br />
