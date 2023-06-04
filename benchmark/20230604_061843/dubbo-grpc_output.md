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
# Warmup Iteration   1: 4.580 ops/ms
# Warmup Iteration   2: 9.257 ops/ms
# Warmup Iteration   3: 10.227 ops/ms
Iteration   1: 10.627 ops/ms
Iteration   2: 10.570 ops/ms
Iteration   3: 10.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.615 ±(99.9%) 0.731 ops/ms [Average]
  (min, avg, max) = (10.570, 10.615, 10.648), stdev = 0.040
  CI (99.9%): [9.884, 11.346] (assumes normal distribution)


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
# Warmup Iteration   1: 7.509 ops/ms
# Warmup Iteration   2: 10.713 ops/ms
# Warmup Iteration   3: 11.107 ops/ms
Iteration   1: 11.138 ops/ms
Iteration   2: 11.097 ops/ms
Iteration   3: 11.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.098 ±(99.9%) 0.714 ops/ms [Average]
  (min, avg, max) = (11.060, 11.098, 11.138), stdev = 0.039
  CI (99.9%): [10.385, 11.812] (assumes normal distribution)


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
# Warmup Iteration   1: 7.173 ops/ms
# Warmup Iteration   2: 10.288 ops/ms
# Warmup Iteration   3: 10.449 ops/ms
Iteration   1: 10.578 ops/ms
Iteration   2: 10.671 ops/ms
Iteration   3: 10.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.686 ±(99.9%) 2.098 ops/ms [Average]
  (min, avg, max) = (10.578, 10.686, 10.807), stdev = 0.115
  CI (99.9%): [8.588, 12.783] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.834 ops/ms
# Warmup Iteration   2: 7.928 ops/ms
# Warmup Iteration   3: 8.234 ops/ms
Iteration   1: 8.298 ops/ms
Iteration   2: 8.261 ops/ms
Iteration   3: 8.273 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.277 ±(99.9%) 0.341 ops/ms [Average]
  (min, avg, max) = (8.261, 8.277, 8.298), stdev = 0.019
  CI (99.9%): [7.937, 8.618] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.332 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.002 ms/op
Iteration   1: 3.027 ±(99.9%) 0.004 ms/op
Iteration   2: 2.967 ±(99.9%) 0.003 ms/op
Iteration   3: 3.022 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.005 ±(99.9%) 0.609 ms/op [Average]
  (min, avg, max) = (2.967, 3.005, 3.027), stdev = 0.033
  CI (99.9%): [2.397, 3.614] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.959 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.022 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.952 ±(99.9%) 0.002 ms/op
Iteration   1: 2.908 ±(99.9%) 0.001 ms/op
Iteration   2: 2.932 ±(99.9%) 0.002 ms/op
Iteration   3: 2.998 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.946 ±(99.9%) 0.844 ms/op [Average]
  (min, avg, max) = (2.908, 2.946, 2.998), stdev = 0.046
  CI (99.9%): [2.102, 3.790] (assumes normal distribution)


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
# Warmup Iteration   1: 4.055 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.002 ms/op
Iteration   1: 3.004 ±(99.9%) 0.004 ms/op
Iteration   2: 3.014 ±(99.9%) 0.003 ms/op
Iteration   3: 2.960 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.993 ±(99.9%) 0.520 ms/op [Average]
  (min, avg, max) = (2.960, 2.993, 3.014), stdev = 0.028
  CI (99.9%): [2.473, 3.513] (assumes normal distribution)


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
# Warmup Iteration   1: 5.181 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.008 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 3.818 ±(99.9%) 0.013 ms/op
Iteration   1: 3.869 ±(99.9%) 0.012 ms/op
Iteration   2: 3.759 ±(99.9%) 0.020 ms/op
Iteration   3: 3.858 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.828 ±(99.9%) 1.103 ms/op [Average]
  (min, avg, max) = (3.759, 3.828, 3.869), stdev = 0.060
  CI (99.9%): [2.725, 4.932] (assumes normal distribution)


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
# Warmup Iteration   1: 4.266 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.214 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.007 ms/op
Iteration   1: 3.028 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.836 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.347 ms/op
                 createUser·p0.999:  7.458 ms/op
                 createUser·p0.9999: 21.080 ms/op
                 createUser·p1.00:   21.529 ms/op

Iteration   2: 2.995 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.817 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  7.422 ms/op
                 createUser·p0.9999: 14.740 ms/op
                 createUser·p1.00:   14.877 ms/op

