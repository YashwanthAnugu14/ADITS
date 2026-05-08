# 👋 ADITS — Assumption Dependency & Impact Tracking System

<div align="center">

![](https://img.shields.io/badge/Python-Application-3776AB?style=for-the-badge&logo=python&logoColor=white)
![](https://img.shields.io/badge/Streamlit-Interactive_UI-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![](https://img.shields.io/badge/SQLite-Database-003B57?style=for-the-badge)
![](https://img.shields.io/badge/Risk-Management-FF8C00?style=for-the-badge)

</div>

---

# 👨‍💻 Developed By

### Yashwanth Reddy Anugu

---

# 📂 File Name

### `helpdesk_app.py`

---

# 🚀 About This Project

The Assumption Dependency & Impact Tracking System (ADITS) is a web-based application designed to manage one of the most overlooked areas in project management — assumptions and their dependencies.

In many real-world projects, teams make important decisions based on assumptions. However, these assumptions are often not tracked properly, and when one assumption changes or becomes invalid, it can silently affect multiple parts of the project. This creates hidden risks, delays, and poor decision making.

To solve this problem, I designed ADITS. The system allows users to create assumptions, define dependency relationships between them, monitor impact levels, evaluate project risks, and maintain complete transparency of changes.

The application provides a centralized platform where teams can manage assumptions in a structured and organized way instead of relying on scattered documentation or manual tracking methods.

---

# ❗ Problem Statement

In many organizations and project environments:

- Assumptions are not managed systematically
- Dependencies between assumptions are difficult to identify
- Risk levels are not measured clearly
- Changes are not documented properly
- Teams lack visibility into cascading impacts

When one important assumption fails, it can affect timelines, planning, resource allocation, and project outcomes without teams realizing the actual impact.

Most existing systems focus mainly on tasks, tickets, or risks, but assumptions themselves are rarely treated as first-class entities in project management.

ADITS addresses these problems by providing:

- Structured assumption management
- Dependency mapping
- Dynamic impact analysis
- Risk calculation
- Audit tracking
- Transparent change monitoring

---

# 🎯 System Objectives

- Centralize assumption management
- Track relationships between assumptions
- Identify cascading dependency impacts
- Improve project risk visibility
- Support better decision making
- Maintain transparency in updates
- Provide clear dashboards and analytics
- Reduce hidden project risks

---

# ✨ Key Capabilities

# 🧩 Assumption Management

- Create new assumptions
- Update existing assumptions
- Delete assumptions when necessary
- Assign ownership and categories
- Track confidence levels and impact scores
- Maintain statuses such as Valid, At Risk, and Invalid

---

# 🔗 Dependency Handling

- Create links between assumptions
- Define dependency relationships clearly
- Prevent circular dependency creation
- Automatically identify cascading effects
- Monitor relationship impact across projects

---

# 📊 Risk Evaluation

- Calculate risk index dynamically
- Analyze confidence and impact weight together
- Display visual risk indicators
- Update risk values automatically after changes
- Help teams quickly identify critical assumptions

---

# 🕘 Version Tracking

- Store history of assumption changes
- Compare old and updated values
- Maintain complete transparency
- Support audit and review activities

---

# 👥 Role-Based Access

### 🛡️ Project Owner
- Full system access
- Manage users and assumptions
- Configure dependencies and settings

### 📈 Analyst
- Create and manage assumptions
- Evaluate dependencies and impacts
- Monitor risk dashboards

### 👁️ Viewer
- Read-only access
- View dashboards and reports
- Monitor assumption status

---

# 📝 Audit Logging

- Track all major user activities
- Record assumption updates
- Maintain accountability
- Support traceability and monitoring

---

# 🔍 Search and Filtering

- Filter assumptions by category
- Search using keywords
- Sort by status or impact
- Quickly locate related assumptions

---

# ⚙️ Technologies Used

<div align="center">

![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge)
![](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

</div>

### Technologies Included

- Python for backend logic and processing
- Streamlit for interactive user interface
- SQLite for lightweight database storage
- Pandas for structured data handling and analysis

---

# ⚙️ How to Run the Project

## 📥 Install Required Packages

```bash
python -m pip install streamlit pandas plotly
```

---

## ▶️ Run the Application

```bash
streamlit run helpdesk_app.py
```

---

# 🔐 Default Access

### Initial Login Credentials

- Username: `admin`
- Password: `admin123`

Additional users can be created after successful login.

---

# 🔄 System Workflow

### 1️⃣ User Login
The user logs into the system using valid credentials.

### 2️⃣ Project Selection
The user creates or selects an existing project.

### 3️⃣ Assumption Creation
Assumptions are added with categories, confidence values, and impact levels.

### 4️⃣ Dependency Mapping
Relationships between assumptions are defined.

### 5️⃣ Status Updates
Users update assumptions whenever conditions change.

### 6️⃣ Risk Calculation
The system automatically recalculates dependency impact and project risk.

### 7️⃣ Dashboard Monitoring
Users monitor project assumptions using dashboards, reports, and visual outputs.

---

# 🏗️ Design Approach

While building this project, I mainly focused on:

- Keeping the UI simple and user-friendly
- Designing clear and maintainable logic
- Ensuring structured data management
- Supporting practical real-world workflows
- Providing transparent impact analysis
- Making the application modular and extendable

Even though the project is implemented as a single-file Streamlit application, the internal structure is designed in a modular way so that it can be expanded into a larger enterprise system in the future.

---

# 📈 System Advantages

- Improves visibility of project assumptions
- Reduces hidden project risks
- Supports better planning and decision making
- Tracks dependency impact automatically
- Provides centralized assumption management
- Maintains transparency and accountability
- Easy to understand and operate

---

# ⚠️ Current Limitations

- SQLite is not ideal for high-concurrency environments
- No external authentication integration
- UI scalability can be improved further
- Notifications are currently limited
- Advanced analytics features can be extended

---

# 🚀 Future Improvements

- Migration to PostgreSQL for scalability
- API integration support
- Token-based authentication system
- Real-time notifications and alerts
- Advanced reporting dashboards
- AI-based risk prediction
- Improved visual analytics and graphs
- Multi-project dependency comparison

---

# 🧪 Testing

The system supports testing for major functionalities including:

- Assumption creation and validation
- Dependency relationship handling
- Risk calculation logic
- Version tracking operations
- User role management
- Audit logging workflows

---

# 🌟 Conclusion

The Assumption Dependency & Impact Tracking System provides a structured and intelligent approach for managing assumptions and understanding their impact within projects.

Instead of treating assumptions as untracked notes or hidden risks, the system converts them into manageable and analyzable entities. This improves project visibility, strengthens decision making, and helps organizations reduce unexpected issues caused by assumption failures.

The project demonstrates how dependency analysis and structured tracking can significantly improve transparency, accountability, and risk management in modern project environments.
