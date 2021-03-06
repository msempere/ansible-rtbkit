# Ansible playbook for RTBkit
This is an [Ansible](http://www.ansibleworks.com/) playbook for [RTBkit](http://rtbkit.org/site/). You can use it by itself or as part of a larger playbook customized for your local environment.

**Ansible-rtbkit** helps preparing and launching RTBkit's basic stack, described in:

- [RTBkit. Getting Started](https://github.com/rtbkit/rtbkit/wiki/Getting%20Started)
- [RTBkit. Demo stack](https://github.com/rtbkit/rtbkit/wiki/Demo-Stack)

## Requeriments:
This playbook asumes you are using an Amazon instance based on ami-7b531a12 (US East - N. Virginia), therefore [environment variables](https://github.com/rtbkit/rtbkit/wiki/Getting%20Started#environment-variables) and [platform-deps](https://github.com/rtbkit/rtbkit/wiki/Getting%20Started#platform-deps) are not installed.

## Installation (using Ansible Galaxy):
```sh
$ ansible-galaxy install msempere.rtbkit 
```
