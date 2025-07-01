genlab.grafana
=========

This ansible role installs [Grafana](https://github.com/grafana/grafana) - the open-source platform for monitoring and observability. It can produce charts, graphs, and alerts for the web when connected to supported data sources.

 This role installs and configures Grafana from binary, uploads dashboards, installs plugins, imports public dashboards and datasources. You can also change admin passwords and create users.

Requirements
------------

You need `community.grafana` module. 

Role Variables
--------------

```
grafana_user: "grafana"
grafana_group: "grafana"
grafana_version: 11.5.0

```

Dependencies
------------

None

Example Playbook
----------------

```yaml
roles:
    - role: genlab.template
```

License
-------

BSD

Author Information
------------------

corvus-migratorius@proton.me
