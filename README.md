# DBWorkout

## Introduction
Our platform gamifies SQL learning, turning it into an engaging, interactive experience. Students practice SQL commands in real-time, track progress on a leaderboard, and receive instant feedback. This fosters motivation, collaboration, and skill development by giving instructors insights into performance, preparing students for technical careers

## Prerequisites
Ensure you have the following installed on your system:
- [Language/Runtime] (e.g., Node.js v16+, Python 3.8+)
- [Database] (if applicable)
- [Package Manager] (e.g., npm, pip)

---

## Getting Started

### 1. Clone the Repository
First, fork this repository to your own GitHub account. Then clone your fork:
```bash
git clone https://github.com/<your-username>/<repo-name>.git
```

then add upstream :
```bash
git remote add upstream https://github.com/ashutoshvt2024/DBWorkout.git 
git remote  -v # Verify remotes 
```

Expected output: 
```bash
origin    https://github.com/YOUR-USERNAME/DBWorkout.git (fetch) 
origin    https://github.com/YOUR-USERNAME/DBWorkout.git (push) 
upstream  https://github.com/ashutoshvt2024/DBWorkout.git (fetch) 
upstream  https://github.com/ashutoshvt2024/DBWorkout.git (push) 
```
If your output matches, it means your repository upstream is set correctly.

### 2. Create a New Feature Branch 
Always create a new branch from dev before making changes. 

1. Fetch the latest updates from dev: 
```bash
git fetch upstream 
git checkout dev 
git pull upstream dev 
```

2. Create a new branch for your feature/fix: 
```bash
git checkout -b feature-xyz
```

### 3. 