# Smart Library Request Workflow in ServiceNow

## Project Overview
The **Smart Library Request Workflow** is a ServiceNow project designed to automate the traditional library book request and approval process. The system helps students request books online and allows librarians to manage approvals, book issuance, and returns efficiently.

This automation improves **data accuracy, transparency, and workflow efficiency** compared to manual record-keeping systems.

---


## Problem Statement
Traditional library systems rely on manual records which create several issues such as:
- No real-time information about book availability
- Slow manual approval process
- Difficulty tracking borrowing history
- Risk of data loss or duplication

This project solves these problems by implementing an automated workflow using **ServiceNow**.

---

## User Roles

### Student
Students can:
- Search for books
- Check book availability
- Submit borrow requests
- Track request status

### Librarian
Librarians can:
- Manage the book catalog
- Review and approve requests
- Issue and return books

---

## Database Tables

### Book Table (`u_book`)
Stores information about books:
- Title
- Author
- Category
- Availability Status

### Borrow Request Table (`u_borrow_request`)
Tracks borrowing transactions:
- Student details
- Book reference
- Borrow date
- Return date
- Request status

---

## Workflow Process

1. Student submits a **book request**.
2. Librarian reviews the request.
3. If approved, the book status changes to **Issued**.
4. After the book is returned, the librarian updates the status to **Available**.

---

## ServiceNow Features Used
- Flow Designer
- Business Rules
- UI Policies
- Reference Qualifiers
- Email Notifications
- Role-Based Access Control (RBAC)

---

## Benefits
- Automated book request system
- Faster approval workflow
- Real-time book availability
- Improved data management
- Better user experience

---

## Conclusion
The **Smart Library Request Workflow** simplifies library operations by automating the borrowing process and improving system efficiency using ServiceNow.
