# bitebody-flask-api
Team Late's back-end API for bitebody.xyz created with Flask (Python micro-framework).

Created by **Bryan Rojas**, **Hector Mendoza**, **Malik Coleman**, **David Ibarra**

## Prerequisites

### Specifications & Tools
* 64-bit environment (Trying to make it system agnostic)
* [Git](https://git-scm.com/downloads)

### Back-end
* [Python 3.7.x](https://www.python.org/downloads/)
* [Pip](https://pip.pypa.io/en/stable/installing/)

## Downloading Application

1. Ensure git is installed on computer. You can verify by running the following command on your terminal.
```
git --version
```
2. Clone the GitHub repository.
```
git clone https://github.com/Bite-Body/bitebody-flask-api.git
```

## Prerequisites

1. Verify you have Python 3.7.x, open up terminal and run the following command.
```
python -V
```
2. If on windows, run powershell as an Administrator, set the execution policy. Type 'Y' after you execute this command.
```
Set-ExecutionPolicy RemoteSigned
```
3. Install pipenv
```
py -m pip install pipenv
```


## Running Application

1. Change directory (cd) into the project folder.
```
cd bitebody-flask-api
```
2. Install Python dependencies.
```
pipenv install
```
3. Run pipenv shell
```
pipenv shell
```
4. Running the API server.
```
python manage.py
```
