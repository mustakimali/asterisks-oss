# ✳ Asterisks
🔐 Working on End to end encrypted and minimal social media

Every commit is built and pushed [in docker hub](https://hub.docker.com/r/mustakimali/asterisks/) andis also deployed to [Azure app service](https://asterisks.mustak.im).

## Live demo
https://asterisks.mustak.im

Alpha version, you will see lots of diagnostic information on the top-left corner.

## Run in kubernetes

```bash
kubectl create -f https://raw.githubusercontent.com/mustakimali/asterisks/master/kubernetes/spec.yml
```

Wait few moments as it will initialize postgres database and get the app running, to access the app go to

`http://localhost:30080`

You need to create a new account as the database will be empty
