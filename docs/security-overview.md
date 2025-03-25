# Security Features
Here is a small overview of the most crucial security tests for the second exercise.

## GitHub Dependabot
Dependabot helps keep dependencies up to date by automatically scanning for outdated or vulnerable packages. It creates pull requests with suggested updates, reducing security risks caused by outdated software.
### Key Benefits
- Detects vulnerabilities in dependencies.
- Automatically suggests updates via pull requests.
- Supports multiple package managers (npm, pip, Maven, etc.).

##  Code Scanning (CodeQL)
GitHub’s CodeQL analyzes code for security vulnerabilities and coding errors. It performs static code analysis and helps developers detect potential threats before deployment.
### Key Benefits
- Detects security issues in source code.
- Uses customizable queries to find vulnerabilities.
- Provides automated scanning via GitHub Actions.

## Secret Scanning
Secret Scanning prevents credential leaks by identifying hardcoded secrets such as API keys, passwords, and tokens in repositories. It alerts repository owners when secrets are exposed.
### Key Benefits
- Detects hardcoded secrets before they get misused.
- Works across public and private repositories.
- Can be enforced at the organization level.

## Security Advisories & Alerts
GitHub provides security advisories and alerts to notify developers about known vulnerabilities in dependencies. These alerts are automatically generated and help mitigate risks quickly.
### Key Benefits
- Tracks known vulnerabilities in repositories.
- Notifies maintainers about risks and fixes.
- Enables coordinated disclosure of security issues.
