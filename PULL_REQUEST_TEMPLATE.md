Asana: 

Checklist for reviewer:
- [ ] The PR can be easily reviewed and does not mix different objectives
- [ ] I have considered the possibility of a pair review
- [ ] The functional changes match the business requirements defined in the task
- [ ] In case of doubt, I have questioned the correctness of the task description
- [ ] Suitable automated tests are present
- [ ] I have ensured that a manual test was performed if necessary (e.g., for UI or integrations)
- [ ] All relevant places have been adjusted and obsolete code has been removed (full-text search)
- [ ] The changed code fits the code locations in the repo known to me
- [ ] The code meets my quality criteria (naming, structure, extensibility, testability, comments, ...)
- [ ] If dependencies were added, I have questioned their necessity and stability
- [ ] I have checked required infrastructure adjustments (e.g., .env.dist, env variables, scheduler jobs, aiven topics)
- [ ] I do not see any errors or unwanted side effects
