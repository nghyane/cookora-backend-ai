# 🍳 COOKORA - 6 WEEK MVP SPRINT

## 📋 Overview
**Start Date**: 17/6/2025 | **End Date**: 29/7/2025 (6 weeks)  
**Strategy**: Ultra-focused MVP - Core flow only  
**Architecture**: Monorepo (Backend: Bun+Hono, Agent: Python+Agno)

---

## 📊 MASTER TASK TABLE

| **Week** | **Date Range** | **Task** | **Days** | **Component** | **Priority** | **Status** | **Dependencies** |
|----------|----------------|----------|----------|---------------|--------------|------------|------------------|
| **1** | 17/6 - 23/6 | Monorepo + Docker Setup | 1 | Both | HIGH | ⏳ | None |
| **1** | 17/6 - 23/6 | Database Schema + Data Import | 2 | Backend | HIGH | ⏳ | Monorepo |
| **1** | 17/6 - 23/6 | Basic Hono API | 2 | Backend | HIGH | ⏳ | Database |
| **1** | 17/6 - 23/6 | Python Agent Integration | 2 | Agent | HIGH | ⏳ | Monorepo |
| **2** | 24/6 - 30/6 | GPT-4o Vision Service | 3 | Agent | HIGH | ⏳ | Python Agent |
| **2** | 24/6 - 30/6 | Recipe AI Service | 3 | Agent | HIGH | ⏳ | Python Agent |
| **2** | 24/6 - 30/6 | Agent-Backend Communication | 2 | Both | HIGH | ⏳ | AI Services |
| **3** | 1/7 - 7/7 | Recipe Database Normalization | 3 | Backend | HIGH | ⏳ | Database Schema |
| **3** | 1/7 - 7/7 | Basic Ingredient Matching | 3 | Backend | HIGH | ⏳ | Recipe DB |
| **3** | 1/7 - 7/7 | SHA-256 Image Caching | 2 | Backend | MEDIUM | ⏳ | Basic API |
| **4** | 8/7 - 14/7 | suggest-recipes API | 4 | Backend | HIGH | ⏳ | Ingredient Matching |
| **4** | 8/7 - 14/7 | Basic Filtering | 2 | Backend | MEDIUM | ⏳ | suggest-recipes |
| **4** | 8/7 - 14/7 | Error Handling | 2 | Both | HIGH | ⏳ | Core APIs |
| **5** | 15/7 - 21/7 | End-to-end Testing | 3 | Both | HIGH | ⏳ | Core Flow |
| **5** | 15/7 - 21/7 | Performance Optimization | 3 | Both | HIGH | ⏳ | Testing |
| **5** | 15/7 - 21/7 | Bug Fixes | 2 | Both | HIGH | ⏳ | Testing |
| **6** | 22/7 - 29/7 | Production Setup | 3 | DevOps | HIGH | ⏳ | Optimization |
| **6** | 22/7 - 29/7 | Final Testing | 2 | Both | HIGH | ⏳ | Production |
| **6** | 22/7 - 29/7 | Documentation | 2 | All | MEDIUM | ⏳ | Final Testing |

---

## 🗓️ WEEKLY BREAKDOWN

### **WEEK 1: FOUNDATION (17/6 - 23/6)**

| **Task** | **Mon 17/6** | **Tue 18/6** | **Wed 19/6** | **Thu 20/6** | **Fri 21/6** | **Status** |
|----------|--------------|--------------|--------------|--------------|--------------|------------|
| Monorepo + Docker Setup | 🔴 Start | | | | | ⏳ |
| Database Schema + Data Import | | 🔴 Start | ✅ Continue | | | ⏳ |
| Basic Hono API | | | 🔴 Start | ✅ Continue | | ⏳ |
| Python Agent Integration | | | | 🔴 Start | ✅ Continue | ⏳ |

### **WEEK 2: AI INTEGRATION (24/6 - 30/6)**

| **Task** | **Mon 24/6** | **Tue 25/6** | **Wed 26/6** | **Thu 27/6** | **Fri 28/6** | **Status** |
|----------|--------------|--------------|--------------|--------------|--------------|------------|
| GPT-4o Vision Service | 🔴 Start | ✅ Continue | ✅ Continue | | | ⏳ |
| Recipe AI Service | 🔴 Start | ✅ Continue | ✅ Continue | | | ⏳ |
| Agent-Backend Communication | | | | 🔴 Start | ✅ Continue | ⏳ |

### **WEEK 3: DATABASE + MATCHING (1/7 - 7/7)**

| **Task** | **Mon 1/7** | **Tue 2/7** | **Wed 3/7** | **Thu 4/7** | **Fri 5/7** | **Status** |
|----------|-------------|-------------|-------------|-------------|-------------|------------|
| Recipe Database Normalization | 🔴 Start | ✅ Continue | ✅ Continue | | | ⏳ |
| Basic Ingredient Matching | 🔴 Start | ✅ Continue | ✅ Continue | | | ⏳ |
| SHA-256 Image Caching | | | | 🔴 Start | ✅ Continue | ⏳ |

