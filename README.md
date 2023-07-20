# Brand NEW repository 🚀
**2023 Summer SKKU GitHub Class**

This project is to learn GitHub in a fun way! :octocat: 🐱 🐙

![GitHub_character](https://f4n3x6c5.stackpathcdn.com/article/what-is-git-github-and-github-desktop-and-create-a-git-repository-in-github-usi/Images/github.png)

## Describe 
1. Start spreading the news
2. I'm leaving today
3. I want to be a part of it
4. [**New York, New York 🗽**](https://en.wikipedia.org/wiki/Theme_from_New_York,_New_York)

---

- [Fly me to the moon](https://en.wikipedia.org/wiki/Fly_Me_to_the_Moon)
- Let me play among the stars
- Let me see what spring is like on Jupiter and Mars
- In other words, hold my hand
- In other words, baby kiss me

## Step by Step

### Step 1: Enter a directory

```bash
# Enter the GitHub directory
cd GitHub

# Next, execute the script
python test.py

```

### Step 2: Execute

```java
public class Test {
  public static void main(String[] args){
    System.out.println("Hello, GitHub!");
  }
}
```

### American Famous 3 Airlines

| # | Name | Info.|
|--------|------|------|
| 1 | Delta Air Lines | [Delta](https://www.delta.com) |
| 2 | American Airlines | [American](https://www.aa.com) |
| 3 | United Airlines | [United](https://www.united.com) |


## How to write branch names efficiently
- main/master: Default branch. Protect safely with 'Branch Protection' and set it not to merge directly.
  
- development branch or other stage branch: Following the DevOps model, modeling branches like DEV. UAT. PROD. For example, the 'main' branch is tested on the 'dev' or 'uat' branch, safely deployed on the 'prod/release' branch, and then merge.
  
- feature-xxx branch: Used to add new features, but set not directly merge to the main/master branch. Works with project management tasks such as JIRA.
  
- hotfix-xxx branch: Branches for fixing critical errors or bugs in Production environments. Feature branches can also be linked to project management tasks such as JIRA.

## Various Git Branch Model
**1. GitHub flow**

Only main and feature branches.
![GitHub_flow](https://oopy.lazyrockets.com/api/v2/notion/image?src=https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F00952fcf-5735-4b2e-b165-6dc9fa3fdc86%2FUntitled.png&blockId=f190f796-a6da-499a-97b1-ffbbed8ea24a)

**2. GitLab flow**

Similar to GitHub Flow, but has a separate production branch for deployment.
![GitLab_flow](https://blog.kakaocdn.net/dn/cKg4cN/btrsC9Iih0f/Xl7RoK2KfrzWVkWttjfKNk/img.png)

**3. Trunk-based**

Some fixed-lasting branches, and merge in the same main branch.
![Trunk-based](https://www.abtasty.com/wp-content/uploads/trunk-based-development-branching-strategy.png)

**4. GitFlow**

The most commonly used branch model in the company. In the main branch, only the hotfix branch can change, and the feature branch merges with the development branch
![GitFlow](https://techblog.woowahan.com/wp-content/uploads/img/2017-10-30/git-flow_overall_graph.png)
