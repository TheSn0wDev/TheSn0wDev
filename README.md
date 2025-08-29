[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/clement-ozor)

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
  languages: ['JavaScript', 'TypeScript', 'HTML', 'CSS', 'PHP', 'SQL', 'C', 'C++', 'Python'],
  tech: ['React', 'Next.js', 'Node.js', 'Express', 'MongoDB', 'PostgreSQL', 'Git', 'Prisma', 'Shadcn UI', 'TailwindCSS'],
  situation: {
    status: 'employee',
    company: 'Thales',
    location: 'Gennevilliers, France'
  },
}
```

![](https://github-readme-stats.vercel.app/api?username=Sn00ww&theme=dark&hide_border=false&include_all_commits=false&count_private=false)<br/>
