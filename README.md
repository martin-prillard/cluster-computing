# cluster-computing
My own script of distributed and parallel computing, Python (Scholar project, 2015)

#### My python script's steps :
1. the master retrieves computers's ip available on the network
2. the master splits input file into chunks
3. each worker (computer's core) processes his chunk
4. the master merges worker's result files

Do not require a Distributed File System (DFS) and divide the computing time by more than 100.

In my case, applied on my school's network (Telecom ParisTech).

If you are interested, please see https://github.com/martin-prillard/shavadoop (my own implementation of Hadoop MapReduce).
