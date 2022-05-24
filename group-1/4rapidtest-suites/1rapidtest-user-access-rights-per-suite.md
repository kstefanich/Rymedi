# rapidtest User Access Rights per Suite


| User Roles      |   Manufacturer Suite  |    Test Suites  | CLIA Audit | Patient Suite | HR Suite | Patient Info                | Reporting Suite | Admin Suite |
| --------------- | :-------------------: | :-------------: | :--------: | :-----------: | :------: | :-------------------------: | :-------------: | :---------: |
| Manufacturer    |x                      |                 |            |               |          |                             |x                |
| Patient         |                       |                 |            |x              |          |                             |                 |
| HCP             |                       |x                |x           |               |          |                             |x                |
| HCP-Senior      |                       |x                |x           |               |          |x                            |x                |
| HCP-Contractor  |                       |x (initate test) |            |               |          |                             |                 |
| HR              |                       |                 |            |               |x         |                         |                 |x (user mng only) |
| CLIA Audit      |                       |                 |x           |               |          |                             |                 |
| Analyst         |                       |                 |            |               |          |                             |x                |
| Admin           |x                      |x                |x           |               |x         |x                            |x                |x
| Accountant      |                       |                 |            |               |          |x (view billing info only)   |                 |
| Customer Support|                       |                 |            |               |          |x (edit patient contact only)|                 |
