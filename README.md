## 🦷Project Name: Chi Chu

![Site Introduction](https://user-images.githubusercontent.com/56299114/169871127-de95efcd-9d57-4d92-bb10-4e0e042aed22.png)

`Big Data-based Dental Insurance Recommendation Service`

__What is Chi Chu?__

The name "Chi Chu" is derived from the Korean words for "Chi" (tooth) and "Chu" (recommendation), representing a service that recommends dental insurance.

#### 👆Click to watch the Chi Chu introduction UCC video!

[![Wait a moment](https://user-images.githubusercontent.com/56299114/169869838-92a86c6f-d7d9-4d2c-ba3a-b72c15653d53.gif)](https://youtu.be/4GcdKajfOug)

---

## 🌈Project Overview

- **Chi Chu** is a big data-based dental insurance recommendation service that provides fast and accurate suggestions using **370,000+ insurance contract records**.

- Based on the **Sample Personal Credit Information DB (50,000 users)** provided by the Korea Credit Information Services, the system recommends insurance plans based on **age, gender, insurance category, desired monthly payment, coverage details, and benefit amounts**.

---

#### 💫Tech Stacks & IDE ####

**Frontend**

- <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React" style="zoom:80%;" /><img src ="https://img.shields.io/badge/TypeScript-3178C6.svg?&style=for-the-badge&logo=TypeScript&logoColor=white" alt="TypeScript" style="zoom:80%;"/><img src="https://img.shields.io/badge/Recoil-003545?style=for-the-badge&logoColor=white" alt="MariaDB" style="zoom:80%;" />
- <img src="https://img.shields.io/badge/styled_components-DB7093.svg?style=for-the-badge&logo=styled-components&logoColor=black" alt="styled_components" style="zoom:80%;" /><img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" alt="JavaScript" style="zoom:80%;" /><img src="https://img.shields.io/badge/Chart.js-FF6384.svg?style=for-the-badge&logo=Chart.js&logoColor=black" alt="Chart.js" style="zoom:80%;" />

**Backend**

- <img alt="Python" src ="https://img.shields.io/badge/Python-3776AB.svg?&style=for-the-badge&logo=Python&logoColor=white" style="zoom:80%;"/><img alt="Django" src ="https://img.shields.io/badge/Django-092E20.svg?&style=for-the-badge&logo=Django&logoColor=white" style="zoom:80%;"/><img alt="MySQL" src ="https://img.shields.io/badge/MySQL-4479A1.svg?&style=for-the-badge&logo=MySQL&logoColor=white" style="zoom:80%;"/><img alt="Swagger" src ="https://img.shields.io/badge/Swagger-85EA2D.svg?&style=for-the-badge&logo=Swagger&logoColor=white" style="zoom:80%;"/>
- <img alt="Docker" src ="https://img.shields.io/badge/Docker-2496ED.svg?&style=for-the-badge&logo=Docker&logoColor=black" style="zoom:80%;"/><img alt="NGINX" src ="https://img.shields.io/badge/NGINX-009639.svg?&style=for-the-badge&logo=NGINX&logoColor=black" style="zoom:80%;"/><img alt="Jenkins" src ="https://img.shields.io/badge/Jenkins-D24939.svg?&style=for-the-badge&logo=Jenkins&logoColor=black" style="zoom:80%;"/>

**Big Data Analysis**

- <img alt="pandas" src ="https://img.shields.io/badge/pandas-150458.svg?&style=for-the-badge&logo=pandas&logoColor=white" style="zoom:80%;"/><img alt="Jupyter" src ="https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white" style="zoom:80%;"/>

---

#### 📅Project Duration ####

- 2022.02.21 ~ 2022.04.08

---

#### :bar_chart:Dataset

Data was obtained from the [Open Financial Big Data System](https://credb.kcredit.or.kr:3446/frt/main.do), including **borrower information, insurance contracts, and coverage details** for about 50,000 users.

- **Borrower Info**: Includes ID, age, and gender for 50,000 borrowers

![Borrower Info](https://user-images.githubusercontent.com/56299114/170535418-c1e2e2a5-0844-48cc-a88d-856e75ad66c2.png)

- **Insurance Contracts**: Includes payment frequency, amount, contract period, insurance type, etc.

![Insurance Contract Info](https://user-images.githubusercontent.com/56299114/170535473-25ba0bf9-7e1f-4f3d-9f80-4d6761419095.png)

- **Coverage Info**: Includes detailed coverage codes and corresponding amounts

> ```json
> 💡What is Coverage?
> Coverage refers to the individual options or clauses you choose when signing up for an insurance plan.
> For example, in a cancer insurance plan, you may choose "Cancer Diagnosis", "Cancer Hospitalization", or "Cancer Death" as coverage options.
> If a coverage is not selected during contract signing, the related benefit won’t be paid after an incident.
> In short, coverage represents the individual insurance options you design and select.
> ```

![Coverage Info](https://user-images.githubusercontent.com/56299114/170535478-809869b9-004a-41db-abb9-c5c586b6c2d7.png)
![Insurance Code](https://user-images.githubusercontent.com/56299114/170535487-488bb326-ef17-407f-911f-1429dfa6613f.png)

---

### 0. Landing Page

- Scroll down from top to bottom to explore Chi Chu's services

![Landing Page](https://user-images.githubusercontent.com/56299114/169867005-41b705de-1ab4-4b0a-943b-5545b32fe9fe.gif)

---

### 1. Insurance Search

- Move to the search page from the landing page by clicking a button
- Input gender and date of birth
- Hover over the insurance age tooltip for an explanation

![Search](https://user-images.githubusercontent.com/56299114/169866835-75a07678-1cfe-44f6-bbb9-3e346562f84f.gif)

---

### 2. Search Results Page

- Display cards for matching insurance plans
- Sort results by Chi Chu Index, lowest premium, or most coverage
- Option to view more results

![Sort and More Results](https://user-images.githubusercontent.com/56299114/169866349-eda30e18-2133-49ef-937b-e9ec5930a339.gif)

- Use filters to adjust coverage and premium amounts

- Adjust gender, age, payment term, and contract duration to refine search

![Advanced Search](https://user-images.githubusercontent.com/56299114/169867156-dfd3f5da-7738-47bb-8f70-e75af434ef14.gif)

- At the bottom: Recommendations for users of similar age/gender & high value-for-money plans with high coverage-to-premium ratio

![Bottom Recommendations](https://user-images.githubusercontent.com/56299114/169867178-66dbcd96-ab35-42c4-bfa1-38995abcbbde.gif)

---

### 3. Insurance Detail Page

- View the Chi Chu Index level of a specific plan
- Explanation of the components: Company Index, Product Index, and User Index

![Insurance Detail 1](https://user-images.githubusercontent.com/56299114/169866302-a1f6bb34-af05-4be7-8b1e-6527f3435713.gif)

- Check the insurance matching your age, gender, and desired coverage
- View detailed coverage descriptions: dental prosthetics, preservation treatment, nerve treatment, etc.
- Graphs: Age distribution of policyholders and primary coverage areas

![Insurance Detail 2](https://user-images.githubusercontent.com/56299114/169866312-991c8cac-64c4-4922-b867-a9ccd06425a1.gif)

---

### 4. Insurance Comparison

- Select up to 3 plans from search results to compare in a modal
- View side-by-side comparison of premiums, Chi Chu Index, and coverage details

![Insurance Comparison](https://user-images.githubusercontent.com/56299114/169866276-513736ee-73e6-4db2-be11-8a938d794bb9.gif)

---

### 5. Insurance Tips

- Card-style tips related to dental insurance

![Tips Page](https://user-images.githubusercontent.com/56299114/169867353-b4a8f543-7e53-4180-8cc6-182cea217d7e.gif)

- A visual coverage guide that explains which coverage is needed in different situations

![Tips Cards](https://user-images.githubusercontent.com/56299114/169866222-e71d2e08-566f-4d48-831a-6fb144d39b7d.gif)
