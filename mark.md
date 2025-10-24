# Project Tasks

This document tracks all tasks for the project.  
Use `[ ]` for pending tasks and `[x]` for completed tasks.

---

## General Guidelines
- **Priority Levels:** High 🔴, Medium 🟡, Low 🟢
- **Status:** Pending `[ ]`, In Progress `[~]`, Done `[x]`
- **Notes:** Additional info about task or blockers

---

## Backend Tasks
| Task | Status | Priority | Notes |
|------|--------|----------|-------|
| Setup MongoDB database | [x] | 🔴 | Database initialized with default collections |
| Implement user authentication | [ ] | 🔴 | Use JWT for token-based auth |
| Create REST API endpoints | [ ] | 🔴 | Endpoints: /users, /auth, /products |
| Setup logging system | [ ] | 🟡 | Consider using Winston or Morgan |
| Write unit tests | [ ] | 🟡 | Focus on critical endpoints first |

---

## Frontend Tasks
| Task | Status | Priority | Notes |
|------|--------|----------|-------|
| Initialize React project | [x] | 🔴 | Using Vite for setup |
| Create login page | [ ] | 🔴 | Form validation required |
| Connect login page to backend API | [ ] | 🔴 | Test with Postman first |
| Build dashboard page | [ ] | 🟡 | Charts and stats visualization |
| Implement responsive design | [ ] | 🟡 | Mobile and tablet support |

---

## DevOps / Deployment
| Task | Status | Priority | Notes |
|------|--------|----------|-------|
| Create Dockerfile for backend | [x] | 🔴 | React/Node
| Create Dockerfile for frontend | [ ] | 🔴 | Node.js container setup |
| Setup CI/CD pipeline | [ ] | 🔴 | GitHub Actions or Jenkins |
| Deployment to server | [ ] | 🔴 | Test staging environment first |
| Configure environment variables | [ ] | 🟡 | Use `.env` file |

---

## Notes
- Update this document as tasks progress.
- Use meaningful commit messages like:
  - `chore(tasks): add initial backend task list`
  - `feat(frontend): implement login page`
  - `fix(devops): correct Dockerfile configuration`
