# CampusChoice starter (Phase 1)

This is a first, beginner-friendly milestone: a UE-inspired red-and-white login page, Spring Security authentication, a dashboard, and role-based URL protection.

## Requirements
- JDK 21
- VS Code with Extension Pack for Java and Spring Boot Extension Pack
- Internet connection on the first build (Maven downloads dependencies)

## Run
1. Open this folder in VS Code.
2. Open **Terminal → New Terminal**.
3. Run `./mvnw spring-boot:run` if the Maven wrapper exists. This starter does not bundle a wrapper, so otherwise install Maven and run `mvn spring-boot:run`.
4. Open `http://localhost:8080`.

On Windows PowerShell, use `mvn spring-boot:run`.

## Demo accounts (local prototype only)
| Role | Username | Password |
|---|---|---|
| Student | `student` | `Student123!` |
| Department Coordinator | `coordinator` | `Coordinator123!` |
| Administrator | `admin` | `Admin123!` |

These are temporary in-memory accounts. Do not deploy this prototype or use these passwords in a real service. Phase 2 replaces them with database-backed accounts and a controlled account provisioning workflow.

## Next phase
After the app runs, install MySQL Server and Workbench. Then add Spring Data JPA and the MySQL Connector, create the database, and implement database-backed accounts, student eligibility, polls, surveys, suggestions, and audit records. Do not connect to real UE student records without institutional authorization.
