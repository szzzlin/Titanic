# Titanic Project

## Setup

1. Install the dependencies

If you are using pip as a package manager, do:
``` python -m venv venv``` then ```pip install -r requirements.txt```

If you are using conda as a package manager, do:
```conda create --name <env> --file requirements.txt```


2. You are now good to go

## Workflow when starting a new project

1. Create a virtual env
``` conda create --name venv ```

2. Install dependencies using 
```conda install <whateverlib>```

3. Then do to set up requirements.txt:
```conda list -e > requirements.txt```

## When you wanna push your changes

1. Update dependencies on reuirements.txt
```conda list -e > requirements.txt```

2. Stage changes locally (Ensure that you are in the correct working directory)
```git add .```

3. Commit Changes
```git commit -m "<your commit message>"```

4. Push changes
```git push```