### **WEEK 4: CORE API (8/7 - 14/7)**

| **Task** | **Mon 8/7** | **Tue 9/7** | **Wed 10/7** | **Thu 11/7** | **Fri 12/7** | **Status** |
|----------|-------------|-------------|--------------|--------------|--------------|------------|
| suggest-recipes API | 🔴 Start | ✅ Continue | ✅ Continue | ✅ Continue | | ⏳ |
| Basic Filtering | | | 🔴 Start | ✅ Continue | | ⏳ |
| Error Handling | | | | 🔴 Start | ✅ Continue | ⏳ |

### **WEEK 5: TESTING + OPTIMIZATION (15/7 - 21/7)**

| **Task** | **Mon 15/7** | **Tue 16/7** | **Wed 17/7** | **Thu 18/7** | **Fri 19/7** | **Status** |
|----------|--------------|--------------|--------------|--------------|--------------|------------|
| End-to-end Testing | 🔴 Start | ✅ Continue | ✅ Continue | | | ⏳ |
| Performance Optimization | 🔴 Start | ✅ Continue | ✅ Continue | | | ⏳ |
| Bug Fixes | | | | 🔴 Start | ✅ Continue | ⏳ |

### **WEEK 6: DEPLOYMENT (22/7 - 29/7)**

| **Task** | **Mon 22/7** | **Tue 23/7** | **Wed 24/7** | **Thu 25/7** | **Fri 26/7** | **Status** |
|----------|--------------|--------------|--------------|--------------|--------------|------------|
| Production Setup | 🔴 Start | ✅ Continue | ✅ Continue | | | ⏳ |
| Final Testing | | | | 🔴 Start | ✅ Continue | ⏳ |
| Documentation | | | | | 🔴 Start | ⏳ |

---

## 🎯 CORE ENDPOINTS TRACKING

| **Endpoint** | **Week** | **Dependencies** | **Status** | **Testing** | **Production** |
|--------------|----------|------------------|------------|-------------|----------------|
| `GET /api/v1/health` | Week 1 | Basic API | ⏳ | ⏳ | ⏳ |
| `POST /api/v1/upload-image` | Week 3 | Database + Caching | ⏳ | ⏳ | ⏳ |
| `POST /agent/detect-ingredients` | Week 2 | Vision Service | ⏳ | ⏳ | ⏳ |
| `GET /api/v1/suggest-recipes` | Week 4 | Matching Algorithm | ⏳ | ⏳ | ⏳ |
| `GET /api/v1/recipe/{id}` | Week 3 | Recipe Database | ⏳ | ⏳ | ⏳ |

---

## 📊 PROGRESS TRACKING

### **Status Legend:**
- 🔴 **Start** - Begin task
- ✅ **Continue** - Work in progress  
- ⏳ **Pending** - Not started
- ✅ **Complete** - Finished
- ❌ **Blocked** - Issues/dependencies

### **Weekly Goals:**
- **Week 1**: ✅ All services running locally
- **Week 2**: ✅ AI detection working
- **Week 3**: ✅ Recipe matching functional  
- **Week 4**: ✅ suggest-recipes API working
- **Week 5**: ✅ MVP stable and tested
- **Week 6**: ✅ MVP deployed and live

---

## 🚨 CRITICAL PATH

| **Milestone** | **Week** | **Critical Dependencies** | **Risk Level** |
|---------------|----------|---------------------------|----------------|
| Services Running | Week 1 | Monorepo + Docker | 🟡 Medium |
| AI Integration | Week 2 | Existing Python code | 🟡 Medium |
| Recipe Matching | Week 3 | Database + Algorithm | 🔴 High |
| Core API Complete | Week 4 | All previous weeks | 🔴 High |
| MVP Testing | Week 5 | Core functionality | 🟡 Medium |
| Production Deploy | Week 6 | Testing complete | 🟡 Medium |

---

## 🏃‍♂️ THIS WEEK ACTIONS (17/6 - 23/6)

| **Day** | **Primary Task** | **Secondary Task** | **Goal** |
|---------|------------------|-------------------|----------|
| **Mon 17/6** | Monorepo Setup | Review existing code | Foundation |
| **Tue 18/6** | Database Schema | Import keywords data | Data ready |
| **Wed 19/6** | Hono API Start | Python agent start | APIs responding |
| **Thu 20/6** | Continue APIs | Continue agent | Integration |
| **Fri 21/6** | Docker setup | End-to-end testing | Week 1 complete |

---

*Table format for easy tracking and daily progress monitoring!* 
