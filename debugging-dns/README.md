# Debugging DNS Resolution

refs: https://kubernetes.io/docs/tasks/administer-cluster/dns-debugging-resolution/

- DNS Resolution(A record)

```
kubectl exec -ti dnsutils -- dig google.co.jp a
```

- Check the local DNS configuration first

```
kubectl exec -ti dnsutils -- cat /etc/resolv.conf
```

- etc...
