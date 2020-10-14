# Quickstart the workshop

Instead of initializing your own repositroy you can just fork this one to you
own github account.

# Quickstart on day 1

Once connected to the build agent please run the following three lines to
generate a new ssh-key:

```shell
rm ~/.ssh/id_rsa
rm ~/.ssh/id_rsa.pub
ssh-keygen
```

Please keep the default location for the new key and leave the password blank.
(Just hit `<return>` a few times.)

# Resume on day 2

To resume on day 2 you will need to take following steps:

1. Update the secrets in your github repository
2. Update all 3 build pipeline yaml files with the new container registry access
   credentials.
3. Run the build pipelines again.

> If you've already started with day 2 you might also need to download the access
> credentials for the kubernetes cluster and deploy your services again.
