# HomePage-set

[中文版说明](<README.zh_CN.md>)

## Introduction

> A modern and elegant personal homepage with fluid animation background, responsive design and smooth page transitions.

![preview](https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExMncyb3oyc21zc3czejU3cGk4M2tiNTdkaTM0N3FodGVpZmU5azNxaCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/fhXFCZEogq39rOpKUi/giphy.gif)

[Online browsing](http://simonaking.com)

Do you want to install such a cool homepage for your website?

Let's start now!

## Deployment

After executing `npm run build` under the root directory, the project file will be generated to the `dist` directory.

You can then deploy the dist directory to your favorite server hosting provider.

The following is an example of `GithubPage`:

1. create `userName.github.io` Repo

2. ```sh
   cd dist
   git init
   git add -A
   git commit -am"init"
   git remote add origin https://github.com/userName/userName.github.io.git
   git push -f origin master
   ```

3. Then set the repo's Github Page option in GitHub.

4. Visit `username.github.io` to browse!



If your previous `username. github.io` repo already has content, you can create another repo, such as `blog`.

 Then migrate the occupied items to `blog` and set the `GithubPage` option for this repo.

 The repo became a subdirectory of `username. github.io/blog`.

 In this way, your `username. github.io` repo can be left to the home page!

## Sponsor
I spent a lot of time and energy to develop this project.

If this project has brought you help, welcome to sponsor, `star`.
