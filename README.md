AntPickax
---------

`AntPickax` includes open source software products which are necessary for Internet services in Yahoo! JAPAN. It includes basic libraries, components and systems.

`AntPickax` is a series of a challenging product that made it easy to solve complicated problems. We hope `AntPickax` products are widely used and create next innovations!

We will keep challenging to publish new open source software as a `AntPickax` product(like an **Ant** working with **pickax**).

### **Background**
Though we use and contribute a lot of open source software in Yahoo! JAPAN, we have started producing the `AntPickax` with the following background.
- Basic functions that are necessary internally are not sufficient.
- Adopting a new architecture to drastically reduce operating costs.
- Performance (mainly speed and scalability) is insufficient.
- License restrictions, it can not be introduced inside the company.

Among the created software, we have released software as an `AntPickax` product that has performance comparable to that of existing OSS and has useful functions not found in existing OSS.

### **AntPickax Product List**
The open source codes that the AntPickax product has published includes the following.

- [k2hdkc](https://github.com/yahoojapan/k2hdkc)  
High-speed autoscaleable distributed KVS cluster system created based on k2hash and chmpx.
- [k2hftfuse](https://github.com/yahoojapan/k2hftfuse)  
A component based on FUSE library which can transfer files, texts, logs at high speed, relay transfer, and aggregate.
- [k2hash](https://github.com/yahoojapan/k2hash)  
Key Value Store(KVS) library featuring high speed, large capacity and many functions.
- [chmpx](https://github.com/yahoojapan/chmpx)  
High-speed communication middleware capable of constructing a cluster.
- [k2htpdtor](https://github.com/yahoojapan/k2htp_dtor)  
A standard plug-in library for transaction processing linked with the k2hash library.
- [fullock](https://github.com/yahoojapan/k2hdkc)  
A fast and secure exclusive control library used by k2hash, chmpx.

### Doccuments
- [AntPickax](http://yahoojapan.github.io/AntPickax)

### License
This software is released under the MIT License, see the license file.

Copyright(C) 2018 Yahoo! JAPAN corporation.

