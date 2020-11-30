# pinpoint-in-thinkphp

## Steps

> prerequisite 

- [ ] pinpoint-c-agent module installed
- [ ] collect-agent works fine

### 1. Download plugins from pinpoint-c-agent

[ pinpoint-php-plugins.tar.gz ](https://github.com/pinpoint-apm/pinpoint-c-agent/releases/download/v0.4.0/pinpoint-php-plugins-v0.4.0.zip)

### 2. Make it works

#### 2.1 ThinkAdmin

1. copy `Plugins` into root
2. composer update
3. cp `Plugins/Framework/ThinkPHP/setting.ini` into `Plugins`
4. Update `public/index.php` as `Plugins/Framework/ThinkPHP/Readme.md`
5. run `php think run`
