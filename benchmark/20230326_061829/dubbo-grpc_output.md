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
# Warmup Iteration   1: 4.604 ops/ms
# Warmup Iteration   2: 9.394 ops/ms
# Warmup Iteration   3: 10.350 ops/ms
Iteration   1: 10.423 ops/ms
Iteration   2: 10.743 ops/ms
Iteration   3: 10.682 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.616 ±(99.9%) 3.102 ops/ms [Average]
  (min, avg, max) = (10.423, 10.616, 10.743), stdev = 0.170
  CI (99.9%): [7.514, 13.718] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.354 ops/ms
# Warmup Iteration   2: 10.802 ops/ms
# Warmup Iteration   3: 11.208 ops/ms
Iteration   1: 11.172 ops/ms
Iteration   2: 11.144 ops/ms
Iteration   3: 11.725 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.347 ±(99.9%) 5.977 ops/ms [Average]
  (min, avg, max) = (11.144, 11.347, 11.725), stdev = 0.328
  CI (99.9%): [5.370, 17.324] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.425 ops/ms
# Warmup Iteration   2: 10.597 ops/ms
# Warmup Iteration   3: 10.788 ops/ms
Iteration   1: 10.911 ops/ms
Iteration   2: 10.929 ops/ms
Iteration   3: 10.897 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.912 ±(99.9%) 0.294 ops/ms [Average]
  (min, avg, max) = (10.897, 10.912, 10.929), stdev = 0.016
  CI (99.9%): [10.618, 11.206] (assumes normal distribution)


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
# Warmup Iteration   1: 6.507 ops/ms
# Warmup Iteration   2: 7.941 ops/ms
# Warmup Iteration   3: 8.186 ops/ms
Iteration   1: 8.282 ops/ms
Iteration   2: 8.297 ops/ms
Iteration   3: 8.294 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.291 ±(99.9%) 0.148 ops/ms [Average]
  (min, avg, max) = (8.282, 8.291, 8.297), stdev = 0.008
  CI (99.9%): [8.143, 8.439] (assumes normal distribution)


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
# Warmup Iteration   1: 4.183 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.959 ±(99.9%) 0.004 ms/op
Iteration   1: 2.953 ±(99.9%) 0.004 ms/op
Iteration   2: 2.983 ±(99.9%) 0.002 ms/op
Iteration   3: 2.967 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.968 ±(99.9%) 0.276 ms/op [Average]
  (min, avg, max) = (2.953, 2.968, 2.983), stdev = 0.015
  CI (99.9%): [2.692, 3.243] (assumes normal distribution)


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
# Warmup Iteration   1: 3.559 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.933 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.846 ±(99.9%) 0.002 ms/op
Iteration   1: 2.816 ±(99.9%) 0.005 ms/op
Iteration   2: 2.842 ±(99.9%) 0.003 ms/op
Iteration   3: 2.843 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.834 ±(99.9%) 0.275 ms/op [Average]
  (min, avg, max) = (2.816, 2.834, 2.843), stdev = 0.015
  CI (99.9%): [2.559, 3.109] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.981 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.003 ms/op
Iteration   1: 2.973 ±(99.9%) 0.002 ms/op
Iteration   2: 2.926 ±(99.9%) 0.003 ms/op
Iteration   3: 2.983 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.961 ±(99.9%) 0.552 ms/op [Average]
  (min, avg, max) = (2.926, 2.961, 2.983), stdev = 0.030
  CI (99.9%): [2.409, 3.512] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.229 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.908 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.917 ±(99.9%) 0.015 ms/op
Iteration   1: 3.844 ±(99.9%) 0.012 ms/op
Iteration   2: 3.932 ±(99.9%) 0.015 ms/op
Iteration   3: 3.914 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.897 ±(99.9%) 0.844 ms/op [Average]
  (min, avg, max) = (3.844, 3.897, 3.932), stdev = 0.046
  CI (99.9%): [3.053, 4.741] (assumes normal distribution)


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
# Warmup Iteration   1: 4.032 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.178 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.007 ms/op
Iteration   1: 2.987 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.745 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  8.320 ms/op
                 createUser·p0.9999: 17.770 ms/op
                 createUser·p1.00:   18.121 ms/op

Iteration   2: 3.041 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.744 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  8.996 ms/op
                 createUser·p0.9999: 12.501 ms/op
                 createUser·p1.00:   21.758 ms/op

Iteration   3: 3.069 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.855 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  7.885 ms/op
                 createUser·p0.9999: 14.132 ms/op
                 createUser·p1.00:   14.664 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316289
  mean =      3.032 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27227 
    [ 2.500,  5.000) = 287745 
    [ 5.000,  7.500) = 838 
    [ 7.500, 10.000) = 276 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      8.412 ms/op
     p(99.9900) =     16.986 ms/op
     p(99.9990) =     18.077 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


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
# Warmup Iteration   1: 3.690 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.907 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.849 ±(99.9%) 0.006 ms/op
Iteration   1: 2.890 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.547 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  5.788 ms/op
                 existUser·p0.9999: 11.876 ms/op
                 existUser·p1.00:   12.878 ms/op

