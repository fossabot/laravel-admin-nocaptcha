# laravel-admin-nocaptcha
laravel-admin 登陆集成 nocaptcha

[Document in English](#laravel-admin-nocaptcha-1)


[![travis.svg](https://img.shields.io/travis/xiaohuilam/laravel-admin-nocaptcha/master.svg?style=flat-square)](https://travis-ci.org/xiaohuilam/laravel-admin-nocaptcha)
[![styleci.svg](https://github.styleci.io/repos/179709246/shield?branch=master)](https://github.styleci.io/repos/179709246)
[![version.svg](https://img.shields.io/packagist/vpre/xiaohuilam/laravel-admin-nocaptcha.svg?style=flat-square)](https://packagist.org/packages/xiaohuilam/laravel-admin-nocaptcha)
[![issues-open.svg](https://img.shields.io/github/issues/xiaohuilam/laravel-admin-nocaptcha.svg?style=flat-square)](https://github.com/xiaohuilam/laravel-admin-nocaptcha/issues)
[![last-commit.svg](https://img.shields.io/github/last-commit/xiaohuilam/laravel-admin-nocaptcha.svg?style=flat-square)](https://github.com/xiaohuilam/laravel-admin-nocaptcha/commits/)
[![contributors.svg](https://img.shields.io/github/contributors/xiaohuilam/laravel-admin-nocaptcha.svg?style=flat-square)](https://github.com/xiaohuilam/laravel-admin-nocaptcha/graphs/contributors)
[![install-count.svg](https://img.shields.io/packagist/dt/xiaohuilam/laravel-admin-nocaptcha.svg?style=flat-square)](https://packagist.org/packages/xiaohuilam/laravel-admin-nocaptcha)
[![license.svg](https://img.shields.io/github/license/xiaohuilam/laravel-admin-nocaptcha.svg?style=flat-square)](LICENSE)

## 安装
**composer 安装**

```bash
composer require xiaohuilam/laravel-admin-nocaptcha
```

**初始化配置文件 `config/admin_nocaptcha.php`**

```bash
php artisan vendor:publish --tag=laravel-admin-nocaptcha
```

**配置 .env**

```env
RECAPTCHAV3_SITEKEY=#your recaptcha v3 sitekey
RECAPTCHAV3_SECRET=#your recaptcha v3 scret
RECAPTCHAV3_ORIGIN=https://www.recaptcha.net #For mainlan china user
RECAPTCHAV3_LOGIN_SCORE=0.3 #如果你需要修改验证分数, 修改这里就对了
```

## 演示

![screenshot.png](https://wantu-kw0-asset007-hz.oss-cn-hangzhou.aliyuncs.com/bJVb0m69U3bLO5e7Ymx.png?x-oss-process=image/resize,h_400)

## 授权

基于MIT开源

---

以下为英文说明

---

# laravel-admin-nocaptcha
nocaptcha(recaptcha v3) implment for laravel-admin login

[中文文档](#laravel-admin-nocaptcha)


[![travis.svg](https://img.shields.io/travis/xiaohuilam/laravel-admin-nocaptcha/master.svg?style=flat-square)](https://travis-ci.org/xiaohuilam/laravel-admin-nocaptcha)
[![styleci.svg](https://github.styleci.io/repos/179709246/shield?branch=master)](https://github.styleci.io/repos/179709246)
[![version.svg](https://img.shields.io/packagist/vpre/xiaohuilam/laravel-admin-nocaptcha.svg?style=flat-square)](https://packagist.org/packages/xiaohuilam/laravel-admin-nocaptcha)
[![issues-open.svg](https://img.shields.io/github/issues/xiaohuilam/laravel-admin-nocaptcha.svg?style=flat-square)](https://github.com/xiaohuilam/laravel-admin-nocaptcha/issues)
[![last-commit.svg](https://img.shields.io/github/last-commit/xiaohuilam/laravel-admin-nocaptcha.svg?style=flat-square)](https://github.com/xiaohuilam/laravel-admin-nocaptcha/commits/)
[![contributors.svg](https://img.shields.io/github/contributors/xiaohuilam/laravel-admin-nocaptcha.svg?style=flat-square)](https://github.com/xiaohuilam/laravel-admin-nocaptcha/graphs/contributors)
[![install-count.svg](https://img.shields.io/packagist/dt/xiaohuilam/laravel-admin-nocaptcha.svg?style=flat-square)](https://packagist.org/packages/xiaohuilam/laravel-admin-nocaptcha)
[![license.svg](https://img.shields.io/github/license/xiaohuilam/laravel-admin-nocaptcha.svg?style=flat-square)](LICENSE)

## 安装
**composer install**

```bash
composer require xiaohuilam/laravel-admin-nocaptcha
```

**create `config/admin_nocaptcha.php` by command**

```bash
php artisan vendor:publish --tag=laravel-admin-nocaptcha
```

**change your .env**

```env
RECAPTCHAV3_SITEKEY=#your recaptcha v3 sitekey
RECAPTCHAV3_SECRET=#your recaptcha v3 scret
RECAPTCHAV3_LOGIN_SCORE=0.3 #Change only if you to adjust the score when validation is request from bot
```

## Demo

![screenshot.png](https://wantu-kw0-asset007-hz.oss-cn-hangzhou.aliyuncs.com/bJVb0m69U3bLO5e7Ymx.png?x-oss-process=image/resize,h_400)

## License

Open source under [MIT license](LICENSE).
