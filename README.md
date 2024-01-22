# GPU DBMS list

## 1. Open-source (Free) GPU DBMS

### 1.1 Traditional Database Extension

| GPU DBMS              | Open Source | Last Active Time | Computational Backend | Derived From         | Developer      |
| :-------------------- | :---------- | :--------------- | :-------------------- | :------------------- | :------------- |
| **PG-Strom**<sup>\[1] | ☑️          | Within a month   | CUDA                  | PostgresSQL<sup>\[9] | HeteroDB, Inc. |

### 1.2 Full-GPU-executed DBMS&#x20;

| GPU DBMS                             | Open Source | Last Active Time      | Computational Backend | Developer  |
| :----------------------------------- | :---------- | :-------------------- | :-------------------- | :--------- |
| **HeavyDB**<sup>\[4]                 | ☑️          | Within a month        | LLVM to PTX           | Heavy.AI   |
| **Dask-sql**<sup>\[5]                | ☑️          | Within a month        | RAPIDS (cuDF)         | Dask, Inc. |
| BlazingSQL<sup>\[6]                  | ☑️          | 2 years ago           | Hadoop                | BlazingDB  |
| OmniSci<sup>\[7]</sup> (Former of HeavyDB) | ☑️          | 3 years ago           | LLVM to PTX           | Heavy.AI   |
| MapD<sup>\[8]</sup> (Former of HeavyDB)    | ☑️          | More than 3 years ago | CUDA                  | Heavy.AI   |

## 2. Commercial GPU DBMS

### 1.1 Traditional Database Extension

| GPU DBMS             | Open Source | Computational Backend | Derived From  | Developer |
| :------------------- | :---------- | :-------------------- | :------------ | :-------- |
| DB2 BLU<sup>\[2]\[3] | ✖️          | CUDA                  | DB2<sup>\[10] | IBM, Inc. |
| Brytlyt<sup>\[11]    | ✖️          | CUDA                  | PostgresSQL<sup>\[9]   | Brytlyt, Inc.    |

### 1.2 Full-GPU-executed DBMS&#x20;

| GPU DBMS                        | Open Source | Computational Backend | Developer           |
| :------------------------------ | :---------- | :-------------------- | :------------------ |
| Kinetica<sup>\[12]              | ✖️          | OpenCL                | Kinetica DB, Inc.   |
| SQream<sup>\[13]              | ✖️          | CUDA                  | SQream Technologies |
| GPUDB<sup>\[14]</sup>(Former of Kinetica) | ✖️          | OpenCL                | Kinetica DB, Inc.   |

## References

\[1] KaiGai Kohei. PG-Strom. <https://github.com/heterodb/pg-strom>, 2023.

\[2] Sina Meraji, Berni Schiefer, Lan Pham, Lee Chu, Peter Kokosielis, Adam Storm, Wayne Young, Chang Ge, Geoffrey Ng, and Kajan Kanagaratnam. Towards a hybrid design for fast query processing in db2 with blu acceleration using graphical processing units: A technology demonstration. In Proceedings of the 2016 International Conference on Management of Data, pages 1951–1960, 2016.

\[3] IBM. Towards Fast SQL Query Processing in DB2 BLU Using GPUs. <https://on-demand.gputechconf.com/gtc/2015/presentation/S5229-Sina-Meraji.pdf>, 2023.

\[4] HEAVY.AI. HeavyDB. <https://github.com/heavyai/heavydb>, 2023.

\[5] Dask. Dask-sql. <https://github.com/dask-contrib/dask-sql>, 2023.

\[6] BlazingSQL. BlazingSQL. <https://github.com/BlazingDB/blazingsql>, 2021.

\[7] OmniSci. Omnisci Technical White Paper: GPU-Accelerated Analytics Big Data Analytics at Speed and Scal. <https://www.omnisci.com/platform>, 2020.

\[8] Christopher Root and Todd Mostak. Mapd: A gpu-powered big data analytics and visualization platform. In *ACM SIGGRAPH 2016 Talks*, pages 1–2. 2016.

\[9] PostgreSQL. PostgreSQL: The World’s Most Advanced Open Source Relational Database. <https://www.postgresql.org/>, 2023.

\[10] IBM. IBM Db2 database. <https://www.ibm.com/products/db2/database>, 2023.

\[11] Brytlyt White Paper: Speed of Thought Analytics at Scale. <https://www.brytlyt.com/>, 2023.

\[12] Kinetica On-Premises Documentation. <https://docs.kinetica.com/>, 2023.

\[13] Sqream DB Architecture Whitepaper: A Next Generation Gpu Powered Analytics SQL Database. <https://sqream.com/>, 2023.

\[14] Yuan Y, Lee R, Zhang X. The yin and yang of processing data warehousing queries on GPU devices. VLDB Journal, 2013,6(10): 817−828.
