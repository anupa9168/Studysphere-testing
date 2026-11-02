# StudySphere - Manual Testing

Manual test cases and bug reports for the StudySphere learning system (ASP.NET Web Forms, C#, SQL Server), a group academic project. This is a beginner testing exercise done on a local copy of the application.

## Scope
Student Registration and Student Login.

## Files
- `StudySphere_Test_Cases.xlsx` - test cases, bug reports and a results summary
- `screenshots/` - screenshots for the bug reports

## Results so far
- 16 test cases written (9 registration, 7 login)
- 16 executed: 12 passed, 4 failed

## Bugs
| ID | Test | Summary | Severity | Status |
|---|---|---|---|---|
| BUG-2 | REG-08 | Registration accepts a one-character password | Medium | Open |
| BUG-3 | REG-09 | Registration accepts a future date of birth | Medium | Open |
| BUG-1 | REG-06 | Registration accepted an email already in use | High | Under verification |
| BUG-4 | LOG-07 | Dashboard access without login | Low | Under verification |

BUG-1 and BUG-4 are being re-checked. The project's code and database script appear to prevent both, so they will be confirmed or marked invalid after retesting.

## Tools
Microsoft Excel, a web browser, SQL Server Express, Visual Studio.

## Next steps
- Test course, quiz and admin pages
- Try API testing with Postman
- Write a basic Playwright test
