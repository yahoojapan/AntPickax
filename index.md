---
layout: default
language: en-us
title: AntPickax
product_name: AntPickax
short_desc: AntPickax provides basic libraries, components and systems
lang_opp_file: indexja.html
lang_opp_word: To Japanese
title_k2hdkc: <a class="to_git_banner" href="https://github.com/yahoojapan/k2hdkc">k2hdkc</a>
title_k2hftfuse: <a class="to_git_banner" href="https://github.com/yahoojapan/k2hftfuse">k2hftfuse</a>
title_k2hash: <a class="to_git_banner" href="https://github.com/yahoojapan/k2hash">k2hash</a>
title_chmpx: <a class="to_git_banner" href="https://github.com/yahoojapan/chmpx">chmpx</a>
title_k2htpdtor: <a class="to_git_banner" href="https://github.com/yahoojapan/k2htp_dtor">k2htp_dtor</a>
title_fullock: <a class="to_git_banner" href="https://github.com/yahoojapan/fullock">fullock</a>
---

# **AntPickax**
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
`AntPickax` includes the following products.

- [`k2hdkc`](https://github.com/yahoojapan/k2hdkc/wiki)    
High performance and horizontal scalable distributed KVS cluster system based on [`k2hash`](https://github.com/yahoojapan/k2hash/wiki) and [`chmpx`](https://github.com/yahoojapan/chmpx/wiki).
- [`k2hftfuse`](https://github.com/yahoojapan/k2hftfuse/wiki)  
A component based on FUSE library which can transfer files, texts and logs at high speed and relay them and aggregate them.
- [`k2hash`](https://github.com/yahoojapan/k2hash/wiki)    
A vey fast Key Value Store(KVS) library featuring very large file support and many useful functions.
- [`chmpx`](https://github.com/yahoojapan/chmpx/wiki)  
A very fast network communication middleware to construct a cluster.
- [`k2htpdtor`](https://github.com/yahoojapan/k2htp_dtor/wiki)  
A standard plug-in library for processing transaction data linked to the [`k2hash`](https://github.com/yahoojapan/k2hash/wiki) library.
- [`fullock`](https://github.com/yahoojapan/fullock/wiki)  
A very fast and powerful lock library for multithread and multiprocess used in [`k2hash`](https://github.com/yahoojapan/k2hash/wiki), [`chmpx`](https://github.com/yahoojapan/chmpx/wiki).

# **AntPickax Products**

## {{ page.title_k2hdkc }}
k2hdkc(**k2h**ash based **D**istributed **K**vs **C**luster) is a high performance and horizontal scalable distributed KVS cluster system based on **[`k2hash`](https://github.com/yahoojapan/k2hash/wiki)**, **[`chmpx`](https://github.com/yahoojapan/chmpx/wiki)** Distributed Key Value Store(KVS).  

The k2hdkc has unique features shown below.
- **Consistency** (Automatic Data Synchronization between Server Nodes)  
Provides automatic merging function of data due to failure/recovery of server nodes in the cluster.
- **Automatic Scaling**  
Server nodes can be added/deleted to the cluster, and the data automatic merging function at this time is also provided.
- **Nested key structure**  
Provides the association function of key and subkey which is the feature of [`k2hash`](https://github.com/yahoojapan/k2hash/wiki) as distributed KVS.
- **Queue(FIFO/LIFO)**  
Provides the queuing function which is the feature of [`k2hash`](https://github.com/yahoojapan/k2hash/wiki) as distributed KVS.
- **Transaction Plugins**  
Provides a function that can perform arbitrary processing using data update processing which is the feature of [`k2hash`](https://github.com/yahoojapan/k2hash/wiki) as a trigger of transaction.
- **Encryption**  
Provides encryption function as distributed KVS for the key's data held as the feature of [`k2hash`](https://github.com/yahoojapan/k2hash/wiki).
- **Expiration**  
Provides the key expiration function which is the feature of [`k2hash`](https://github.com/yahoojapan/k2hash/wiki) as distributed KVS.

For details, please refer to [Codes on github](https://github.com/yahoojapan/k2hdkc), [Documents](https://github.com/yahoojapan/k2hdkc/wiki).

## {{ page.title_k2hftfuse }}
[`k2hftfuse`](https://github.com/yahoojapan/k2hftfuse/wiki)(**k2h**ash **F**ile **T**ransaction by **FUSE** based file system) is [FUSE (Filesystem in Userspace)](https://github.com/libfuse/libfuse) is a file/message transfer system using the user space mounting function.  

[`k2hftfuse`](https://github.com/yahoojapan/k2hftfuse/wiki) is a system developed to realize **reliable** and **fast** file/message transfer at low cost.  
[`k2hftfuse`](https://github.com/yahoojapan/k2hftfuse/wiki) provides a virtual file system, you can use it by writing the file to the mounted directory.  
Just by mounting the directory of the output file of the existing program with [`k2hftfuse`](https://github.com/yahoojapan/k2hftfuse/wiki), you can transfer files/messages **without changing** the existing program.

- **Zero cost integration with applications**  
Additional API dependency for client applications is zero!
- **Very fast and reliable file transfer**  
Very fast and reliable file transfer based on [`k2hash`](https://github.com/yahoojapan/k2hash/wiki) and [`chmpx`](https://github.com/yahoojapan/chmpx/wiki).
- **Various data format**  
Supported data formats are a single data message, a text file and a binary file.
- **Filter**  
Processing data for your purpose very easily!
- **Trigger**
Invoking your own function against particular data.

For details, please refer to [Codes on github](https://github.com/yahoojapan/k2hftfuse), [Documents](https://github.com/yahoojapan/k2hftfuse/wiki).

## {{ page.title_k2hash }}
[`k2hash`](https://github.com/yahoojapan/k2hash/wiki) is the NoSQL Key Value Store(KVS) library.
[`k2hash`](https://github.com/yahoojapan/k2hash/wiki) has basic KVS functions and unique features shown below.

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
Queue(FIFO/LIFO) can be configured as data of [`k2hash`](https://github.com/yahoojapan/k2hash/wiki) and you can push/pop from it.
- **Attributes**  
Attributes(embedded or customized) can be set for the key.
- **Encryption**  
Can encrypt the key value and save it.
- **History**  
Can keep the update history of the key and this function can be used as a versioning for data.
- **Expiration**  
A function that can set the expiration date of the key as an attribute.

For details, please refer to [Codes on github](https://github.com/yahoojapan/k2hash), [Documents](https://github.com/yahoojapan/k2hash/wiki).

## {{ page.title_chmpx }}
[`chmpx`](https://github.com/yahoojapan/chmpx/wiki) (**C**onsistent **H**ashing **M**q in**P**rocess data e**X**change) is a communication middleware for sending and receiving binary data between processes that cross network.

- **Basic functions**  
[`chmpx`](https://github.com/yahoojapan/chmpx/wiki) is responsible for communication between the server program and the client program, and hides the network communication connection from each program.
- **Cluster/Multiplexing/Auto scaling**  
[`chmpx`](https://github.com/yahoojapan/chmpx/wiki) is a communication middleware that can create a cluster configuration, has high fault tolerance and multiplexing, and can be autoscaled.
- **Communication data**  
The format of the data to communicate is free, and it can communicate binary data and large size data.
- **Communication encryption**  
Supports communication with SSL.
- **Communication multiplexing/Parallel processing**  
Can multiplex and parallel communication between [`chmpx`](https://github.com/yahoojapan/chmpx/wiki) server and slave.
- **Queuing communication data**  
Data to be transmitted/received is queued and data will not be lost even with small delay due to high load etc.
- **Multi-threading/Multi-processing**  
The client program can use this component in multi process, multithreading.

For details, please refer to [Codes on github](https://github.com/yahoojapan/chmpx), [Documents](https://github.com/yahoojapan/chmpx/wiki).

## {{ page.title_k2htpdtor }}
[`k2htp_dtor`](https://github.com/yahoojapan/k2htp_dtor/wiki)(**k2h**ash **T**ransaction **P**lugin **D**istributed **T**ransaction **O**f **R** epeater) easily duplicates the [`k2hash`](https://github.com/yahoojapan/k2hash/wiki) data by transferring the transaction data of **[`k2hash`](https://github.com/yahoojapan/k2hash/wiki)** to another host using **[`chmpx`](https://github.com/yahoojapan/chmpx/wiki)**.  

This library is a standard transaction plugin library compatible with the [`k2hash`](https://github.com/yahoojapan/k2hash/wiki) library provided by Yahoo! JAPAN.  
This provides a general tool for users to process their own transactions as transaction triggers.

- **Multiple plugins**
[`k2htpdtor`](https://github.com/yahoojapan/k2htp_dtor/wiki) is a base component of data processing pipeline. A [`k2htpdtor`](https://github.com/yahoojapan/k2htp_dtor/wiki) plugin can invoke another plugin. As a result of processing by a certain plugin, the generated data can be processed by another plugin.

For details, please refer to [Codes on github](https://github.com/yahoojapan/k2htp_dtor), [Documents](https://github.com/yahoojapan/k2htp_dtor/wiki).

## {{ page.title_fullock }}
[`fullock`](https://github.com/yahoojapan/fullock/wiki)(**F**ast **U**ser **L**evel **LOCK** library) is a low-level lock library that provides a safe and fast locking function for multiprocess, multithreaded programs.  
This library is also used by other AntPickax products such as **[`k2hash`](https://github.com/yahoojapan/k2hash/wiki)**, **[`chmpx`](https://github.com/yahoojapan/chmpx/wiki)**.

For details, please refer to [Codes on github](https://github.com/yahoojapan/fullock), [Documents](https://github.com/yahoojapan/fullock/wiki).
