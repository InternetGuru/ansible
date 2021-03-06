# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [1.3.0] - 2020-12-11
### Added
 - Add tags to distinguish user and global installation

### Changed
 - Show username and host in prompt
 - Apply ansible for all users process does not manipulate with passwords.

## [1.2.0] - 2020-11-30
### Added
 - Run commands for all users at once by `./all_users.sh 'command'`
 - Check installed version to prevent downgrade
 - Starship prompt
 - Fish shell
 - Sublime Text editor with shared settings
 - How to restore Variety default configuration

### Changed
 - Variety default configuration

### Removed
 - Zsh shell and oh-my-zsh
 - Remove Visual Studio Code

## [1.1.0] - 2020-10-15
### Added
 - Add `avahi-daemon` to `basic_enviroment.yml`

### Fixed
 - Ansible forces VirtualBox version to 6.0

[1.3.0]: https://github.com/InternetGuru/ansible/compare/v1.2.0...v1.3.0
[1.2.0]: https://github.com/InternetGuru/ansible/compare/v1.1.0...v1.2.0
[1.1.0]: https://github.com/InternetGuru/ansible/compare/v1.0.0...v1.1.0
