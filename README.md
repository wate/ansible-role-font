font
=================

install font

OS Platform
-----------------

### Debian

- bookworm

Role Variables
--------------

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードを参照してください。

### `font_install_fonts`

インストールするパッケージ

### `font_hackgen_version`

### `font_plemoljp_version`

### `font_udevgothic_version`

### `font_moralerspace_version`

### `font_firge_version`

### `font_juisee_version`

### `font_bizingothic_version`

### `font_explex_version`

### `font_nerd_version`

### `font_nerd_variations`

インストールするNerd fontのバリエーション

Example Playbook
--------------

```yaml
- hosts: servers
  roles:
    - role: font
```

License
--------------

Apache License 2.0
