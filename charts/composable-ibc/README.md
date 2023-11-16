# composable-ibc

![Version: 0.1.0](https://img.shields.io/badge/Version-0.1.0-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 0.1.0](https://img.shields.io/badge/AppVersion-0.1.0-informational?style=flat-square)

A Helm chart withy deployment manifests of composable-ibc for Kubernetes

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| affinity | object | `{}` |  |
| args[0] | string | `"relay"` |  |
| args[1] | string | `"--config-a"` |  |
| args[2] | string | `"/config-a.toml"` |  |
| args[3] | string | `"--config-b"` |  |
| args[4] | string | `"/config-b.toml"` |  |
| args[5] | string | `"--config-core"` |  |
| args[6] | string | `"/config-core.toml"` |  |
| extraLabels | object | `{}` | Additional common labels on pods and services |
| fullnameOverride | string | `""` |  |
| fullnameOverride | string | `""` | Provide a name to substitute for the full names of resources |
| image | object | `{"pullPolicy":"IfNotPresent","repository":"composablefi/composable-ibc","tag":"master"}` | Image of relayer. |
| image.pullPolicy | string | `"IfNotPresent"` | Image pull policy |
| image.repository | string | `"composablefi/composable-ibc"` | Image repository |
| image.tag | string | `"master"` | Image tag |
| imagePullSecrets | list | `[]` |  |
| nameOverride | string | `""` | Provide a name in place of node for `app:` labels |
| nameOverride | string | `""` |  |
| nodeSelector | object | `{}` |  |
| podAnnotations | object | `{}` |  |
| podSecurityContext | object | `{}` |  |
| replicaCount | int | `1` | Number of replicas |
| resources | object | `{}` |  |
| securityContext | object | `{}` |  |
| serviceAccount.annotations | object | `{}` |  |
| serviceAccount.create | bool | `true` |  |
| serviceAccount.name | string | `""` |  |
| tolerations | list | `[]` |  |

