# Manual for deploying changes
The best manual I found on how to create a github page and deploy is this one:
https://www.youtube.com/watch?v=LIFvgrRxdt4

## Create a new thread
Here of type 'post':
```bash
cd ./atecon
hugo new post/<NAME>.md

```

## Start the web server locally:
```bash
hugo server -D
```

## Deploy changes
This will copy changes made under `./content` to the `./public` folder which is a git submodule of the production repo:
```bash
cd ./atecon
hugo -t <THEME>
```

My current theme is "blackburn".

Now let's push the changes to the production repo:
```bash
cd ./atecon/public
git add .
git commit -m "msg"
git push origin main
```

Wait a few seconds before the changes go live.
