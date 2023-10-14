# Techligence
Logicblocks: A Blockly-Based Application🎮
Logicblocks is a web application designed to provide a Blockly-based interface for learning and building block-based code. This application is built with ReactJS and integrates Google's Blockly library.

Before starting ensure the following pre-requisites are met, if not you can download them from the link below.
1. [Git](https://git-scm.com/downloads)🐱‍💻
2. [nodeJS](https://nodejs.org/en/download)🟢

## Getting started🌟
### Steps  
1.Clone the Repository: This will download a copy of the code onto your local machine.
```
git clone https://github.com/bhaveshsirvi/Techligence.git

#Navigate to the directory
cd Techligence
```
2. Install dependencies and run a local development server🛠️ 
```
#Install all the dependencies mentioned in the 'package.json' file
npm install

#Start the development server
npm run dev
```
### Troubleshooting🚧

If you encounter any errors, make sure you have the latest versions of Node.js and npm, and try running the commands again.

If that still does not work [contact us](mailto:bhaveshsirvi876@gmail.com).


## Contributing👩‍💻👨‍💻
### Getting Started with Git🐱‍👤
After installing Git, open your terminal ("Git Bash" for Windows or the terminal for Linux and macOS). Configure Git by executing the following commands:
```
# Set your global username
git config --global user.name "Your Name"

# Set your global email
git config --global user.email "youremail@example.com"

# Add the remote directory to your local repository
git remote add origin https://github.com/bhaveshsirvi/Techligence.git

# Fetch updates from the main repository
# (Note: Make sure you are on the main branch before updating)
git fetch origin

```
Congratulations, you're all set to contribute to the project! 🎉
### Creating a New Feature Branch

Start by creating a new branch following the naming convention feature/feature-name. ```git checkout {branchname}``` allows to switch between branches.
```
# Create and switch to a new feature branch🌿
git checkout -b feature/<feature-name>

# Stage all modified files
git add .

# Commit your changes
git commit -m "Your descriptive commit message here"

# Push your changes to the remote repository
git push origin feature/<feature-name>
```

You will be prompted for your GitHub username and password after this.

### Authentication Issues🔒
If you encounter any errors while proceeding, perform the following steps to generate a new personal access token:
1. **Log in to your GitHub account**. 👤
2. **Navigate to Settings**:
   - Click on your profile picture in the upper-right corner.
   - Select "Settings." ⚙️
3. **Access Developer Settings**:
   - In the left sidebar, click on "Developer settings." 👨‍💻
4. **Go to Personal Access Tokens**:
   - In the left sidebar again, click on "Personal access tokens."
   - Select "Tokens(Classic)." 🗝️
5. **Generate New Token**: 
   - Click on "Generate new token." ➕
6. **Set a Token Name**: 
   - Enter a descriptive name for your token in the "Note" field. 📝
7. **Set Permissions**: 
   - Under "Scopes," select the permissions your token needs. For general Git operations, "repo," "read:org," "write:org," are usually sufficient. ✅
8. **Create Token**: 
   - Scroll down and click "Generate token." 🟢
9. **Copy Token**: 
   - Copy the generated token and keep it secure. You won't be able to see it again. 🔒
10. **Use Token for Authentication**: 
    - After executing the `git push` command, enter your username as usual. Use the token as your password when prompted. 🛡️


Nearly there! 🌈

### Creating a Pull Request🤝
To let use us know that you are done just start a new pull request from your github account which should be visible as such 
![image](https://github.com/bhaveshsirvi/Techligence/assets/79744815/ac428199-9ee5-459b-afc2-be053c4b3d55)
Follow the steps and write a short description about your feature this will count as your final submission.

You're all done! Now, sit back, relax ☕, and await your next task or feedback in case there are some issues with your work.











































