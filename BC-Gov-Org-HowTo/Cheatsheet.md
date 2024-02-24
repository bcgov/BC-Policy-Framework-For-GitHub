---
description: A list of tips, tricks and best practices for using GitHub as a code repository for government projects.
tags:
- GitHub
- cheatsheet
- open source
- code repo repository
- license
- application development
- guidelines
---
## "Working in github.com/bcgov" Cheatsheet

This github.com/bcgov Cheatsheet covers:

- a few things to help when you are just starting out
- things to touch base with *every time* you open or contribute to a repository (as a BC Government employee)

 All BC Government employees working in github.com/bcgov should be familiar with the full [BC-Policy-Framework-For-GitHub](https://github.com/bcgov/BC-Policy-Framework-For-GitHub)


### Joining github.com/bcgov
- Create a GitHub account with your work email and "Province of British Columbia" as the company (optional)
- Enable [two-factor authentication](https://help.github.com/articles/about-two-factor-authentication/) for your GitHub account
- Join the BCGov Organization (follow [these instructions](https://developer.gov.bc.ca/Getting-Started-on-the-DevOps-Platform/How-to-request-new-GitHub-user-access-or-repository-creation)) 
- Make sure you have [Git](https://git-scm.com/) installed on your computer


### Some Resources for Learning Git & GitHub
- [Git and GitHub are not the same thing](https://jahya.net/blog/git-vs-github/)
- [Learn Git in 15 minutes](https://try.github.io/levels/1/challenges/1)
- [On-demand course in GitHub basics](https://github.com/blog/2245-are-you-new-around-here-introducing-an-on-demand-course-in-github-basics)


### Creating a Repository (also called a "repo", basically a project)
-  Choose a path based on whether you are [publishing existing code, initiating a new repository or contributing to an outside repository](https://github.com/bcgov/BC-Policy-Framework-For-GitHub/blob/master/BC-Open-Source-Development-Employee-Guide/Collaborating-Contributing.md)
-  Complete your [Open Content Assessment Checklist](https://github.com/bcgov/BC-Policy-Framework-For-GitHub/blob/master/BC-Open-Source-Development-Employee-Guide/Content-Approval-Checklist.md)
-  Follow [GitHub instructions](https://help.github.com/articles/creating-a-new-repository/), and select 'BCGov' as the owner for all new repositories
-  Pick a repository name that follows [best practices](https://github.com/bcgov/BC-Policy-Framework-For-GitHub/blob/master/BC-Gov-Org-HowTo/Naming-Repos.md)&mdash;for example typically using lowercase with dashes
-  Ensure the repo contains the minimum required content (LICENSE, README.md, CONTRIBUTING.md files)


### ALL github.com/bcgov Repositories
- Every github.com/bcgov repo must have 3 items:
   1. LICENSE file
   2. README file
   3. CONTRIBUTING file
- Adding a [Contributor Code of Conduct](http://contributor-covenant.org/) to your repository is [highly encouraged](https://github.com/bcgov/BC-Policy-Framework-For-GitHub/blob/master/BC-Open-Source-Development-Employee-Guide/Collaborating-Contributing.md)
- [Sample templates](https://github.com/bcgov/BC-Policy-Framework-For-GitHub/blob/master/BC-Gov-Org-HowTo/README.md) are available for all of these 'must have' files


### How to License the Contents of a Repository
- Ensure [authority to LICENSE](https://github.com/bcgov/BC-Policy-Framework-For-GitHub/blob/master/BC-Open-Source-Development-Employee-Guide/Licenses.md) the code and other non-code content in the repository
- Choose [a LICENSE](https://github.com/bcgov/BC-Policy-Framework-For-GitHub/blob/master/BC-Open-Source-Development-Employee-Guide/Licenses.md) for your code (.md files are considered code). The default is the Apache 2.0 LICENSE
- Apply the Apache 2.0 LICENSE in 1-2-3 easy steps:
   1. Attach appropriate LICENSE file directly in the repository
   2. Add the boiler-plate Apache 2.0 LICENSE to the the bottom of your README.md
   3. Add the boiler-plate Apache 2.0 LICENSE to the comments header of *every source code file* 
- Choose a license for any other content (e.g. docs, wikis and non-code stuff) &mdash;the default is [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/)&mdash;and add to the footer of your README.md
- Repositories can have multiple licenses, for example if there is a mix of code and non-code or if the repo contains open datasets under more than one license

### Privacy, Security & Intellectual Property/Copyright
-  Completing the [Open Content Assessment Checklist](https://github.com/bcgov/BC-Policy-Framework-For-GitHub/blob/master/BC-Open-Source-Development-Employee-Guide/Content-Approval-Checklist.md) helps determine if content can be posted to GitHub by ensuring:
   1. The content is free of [Personal Information](http://www2.gov.bc.ca/gov/content/governments/services-for-government/information-management-technology/privacy) (Privacy)
   2. The content has been labelled 'Public' using the  [Information Security Classification Framework](http://www2.gov.bc.ca/gov/content/governments/services-for-government/information-management-technology/information-security/information-security-classification-framework) (Security)
   3. The content is fully owned by the B.C. government and/or the B.C. government holds the [Intellectual Property/Copyright](http://www2.gov.bc.ca/gov/content/governments/services-for-government/policies-procedures/intellectual-property) for the content
   4. There are no other legal, contractual or policy constraints
- Read more about privacy, security and intellectual property in the [BC-Policy-Framework-For-GitHub](https://github.com/bcgov/BC-Policy-Framework-For-GitHub/blob/master/BC-Open-Source-Development-Employee-Guide/COI-Priv-IP.md)


### Approval Requirements
-  Approvals and minium requirements are set out in the [Open Development Standard (pages 14-15)](http://www2.gov.bc.ca/assets/gov/government/services-for-government-and-broader-public-sector/information-technology-services/standards-files/development_standards_for_information_systems_and_services.pdf)
-  BC Government employees are responsible for adhering to any Ministry-specific approvals for working in GitHub


### Appropriate Use 
- When you’re consuming, sharing or contributing content to GitHub in your role as a government employee, you must adhere to the [BC Public Service Standards of Conduct](http://www2.gov.bc.ca/gov/content/careers-myhr/managers-supervisors/employee-labour-relations/conditions-agreements/policy#standards)
- It is essential that [employees avoid any conflicts of interest when using GitHub](https://github.com/bcgov/BC-Policy-Framework-For-GitHub/blob/master/BC-Open-Source-Development-Employee-Guide/COI-Priv-IP.md), and personal use of GitHub must never be confused with professional use
- Make sure you're familiar with existing [OCIO policy on information security](http://www2.gov.bc.ca/gov/content?id=BB7D7F3938634BF2973BDE1A899FB755) before downloading or testing any code
- Be familiar with and follow the various [Appropriate Use](https://github.com/bcgov/BC-Policy-Framework-For-GitHub/blob/master/BC-Open-Source-Development-Employee-Guide/appropriate-use.md) policies, such as the [Social Media Guidelines](http://www.gov.bc.ca/citz/citizens_engagement/some_guidelines_master.pdf) and the [Open Development Standards](http://www2.gov.bc.ca/assets/gov/government/services-for-government-and-broader-public-sector/information-technology-services/standards-files/development_standards_for_information_systems_and_services.pdf)







