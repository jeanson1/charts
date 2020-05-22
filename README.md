# Helm Charts

You know, for Kubernetes.

## Install Helm

Get the latest [Helm release](https://github.com/kubernetes/helm).

## Add Repo

The following command allows you to download and install all the charts from this repository:

```console
helm repo add ioniscorporate https://charts.ioniscorporate.engineering
helm repo update
```

## Install a chart

Once you have installed the Helm client, you can deploy a IONIS CORPORATE Helm Chart into a Kubernetes cluster.

**View available charts:**

```console
helm search repo
```

**Install a chart:**

```console
helm install my-release ioniscorporate/<PACKAGE_NAME>
```

**Upgrade your application:**

```console
helm upgrade
```

# License

Copyright 2020 IONIS CORPORATE

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

```
http://www.apache.org/licenses/LICENSE-2.0
```

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.