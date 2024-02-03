# GPU DBMS list

## 1. Research Prototype

### 1.1 OLTP

| GPU DBMS   | Open Source | Last Active Time | Computational Backend | Developer          |
| :--------- | :---------- | :--------------- | :-------------------- | :----------------- |
| GPUTx<sup>\[15] | ✖️          | -                | CUDA                  | Bingsheng He, etc. |

### 1.2 OLAP

| GPU DBMS                             | Open Source | Last Active Time      | Computational Backend | Developer            |
| :----------------------------------- | :---------- | :-------------------- | :-------------------- | :------------------- |
| MultiQX-GPU<sup>\[16]                     | ✖️          | -                     | CUDA                  | Kaibo Wang, etc.     |
| YDB(YSmart)<sup>\[17]                     | ✖️          | -                     | CUDA                  | Yuan Yuan, etc.      |
| CoGaDB<sup>\[18]                          | ✖️          | -                     | CUDA                  | Sebastian Breß, etc. |
| MapD<sup>\[8]</sup> (Former of HeavyDB)    | ☑️          | More than 3 years ago | CUDA                  | Heavy.AI             |
| Alenka<sup>\[19]                          | ☑️          | More than 3 years ago | CUDA                  | Furst E, etc.        |
| GDB(GPUQP)<sup>\[20]                      | ✖️          | -                     | CUDA                  | Rui Fang, etc.       |
| GalacticaDB<sup>\[21]                     | ☑️          | 3 years ago           | CUDA                  | Keh Kok Yong, etc.   |
| HippogriffDB<sup>\[22]                    | ✖️          | -                     | CUDA                  | Li J, etc.           |
| Ocelot<sup>\[23]                          | ✖️          | -                     | OpenCL                | Sebastian Breß, etc. |
| OmniDB<sup>\[24]                          | ☑️          | More than 3 years ago | OpenCL                | Zhang S, etc.        |
| Virginian<sup>\[25]                       | ☑️          | More than 3 years ago | OpenCL                | Angstadt K, etc.     |
| GPUDB<sup>\[14]</sup>(Former of Kinetica) | ☑️          | More than 3 years ago | OpenCL                | Kinetica DB, Inc.    |

## 2. Commercial GPU DBMS

### 2.1 Traditional Database Extension

| GPU DBMS              | Open Source | Free/Charge | Last Active Time | Computational Backend | Derived From    | Developer      |
| :-------------------- | :---------- | :---------- | :--------------- | :-------------------- | :-------------- | :------------- |
| **PG-Strom**<sup>\[1] | ☑️          | Free        | Within a month   | CUDA                  | PostgresSQL<sup>\[9] | HeteroDB, Inc. |
| Brytlyt<sup>\[11]     | ✖️          | Charge      | -                | CUDA                  | PostgresSQL<sup>\[9] | Brytlyt, Inc.  |
| DB2 BLU<sup>\[2]\[3]  | ✖️          | Charge      | -                | CUDA                  | DB2<sup>\[10]   | IBM, Inc.      |

### 2.2 Full-GPU-executed DBMS&#x20;

| GPU DBMS                             | Open Source | Free/Charge | Last Active Time | Computational Backend | Developer           |
| :----------------------------------- | :---------- | :---------- | :--------------- | :-------------------- | :------------------ |
| **HeavyDB**<sup>\[4]                 | ☑️          | Partly Free | Within a month   | LLVM to PTX           | Heavy.AI            |
| **Dask-sql**<sup>\[5]                | ☑️          | Free        | Within a month   | RAPIDS (cuDF)         | Dask, Inc.          |
| OmniSci<sup>\[7]</sup> (Former of HeavyDB) | ☑️          | Free        | 3 years ago      | LLVM to PTX           | Heavy.AI            |
| Kinetica<sup>\[12]                   | ✖️          | Charge      | -                | OpenCL                | Kinetica DB, Inc.   |
| SQream<sup>\[13]                     | ✖️          | Charge      | -                | CUDA                  | SQream Technologies |
| BlazingSQL<sup>\[6]                  | ☑️          | Free        | 3 years ago      | Hadoop                | BlazingDB           |

## References

\[1] KaiGai Kohei. PG-Strom. <https://github.com/heterodb/pg-strom>, 2023.

