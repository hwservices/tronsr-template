For production/mainnet configuration, we would like to initially roll out a cloud server on AWS and Google Cloud Platform in US East and/or US West.

The configuration for deployment is to match the performance of the recommended 

`x1.16xlarge 64 core 1T RAM 20T EBS`

*There is a 10G bandwidth cap to [our knowledge] (https://aws.amazon.com/ec2/instance-types/) for x1.16xlarge instance*

We plan to evaluate the cost/performance of a load-balancer/dual-node setup on EC2 with r4 types to support 25G bandwidth: 

`r4.16xlarge 64 core 500GB RAM 10T EBS 25G bandwidth`

After the initial cloud server deployment, we would like to add more capacity and replicate the setup locally in:

* Buenos Aires (Argentina)
* Sofia (Bulgaria)
* St. Petersburg (Russia)




