Npm
=========

Setup npm global dependencies

Requirements
------------

Need ansible 2+

Role Variables
--------------

```yaml
npm_packages:
  - yarn
  - name: webpack
    version: 3
  - name: grunt
    state: absent
```

Dependencies
------------

Nodejs / npm must be installed

Example Playbook
----------------

```yaml
npm_packages:
  - yarn
  - name: webpack
    version: 3
  - name: grunt
    state: absent
```

License
-------

BSD
