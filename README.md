# Aurganza - Electronics eCommerce Shop With Admin Dashboard in Next.js and Node.js

**Aurganza** is a **free eCommerce store** developed using Next.js, Node.js, and MySQL. The application is custom-built from scratch with a responsive design. Aurganza is a modern online shop that specializes in selling various types of electronic products. The goal of the project is to create a modern web application **by following key stages in software engineering**.  
I, **Farhan Mallick**, developed this online shop as part of my project with detailed software engineering documentation. The project follows a systematic approach to building an eCommerce platform and provides a fully functional admin dashboard.

## 2. Software Engineering Process

During the design and modeling of the software, we decided to use the **cascade model** (waterfall model). We decided on it considering its simplicity, easy project monitoring, and easy application of the model. The cascade model is probably the oldest published model. It was first published in 1970 and represents a high level of abstraction. The stages in the model are connected in cascade, and the model itself is organized so that the next level is passed only after the completion of the previous level.

### 2.1. Defining Milestones

Milestones are key events in the project that show us by what date something must be finished. At this stage, we defined our milestones for every stage in our software engineering process.

### 2.2. Plaky - Project Management Application

The Plaky application was used for project management and project tracking. It is a free application that facilitates collaboration between team members and enables easy export of project reports in one click.

## 3. Requirements Analysis

### 3.1. Software Requirements Specification

At this stage, we defined all our functional and non-functional software requirements regarding the whole application. Also, we defined requirements that define the connections of the system with the environment and performance requirements that the system should meet.

### 3.2. Modeling the System with a Use Case Diagram

The Use Case Diagram represents a detailed description of the functionality of the system in different situations. It describes the steps and actors involved in each situation. The use case diagram is used as a basis for further design, implementation, and testing of the software.

## 4. System Design

System design is the software engineering stage that transforms concepts and requirements into tangible software structures. It is the strategic process of defining the architecture, components, and interactions of a software system to fulfill specific functional and non-functional requirements. In this stage, we wrote about the type of system architecture. We defined our front-end and back-end and wrote about the structure of the front-end and back-end in our application. We defined our data structures, database structures, and important types in our application.

## 5. Software Implementation

Software implementation is the process of converting a software design into a functional software system. This is where all programming should begin.  
When you are in the software implementation stage, it is important to take care of the internal documentation. This documentation includes headers and comments that provide basic information about the component and explanations of specific parts of the code. Thanks to these elements, we are easier to manage in code and better understand what we have done, which contributes to more efficient work and maintaining software projects.

## 6. Testing

Testing is a formal process that is performed by the testing team with the aim of determining the logical correctness and purposefulness of the tested program. The importance of testing is great because it significantly reduces the losses that software companies have due to errors and failure of software incurred after its delivery to the customer. **We have done the entire testing process manually and documented everything in detail.**

The test scripts represent the instructions from which it is clearly seen step-by-step how the testing was performed. They provide full control over testing, so if some errors or cancellations occur, testing conditions can be repeated, and the system can again lead to that error or cancellation. This is necessary to establish the cause of the problem.  
As the above image shows, we documented each of our test examples in terms of test ID, input data, instruction, expected result, actual result, additional comment, component, method, and testing technique. Currently, our test script has over 350 manually tested examples.

During the software testing process, we documented each error found in the error report form. As shown in the image above, each error has its own unique error ID and a detailed description of the error containing: date of identifying an error, date of troubleshooting an error, error priority, type of error, file name, and testing phase.

### 6.1. Ad hoc Testing

The first step in software testing after each newly added functionality in our application was ad hoc testing. The ad hoc testing takes place in an unofficial atmosphere. The developer presents the code to the rest of the group, and then the discussion occurs. The members of the group ask questions, the developer responds to them, together they analyze individual implementation aspects that they consider significant and try to find mistakes.  
We have applied this method by examining the code after each new added functionality and had long discussions about it and the potential problems that may occur.

### 6.2. Component System Hierarchy

The component system hierarchy of the application components is a complete sketch of all components in our application created in the Figma design tool. This sketch is very important to us when testing because it represents an insight into the order of the component testing. The below image represents our component system hierarchy from the bird's-eye view:

### 6.3. Unit Testing

Unit testing for our application includes the process of testing individual functionalities or application components to ensure each of them works properly independently. The goal of unit testing is to identify and correct errors in the early stages of development, increase the reliability of code, and facilitate future application maintenance.

As the image above shows, we found a total of 75 errors in unit tests of 103 total errors found, which in our testing, unit testing had the highest efficiency with 72.8%. During unit testing, we used the black-box and white-box methods. The techniques we used for testing were:

The black-box method:
1. Equivalence partitioning
2. Boundary Value Analysis – BVA

The white-box method:
1. Statement coverage
2. Decision coverage
3. Condition coverage

