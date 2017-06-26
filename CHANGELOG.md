# [v0.1.0](https://github.com/koudaiii/sltd/releases/tag/v0.1.0)

Update labels Datadog format.

- service_name

```
{
  key: "kube_service",
  value: kubenetes.io/service-name,
}
```

- kubernetescluster

```
{
  key: "kubernetescluster",
  value: cluster name,
}
```

- labels

```
{
  key: "kube_" + key,
  value: value,
}
```

# [v0.0.1](https://github.com/koudaiii/sltd/releases/tag/v0.0.1)

Initial release.
