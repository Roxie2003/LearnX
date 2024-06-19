# Build an LMS Platform: Next.js 13, React, Stripe, Mux, Prisma, Tailwind, MySQL | Full Course 2023

This is a repository for Build an LMS Platform: Next.js 13, React, Stripe, Mux, Prisma, Tailwind, MySQL | Full Course 2023

Key Features:

- Browse & Filter Courses
- Purchase Courses using Stripe
- Mark Chapters as Completed or Uncompleted
- Progress Calculation of each Course
- Student Dashboard
- Teacher mode
- Create new Courses
- Create new Chapters
- Easily reorder chapter position with drag n’ drop
- Upload thumbnails, attachments and videos using UploadThing
- Video processing using Mux
- HLS Video player using Mux
- Rich text editor for chapter description
- Authentication using Clerk
- ORM using Prisma
- MongoDB database

### Prerequisites

**Node version 18.x.x**

### Cloning the repository

```shell
git clone https://github.com/Roxie2003/learn_x.git
```

### Install packages

```shell
npm i
```

### Setup .env file

```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=

DATABASE_URL=

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

MUX_TOKEN_ID=
MUX_TOKEN_SECRET=

STRIPE_API_KEY=
NEXT_PUBLIC_APP_URL=http://localhost:3000
STRIPE_WEBHOOK_SECRET=

NEXT_PUBLIC_TEACHER_ID=
```

### Setup Prisma

Add Mongo Database

```shell
npx prisma generate
npx prisma db push

```

### Populate Database
Populate the database

```shell
node scripts/seed.ts
```

### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command | description                              |
| :------ | :--------------------------------------- |
| `dev`   | Starts a development instance of the app |
"# LearnX" 

## Screenshots
### 1.Student View 

1. Search All Courses
![image](https://github.com/Roxie2003/LearnX/assets/59964427/872ff548-4ea7-435c-a777-cd95afae714c)

2. View Course
![image](https://github.com/Roxie2003/LearnX/assets/59964427/ab85867d-9a31-40c9-8fd6-33c80f4817d6)

3. Buy Course with Stripe
![image](https://github.com/Roxie2003/LearnX/assets/59964427/2e458abf-6c01-4501-9a09-354f1d66435d)

### 2. Teacher View

1. Teacher Dashboard for all courses
![image](https://github.com/Roxie2003/LearnX/assets/59964427/2a7b38cc-21bb-490a-a7ba-116c1f48edcb)

2. Create new Course
![image](https://github.com/Roxie2003/LearnX/assets/59964427/d2ca194f-dfb9-4972-a0b4-e5f199c33a32)

3. Create Course Form
![image](https://github.com/Roxie2003/LearnX/assets/59964427/6b3b3511-b257-400a-9d4d-8da82eff4643)

4. Publish Course 
![image](https://github.com/Roxie2003/LearnX/assets/59964427/733cbf53-131b-48c3-81d9-b1cbe784fb4f)



