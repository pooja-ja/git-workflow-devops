# Git-Workflow

A hands-on repo to learn Git workflow from scratch.

## What's Inside

This repo contains a **Flask web app** with git workflow

```
git-commands.md         → Useful commands to work with git 
app.py                  → Flask app (source code)
Dockerfile              → Container image definition
docker-compose.yml      → Production deployment config
templates/index.html    → App frontend
requirements.txt        → Python dependencies (flask, flake8, bandit, gunicorn, pytest)
test_app.py             → Route tests (pytest)
  
```

###  Key Features

1. `main` stable branch
2. `dev` integration branch
3. Task specific `feature/*` barnch
4. .gitignoore
5. Pull request based merging
6. Git release tagging
7. Markdown documentation


###  Git Branching Strategy
```
feature/* or fix/*
      ↓
 pull request
      ↓
     dev
      ↓
  pull request       
      ↓
     main
```
Branch Types with purpose

| # | Branch | What It Does |
|---|---------|-----------------|
| 1 | main | stable and release ready project content |
| 2 | dev | Integration branch acts as a staging point before main|
| 3 | feature/* | Focuses on specific task|
| 4 | fix/* | hotfixes maintenance work |


The log onelines as below

![snapshot](images/1.jpeg)
