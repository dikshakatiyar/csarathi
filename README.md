# 💬 C-SARATHI — College Helpdesk Platform

C-Sarathi is a centralized **college helpdesk platform** designed to streamline student–faculty interaction and query resolution.  
It allows students to raise tickets, browse FAQs, and contact faculty, while administrators can manage and resolve queries efficiently.

---

## 🏗️ Repository Structure: A Poly-Repo Architecture

This project follows a **poly-repo architecture** managed via **Git Submodules**.  
Each component (Frontend, Backend) resides in its own dedicated repository, while this **parent repository** acts as a **central hub** for documentation, version tracking, and deployment overview.

| Component | Description | Repository Link |
|------------|--------------|-----------------|
| **Frontend** | User interface built with HTML, CSS, and JavaScript | [C-SARATHI Frontend](https://github.com/dikshakatiyar/C-SARATHI-html) |
| **Backend** | RESTful API built with Node.js and Express | [C-SARATHI Backend](https://github.com/dikshakatiyar/csarathi-backend) |
| **Parent Repo** | Central documentation and architecture overview | [C-SARATHI Main](https://github.com/dikshakatiyar/csarathi) |

This architecture keeps codebases clean, modular, and independently deployable — while maintaining a single point of reference for the complete project.

---

## ⚙️ Features

- 🧾 **Ticket Management System:** Students can raise, track, and close helpdesk tickets.  
- 💬 **FAQ Section:** Dynamic FAQs for quick solutions.  
- 👩‍🏫 **Admin Dashboard:** Faculty/admins can view and resolve queries.  
- 🔒 **Authentication:** Secure login system for users and admins.  
- 📋 **Contact Directory:** Static list of faculty and department contacts.  

---

## 🖥️ Tech Stack

| Layer | Technology |
|-------|-------------|
| **Frontend** | HTML, CSS, JavaScript |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB |
| **Hosting (suggested)** | Frontend → Netlify / Vercel <br> Backend → Render / Railway |

---

## 🚀 Deployment Note

> The **frontend** and **backend** are hosted and maintained independently.  
> This **main repository** is used for project structure, documentation, and as a unified reference point.

---

## 🧩 Setting Up Locally

If you wish to clone this **parent repo** with all submodules (frontend & backend included):

```bash
# Clone with submodules
git clone --recurse-submodules https://github.com/dikshakatiyar/csarathi.git

# Or if already cloned, initialize submodules
git submodule update --init --recursive
