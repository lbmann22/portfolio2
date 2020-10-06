Leslie's (More Compact) Portfolio Project
---

## To Get Started:

1. Install node and make sure npm (Node Package Manager) is also installed
2. Clone this repo with git clone https://github.com/galloanna/here-ya-go-leslie <your-project-name> to build this repo into your own project or download the zip
3. In terminal, cd (change directory) to the folder containing your project.
4. `git init` for a clean history
5. `npm install` to download dependancies
6. In the terminal, enter `gulp` to make everything run.
7. Take note of the Access URLs provided in your terminal. Your web page should pop up at `http://localhost:3000`. You can access this same page on your various devices in the same wifi network with the provided External URL. You can share the External URL with coworkers and they'll see whats on your screen.
NOTE: If you see missing images the first time you build the project or when you add new images, `imagemin` is likely still running. Wait a few seconds and either refresh the page or re-save the HTML file you're working on.
8. Edit your Sass code inside of the scss folder. You can make subfolders inside of that to better organize your code. Prefix your sass files with an underscore. More info on using @import to organize your files [here](http://sass-guidelin.es/#main-file)
9. Your minified files will be automagically created and updated in `dist/`. It will create your optimized css, html, and javascript files for you. Never edit files within the `dist/` folder. (Dist stands for Distribution)
10. Keep gulp running while you're making changes. When you want to close out of the gulp task, in the terminal, hit `ctrl + C`

## Deploying to gh-pages

You can run `gulp deploy` to push your site onto the gh-pages branch. Then, you can navigate to it via *http://< your-github-username >.github.io/< project-name >* **Note:** this doesn't work if your project name is *< your-github-username  >.github.io*.

## Commonly Confusing Terms

- `cd`: change directory (a terminal command). Make sure you have a space between `cd` and the location you are navigating to
- `repo`: repository (this is a 'repository' of code)
- `sudo`: you get access as a 'super user' of your system (you can override permissions)
- `npm`: node project manager -- the command line task manager that is installing everything inside of `package.json`
- `package.json`: a file with information about your project. This is also where your list of dependencies lives which npm installs
- `gulp`: a [task manager](http://gulpjs.com) that is running a bunch of scripts to make this environment work
- `dist`: distribution folder -- don't edit anything in here. It is where your gulp task builds into
- `scss`: a Sass syntax that imitates CSS
