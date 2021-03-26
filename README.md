# Use environment

## Setup cli completion

``` bash
# install and build
npm install && npm run build

# change access permission
chmod u+x ./dist/cli.js

# link 
npm run link

# completion
npm run completion
```

terminal을 재시작 후 자동완성이 잘 되는지 확인합니다.
```
$ use gcloud <tab>
dev   -- development
prod  -- production
```