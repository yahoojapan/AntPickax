---
layout: default
language: en-us
title: AntPickax
short_desc: AntPickax provides basic libraries, components and systems
lang_opp_file: indexja.html
lang_opp_word: To Japanese
title_k2hdkc_dbaas: <a class="to_antpickax_banner" href="https://dbaas.k2hdkc.antpick.ax/">K2HDKC DBaaS</a>
title_k2hr3: <a class="to_antpickax_banner" href="https://k2hr3.antpick.ax/">K2HR3</a>
title_k2hdkc: <a class="to_antpickax_banner" href="https://k2hdkc.antpick.ax/">K2HDKC</a>
title_k2hdkc_nodejs: <a class="to_antpickax_banner" href="https://nodejs.k2hdkc.antpick.ax/">K2HDKC nodejs addon</a>
title_k2hdkc_phpext: <a class="to_antpickax_banner" href="https://php.k2hdkc.antpick.ax/">K2HDKC phpext</a>
title_k2hdkc_java: <a class="to_antpickax_banner" href="https://java.k2hdkc.antpick.ax/">K2HDKC java driver</a>
title_k2hdkc_go: <a class="to_antpickax_banner" href="https://pkg.go.dev/github.com/yahoojapan/k2hdkc_go/k2hdkc">K2HDKC golang</a>
title_k2hdkc_python: <a class="to_antpickax_banner" href="https://k2hdkc-python.readthedocs.io/">K2HDKC python</a>
title_k2hftfuse: <a class="to_antpickax_banner" href="https://k2hftfuse.antpick.ax/">K2HFTFUSE</a>
title_k2hash: <a class="to_antpickax_banner" href="https://k2hash.antpick.ax/">K2HASH</a>
title_k2hash_nodejs: <a class="to_antpickax_banner" href="https://nodejs.k2hash.antpick.ax/">K2HASH nodejs addon</a>
title_k2hash_java: <a class="to_antpickax_banner" href="https://java.k2hash.antpick.ax/">K2HASH java driver</a>
title_k2hash_go: <a class="to_antpickax_banner" href="https://pkg.go.dev/github.com/yahoojapan/k2hash_go/k2hash">K2HASH golang</a>
title_k2hash_python: <a class="to_antpickax_banner" href="https://k2hash-python.readthedocs.io/">K2HASH python</a>
title_k2hash_phpext: <a class="to_antpickax_banner" href="https://php.k2hash.antpick.ax/">K2HASH phpext</a>
title_chmpx: <a class="to_antpickax_banner" href="https://chmpx.antpick.ax/">CHMPX</a>
title_chmpx_nodejs: <a class="to_antpickax_banner" href="https://nodejs.chmpx.antpick.ax/">CHMPX nodejs addon</a>
title_chmpx_phpext: <a class="to_antpickax_banner" href="https://php.chmpx.antpick.ax/">CHMPX phpext</a>
title_k2htpdtor: <a class="to_antpickax_banner" href="https://k2htpdtor.antpick.ax/">K2HTP_DTOR</a>
title_k2htpmdtor: <a class="to_antpickax_banner" href="https://k2htpmdtor.antpick.ax/">K2HTP_MDTOR</a>
title_fullock: <a class="to_antpickax_banner" href="https://fullock.antpick.ax/">FULLOCK</a>
antpickax_icon: <span class="antpickax-icon-font-icon"></span>
github_icon: <span class="to_git_icon"></span>
---

# **AntPickax**
**AntPickax** includes open source software products which are necessary for Internet services in Yahoo! JAPAN. It includes basic libraries, components and systems.

**AntPickax** is a series of a challenging product that made it easy to solve complicated problems. We hope **AntPickax** products are widely used and create next innovations!

We will keep challenging to publish new open source software as a **AntPickax** product(like an **Ant** working with a  **pickax**).

### **Background**
Though we use and contribute a lot of open source software in Yahoo! JAPAN, we have started producing **AntPickax** with the following background.
- Basic functions that are necessary internally are not sufficient.
- Adopting a new architecture to drastically reduce operating costs.
- Performance (mainly speed and scalability) is insufficient.
- License restrictions, it can not be introduced inside the company.

