# Issue Templates

This directory contains issue templates for the Spacepixels repository.

## Security Settings

The issue templates are configured with the following security settings:

### What Users Can Do:
- ✅ Create new issues using the provided templates
- ✅ Fill out the form fields in the templates
- ✅ View and comment on existing issues

### What Users Cannot Do:
- ❌ Edit or remove the automatically applied labels
- ❌ Delete issues (requires write access)
- ❌ Create blank issues without using a template

## Available Templates

### Bug Report (`bug-report.yml`)
Use this template to report bugs or issues with the project.
- **Automatically applied labels**: `bug`, `invalid`
- **Required fields**: What happened, Expected Behavior, Steps to Reproduce

### Feature Request (`feature-request.yml`)
Use this template to suggest new features or enhancements.
- **Automatically applied labels**: `feature request`
- **Required fields**: Problem Description, Proposed Solution

### Security Report (`security-report.yml`)
Use this template to report security vulnerabilities.
- **Intended for**: Collaborators only (low-risk or public security concerns)
- **Automatically applied labels**: `security`
- **Important**: For sensitive security issues, prefer GitHub's private Security Advisories feature instead of public issues
- **Required fields**: Vulnerability Description, Affected Component, Severity Level, Steps to Reproduce, Impact

## Configuration

The `config.yml` file disables blank issue creation, ensuring all issues are
created using one of the templates above.

## Technical Implementation

These templates use GitHub's YAML-based issue forms which provide:
1. **Locked labels**: Labels specified in the template are automatically
   applied and cannot be modified by issue creators
2. **Structured input**: Form fields ensure consistent issue formatting
3. **Validation**: Required fields must be completed before submission

## Permissions

Issue deletion and label management require write access to the repository,
which is restricted to collaborators, maintainers, and administrators.

## Security Reporting Best Practices

While a public security report template is available for collaborators, it is
**strongly recommended** to use GitHub's private Security Advisories feature
for reporting sensitive security vulnerabilities. This ensures:
- Vulnerabilities are not disclosed publicly before patches are available
- Repository maintainers can coordinate fixes privately
- Users are protected from exploitation during the remediation process

The public security template should only be used for:
- Low-risk security concerns
- Security issues that are already publicly known
- Security-related discussions that don't involve active vulnerabilities
