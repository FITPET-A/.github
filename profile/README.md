# 🐶 FitPet_A
**스마트커버인슈어런스 개선 프로젝트** 

한국대학생IT경영학회 KUSITMS 30th

FitPet A조, Pit-A-Pet <br>

![1](https://github.com/user-attachments/assets/416beeee-a351-4bbc-a92e-399bae497621)



<br><br>

## 👥 Member
| **분야** | **이름** | **포지션** |
| --- | --- | --- |
| 기획 | 최시현 | 🐶 **기획 리드**, 서비스 기획 - 서비스 정책 확립, 비즈니스 모델 구축 |
| 기획 | 김채연 | 🐶서비스 기획 - 유저 리서치, 와이어프레임 작성, UX writing |
| 기획 | 주연진 | 🐶 서비스 기획 - 서비스 정책 확립, 비즈니스 모델 구축 |
| 디자인 | 구름 | 🐶 **PM**, **디자인 리드**, UXUI 디자인 |
| 디자인 | 윤지우 | 🐶 그래픽디자인, UXUI 디자인 |
| 개발 | 이주현 | 🐶 **프론트엔드 리드**, 화면 UI 구현, 서버 연동 |
| 개발 | 이은학 | 🐶 화면 UI 구현, 서버 연동 |
| 개발 | 김다은 | 🐶 **백엔드 리드**, DB 및 API 구축, 서버 배포 |
| 개발 | 김수진 | 🐶 DB 및 API 구축, 서버 배포 |

<br><br>

# ✔️과제 1

### SC 홈페이지 개편을 통한 SC 신뢰도 향상 및 가망고개 DB 수 증가

### 🎯 문제 정의 및 솔루션 도출

### **Problem : 낮은 가망고객 전환율**




<br>

> **문제 인식**

![2](https://github.com/user-attachments/assets/597db458-da96-41fb-8733-5a87c00b41db)  <br><br>




> **문제 정의**

펫보험은 반려동물의 건강과 직결된다는 점에서 고관여 상품임에도 불구하고 다양하고 복잡한 상품, 어려운 설명 등으로 인해 유저들은 **1) 정보의 비대칭 문제**라는 페인포인트에 직면합니다. 

이로 인해 유저들은 최대한 합리적이고 적합한 상품을 선택하고자 믿을만하고 원하는 정보를 제공하는 대리 기관을 모색하게 됩니다. 그러나 이 과정에서 **2) 원치 않는 가입 유도 등의 문제**에 예민하게 반응하기 때문에 **정확하고 필요한 정보를 제공하는, 신뢰할 수 있는 창구**를 필요로 합니다. 따라서 해당 니즈를 충족시켜야 가망고객 전환율을 높일 수 있습니다. <br>

그러나 반려인 대상 In-Depth Interview 결과, SC는 다음과 같은 요인으로 인해 니즈 충족에 대한 확신을 주지 못하고 있음을 확인했습니다.

1. **신뢰성이 떨어지는 랜딩 페이지**
2. **불편한 UIUX** 
3. **잘 드러나지 않은 차별점**

<br>

