<template>
<div id="container">
    <div id="root">
        <header class="header">
            <h3 class="welcome">welcome</h3>
            <h1 class="my"><a href="/">LJY</a></h1>
            <a href="/" class="resume">resume</a>
        </header>
        <div class="nav_dots">
            <ul>
                <li class="dot"><a href="#home" class="dot_title">
                    <span>home</span><i class="fa-solid fa-circle" style="font-size:16px;"></i></a>
                </li>
                <li class="dot"><a href="#about" class="dot_title">
                    <span>About</span><i class="fa-solid fa-circle" style="font-size:16px;"></i></a></li>
                <li class="dot"><a href="#skills" class="dot_title">
                    <span>Skills</span><i class="fa-solid fa-circle" style="font-size:16px;"></i></a></li>
                <li class="dot"><a href="#archiving" class="dot_title">
                    <span>Archiving</span><i class="fa-solid fa-circle" style="font-size:16px;"></i></a></li>
                <li class="dot"><a href="#projects" class="dot_title">
                    <span>Projects</span><i class="fa-solid fa-circle" style="font-size:16px;"></i></a></li>
            </ul>
        </div>
        <main>
            <section id="home" class="home">
                <h2 class="scroll_on scroll_on type_left hi" ref="scrollItem1">안녕하세요!</h2>
                <h2 class="scroll_on my_self" ref="scrollItem2">백엔드 개발자 이재윤입니다!</h2>
                <hr class="scroll_on hr" ref="scrollItem3">
                <h2 class="scroll_on type_left introduce" ref="scrollItem4">기본에 충실해 지고 싶은 사람</h2>
                <h2 class="scroll_on introduce" ref="scrollItem5">함께 즐기며 일하고 싶은 사람, 이재윤 입니다!</h2>
            </section>
            <section id="about" class="about">
                <h2 class="title">About</h2>
                <div class="about_me">
                    <div class="about_me_wrapper">
                        <div class="about_me_info">
                            <div class="about_me_icon"><img class="about_me_img" src="./assets/images/user.svg" /></div>
                            <div class="about_me_field">
                                <div class="about_me_label">이름</div>
                                <div class="about_me_value">이재윤</div>
                            </div>
                        </div>
                    </div>
                    <div class="about_me_wrapper">
                        <div class="about_me_info">
                            <div class="about_me_icon"><img class="about_me_img" src="./assets/images/calendar.svg" /></div>
                            <div class="about_me_field">
                                <div class="about_me_label">생년월일</div>
                                <div class="about_me_value">1998.03.12</div>
                            </div>
                        </div>
                    </div>
                    <div class="about_me_wrapper">
                        <div class="about_me_info">
                            <div class="about_me_icon"><img class="about_me_img" src="./assets/images/location.svg" /></div>
                            <div class="about_me_field">
                                <div class="about_me_label">주소지</div>
                                <div class="about_me_value">경기도 광주시 삼동</div>
                            </div>
                        </div>
                    </div>
                    <div class="about_me_wrapper">
                        <div class="about_me_info">
                            <div class="about_me_icon"><img class="about_me_img" src="./assets/images/mobile.svg" /></div>
                            <div class="about_me_field">
                                <div class="about_me_label">연락처</div>
                                <div class="about_me_value">010-2808-6087</div>
                            </div>
                        </div>
                    </div>
                    <div class="about_me_wrapper">
                        <div class="about_me_info">
                            <div class="about_me_icon"><img class="about_me_img" src="./assets/images/mail.svg" /></div>
                            <div class="about_me_field">
                                <div class="about_me_label">이메일</div>
                                <div class="about_me_value">soacb1@naver.com</div>
                            </div>
                        </div>
                    </div>
                    <div class="about_me_wrapper">
                        <div class="about_me_info">
                            <div class="about_me_icon"><img class="about_me_img" src="./assets/images/card.svg" /></div>
                            <div class="about_me_field">
                                <div class="about_me_label">자격증</div>
                                <div class="about_me_value">정보처리산업기사</div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            <section id="skills" class="skills">
                <h2 class="title">Skills</h2>
                <div class="skills_container">
                    <div class="skills_tech_stacks hov">
                        <div class="skill_title">Backend</div>
                        <img class="skill_img" src="./assets/images/java.png" />
                        <img class="skill_img" src="./assets/images/spring.png" />
                        <img class="skill_img" src="./assets/images/mybatis.png" />
                        <img class="skill_img" src="./assets/images/oracle.png" />
                    </div>
                    <div class="skills_tech_stacks hov" style="margin:0px 80px 26px 80px;">
                        <div class="skill_title">Frontend</div>
                        <img class="skill_img" src="./assets/images/html,js,css.png"/>
                        <img class="skill_img" src="./assets/images/jquery.png"/>
                        <img class="skill_img" src="./assets/images/vue.png"/>
                    </div>
                    <div class="skills_tech_stacks hov">
                        <div class="skill_title">Deployment</div>
                        <img class="skill_img" src="./assets/images/netlify.png"/>
                    </div>
                    <div class="skills_tech_stacks hov">
                        <div class="skill_title">Version Control</div>
                        <img class="skill_img" src="./assets/images/git.png" style="margin-left:-11px;"/>
                        <img class="skill_img" src="./assets/images/github.png"/>
                        <img class="skill_img" src="./assets/images/sourcetree.png" style="margin-left: 5px;"/>
                    </div>
                    
                </div>
            </section>
            <section id="archiving" class="archiving">
                <h2 class="title">archiving</h2>
                <div class="archiving_container">
                    <a href="https://github.com/Jaegeul" class="archiving_content hov" target="_blank">
                        <div class="archiving_img_wrapper">
                            <img class="archiving_img" src="./assets/images/github.png" />
                        </div>
                        <div class="archiving_url">https://github.com/Jaegeul</div>
                        <div class="archiving_description">
                            <p><b>소스 코드 저장소</b>입니다.</p>
                            <ul>
                                <li>과거 프로젝트 소스 코드</li>
                                <li>현재 진행중인 프로젝트 소스 코드</li>
                            </ul>
                        </div>
                    </a>
                    <a href="#" class="archiving_content hov">
                        <div class="portfolio_img_wrapper">
                            <img class="portfolio_img" src="./assets/images/portfolio.png" />
                            <p class="portfolio">Portfolio</p>
                        </div>
                        <div class="archiving_description">
                            <p><b style="font-family: sans-serif;">클릭 시 포트폴리오 pdf 파일로 이동합니다.</b></p>
                        </div>
                        <div class="portfolio_description">
                            <p class="archiving_description port">포트폴리오를 웹 애플리케이션이 아닌</p>
                            <p class="archiving_description port">문서형식으로 작성한 pdf 파일 입니다.</p>
                        </div>
                    </a>
                </div>
            </section>
            <section id="projects" class="projects">
                <h2 class="title">Projects</h2>
                <div class="projects_container">
                    <div class="projects_title">포트폴리오 웹사이트</div>
                    <div class="projects_period">2024.06&nbsp;(개인 프로젝트)</div>
                    <div class="projects_info">
                        <div class="projects_img-carousel2">
                            <div id="carouselExampleAutoplaying" class="carousel slide" data-bs-ride="carousel">
                                <div class="carousel-indicators">
                                    <button type="button" data-bs-target="#carouselExampleAutoplaying" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                                    <button type="button" data-bs-target="#carouselExampleAutoplaying" v-for="index in 3" :key="index" :data-bs-slide-to="[index]" :aria-label="'Slide '+ (index+1)" ></button>
                                    <button type="button" data-bs-target="#carouselExampleAutoplaying" data-bs-slide-to="4" aria-label="Slide 5"></button>
                                    
                                </div>
                                <div class="carousel-inner">
                                    <div class="carousel-item active">
                                        <img src="./assets/images/portfolio/1.png" class="d-block w-100" alt=".">
                                    </div>
                                    <div v-for="(image, index) in images1" :key="index" class="carousel-item">
                                        <img :src="image" class="d-block w-100">
                                    </div>
                                </div>
                                <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleAutoplaying" data-bs-slide="prev">
                                    <span class="carousel-control-prev-icon icon-color" aria-hidden="true"></span>
                                    <span class="visually-hidden">Previous</span>
                                </button>
                                <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleAutoplaying" data-bs-slide="next">
                                    <span class="carousel-control-next-icon icon-color" aria-hidden="true"></span>
                                    <span class="visually-hidden">Next</span>
                                </button>
                            </div>
                        </div>
                        <div class="projects_descriptions2">
                            <div class="projects_main-descriptions2">
                                <b>포트폴리오 용도로 제작한 웹사이트</b>입니다. 지금 보고 있는 바로 이 사이트에 해당합니다.
                                다양한 언어를 접하고 경험을 쌓기 위한 첫 걸음으로 포트폴리오 사이트를 제작 하였습니다.
                                <p></p>
                                이미 Javascript와 jQuery를 사용하여 개발을 완료한 프로젝트였지만, <span class="projects_red">Vue.js</span>의 학습을 위해
                                이를 Vue.js로 다시 개발하였습니다. 그 과정에서 Vue.js의 장점인 쉬운 학습 곡선과 반응성, 서버 사이드 렌더링 등을 경험하였습니다.
                                또한, <span class="projects_red">Netlify</span>을 이용하여 정적 웹사이트의 배포를 경험해볼 수 있었습니다.
                                <p></p>
                            </div>
                            <div class="projects_description_container">
                                <div class="projects_description">
                                    <div class="projects_label">
                                        <img class="label_img" src="./assets/images/check.svg" /> 주요기능
                                    </div>
                                    <div class="projects_value">
                                        간단한 자기소개, 인적 사항, 기술 스택, GitHub 및 포트폴리오 pdf 파일 링크, 프로젝트 경험
                                    </div>
                                </div>
                                <div class="projects_description">
                                    <div class="projects_label">
                                        <img class="label_img" src="./assets/images/check.svg" /> 
                                        <span class="projects_label_en">GitHub</span>
                                    </div>
                                    <div class="projects_value">
                                        <a class="projects_url" href="https://github.com/Jaegeul/portfolio-vue" target="_blank">github.com/Jaegeul/portfolio-vue</a>
                                    </div>
                                </div>
                                <div class="projects_description">
                                    <div class="projects_label">
                                        <img class="label_img" src="./assets/images/check.svg" /> 
                                        <span class="projects_label_en">URL</span>
                                    </div>
                                    <div class="projects_value">
                                        <a class="projects_url" href="http://ljy-portfolio.site/" target="_blank">ljy-portfolio.site</a>
                                    </div>
                                </div>
                                <div class="projects_description">
                                    <div class="projects_label">
                                        <img class="label_img" src="./assets/images/check.svg" /> 
                                        <span class="projects_label_en">Frontend</span>
                                    </div>
                                    <div class="projects_value">
                                        Vue.js, Bootstrap
                                    </div>
                                </div>
                                <div class="projects_description">
                                    <div class="projects_label">
                                        <img class="label_img" src="./assets/images/check.svg" /> 
                                        <span class="projects_label_en">Deployment</span>
                                    </div>
                                    <div class="projects_value">
                                        Netlify
                                    </div>
                                </div>
                                <div class="projects_description">
                                    <div class="projects_label">
                                        <img class="label_img" src="./assets/images/check.svg" /> 
                                        <span class="projects_label_en">IDE</span>
                                    </div>
                                    <div class="projects_value">
                                        Visual Studio Code
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            <section class="projects">
                <div class="projects_container">
                    <div class="projects_title">GongCha</div>
                    <div class="projects_period">2022.07&nbsp;~&nbsp;2022.11&nbsp;(3人 팀 프로젝트)</div>
                    <div class="projects_info">
                        <div class="projects_img-carousel2">
                            <div id="carouselExampleAutoplaying2" class="carousel slide" data-bs-ride="carousel">
                                <div class="carousel-indicators">
                                    <button type="button" data-bs-target="#carouselExampleAutoplaying2" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                                    <button type="button" data-bs-target="#carouselExampleAutoplaying2" v-for="index in 14" :key="index" :data-bs-slide-to="[index]" :aria-label="'Slide '+ (index+1)" ></button>
                                    <button type="button" data-bs-target="#carouselExampleAutoplaying2" data-bs-slide-to="15" aria-label="Slide 16"></button>
                                </div>
                                <div class="carousel-inner">
                                    <div class="carousel-item active">
                                        <img src="./assets/images/Gongcha/1.png" class="d-block w-100" alt=".">
                                    </div>
                                    <div v-for="(image, index) in images2" :key="index" class="carousel-item">
                                        <img :src="image" class="d-block w-100">
                                    </div>
                                </div>
                                <button class="carousel-control-prev position" type="button" data-bs-target="#carouselExampleAutoplaying2" data-bs-slide="prev">
                                    <span class="carousel-control-prev-icon icon-color" aria-hidden="true"></span>
                                    <span class="visually-hidden">Previous</span>
                                </button>
                                <button class="carousel-control-next position" type="button" data-bs-target="#carouselExampleAutoplaying2" data-bs-slide="next">
                                    <span class="carousel-control-next-icon icon-color" aria-hidden="true"></span>
                                    <span class="visually-hidden">Next</span>
                                </button>
                            </div>
                        </div>
                        <div class="projects_descriptions2">
                            <div class="projects_main-descriptions2">
                                <b>공차는 여러 사람들과 함께 해야하는 풋살을 보다 쉽게 즐길 수 있게 도와주는 웹사이트</b>입니다.
                                주요 서비스로는 개인이나 소수의 사용자가 경기를 예약할 수 있는 서비스인 <b>소셜매치</b>,
                                팀이 있는 사용자가 구장을 대관할 때 사용하는 서비스인 <b>구장 예약</b>,
                                경기가 있는 사용자가 충원 공고를 올리는 게시판인 <b>용병 모집</b>으로 구성 하였습니다.
                                <p></p>
                                처음으로 <span class="projects_red">Git</span>을 이용하여 다른 사람들과 협업을 해보며,
                                <span class="projects_red"> HTML, CSS, Javascript</span>와 여러 <span class="projects_red">API, 라이브러리</span>를
                                연동하여 UI를 구현하였고,<span class="projects_red"> Java, Spring Framework</span>를 함께 배우면서 웹개발의 프론트엔드와 백엔드의 기본 지식을
                                쌓을 수 있었던 프로젝트 입니다. 또한 저에게 웹개발에 대한 매력을 알게해준 계기이기도 합니다.
                                <p></p>
                            </div>
                            <div class="projects_description_container">
                                <div class="projects_description">
                                    <div class="projects_label">
                                        <img class="label_img" src="./assets/images/check.svg" /> 주요기능
                                    </div>
                                    <div class="projects_value">
                                       회원가입, 로그인, 마이페이지 (회원정보 관리,캐쉬충전/충전내역), 소셜매치, 구장예약, 용병모집 (게시판 글등록/수정/삭제, 댓글등록/수정/삭제)
                                    </div>
                                </div>
                                <div class="projects_description">
                                    <div class="projects_label">
                                        <img class="label_img" src="./assets/images/check.svg" /> 
                                        <span class="projects_label_en">GitHub</span>
                                    </div>
                                    <div class="projects_value">
                                        <a class="projects_url" href="https://github.com/Jaegeul/Gongcha" target="_blank">github.com/Jaegeul/Gongcha</a>
                                    </div>
                                </div>
                                <div class="projects_description">
                                    <div class="projects_label">
                                        <img class="label_img" src="./assets/images/check.svg" /> 
                                        <span class="projects_label_en">Frontend</span>
                                    </div>
                                    <div class="projects_value">
                                        HTML/CSS, jQuery, Bootstrap
                                    </div>
                                </div>
                                <div class="projects_description">
                                    <div class="projects_label">
                                        <img class="label_img" src="./assets/images/check.svg" /> 
                                        <span class="projects_label_en">Backend</span>
                                    </div>
                                    <div class="projects_value">
                                        Java(JDK 1.8), Spring Framework, Mybaits
                                    </div>
                                </div>
                                <div class="projects_description">
                                    <div class="projects_label">
                                        <img class="label_img" src="./assets/images/check.svg" /> 
                                        <span class="projects_label_en">Detabase</span>
                                    </div>
                                    <div class="projects_value">
                                        Oracle
                                    </div>
                                </div>
                                <div class="projects_description">
                                    <div class="projects_label">
                                        <img class="label_img" src="./assets/images/check.svg" /> 
                                        <span class="projects_label_en">IDE</span>
                                    </div>
                                    <div class="projects_value">
                                        Eclipse, SQL Developer
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
        </main>
    </div>
