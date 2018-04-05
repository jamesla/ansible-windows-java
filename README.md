# ansible-windows-java
Installs Java on Windows

### Usage

playbook.yml:
```
- { role: ansible-windows-java }
```

requirements.yml:
```
- src: https://github.com/jamesla/ansible-windows-java.git
  version: master
  name: ansible-windows-java
```

### Options

Override these variables to change the version of JDK installed.
```
jdk_package: jdk8
java_major_version: 8.0
java_minor_version: 162
```

### Note

This role installs JDK.
