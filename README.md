## Clone to starling
```
cd /data
git clone https://github.com/wvat/starling_scripts.git
```

## Install
```
export NAMESPACE=r0
cd /data/starling_scripts
bash setup-local.bash --ros ${NAMESPACE} --params --docker --offboard --disable-cams --pac ${NAMESPACE}
```

