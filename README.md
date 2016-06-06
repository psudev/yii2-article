# yii2-article
#### ระบบจัดการบทความ

> ### ความสามารถของระบบดังนี้
> 1. สามารถใช้งาน Text Editor ได้
> 2. สามารถใช้ความสามารถของ Tag ได้
> 3. สามารถใช้ความสามารถของ Slug ได้
> 4. สามารถแบ่งตามภาษา Language ได้


## Install
```php
composer require thaisouthdev/article "dev-master"
```

## Use
```php
return [
    'modules' => [
        'admin' => [
            'class' => 'mdm\admin\Module',
            ...
        ]
        ...
    ],
```

To use the menu manager (optional), execute the migration here:
```
yii migrate --migrationPath=@thaisouthdev/article/migrations
```

