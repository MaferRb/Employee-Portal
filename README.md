# Employee Portal

## Project Description

The Employee Portal is a Laravel-based HR self-service web application. It centralizes Leave, Vehicle, Recommendation Letter, and Equipment requests into a single role-gated system Employee, Manager, and Admin replacing scattered manual processes with a transparent, trackable workflow.

## Tech Stack

**Development**
- Frontend: React
- Backend: Laravel (PHP)
- Database: SQLite
- Version Control: Git & GitHub
- Development Environment: Visual Studio Code

**Testing**
- Selenium: Automated UI testing
- Pest: Backend feature testing
- Pytest: Test execution and reporting

## Test Execution Evidence

### Backend Test Results (Pest)

![Backend test execution](tests/evidence/screenshots/backend-test-execution.png)

This is the output of `php artisan test`, showing the backend feature test suite.

### UI Test Results (Selenium)

![Selenium UI test execution](tests/evidence/screenshots/selenium-test-execution.png)

This is the output of `pytest -v`, showing the automated UI test suite running against the live application.

## Updated Test Results

This is an updated testing pass on a project that already had prior testing work completed and documented. The suite was re-executed to confirm current status:

- **Backend (Pest):** 2 failed, 25 passed — DEF-BE-01 and DEF-BE-02 confirmed, unresolved
- **UI (Selenium):** 18 passed, 1 skipped, 0 failed

## Test Execution Video

A short video demonstrating the Selenium test execution (login, dashboard access, and unauthorized admin page blocking) is available here:

[Watch the test execution video](https://drive.google.com/file/d/11J6TCSwgSvWDBazA4OvcOVlq2HIHsmnj/view?usp=sharing)

## Final Presentation

The final, updated project presentation is available here:

[View the final presentation](https://docs.google.com/presentation/d/1VgLql71FbNxZVwRHnJdbxod8PUSJYLCi/edit?usp=sharing&ouid=103813443076117236926&rtpof=true&sd=true)
