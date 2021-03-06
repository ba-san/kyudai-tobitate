[![Netlify Status](https://api.netlify.com/api/v1/badges/827bdc95-30ed-4b70-8274-ad70207f4bd1/deploy-status)](https://app.netlify.com/sites/kyudai-tobitate/deploys)

# 保守メモ

URL変えたら以下のページのURLも変更  
https://github.com/ba-san/kyudai-tobitate/blob/master/layouts/partials/sidebar.html  
https://github.com/ba-san/kyudai-tobitate/blob/master/layouts/partials/header.html  
  

## 現状の問題
→ログイン機能(ログイン後のページ遷移などは自分で書かないといけない)

とまりぎも参考に

申請にかかるアドバイスやTips

見出しの余白→とりあえず，大した問題でもないので放置  


~~実際に運用するときは，GitのページはPrivateにすること~~

## 有料化(主にNetlify)しないとできないこと  
独自ドメイン，HTTPS化（セキュリティ的にも重要）  
ビルドの制限解除，Webページのプライベート化(パスワードで閲覧可能にするなど)(Netlifyの機能としての話だが)，  

# Easy Setup (Hugo + Netlify + Forestry)
Build your website with Parsa hugo theme by following this easy steps (No Coding Required)

<a href="http://bit.ly/meghna-hugo-installation" target="_blank" title="meghna hugo installation" rel="nofollow"><img width="100%" src="https://user-images.githubusercontent.com/37659754/70844354-4028be00-1e6a-11ea-8d84-02e9a25e7db8.png"></a>

In this tutorial we will show you to make your website live without buying any hosting and touching a single line of code. We made this tutorial based on [meghna hugo](https://github.com/themefisher/meghna-hugo) but you can setup everithing like this.

### What you need !!

1. Git acccount (Ex: Github, Gitlab etc ) . In our case we use github.
2. [Netlify](https://bit.ly/netlify-account) account to host files and add custom domain .
3. [Forestry](https://bit.ly/forestry-account) account to maintain whole project without code.


### Step 1 : Fork or Clone repository

First we will fork this [parsa hugo](https://github.com/themefisher/parsa-hugo) template.

### Step 2 : Add your repository in Forestry

Go to your [forestry](https://bit.ly/forestry-account)  account and click on `import your site now`. declare your config.toml file [`exampleSite`] and fill up basic settings . Mark everything is done then go to configuration to change the base url . You can put any url but this have to similar as netlify . So for now put a name which you are going to put in netlify as netlify subdomain.

### Step 3 : Setup and host website with Netlify

Here comes the last step . Go to your [netlify](https://bit.ly/netlify-account) account and click add new site . Choose your git repository to import your website in netlify .  And now you can see the forked `parsa hugo` theme. select it and follow the steps. Then go to `site settings` for change the site name and put your subdoamin name here what you puted on forestry as base url. save it and go to `deploy` from top menu, Wait a while and click on `site preview` or just simply go to the subdomain you puted as base url. **BOOM! Your site is live.** Now you can go to forestry and add, remove or customize every setting and content.

> If you face any issue regarding the installation feel free to onen [open a new issue](https://github.com/themefisher/parsa-hugo/issues)


## Table of Contents

- [Demo](#demo)
- [Installation](#installation)
- [Reporting Issues](#reporting-issues)
- [Technical Support or Questions](#technical-support-or-questions-(paid))
- [Licensing](#licensing)
- [More Hugo Themes](https://themefisher.com/hugo-themes/)


## Demo

| ![](https://user-images.githubusercontent.com/37659754/58609653-2c50ac80-82ca-11e9-9f42-887141a0f6dd.png) | ![](https://user-images.githubusercontent.com/37659754/58609715-7043b180-82ca-11e9-9225-dfc9d255f516.png) | ![](https://user-images.githubusercontent.com/37659754/58609747-894c6280-82ca-11e9-9253-d1256af4aad9.png) | ![](https://user-images.githubusercontent.com/37659754/58609762-9cf7c900-82ca-11e9-9956-53e6a3b65636.png) | ![](https://user-images.githubusercontent.com/37659754/58609777-ac771200-82ca-11e9-9814-9e1fc7404b91.png) |
|---|---|---|---|---|
| Homepage  | Homepage 2  | Single  | About  | Contact  |


**The images are only for demonstration purpose, Please don't use those images.**

[Live Preview](http://demo.themefisher.com/parsa-hugo/).


## Installation
At the top we have shown an easy hugo installation. but still if you think you want to go with the traditional way then use the following commands:

**Note : You must use `hugo-extended` version to compile SCSS**

```
$ git clone git@github.com:themefisher/parsa-hugo.git
$ cd parsa-hugo/exampleSite/
$ hugo server --themesDir ../..
```

## Reporting Issues

We use GitHub Issues as the official bug tracker for the **Parsa Theme**. Please Search [existing issues](https://github.com/themefisher/parsa-hugo/issues). It’s possible someone has already reported the same problem.
If your problem or idea is not addressed yet, [open a new issue](https://github.com/themefisher/parsa-hugo/issues/new)

## Technical Support or Questions (Paid)

If you have questions or need help integrating the product please [contact us](mailto:mehedi@themefisher.com) instead of opening an issue.

## Licensing

- Copyright 2020 Designed by [Themefisher](https://themefisher.com/) & Developed by [Gethugothemes](https://gethugothemes.com/)
- Licensed under MIT (https://github.com/themefisher/parsa-hugo/blob/master/LICENSE)
