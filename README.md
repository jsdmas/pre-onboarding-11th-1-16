# 🌱 프리온보딩 프론트엔드 과제 Week 1 TEAM 16

wanted 프리온보딩 1주차 과제입니다 🔥

## 배포 페이지

🎉 Team16 배포 링크 👇

[https://pre-onboarding-11th-1-16.netlify.app/](https://pre-onboarding-11th-1-16.netlify.app/)

## 📝 프로젝트 핵심 요구사항

- 로그인 / 회원가입 기능 구현
- 이메일과 비밀번호의 유효성 검사기능을 구현
- 로그인 여부에 따른 리다이렉트 처리
- API명세서를 활용한 todo CRUD

## 💾 **기술 스택**

- Style : `Emotion`
- Language : `TypeScript`
- Interface : `React.js`

## **💻 핵심 구현 기능**

- 프라이빗 라우터
    
    - 사용자의 로그인 여부를 확인하여 **token**을 검사해 페이지로 보내줄지 여부를 검사합니다.
    
    - 사용자 로그인 여부는 localStorage 에 저장되며 JWT형태로 저장되어 식별합니다.
    
    기존에는 useEffect를 사용해 token을 식별하여 사용자에게 페이지를 보여주었습니다.
    
    하지만 팀원들과 소통하며 **페이지를 렌더링 한 후에 사용자를 redirect 시켜주는것은 매우 비효율적**이라 판단했습니다. 
    
    떄문에 **렌더링 비용을 줄이기 위해** router에서 token을 식별해주는 프라이빗 라우터를 구현하게 되었습니다.
    
    **token O**
    
    ![](https://github.com/jsdmas/jsdmas.github.io/assets/105098581/0091eff0-d764-4f3d-91bd-ea0ee0851c7b)
    
    **token X**
    
    ![](https://github.com/jsdmas/jsdmas.github.io/assets/105098581/da356524-06fb-449a-945e-351e2b11c3f3)
    

## ‼️ **깨달은 점**

- **Suspense**를 라우터에 적용하여 페이지 로딩을 표시하며 **사용자 편의 개선 경험**
- **formatter**를 활용해 일관된 규칙으로 코드를 작성하여 **가독성 향상 경험**
- 다른 팀원이 만든 customHook을 사용해보며 **코드 재사용성과 모듈화에 대한 이해 향상**
- 사람들과 협업하여 결과물을 만들어 내기까지 **적극적인 소통의 중요성**을 인지
- github commit message 표현의 중요성, 상세한 PR, Code Review를 통해 **협업 이해도 상승**

## **Team 16 팀원 소개**

<table>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/scs0209"><img src="https://github.com/jsdmas/jsdmas.github.io/assets/105098581/e237b4f3-26f3-4a37-8818-86787f5d858b" width="100px" alt=""/><br /><sub><b>🙎🏻‍♂️ FE 팀원 : 창수 </b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/jsdmas"><img src="https://avatars.githubusercontent.com/u/105098581?s=400&v=4" width="100px;" alt=""/><br /><sub><b>🙎🏻‍♂️ FE 팀원 : 진호</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/seongminn"><img src="https://github.com/jsdmas/jsdmas.github.io/assets/105098581/3fdd5b88-e4ba-412b-a89e-b71694c153f7" width="100px;" alt=""/><br /><sub><b>🙎🏻‍♂️ FE 팀원 : 성민</b></sub></a><br /></td>
     <tr/>
      <td align="center"><a href="https://github.com/sjerry-kim"><img src="https://github.com/sjerry-kim/Portfolio_Academy_ARCO/assets/112137364/23130bde-b5ff-48c3-bfd9-45a1e8bebe07" width="100px;" alt=""/><br /><sub><b>🙎🏻‍♀️ FE 팀장 : 진혜</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/seunghowhite"><img src="https://avatars.githubusercontent.com/u/105100315?v=4" width="100px;" alt=""/><br /><sub><b>🙎🏻‍♂️ FE 팀원 : 승호</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/jioneee"><img src="https://github.com/jsdmas/jsdmas.github.io/assets/105098581/11d05a3a-57b2-4ae0-96b3-747b557ff6be" width="100px;" alt=""/><br /><sub><b>🙎🏻‍♀️ FE 팀원 : 지원</b></sub></a><br /></td>
    </tr>
  </tbody>
</table>

<br/>
