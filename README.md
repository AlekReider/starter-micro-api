# **Documentation parser script**

## Table of Contents

1. Prerequisites
2. Installation
3. Usage

## 1. Prerequisites

Before you begin, ensure you have the following:

- Node.js (v18 or newer)
- The Olympe Documentation Service Application is running

## 2. Instalation

### Step 1: Install Dependencies

```bash
npm install
```

### Step 2: Set Environment Variables

```bash
cp .env_example .env 
```

Set value of the *HOST* environment variable equals the host of the Olympe Docs Service app in .env file 

## 3. Usage

```bash
node parser --rootTags rootTag1,rootTag2 --projects projectName1,projectName2 ---outPaths outPutDir1,outputDir2
```

rootTags and --projects are required. \
if you don't pass --outPaths generated docs files will be stored in the current parser directory
