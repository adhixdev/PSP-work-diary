# Week Eight – Sprint Week

## Day 1 – API Development Initiation

### Task Completed
- Set up a custom **C# Web API** to connect the PHP frontend with the SQLite database.
- Chose API architecture for better **scalability, maintainability**, and **performance**.
- Began integration using tools like **Postman** and **Swagger**.

### Task To Do
- Finalize all API endpoints.
- Begin frontend integration with API responses.

### Issues
- Initial connectivity problems between API and PHP due to CORS and route misconfigurations.
- API was not responding properly until debugging was done.

---

## Day 2 – Frontend Integration & Debugging

### Task Completed
- Integrated API responses into the **PHP dashboard** to display real-time case summaries.
- Handled asynchronous calls with proper **AJAX** and JSON parsing.
- Added loading states and fallback handling in UI.

### Task To Do
- Polish UI with proper feedback for failed requests.
- Begin integrating additional case-related stats on the dashboard.

### Issues
- Inconsistent rendering of API data due to delay in async responses.
- Minor bugs while handling empty or malformed responses.

---

## Day 3 – Database Cleanup & Controlled Seeding

### Task Completed
- Cleared the old dataset and introduced **version-controlled (v6)** seed data.
- Validated schema relationships (e.g., case-agent-manager).
- Ensured data consistency and referential integrity.

### Task To Do
- Add more realistic test data for deeper validation.
- Run multiple test cases simulating real-world input.

### Issues
- Some fields were not mapped correctly after reset, requiring manual adjustment.
- A few validation rules conflicted with seeded data.

---

## Day 4 – Backend Logic & Dashboard Functionality

### Task Completed
- Enhanced API logic to include:
  - Auto-generated **Customer IDs**
  - Session-based **Agent ID** assignment
  - Duplicate case prevention logic with existing case display
- Linked these features with frontend forms and ensured dashboard metrics updated accordingly.

### Task To Do
- Add pagination and advanced filtering on dashboard.
- Test duplicate logic across all departments.

### Issues
- Limited test coverage led to missed scenarios in duplicate detection.
- Some metrics on the dashboard lagged or didn’t update correctly after changes.

---

## Day 5 – Testing & Validation

### Task Completed
- Conducted limited but focused testing on frontend and backend integration.
- Verified core functionalities like case creation, duplication handling, and summary display.
- Logged feedback for edge case handling.

### Task To Do
- Perform more extensive testing across roles (agents vs managers).
- Expand error handling and data validation coverage.

### Issues
- Performance drops observed with certain API calls.
- Need for improved feedback for backend errors and form validation failures.
