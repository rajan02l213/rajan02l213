Improvements: 

1) Branch protection Rules - can't push directly to branch(main) without a PR 
2) PR creation start the checks for static code scanning(codeQL), unit tests, code coverage(jacoco), security checks
3) approval form codeowners required for merge
4) Deployment environment rules - conditionally stop the release train for not passing quality threshold (latency of the application & availability of prod servers), add reviwers for environment specific deployments

Governance: 

1) Roles and responsibilities: SRE team to own deployment ownership , Dev team lead being the codeowner for the repo
2) guardrails : direct push is not allowed 
3) One person should not be develope, reviewing and merge code to all the way to production
4) Standardize the practices and protocols for code review and testing
5) Security measures: preactice least privilege - github actions workflow privilege - read and write permissions to repo, create and approve pull requests;
     Secrets management
     

 
