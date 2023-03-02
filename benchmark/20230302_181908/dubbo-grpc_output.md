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
# Warmup Iteration   1: 4.865 ops/ms
# Warmup Iteration   2: 9.539 ops/ms
# Warmup Iteration   3: 10.026 ops/ms
Iteration   1: 10.794 ops/ms
Iteration   2: 10.398 ops/ms
Iteration   3: 10.283 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.492 ±(99.9%) 4.889 ops/ms [Average]
  (min, avg, max) = (10.283, 10.492, 10.794), stdev = 0.268
  CI (99.9%): [5.603, 15.381] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 8.124 ops/ms
# Warmup Iteration   2: 10.782 ops/ms
# Warmup Iteration   3: 10.709 ops/ms
Iteration   1: 10.866 ops/ms
Iteration   2: 10.769 ops/ms
Iteration   3: 10.962 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.866 ±(99.9%) 1.758 ops/ms [Average]
  (min, avg, max) = (10.769, 10.866, 10.962), stdev = 0.096
  CI (99.9%): [9.108, 12.624] (assumes normal distribution)


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
# Warmup Iteration   1: 8.186 ops/ms
# Warmup Iteration   2: 10.245 ops/ms
# Warmup Iteration   3: 10.667 ops/ms
Iteration   1: 10.576 ops/ms
Iteration   2: 10.410 ops/ms
Iteration   3: 10.275 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.420 ±(99.9%) 2.746 ops/ms [Average]
  (min, avg, max) = (10.275, 10.420, 10.576), stdev = 0.151
  CI (99.9%): [7.675, 13.166] (assumes normal distribution)


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
# Warmup Iteration   1: 6.004 ops/ms
# Warmup Iteration   2: 7.773 ops/ms
# Warmup Iteration   3: 7.952 ops/ms
Iteration   1: 8.133 ops/ms
Iteration   2: 8.269 ops/ms
Iteration   3: 8.236 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.213 ±(99.9%) 1.290 ops/ms [Average]
  (min, avg, max) = (8.133, 8.213, 8.269), stdev = 0.071
  CI (99.9%): [6.923, 9.503] (assumes normal distribution)


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
# Warmup Iteration   1: 3.852 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.002 ms/op
Iteration   1: 3.111 ±(99.9%) 0.002 ms/op
Iteration   2: 3.132 ±(99.9%) 0.001 ms/op
Iteration   3: 3.095 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.113 ±(99.9%) 0.340 ms/op [Average]
  (min, avg, max) = (3.095, 3.113, 3.132), stdev = 0.019
  CI (99.9%): [2.773, 3.453] (assumes normal distribution)


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
# Warmup Iteration   1: 3.962 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.003 ms/op
Iteration   1: 2.909 ±(99.9%) 0.003 ms/op
Iteration   2: 2.946 ±(99.9%) 0.005 ms/op
Iteration   3: 2.896 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.917 ±(99.9%) 0.473 ms/op [Average]
  (min, avg, max) = (2.896, 2.917, 2.946), stdev = 0.026
  CI (99.9%): [2.443, 3.390] (assumes normal distribution)


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
# Warmup Iteration   1: 3.822 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.003 ms/op
Iteration   1: 3.020 ±(99.9%) 0.004 ms/op
Iteration   2: 3.153 ±(99.9%) 0.001 ms/op
Iteration   3: 3.039 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.071 ±(99.9%) 1.306 ms/op [Average]
  (min, avg, max) = (3.020, 3.071, 3.153), stdev = 0.072
  CI (99.9%): [1.764, 4.377] (assumes normal distribution)


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
# Warmup Iteration   1: 4.519 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.051 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.925 ±(99.9%) 0.008 ms/op
Iteration   1: 3.944 ±(99.9%) 0.005 ms/op
Iteration   2: 3.844 ±(99.9%) 0.019 ms/op
Iteration   3: 3.924 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.904 ±(99.9%) 0.960 ms/op [Average]
  (min, avg, max) = (3.844, 3.904, 3.944), stdev = 0.053
  CI (99.9%): [2.944, 4.864] (assumes normal distribution)


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
# Warmup Iteration   1: 4.038 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.006 ms/op
Iteration   1: 3.034 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.705 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  6.059 ms/op
                 createUser·p0.9999: 13.219 ms/op
                 createUser·p1.00:   13.763 ms/op

Iteration   2: 3.014 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.388 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  8.860 ms/op
                 createUser·p0.9999: 16.406 ms/op
                 createUser·p1.00:   18.579 ms/op

