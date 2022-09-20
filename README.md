# Gradingsetup

Bash script for setting up grading enviroment for student delieveries.

## Usage

`$ bash setupscript <obligdir> <templatefile>`

### V 1.0
Creates markdown file based on a template in the script directory.
The directory should be as follows before starting the script:

```
|_ [obligfolder]
    |_ [username]
      |_ [deadline-...]
    |_ [username]
    |  ...
|_ setupscript
|_ [template markdown file]
```

