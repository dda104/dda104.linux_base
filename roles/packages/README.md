# packages

Role for install and upgrade packages on Linux systems

## Table of content

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [packages_list](#packages_list)
  - [packages_skip_upgrade](#packages_skip_upgrade)
  - [packages_snap_list](#packages_snap_list)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.11`

## Default Variables

### packages_list

#### Default value

```YAML
packages_list: []
```

### packages_skip_upgrade

#### Default value

```YAML
packages_skip_upgrade: true
```

### packages_snap_list

#### Default value

```YAML
packages_snap_list: []
```

## Dependencies

None.

## License

Unlicense

## Author

Denis Dvornikov