\[2] Sina Meraji, Berni Schiefer, Lan Pham, Lee Chu, Peter Kokosielis, Adam Storm, Wayne Young, Chang Ge, Ge- offrey Ng, and Kajan Kanagaratnam. Towards a hybrid design for fast query processing in db2 with blu accel- eration using graphical processing units: A technology demonstration. In Proceedings of the 2016 International Conference on Management of Data, pages 1951–1960, 2016.

\[3] IBM. Towards Fast SQL Query Processing in DB2 BLU Using GPUs. <https://on-demand.gputechconf.com/gtc/2015/presentation/S5229-Sina-Meraji.pdf>, 2023.

\[4] HEAVY.AI. HeavyDB. <https://github.com/heavyai/heavydb>, 2023.

\[5] Dask. Dask-sql. <https://github.com/dask-contrib/dask-sql>, 2023.

\[6] BlazingSQL. BlazingSQL. <https://github.com/BlazingDB/blazingsql>, 2021.

\[7] OmniSci. Omnisci Technical White Paper: GPU- Accelerated Analytics-Big Data Analytics at Speed and Scal. <https://www.omnisci.com/platform>, 2020.

\[8] Christopher Root and Todd Mostak. Mapd: A gpu-powered big data analytics and visualization platform. In *ACM SIGGRAPH 2016 Talks*, pages 1–2. 2016.

\[9] PostgreSQL. PostgreSQL: The World’s Most Advanced Open Source Relational Database. [www.postgresql.org/](http://www.postgresql.org/), 2023.

\[10] IBM. IBM Db2 database. <https://www.ibm.com/products/db2/database>, 2023.

\[11] Brytlyt White Paper: Speed of Thought Analytics at Scale. <https://www.brytlyt.com/>, 2023.

\[12] Kinetica On-Premises Documentation. <https://docs.kinetica.com/>, 2023.

\[13] Sqream DB Architecture Whitepaper: A Next Gener- ation Gpu Powered Analytics SQL Database. https://sqream.com/, 2023.

\[14] Yuan Y, Lee R, Zhang X. The yin and yang of processing data warehousing queries on GPU devices. VLDB Journal, 2013,6(10): 817−828.

\[15] He B, Yu JX. High-Throughput transaction executions on graphics processors. Proc. of the VLDB Endowment, 2011,4(5):314−325.

\[16] Wang K, Zhang K, Yuan Y, Ma S, Lee R, Ding X, Zhang X. Concurrent analytical query processing with GPUs. Proc. of the VLDB Endowment, 2014,7(11):1011−1022.&#x20;

\[17] Yuan Y, Lee R, Zhang X. The yin and yang of processing data warehousing queries on GPU devices. VLDB Journal, 2013,6(10): 817−828.&#x20;

\[18] Breß S. The design and implementation of cogadb: A column-oriented GPU-accelerated DBMS. Datenbank-Spektrum, 2014,14(3): 199−209.

\[19] Furst E, Oskin M, Howe B. Profiling a GPU database implementation: A holistic view of GPU resource utilization on tpc-h queries. In: Proc. of the Int'l Workshop on Data Management on New Hardware. Chicago: ACM, 2017. 1−6.

\[20] Fang R, He B, Lu M, Yang K, Govindaraju NK, Luo Q, Sander PV. GPUQP: Query co-processing using graphics processors. In: Proc. of the 2007 ACM SIGMOD Int'l Conf. on Management of data. Beijing: ACM, 2007. 1061−1063.

\[21] Yong KK, Ho WK, Chua MW, See S. A GPU query accelerator for geospatial coordinates computation. In: Proc. of the 2015 Int'l Conf. on Cloud Computing Research and Innovation (ICCCRI). IEEE Computer Society, 2015. 166−172.

\[22] Li J, Tseng HW, Lin C, Papakonstantinou Y, Swanson S. Hippogriffdb: Balancing I/O and GPU bandwidth in big data analytics. VLDB, 2016,9(14):1647−1658.

\[23] Breß S, Kocher B, Heimel M, Markl V, Saecker M, Saake G. Ocelot/hype: Optimized data processing on heterogeneous hardware. Proc. of the VLDB Endowment, 2014,7(13):1609−1612.

\[24] Zhang S, He J, He B, Lu M. Omnidb: Towards portable and efficient query processing on parallel CPU/GPU architectures. Proc. of the VLDB Endowment, 2013,6(12):1374−1377.&#x20;

\[25] Angstadt K, Harcourt E. A virtual machine model for accelerating relational database joins using a general purpose GPU. In: Proc. of the Symp. on High PERFORMANCE Computing. 127−134.&#x20;

