# vagrant-centos72-chef

## About

Vagrant base box containing CentOS 7.2 with Chef 12.15.19

## How to use

Shell 
```shell
$ vagrant init krzysztof/centos72-chef; 
$ vagrant up --provider virtualbox
```

or in Vagrantfile

```ruby
config.vm.box = "krzysztof/centos67-chef"
```
