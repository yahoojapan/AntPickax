AntPickax
---------

[**AntPickax**](https://antpick.ax/) includes open source software products which are necessary for Internet services in Yahoo! JAPAN. It includes basic libraries, components and systems.

[**AntPickax**](https://antpick.ax/) is a series of a challenging product that made it easy to solve complicated problems. We hope [**AntPickax**](https://antpick.ax/) products are widely used and create next innovations!

We will keep challenging to publish new open source software as a [**AntPickax**](https://antpick.ax/) product(like an **Ant** working with **pickax**).

### **Background**
Though we use and contribute a lot of open source software in Yahoo! JAPAN, we have started producing the [**AntPickax**](https://antpick.ax/) with the following background.
- Basic functions that are necessary internally are not sufficient.
- Adopting a new architecture to drastically reduce operating costs.
- Performance (mainly speed and scalability) is insufficient.
- License restrictions, it can not be introduced inside the company.

Among the created software, we have released software as an [**AntPickax**](https://antpick.ax/) product that has performance comparable to that of existing OSS and has useful functions not found in existing OSS.

### **AntPickax Product List**

![AntPickax Products](https://antpick.ax/images/top_antpickax.png)

The open source codes that the AntPickax product has published includes the following.

#### [K2HDKC DBAAS](https://github.com/yahoojapan/k2hdkc_dbaas)
Database as a Service for K2HDKC is provided by Trove(OpenStack component).
- [K2HDKC DBaaS Override Configuration](https://github.com/yahoojapan/k2hdkc_dbaas_override_conf)

#### [K2HR3](https://github.com/yahoojapan/k2hr3)
RBAC system(K2Hdkc based Resource and Roles and policy Rules).  
- [K2HR3 REST API](https://github.com/yahoojapan/k2hr3_api) - K2HR3 Backend server
- [K2HR3 Web Appication](https://github.com/yahoojapan/k2hr3_app) - K2HR3 GUI Frontend
- [K2HR3 Utilities](https://github.com/yahoojapan/k2hr3_utils)
- [K2HR3 OpenStack Notification Listener](https://github.com/yahoojapan/k2hr3_osnl)
- [K2HR3 Container Registration Sidecar](https://github.com/yahoojapan/k2hr3_sidecar)
- [K2HR3 Get Resource](https://github.com/yahoojapan/k2hr3_get_resource)

#### [K2HDKC](https://github.com/yahoojapan/k2hdkc)
High-speed autoscaleable distributed KVS cluster system created based on k2hash and chmpx.
- [K2HDKC nodejs addon](https://github.com/yahoojapan/k2hdkc_nodejs) - Node.js addon library
- [K2HDKC java driver](https://github.com/yahoojapan/k2hdkc_java) - Java driver
- [K2HDKC golang](https://github.com/yahoojapan/k2hdkc_go) - golang library

#### [K2HFTFUSE](https://github.com/yahoojapan/k2hftfuse)
A component based on FUSE library which can transfer files, texts, logs at high speed, relay transfer, and aggregate.

#### [CHMPX](https://github.com/yahoojapan/chmpx)
High-speed communication middleware capable of constructing a cluster.
- [CHMPX nodejs addon](https://github.com/yahoojapan/chmpx_nodejs) - Node.js addon library

#### [K2HASH](https://github.com/yahoojapan/k2hash)
Key Value Store(KVS) library featuring high speed, large capacity and many functions.
- [K2HASH nodejs addon](https://github.com/yahoojapan/k2hash_nodejs) - Node.js addon library
- [K2HASH java driver](https://github.com/yahoojapan/k2hash_java) - Java driver
- [K2HASH golang](https://github.com/yahoojapan/k2hash_go) - golang library
- [K2HTPDTOR](https://github.com/yahoojapan/k2htp_dtor) - Standard plug-in for K2HASH Transaction processing
- [K2HTPMDTOR](https://github.com/yahoojapan/k2htp_mdtor) Multiple plug-in for K2HASH Transaction processing

#### [FULLOCK](https://github.com/yahoojapan/fullock)
A fast and secure exclusive control library used by k2hash, chmpx.

### Documents
- [AntPickax](https://antpick.ax/)
- [k2hdkc dbaas](https://dbaas.k2hdkc.antpick.ax/)
- [k2hr3](https://k2hr3.antpick.ax/)
- [k2hr3 demonstration](https://demo.k2hr3.antpick.ax/)
- [k2hdkc](https://k2hdkc.antpick.ax/)
- [k2hdkc nodejs addon](https://nodejs.k2hdkc.antpick.ax/)
- [k2hdkc java driver](https://java.k2hdkc.antpick.ax/)
- [k2hftfuse](https://k2hftfuse.antpick.ax/)
- [chmpx](https://chmpx.antpick.ax/)
- [chmpx nodejs addon](https://nodejs.chmpx.antpick.ax/)
- [k2hash](https://k2hash.antpick.ax/)
- [k2hash nodejs addon](https://nodejs.k2hash.antpick.ax/)
- [k2hash java driver](https://java.k2hash.antpick.ax/)
- [k2htpdtor](https://k2htpdtor.antpick.ax/)
- [k2htpmdtor](https://k2htpmdtor.antpick.ax/)
- [fullock](https://fullock.antpick.ax/)

### License
This software is released under the MIT License, see the license file.

Copyright(C) 2018 Yahoo Japan Corporation.
