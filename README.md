# Helm Charts

You know, for Kubernetes.

## Install Helm

Get the latest [Helm release](https://github.com/kubernetes/helm).

## Add Repo

The following command allows you to download and install all the charts from this repository:

```console
$ helm repo add ioniscorporate https://charts.ioniscorporate.engineering
$ helm repo update
```

## Install a chart

Once you have installed the Helm client, you can deploy a IONIS CORPORATE Helm Chart into a Kubernetes cluster.

**View available charts:**

```console
$ helm search repo
```

**Install a chart:**

```console
$ helm install my-release ioniscorporate/<PACKAGE_NAME>
```

**Upgrade your application:**

```console
$ helm upgrade
```