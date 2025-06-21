# Test Plan – Movie Streaming Application

---

## 1. Context of Testing

### Scope

**Components to be tested:**
- **User registration/login** – Email, password (6–60 characters)
- **Search functionality** – Movie search (accepts only numbers and letters)
- **Playback** – Streaming quality and buffering
- **Multiple devices** – Compatibility on desktop, laptop, tablet, smartphone

**Components not to be tested:**
- Subscription History – Assumed stable
- Third-party integrations – Email/payment providers assumed reliable

### Test Objectives

- Ensure app meets functional requirements (registration, search, playback)
- Validate performance, security, and usability
- Confirm user-friendly login and registration
- Detect and fix defects before release
- Ensure compatibility across supported devices/OS

### Constraints

- Limited access to real user data due to privacy
- Tight deadlines
- Dependencies on third-party services
- Only English letters tested (other languages tested by other teams)

### Test Basis

- Requirement Specification Document  
- UI Design Document  
- User Stories  
- Acceptance Criteria  

---

## 2. Stakeholders

### Roles and Responsibilities

- **Project Manager** – Oversees full project lifecycle  
- **Test Manager** – Plans and monitors testing  
- **Test Lead** – Coordinates team activities  
- **Test Engineers** – Design, execute, report  
- **Developers** – Fix reported defects  
- **Product Owner** – Defines requirements and reviews results  
- **Business Analysts** – Support in clarifying requirements  

### Relevance to Testing

- Test Engineers: Execute and report on test results  
- Developers: Resolve issues  
- Product Owner: Validate alignment with business needs  

### Hiring & Training

- Hire test engineers with automation experience  
- Train team on new tools and methodologies  

---

## 3. Risk Register

### Product Risks

| Risk | Mitigation |
|------|------------|
| High buffering / latency | Auto-adjust video quality |
| Compatibility issues | Use list of supported devices/OS provided by PO |
| Non-English input issues | Scope limited to English |

### Project Risks

| Risk | Mitigation |
|------|------------|
| Dev delays | Regular status meetings |
| Resource unavailability | Cross-training, backups |

---

## 4. Budget and Schedule

### Budget

| Item | Cost |
|------|------|
| Personnel | $50,000 |
| Tool Licenses | $10,000 |
| Training | $5,000 |
| Misc. | $2,000 |
| **Total** | **$67,000** |

### Schedule

| Phase | Dates |
|-------|-------|
| Test Planning | Jan 1 – Jan 10 |
| Test Case Dev | Jan 11 – Jan 20 |
| Env Setup | Jan 21 – Jan 25 |
| Execution | Jan 26 – Feb 15 |
| Retesting | Feb 16 – Feb 25 |
| Closure | Feb 26 – Feb 28 |

---

## 5. Assumptions and Constraints

### Assumptions

- Documentation is ready before testing  
- Test environments are stable  
- Adequate test data available  

### Constraints

- Limited budget  
- Limited device/browser access  
- Dependency on external tools/services  

---

## 6. Communication

### Formats & Frequency

- **Daily Stand-ups** – Short updates
- **Weekly Reports** – Status, risks, defects
- **Test Summary** – At test phase end

### Templates Used

- Test Plan  
- Test Case  
- Defect Report  
- Test Summary Report  

---

## 7. Test Approach

### Test Levels

- **Unit Testing** – By developers  
- **Integration Testing** – Combined module validation  
- **System Testing** – Full app testing  
- **Acceptance Testing** – Against business requirements  

### Test Types

- Functional  
- Non-functional (performance, security, usability, compatibility)  
- Regression  

### Test Techniques

- Equivalence Partitioning  
- Boundary Value Analysis  
- Decision Table Testing  
- Exploratory Testing  

### Tools & Automation

- **Selenium** – UI automation  
- **JMeter** – Performance testing  

### Test Deliverables

- Test Plan  
- Test Cases  
- Scripts  
- Test Data  
- Defect Reports  
- Execution Reports  
- Summary Report  

---

## 8. Entry and Exit Criteria

### Entry Criteria

- Test environment is set up  
- Requirements are documented and approved  
- Test plan and cases are reviewed  
- Test data is available  

### Exit Criteria

- All planned test cases executed  
- All high/critical defects resolved and verified  
- All test documentation is reviewed and complete  

---

## 9. Metrics to Be Collected

- **Test Execution Status** – Pass/fail counts  
- **Defect Density** – Defects per module  
- **Test Coverage** – % of requirements covered  
- **Defect Resolution Time** – Avg. fix time  

---

## 10. Test Data Requirements

- **User Data** – Login  
- **Product Data** – Search functionality  

---

## 11. Deviations from Policy/Strategy

- **Deviation**: Use of exploratory testing in parallel  
- **Justification**: Improves coverage, catches edge cases not in predefined tests
