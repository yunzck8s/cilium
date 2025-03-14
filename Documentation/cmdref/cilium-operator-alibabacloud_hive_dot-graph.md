<!-- This file was autogenerated via cilium-operator --cmdref, do not edit manually-->

## cilium-operator-alibabacloud hive dot-graph

Output the dependencies graph in graphviz dot format

```
cilium-operator-alibabacloud hive dot-graph [flags]
```

### Options

```
  -h, --help   help for dot-graph
```

### Options inherited from parent commands

```
      --cluster-id uint32                                    Unique identifier of the cluster
      --cluster-name string                                  Name of the cluster (default "default")
      --controller-group-metrics strings                     List of controller group names for which to to enable metrics. Accepts 'all' and 'none'. The set of controller group names available is not guaranteed to be stable between Cilium versions.
      --enable-cilium-operator-server-access strings         List of cilium operator APIs which are administratively enabled. Supports '*'. (default [*])
      --enable-k8s                                           Enable the k8s clientset (default true)
      --enable-k8s-api-discovery                             Enable discovery of Kubernetes API groups and resources with the discovery API
      --gops-port uint16                                     Port for gops server to listen on (default 9891)
      --identity-gc-interval duration                        GC interval for security identities (default 15m0s)
      --identity-gc-rate-interval duration                   Interval used for rate limiting the GC of security identities (default 1m0s)
      --identity-gc-rate-limit int                           Maximum number of security identities that will be deleted within the identity-gc-rate-interval (default 2500)
      --identity-heartbeat-timeout duration                  Timeout after which identity expires on lack of heartbeat (default 30m0s)
      --k8s-api-server string                                Kubernetes API server URL
      --k8s-client-burst int                                 Burst value allowed for the K8s client
      --k8s-client-qps float32                               Queries per second limit for the K8s client
      --k8s-heartbeat-timeout duration                       Configures the timeout for api-server heartbeat, set to 0 to disable (default 30s)
      --k8s-kubeconfig-path string                           Absolute path of the kubernetes kubeconfig file
      --mesh-auth-mutual-enabled                             The flag to enable mutual authentication for the SPIRE server (beta).
      --mesh-auth-spiffe-trust-domain string                 The trust domain for the SPIFFE identity. (default "spiffe.cilium")
      --mesh-auth-spire-agent-socket string                  The path for the SPIRE admin agent Unix socket. (default "/run/spire/sockets/agent/agent.sock")
      --mesh-auth-spire-server-address string                SPIRE server endpoint. (default "spire-server.spire.svc:8081")
      --mesh-auth-spire-server-connection-timeout duration   SPIRE server connection timeout. (default 10s)
      --operator-api-serve-addr string                       Address to serve API requests (default "localhost:9234")
      --operator-pprof                                       Enable serving pprof debugging API
      --operator-pprof-address string                        Address that pprof listens on (default "localhost")
      --operator-pprof-port uint16                           Port that pprof listens on (default 6061)
      --skip-crd-creation                                    When true, Kubernetes Custom Resource Definitions will not be created
```

### SEE ALSO

* [cilium-operator-alibabacloud hive](cilium-operator-alibabacloud_hive.md)	 - Inspect the hive

