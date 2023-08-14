<!-- About the Project -->
## About kk-app
Small ERP for transportation companies that allows drivers to save information about cargo. The project consists of a web dashboard for supervisors, an Android app for drivers and a backend used by forementioned services.



<!-- TechStack -->
### Tech Stack

<details>
  <summary>Web</summary>
  <ul>
    <li>React</li>
    <li>TypeScript</li>
    <li>Next.js 13</li>
    <li>Tailwind CSS</li>
  </ul>
</details>

<details>
  <summary>Mobile</summary>
  <ul>
    <li>Kotlin</li>
    <li>JetPack Compose</li>
    <li>Retrofit2</li>
  </ul>
</details>

<details>
  <summary>Server</summary>
  <ul>
    <li>Java</li>
    <li>Spring Boot</li>
    <li>MariaDB</li>
  </ul>
</details>

<details>
<summary>DevOps</summary>
  <ul>
    <li>Git</li>
    <li>GitHub Actions</li>
    <li>Docker</li>
  </ul>
</details>

<details>
<summary>Cloud</summary>
  <ul>
    <li>EC2</li>
    <li>S3</li>
    <li>ECS</li>
    <li>ECR</li>
    <li>Lambda</li>
  </ul>
</details>

### AWS Diagram
<img src="assets/aws.png"/>

## Todo

#### Mobile
* [ ] Finish authentication
* [x] Add http request caching
* [x] Implement in-app updating
   
#### Web
* [ ] Implement JWT authentication
* [ ] Generic table component with filtering and pagination
* [ ] Deploy on AWS
* [x] Switch to Next.js 13
* [x] Switch to Tailwind CSS  

#### Backend
* [ ] Read cargo information from receipts using OCR
* [x] Serve mobile app apks from S3 bucket
* [x] Controller level exception handling
