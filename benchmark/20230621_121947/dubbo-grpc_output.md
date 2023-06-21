# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.648 ops/ms
# Warmup Iteration   2: 9.347 ops/ms
# Warmup Iteration   3: 10.202 ops/ms
Iteration   1: 10.631 ops/ms
Iteration   2: 10.603 ops/ms
Iteration   3: 10.527 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.587 ±(99.9%) 0.980 ops/ms [Average]
  (min, avg, max) = (10.527, 10.587, 10.631), stdev = 0.054
  CI (99.9%): [9.608, 11.567] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.774 ops/ms
# Warmup Iteration   2: 10.581 ops/ms
# Warmup Iteration   3: 11.121 ops/ms
Iteration   1: 11.165 ops/ms
Iteration   2: 11.138 ops/ms
Iteration   3: 11.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.125 ±(99.9%) 0.892 ops/ms [Average]
  (min, avg, max) = (11.070, 11.125, 11.165), stdev = 0.049
  CI (99.9%): [10.233, 12.016] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.346 ops/ms
# Warmup Iteration   2: 10.321 ops/ms
# Warmup Iteration   3: 10.682 ops/ms
Iteration   1: 10.577 ops/ms
Iteration   2: 10.623 ops/ms
Iteration   3: 10.397 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.533 ±(99.9%) 2.177 ops/ms [Average]
  (min, avg, max) = (10.397, 10.533, 10.623), stdev = 0.119
  CI (99.9%): [8.356, 12.709] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.636 ops/ms
# Warmup Iteration   2: 7.673 ops/ms
# Warmup Iteration   3: 7.966 ops/ms
Iteration   1: 8.021 ops/ms
Iteration   2: 8.139 ops/ms
Iteration   3: 8.261 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.140 ±(99.9%) 2.197 ops/ms [Average]
  (min, avg, max) = (8.021, 8.140, 8.261), stdev = 0.120
  CI (99.9%): [5.943, 10.337] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.112 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.156 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.003 ms/op
Iteration   1: 3.051 ±(99.9%) 0.006 ms/op
Iteration   2: 3.056 ±(99.9%) 0.002 ms/op
Iteration   3: 2.957 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.021 ±(99.9%) 1.019 ms/op [Average]
  (min, avg, max) = (2.957, 3.021, 3.056), stdev = 0.056
  CI (99.9%): [2.002, 4.041] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.847 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.961 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.002 ms/op
Iteration   1: 2.945 ±(99.9%) 0.003 ms/op
Iteration   2: 2.921 ±(99.9%) 0.004 ms/op
Iteration   3: 2.896 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.921 ±(99.9%) 0.445 ms/op [Average]
  (min, avg, max) = (2.896, 2.921, 2.945), stdev = 0.024
  CI (99.9%): [2.476, 3.366] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.058 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.003 ms/op
Iteration   1: 3.041 ±(99.9%) 0.004 ms/op
Iteration   2: 2.976 ±(99.9%) 0.003 ms/op
Iteration   3: 2.985 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.001 ±(99.9%) 0.648 ms/op [Average]
  (min, avg, max) = (2.976, 3.001, 3.041), stdev = 0.036
  CI (99.9%): [2.353, 3.648] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.269 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.052 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.977 ±(99.9%) 0.019 ms/op
Iteration   1: 3.973 ±(99.9%) 0.010 ms/op
Iteration   2: 3.869 ±(99.9%) 0.016 ms/op
Iteration   3: 3.938 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.927 ±(99.9%) 0.972 ms/op [Average]
  (min, avg, max) = (3.869, 3.927, 3.973), stdev = 0.053
  CI (99.9%): [2.954, 4.899] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.131 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.007 ms/op
Iteration   1: 3.013 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.711 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  7.196 ms/op
                 createUser·p0.9999: 20.840 ms/op
                 createUser·p1.00:   21.103 ms/op

Iteration   2: 3.023 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.759 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  11.063 ms/op
                 createUser·p0.9999: 17.938 ms/op
                 createUser·p1.00:   18.579 ms/op

