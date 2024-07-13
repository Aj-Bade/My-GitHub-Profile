# GitHub Portfolio


# Installation :arrow_down:

### You will need to download Git and Node to run this project

- [Git](https://git-scm.com/downloads)
- [Node](https://nodejs.org/en/download/)

#### Make sure you have the latest version of both Git and Node on your computer.

```
node --version
git --version
```

## <br />

# Getting Started :dart:

### Fork and Clone the repo

To Fork the repo click on the fork button at the top right of the page. Once the repo is forked open your terminal and perform the following commands

```
git clone https://github.com/<YOUR GITHUB USERNAME>/github-portfolio.git

cd github-portfolio
```

### Install packages from the root directory

```bash
npm install
# or
yarn install
```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

---

# Usage :joystick:

If you want to use Google Analytics, Please create a new `.env` file from `.env.example` file and provide the value.

Eg:

```env
NEXT_PUBLIC_GTM = ""
```


Eg:

```javascript
export const userData = {
  githubUser: "Aj-Bade",
  devUsername: "Aj-Bade",
  github: "https://github.com/Aj-Bade",
  linkedIn: "https://www.linkedin.com/in/ajay-bade/",
  twitter: "https://x.com/Aj_Bade_",
  stackOverflow: "https://stackoverflow.com/",
  leetcode: "https://leetcode.com/",
  resume:
    "https://drive.google.com/file/d/1Z44eJVaTRqUpycP16rPmlGbxeoLvVyDn/view?usp=sharing",
  skills: [
    "React",
    "NextJS",
    "Redux",
    "Express",
    "NestJS",
    "MySql",
    "MongoDB",
    "Postgres",
    "Docker",
    "AWS",
  ],
  timezone: "GMT+5:30",
};
```

---

---

# Packages Used :package:

|   Used Package List   |
| :-------------------: |
|         next          |
|  @next/third-parties  |
|         axios         |
|      react-icons      |
| react-github-calendar |
|         sass          |
|      tailwindcss      |

---

## Disclaimer

In this repository, I have used some open source APIs. All credits go to the owners of those repositories.
