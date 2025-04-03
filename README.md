[![Discord](https://img.shields.io/badge/Discord-%237289DA.svg?logo=discord&logoColor=white)](https://discord.gg/XqntKQ2JP7) [![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/sn0wdev) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/clement-ozor) [![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?logo=Twitter&logoColor=white)](https://twitter.com/Sn0wDev__) 

```typescript
interface Sn0wData {
  languages: string[]
  tech: string[]
  situation: {
    status: 'student' | 'freelance' | 'employee'
    company: string
    location: string
    internship?: {
      company: string
      location: string
    }
  }
}

const aboutMe: Required<Sn0wData> = {
  languages: ['JavaScript', 'TypeScript', 'HTML', 'CSS', 'PHP', 'SQL', 'C', 'C++'],
  tech: ['React', 'Next.js', 'Node.js', 'Express', 'MongoDB', 'MySQL', 'Git', 'Prisma', 'Ant Design', 'Chakra UI'],
  situation: {
    status: 'student',
    company: 'Epitech',
    location: 'Montpellier, France',
    internship: {
      company: 'Thales',
      location: 'Genneviliers, France',
    },
  },
}

```

![](https://github-readme-stats.vercel.app/api?username=Sn00ww&theme=dark&hide_border=false&include_all_commits=false&count_private=false)<br/>

<img src="https://rm.up.railway.app/" width="512px"/>
