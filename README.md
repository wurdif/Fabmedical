# Quickstart the workshop

Instead of initializing your own repositroy you can just fork this one to you
own github account.

## Quickstart on day 1

Once connected to the build agent please run the following three lines to
generate a new ssh-key:

```shell
rm ~/.ssh/id_rsa
rm ~/.ssh/id_rsa.pub
ssh-keygen
```

Please keep the default location for the new key and leave the password blank.
(Just hit `<return>` a few times.)

Then copy the public part of your key to github for you to be able to authenticate using the access credentials.

## Resume on day 2

To resume on day 2 you will need to take following steps:

1. Update the secrets for the container registry in your github repository.
2. Update all 3 build pipelines yaml files with the correct values for the new
   container registry.
3. Run the build pipelines again.

> If you've already started with day 2 you might also need to download the access
> credentials for the kubernetes cluster and deploy your services again.
