## 容器内编译 radclient, radeapclient
``` bash
cd /app/third_party/freeradius-3.0.21

./configure --build=aarch64-unknown-linux-gnu

./configure --build=x86_64-unknown-linux-gnu

make
make install

ls /app/third_party/freeradius-3.0.21/build/bin/
dhcpclient  local  map_unit  radattr  radclient  radeapclient  radiusd radmin  radwho  rbmonkey  smbencrypt  unittest
```
