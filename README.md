# Online-Banking-Platform
<img align="left" src="https://github.com/adrianhajdin/banking/assets/151519281/3c03519c-7ebd-4539-b598-49e63d1770b4" alt="Alierenkayhan" width ="100%" height = "auto"/></p>

# <h1 align="center" > Online Banking Paltform with React  </h1>

<br />
<div align="center">
  <p align="center">
    👨‍💻 This application is made with React and Next.JS 👨‍💻
    <br />
    <a href="https://github.com/Alierenkayhan/Online-Banking-Platform"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/Alierenkayhan/Online-Banking-Platform/issues">Report Bug</a>
    ·
    <a href="https://github.com/Alierenkayhan/Online-Banking-Platform/issues">Request Feature</a>
  </p>
</div>

## 📋 <a name="table">Table of Contents</a>

1.  ℹ [Description](#description)
2. 🤖 [Introduction](#introduction)
3. ⚙️ [Tech Stack](#tech-stack)
4. 🏁 [Getting Started](#getting-started)
   1. 🔋 [Features](#features)
   2. 💡 [Prerequisites](#pre-requisites)
   3. ⚙️ [Installation](#installation)
5. 🧐 [Contributing](#contributing)
6. 🤩 [Resources](#resources)

## <a name="description">ℹ️ Description</a> 

From Youtube Tutorial => https://www.youtube.com/watch?v=DwbwuYYiBTk

Docker Hub repo => https://hub.docker.com/r/alieren/online_banking_platform

Docker file dan container build etme
docker build -t online_banking_platform_tutorial:latest .

Docker file'ı çalıştırma
docker run -p 3000:3000 online_banking_platform_tutorial:latest

Container'ı Durdurma
docker ps
docker stop <CONTAINER_ID>

Docker Hub a gönderme için
Docker Hub'da Giriş Yapma => docker login
Docker İmajı Etiketleyin => docker tag online_banking_platform_tutorial:latest alieren/online_banking_platform:1.0.0

## <a name="introduction">🤖  Introduction</a> 
Built with Next.js, Horizon is a financial SaaS platform that connects to multiple bank accounts, displays transactions in real-time, allows users to transfer money to other platform users, and manages their finances altogether.

## <a name="tech-stack">⚙️  Tech Stack</a>

* <img align="left" src="https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white" /> 
* <img align="left" src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white" /> 
* <img align="left" src="https://img.shields.io/badge/Appwrite-%23FD366E.svg?style=for-the-badge&logo=appwrite&logoColor=white" /> 
* Plaid
* Dwolla
* <img align="left" src="https://img.shields.io/badge/React%20Hook%20Form-%23EC5990.svg?style=for-the-badge&logo=reacthookform&logoColor=white" /> 
* <img align="left" src="https://img.shields.io/badge/zod-%233068b7.svg?style=for-the-badge&logo=zod&logoColor=white" /> 
* <img align="left" src="https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white" /> 
* <img align="left" src="https://img.shields.io/badge/chart.js-F5788D.svg?style=for-the-badge&logo=chart.js&logoColor=white" /> 
* ShadCN 

## <a name="getting-started">🏁 Getting Started</a>
### <a name="features">🔋 Features</a>

👉 **Authentication**: An ultra-secure SSR authentication with proper validations and authorization

👉 **Connect Banks**: Integrates with Plaid for multiple bank account linking

👉 **Home Page**: Shows general overview of user account with total balance from all connected banks, recent transactions, money spent on different categories, etc

👉 **My Banks**: Check the complete list of all connected banks with respective balances, account details

👉 **Transaction History**: Includes pagination and filtering options for viewing transaction history of different banks

👉 **Real-time Updates**: Reflects changes across all relevant pages upon connecting new bank accounts.

👉 **Funds Transfer**: Allows users to transfer funds using Dwolla to other accounts with required fields and recipient bank ID.

👉 **Responsiveness**: Ensures the application adapts seamlessly to various screen sizes and devices, providing a consistent user experience across desktop, tablet, and mobile platforms.

and many more, including code architecture and reusability. 


### <a name="pre-requisites">💡 Prerequisites</a>
  ```sh
  VS Code 
  Git
  Node.js
  node --version v20.10.0
  npm
  ```


### <a name="installation">⚙️ Installation</a>
1. To Get Started, Fork this repository to your GitHub account:
2. Clone the repo from your account using:
   ```sh
   git clone https://github.com/Alierenkayhan/Online-Banking-Platform.git
   ```
3. Open the project on Vs Code and go to the project directory 
   ```sh
   cd Online-Banking-Platform
   ```
4. Npm install
   ```sh
   npm install
   ```
5. Create a new file named .env in the root of your project and add the following content:

    ```env
    #NEXT
    NEXT_PUBLIC_SITE_URL=
    
    #APPWRITE
    NEXT_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
    NEXT_PUBLIC_APPWRITE_PROJECT=
    APPWRITE_DATABASE_ID=
    APPWRITE_USER_COLLECTION_ID=
    APPWRITE_BANK_COLLECTION_ID=
    APPWRITE_TRANSACTION_COLLECTION_ID=
    APPWRITE_SECRET=
    
    #PLAID
    PLAID_CLIENT_ID=
    PLAID_SECRET=
    PLAID_ENV=
    PLAID_PRODUCTS=
    PLAID_COUNTRY_CODES=
    
    #DWOLLA
    DWOLLA_KEY=
    DWOLLA_SECRET=
    DWOLLA_BASE_URL=https://api-sandbox.dwolla.com
    DWOLLA_ENV=sandbox
    
    ```
Replace the placeholder values with your actual respective account credentials. You can obtain these credentials by signing up on the [Appwrite](https://appwrite.io/?utm_source=youtube&utm_content=reactnative&ref=JSmastery), [Plaid](https://plaid.com/) and [Dwolla](https://www.dwolla.com/)

6. Run the server
   ```sh
   npm run dev
   ```
7. Open http://localhost:3000 in your browser to view the project.


See the [open issues](https://github.com/Alierenkayhan/Online-Banking-Platform/issues) for a full list of proposed features (and known issues).
 

## <a name="contributing">🧐 Contributing</a>

Pull requests are **accepted**. For major changes, please open a thread to discuss what you want to change first.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch 
3. Commit your Changes 
4. Push to the Branch 
5. Open a Pull Request
  
## <a name="links">🔗 Links</a>
Assets used in the project can be found [here](https://drive.google.com/file/d/1TVhdnD97LajGsyaiNa6sDs-ap-z1oerA/view?usp=sharing)

Tutorial video that I follow: 

<a href="https://youtu.be/PuOVqP_cjkE?feature=shared" target="_blank"><img src="https://github.com/sujatagunale/EasyRead/assets/151519281/1736fca5-a031-4854-8c09-bc110e3bc16d" /></a>

## <a name="resources">🤩 Resources</a>
Based on "Build and Deploy a Banking App with Finance Management Dashboard Using Next.js 14" video by [**JavaScript Mastery**](https://www.youtube.com/watch?v=DwbwuYYiBTk).
Image from [**adrianhajdin**](https://github.com/adrianhajdin/banking).