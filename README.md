```JavaScript
class Profile extends Me {

  name_kor: 'Jeongin.Oh' ;
  name_eng: 'Zayden.Oh' ;
  
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
        position: 'Developer'
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

* Notion (Eng) : <a href="https://devjeongin.notion.site/Resume-8fd46c435272438d906e8b2957c4b551" target="_blank">Click the Link</a>
* Web Resume (Kor) : <a href="https://jeongin-devv.github.io" target="_blank">Click the Link</a>

