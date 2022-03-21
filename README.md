```php
<?php

namespace Maximus;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'IBM',
                'position' => 'Software_Engineer'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Docker::class,
            OpenshiftK8s::class,
            IBMKubernetes::class,
            Terraform::class,
            Bash::class,
            GoogleCloudPlatform::class,
        ];
    }

    public function getInterests(): string
    {
        return 'Part of the K8s community, public speaker, lend expertise on GCP';
    }
}
```