Iteration   2: 2.814 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.658 ms/op
                 existUser·p0.50:   2.802 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  5.983 ms/op
                 existUser·p0.9999: 12.522 ms/op
                 existUser·p1.00:   12.943 ms/op

Iteration   3: 2.852 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.486 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  7.322 ms/op
                 existUser·p0.9999: 14.755 ms/op
                 existUser·p1.00:   15.237 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336668
  mean =      2.852 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2772 
    [ 1.250,  2.500) = 53607 
    [ 2.500,  3.750) = 269812 
    [ 3.750,  5.000) = 9477 
    [ 5.000,  6.250) = 654 
    [ 6.250,  7.500) = 150 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.486 ms/op
     p(50.0000) =      2.834 ms/op
     p(90.0000) =      3.363 ms/op
     p(95.0000) =      3.572 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      6.283 ms/op
     p(99.9900) =     13.309 ms/op
     p(99.9990) =     15.121 ms/op
     p(99.9999) =     15.237 ms/op
    p(100.0000) =     15.237 ms/op


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
# Warmup Iteration   1: 3.878 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.067 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.876 ±(99.9%) 0.006 ms/op
Iteration   1: 2.985 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.596 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  9.552 ms/op
                 getUser·p0.9999: 18.547 ms/op
                 getUser·p1.00:   18.809 ms/op

Iteration   2: 2.947 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.823 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.293 ms/op
                 getUser·p0.95:   3.396 ms/op
                 getUser·p0.99:   3.944 ms/op
                 getUser·p0.999:  8.689 ms/op
                 getUser·p0.9999: 12.552 ms/op
                 getUser·p1.00:   12.796 ms/op

Iteration   3: 2.905 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.720 ms/op
                 getUser·p0.50:   2.925 ms/op
                 getUser·p0.90:   3.269 ms/op
                 getUser·p0.95:   3.416 ms/op
                 getUser·p0.99:   4.182 ms/op
                 getUser·p0.999:  7.364 ms/op
                 getUser·p0.9999: 16.876 ms/op
                 getUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 326005
  mean =      2.945 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1732 
    [ 1.250,  2.500) = 19933 
    [ 2.500,  3.750) = 295192 
    [ 3.750,  5.000) = 8123 
    [ 5.000,  6.250) = 357 
    [ 6.250,  7.500) = 204 
    [ 7.500,  8.750) = 117 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.596 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.543 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      9.027 ms/op
     p(99.9900) =     17.478 ms/op
     p(99.9990) =     18.743 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


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
# Warmup Iteration   1: 4.023 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.033 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.768 ±(99.9%) 0.011 ms/op
Iteration   1: 3.827 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.149 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  11.567 ms/op
                 listUser·p0.9999: 14.311 ms/op
                 listUser·p1.00:   16.482 ms/op

Iteration   2: 3.817 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.736 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.439 ms/op
                 listUser·p0.999:  14.680 ms/op
                 listUser·p0.9999: 16.475 ms/op
                 listUser·p1.00:   18.022 ms/op

Iteration   3: 3.850 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.839 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  15.440 ms/op
                 listUser·p0.9999: 22.698 ms/op
                 listUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250578
  mean =      3.831 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4215 
    [ 2.500,  5.000) = 227647 
    [ 5.000,  7.500) = 17780 
    [ 7.500, 10.000) = 518 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     13.905 ms/op
     p(99.9900) =     21.230 ms/op
     p(99.9990) =     23.314 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.616 ± 3.102  ops/ms
ClientGrpc.existUser                       thrpt       3  11.347 ± 5.977  ops/ms
ClientGrpc.getUser                         thrpt       3  10.912 ± 0.294  ops/ms
ClientGrpc.listUser                        thrpt       3   8.291 ± 0.148  ops/ms
ClientGrpc.createUser                       avgt       3   2.968 ± 0.276   ms/op
ClientGrpc.existUser                        avgt       3   2.834 ± 0.275   ms/op
ClientGrpc.getUser                          avgt       3   2.961 ± 0.552   ms/op
ClientGrpc.listUser                         avgt       3   3.897 ± 0.844   ms/op
ClientGrpc.createUser                     sample  316289   3.032 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.744           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.625           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.830           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.473           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.412           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.986           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.758           ms/op
ClientGrpc.existUser                      sample  336668   2.852 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.486           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.834           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.363           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.283           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.309           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.237           ms/op
ClientGrpc.getUser                        sample  326005   2.945 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.596           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.941           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.330           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.543           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.194           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.027           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.478           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.809           ms/op
ClientGrpc.listUser                       sample  250578   3.831 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.736           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.695           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.743           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.423           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.603           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.905           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.230           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.019           ms/op
