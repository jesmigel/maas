# maas
Ansible deployment of canonical MaaS to an ESXI host

### Dependencies
| Dependency | Comments |
| - | - |
| [Ansible](https://docs.ansible.com/) | Configuration management automation tool|
| [ESXI (6.7u3)](https://my.vmware.com/en/group/vmware/evalcenter?p=free-esxi6) | Hypervisor |
| [Python](https://www.python.org/downloads/) | Programming language required to run ansible |
| [Vagrant](https://www.vagrantup.com/docs) | VM manager. Local dev/test environment |
| [Virtualenv](https://docs.python.org/3/tutorial/venv.html) | Python environment isolation |
|||

### References
| Name | Comments |
| - | - |
| [MaaS](https://maas.io/docs/installation) | Canonical Metal as a Service |
| [vagrant-vmware-esxi](https://github.com/josenk/vagrant-vmware-esxi) | OpenSource Vagrant-ESXI plugin |

## Requirements: sample hardware
- Dell Poweredge r710 (3x)
- Dell Poweredge r810 (2x)

### Blocker
- OVF Tool installation
