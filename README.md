# Introduction

A simple webpage created by Flask and Docker to login and calculate data.


## Run the following commands

pip3 install -r requirements.txt (could be pip instead of pip3)
flask db init
flask db migrate -m 'first migration'
flask db upgrade
Submit the link to the repo on GitHub Classroom here.

## Usage

1. A user goes to the homepage
2. A user clicks on the link for "Calculate Sample"
3. If the user is not logged in they are prompted to login and after login they are redirected to a sample calculation form.
4. The sample calculation form should have a dropdown form control to select the z-score / confidence.
5. Once the user enters the values they should press the submit button and be redirected to a list of sample size calculations that they have previously entered.
