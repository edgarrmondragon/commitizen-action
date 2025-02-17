## 0.13.2 (2022-05-11)

### Fix

- Don't quote the > operator in entrypoint.sh
- Don't quote the > operator in entrypoint.sh
- Follow Bash best practices in entrypoint
- Configure git pull to rebase instead of merge
- Configure git pull to rebase instead of merge

### Refactor

- Remove unnecessary --follow-tags
- Get current Git branch more simply

## 0.13.1 (2022-05-10)

### Fix

- Correct default branch from master to current

## 0.13.0 (2022-05-04)

### Feat

- add no-raise option
- add no-raise option

## 0.12.0 (2022-02-24)

### Feat

- add commitizen version input
- add commitizen version input

### Refactor

- rename cz version variable

## 0.11.0 (2021-12-18)

### Feat

- detect default branch
- detect default branch

## 0.10.0 (2021-11-17)

### Feat

- add `commit` and `push` inputs

## 0.9.0 (2021-09-14)

### Feat

- add version output

## 0.8.0 (2021-08-30)

### Fix

- removed id from default git_email

### Feat

- support  custom git config

## 0.7.0 (2021-03-08)

### Feat

- add support for `--changelog-to-stdout`

### Fix

- use commitizen-tool action instead of Woile's

## 0.6.0 (2021-02-06)

### Feat

- add pull before pushing to avoid error with remote with new changes

## 0.5.0 (2020-12-02)

### Feat

- add extra_requirements parameters instead of reading the requirements.txt file

## 0.4.0 (2020-11-24)

### Feat

- add echo Commitizen version to better debug (#4)

## 0.3.0 (2020-10-05)

### Feat

- add prerelease option

## 0.2.1 (2020-10-04)

### Fix

- **entrypoint**: typo correction

## 0.2.0 (2020-08-13)

### Feat

- change tag format

## 0.1.0 (2020-08-13)

### Feat

- add parameters `github_token`, `repository` and `branch`
- introduce github action

### Fix

- **entrypoint**: add git user and email
- add 'yes' arg to bump
- remove tag format
