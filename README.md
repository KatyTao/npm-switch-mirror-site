# npm-switch-mirror-site
## Method 1
```
npm config set registry URL
```
Replace url to the site address

Taobao:`http://registry.npm.taobao.org`

---

## Method 2
Install nrm
```
npm install -g nrm
```

```
nrm use taobao
```
Can also check site lists through

```
nrm ls
```

#### Add customized site address
```
nrm add URL 'registry_name'
```

#### Delete site address
```
nrm del 'registry_name'
```

#### Test response speed
```
nrm test ['registry_name']
```
