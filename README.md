# whyhellothere! I'm Eduardo Tioma aka @edukure

## 💬 About me

I started programming with C# back in 2018 developing desktop applications, but in early 2021 Next.js showed me how easy I could build frontend (even fullstack) software. Since then I've been studying frontend development with React and Next.js.

🎓 I'm in the end of my graduation in Biomedical Engineering at the Universidade Federal de Uberlândia.
Even though I find many things about this field interesting, I feel happier coding and studying about software development.

## 📬 How to reach me

[![Linkedin: Eduardo Tioma](https://img.shields.io/badge/-Eduardo%20Tioma-blue?style=flat&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/eduardo-tioma-b036a4170/)](eduardo-tioma)
[![Gmail Badge](https://img.shields.io/badge/-tioma.eduardo@gmail.com-006bed?style=flat&logo=Gmail&logoColor=white&link=mailto:SEU-EMAIL)](mailto:tioma.eduardo@gmail.com)
[![GitHub edukure](https://img.shields.io/github/followers/edukure?label=follow&style=social)](edukure)

## 💼 Experience

### [Alura](https://www.alura.com.br/)

#### Current: Front-End intern of the Content Team

- I'm contributing to new courses about React and Next.js with TypeScript
- I'll start writing articles about topics I find interesting about those tecnologies soon

#### Advanced Front-End Bootcamp (Next.js)

- Spent 3 months dedicated to this bootcamp in which my primary responsability was helping students and explaining concepts that they didn't quite understand with video lessons only. The main subject of the course was Next.js, but I also helped filling the gaps related to React and Front-End as a whole.
- Every module (2 weeks), I wrote about problems the students could face and gave them tips about how they could solve them.
- With the help of other interns, I reviewed student's projects and helped choosing which ones would be showcased.

#### Scuba Team intern

- Spent a few months just answering basic questions of HTML, CSS and JavaScript. I didn't go beyond the basics, but this taught me how to explain
  concepts in a simple manner for beginners to understand.
- Studied React and Next.js when I could

## 🧠 Currently learning

### 👉 Next.js + Typescript

Next.js is just amazing to work with and TypeScript makes me feel safer while writing code.

### 👉 Supabase

I'm not proficient in developing backends, so supabase helps a lot.

### 👉 Redis

I'm using Redis to cache limit rated API responses in a personal project. It was so easy to add to an existing project and using it has been very pleasent.

## ❗ What I want to learn next

### [tRPC](https://trpc.io/) and [Prisma](https://www.prisma.io/)

Even with TypeScript, I still face some problems regarding type safety in my projects. Next's APIs routes are amazing, but at the moment we still have to define an Interface or Type to help with intellisense while consuming the endpoints we created (or just live in the dark like js 🤷‍♂️).

With supabase I have a similar problem: I can create databases really quickly but I still have to create interfaces or types myself.

It's not hard to do so, but the problem is that I now have 2 sources of truth in both cases. So if I make a change to the API response or the database tables/fields I'll have to update their types manually 😡. Again, that's not hard but it definitely opens up space for mistakes regarding type safety.

Prisma will allow me to create tables that are tied to the types I declared in my code. If I update that type, the database will follow and its queries will be typed without more effort.

With tRPC it's possible to _infer_ API response's types instead of _declaring_ them. Any changes to the endpoint's response won't need changing its interface because it its **inferred** and that's AWESOME.
