Architecture
============

1. sys-vpn-{name}-dvm: Type AppVM, [Advanced tab] -> Disposable template. Base: debian-12-xfce. Playbook: `playbook-dvm-template.yaml`
2. sys-vpn-{name}: Type DisposableVM, [Advanced tab] -> Provides Network. Base: sys-vpn-{name}-dvm. Playbook: NONE
3. debian-12-xfce: Type Base template. Playbook: `playbook-template.yaml`
