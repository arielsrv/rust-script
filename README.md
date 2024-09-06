# Usage

## Id

```bash
alias task="export APP_NAME=$(curl --silent -H "PRIVATE-TOKEN: ${GITLAB_TOKEN}" 'https://gitlab.com/api/v4/projects/56219337' |jq .name -r) ; task --taskfile https://raw.githubusercontent.com/arielsrv/rust-script/main/Taskfile.yml"
```

## APP_NAME

```bash
alias task="task --taskfile https://raw.githubusercontent.com/arielsrv/rust-script/main/Taskfile.yml"
```

## file

```bash
alias task="export APP_NAME=$(cat .pets) ; task --taskfile https://raw.githubusercontent.com/arielsrv/rust-script/main/Taskfile.yml"
```

## file

```bash
alias task="export APP_NAME=$(cat .pets) ; task --taskfile https://raw.githubusercontent.com/arielsrv/rust-script/main/Taskfile.yml"
```

## harcoded
```bash
alias task="APP_NAME=go-api task --taskfile https://raw.githubusercontent.com/arielsrv/rust-script/main/Taskfile.yml"
```