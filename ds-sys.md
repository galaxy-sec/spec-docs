```
Usage: ds-sys <COMMAND>

Commands:
  new       
  update    
  localize  
  help      Print this message or the help of the given subcommand(s)

Options:
  -h, --help     Print help
  -V, --version  Print version

```

## mod-list

```yaml
- name: fluent-bit
  addr:
    repo: git@github...
    branch:  master
  node: arm-mac14-host
  enable: true

- name: gflow
  addr:
    repo: git@github...
    tag: 0.5.0
  node: arm-mac14-host
  enable: true

- name: ds-mod
  addr:
    repo: git@github...
    branch : main
  node: arm-mac14-host
  enable: true
```
