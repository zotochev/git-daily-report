# git-day-report
Bash script for creating report out of commit messages from current git repository for current user.

## Report format
```
<repository-name>:<branch>:
<commit message 1>
<commit message 2>
<commit message 3>
```

## Installation
```bash
./install.sh
```

## Usage
Go to directory with git repository.
```bash
cd <directory-with-git-repository>
```
Run command
```bash
report
```
Also as a first argument supported any [date-like](https://www.gnu.org/software/coreutils/manual/html_node/Examples-of-date.html) argument.
```bash
report yesterday
report today
report 2023-04-07
```

