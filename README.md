
## Description

Automating LinkedIn easy apply process.

This is for educational purposes only. I am not responsible if your LinkedIn account gets suspended or for anything else.

## Features

- Filter by experiences (Internship Entry-level Associate Mid-Senior Director Executive).
- Filter by job type (Full-time Part-time Contract Temporary Internship Other Volunteer).
- Filter by on site or remote jobs
- Set the number of jobs limit
- Sort by date or relevant jobs
- Follow posting company
- Save failed jobs locally into a txt file


## Installation

1. Install the dependecies using yarn or npm

```bash
npm install
yarn install
```

2. Create a copy of **.env.example** file and rename it **.env**

3. Edit the **.env** file

```env
EMAIL="your email here"
PASSWORD="your password here"
LOCATION="SomeWhere"
POSITION="TypeScript"
EXPERIENCES="Internship Entry-level Associate Mid-Senior Director Executive"
JOB_TYPES="Full-time Part-time Contract Temporary Internship Other Volunteer"
ON_SITE_OR_REMOTE="On-site Remote Hybrid"
JOBS_LIMIT=100
SORT_BY_DATE=false
FOLLOW_COMPANY=false
NON_APPLIED_JOBS_FILE="jobs.txt"

```

## Execution

To execute this project run :

```bash
  npm start
```

Or

```bash
  yarn start
```

## Build

to build this project run :

```bash
  npm run build
```

Or

```bash
  yarn build
```

## Feedback

If you have any feedback, please reach out to me at wassim.elbakkouri@yahoo.com