Iteration   3: 3.022 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.505 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  7.779 ms/op
                 createUser·p0.9999: 19.393 ms/op
                 createUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317549
  mean =      3.023 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1358 
    [ 1.250,  2.500) = 27355 
    [ 2.500,  3.750) = 274036 
    [ 3.750,  5.000) = 13684 
    [ 5.000,  6.250) = 638 
    [ 6.250,  7.500) = 162 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.388 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      7.496 ms/op
     p(99.9900) =     17.539 ms/op
     p(99.9990) =     19.655 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


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
# Warmup Iteration   1: 3.756 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.083 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.950 ±(99.9%) 0.005 ms/op
Iteration   1: 2.929 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.741 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  7.405 ms/op
                 existUser·p0.9999: 21.266 ms/op
                 existUser·p1.00:   21.627 ms/op

Iteration   2: 2.995 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.785 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.641 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   4.108 ms/op
                 existUser·p0.999:  6.334 ms/op
                 existUser·p0.9999: 13.424 ms/op
                 existUser·p1.00:   13.648 ms/op

Iteration   3: 2.899 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.630 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.162 ms/op
                 existUser·p0.999:  7.087 ms/op
                 existUser·p0.9999: 15.053 ms/op
                 existUser·p1.00:   16.302 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326542
  mean =      2.941 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42610 
    [ 2.500,  5.000) = 283170 
    [ 5.000,  7.500) = 517 
    [ 7.500, 10.000) = 54 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.162 ms/op
     p(99.9000) =      6.914 ms/op
     p(99.9900) =     17.678 ms/op
     p(99.9990) =     21.478 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


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
# Warmup Iteration   1: 4.010 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.006 ms/op
Iteration   1: 3.056 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.403 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  6.887 ms/op
                 getUser·p0.9999: 15.476 ms/op
                 getUser·p1.00:   15.663 ms/op

Iteration   2: 3.048 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.781 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.314 ms/op
                 getUser·p0.999:  6.963 ms/op
                 getUser·p0.9999: 19.464 ms/op
                 getUser·p1.00:   20.185 ms/op

Iteration   3: 3.073 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.662 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.166 ms/op
                 getUser·p0.9999: 17.056 ms/op
                 getUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313874
  mean =      3.059 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24304 
    [ 2.500,  5.000) = 288604 
    [ 5.000,  7.500) = 740 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.403 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      6.799 ms/op
     p(99.9900) =     18.468 ms/op
     p(99.9990) =     19.816 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


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
# Warmup Iteration   1: 4.861 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.200 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.035 ±(99.9%) 0.011 ms/op
Iteration   1: 4.076 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.147 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  12.248 ms/op
                 listUser·p0.9999: 14.879 ms/op
                 listUser·p1.00:   16.220 ms/op

Iteration   2: 4.019 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.645 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  15.375 ms/op
                 listUser·p0.9999: 22.808 ms/op
                 listUser·p1.00:   24.183 ms/op

Iteration   3: 3.982 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.247 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  14.746 ms/op
                 listUser·p0.9999: 24.968 ms/op
                 listUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238485
  mean =      4.025 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5252 
    [ 2.500,  5.000) = 198598 
    [ 5.000,  7.500) = 33585 
    [ 7.500, 10.000) = 627 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      5.251 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     13.828 ms/op
     p(99.9900) =     24.488 ms/op
     p(99.9990) =     25.370 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.492 ± 4.889  ops/ms
ClientGrpc.existUser                       thrpt       3  10.866 ± 1.758  ops/ms
ClientGrpc.getUser                         thrpt       3  10.420 ± 2.746  ops/ms
ClientGrpc.listUser                        thrpt       3   8.213 ± 1.290  ops/ms
ClientGrpc.createUser                       avgt       3   3.113 ± 0.340   ms/op
ClientGrpc.existUser                        avgt       3   2.917 ± 0.473   ms/op
ClientGrpc.getUser                          avgt       3   3.071 ± 1.306   ms/op
ClientGrpc.listUser                         avgt       3   3.904 ± 0.960   ms/op
ClientGrpc.createUser                     sample  317549   3.023 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.388           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.531           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.727           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.309           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.496           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.539           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.792           ms/op
ClientGrpc.existUser                      sample  326542   2.941 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.630           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.506           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.723           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.162           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.914           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.678           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.627           ms/op
ClientGrpc.getUser                        sample  313874   3.059 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.403           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.052           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.625           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.817           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.799           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.468           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.185           ms/op
ClientGrpc.listUser                       sample  238485   4.025 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.645           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.817           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.251           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.799           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.828           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.488           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.395           ms/op
