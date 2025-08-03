# Medical History Integration System – 3-Week Development Roadmap

**Goal:**  
Developing a local demo of a **role-based medical history management system** with:  
- Role-based login (Doctor and Lab(Hospitals and clinics), Pharmacy, Admin, Patient)  
- Patient medical history  
- Permission code system for patient data access  
- Basic authentication
- Demo presentation at the end of 3 weeks

---

## Team Structure

- **Frontend Team**: React + Tailwind (Web Dashboard)
    > Mainly Yohannes habtamu and Saron Miruts

- **Backend Team **: Node.js or Django + PostgreSQL (API, Auth, CRUD)
    > Mainly Mentesinot getu and Chala Hiko
- **Integration**: Every 2–3 days  
- **Testing**: Every 4 days  

---

## Week 1 – Foundations & Authentication

> **Goal:** Project setup, database design, authentication, role-based access

### Frontend (Team 1)
- [ ] Initialize React project with Tailwind
- [ ] Setup Git repo & folder structure
- [ ] Create page skeletons (Login, Dashboard, Patients)
- [ ] Build **Login Page UI**
- [ ] Create **Dashboard skeleton with navigation**
- [ ] Build **Patient Registration Form UI**
- [ ] Integration & Testing #1 (End of Week)

### Backend (Team 2)
- [ ] Initialize Node.js/Django project & connect PostgreSQL
- [ ] Setup Git repo & project structure
- [ ] Define **DB schema** (patients, medical history, permissions, roles)
- [ ] Implement **Basic Auth (JWT/Session)**
- [ ] Implement **Role-based access (Doctor, Lab, Pharmacy, Admin)**
- [ ] Implement **Patient CRUD API (Create + Read)**
- [ ] Integration & Testing #1 (End of Week)

**Milestone:**  
  Login + Role-based access + Basic patient creation flow works locally

---

## Week 2 – Core Features & Permissions

> **Goal:** Complete patient medical history management and permission code system

### Frontend (Team 1)
- [ ] Build **Patient List & Details Page**
- [ ] Build **Medical History Form UI**
- [ ] Connect **Medical History UI → API**
- [ ] Build **Permission Code Entry UI**
- [ ] Connect **Permission UI → Backend**
- [ ] Integration & Testing #2
- [ ] UI Polish & Responsive Design (Tablet & Phone)

### Backend (Team 2)
- [ ] Implement **Get All Patients API**
- [ ] Implement **Medical History CRUD API**
- [ ] Add **role-based checks for medical history access**
- [ ] Implement **Permission System (Generate + Verify Codes)**
- [ ] Integrate **permission checks before patient data access**
- [ ] Integration & Testing #2
- [ ] Code refactor & cleanup

**Milestone:**  
 Full patient workflow: **Login → Search → Add/View History → Permission Check**

---

## Week 3 – Finalization & Local Demo

> **Goal:** Add search & filtering, finalize dashboards, and prepare local demo

### Frontend (Team 1)
- [ ] Implement **Role-based Dashboard Views**  
- [ ] Build **Search & Filter UI** for patients  
- [ ] Add **Loading States & Error Handling**  
- [ ] Integration & Testing #3  
- [ ] Prepare **Demo Flow Script**  
- [ ] Final **Bug Fixes & Polish**

### Backend (Team 2)
- [ ] Implement **Search Endpoint (basic SQL LIKE)**  
- [ ] Add **Basic Patient Filters**  
- [ ] Add **Optional Audit Logs (if time)**  
- [ ] Integration & Testing #3  
- [ ] Seed database with **Sample Patients & Histories**  
- [ ] Final **Bug Fixes & Polish**

**Milestone:**  
End-to-end **Demo Presentation** (Login → Patient Search → History → Permission)

---

## Integration & Testing Checkpoints
- **Day 7 (Sun)** – Login + Patient CRUD works  
- **Day 13 (Sat)** – Full patient workflow functional  
- **Day 18 (Thu)** – End-to-end workflow ready for demo  

---