Iteration   3: 3.052 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.665 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  6.533 ms/op
                 createUser·p0.9999: 31.081 ms/op
                 createUser·p1.00:   31.588 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316837
  mean =      3.029 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29698 
    [ 2.500,  5.000) = 285817 
    [ 5.000,  7.500) = 953 
    [ 7.500, 10.000) = 112 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      7.819 ms/op
     p(99.9900) =     29.008 ms/op
     p(99.9990) =     31.468 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.896 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.037 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.959 ±(99.9%) 0.006 ms/op
Iteration   1: 2.873 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.701 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  6.378 ms/op
                 existUser·p0.9999: 22.053 ms/op
                 existUser·p1.00:   22.610 ms/op

Iteration   2: 2.923 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.700 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.420 ms/op
                 existUser·p0.99:   4.096 ms/op
                 existUser·p0.999:  6.835 ms/op
                 existUser·p0.9999: 16.400 ms/op
                 existUser·p1.00:   16.810 ms/op

Iteration   3: 2.934 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.351 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  6.448 ms/op
                 existUser·p0.9999: 20.546 ms/op
                 existUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329956
  mean =      2.910 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34064 
    [ 2.500,  5.000) = 294996 
    [ 5.000,  7.500) = 668 
    [ 7.500, 10.000) = 36 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.351 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.363 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      4.186 ms/op
     p(99.9000) =      6.529 ms/op
     p(99.9900) =     20.810 ms/op
     p(99.9990) =     22.338 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.905 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.006 ms/op
Iteration   1: 3.053 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.731 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  6.749 ms/op
                 getUser·p0.9999: 12.797 ms/op
                 getUser·p1.00:   13.107 ms/op

Iteration   2: 3.018 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.679 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  6.646 ms/op
                 getUser·p0.9999: 13.671 ms/op
                 getUser·p1.00:   13.926 ms/op

Iteration   3: 3.044 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.538 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  9.335 ms/op
                 getUser·p0.9999: 19.098 ms/op
                 getUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315772
  mean =      3.039 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22639 
    [ 2.500,  5.000) = 291416 
    [ 5.000,  7.500) = 1375 
    [ 7.500, 10.000) = 115 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.538 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      7.927 ms/op
     p(99.9900) =     17.577 ms/op
     p(99.9990) =     19.907 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.130 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.002 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.994 ±(99.9%) 0.010 ms/op
Iteration   1: 3.969 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.094 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  13.006 ms/op
                 listUser·p0.9999: 16.974 ms/op
                 listUser·p1.00:   17.498 ms/op

Iteration   2: 3.945 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.951 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   7.164 ms/op
                 listUser·p0.999:  13.446 ms/op
                 listUser·p0.9999: 15.426 ms/op
                 listUser·p1.00:   17.596 ms/op

Iteration   3: 3.989 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.046 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.746 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  20.546 ms/op
                 listUser·p0.9999: 23.264 ms/op
                 listUser·p1.00:   23.822 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242071
  mean =      3.967 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4603 
    [ 2.500,  5.000) = 211811 
    [ 5.000,  7.500) = 24090 
    [ 7.500, 10.000) = 1116 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 184 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     13.976 ms/op
     p(99.9900) =     21.974 ms/op
     p(99.9990) =     23.809 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.587 ± 0.980  ops/ms
ClientGrpc.existUser                       thrpt       3  11.125 ± 0.892  ops/ms
ClientGrpc.getUser                         thrpt       3  10.533 ± 2.177  ops/ms
ClientGrpc.listUser                        thrpt       3   8.140 ± 2.197  ops/ms
ClientGrpc.createUser                       avgt       3   3.021 ± 1.019   ms/op
ClientGrpc.existUser                        avgt       3   2.921 ± 0.445   ms/op
ClientGrpc.getUser                          avgt       3   3.001 ± 0.648   ms/op
ClientGrpc.listUser                         avgt       3   3.927 ± 0.972   ms/op
ClientGrpc.createUser                     sample  316837   3.029 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.665           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.015           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.621           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.838           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.819           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.008           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.588           ms/op
ClientGrpc.existUser                      sample  329956   2.910 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.351           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.363           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.186           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.529           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.810           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.610           ms/op
ClientGrpc.getUser                        sample  315772   3.039 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.538           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.523           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.927           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.577           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.087           ms/op
ClientGrpc.listUser                       sample  242071   3.967 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.951           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.054           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.053           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.976           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.974           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.822           ms/op