Iteration   3: 3.030 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.753 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  8.733 ms/op
                 createUser·p0.9999: 17.840 ms/op
                 createUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317939
  mean =      3.017 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25711 
    [ 2.500,  5.000) = 290748 
    [ 5.000,  7.500) = 1123 
    [ 7.500, 10.000) = 129 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.635 ms/op
     p(99.9900) =     19.819 ms/op
     p(99.9990) =     21.419 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


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
# Warmup Iteration   1: 4.074 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.940 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.861 ±(99.9%) 0.005 ms/op
Iteration   1: 2.874 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.819 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  7.381 ms/op
                 existUser·p0.9999: 14.813 ms/op
                 existUser·p1.00:   15.204 ms/op

Iteration   2: 2.903 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.698 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.043 ms/op
                 existUser·p0.999:  5.914 ms/op
                 existUser·p0.9999: 13.597 ms/op
                 existUser·p1.00:   14.647 ms/op

Iteration   3: 2.928 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.582 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  7.469 ms/op
                 existUser·p0.9999: 26.545 ms/op
                 existUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330720
  mean =      2.901 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44638 
    [ 2.500,  5.000) = 285085 
    [ 5.000,  7.500) = 749 
    [ 7.500, 10.000) = 16 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.621 ms/op
     p(99.0000) =      4.178 ms/op
     p(99.9000) =      6.906 ms/op
     p(99.9900) =     19.298 ms/op
     p(99.9990) =     27.361 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


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
# Warmup Iteration   1: 4.348 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.008 ms/op
Iteration   1: 3.003 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.555 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  6.857 ms/op
                 getUser·p0.9999: 12.856 ms/op
                 getUser·p1.00:   13.566 ms/op

Iteration   2: 3.002 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.758 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  11.034 ms/op
                 getUser·p0.9999: 14.233 ms/op
                 getUser·p1.00:   14.451 ms/op

Iteration   3: 2.980 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.687 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.416 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  7.095 ms/op
                 getUser·p0.9999: 16.777 ms/op
                 getUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320506
  mean =      2.995 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 937 
    [ 1.250,  2.500) = 22825 
    [ 2.500,  3.750) = 280210 
    [ 3.750,  5.000) = 15324 
    [ 5.000,  6.250) = 659 
    [ 6.250,  7.500) = 256 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.328 ms/op
     p(99.9900) =     15.465 ms/op
     p(99.9990) =     17.098 ms/op
     p(99.9999) =     17.203 ms/op
    p(100.0000) =     17.203 ms/op


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
# Warmup Iteration   1: 5.234 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.041 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.907 ±(99.9%) 0.010 ms/op
Iteration   1: 3.873 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.031 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   6.586 ms/op
                 listUser·p0.999:  13.566 ms/op
                 listUser·p0.9999: 17.932 ms/op
                 listUser·p1.00:   18.514 ms/op

Iteration   2: 3.861 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.011 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  14.139 ms/op
                 listUser·p0.9999: 19.498 ms/op
                 listUser·p1.00:   21.627 ms/op

Iteration   3: 3.899 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.918 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.541 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  14.712 ms/op
                 listUser·p0.9999: 19.333 ms/op
                 listUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247606
  mean =      3.877 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3317 
    [ 2.500,  5.000) = 222935 
    [ 5.000,  7.500) = 20294 
    [ 7.500, 10.000) = 669 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 213 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.918 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.874 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     14.172 ms/op
     p(99.9900) =     19.070 ms/op
     p(99.9990) =     21.627 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.615 ± 0.731  ops/ms
ClientGrpc.existUser                       thrpt       3  11.098 ± 0.714  ops/ms
ClientGrpc.getUser                         thrpt       3  10.686 ± 2.098  ops/ms
ClientGrpc.listUser                        thrpt       3   8.277 ± 0.341  ops/ms
ClientGrpc.createUser                       avgt       3   3.005 ± 0.609   ms/op
ClientGrpc.existUser                        avgt       3   2.946 ± 0.844   ms/op
ClientGrpc.getUser                          avgt       3   2.993 ± 0.520   ms/op
ClientGrpc.listUser                         avgt       3   3.828 ± 1.103   ms/op
ClientGrpc.createUser                     sample  317939   3.017 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.753           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.531           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.635           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.819           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.529           ms/op
ClientGrpc.existUser                      sample  330720   2.901 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.582           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.396           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.621           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.178           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.906           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.298           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.148           ms/op
ClientGrpc.getUser                        sample  320506   2.995 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.555           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.966           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.502           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.328           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.465           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.203           ms/op
ClientGrpc.listUser                       sample  247606   3.877 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.918           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.715           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.874           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.505           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.676           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.172           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.070           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.758           ms/op
