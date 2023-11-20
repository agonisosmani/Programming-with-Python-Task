# Programming-with-Python-Task 

# Below I will insert all neccesary git commands to perform Task 1.3 
# This task requires to create a branch called develop 
# then clone the repository and develop new features which 
# need to be commited to the branch develop (from the team in their local machines) 

# The commands would look like this: 

class GitHandler:
    def __init__(self, repository_url):
        self.repository_url = repository_url

    def clone_branch(self):
        # Git command to clone the develop branch
        git clone -b develop <https://github.com/agonisosmani/Programming-with-Python-Task>
        pass

    def commit_and_push(self):
        # Git commands to commit and push changes
  
        # git add .
        # git commit -m "Commit message"
        # git push origin develop
        pass

    def create_pull_request(self):
        # Git commands to create a pull request
        
        # git checkout -b feature_branch
        # git add .
        # git commit -m "Commit message"
        # git push origin feature_branch
        
        pass
        
if __name__ == "__main__":
    
    git_handler = GitHandler()

    # Execute Git operations
    git_handler.clone_branch()
    git_handler.commit_and_push()
    git_handler.create_pull_request()
