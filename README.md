```JavaScript
class Profile extends Me {

  name_kor = 'Jeongin.Oh' ;
  name_eng = 'Zayden.Oh' ;
  
  constructor(){
    this.everything : any = true ;
    this.lies : any = false ;
  }
  
  getUsedSkillAndTool(): { skills: skill[], tools: tool[] } {
    return {
      skills: [
        'JavaScript(ES6+)', 'TypeScript', 'HTML', 'CSS3',
        'React', 'Redux', 'Mobx', 'Material-UI', 'Styled-Compoment',
        'Vue.js', 'Vuex', 'Vuetify', 'JQuery'
      ],
      tools: [
        'vsCode', 'Brackets', 'LambdaTest', 'Email on Acid',
        'Jira', 'Confluence', 'Figma', 'Zeplin',
        'GitHub', 'GitLab', 'SVN', 'Postman', 'DBeaver'
      ]
    };
  }
  
  getCareer(): Array<Career> {
    return [
      {
        status: 'Current',
        company: 'Kinemaster',
        department: 'Service Platform Team 1',
        position: 'Frontend Developer'
      },
      {
        status: 'Previous',
        company: 'VinnsMedia',
        department: 'Institute of Technology',
        position: 'Web Full-Stack Developer'
    ];
  },
  
  getEducations(): Array<Education> {
    return [
      'Hongik University Department of Industrial Engineering',
      'Udemy Frontend RoadMap using React & TypeScript',
      'Nomad Coders Frontend RoadMap using React & TypeScript',
      'Inflearn Frontend RoadMap using Vue.js',
      'HTA Java developer A course Using egovFrame, Vue.js' 
    ];
  },
  
  getAboutMe(): string {
    return 'Please refer to Notion at the Bottom';
  }
}

```

* Notion : <a href="https://devjeongin.notion.site/Resume-57d3c3a19fdb44bd9180051590f2784c" target="_blank">Click the Link</a>
* Web Resume : <a href="https://jeongin-devv.github.io" target="_blank">Click the Link</a>

