# Test-Conducting-Site
An exam portal to conduct online mcq test
#TechStack
<details>
  <summary>Frontend</summary>
  <ul>
    <li><a href="https://reactjs.org/">React.js</a></li>
    <li><a href="https://www.mui.com">Material UI library</a></li>
    <li><a href="https://html.com/html5/">HTML 5</a></li>
    <li><a href="https://www.css3.com/">CSS 3</a></li>
  </ul>
</details>

<details>
  <summary>Backend</summary>
  <ul>
    <li><a href="https://www.nodejs.org">Node.js</a></li>
    <li><a href="https://www.expressjs.com/">Express.js</a></li>
  </ul>
</details>

<details>
<summary>Database</summary>
  <ul>
    <li><a href="https://www.mongodb.com/">MongoDB</a></li>
  </ul>
</details>
### :dart: Features

- Student User
  - View Tests Details
  - Register for test
  - Give Test
  - Check Result and correct answer and explanation for questions
- Teacher User
  - Create, Update Questions and Question Banks
  - Create, View Test
- Admin User
  - Create and Manage Teacher users
  - Create and Manage subjects

### :running: Run Locally
Go to the project directory

```bash
  cd project-directory
```

Install dependencies

```bash
  cd backend
  npm install
  cd ../frontend
  npm install
  cd ../user-portal-frontend
  npm install
```

Start the backend server

```bash
  cd backend
  npm start
```

Start the frontend client for admin

```bash
  cd frontend
  npm start
```

Start the frontend client for teacher/student

```bash
  cd user-portal-frontend
  npm start
```


<b>Note</b> : admin user is created when backend runs first time. default admin (username, password) details are <b>("sysadmin","systemadmin"). addAdminIfNotFound() function of backend/services/admin.js file </b> is for this logic. You can check/modify default admin details from this function.

### :running: Screenshots
Admin Portal Sign In
![2a0c524d-1f75-458f-96da-16464500e291](https://github.com/SaranshYadav/Test-Conducting-Site/assets/97433080/94967858-c29c-4173-8e32-4d22371baf18)

Admin Dashboard
![83a13ec1-d12f-476f-80dd-3a0973fba047](https://github.com/SaranshYadav/Test-Conducting-Site/assets/97433080/b522e686-cd6f-48e1-a43d-54d748d1a64a)

Adding Teachers
![e7666d7f-edcb-4264-9c8b-1e2efcc4fae1](https://github.com/SaranshYadav/Test-Conducting-Site/assets/97433080/c1015955-ad95-4f8a-a0e6-e2d1d7ba04c6)

Show Teachers
![fe2316b9-4fda-42e1-a774-f64d31c70545](https://github.com/SaranshYadav/Test-Conducting-Site/assets/97433080/5d3ebf85-4657-4d6c-82e2-5267051b31da)

Show Subjects
![067410ba-290a-4ed5-927d-d7871d602ada](https://github.com/SaranshYadav/Test-Conducting-Site/assets/97433080/b0527021-0c67-4988-babf-c1d0c2c93010)

Show Students- provides us with the option to block students too
![72c75899-5822-45c5-9143-69be71a46164](https://github.com/SaranshYadav/Test-Conducting-Site/assets/97433080/6a2f7b59-ecb6-41a3-b727-4d2657e46419)

User-Portal-
Teacher-Sign In
![e30fba5a-5776-4562-b3f2-b62e1c0ddd87](https://github.com/SaranshYadav/Test-Conducting-Site/assets/97433080/7bca8da0-217b-4b2f-bbac-c3ea58992180)

Techer Dashboad Home
![1fe0eafc-a2ed-4c38-94d7-d3d0d1d7fb09](https://github.com/SaranshYadav/Test-Conducting-Site/assets/97433080/6d89fd31-a2d3-4b9e-bbe9-3edb23f8ae8f)

Add Question
![c69f12b7-6a7b-4be3-a88d-cd21f335ca10](https://github.com/SaranshYadav/Test-Conducting-Site/assets/97433080/b67d8b91-bde8-4182-8c5f-d4ec237de7b0)
![587c6586-66b6-4141-8fca-2ed14a118356](https://github.com/SaranshYadav/Test-Conducting-Site/assets/97433080/3a454780-b771-4280-b410-7853c267b764)

Search for question -Also provides with functionality to block questions
![5f243b5b-825a-4948-a90a-93d60d8ccc28](https://github.com/SaranshYadav/Test-Conducting-Site/assets/97433080/6c443c78-d022-47c6-9e2c-3596548c545f)

Create Test-
![7e4aa495-98b8-43fe-93c0-e63eaae95b23](https://github.com/SaranshYadav/Test-Conducting-Site/assets/97433080/cab4e41c-00ae-45ac-a4f8-1c5e7c5712db)
![829d7a8b-e766-44b2-90a3-85a13874882f](https://github.com/SaranshYadav/Test-Conducting-Site/assets/97433080/d47c4cc2-90cf-47e1-a36e-b8b864954a23)

Table for all the tests created-
![d2c2c9f6-1a9d-4592-8ebb-66c33bf57b6c](https://github.com/SaranshYadav/Test-Conducting-Site/assets/97433080/4837aeb9-915d-4917-8b3e-8d2f169297c8)

Functionality for view test-
![50c378c0-f024-48a8-b8cd-d314e750c734](https://github.com/SaranshYadav/Test-Conducting-Site/assets/97433080/6dce0598-f5da-40e5-b6a9-b3ab87737b4d)

Student Portal-
Sign In-
![86c81288-4117-405c-b885-343561468d73](https://github.com/SaranshYadav/Test-Conducting-Site/assets/97433080/39640a5b-3915-4a79-ad09-63f402d0e6c2)

Resgister-
![8a840c04-0e00-49f0-87df-50abd16485f7](https://github.com/SaranshYadav/Test-Conducting-Site/assets/97433080/ba586aa5-3a8c-418f-99a7-7d553f04d530)
![8208a409-e5c2-4f4b-aed6-5ad1cefd4d2b](https://github.com/SaranshYadav/Test-Conducting-Site/assets/97433080/f5ba51c9-6f44-499a-8973-ee5d2e97f1b1)

Student Dashboard-
![bdfbcfa3-b301-42e8-a174-8f826eb97ecf](https://github.com/SaranshYadav/Test-Conducting-Site/assets/97433080/26b4b3f9-787b-423b-aa42-fb5f0a7873bd)

Students View All tests- Students have functionality to view all test and register for those tests.

![2023e65a-04c3-4088-b7e0-cff0f42ab0a5](https://github.com/SaranshYadav/Test-Conducting-Site/assets/97433080/b8903453-1933-42ef-be22-e544b6878fad)
![30fcd7fe-5c40-4ac1-a51a-3339b41994bf](https://github.com/SaranshYadav/Test-Conducting-Site/assets/97433080/da13da7c-0a2b-4df5-af77-2975e94d2a6a)

Students also can take view the upcoming test and attempt it.

![2ec196da-87bf-4b4d-af36-2eec4b5f00a9](https://github.com/SaranshYadav/Test-Conducting-Site/assets/97433080/e3d8b7f3-f6b5-4ddd-a986-b0578b472cb4)


## :gem: Acknowledgements
Following libraries have been used in this projects.

 - [Material UI](https://www.mui.com)
