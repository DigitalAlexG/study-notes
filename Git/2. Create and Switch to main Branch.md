# Create and Switch to main Branch
**1. Check Current Branch**: First, check which branch you are currently on by using the following command:

```
git branch
```
If main branch is not listed, you'll need to either create a new main branch or rename your current branch to main.

**2. Create and Switch to main Branch**: If you haven't made any commits yet, you can create and switch to the main branch directly:

```
git checkout -b main
```
**3. Add and Commit Changes**: If you haven't already added and committed your changes, do so with the following commands:

```
git add .
git commit -m "Initial commit"
```
**4. Push to Remote Repository**: Now you should be able to push your code to the main branch:

```
git push -u origin main
```
## Here's a complete example workflow:

```
cd /path/to/your/project
git init
git checkout -b main
git remote add origin https://github.com/DigitalAlexG/Kids_Coding.git
git add .
git commit -m "Initial commit"
git push -u origin main
```
