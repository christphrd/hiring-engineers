#Christopher Diep
Solutions Engineer Exercise for digesting technical concepts and presenting them

## Prequisites - Setup the environment

Following these instructions: https://www.vagrantup.com/intro/getting-started/
1. I downloaded Vagrant and installed it.
2. I downloaded VirtualBox and installed it.
3. I ran commands `vagrant init hashicorp/precise64` and `vagrant up`
4. After running `vagrant ssh`, I saw an option to upgrade Ubuntu and ran `do-release-upgrade`

![Ubuntu upgrade](img/0-ubuntu-upgrade.png)

While upgrading, I signed up for Datadog.

![Datadog Signup](img/0-datadog-signup.png)

I then followed step-by-step instructions to start the Agent with Ubuntu 14.04.

I went to the Datadog website to see my metrics.

![Datadog Metrics](img/0-datadog-metrics.png)