</div>
</template>

<script>
export default {
  data() {
    return {
        images1: [
            require('./assets/images/portfolio/2.png') ,
            require('./assets/images/portfolio/3.png') ,
            require('./assets/images/portfolio/4.png') ,
            require('./assets/images/portfolio/5.png') 
        ],
        images2: [
            require('./assets/images/Gongcha/2.png') ,
            require('./assets/images/Gongcha/3.png') ,
            require('./assets/images/Gongcha/4.png') ,
            require('./assets/images/Gongcha/5.png') ,
            require('./assets/images/Gongcha/6.png') ,
            require('./assets/images/Gongcha/7.png') ,
            require('./assets/images/Gongcha/8.png') ,
            require('./assets/images/Gongcha/9.png') ,
            require('./assets/images/Gongcha/10.png') ,
            require('./assets/images/Gongcha/11.png') ,
            require('./assets/images/Gongcha/12.png') ,
            require('./assets/images/Gongcha/13.png') ,
            require('./assets/images/Gongcha/14.png') ,
            require('./assets/images/Gongcha/15.png') ,
            require('./assets/images/Gongcha/16.png') 
        ]
    }
  },
  mounted() {
    window.addEventListener('scroll', this.handleScroll);
    this.handleScroll(); // 초기 로딩 시 스크롤 이벤트 트리거
  },
  beforeUnmount() {
    window.removeEventListener('scroll', this.handleScroll);
  },
  methods: {
    handleScroll() {
      const winHeight = window.innerHeight;
      const scrollItems = [
        this.$refs.scrollItem1,
        this.$refs.scrollItem2,
        this.$refs.scrollItem3,
        this.$refs.scrollItem4,
        this.$refs.scrollItem5,
      ];

      scrollItems.forEach(el => {
        const rect = el.getBoundingClientRect();
        if (rect.top <= winHeight && rect.bottom >= 0) {
          el.classList.add('active');
        } else {
          el.classList.remove('active');
        }
      });
    },
  },
};
</script>

<style>

@import "./assets/css/main.css";

</style>