![3](https://github.com/user-attachments/assets/a68a9d2f-1ca5-4edf-89ce-d00d7183c0cb) <br><br>





> **프로젝트 목표**

따라서, 저희는 ‘가망고객 DB 전환율 상승’이라는 프로젝트 목표 아래 다음과 같은 세 가지 세부 목표에 따라 프로젝트를 진행했습니다.

<br><br><br>




> **경쟁사 분석**

한편 펫보험 견적을 제공하는 경쟁사를 분석한 결과는 다음과 같습니다. <br>
| 서비스명 | 카카오 펫보험 | 비마이펫 | PETFINS | 개별 전문가 및 보험회사직원 | SC |
| --- | --- | --- | --- | --- | --- |
| 서비스 메인 기능 | - 다양한 보험 비교 서비스 제공<br>- 펫보험 가입 | - 반려동물 관련 콘텐츠 제공<br>- 펫보험 추천, 1:1 비교 서비스 제공 | - 펫보험 견적서 제공<br>- 보험 가입 및 청구<br>- 반려동물 관련 콘텐츠 제공 | - 펫보험 가입 상담 서비스 제공 | - 펫보험 견적서 제공<br>- 상담 및 가입 서비스 제공 |
| 서비스 제공 채널 | 카카오톡 앱 (카카오페이 서비스) | 비마이펫 웹, 앱 | PETFINS 웹 | 오픈채팅 및 유선전화 | SC 웹, 카카오톡, 유선 전화 |
| 견적서 및 추천 보험 제시 | - 반려동물의 나이, 질환, 추가 정보 기반 많이 가입하는 보험 제시<br>- 서비스 자체에서 제공하는 보험 관련 설명 부족<br>- 메리츠 화재 보험 제휴 X | - 강아지/고양이 선택 후 질환에 따른 보험 제시<br>- 관심 보험 1:1 비교 가능<br>- 맞춤형 보험 추천에 한계 | - 견종, 나이에 따른 보험사 보험 추천<br>- 1가지 보험 정보만 제공 (견적 비교X) | X (주로 상담으로 대체) | - 주요 보험사 견적 모두 제시<br>- 보장 비율에 따른 세부적인 견적 |
| 상담 서비스 | X | - 커뮤니티 Q&A | - 1:1 문의하기 | - 오픈채팅 및 유선 상담 | - 카카오톡 및 유선 상담<br>- 견적서 받은 카톡 채널을 통해 바로 상담 가능 |
| 가입 서비스 | - ‘보험 가입하기’ CTA 버튼 클릭 후 해당 보험사 페이지로 이동 | - ‘자세히 보기’ CTA 버튼 클릭 후 해당 보험사 페이지로 이동 | - 펫핀스 웹 내에서 정보 입력하고 해당 페이지에서 보험 가입 | - 상담 | - 카카오톡 상담을 통해 보험 가입 |
| 콘텐츠 | X | - 펫보험 관련 콘텐츠 제공 | - 반려동물 관련 콘텐츠 제공<br>- 반려인 커뮤니티 | X | - 반려동물 관련 콘텐츠 제공 (핏팻으로 연결) |
| 타 서비스 대비 SC의 차별성 | - 주요 5대 보험사 제휴<br>- 다양한 옵션의 견적서 제공 (이용자가 직접 판단 가능)<br>- 상담 서비스 제공<br>- 펫보험 단일 서비스 (전문성) | - 맞춤형 보험 추천 가능<br>- 구체적인 견적서 제공<br>- 1:1 상담 서비스 제공 | - 상담 서비스<br>- 주요 보험사 견적 비교 서비스 | - 개인보다 신뢰성 및 전문성 갖춤<br>- 보험 가입 유도 X | |
| 타 서비스 대비 SC의 결점 | - UIUX<br>- 보험 가입까지 한 번에 해결하기 어려움 (상담을 거쳐야 함) | - ‘다른 이용자에게 인기 있는 보험’과 같이 이용자가 결정 과정에 더 참고할 수 있는 자료 부족 (꼭 상담을 거쳐야 함)<br>- 펫보험 서비스와 콘텐츠 간 유기성 부족 | - UIUX<br>- 보험 가입까지 한 번에 해결하기 어려움 (펫핀스는 웹 내에서 바로 해결 가능) |  |  |

<br><br>

경쟁사 분석 결과 SC는 유저들의 정보 비대칭 문제를 해결할 수 있는 서비스를 충분히 갖추고 있음을 알 수 있습니다. 

1. [**간편 견적서 서비스**]는 주요 5대 보험사의 상품 견적을 알기 쉽게 제공하여 펫보험 상품에 장벽을 느끼는 유저들의 페인포인트를 해결할 수 있습니다. 
2. [**1:1 카카오톡 상담 서비스**]는 펫보험 전문가들로부터 원하는 정보를 바로 얻을 수 있다는 점에서 경쟁사와 차별화된 지점입니다. 

따라서 SC만의 서비스를 강조하여 ‘SC를 통해 보험 견적을 비교해야 하는 이유’를 명확히 제시하고자 합니다.

<br><br>

> **서비스 타겟 정의**

서비스의 타겟은 다음과 같습니다. <br>
![4](https://github.com/user-attachments/assets/9963c1e2-7ec0-4850-ba5b-2f39c8304889) <br><br>
이들을 대상으로 서비스 이용에 대한 장벽을 낮추고 SC에 대한 신뢰를 형성했을 때 각각의 목표 과제를 달성하여 DB 전환율을 높일 수 있을 것입니다. <br><br><br>





> **솔루션 도출**

![6](https://github.com/user-attachments/assets/cc72cd46-54a2-4b8c-9e14-cad7be116ed5)

![7](https://github.com/user-attachments/assets/b099adb0-d62e-442f-a076-d366eec80e91)

![8](https://github.com/user-attachments/assets/74ad31c0-5b2f-4b33-a907-8c47f005ba80)

![9](https://github.com/user-attachments/assets/139a2f26-8f3b-4479-be95-084e2f511328)
![10](https://github.com/user-attachments/assets/a80d339e-b8f5-4d21-a674-4b6a513e31a4) <br><br><br>




> **브랜딩 및 캐릭터 디자인**

정보 비대칭으로 인한 불확실성과 불안감을 해소하기 위해 SC 전반에 걸쳐 친근함을 전달할 수 있는 캐릭터를 제작했습니다. <br>
![캐릭터 1](https://github.com/user-attachments/assets/7a3a0fa1-4b8d-4a2d-b231-6a874ca3b4bf)

![캐릭터 2](https://github.com/user-attachments/assets/87b15c08-332c-41e5-975a-498ef4b9f690) <br><br><br>




<br><br><br><br>





## 💻 Technology

### 🕸️ FrontEnd
**Framework & Libraries**  
<img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=React&logoColor=white" />
<img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=Next.js&logoColor=white" /> 
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=TypeScript&logoColor=white" /> 

**UI & Styling**  
<img src="https://img.shields.io/badge/Chakra UI-319795?style=flat&logo=ChakraUI&logoColor=white" />
<img src="https://img.shields.io/badge/Tailwind CSS-06B6D4?style=flat&logo=TailwindCSS&logoColor=white" />  

**Form Management**  
<img src="https://img.shields.io/badge/React Hook Form-EC5990?style=flat&logo=ReactHookForm&logoColor=white" />  

**Linting & Formatting**  
<img src="https://img.shields.io/badge/ESLint-4B32C3?style=flat&logo=ESLint&logoColor=white" />
<img src="https://img.shields.io/badge/Prettier-F7B93E?style=flat&logo=Prettier&logoColor=white" />

**Data Fetching**  
<img src="https://img.shields.io/badge/TanStack Query-FF4154?style=flat&logo=ReactQuery&logoColor=white" />
<img src="https://img.shields.io/badge/Axios-5A29E4?style=flat&logo=Axios&logoColor=white" />

**CI/CD & Tooling**  
<img src="https://img.shields.io/badge/Husky-000000?style=flat&logo=Husky&logoColor=white" />
<img src="https://img.shields.io/badge/Vercel-000000?style=flat&logo=Vercel&logoColor=white" />

<br><br>

### 🛠️ BackEnd

**Language & Framework**  
<img src="https://img.shields.io/badge/Java-007396?style=flat&logo=Java&logoColor=white" />
<img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat&logo=SpringBoot&logoColor=white" /> 
<img src="https://img.shields.io/badge/Spring Security-6DB33F?style=flat&logo=SpringSecurity&logoColor=white" />


**Documentation**  
<img src="https://img.shields.io/badge/Rest Docs-6DB33F?style=flat&logo=Spring&logoColor=white" /> 
<img src="https://img.shields.io/badge/Swagger-85EA2D?style=flat&logo=Swagger&logoColor=black" />

**Database & ORM**  
<img src="https://img.shields.io/badge/Spring Data JPA-6DB33F?style=flat&logo=Spring&logoColor=white" /> 
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=MySQL&logoColor=white" /> 

**Build Tool**  
<img src="https://img.shields.io/badge/Gradle-02303A?style=flat&logo=Gradle&logoColor=white" />

**Cloud & Hosting**  
<img src="https://img.shields.io/badge/AmazonEC2-FF9900?style=flat&logo=AmazonEC2&logoColor=white" /> 
<img src="https://img.shields.io/badge/AmazonRDS-527FFF?style=flat&logo=AmazonRDS&logoColor=white" /> 

**Containerization & CI/CD**  
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=Docker&logoColor=white" /> 
<img src="https://img.shields.io/badge/GithubActions-2088FF?style=flat&logo=GithubActions&logoColor=white" />

<br><br>


### 🌎 Co-Work
[<img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=white" />](https://github.com/FITPET-A)
<img src="https://img.shields.io/badge/Notion-000000?style=flat&logo=Notion&logoColor=white" />


