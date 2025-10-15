# Votify 🗳️

Votify is a **Spring Boot Web-Based Application** designed to enable **efficient and transparent online voting**.  
This system allows **candidates and voters to register**, lets **voters cast their votes**, and finally **view election results** in real-time.

---

## 🏗️ System Architecture

The system follows a **three-tier architecture**:

### 1. Presentation Layer
REST API endpoints exposed through **Spring Boot Controllers**.

### 2. Business Layer
Implements the **business logic** for voting, election results, and validation.

### 3. Data Layer
Uses **Spring Data JPA** for database interactions with **MySQL**.

---

## ⚙️ Application Workflow

### 1. Voters & Candidate Registration
- Voters register with their **name** and **email**.  
- Candidates register with their **name** and **party**.

---

### 2. Casting a Vote
- A registered voter selects a candidate and submits their vote.

---

### 3. Viewing Election Results
- With just one click, the system calculates votes and displays the **election results**.

---

## 🚨 Special Cases Handled
- A voter **cannot vote twice** in the same election.  
- A voter **cannot vote for a non-existing candidate**.  
- A **non-registered voter** is not allowed to cast votes.

---

## 🧩 Modules

### 1. Voters Module
- Register Voter  
- View Voter Details

### 2. Candidate Module
- Register Candidate  
- View Candidate Details

### 3. Voting Module
- Cast Votes  
- Track Voter Participation

### 4. Election Results Module
- Calculate and Display Election Results

---

## 💡 Tech Stack
- **Backend:** Java, Spring Boot  
- **Database:** MySQL  
- **ORM:** Spring Data JPA  
- **Architecture:** Three-tier (Presentation, Business, Data)

---

## 📄 License
This project is for educational purposes and can be freely used for learning and research.

---

### 👨‍💻 Author
**Ashish Ranjan Samal**  
*5th Semester BCA Student | Passionate about Coding and Web Applications*
