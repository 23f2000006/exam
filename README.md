# GitHub Actions Matrix Build Assignment

**Student Email:** 23f2000006@ds.study.iitm.ac.in

## Assignment Overview

This repository demonstrates a GitHub Actions workflow with matrix build strategy and artifact management.

## Matrix Configuration

- **Operating Systems:** ubuntu-latest, macos-latest, windows-latest
- **Node.js Versions:** 14, 16, 18
- **Total Jobs:** 9 parallel jobs (3 OS × 3 Node versions)

## Workflow Features

1. Matrix strategy with 3 different variants (OS and Node versions)
2. Parallel execution of all matrix combinations
3. Each job generates a unique build artifact
4. Artifacts are uploaded with the required prefix `build-ac4a0e2`
5. Step identifier `matrix-ac4a0e2` is included in the workflow

## Validation Checklist

- ✅ At least 3 successful matrix jobs in the latest run
- ✅ At least 3 artifacts uploaded with prefix `build-ac4a0e2`
- ✅ All artifacts contain actual content (non-empty)
- ✅ At least one step includes the identifier `matrix-ac4a0e2`
- ✅ Repository contains README.md file with email address

## How to Use

1. Update the email address in this README.md file
2. Push to GitHub to trigger the workflow
3. Check the Actions tab to see the matrix build in action
4. Verify artifacts are generated and uploaded successfully
