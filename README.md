```php
<?php

namespace HenriqueSiqueiraCheim;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Americanas Delivery',
                'position' => 'Developer FullStack'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Vuejs::class,
            Angular::class,
            Lumen::class,
            MySql::class,
            Html::class,
            Css::class,
            Docker::class
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```
