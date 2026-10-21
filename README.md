### Hi, I'm Sebastian 👋

Head of Platform and Data Engineering at [Cardo AI](https://cardoai.com). I build data platforms on Kubernetes and AWS, mostly with Trino, Spark, Airflow, Kafka, Iceberg and Delta Lake. Before that I did a PhD and a postdoc in Information Engineering at the University of Padua, working on protein docking, HPC and clinical machine learning.

**What I work on**

- Trino at scale on EKS: spot workers, Karpenter node pools on local NVMe, KEDA autoscaling, query retries and spill to disk, Trino Gateway
- Lakehouses on S3 with Iceberg, Delta Lake and the AWS Glue Data Catalog, fed by Postgres CDC through Kafka and Debezium
- Multi-account AWS with Terraform, GitOps with ArgoCD, observability with the Grafana LGTM stack

**Open source**

I contribute upstream to the projects I run in production:

- [trinodb/charts](https://github.com/trinodb/charts/pulls?q=is%3Apr+author%3Asdaberdaku+is%3Amerged): 17 merged PRs, including KEDA worker autoscaling, graceful worker shutdown, NetworkPolicy, the JMX exporter, and PDBs, lifecycle hooks and rollout strategies for Trino Gateway. Nominated as a Trino Champion in 2024 for this work.
- [trinodb/trino](https://github.com/trinodb/trino/pulls?q=is%3Apr+author%3Asdaberdaku+is%3Amerged): Delta Lake connector fixes (transaction conflict retries, `_delta_log` caching) and a SQL routine compiler fix
- [apache/airflow](https://github.com/apache/airflow/pulls?q=is%3Apr+author%3Asdaberdaku): AWS STS region support for the HashiCorp Vault provider
**Projects**

| Project | What it does |
| --- | --- |
| [kafka2delta](https://github.com/sdaberdaku/kafka2delta) | Streams Kafka topics into Delta Lake tables. On [PyPI](https://pypi.org/project/kafka2delta/). |
| [nodereaper](https://github.com/sdaberdaku/nodereaper) | Removes empty and unhealthy Kubernetes nodes when autoscalers fail to scale down |
| [aws-glue-data-catalog-spark-client](https://github.com/sdaberdaku/aws-glue-data-catalog-spark-client) | Lets Apache Spark, including Spark 4, use the AWS Glue Data Catalog as its metastore |
| [spark-with-glue](https://github.com/sdaberdaku/spark-with-glue) | Apache Spark Docker image with Glue metastore support built in |
| [charts](https://github.com/sdaberdaku/charts) | Helm charts for Spark Connect, Spark History Server, Trino, Karpenter and Kyverno |
| [apache-airflow-providers-pysparkonk8s](https://github.com/sdaberdaku/apache-airflow-providers-pysparkonk8s) | Airflow provider that runs PySpark tasks on Kubernetes |
| [wkNNMI](https://cran.r-project.org/package=wkNNMI) | R package on CRAN for mutual-information-weighted k-NN imputation |
| [baggage-conveyor-assignment](https://github.com/sdaberdaku/baggage-conveyor-assignment) | Assigns arriving flights to airport baggage reclaim conveyors with a mixed-integer model (OR-Tools) |

**Talks and writing**

- Trino Summit 2024: *Optimizing Trino on Kubernetes* ([slides](https://sdaberdaku.github.io/optimizing-trino-on-k8s/))

Articles on [Medium](https://medium.com/@sebastiandaberdaku):

- [Taming noisy neighbours in a multi-tenant Trino cluster](https://medium.com/@sebastiandaberdaku/taming-noisy-neighbours-in-a-multi-tenant-trino-cluster-d34b98d42305)
- [Trino on Kubernetes, two years after my Trino Summit talk](https://medium.com/@sebastiandaberdaku/trino-on-kubernetes-two-years-after-my-trino-summit-talk-e8a41db8486e)
- [Running Trino workers on spot instances](https://medium.com/@sebastiandaberdaku/running-trino-workers-on-spot-instances-29ab409ed5ae)
- [Upgrading Trino on Kubernetes with blue/green clusters](https://medium.com/@sebastiandaberdaku/upgrading-trino-on-kubernetes-with-blue-green-clusters-62adf8e15ab1)
- [Blocking partial clears in Airflow 2 and 3](https://medium.com/@sebastiandaberdaku/blocking-partial-clears-in-airflow-2-and-3-e6b54111dd4f)
- [Free TLS for internal services on AWS](https://medium.com/@sebastiandaberdaku/free-tls-for-internal-services-on-aws-34550740ed15)
- [Enabling AWS Glue support in Apache Spark 4](https://medium.com/towards-data-engineering/enabling-aws-glue-support-in-apache-spark-4-2c1fca7a7149)
- [Centralized AWS CloudWatch log collection to S3](https://medium.com/towards-data-engineering/centralized-aws-cloudwatch-log-collection-to-s3-7f66a066b48b)
- [Exploring the Machine Learning capabilities of Trino](https://medium.com/towards-data-engineering/exploring-the-machine-learning-capabilities-of-trino-b35a43a2b1d6)
- [Testing Apache Airflow DAGs locally with Testcontainers and LocalStack](https://medium.com/towards-data-engineering/testing-apache-airflow-dags-locally-with-testcontainers-and-localstack-6bca9ff62d61)
- [Building a custom Apache Spark Docker image with AWS Glue Data Catalog support as metastore](https://medium.com/towards-data-engineering/building-a-custom-apache-spark-docker-image-with-aws-glue-data-catalog-support-as-metastore-95ef9a709794)
- [Performing Delta Table operations in PySpark with Spark Connect](https://medium.com/towards-data-engineering/performing-delta-table-operations-in-pyspark-with-spark-connect-3925b08d4766)

**Research**

400+ citations, h-index 10. Papers in *Bioinformatics*, *BMC Bioinformatics*, *Journal of Neurology*, *Machine Learning*, *BMC Medical Informatics and Decision Making*, *The Journal of Supercomputing* and *The International Journal of High Performance Computing Applications*, plus a European patent application on predicting ALS progression (grant intended). Code: [AntibodyInterfacePrediction](https://github.com/sdaberdaku/AntibodyInterfacePrediction), [PPIprediction](https://github.com/sdaberdaku/PPIprediction), [VoxMeshSurfOpenMP](https://github.com/sdaberdaku/VoxMeshSurfOpenMP), [PoCavEDT](https://github.com/sdaberdaku/PoCavEDT), [HSS-PPI](https://github.com/sdaberdaku/hss-ppi).

**Elsewhere:** [Resume](https://sdaberdaku.github.io/resume/) · [LinkedIn](https://www.linkedin.com/in/sebastian-daberdaku/) · [Medium](https://medium.com/@sebastiandaberdaku) · [Google Scholar](https://scholar.google.com/citations?user=XpyjCaUAAAAJ) · [ORCID](https://orcid.org/0000-0003-0544-1465)
