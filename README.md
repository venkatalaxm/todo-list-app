# todo-list-app# Go to your local directory
cd todo-list-app

# Create an initial README file
echo "# Todo List App" > README.md

# Initialize Git and add the files to the repository
git init
git add README.md
git commit -m "Initial commit: Added README.md"

# Push the changes to GitHub
git branch -M main
git remote add origin https://github.com/your-username/todo-list-app.git
git push -u origin main
