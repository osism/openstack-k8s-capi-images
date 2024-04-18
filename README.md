# kubernetes-capi-images

Images intended for use with Kubernetes CAPI providers. More details on
https://image-builder.sigs.k8s.io/capi/capi.html.

The images are built with the [Image Builder](https://github.com/kubernetes-sigs/image-builder/),
a collection of cross-provider Kubernetes virtual machine image building utilities.

The following images contain the latest [stable releases](https://kubernetes.io/releases/),
which are updated as required. This means that the image for version `1.27` contains, for example,
version `1.27.3`.

| Version | Image URL                                                                                                                                                                                              | End of life                                     |
|---------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------|
| v1.30   | [ubuntu-2204-kube-v1.30.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.30/ubuntu-2204-kube-v1.30.qcow2)  | [2025-04-28](https://endoflife.date/kubernetes) |
| v1.29   | [ubuntu-2204-kube-v1.29.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.29/ubuntu-2204-kube-v1.29.qcow2)  | [2025-02-28](https://endoflife.date/kubernetes) |
| v1.28   | [ubuntu-2204-kube-v1.28.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.28/ubuntu-2204-kube-v1.28.qcow2)  | [2024-10-28](https://endoflife.date/kubernetes) |
| v1.27   | [ubuntu-2204-kube-v1.27.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.27/ubuntu-2204-kube-v1.27.qcow2)  | [2024-06-28](https://endoflife.date/kubernetes) |

## Ubuntu 22.04

| Series | Version  | Image URL                                                                                                                                                                                                     | CHECKSUM URL                                                                                                                                                                                                                  |
|--------|----------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| v1.30  |          |                                                                                                                                                                                                               |                                                                                                                                                                                                                               |
|        | v1.30.0  | [ubuntu-2204-kube-v1.30.0.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.30/ubuntu-2204-kube-v1.30.0.qcow2)     | [ubuntu-2204-kube-v1.30.0.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.30/ubuntu-2204-kube-v1.30.0.qcow2.CHECKSUM)   |
| v1.29  |          |                                                                                                                                                                                                               |                                                                                                                                                                                                                               |
|        | v1.29.4  | [ubuntu-2204-kube-v1.29.4.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.29/ubuntu-2204-kube-v1.29.4.qcow2)     | [ubuntu-2204-kube-v1.29.4.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.29/ubuntu-2204-kube-v1.29.4.qcow2.CHECKSUM)   |
|        | v1.29.3  | [ubuntu-2204-kube-v1.29.3.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.29/ubuntu-2204-kube-v1.29.3.qcow2)     | [ubuntu-2204-kube-v1.29.3.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.29/ubuntu-2204-kube-v1.29.3.qcow2.CHECKSUM)   |
|        | v1.29.2  | [ubuntu-2204-kube-v1.29.2.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.29/ubuntu-2204-kube-v1.29.2.qcow2)     | [ubuntu-2204-kube-v1.29.2.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.29/ubuntu-2204-kube-v1.29.2.qcow2.CHECKSUM)   |
|        | v1.29.1  | [ubuntu-2204-kube-v1.29.1.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.29/ubuntu-2204-kube-v1.29.1.qcow2)     | [ubuntu-2204-kube-v1.29.1.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.29/ubuntu-2204-kube-v1.29.1.qcow2.CHECKSUM)   |
|        | v1.29.0  | [ubuntu-2204-kube-v1.29.0.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.29/ubuntu-2204-kube-v1.29.0.qcow2)     | [ubuntu-2204-kube-v1.29.0.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.29/ubuntu-2204-kube-v1.29.0.qcow2.CHECKSUM)   |
| v1.28  |          |                                                                                                                                                                                                               |                                                                                                                                                                                                                               |
|        | v1.28.9  | [ubuntu-2204-kube-v1.28.9.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.28/ubuntu-2204-kube-v1.28.9.qcow2)     | [ubuntu-2204-kube-v1.28.9.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.28/ubuntu-2204-kube-v1.28.9.qcow2.CHECKSUM)   |
|        | v1.28.8  | [ubuntu-2204-kube-v1.28.8.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.28/ubuntu-2204-kube-v1.28.8.qcow2)     | [ubuntu-2204-kube-v1.28.8.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.28/ubuntu-2204-kube-v1.28.8.qcow2.CHECKSUM)   |
|        | v1.28.7  | [ubuntu-2204-kube-v1.28.7.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.28/ubuntu-2204-kube-v1.28.7.qcow2)     | [ubuntu-2204-kube-v1.28.7.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.28/ubuntu-2204-kube-v1.28.7.qcow2.CHECKSUM)   |
|        | v1.28.6  | [ubuntu-2204-kube-v1.28.6.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.28/ubuntu-2204-kube-v1.28.6.qcow2)     | [ubuntu-2204-kube-v1.28.6.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.28/ubuntu-2204-kube-v1.28.6.qcow2.CHECKSUM)   |
|        | v1.28.5  | [ubuntu-2204-kube-v1.28.5.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.28/ubuntu-2204-kube-v1.28.5.qcow2)     | [ubuntu-2204-kube-v1.28.5.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.28/ubuntu-2204-kube-v1.28.5.qcow2.CHECKSUM)   |
|        | v1.28.4  | [ubuntu-2204-kube-v1.28.4.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.28/ubuntu-2204-kube-v1.28.4.qcow2)     | [ubuntu-2204-kube-v1.28.4.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.28/ubuntu-2204-kube-v1.28.4.qcow2.CHECKSUM)   |
|        | v1.28.3  | [ubuntu-2204-kube-v1.28.3.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.28/ubuntu-2204-kube-v1.28.3.qcow2)     | [ubuntu-2204-kube-v1.28.3.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.28/ubuntu-2204-kube-v1.28.3.qcow2.CHECKSUM)   |
|        | v1.28.2  | [ubuntu-2204-kube-v1.28.2.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.28/ubuntu-2204-kube-v1.28.2.qcow2)     | [ubuntu-2204-kube-v1.28.2.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.28/ubuntu-2204-kube-v1.28.2.qcow2.CHECKSUM)   |
|        | v1.28.1  | [ubuntu-2204-kube-v1.28.1.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.28/ubuntu-2204-kube-v1.28.1.qcow2)     | [ubuntu-2204-kube-v1.28.1.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.28/ubuntu-2204-kube-v1.28.1.qcow2.CHECKSUM)   |
|        | v1.28.0  | [ubuntu-2204-kube-v1.28.0.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.28/ubuntu-2204-kube-v1.28.0.qcow2)     | [ubuntu-2204-kube-v1.28.0.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.28/ubuntu-2204-kube-v1.28.0.qcow2.CHECKSUM)   |
| v1.27  |          |                                                                                                                                                                                                               |                                                                                                                                                                                                                               |
|        | v1.27.13 | [ubuntu-2204-kube-v1.27.13.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.27/ubuntu-2204-kube-v1.27.13.qcow2)     | [ubuntu-2204-kube-v1.27.13.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.27/ubuntu-2204-kube-v1.27.13.qcow2.CHECKSUM)   |
|        | v1.27.12 | [ubuntu-2204-kube-v1.27.12.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.27/ubuntu-2204-kube-v1.27.12.qcow2)     | [ubuntu-2204-kube-v1.27.12.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.27/ubuntu-2204-kube-v1.27.12.qcow2.CHECKSUM)   |
|        | v1.27.11 | [ubuntu-2204-kube-v1.27.11.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.27/ubuntu-2204-kube-v1.27.11.qcow2)     | [ubuntu-2204-kube-v1.27.11.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.27/ubuntu-2204-kube-v1.27.11.qcow2.CHECKSUM)   |
|        | v1.27.10 | [ubuntu-2204-kube-v1.27.10.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.27/ubuntu-2204-kube-v1.27.10.qcow2)     | [ubuntu-2204-kube-v1.27.10.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.27/ubuntu-2204-kube-v1.27.10.qcow2.CHECKSUM)   |
|        | v1.27.9  | [ubuntu-2204-kube-v1.27.9.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.27/ubuntu-2204-kube-v1.27.9.qcow2)     | [ubuntu-2204-kube-v1.27.9.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.27/ubuntu-2204-kube-v1.27.9.qcow2.CHECKSUM)   |
|        | v1.27.8  | [ubuntu-2204-kube-v1.27.8.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.27/ubuntu-2204-kube-v1.27.8.qcow2)     | [ubuntu-2204-kube-v1.27.8.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.27/ubuntu-2204-kube-v1.27.8.qcow2.CHECKSUM)   |
|        | v1.27.7  | [ubuntu-2204-kube-v1.27.7.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.27/ubuntu-2204-kube-v1.27.7.qcow2)     | [ubuntu-2204-kube-v1.27.7.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.27/ubuntu-2204-kube-v1.27.7.qcow2.CHECKSUM)   |
|        | v1.27.6  | [ubuntu-2204-kube-v1.27.6.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.27/ubuntu-2204-kube-v1.27.6.qcow2)     | [ubuntu-2204-kube-v1.27.6.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.27/ubuntu-2204-kube-v1.27.6.qcow2.CHECKSUM)   |
|        | v1.27.5  | [ubuntu-2204-kube-v1.27.5.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.27/ubuntu-2204-kube-v1.27.5.qcow2)     | [ubuntu-2204-kube-v1.27.5.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.27/ubuntu-2204-kube-v1.27.5.qcow2.CHECKSUM)   |
|        | v1.27.4  | [ubuntu-2204-kube-v1.27.4.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.27/ubuntu-2204-kube-v1.27.4.qcow2)     | [ubuntu-2204-kube-v1.27.4.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.27/ubuntu-2204-kube-v1.27.4.qcow2.CHECKSUM)   |
|        | v1.27.3  | [ubuntu-2204-kube-v1.27.3.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.27/ubuntu-2204-kube-v1.27.3.qcow2)     | [ubuntu-2204-kube-v1.27.3.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.27/ubuntu-2204-kube-v1.27.3.qcow2.CHECKSUM)   |
|        | v1.27.2  | [ubuntu-2204-kube-v1.27.2.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.27/ubuntu-2204-kube-v1.27.2.qcow2)     | [ubuntu-2204-kube-v1.27.2.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.27/ubuntu-2204-kube-v1.27.2.qcow2.CHECKSUM)   |
|        | v1.27.1  | [ubuntu-2204-kube-v1.27.1.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.27/ubuntu-2204-kube-v1.27.1.qcow2)     | [ubuntu-2204-kube-v1.27.1.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.27/ubuntu-2204-kube-v1.27.1.qcow2.CHECKSUM)   |

## Ubuntu 22.04 (Archived)

| Series | Version  | Image URL                                                                                                                                               | CHECKSUM URL                                                                                                                                                            |
|--------|----------|---------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| v1.26  |          |                                                                                                                                                                                                               |                                                                                                                                                                                                                               |
|        | v1.26.14 | [ubuntu-2204-kube-v1.26.14.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.26/ubuntu-2204-kube-v1.26.14.qcow2)   | [ubuntu-2204-kube-v1.26.14.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.26/ubuntu-2204-kube-v1.26.14.qcow2.CHECKSUM) |
|        | v1.26.13 | [ubuntu-2204-kube-v1.26.13.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.26/ubuntu-2204-kube-v1.26.13.qcow2)   | [ubuntu-2204-kube-v1.26.13.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.26/ubuntu-2204-kube-v1.26.13.qcow2.CHECKSUM) |
|        | v1.26.12 | [ubuntu-2204-kube-v1.26.12.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.26/ubuntu-2204-kube-v1.26.12.qcow2)   | [ubuntu-2204-kube-v1.26.12.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.26/ubuntu-2204-kube-v1.26.12.qcow2.CHECKSUM) |
|        | v1.26.11 | [ubuntu-2204-kube-v1.26.11.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.26/ubuntu-2204-kube-v1.26.11.qcow2)   | [ubuntu-2204-kube-v1.26.11.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.26/ubuntu-2204-kube-v1.26.11.qcow2.CHECKSUM) |
|        | v1.26.10 | [ubuntu-2204-kube-v1.26.10.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.26/ubuntu-2204-kube-v1.26.10.qcow2)   | [ubuntu-2204-kube-v1.26.10.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.26/ubuntu-2204-kube-v1.26.10.qcow2.CHECKSUM) |
|        | v1.26.9  | [ubuntu-2204-kube-v1.26.9.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.26/ubuntu-2204-kube-v1.26.9.qcow2)     | [ubuntu-2204-kube-v1.26.9.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.26/ubuntu-2204-kube-v1.26.9.qcow2.CHECKSUM)   |
|        | v1.26.8  | [ubuntu-2204-kube-v1.26.8.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.26/ubuntu-2204-kube-v1.26.8.qcow2)     | [ubuntu-2204-kube-v1.26.8.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.26/ubuntu-2204-kube-v1.26.8.qcow2.CHECKSUM)   |
|        | v1.26.7  | [ubuntu-2204-kube-v1.26.7.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.26/ubuntu-2204-kube-v1.26.7.qcow2)     | [ubuntu-2204-kube-v1.26.7.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.26/ubuntu-2204-kube-v1.26.7.qcow2.CHECKSUM)   |
|        | v1.26.6  | [ubuntu-2204-kube-v1.26.6.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.26/ubuntu-2204-kube-v1.26.6.qcow2)     | [ubuntu-2204-kube-v1.26.6.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.26/ubuntu-2204-kube-v1.26.6.qcow2.CHECKSUM)   |
|        | v1.26.5  | [ubuntu-2204-kube-v1.26.5.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.26/ubuntu-2204-kube-v1.26.5.qcow2)     | [ubuntu-2204-kube-v1.26.5.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.26/ubuntu-2204-kube-v1.26.5.qcow2.CHECKSUM)   |
|        | v1.26.4  | [ubuntu-2204-kube-v1.26.4.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.26/ubuntu-2204-kube-v1.26.4.qcow2)     | [ubuntu-2204-kube-v1.26.4.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.26/ubuntu-2204-kube-v1.26.4.qcow2.CHECKSUM)   |
| v1.25  |          |                                                                                                                                                                                                               |                                                                                                                                                                                                                               |
|        | v1.25.15 | [ubuntu-2204-kube-v1.25.15.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.25/ubuntu-2204-kube-v1.25.15.qcow2)   | [ubuntu-2204-kube-v1.25.13.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.25/ubuntu-2204-kube-v1.25.15.qcow2.CHECKSUM) |
|        | v1.25.14 | [ubuntu-2204-kube-v1.25.14.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.25/ubuntu-2204-kube-v1.25.14.qcow2)   | [ubuntu-2204-kube-v1.25.13.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.25/ubuntu-2204-kube-v1.25.14.qcow2.CHECKSUM) |
|        | v1.25.13 | [ubuntu-2204-kube-v1.25.13.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.25/ubuntu-2204-kube-v1.25.13.qcow2)   | [ubuntu-2204-kube-v1.25.13.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.25/ubuntu-2204-kube-v1.25.13.qcow2.CHECKSUM) |
|        | v1.25.12 | [ubuntu-2204-kube-v1.25.12.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.25/ubuntu-2204-kube-v1.25.12.qcow2)   | [ubuntu-2204-kube-v1.25.12.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.25/ubuntu-2204-kube-v1.25.12.qcow2.CHECKSUM) |
|        | v1.25.11 | [ubuntu-2204-kube-v1.25.11.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.25/ubuntu-2204-kube-v1.25.11.qcow2)   | [ubuntu-2204-kube-v1.25.11.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.25/ubuntu-2204-kube-v1.25.11.qcow2.CHECKSUM) |
|        | v1.25.10 | [ubuntu-2204-kube-v1.25.10.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.25/ubuntu-2204-kube-v1.25.10.qcow2)   | [ubuntu-2204-kube-v1.25.10.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.25/ubuntu-2204-kube-v1.25.10.qcow2.CHECKSUM) |
|        | v1.25.9  | [ubuntu-2204-kube-v1.25.9.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.25/ubuntu-2204-kube-v1.25.9.qcow2)     | [ubuntu-2204-kube-v1.25.9.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.25/ubuntu-2204-kube-v1.25.9.qcow2.CHECKSUM)   |
| v1.24  |          |                                                                                                                                                                                                               |                                                                                                                                                                                                                               |
|        | v1.24.15 | [ubuntu-2204-kube-v1.24.15.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.24/ubuntu-2204-kube-v1.24.15.qcow2)   | [ubuntu-2204-kube-v1.24.15.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.24/ubuntu-2204-kube-v1.24.15.qcow2.CHECKSUM) |
|        | v1.24.14 | [ubuntu-2204-kube-v1.24.14.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.24/ubuntu-2204-kube-v1.24.14.qcow2)   | [ubuntu-2204-kube-v1.24.14.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.24/ubuntu-2204-kube-v1.24.14.qcow2.CHECKSUM) |
|        | v1.24.13 | [ubuntu-2204-kube-v1.24.13.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.24/ubuntu-2204-kube-v1.24.13.qcow2)   | [ubuntu-2204-kube-v1.24.13.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2204-kube-v1.24/ubuntu-2204-kube-v1.24.13.qcow2.CHECKSUM) |


## Ubuntu 20.04

| Series | Version  | Image URL                                                                                                                                               | CHECKSUM URL                                                                                                                                                             |
|--------|----------|---------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| v1.26  | v1.26.6  | [ubuntu-2004-kube-v1.26.6.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2004-kube-v1.26/ubuntu-2004-kube-v1.26.6.qcow2)     | [ubuntu-2004-kube-v1.26.6.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2004-kube-v1.26/ubuntu-2004-kube-v1.26.6.qcow2.CHECKSUM)    |
|        | v1.26.5  | [ubuntu-2004-kube-v1.26.5.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2004-kube-v1.26/ubuntu-2004-kube-v1.26.5.qcow2)     | [ubuntu-2004-kube-v1.26.5.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2004-kube-v1.26/ubuntu-2004-kube-v1.26.5.qcow2.CHECKSUM)    |
|        | v1.26.4  | [ubuntu-2004-kube-v1.26.4.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2004-kube-v1.26/ubuntu-2004-kube-v1.26.4.qcow2)     | [ubuntu-2004-kube-v1.26.4.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2004-kube-v1.26/ubuntu-2004-kube-v1.26.4.qcow2.CHECKSUM)    |
| v1.25  | v1.25.11 | [ubuntu-2004-kube-v1.25.11.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2004-kube-v1.25/ubuntu-2004-kube-v1.25.11.qcow2)   | [ubuntu-2004-kube-v1.25.11.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2004-kube-v1.25/ubuntu-2004-kube-v1.25.11.qcow2.CHECKSUM)  |
|        | v1.25.10 | [ubuntu-2004-kube-v1.25.10.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2004-kube-v1.25/ubuntu-2004-kube-v1.25.10.qcow2)   | [ubuntu-2004-kube-v1.25.10.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2004-kube-v1.25/ubuntu-2004-kube-v1.25.10.qcow2.CHECKSUM)  |
|        | v1.25.9  | [ubuntu-2004-kube-v1.25.9.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2004-kube-v1.25/ubuntu-2004-kube-v1.25.9.qcow2)     | [ubuntu-2004-kube-v1.25.9.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2004-kube-v1.25/ubuntu-2004-kube-v1.25.9.qcow2.CHECKSUM)    |

## Ubuntu 20.04 (Archived)

These images are no longer updated.

| Series | Version  | Image URL                                                                                                                                               | CHECKSUM URL                                                                                                                                                             |
|--------|----------|---------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| v1.24  | v1.24.15 | [ubuntu-2004-kube-v1.24.15.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2004-kube-v1.24/ubuntu-2004-kube-v1.24.15.qcow2)   | [ubuntu-2004-kube-v1.24.15.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2004-kube-v1.24/ubuntu-2004-kube-v1.24.15.qcow2.CHECKSUM)  |
|        | v1.24.14 | [ubuntu-2004-kube-v1.24.14.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2004-kube-v1.24/ubuntu-2004-kube-v1.24.14.qcow2)   | [ubuntu-2004-kube-v1.24.14.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2004-kube-v1.24/ubuntu-2004-kube-v1.24.14.qcow2.CHECKSUM)  |
|        | v1.24.13 | [ubuntu-2004-kube-v1.24.13.qcow2](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2004-kube-v1.24/ubuntu-2004-kube-v1.24.13.qcow2)   | [ubuntu-2004-kube-v1.24.13.qcow2.CHECKSUM](https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2004-kube-v1.24/ubuntu-2004-kube-v1.24.13.qcow2.CHECKSUM)  |

* https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2004-kube-v1.23/ubuntu-2004-kube-v1.23.qcow2
* https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2004-kube-v1.22/ubuntu-2004-kube-v1.22.qcow2
* https://swift.services.a.regiocloud.tech/swift/v1/AUTH_b182637428444b9aa302bb8d5a5a418c/openstack-k8s-capi-images/ubuntu-2004-kube-v1.21/ubuntu-2004-kube-v1.21.qcow2
