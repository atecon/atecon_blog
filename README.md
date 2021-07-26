# Manual for deploying changes
The best manual I found on how to create a github page and deploy is this one:
https://www.youtube.com/watch?v=LIFvgrRxdt4


## Project structure
In my `./content` folder, I have folders for each relevant page type such as `post` and `about`.


Each post has its own directory including an index.md file with the actual content of the thread and e.g. image files. When the site is built, all content gets organized appropriately in the ‘public’ folder.

## Create a new thread
Here of type 'post':
```bash
cd ./atecon
hugo new post/<THREAD_LABEL>/index.md
```

where `<THREAD_LABEL>` might be, for instance, `football_gretl`.

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


# Useful links
- https://mltconsecol.github.io/post/20170123_blogdown_hugo/

- https://www.youtube.com/watch?v=LIFvgrRxdt4
