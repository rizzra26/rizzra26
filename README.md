```php
<?php

namespace RizkiRamadhan;

class About extends Me
{
    public function getProfile(): array
    {
        return [
            'rizzra26' => [
                'pronouns' => 'he' | 'him',
                'position' => 'Founder'         
            ]
        ];
    }

    public function getTechStacks): array
    {
        return [
            Javascript::class,
            Typescript::class,
            Vuejs::class,
            Reactjs::class,
            ReactNative::class,
            Nextjs::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```
