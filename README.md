Running:

```
ansible-playbook playbook.yaml
```

Will produce the following hiearchy:

```
output/
├── nerc-ocp-infra
│   ├── kustomization.yaml
│   ├── manifest_for_admin_acess.yaml
│   ├── manifest_for_internal_address.yaml
│   └── some_common_template.yaml
├── nerc-ocp-obs
│   ├── kustomization.yaml
│   ├── manifest_for_admin_acess.yaml
│   ├── manifest_for_external_address.yaml
│   └── some_common_template.yaml
└── nerc-ocp-pub
    ├── kustomization.yaml
    ├── manifest_for_external_address.yaml
    ├── manifest_for_public_access.yaml
    └── some_common_template.yaml
```
