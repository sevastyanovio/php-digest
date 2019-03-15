# PHP Дайжест #19: 

## Основне
* [Symfony Gets Real-time Push Capabilities!](https://symfony.com/blog/symfony-gets-real-time-push-capabilities) 
* [Подкаст з Nikita Popov, інтервьювить Derick Rethans (засновник Xdebug)](https://derickrethans.nl/phpinternalsnews-01.html) – говорять про новий RFC Saner string to number comparisons
* [Intro to basic web application security (PHP)](https://www.raeder.technology/post/intro-to-basic-web-application-security) – хороший гайд про основні помилки в безпеці
* [Як я гейміфікував тести на PHP і пройшов від 0% охоплення до 93% за 30 днів](https://technex.us/2019/02/how-I-gamified-unit-testing-my-php-framework-and-went-from-zero-percent-unit-test-coverage-to-93-percent-in-30-days/)
* [Moving away from magic – АБО: чому я більше не хочу використовувати Laravel](https://medium.freecodecamp.org/moving-away-from-magic-or-why-i-dont-want-to-use-laravel-anymore-2ce098c979bd)
* [Оптимізуємо швидкість роботи РНР](https://dev.to/elabftw/optimizing-your-php-app-speed-3hd4)
* [Design Microservice Architectures the Right Way](https://www.youtube.com/watch?v=j6ow-UemzBc)
* [Hand-written service containers](https://matthiasnoback.nl/2019/03/hand-written-service-containers/)
* [Keeping (large) data providers organized in PHPUnit ](https://dev.to/erikbooij/keeping-large-data-providers-organized-in-phpunit-983)
* [Getting the most out of server side caching ](https://dev.to/erikbooij/getting-the-most-out-of-server-side-caching-35o7)
* [Comparing PHP’s Autoload](https://dev.to/jorgecc/comparing-phps-autoload-176a)


## PHP RFC
[[7.4] Arrow Functions 2.0](https://wiki.php.net/rfc/arrow_functions_v2):
Такий код:
![](https://i.imgur.com/K4fqM3T.png)
Можна буде написати так (як в JS):
![](https://i.imgur.com/G5mw28a.png)

[[8.0] Saner string to number comparisons](https://wiki.php.net/rfc/string_to_number_comparison):
Пропонується змінити перетворення string в number при зрівнюванні:
![](https://i.imgur.com/pt6uJOy.png)
![](https://i.imgur.com/rp06zyx.png)

## Релізи
* [PHP 7.3.3](http://php.net/ChangeLog-7.php#7.3.3)
* [PHP 7.2.16](http://php.net/ChangeLog-7.php#7.2.16)
Список основних змін у PHP 7.3.3 та PHP 7.2.16:
    1) MySQL: Disabled LOCAL INFILE by default, can be enabled using php.ini directive mysqli.allow_local_infile for mysqli, or PDO::MYSQL_ATTR_LOCAL_INFILE attribute for pdo_mysql.
    2) PDO_OCI: Support Oracle Database tracing attributes ACTION, MODULE, CLIENT_INFO, and CLIENT_IDENTIFIER.
    3) Bug fixes.
* [PHP 7.1.27](http://php.net/ChangeLog-7.php#7.1.27) – баг фікси.
* [Xdebug 2.7.0](https://xdebug.org/#2019_03_06) – підтримка PHP 7.3.3.

## Open source
* [Компілятор РНР (ircmaxell/php-compiler)](https://github.com/ircmaxell/php-compiler)
* [Генеруємо піксельні карти з РНР (IndyIndyIndy/landmap-generation)](https://github.com/IndyIndyIndy/landmap-generation)
* [Оптимізуємо зображення (spatie/image-optimizer)](https://github.com/spatie/image-optimizer)

## Різне

![](https://external-preview.redd.it/QwBEUJsg-0SmChi8V1DyCtk5ECUFViDcZya8m_xUCcA.jpg?width=640&crop=smart&auto=webp&s=8443fafcb161193c82f0aeae9098f3c18468aef9)
![](https://preview.redd.it/jrc1plsv9pi21.png?width=640&crop=smart&auto=webp&s=9187d9e5c25aed1015ac1fecb4360fbdb2aeb17a)
![](https://preview.redd.it/32eetcrujjk21.jpg?width=640&crop=smart&auto=webp&s=c434bca38ff0c57b94c6d74db038c2a93786d53e)
![](https://preview.redd.it/tsmmgdxmkui21.jpg?width=640&crop=smart&auto=webp&s=03a0dbb7bc63bcdff8e4ac72e8b2a447dbf5e8b7)
![](https://preview.redd.it/6fttplx5kbk21.jpg?width=640&crop=smart&auto=webp&s=cc382a419b2ea4fd0ad6e55c277473266f0e70ac)
![](https://preview.redd.it/wq4fs51bfwh21.jpg?width=640&crop=smart&auto=webp&s=f96dff4d91a09c9d2fadb4a3b1ce5ec5e2f2ebd7)
![](https://preview.redd.it/d2zwx0bk29l21.jpg?width=640&crop=smart&auto=webp&s=3ba20371ca8509c157c125293ff35c07a2ced91f)
![](https://preview.redd.it/0glcvbrpc3i21.jpg?width=640&crop=smart&auto=webp&s=1a1239a5b7d2a8dcb5f3e537a58f98c0337c24c1)
![](https://preview.redd.it/15ethpe8xkh21.png?width=640&crop=smart&auto=webp&s=c0c53cb177fd76d208acbbc85b3e5f55a7c26cac)
![](https://preview.redd.it/shhzaf859jl21.jpg?width=640&crop=smart&auto=webp&s=7260f58d73fe26bff7c591b250ef72566f54d5ee)
![](https://preview.redd.it/6h95i19jpsh21.jpg?width=640&crop=smart&auto=webp&s=11d70399d41995f1e02ae00a43be0ba6e493894a)

З вами був Роман Севастьянов.\
Підписуйтесь на мій [Телеграм канал про PHP](https://t.me/elephant_php) - я там публікую новини зі світу PHP, security баги в live режимі.
