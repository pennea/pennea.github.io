#Setup and usage
##Install jekyll
Linux, Mac, Windows.

## Clone the repo
```
cd location/to/hold/repo
git clone git@github.com:pennea/pennea.github.io.git
```

## Basic local usage
To launch a local webserver that will build and show the site, as well as watch for any changes, run this from the command line:
```
cd path/to/pennea-repo
jekyll serve
```
Leave that terminal window running (you can see it rebuilding the site every time you edit a file) and point your browser to `http://localhost:4000`.

## Testing for launch
You can run `jekyll` under the same conditions as Github Pages will.

## Publishing to the web
Just push your changes to the github repo and github will do the rest.

# Tips

- 'for loops' go in reverse filename order, so posts -- which are named by date -- get displayed newest first
