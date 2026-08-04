Container infrastructure at Google. containerd reviewer and security advisor.

- Triaging containerd's inbound vulnerability reports and fixing the real ones.
- Led GKE's migration to containerd 2.0. Published a
  [socket tracer](https://github.com/GoogleCloudPlatform/k8s-node-tools/tree/master/containerd/socket-tracer)
  for finding workloads still on the removed CRI API.
- Driving the containerd
  [Node Resource Interface](https://github.com/containerd/nri) to 1.0, the
  plugin API that node-level resource controls are built on.
- Co-authored
  [KEP-5474](https://github.com/kubernetes/enhancements/tree/master/keps/sig-node/5474-enable-writable-cgroups)
  (writable cgroups). Authored
  [KEP-2485](https://github.com/kubernetes/enhancements/issues/2485), the
  ReadWriteOncePod access mode,
  [stable in 1.29](https://kubernetes.io/blog/2023/12/18/read-write-once-pod-access-mode-ga/).

[chrishenzie.com](https://chrishenzie.com)
