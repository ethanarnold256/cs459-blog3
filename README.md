# How to set up a Droplet
## Table of Contents
1. [Making an Account](#making-an-account)
2. [Setting up a Droplet](#setting-up-a-droplet)
1. [Creation](#creation)
2. [Region](#region)
3. [Operating Systems](#operating-systems)
4. [Pricing](#pricing)
5. [Authentication Method](#authentication-method)
## Making an Account
In order to create a Droplet, you will need to make an account at DigitalOcean. This can be done by going to the following site:

www.digitalocean.com

Once you have created an account you may continue.

## Setting up a Droplet
### Creation
Second, you must create a droplet. This will be done by pressing the green *Create* button at the top of the page. Select *Droplets* from the dropdown and you will be prompted with alot of options.

### Region
You will be prompted with several regions. Please select the closest one to your target audience/language. If you are targeting a global audience, select the region that is closest to most or closest to you.

### Operating Systems
Ubuntu LTS is recommended for several reasons. Ubuntu is based on *Debian* which is one of the most stable operating systems out there. Ubuntu also has a nice package management system called *Snap* which has sandboxing features. It is specifically recommended to use the LTS *(Long Term Support)* edition because of its longevity of support (~5 years post-launch).

### Pricing
As for pricing, picking the cheapest one that has your minimum specifications for RAM and storage is best.

### Authentication Method
You have two options for authentication:
1. SSH key
2. SSH password
The `SSH key` option is more secure in that only the computer that has the key can access the droplet. This however is inconvenient, as the `SSH password` option can be accessed by any computer *so long as they have the password.*

## Outro
And there you have it! That was your guide on how to create a Droplet at www.digitalocean.com.