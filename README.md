**Do not change password in heroku env (But use to login)**


## To install a new python dependency:
Open a terminal tab and type the following:
```sh
pipenv install <PACKAGE_NAME>
```
Ensure you update the Pipenv and Pipenv.lock files
```sh
cat Pipenv
# Copy contents to local repo
cat Pipenv.lock
# Copy contents to local repo
```
On your local repo
```sh
git add Pipenv Pipenv.lock
git commit -m "added new python dependency"
git push origin master
```
