## jprofiler

Set up [JProfiler](https://www.ej-technologies.com/products/jprofiler/overview.html).

#### Requirements

None

#### Role Variables

* `jprofiler_version` [default: `10.0.3`]: Version to install
* `jprofiler_install_prefix` [default: `/opt`]: Install prefix
* `jprofiler_downloads_path` [default: `/tmp`]: Download location
* `jprofiler_license_key` [default: ``]: License Key
* `jprofiler_license_name` [default: ``]: License Name
* `jprofiler_license_company` [default: ``]: License Company

## Dependencies

None

#### Example Playbook

```yaml
---
- hosts: all
  roles:
    - jprofiler
```

#### License

MIT

