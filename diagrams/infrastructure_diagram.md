graph TD;
    A[VPC]
    B[Subnets]
    C[EC2 Instances]
    D[RDS]
    E[S3]
    F[CloudFront]
    G[ALB]
    H[Security Groups]
    I[IAM Roles]
    J[Lambda Functions]
    K[Kinesis]
    L[CloudWatch]

    A --> B
    B --> C
    B --> D
    B --> E
    B --> J
    C --> G
    G --> F
    C -.-> H
    H -.-> I
    D --> L
    E --> L
    K --> J
    J --> L
