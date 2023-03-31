# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.589 ops/ms
# Warmup Iteration   2: 8.637 ops/ms
# Warmup Iteration   3: 10.103 ops/ms
Iteration   1: 10.501 ops/ms
Iteration   2: 10.949 ops/ms
Iteration   3: 10.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.741 ±(99.9%) 4.121 ops/ms [Average]
  (min, avg, max) = (10.501, 10.741, 10.949), stdev = 0.226
  CI (99.9%): [6.620, 14.862] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.716 ops/ms
# Warmup Iteration   2: 11.136 ops/ms
# Warmup Iteration   3: 11.859 ops/ms
Iteration   1: 11.159 ops/ms
Iteration   2: 11.397 ops/ms
Iteration   3: 11.506 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.354 ±(99.9%) 3.236 ops/ms [Average]
  (min, avg, max) = (11.159, 11.354, 11.506), stdev = 0.177
  CI (99.9%): [8.118, 14.590] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.204 ops/ms
# Warmup Iteration   2: 10.121 ops/ms
# Warmup Iteration   3: 10.522 ops/ms
Iteration   1: 10.299 ops/ms
Iteration   2: 10.352 ops/ms
Iteration   3: 10.503 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.385 ±(99.9%) 1.936 ops/ms [Average]
  (min, avg, max) = (10.299, 10.385, 10.503), stdev = 0.106
  CI (99.9%): [8.449, 12.321] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.885 ops/ms
# Warmup Iteration   2: 7.552 ops/ms
# Warmup Iteration   3: 7.951 ops/ms
Iteration   1: 7.970 ops/ms
Iteration   2: 7.933 ops/ms
Iteration   3: 8.066 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.990 ±(99.9%) 1.257 ops/ms [Average]
  (min, avg, max) = (7.933, 7.990, 8.066), stdev = 0.069
  CI (99.9%): [6.732, 9.247] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.434 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.003 ms/op
Iteration   1: 3.055 ±(99.9%) 0.010 ms/op
Iteration   2: 3.022 ±(99.9%) 0.002 ms/op
Iteration   3: 3.009 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.029 ±(99.9%) 0.432 ms/op [Average]
  (min, avg, max) = (3.009, 3.029, 3.055), stdev = 0.024
  CI (99.9%): [2.597, 3.460] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.980 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.879 ±(99.9%) 0.002 ms/op
Iteration   1: 2.928 ±(99.9%) 0.004 ms/op
Iteration   2: 2.872 ±(99.9%) 0.001 ms/op
Iteration   3: 2.904 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.901 ±(99.9%) 0.512 ms/op [Average]
  (min, avg, max) = (2.872, 2.901, 2.928), stdev = 0.028
  CI (99.9%): [2.389, 3.414] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.482 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.004 ms/op
Iteration   1: 3.037 ±(99.9%) 0.002 ms/op
Iteration   2: 2.970 ±(99.9%) 0.003 ms/op
Iteration   3: 3.007 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.005 ±(99.9%) 0.611 ms/op [Average]
  (min, avg, max) = (2.970, 3.005, 3.037), stdev = 0.034
  CI (99.9%): [2.393, 3.616] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.403 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.132 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.025 ±(99.9%) 0.012 ms/op
Iteration   1: 3.989 ±(99.9%) 0.017 ms/op
Iteration   2: 3.976 ±(99.9%) 0.023 ms/op
Iteration   3: 3.868 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.944 ±(99.9%) 1.214 ms/op [Average]
  (min, avg, max) = (3.868, 3.944, 3.989), stdev = 0.067
  CI (99.9%): [2.730, 5.159] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.175 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.009 ms/op
Iteration   1: 3.009 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.590 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.697 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  7.362 ms/op
                 createUser·p0.9999: 21.409 ms/op
                 createUser·p1.00:   21.889 ms/op

Iteration   2: 2.985 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.813 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  7.044 ms/op
                 createUser·p0.9999: 22.423 ms/op
                 createUser·p1.00:   22.643 ms/op

Iteration   3: 3.040 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.880 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   4.153 ms/op
                 createUser·p0.999:  9.978 ms/op
                 createUser·p0.9999: 27.623 ms/op
                 createUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318823
  mean =      3.011 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26508 
    [ 2.500,  5.000) = 290791 
    [ 5.000,  7.500) = 1131 
    [ 7.500, 10.000) = 163 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      8.817 ms/op
     p(99.9900) =     27.140 ms/op
     p(99.9990) =     27.861 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.009 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.987 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.890 ±(99.9%) 0.005 ms/op
