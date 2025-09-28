# COMP3104 - DevOps

[![CI](https://github.com/SOROUSH911/comp3104/actions/workflows/ci.yml/badge.svg)](https://github.com/SOROUSH911/comp3104/actions/workflows/ci.yml)

## Course Repository
This repository is for COMP3104 DevOps course at George Brown College.

## 🚀 CI/CD Setup
This repository uses GitHub Actions for continuous integration and deployment.

### Features
- ✅ Automated testing with Node.js
- ✅ Multi-version testing (Node 18.x and 20.x)
- ✅ GitHub Pages deployment
- ✅ Pull request validation
- ✅ Build status monitoring

## 📁 Project Structure
```
comp3104/
├── .github/
│   ├── workflows/
│   │   └── ci.yml              # GitHub Actions CI/CD pipeline
│   └── PULL_REQUEST_TEMPLATE.md # PR template
├── build/
│   └── index.html              # GitHub Pages site
├── .travis.yml                 # Travis CI config (legacy)
├── package.json                # Node.js project config
└── README.md                   # This file
```

## 🛠️ Setup Instructions
1. Clone the repository
2. Run `npm install` to install dependencies
3. Run `npm test` to execute tests

## 📊 Pipeline Status
The CI/CD pipeline runs automatically on:
- Every push to main/master branch
- Every pull request

## Student Information
- **Name:** Soroush Salari
- **Course:** COMP3104 - DevOps
- **Term:** Fall 2025
- **Exercise:** 04 - CI/CD Configuration