# rbenv

rbenv install to `${user_home_dir}/.rbenv`

## Requirements
Ubuntu

## Example

  ---
  - hosts: all
    roles:
    - role: Qooh0.rbenv_ubuntu

## Role Variables

- `rbenv_ruby_version`: global ruby version
- `rbenv_install_dir`: install location
- `rbenv_system_packages`: depends packages

## ansible Role Dependencies

None.

## APT Package Dependencies
- zlib1g-dev
- build-essential
- git
- libffi-dev
- libreadline6
- libreadline6-dev
- libssl-dev
- libssl1.0.0

## License

MIT License
