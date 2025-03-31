# Projector HSA Home work #26: AWS: Autoscale groups

## Todo:

1. Create autoscale group that will contain one on-demand instance and will scale on spot instances.
2. Set up scaling policy based on AVG CPU usage.
3. Set up scaling policy based on requests amount that allows non-linear growth.

## How to run?

1. Clone the repository
2. Switch to your AWS account in `provider.tf`
3. Run `terraform init`
4. Run `terraform plan`
5. Run `terraform apply`

## How to destroy?

1. Run `terraform destroy`
