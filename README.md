# PennApps17-backend
Back end for PennApps F17 project

## Setup instructions

To setup `virtualenv` with Python 3.x, navigate to the root directory of this repo and type:

```
$ virtualenv -p python3 .
```

Activate `virtualenv`:
```
$ source bin/activate
```

Deactivate `virtualenv`:
```
$ deactivate
```

Note: `virtualenv` creates a bunch of directories, which have been added to `.gitignore`. Do not remove them from `.gitignore`.

## Adding and updating dependencies

To add a dependency, simply run `pip3 install <dependency_name>` from within the virtualenv.

Export the list of dependencies:
```
$ pip3 freeze -r requirements.txt > requirements.txt
```

Install or update dependencies from the list:
```
$ pip install -r requirements.txt
```

Warning: Do not remove `requirements.txt` from `.gitignore`!
