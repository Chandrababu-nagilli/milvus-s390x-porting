### WatsonX on X86 supports Milvus.
https://milvus.io
https://github.com/milvus-io/milvus

### Porting of Conan package manager:
https://github.com/conan-io/conan.git

### More details of conan here:
https://docs.conan.io/2/tutorial.html
### If you want to clone the recipes from here:
https://github.com/conan-io/conan-center-index/tree/master/recipes



# Milvus Architecture Overview
Built on top of popular vector search libraries including Faiss, HNSW, DiskANN, SCANN and more, Milvus was designed for similarity search on dense vector datasets containing millions, billions, or even trillions of vectors. Before proceeding, familiarize yourself with the [basic principles](https://milvus.io/docs/glossary.md) of embedding retrieval.

Milvus also supports data sharding, streaming data ingestion, dynamic schema, search combine vector and scalar data, multi-vetor and hybrid search, sparse vector and many other advanced functions. The platform offers performance on demand and can be optimized to suit any embedding retrieval scenario. We recommend deploying Milvus using Kubernetes for optimal availability and elasticity.

Milvus adopts a shared-storage architecture featuring storage and computing disaggregation and horizontal scalability for its computing nodes. Following the principle of data plane and control plane disaggregation, Milvus comprises [four layers](https://milvus.io/docs/four_layers.md): access layer, coordinator service, worker node, and storage. These layers are mutually independent when it comes to scaling or disaster recovery.

<img width="1329" alt="image" src="https://github.com/Chandrababu-nagilli/milvus-s390x-porting/assets/92324757/9c1cc550-8ad0-45d1-b8bd-e4c5e96a8776">


