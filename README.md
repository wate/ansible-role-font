font
=================

Install font

OS Platform
-----------------

### Debian

- bookworm

Role Variables
--------------

### [defaults/main.yml](defaults/main.yml)

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードなどを参照してください。

#### `font_install_fonts`

インストールするパッケージ

#### `font_hackgen_version`

#### `font_plemoljp_version`

#### `font_udevgothic_version`

#### `font_moralerspace_version`

#### `font_firge_version`

#### `font_juisee_version`

#### `font_bizingothic_version`

#### `font_bizter_version`

#### `font_explex_version`

#### `font_nerdfonts_version`

#### `font_fontawesome_version`

#### `font_nerdfonts_variations`

インストールするNerd fontsのバリエーション

### [vars/main.yml](vars/main.yml)

設定値については[vars/main.yml](vars/main.yml)を参照してください。

#### `font_dir`

#### `font_hackgen_repo`

#### `font_plemoljp_repo`

#### `font_udevgothic_repo`

#### `font_moralerspace_repo`

#### `font_firge_repo`

#### `font_juisee_repo`

#### `font_bizingothic_repo`

#### `font_bizter_repo`

#### `font_explex_repo`

#### `font_nerdfonts_repo`

#### `font_fontawesome_repo`

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
