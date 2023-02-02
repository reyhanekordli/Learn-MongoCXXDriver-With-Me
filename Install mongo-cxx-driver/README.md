## MONGO-CXX-DRIVER on Linux

**releases:**

`https://github.com/mongodb/mongo-cxx-driver/releases`

**I Used the following instructure for guidance:**

`https://mongocxx.org/mongocxx-v3/installation/linux/`

```bash
curl -OL https://github.com/mongodb/mongo-cxx-driver/releases/download/r3.7.0/mongo-cxx-driver-r3.7.0.tar.gz
tar -xzf mongo-cxx-driver-r3.7.0.tar.gz
cd mongo-cxx-driver-r3.7.0/build
```

```bash
cmake .. -DCMAKE_BUILD_TYPE=Release -DCMAKE_INSTALL_PREFIX=/usr/local
```

```bash
sudo cmake --build . --target EP_mnmlstc_core
```

**Building the driver:**

```bash
cmake --build .
```

**Now install the driver:**

```bash
sudo cmake --build . --target install
```

### You successfully installed mongo-cxx-driver on distro!
