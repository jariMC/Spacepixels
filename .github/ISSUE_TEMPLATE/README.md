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

### Security Report (`security-report.md`)
Use this template to report security vulnerabilities.
- **Intended for**: Collaborators only
- **Automatically applied labels**: `security`
- **Important**: Non-collaborators should contact maintainers privately instead of creating public security issues

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
