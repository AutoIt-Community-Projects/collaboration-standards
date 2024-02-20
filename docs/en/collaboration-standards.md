## Contribution guideline

### Purpose

For projects/repositories, there are several common and recommended guidelines which lead to a stable and understandable way of working with code as a team.

One of the main reasons why this guidance and standards exists is consistency for writing code, also for reviewing code. Otherwise all kinds of styles could be exists which would mislead newcomers and would make the start into the project more difficult.

<br>

### 1. Language

- use english for code, comments, branches, tags, commit messages etc.
- do not mix german and english as long as possible
- but also do not translate german specific names (keep them)

<br>

### 2. Branch naming

**Usage**

- use kebab-style for the branch name
  - all lowercase
  - all words separated by the hyphen

**Examples**

- add-database-connection
- add-login-feature
- apply-common-standards
- fix-prototype-code
- project-restructuring
- remove-obsolete-feature
- update-to-specific-version

**Why**

- consistency
- common way to do it

<br>

### 3. Commit messages

**Usage**

- use the "Keep a Changelog" style (https://keepachangelog.com/en/1.0.0/)
  - \<Keyword\>\<colon\>\<space\>\<Message as a sentence with final punctuation.\>
- Keywords and their purposes
  - **Added** for new features.
  - **Changed** for changes in existing functionality.
  - **Deprecated** for soon-to-be removed features.
  - **Documented** for documentation only changes.
  - **Fixed** for any bug fixes.
  - **Refactored** for changes that neither fixes a bug nor adds a feature.
  - **Removed** for now removed features.
  - **Security** in case of vulnerabilities.
  - **Styled** for changes like whitespaces, formatting, missing semicolons etc.

**Examples**

- `git commit -m "Added: Login feature to main view."`
- `git commit -m "Changed: Adjustment of the GUI layout."`
- `git commit -m "Fixed: Broken label by set on top attribute"`
- `git commit -m "Refactored: Usage of map data type instead of array."`

**Why**

- consistency
- beside "conventional commits" (cc) (https://www.conventionalcommits.org/en/v1.0.0/) is the "Keep a Changelog" style another common way (more easy and more human readable than cc) to deal with
- CHANGELOG.md file can be generated and maintained in an easy fashion

<br>

### 4. Pull requests (merge requests)

<br>

### 5. Code review

<br>

### 6. Version bump (SemVer)

<br>

### 7. Changelog

<br>

### 8. Releases and Tags

<br>

## [Workflows and how-tos](/docs/de/workflows-how-tos.md)
