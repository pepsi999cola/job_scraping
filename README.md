環境
Laravel8

composer require weidner/goutte

追記するコード
```config/app.php
'providers' => [
    Weidner\Goutte\GoutteServiceProvider::class,
]

'aliases' => [
    'Goutte' => Weidner\Goutte\GoutteFacade::class, 
]```
