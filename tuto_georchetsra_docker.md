# Tutoriel : Deploy geOrchestra with docker on production

We are going to explain how to adapt the docker composition offered by geOrhcestra community, to run it on production.
This is probably still not really a production-ready deployement, but will work on a remote server, with custom domain name and SSl certificate.

## Step 1 - Clone the official repository

```bash
git clone --recurse-submodules https://github.com/georchestra/docker.git
cd docker
git checkout 23.0 && git submodule update
 ```

## Step 2 - Test
gyt
