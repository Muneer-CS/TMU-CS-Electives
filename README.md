# Elective Atlas

Elective Atlas is a student-friendly guide to elective options for Toronto Metropolitan University Computer Science students. It brings lower liberals, upper liberals, open electives, and core electives into one searchable interface.

## Live website

[Open Elective Atlas](https://muneer-cs.github.io/TMU-CS-Electives/)

## Features

- Search by course code, title, topic, or description
- Browse 130 Lower Liberal Studies courses
- Browse 237 Upper Liberal Studies courses
- Explore 3,550 Open Elective options not explicitly excluded for Computer Science students
- Review 105 Core Elective options across the official Computer Science, Engineering/Science/Business, and Mathematics groups
- View prerequisites, corequisites, antirequisites, restrictions, and official TMU source links
- Filter by inferred topic tags and core-elective group
- Responsive layout for desktop and mobile devices

## Data and evidence

The dataset is based on the official TMU 2026-2027 Undergraduate Calendar. It was cross-checked against:

- The Computer Science program curriculum
- Computer Science core-elective tables
- Lower Level Liberal Studies Table A
- Upper Level Liberal Studies Table B
- Open Elective rules and exclusions
- Individual official TMU course records

The repository currently contains 3,971 unique course records. Topic tags are editorial inferences based on official titles and descriptions; they are not official TMU classifications.

## Important note

Elective Atlas is an independent student project and is not affiliated with or endorsed by Toronto Metropolitan University. Calendar eligibility does not guarantee that a course is offered in a particular semester or that a student can enrol. Always confirm decisions using the official TMU Undergraduate Calendar and your Academic Advisement Report.

## Local development

Requirements:

- Node.js 22.13 or newer
- pnpm

Install dependencies and start the development server:

```bash
pnpm install
pnpm dev
```

Create and test the GitHub Pages build:

```bash
pnpm test
```

## Author

Created by Muneer Mahmoud.

- [GitHub](https://github.com/Muneer-CS)
- [LinkedIn](https://www.linkedin.com/in/muneer-mahmoud/)

## License

This project is licensed under the [MIT License](LICENSE).
