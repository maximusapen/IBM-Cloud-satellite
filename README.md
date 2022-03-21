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
            Bash::class,
            Kubernetes::class,
            Docker::class,
            Terraform::class,
            BigQuery::class,
            RedHatOpenshiftK8sService::class,
            GCP::class,
        ];
    }

    certifications function accomplishments(): string
    {
        return 'Google Cloud Certified Engineer, Certified Kubernetes Admin Developer';
    }
}