Iteration   1: 2.880 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.600 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   4.047 ms/op
                 existUser·p0.999:  6.595 ms/op
                 existUser·p0.9999: 11.664 ms/op
                 existUser·p1.00:   11.862 ms/op

Iteration   2: 2.886 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.713 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   3.990 ms/op
                 existUser·p0.999:  6.431 ms/op
                 existUser·p0.9999: 13.645 ms/op
                 existUser·p1.00:   14.189 ms/op

Iteration   3: 2.857 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.678 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   3.953 ms/op
                 existUser·p0.999:  6.137 ms/op
                 existUser·p0.9999: 16.867 ms/op
                 existUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333917
  mean =      2.874 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2076 
    [ 1.250,  2.500) = 43679 
    [ 2.500,  3.750) = 281040 
    [ 3.750,  5.000) = 6214 
    [ 5.000,  6.250) = 535 
    [ 6.250,  7.500) = 179 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.600 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.502 ms/op
     p(99.0000) =      3.998 ms/op
     p(99.9000) =      6.374 ms/op
     p(99.9900) =     15.484 ms/op
     p(99.9990) =     17.891 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.055 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.008 ms/op
Iteration   1: 3.019 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.705 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  6.989 ms/op
                 getUser·p0.9999: 19.268 ms/op
                 getUser·p1.00:   20.185 ms/op

Iteration   2: 3.035 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.514 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  7.148 ms/op
                 getUser·p0.9999: 25.559 ms/op
                 getUser·p1.00:   27.329 ms/op

Iteration   3: 2.990 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.590 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  6.858 ms/op
                 getUser·p0.9999: 23.298 ms/op
                 getUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318237
  mean =      3.015 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23745 
    [ 2.500,  5.000) = 293032 
    [ 5.000,  7.500) = 1206 
    [ 7.500, 10.000) = 62 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.514 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      6.986 ms/op
     p(99.9900) =     24.670 ms/op
     p(99.9990) =     26.804 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.802 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.214 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.945 ±(99.9%) 0.010 ms/op
Iteration   1: 3.926 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.458 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  12.737 ms/op
                 listUser·p0.9999: 14.759 ms/op
                 listUser·p1.00:   15.745 ms/op

Iteration   2: 3.923 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.214 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.966 ms/op
                 listUser·p0.999:  17.859 ms/op
                 listUser·p0.9999: 23.490 ms/op
                 listUser·p1.00:   24.314 ms/op

Iteration   3: 3.989 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.124 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  18.472 ms/op
                 listUser·p0.9999: 25.722 ms/op
                 listUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243475
  mean =      3.946 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3155 
    [ 2.500,  5.000) = 217088 
    [ 5.000,  7.500) = 22094 
    [ 7.500, 10.000) = 735 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 167 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.546 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     14.402 ms/op
     p(99.9900) =     25.154 ms/op
     p(99.9990) =     26.233 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.741 ± 4.121  ops/ms
ClientGrpc.existUser                       thrpt       3  11.354 ± 3.236  ops/ms
ClientGrpc.getUser                         thrpt       3  10.385 ± 1.936  ops/ms
ClientGrpc.listUser                        thrpt       3   7.990 ± 1.257  ops/ms
ClientGrpc.createUser                       avgt       3   3.029 ± 0.432   ms/op
ClientGrpc.existUser                        avgt       3   2.901 ± 0.512   ms/op
ClientGrpc.getUser                          avgt       3   3.005 ± 0.611   ms/op
ClientGrpc.listUser                         avgt       3   3.944 ± 1.214   ms/op
ClientGrpc.createUser                     sample  318823   3.011 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.590           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.986           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.502           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.678           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.817           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.140           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.443           ms/op
ClientGrpc.existUser                      sample  333917   2.874 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.600           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.338           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.502           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           3.998           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.374           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.484           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.924           ms/op
ClientGrpc.getUser                        sample  318237   3.015 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.514           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.535           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.986           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.670           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.329           ms/op
ClientGrpc.listUser                       sample  243475   3.946 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.124           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.793           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.956           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.546           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.889           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.402           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.154           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.313           ms/op
