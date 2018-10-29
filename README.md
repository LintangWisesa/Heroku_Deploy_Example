![simplinnovation](https://4.bp.blogspot.com/-f7YxPyqHAzY/WJ6VnkvE0SI/AAAAAAAADTQ/0tDQPTrVrtMAFT-q-1-3ktUQT5Il9FGdQCLcB/s350/simpLINnovation1a.png)

# Deploy NodeJS (Express App) to Heroku

### Heroku ([https://www.heroku.com/](https://www.heroku.com/)) is a container-based cloud Platform as a Service (PaaS). Developers use Heroku to deploy, manage, and scale modern apps. This platform is elegant, flexible, and easy to use, offering developers the simplest path to getting their apps to market. In this repo, I'll share the example of Node.js app (using Express) that can be deployed to Heroku. Follow my instructions below. Happy hacking!

![simplinnovation_heroku](https://1.bp.blogspot.com/--CYt_O2JQNw/WsnI-GsvdwI/AAAAAAAAD-o/ForjXhspfuAwrtNm0R_wmnDxahnsOuiSwCLcBGAs/s320/heroku.png)

#### 1. Create an account by sign-up/login to [Heroku](https://www.heroku.com/).

#### 2. Install Heroku CLI (Command Line Interface) globally then login:

```shell
  $ npm install -g heroku
  $ heroku --version
  $ heroku login
```

#### 3. Clone the Node.js boilerplate from my repo:

```shell
  $ git clone https://github.com/LintangWisesa/Heroku_Deploy_Example.git
```

#### 4. Go to the repo then install all packages needed:

```shell
  $ cd Heroku_Deploy_Example
  $ npm install
```

#### 5. Edit Express app route on index.js! Make sure there is no error on your app by running index.js. Server will be running by default on localhost:5000!

```shell
  $ node index
```

#### or simply type:

```shell
  $ npm start
```

#### Open *localhost:5000* via browser, then try also to open *localhost:5000/something*. If everything's fine, the response will be similar to the picture below:

![simplinnovation_ok](
https://raw.githubusercontent.com/LintangWisesa/Heroku_Deploy_Example/master/heroku_local.png)

#### 6. After that, create git repo locally then commit it:

```shell
  $ git init
  $ git add .
  $ git commit –m "tes deploy heroku"
```

#### 7. Create Heroku project

```shell
  $ heroku create

    Creating app... done, ⬢ your_url_to_deploy
    https://your_url_to_deploy.herokuapp.com/ |
    https://git.heroku.com/your_url_to_deploy.git
```

#### 8. Last step: deploy!

```shell
  $ git push https://git.heroku.com/your_url_to_deploy.git master
```

#### Try to open that URL via browser. Finish! Your app has just been deployed!

![simplinnovation_online](
https://raw.githubusercontent.com/LintangWisesa/Heroku_Deploy_Example/master/heroku_online.png)

### More information [click here](https://devcenter.heroku.com/articles/getting-started-with-nodejs#introduction).

#

#### Lintang Wisesa :love_letter: _lintangwisesa@ymail.com_

[Facebook](https://www.facebook.com/lintangbagus) | 
[Twitter](https://twitter.com/Lintang_Wisesa) |
[Google+](https://plus.google.com/u/0/+LintangWisesa1) |
[Youtube](https://www.youtube.com/user/lintangbagus) | 
:octocat: [GitHub](https://github.com/LintangWisesa) |
[Hackster](https://www.hackster.io/lintangwisesa)
