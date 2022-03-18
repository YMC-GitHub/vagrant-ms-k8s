# vagrant-ms-k8s

prepare k8s stack ms envirenment with vagrant

## prepare

- virtualbox
- vagrant

## setup

```bash
# speed up git clone in china
GC_PROXY="https://ghproxy.com/"
GC_URL="https://github.com/YMC-GitHub/vagrant-ms-k8s.git"
GC_URL="${GC_PROXY}${GC_URL}"
git clone -b main "$GC_URL"
```

## start

```bash
vagrant up
```

## usage
```bash
vagrant ssh
```

## Author

yemiancheng <ymc.github@gmail.com>

## License

MIT

## operation system

now is ubuntu server 1804