Among the created software, we have released software as an **AntPickax** product that has performance comparable to that of existing OSS and has useful functions not found in existing OSS.

## **AntPickax Product List**

![AntPickax Products](images/top_antpickax.png)

**AntPickax** publishes the following products as open source.

### **K2HDKC DBaaS**
[**K2HDKC DBaaS**](https://dbaas.k2hdkc.antpick.ax/) (Database as a Service for K2HDKC) is a **Database as a Service** that uses [K2HR3](https://k2hr3.antpick.ax/) and works with [OpenStack](https://www.openstack.org/) and [kubernetes](https://kubernetes.io/) to build a [K2HDKC(K2Hash based Distributed Kvs Cluster)](https://k2hdkc.antpick.ax/index.html) Cluster for distributed KVS.
### **K2HR3**
[**K2HR3**](https://k2hr3.antpick.ax/) (**K2H**dkc based **R**esource and **R**oles and policy **R**ules) is an **RBAC**(**R**ole **B**ased **A**ccess **C**ontrol) system that cooperates with **IaaS**(Infrastructure as a Service).
### **K2HDKC**
[**K2HDKC**](https://k2hdkc.antpick.ax/) (**K2H**ash based **D**istributed **K**vs **C**luster) is a high performance and horizontal scalable distributed KVS cluster system based on [**K2HASH**](https://k2hash.antpick.ax/) and [**CHMPX**](https://chmpx.antpick.ax/).
### **K2HFTFUSE**
[**K2HFTFUSE**](https://k2hftfuse.antpick.ax/) (**K2H**ash **F**ile **T**ransaction by **FUSE** based file system) is a component based on FUSE library which can transfer files, texts and logs at high speed and relay them and aggregate them.
### **CHMPX**
[**CHMPX**](https://chmpx.antpick.ax/) (**C**onsistent **H**ashing **M**q in**P**rocess data e**X**change) is a very fast network communication middleware to construct a cluster.
### **K2HASH**
[**K2HASH**](https://k2hash.antpick.ax/) is a vey fast Key Value Store(KVS) library featuring very large file support and many useful functions.
### **FULLOCK**
[**FULLOCK**](https://fullock.antpick.ax/) (**F**ast **U**ser **L**evel **LOCK** library) is a very fast and powerful lock library for multithread and multiprocess used in [**K2HASH**](https://k2hash.antpick.ax/), [**CHMPX**](https://chmpx.antpick.ax/).

# **AntPickax Products**

## {{ page.title_k2hdkc_dbaas }}

[**K2HDKC DBaaS** (Database as a Service for K2HDKC)](https://dbaas.k2hdkc.antpick.ax/) is a **Database as a Service** that uses [K2HR3](https://k2hr3.antpick.ax/) and works with [OpenStack](https://www.openstack.org/) to build a [K2HDKC(K2Hash based Distributed Kvs Cluster)](https://k2hdkc.antpick.ax/index.html) Cluster for distributed KVS.  

[**K2HDKC DBaaS** (Database as a Service for K2HDKC)](https://dbaas.k2hdkc.antpick.ax/) provides **four ways**.  

- **K2HDKC DBaaS** with Trove  
This is **DBaaS (Database as a Service)** using [Trove(Trove is Database as a Service for OpenStack)](https://wiki.openstack.org/wiki/Trove), which is a product of [OpenStack](https://www.openstack.org/).  
This type embeds [K2HDKC](https://k2hdkc.antpick.ax/) as one database(distributed KVS) of [Trove(Trove is Database as a Service for OpenStack)](https://wiki.openstack.org/wiki/Trove) and realizes DBaaS.  

- **K2HDKC DBaaS CLI**  
Realize **DBaaS (Database as a Service)** by using **Command Line Interface (CLI)** for [OpenStack](https://www.openstack.org/).  
Delivered as a **K2HDKC DBaaS CLI (Command Line Interface)**, it automates the construction and scaling of [K2HDKC](https://k2hdkc.antpick.ax/index.html) clusters, data merging, etc. as **Database as a Service**.  

- **K2HDKC DBaaS on Kubernetes CLI**  
Realize **DBaaS (Database as a Service)** by using **Command Line Interface (CLI)** for [kubernetes](https://kubernetes.io/).  
Delivered as **K2HDKC DBaaS on kubernetes CLI (Command Line Interface)**, it automates the construction and scaling of [K2HDKC](https://k2hdkc.antpick.ax/index.html) clusters as **Database as a Service**.  

- **K2HDKC Helm Chart**  
Implement **DBaaS (Database as a Service)** using [Helm(The package manager for Kubernetes)](https://helm.sh/) for [kubernetes](https://kubernetes.io/).  
Delivered as **K2HDKC Helm Chart**, it automates the construction and scaling of [K2HDKC](https://k2hdkc.antpick.ax/index.html) clusters as **Database as a Service**.  
In addition, **K2HDKC Helm Chart** can be registered as a repository in [RANCHER](https://rancher.com/) as **RANCHER Helm Chart** and used.  

[**K2HDKC DBaaS**](https://dbaas.k2hdkc.antpick.ax/) is built using [Trove](https://wiki.openstack.org/wiki/Trove) and [**K2HDKC**](https://k2hdkc.antpick.ax/), [**K2HR3**](https://k2hr3.antpick.ax/), [**CHMPX**](https://chmpx.antpick.ax/), etc. published by Yahoo! JAPAN.  

Please refer to the following for details.  
- **Information aggregation of K2HDKC DBaaS** - {{ page.github_icon }}[**Codes on github**](https://github.com/yahoojapan/k2hdkc_dbaas) and {{ page.antpickax_icon }}[**Documents**](https://dbaas.k2hdkc.antpick.ax/)

- **K2HDKC DBaaS** with Trove - {{ page.github_icon }}[**Codes on github**](https://github.com/yahoojapan/k2hdkc_dbaas_trove) and {{ page.antpickax_icon }}[**Usage**](https://dbaas.k2hdkc.antpick.ax/usage_trove.html)

- **K2HDKC DBaaS CLI**(Command Line Interface) - {{ page.github_icon }}[**Codes on github**](https://github.com/yahoojapan/k2hdkc_dbaas_cli) and {{ page.antpickax_icon }}[**Usage**](https://dbaas.k2hdkc.antpick.ax/usage_cli.html)

- **K2HDKC DBaaS on kubernetes CLI**(Command Line Interface) - {{ page.github_icon }}[**Codes on github**](https://github.com/yahoojapan/k2hdkc_dbaas_k8s_cli) and {{ page.antpickax_icon }}[**Usage**](https://dbaas.k2hdkc.antpick.ax/usage_k8s_cli.html)

- **K2HDKC Helm Chart** - {{ page.github_icon }}[**Codes on github**](https://github.com/yahoojapan/k2hdkc_helm_chart) and {{ page.antpickax_icon }}[**Usage**](https://dbaas.k2hdkc.antpick.ax/usage_helm_chart.html)

- **Utility - K2HDKC DBaaS Override Configuration** - {{ page.github_icon }}[**Codes on github**](https://github.com/yahoojapan/k2hdkc_dbaas_override_conf)

## {{ page.title_k2hr3 }}
[**K2HR3**](https://k2hr3.antpick.ax/) (**K2H**dkc based **R**esource and **R**oles and policy **R**ules) is one of **RBAC** (**R**ole **B**ased **A**ccess **C**ontrol) systems provided by Yahoo! JAPAN.  

[**K2HR3**](https://k2hr3.antpick.ax/) works as **RBAC** in cooperation with **OpenStack** which is one of **IaaS** (Infrastructure as a Service), and also provides **useful functions** for using RBAC.  

[**K2HR3**](https://k2hr3.antpick.ax/) gathers common management information for the cloud, and is built [**K2HASH**](https://k2hash.antpick.ax/), [**K2HTP_DTOR**](https://k2htpdtor.antpick.ax/), [**CHMPX**](https://chmpx.antpick.ax/) and [**K2HDKC**](https://k2hdkc.antpick.ax/) components.  

[**K2HR3**](https://k2hr3.antpick.ax/) consists of the following components and tools.  

- **Information aggregation of K2HR3** - {{ page.github_icon }}[**Codes on github**](https://github.com/yahoojapan/k2hr3) and {{ page.antpickax_icon }}[**Documents**](https://k2hr3.antpick.ax/)

- **Web Application** - {{ page.github_icon }}[**Codes on github**](https://github.com/yahoojapan/k2hr3_app) and {{ page.antpickax_icon }}[**Demonstration**](https://demo.k2hr3.antpick.ax/)

- **Command Line Interface(CLI)** - {{ page.github_icon }}[**Codes on github**](https://github.com/yahoojapan/k2hr3_cli) and {{ page.antpickax_icon }}[**Usage**](https://k2hr3.antpick.ax/cli.html)

- **REST API** - {{ page.github_icon }}[**Codes on github**](https://github.com/yahoojapan/k2hr3_api) and {{ page.antpickax_icon }}[**Demonstration**](https://k2hr3.antpick.ax/api.html)

- **Helm Chart** - {{ page.github_icon }}[**Codes on github**](https://github.com/yahoojapan/k2hr3_helm_chart) and {{ page.antpickax_icon }}[**Documents**](https://k2hr3.antpick.ax/helm_chart.html)

- **OpenStack Notification Listener** - {{ page.github_icon }}[**Codes on github**](https://github.com/yahoojapan/k2hr3_osnl)

- **Utilities** - {{ page.github_icon }}[**Codes on github**](https://github.com/yahoojapan/k2hr3_utils)

- **Container Registration Sidecar** - {{ page.github_icon }}[**Codes on github**](https://github.com/yahoojapan/k2hr3_sidecar)

- **K2HR3 Get Resource** - {{ page.github_icon }}[**Codes on github**](https://github.com/yahoojapan/k2hr3_get_resource)

## {{ page.title_k2hdkc }}
K2HDKC (**k2h**ash based **D**istributed **K**vs **C**luster) is a high performance and horizontal scalable distributed KVS cluster system based on [**K2HASH**](https://k2hash.antpick.ax/), [**CHMPX**](https://chmpx.antpick.ax/) Distributed Key Value Store(KVS).  

The K2HDKC has unique features shown below.
- **Consistency** (Automatic Data Synchronization between Server Nodes)  
Provides automatic merging function of data due to failure/recovery of server nodes in the cluster.
- **Automatic Scaling**  
Server nodes can be added/deleted to the cluster, and the data automatic merging function at this time is also provided.
- **Nested key structure**  
Provides the association function of key and subkey which is the feature of [**K2HASH**](https://k2hash.antpick.ax/) as distributed KVS.
- **Queue(FIFO/LIFO)**  
Provides the queuing function which is the feature of [**K2HASH**](https://k2hash.antpick.ax/) as distributed KVS.
- **Transaction Plugins**  
Provides a function that can perform arbitrary processing using data update processing which is the feature of [**K2HASH**](https://k2hash.antpick.ax/) as a trigger of transaction.
- **Encryption**  
Provides encryption function as distributed KVS for the key's data held as the feature of [**K2HASH**](https://k2hash.antpick.ax/).
- **Expiration**  
Provides the key expiration function which is the feature of [**K2HASH**](https://k2hash.antpick.ax/) as distributed KVS.

For details, please refer to {{ page.github_icon }}[**Codes on github**](https://github.com/yahoojapan/k2hdkc), {{ page.antpickax_icon }}[**Documents**](https://k2hdkc.antpick.ax/).

## {{ page.title_k2hdkc_nodejs }}
[**K2HDKC nodejs addon**](https://nodejs.k2hdkc.antpick.ax/)（**K2HDKC** nodejs addon - **K2H**ash based **D**istributed **K**vs **C**luster) is a Node.js addon library of [**K2HDKC**](https://k2hdkc.antpick.ax/).  
Using this library, [**K2HDKC**](https://k2hdkc.antpick.ax/)'s slave side client application can be implemented with Node.js based JavaScript.  
[**K2HDKC nodejs addon**](https://nodejs.k2hdkc.antpick.ax/) provides all functions and features necessary for the slave side client of distributed KVS of [**K2HDKC**](https://k2hdkc.antpick.ax/).  

For details, please refer to {{ page.github_icon }}[**Codes on github**](https://github.com/yahoojapan/k2hdkc_nodejs), {{ page.antpickax_icon }}[**Documents**](https://nodejs.k2hdkc.antpick.ax/).

## {{ page.title_k2hdkc_phpext }}
[**K2HDKC phpext**](https://php.k2hdkc.antpick.ax/)（**K2HDKC** phpext - Consistent Hashing Mq inProcess data eXchange) is a php extension library of [**K2HDKC**](https://k2hdkc.antpick.ax/).  
Using this library, [**K2HDKC**](https://k2hdkc.antpick.ax/)'s slave side client application can be implemented with this PHP Extention library.  
[**K2HDKC phpext**](https://php.k2hdkc.antpick.ax/) provides all functions and features of [**K2HDKC**](https://k2hdkc.antpick.ax/).  

For details, please refer to {{ page.github_icon }}[**Codes on github**](https://github.com/yahoojapan/k2hdkc_phpext), {{ page.antpickax_icon }}[**Documents**](https://php.k2hdkc.antpick.ax/).

## {{ page.title_k2hdkc_java }}
[**Java Driver for K2HDKC**](https://java.k2hdkc.antpick.ax/index.html)（Java Driver for **K2HDKC**) is an official Java client library for [**K2HDKC**](https://k2hdkc.antpick.ax/index.html).  
This library provies all functions and features necessary for the slave side client of distributed KVS of [**K2HDKC**](https://k2hdkc.antpick.ax/).  
That means eveyone is able to implement [**K2HDKC**](https://k2hdkc.antpick.ax/)'s slave side client application by using this library.  

For details, see the {{ page.github_icon }}[**Code on GitHub**](https://github.com/yahoojapan/k2hdkc_java), {{ page.antpickax_icon }}[**Documents**](https://java.k2hdkc.antpick.ax/index.html).

## {{ page.title_k2hdkc_go }}
[**K2HDKC golang**](https://pkg.go.dev/github.com/yahoojapan/k2hdkc_go/k2hdkc) (**K2HDKC** golang - **K2H**ash based **D**istributed **K**vs **C**luster) is [**K2HDKC**](https://k2hdkc.antpick.ax/)'s Go language client library.  
You can use this library to implement [**K2HDKC**](https://k2hdkc.antpick.ax/) slave-side client applications in Go language.  
[**K2HDKC golang**](https://pkg.go.dev/github.com/yahoojapan/k2hdkc_go/k2hdkc) provides all the features and features required for the slave side client of the distributed KVS of [**K2HDKC**](https://k2hdkc.antpick.ax/).  

For details, see the {{ page.github_icon }}[**Code on GitHub**](https://github.com/yahoojapan/k2hdkc_go), {{ page.antpickax_icon }}[**Documents**](https://pkg.go.dev/github.com/yahoojapan/k2hdkc_go/k2hdkc).

## {{ page.title_k2hdkc_python }}
[**K2HDKC python**](https://k2hdkc-python.readthedocs.io/en/latest/) (**K2HDKC** python - **K2H**ash based **D**istributed **K**vs **C**luster) is [**K2HDKC**](https://k2hdkc.antpick.ax/)'s Python language client library.  
You can use this library to implement [**K2HDKC**](https://k2hdkc.antpick.ax/) slave-side client applications in Python language.  
[**K2HDKC python**](https://k2hdkc-python.readthedocs.io/en/latest/) provides all the features and features required for the slave side client of the distributed KVS of [**K2HDKC**](https://k2hdkc.antpick.ax/).  

For details, see the {{ page.github_icon }}[**Code on GitHub**](https://github.com/yahoojapan/k2hdkc_python), {{ page.antpickax_icon }}[**Documents**](https://k2hdkc-python.readthedocs.io/en/latest/).

## {{ page.title_k2hftfuse }}
[**K2HFTFUSE**](https://k2hftfuse.antpick.ax/)(**k2h**ash **F**ile **T**ransaction by **FUSE** based file system) is [FUSE (Filesystem in Userspace)](https://github.com/libfuse/libfuse) is a file/message transfer system using the user space mounting function.  

[**K2HFTFUSE**](https://k2hftfuse.antpick.ax/) is a system developed to realize **reliable** and **fast** file/message transfer at low cost.  
[**K2HFTFUSE**](https://k2hftfuse.antpick.ax/) provides a virtual file system, you can use it by writing the file to the mounted directory.  
Just by mounting the directory of the output file of the existing program with [**K2HFTFUSE**](https://k2hftfuse.antpick.ax/), you can transfer files/messages **without changing** the existing program.

- **Zero cost integration with applications**  
Additional API dependency for client applications is zero!
- **Very fast and reliable file transfer**  
Very fast and reliable file transfer based on [**K2HASH**](https://k2hash.antpick.ax/) and [**CHMPX**](https://chmpx.antpick.ax/).
- **Various data format**  
Supported data formats are a single data message, a text file and a binary file.
- **Filter**  
Processing data for your purpose very easily!
- **Trigger**  
Invoking your own function against particular data.

For details, please refer to {{ page.github_icon }}[**Codes on github**](https://github.com/yahoojapan/k2hftfuse), {{ page.antpickax_icon }}[**Documents**](https://k2hftfuse.antpick.ax/).

## {{ page.title_chmpx }}
[**CHMPX**](https://chmpx.antpick.ax/) (**C**onsistent **H**ashing **M**q in**P**rocess data e**X**change) is a communication middleware for sending and receiving binary data between processes that cross network.

- **Basic functions**  
[**CHMPX**](https://chmpx.antpick.ax/) is responsible for communication between the server program and the client program, and hides the network communication connection from each program.
- **Cluster/Multiplexing/Auto scaling**  
[**CHMPX**](https://chmpx.antpick.ax/) is a communication middleware that can create a cluster configuration, has high fault tolerance and multiplexing, and can be autoscaled.
- **Communication data**  
The format of the data to communicate is free, and it can communicate binary data and large size data.
- **Communication encryption**  
Supports communication with SSL.
- **Communication multiplexing/Parallel processing**  
Can multiplex and parallel communication between [**CHMPX**](https://chmpx.antpick.ax/) server and slave.
- **Queuing communication data**  
Data to be transmitted/received is queued and data will not be lost even with small delay due to high load etc.
- **Multi-threading/Multi-processing**  
The client program can use this component in multi process, multithreading.

For details, please refer to {{ page.github_icon }}[**Codes on github**](https://github.com/yahoojapan/chmpx), {{ page.antpickax_icon }}[**Documents**](https://chmpx.antpick.ax/).

## {{ page.title_chmpx_nodejs }}
[**CHMPX nodejs addon**](https://nodejs.chmpx.antpick.ax/)（**CHMPX** nodejs addon - Consistent Hashing Mq inProcess data eXchange) is a Node.js addon library of [**CHMPX**](https://chmpx.antpick.ax/).  
Using this library, both server side and slave side of communication program using [**CHMPX**](https://chmpx.antpick.ax/) can be implemented with Node.js based JavaScript program.  
[**CHMPX nodejs addon**](https://nodejs.chmpx.antpick.ax/) provides all functions and features of [**CHMPX**](https://chmpx.antpick.ax/).  

For details, please refer to {{ page.github_icon }}[**Codes on github**](https://github.com/yahoojapan/chmpx_nodejs), {{ page.antpickax_icon }}[**Documents**](https://nodejs.chmpx.antpick.ax/).

## {{ page.title_chmpx_phpext }}
[**CHMPX phpext**](https://php.chmpx.antpick.ax/)（**CHMPX** phpext - Consistent Hashing Mq inProcess data eXchange) is a php extension library of [**CHMPX**](https://chmpx.antpick.ax/).  
Using this library, both server side and slave side of communication program using [**CHMPX**](https://chmpx.antpick.ax/) can be implemented with your PHP application program.  
[**CHMPX phpext**](https://php.chmpx.antpick.ax/) provides all functions and features of [**CHMPX**](https://chmpx.antpick.ax/).  

For details, please refer to {{ page.github_icon }}[**Codes on github**](https://github.com/yahoojapan/chmpx_phpext), {{ page.antpickax_icon }}[**Documents**](https://php.chmpx.antpick.ax/).

## {{ page.title_k2hash }}
[**K2HASH**](https://k2hash.antpick.ax/) is a NoSQL Key Value Store(KVS) library.
[**K2HASH**](https://k2hash.antpick.ax/) has basic KVS functions and unique features shown below.

- **High speed**  
Access to data(read and write) is very fast.
- **Multi-threadeding/multi-processing available**  
The client program can use this library in multi process, multithreading.
- **Binary data**  
Can use binary(any types of value) and variable length array(VLA) for Key and Value.
- **Automatic expansion of data area/low fragment**  
Dynamically extends the data area(for data and hash table).  
Use paging to minimize fragments.
- **Data storage/mapping type**  
Can store data on memory(volatile), persistent file(including temporary file).  
In the case of persistent files, it provides a mapping method for the whole file(data maintained at high speed and persisted) and index only(large capacity).
- **Nested key structure**  
In addition to KVS's ability to store values for keys, you can associate other keys as keys to subkeys.
- **Transaction Plugins**  
Can implement your own processing by triggering data update processing as a transaction trigger.
- **Archiving**  
Data update processing can be output as an archive file as embedded transaction processing.
- **Queue(FIFO/LIFO)**  
Queue(FIFO/LIFO) can be configured as data of [**K2HASH**](https://k2hash.antpick.ax/) and you can push/pop from it.
- **Attributes**  
Attributes(embedded or customized) can be set for the key.
- **Encryption**  
Can encrypt the key value and save it.
- **History**  
Can keep the update history of the key and this function can be used as a versioning for data.
- **Expiration**  
A function that can set the expiration date of the key as an attribute.

For details, please refer to {{ page.github_icon }}[**Codes on github**](https://github.com/yahoojapan/k2hash), {{ page.antpickax_icon }}[**Documents**](https://k2hash.antpick.ax/).

## {{ page.title_k2hash_nodejs }}
[**K2HASH nodejs addon**](https://nodejs.k2hash.antpick.ax/)（**K2HASH** nodejs addon - NoSQL Key Value Store(KVS) nodejs library) is a Node.js addon library of [**K2HASH**](https://k2hash.antpick.ax/).  
Using this library, you can operate [**K2HASH**](https://k2hash.antpick.ax/)'s data from your Node.js based JavaScript program.  
[**K2HASH nodejs addon**](https://nodejs.k2hash.antpick.ax/) provides all functions and features of [**K2HASH**](https://k2hash.antpick.ax/).  

For details, please refer to {{ page.github_icon }}[**Codes on github**](https://github.com/yahoojapan/k2hash_nodejs), {{ page.antpickax_icon }}[**Documents**](https://nodejs.k2hash.antpick.ax/).

## {{ page.title_k2hash_java }}
[**Java Driver for K2HASH**](https://java.k2hash.antpick.ax/index.html)（Java Driver for **K2HASH**) is an official Java client library for [**K2HASH**](https://k2hash.antpick.ax/index.html).  
This library provies all functions and features necessary for the slave side client of distributed KVS of [**K2HASH**](https://k2hash.antpick.ax/).  
That means eveyone is able to implement [**K2HASH**](https://k2hash.antpick.ax/)'s slave side client application by using this library.  

For details, see the {{ page.github_icon }}[**Code on GitHub**](https://github.com/yahoojapan/k2hash_java), {{ page.antpickax_icon }}[**Documents**](https://java.k2hash.antpick.ax/index.html).

## {{ page.title_k2hash_go }}
[**K2HASH golang**](https://pkg.go.dev/github.com/yahoojapan/k2hash_go/k2hash) (**K2HASH** golang - NoSQL Key Value Store(KVS) Go library) is [**K2HASH**](https://k2hash.antpick.ax/)'s Go language client library.  
You can use this library to implement [**K2HASH**](https://k2hash.antpick.ax/) slave-side client applications in Go language.  
[**K2HASH golang**](https://pkg.go.dev/github.com/yahoojapan/k2hash_go/k2hash) provides all the functions and features of [**K2HASH**](https://k2hash.antpick.ax/).  

For details, see the {{ page.github_icon }}[**Code on GitHub**](https://github.com/yahoojapan/k2hash_go), {{ page.antpickax_icon }}[**Documents**](https://pkg.go.dev/github.com/yahoojapan/k2hash_go/k2hash).

## {{ page.title_k2hash_phpext }}
[**K2HASH phpext**](https://php.k2hash.antpick.ax/)（**K2HASH** phpext - NoSQL Key Value Store(KVS) php extension library) is a php extension library of [**K2HASH**](https://k2hash.antpick.ax/).  
Using this library, you can operate [**K2HASH**](https://k2hash.antpick.ax/)'s data from your PHP application.  
[**K2HASH phpext**](https://php.k2hash.antpick.ax/) provides all functions and features of [**K2HASH**](https://k2hash.antpick.ax/).  

For details, please refer to {{ page.github_icon }}[**Codes on github**](https://github.com/yahoojapan/k2hash_phpext), {{ page.antpickax_icon }}[**Documents**](https://php.k2hash.antpick.ax/).

## {{ page.title_k2hash_python }}
[**K2HASH python**](https://k2hash-python.readthedocs.io/en/latest/)（**K2HASH** python - NoSQL Key Value Store(KVS) python library) is a python library of [**K2HASH**](https://k2hash.antpick.ax/).  
Using this library, you can operate [**K2HASH**](https://k2hash.antpick.ax/)'s data from your Python application.  
[**K2HASH python**](https://k2hash-python.readthedocs.io/en/latest/) provides all functions and features of [**K2HASH**](https://k2hash.antpick.ax/).  

For details, please refer to {{ page.github_icon }}[**Codes on github**](https://github.com/yahoojapan/k2hash_python), {{ page.antpickax_icon }}[**Documents**](https://k2hash-python.readthedocs.io/en/latest/).

## {{ page.title_k2htpdtor }}
[**K2HTP_DTOR**](https://k2htpdtor.antpick.ax/)(**k2h**ash **T**ransaction **P**lugin **D**istributed **T**ransaction **O**f **R** epeater) easily duplicates the [**K2HASH**](https://k2hash.antpick.ax/) data by transferring the transaction data of [**K2HASH**](https://k2hash.antpick.ax/) to another host using [**CHMPX**](https://chmpx.antpick.ax/).  

This library is a standard transaction plugin library compatible with the [**K2HASH**](https://k2hash.antpick.ax/) library provided by Yahoo! JAPAN.  
This provides a general tool for users to process their own transactions as transaction triggers.

For details, please refer to {{ page.github_icon }}[**Codes on github**](https://github.com/yahoojapan/k2htp_dtor), {{ page.antpickax_icon }}[**Documents**](https://k2htpdtor.antpick.ax/).

## {{ page.title_k2htpmdtor }}
[**K2HTP_MDTOR**](https://k2htpmdtor.antpick.ax/)(**k2h**ash **T**ransaction **P**lugin **M**ultiple **D**istributed **T**ransaction **O**f **R** epeater) easily duplicates the [**K2HASH**](https://k2hash.antpick.ax/) data by transferring the transaction data of [**K2HASH**](https://k2hash.antpick.ax/) to another host using [**CHMPX**](https://chmpx.antpick.ax/).  

The main purpose of **K2HTP_MDTOR**, which loads multiple [**K2HASH**](https://k2hash.antpick.ax/) transaction plugins, is to call the arbitrary function defined in them. When calling the each function, **K2HTP_MDTOR** passes [**K2HASH**](https://k2hash.antpick.ax/) transaction logs to it as a function's parameter. A common [**K2HASH**](https://k2hash.antpick.ax/) transaction plugin loads no other one. We recommend you to use **K2HTP_MDTOR** if you want to use multiple [**K2HASH**](https://k2hash.antpick.ax/) transaction plugins.

For details, please refer to {{ page.github_icon }}[**Codes on github**](https://github.com/yahoojapan/k2htp_mdtor), {{ page.antpickax_icon }}[**Documents**](https://k2htpmdtor.antpick.ax/).

## {{ page.title_fullock }}
[**FULLOCK**](https://fullock.antpick.ax/)(**F**ast **U**ser **L**evel **LOCK** library) is a low-level lock library that provides a safe and fast locking function for multiprocess, multithreaded programs.  
This library is also used by other AntPickax products such as [**K2HASH**](https://k2hash.antpick.ax/), [**CHMPX**](https://chmpx.antpick.ax/).

For details, please refer to {{ page.github_icon }}[**Codes on github**](https://github.com/yahoojapan/fullock), {{ page.antpickax_icon }}[**Documents**](https://fullock.antpick.ax/).
