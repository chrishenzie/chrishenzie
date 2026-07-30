I work on container infrastructure at Google, mostly upstream in
[containerd](https://containerd.io) and [Kubernetes](https://kubernetes.io).

- containerd reviewer and security advisor. Most of my week is triaging incoming
  vulnerability reports and landing the fixes that hold up.
- Led GKE's migration to containerd 2.0. Every cluster reaching Kubernetes 1.33
  passes through the detection path, and the ones it flags have upgrades paused
  until they migrate off. For customers who could not tell which workload still
  called the removed API, I published a
  [socket tracer](https://github.com/GoogleCloudPlatform/k8s-node-tools/tree/master/containerd/socket-tracer)
  that resolves the calls back to the container.
- Driving the containerd
  [Node Resource Interface](https://github.com/containerd/nri) to 1.0, the
  plugin API that node-level resource controls are built on.
- Co-authored
  [KEP-5474](https://github.com/kubernetes/enhancements/tree/master/keps/sig-node/5474-enable-writable-cgroups),
  writable cgroups. Earlier, in SIG-Storage, authored
  [KEP-2485](https://github.com/kubernetes/enhancements/issues/2485), the
  ReadWriteOncePod access mode,
  [stable in 1.29](https://kubernetes.io/blog/2023/12/18/read-write-once-pod-access-mode-ga/).

More at [chrishenzie.com](https://chrishenzie.com).
