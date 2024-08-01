# Conventional Commits

Conventional commit is a formatting convention that provides a set of rules to formulate a consistent commit message structure. conventional commit is a great practice among engineering teams.

#### An example of a conventional commit message

```
<commit type> [optional scope]: <description>

[optional]

[optional footer(s)]
```

## Commit Type

The commit type can include the following

- **feat** - a new feature is introduced with changes

```
feat : sign up types
```

```
feat : sign up types added

This adds interfaces for the sign up types
```

```
feat: improve performance with lazy load implementation for images
```

```
feat: allow provided config object to extend other configs
```

```
feat(lang): add Polish language
```

- **fix** - patches a bug in the codebase

```
fix: foo to enable bar

This fixes the broken behavior of the component by doing xyz
```

```
fix: crash when user uploads photo for profile

Crash was because uploaded files too large.
```

- **chore** - changes that do not relate to a fix or feature and don't modify src or test files (for example update dependencies)

```
chore : update npm dependency to latest version
```

- **refactor** - refactored code that neither fixes a bug nor adds a feature
- **docs** - updates to documentation such as a README or other markdown files

```
docs: correct spelling of CHANGELOG
```

```
docs: add section about file upload limits

This update is for the internal team docs, only
```

- **style** - changes that do not affecting the meaning of the code, likely related to code formatting such as white-space, missing semi-colons, and so on

```
style: format source files

Forgot to run lint tool for previous commits.
```

- **test** - including new or correcting previous tests
- **pref** - performance improvements
- **ci** - continuous integration
- **build** - changes that affect the build system or external dependencies
- **revert** - reverts a previous commit
- **remove** - remove files in the codebase
