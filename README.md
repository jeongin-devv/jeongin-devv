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
        'JavaScript', 'TypeScript', 'HTML', 'CSS3'
        'React', 'Redux', 'Mobx', 'Material-UI', 'Styled-Compoment',
        'Vue.js', 'Vuex', 'Vuetify', 'JQuery'
      ],
      tools: [
        'vsCode', 'Brackets', 'Eclipse', 'STS',
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
      'Udemy Frontend RoadMap using React',
      'Inflearn Frontend RoadMap using Vue.js',
      'HTA Java developer A course Using egovFrame, Vue.js' 
    ];
  },
  
  getAboutMe(): string {
    return 'Please refer to Notion at the Bottom';
  }
}

```

* Notion : <a href="https://devjeongin.notion.site/Resume-8fd46c435272438d906e8b2957c4b551" target="_blank">Click the Link</a>
