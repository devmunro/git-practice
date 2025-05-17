# Git Practice Instructions

Welcome to the Git practice repository!

## Steps to Complete the Task

### 1a. Fork This Repository - HOWEVER if you are a collaborator then you can just directly clone this repo

Click the "Fork" button at the top-right corner of this repository to create your own copy on GitHub.

### 1b. Clone Your Own Fork -

Clone your forked repository to your local machine using SSH key:

```bash
git clone git@github.com:youraccountname/yourgitreponame.git
cd <repo-name>
```

### 2. Create a New Branch

Create a new branch for your work (e.g. feat-add-your-name-file:

```bash
git checkout -b feat-add-your-name-file
```

### 3. Add Your File

Create a new file inside the folder 'add_file_here' named after your name or nickname (e.g., `john_doe.py`).

Inside the file, add a simple function. For example:

```python
# john_doe.py

def greet():
    """Returns a simple greeting."""
    return "Hello from John Doe!"
```

### 4. Commit Your Changes

Stage and commit your file (remember add your file, not the example john_doe.py):

```bash
git add john_doe.py
git commit -m "Added john_doe.py with a greet function"
```

### 5. Push Your Changes

Push your branch to your forked repository:

```bash
git push -u origin feat-add-your-name-file
```

### 6. Create a Pull Request

Go to the original repository on GitHub. (davemasterschool)

Click the "Pull Requests" tab, then "New Pull Request."

Select your branch from your forked repository and propose your changes.


## Example Output

If your name is John Doe, the repository will now include a file named `john_doe.py` with the following content:

```python
# john_doe.py

def greet():
    """Returns a simple greeting."""
    return "Hello from John Doe!"
```
## Important Notes

- **File Naming**: Use only lowercase letters, numbers, and underscores in your filename (e.g., `jane_smith.py`).
- **Function Format**: Add a simple function with a docstring explaining what it does.
- **Avoid Conflicts**: Ensure you only edit your file to avoid merge conflicts.

 If you have any questions, feel free to ask for help! Happy coding!
