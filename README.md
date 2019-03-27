# Provisioning and Deploying Cloud Native Systems in AWS with Terraform and Shell Scripts.

A 1-day hands-on training class in which participants will learn:

* AWS guest network architecture: regions, availability zones, VPCs, subnets, security groups, routes, gateways.
* How to configure a simple, highly available AWS application environment with AWS autoscaling groups, load balancers, and CloudWatch.
* Infrastructure-as-Code with AWS and Terraform: How to configure and manage AWS infrastructure using Terraform.

### Running the slides locally

The workshop is run as a series of slide decks. The decks are written in HTML, and use [reveal.js](http://lab.hakim.se/reveal-js/#/). To view the slides on your local machine, first go to the [slides](slides) directory. Then install `npm` if you don't already have it, and run the following commands:

```
npm install
grunt serve
```

This should run an http server locally and spawn a browser window with the first slide of the workshop. Check out the [reveal.js documentation](https://github.com/hakimel/reveal.js) for more on using reveal.js.

### Acknowledgements

This an adapted version of the [original workshop run at 18F](https://github.com/18F/cloud-native-aws-terraform-workshop).

Charity Majors' [blog posts on Terraform](https://charity.wtf/tag/terraform/) proved valuable in preparing this workshop. Thanks Charity.

### Public domain

This project is in the worldwide [public domain](LICENSE.md). As stated
in [CONTRIBUTING](CONTRIBUTING.md):

> This project is in the public domain within the United States, and copyright
> and related rights in the work worldwide are waived through the [CC0 1.0
> Universal public domain
> dedication](https://creativecommons.org/publicdomain/zero/1.0/).
>
> All contributions to this project will be released under the CC0 dedication.
> By submitting a pull request, you are agreeing to comply with this waiver of
> copyright interest.

Note that parts of this project have been taken from the [reveal.js][]
repository, and are Copyright (C) 2016 Hakim El Hattab.

[reveal.js]: https://github.com/hakimel/reveal.js
[18F branding]: https://pages-staging.18f.gov/brand/
[visual style guide]: https://pages-staging.18f.gov/brand/visual-style/
