# Functional Requirements
# Functional Requirements

The system must support the following key functionalities for different user roles.

| Requirement ID | User      | Action                           | System Response |
|----------------|-----------|----------------------------------|-----------------|
| FR-1           | Student   | Login with UTA credentials       | System validates and redirects to student dashboard |
| FR-2           | Student   | Browse events                    | System displays a list of upcoming events with filters |
| FR-3           | Student   | RSVP to an event                 | System records RSVP in database and shows confirmation |
| FR-4           | Student   | Submit feedback                  | System stores rating and comments linked to the event |
| FR-5           | Admin     | Create new event                 | System saves event details and displays it to students |
| FR-6           | Admin     | Update or delete event           | System modifies or removes event in database |
| FR-7           | Admin     | Send notification                | System delivers notification to selected users |
| FR-8           | All Users | Logout                           | System ends session and returns to login page |