### 6.4. Integration Testing

In integration testing, we used the approach "Integration from the bottom to top". This is a widely used approach in integration testing. This method starts from the components of the system organized in the hierarchy on which the main program is located. Testing starts by unit testing all components located at the lowest level in the hierarchy. The components are then tested at the next level that calls previously tested components.

As the image above shows, we found a total of 28 errors in integration testing of 103 total errors found, which in our testing, integration testing had an efficiency with 27.2%.

### 6.5. End-to-End Testing

End-to-end testing is the highest, final level of testing. It checks whether the system, as a whole, acts in accordance with the specification of the requests set by the customer. Since most functional requirements have already been verified at lower levels of testing, the emphasis is now on non-functional requirements, such as speed, reliability, and efficiency.

### 6.6. Error Records at a Specified Time Interval

During testing, we recorded the found mistakes by days. The next diagram helped us know how to track our testing progress.

As the image above shows, the number of errors increases day by day, so testing must continue. Throughout 4 days of testing, we managed to find a total of 103 errors.

### 6.7. Analysis of Errors Found

During testing, we also conducted the error report form that we have already mentioned in the introductory chapter on testing. This document has helped us significantly in order to document all the most common types of mistakes in our application, which shows the image below.

## Aurganza – Key Features

Aurganza is a Next.js and Node.js full-stack e-commerce website with a **free source code**. Our application comes with the fully functional **admin panel** and it is fully open-source. Our **free online store website** is completely responsive and manually tested. You can use our e-commerce project as a template or boilerplate for your next project. Our ecommerce shop template and Next.js ecommerce theme are fully customized for all your needs. It is available for **free download** and can be used as an e-commerce example for all your future projects.

### Is Next.js good for eCommerce?

Next.js is currently one of the best ways for developing custom eCommerce solutions. Its benefits include improved performance, SEO-friendliness, easy development and deployment, excellent developer experience, and the ability to handle versatile and scalable projects. By leveraging Next.js, developers can create compelling web applications that deliver an exceptional user experience while maintaining optimal performance.

## Instructions

1. To run the app, you first need to download and install Node.js and npm on your computer. Here is a link to the tutorial that explains how to install them: [Install Node.js](https://www.youtube.com/watch?v=4FAtFwKVhn0). Also, here is the link where you can download them: [Download Node.js](https://nodejs.org/en).

2. After you have installed Node.js and npm, you need to download and install MySQL on your computer. Here's another tutorial that explains how you can download and install MySQL: [Install MySQL](https://www.youtube.com/watch?v=BxdSUGBs0gM&t=212s). You can download MySQL from the official website: [Download MySQL](https://dev.mysql.com/downloads/installer/).

3. This step is optional but highly recommended if you don't have a database management app. **HeidiSQL** is beginner-friendly and very easy to use for database management. Here's a tutorial that explains how to download and install HeidiSQL: [Install HeidiSQL](https://www.youtube.com/watch?v=oJ24MyLeiPs). You can download HeidiSQL from: [Download HeidiSQL](https://www.heidisql.com).

4. Once you have installed all the programs you need on your computer, you need to download the project files. After downloading, extract the project files into a folder on your computer.

5. After extracting the project, open the project folder in your preferred code editor (e.g., VS Code). In the root directory of the project, create a new file named `.env`.

6. Inside the `.env` file, add the following code (replace `username` and `password` with your MySQL credentials):

   ```bash
   DATABASE_URL="mysql://username:password@localhost:3306/aurganza_nextjs"
   NEXTAUTH_SECRET=12D16C923BA17672F89B18C1DB22A
   NEXTAUTH_URL=http://localhost:3000

7. After you do it, you need to create another `.env` file in the `server` folder and put the same `DATABASE_URL` you used in the previous `.env` file:

   ```bash
   DATABASE_URL="mysql://username:password@localhost:3306/aurganza_nextjs"

8. Now you need to open your terminal of choice in the root folder of the project and run the following command to install the dependencies:

   ```bash
   npm install

9. Then, navigate to the `server` folder and install the dependencies for the server:

   ```bash
   cd server
   npm install

10. You will now need to run the Prisma migration. In the `server` folder, run the following command:

   ```bash
   npx prisma migrate dev
 ```

11. Once the migration is complete, you need to insert demo data into the database. To do this, go to the `server/utils` folder and run the `insertDemoData.js` script:

   ```bash
   cd utils
   node insertDemoData.js
 ```


12. After the demo data is inserted, go back to the `server` folder and start the backend server:

   ```bash
   cd ..
   node app.js
 ```


13. While your backend server is running, open another terminal window (do not stop the backend). In the second terminal, navigate to the root project folder and run the following command to start the front-end:

   ```bash
   npm run dev
 ```


14. Finally, open your browser and visit [http://localhost:3000](http://localhost:3000) to see the app running live!
