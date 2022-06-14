## Start Machine Learning Project.

## Software and Account Requirement.

1. [Github Account](https://id.heroku.com/login)
2. [Heroku Account](https://github.com/)
3. [VS Code IDE](https://code.visualstudio.com/download)
4. [GIT cli](https://git-scm.com/downloads)
5. [Git Documentation](https://git-scm.com/docs/gittutorial)


Creating conda environment

```
conda create -p venv python==3.7 -y
```

To Activate environment

```
conda activate venv/
```

or

```
conda activate venv
```

```
pip install -r requirements.txt
```

To Add files to git

```
git add .
```

or

```
git add <file_name>
```

Note: To ignore file or folder from git we can write name of file/folder in .gitignore file

To check the git status

```
git status
```

To check all version maintained by git

```
git log
```

To  create version/commit all changes by git

```
git commit -m "message"
```

To send version/changes to github

```
git push origin main
```

To check remote URL

```
git remote -v
```
To setup CI/CD pipeline in heroku we need 3 information

1. HEROKU_EMAIL = islamenamul124@gmail.com
2. HEROKU_API_KEY = df80d99f-4cf6-4077-9416-ec233fbdec32
3. HEROKU_APP_NAME = my-first-ml--app


BUILD DOCKER IMAGE

```
docker build -t <image_name>:<tagname> .
```

Note: Image name for docker must be lowercase

To list docker image

```
docker images
```

Run docker image

```
docker run -p 5000:5000 -e PORT=5000 <image id>
```

To check runing container in bdocker
```
docker ps
```

To stop docker image
```
docker stop<container id>
```