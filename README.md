# Hi, I'm Edwin

Software Engineer at Accredify, Singapore.

Full stack developer building reliable, maintainable web applications.

## What I work with

- **Backend:** PHP, Laravel, REST APIs, MySQL
- **Frontend:** JavaScript, TypeScript, React, Inertia.js
- **Cloud & DevOps:** AWS, Docker, GitLab CI/CD, GitHub Actions, GCC, SHIP-HATS
- **Testing & quality:** Unit testing, K6, SonarQube, Nexus IQ, Fortify, visual regression testing

## Highlights


### Serverless PDF Generation

**Tech Stack:** Laravel · Laravel Queues · AWS SDK · AWS Lambda · Puppeteer · Amazon S3

Designed and implemented a queue-based, serverless PDF generation workflow to offload resource-intensive HTML-to-PDF processing from the main application.

- **Architecture:** Used Laravel Queues to process PDF generation requests in the background without blocking application requests.
- **Integration:** Invoked AWS Lambda synchronously through the AWS SDK from queued Laravel jobs.
- **Processing & Storage:** Generated PDF documents using Puppeteer within Lambda and stored the resulting files in Amazon S3.
- **Impact:** Offloaded resource-intensive PDF rendering from the main application, improving workload isolation and keeping document generation out of the user-facing request flow.



### Automated Visual Regression Testing

**Tech Stack:** React.js · Storybook · Loki · AWS Lambda · Amazon S3 · CI/CD

Designed and implemented automated visual regression testing to remove manual checking of different document templates written in React.js.

- **Architecture:** Catalogued the list of design templates in Storybook, so each template could be tested consistently in one place.
- **Integration:** Used Loki for visual regression testing, with AWS Lambda and Amazon S3 supporting the test workflow and image storage.
- **CI/CD Integration:** Integrated the visual regression test into the CI/CD pipeline, so it runs automatically whenever a pull request is created.
- **Testing:** Compared generated documents against reference images to detect unintended document layout changes.
- **Impact:** Removed the need to manually check each document template, while automatically catching unintended layout changes before they reached users.

