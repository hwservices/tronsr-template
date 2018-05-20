We have just completed (as of late May) the initial testing and node setup on AWS in Ohio, US:

`18.188.227.130` with ports `18888` and `50051` open

Our plan is to also set up and evaluate a cloud server on Google App Engine and compare cost and performance vs EC2.

For production/mainnet configuration, once approved, we would initially roll out a test server in one of AWS or
Google locations in

`US East (N. Virginia, Washington, Ohio)`

and/or

`US West (Oregon, California)`

The configuration for deployment is to match the performance of the recommended

`x1.16xlarge 64 core 1T RAM 20T EBS`

*There is a 10G bandwidth cap to [our knowledge] (https://aws.amazon.com/ec2/instance-types/) for x1.16xlarge instance*

We plan to evaluate the cost/performance of a load-balancer/dual-node setup on EC2 with r4 types to support
25G bandwidth:

`r4.16xlarge 64 core 500GB RAM 10T EBS 25G bandwidth`

After the initial cloud server deployment, we would like to add more capacity and replicate the setup locally
in:

* Buenos Aires (Argentina)
* Sofia (Bulgaria)
* St. Petersburg (Russia).

The alternative cloud locations could be:

* Ireland
* UK
* Germany







