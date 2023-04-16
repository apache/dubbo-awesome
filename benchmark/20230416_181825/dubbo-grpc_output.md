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
# Warmup Iteration   1: 4.633 ops/ms
# Warmup Iteration   2: 9.331 ops/ms
# Warmup Iteration   3: 10.267 ops/ms
Iteration   1: 10.533 ops/ms
Iteration   2: 10.779 ops/ms
Iteration   3: 10.622 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.645 ±(99.9%) 2.268 ops/ms [Average]
  (min, avg, max) = (10.533, 10.645, 10.779), stdev = 0.124
  CI (99.9%): [8.377, 12.913] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:55
# Fork: 1 of 1
# Warmup Iteration   1: 7.932 ops/ms
# Warmup Iteration   2: 10.822 ops/ms
# Warmup Iteration   3: 11.238 ops/ms
Iteration   1: 11.417 ops/ms
Iteration   2: 11.176 ops/ms
Iteration   3: 11.148 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.247 ±(99.9%) 2.701 ops/ms [Average]
  (min, avg, max) = (11.148, 11.247, 11.417), stdev = 0.148
  CI (99.9%): [8.547, 13.948] (assumes normal distribution)


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
# Warmup Iteration   1: 8.021 ops/ms
# Warmup Iteration   2: 10.439 ops/ms
# Warmup Iteration   3: 10.785 ops/ms
Iteration   1: 10.621 ops/ms
Iteration   2: 10.898 ops/ms
Iteration   3: 11.037 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.852 ±(99.9%) 3.861 ops/ms [Average]
  (min, avg, max) = (10.621, 10.852, 11.037), stdev = 0.212
  CI (99.9%): [6.991, 14.713] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.873 ops/ms
# Warmup Iteration   2: 8.054 ops/ms
# Warmup Iteration   3: 8.185 ops/ms
Iteration   1: 8.169 ops/ms
Iteration   2: 8.221 ops/ms
Iteration   3: 8.384 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.258 ±(99.9%) 2.042 ops/ms [Average]
  (min, avg, max) = (8.169, 8.258, 8.384), stdev = 0.112
  CI (99.9%): [6.216, 10.300] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.221 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.112 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.007 ms/op
Iteration   1: 2.973 ±(99.9%) 0.002 ms/op
Iteration   2: 2.984 ±(99.9%) 0.003 ms/op
Iteration   3: 3.006 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.988 ±(99.9%) 0.301 ms/op [Average]
  (min, avg, max) = (2.973, 2.988, 3.006), stdev = 0.017
  CI (99.9%): [2.686, 3.289] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.671 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.915 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.862 ±(99.9%) 0.003 ms/op
Iteration   1: 2.817 ±(99.9%) 0.004 ms/op
Iteration   2: 2.910 ±(99.9%) 0.003 ms/op
Iteration   3: 2.842 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.856 ±(99.9%) 0.884 ms/op [Average]
  (min, avg, max) = (2.817, 2.856, 2.910), stdev = 0.048
  CI (99.9%): [1.972, 3.740] (assumes normal distribution)


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
# Warmup Iteration   1: 3.810 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.004 ms/op
Iteration   1: 2.926 ±(99.9%) 0.002 ms/op
Iteration   2: 2.978 ±(99.9%) 0.003 ms/op
Iteration   3: 2.990 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.965 ±(99.9%) 0.622 ms/op [Average]
  (min, avg, max) = (2.926, 2.965, 2.990), stdev = 0.034
  CI (99.9%): [2.343, 3.587] (assumes normal distribution)


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
# Warmup Iteration   1: 4.252 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.994 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.918 ±(99.9%) 0.015 ms/op
Iteration   1: 3.899 ±(99.9%) 0.014 ms/op
Iteration   2: 3.848 ±(99.9%) 0.012 ms/op
Iteration   3: 3.865 ±(99.9%) 0.047 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.871 ±(99.9%) 0.477 ms/op [Average]
  (min, avg, max) = (3.848, 3.871, 3.899), stdev = 0.026
  CI (99.9%): [3.393, 4.348] (assumes normal distribution)


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
# Warmup Iteration   1: 4.154 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.007 ms/op
Iteration   1: 2.993 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.635 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  6.457 ms/op
                 createUser·p0.9999: 11.288 ms/op
                 createUser·p1.00:   11.551 ms/op

Iteration   2: 2.965 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.701 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.387 ms/op
                 createUser·p0.95:   3.633 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  7.309 ms/op
                 createUser·p0.9999: 12.930 ms/op
                 createUser·p1.00:   13.058 ms/op

Iteration   3: 2.927 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.636 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  6.767 ms/op
                 createUser·p0.9999: 23.005 ms/op
                 createUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323989
  mean =      2.961 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32104 
    [ 2.500,  5.000) = 290638 
    [ 5.000,  7.500) = 979 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      6.767 ms/op
     p(99.9900) =     21.799 ms/op
     p(99.9990) =     23.257 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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
# Warmup Iteration   1: 3.751 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.996 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.934 ±(99.9%) 0.006 ms/op
Iteration   1: 2.866 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.736 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  5.915 ms/op
                 existUser·p0.9999: 13.744 ms/op
                 existUser·p1.00:   15.073 ms/op

Iteration   2: 2.917 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.618 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  5.795 ms/op
                 existUser·p0.9999: 22.119 ms/op
                 existUser·p1.00:   22.446 ms/op

Iteration   3: 2.879 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.642 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.430 ms/op
                 existUser·p0.999:  6.619 ms/op
                 existUser·p0.9999: 15.874 ms/op
                 existUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332396
  mean =      2.887 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50391 
    [ 2.500,  5.000) = 281150 
    [ 5.000,  7.500) = 647 
    [ 7.500, 10.000) = 48 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      6.347 ms/op
     p(99.9900) =     17.883 ms/op
     p(99.9990) =     22.327 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


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
# Warmup Iteration   1: 3.768 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.971 ±(99.9%) 0.007 ms/op
Iteration   1: 3.031 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.701 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  6.450 ms/op
                 getUser·p0.9999: 13.074 ms/op
                 getUser·p1.00:   13.238 ms/op

Iteration   2: 2.974 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.674 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  6.459 ms/op
                 getUser·p0.9999: 16.617 ms/op
                 getUser·p1.00:   17.072 ms/op

Iteration   3: 3.032 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.675 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  8.421 ms/op
                 getUser·p0.9999: 30.081 ms/op
                 getUser·p1.00:   32.768 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318423
  mean =      3.012 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29167 
    [ 2.500,  5.000) = 288141 
    [ 5.000,  7.500) = 840 
    [ 7.500, 10.000) = 80 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      7.242 ms/op
     p(99.9900) =     28.894 ms/op
     p(99.9990) =     32.762 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


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
# Warmup Iteration   1: 5.135 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.877 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.811 ±(99.9%) 0.010 ms/op
Iteration   1: 3.859 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.163 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  12.127 ms/op
                 listUser·p0.9999: 14.364 ms/op
                 listUser·p1.00:   15.008 ms/op

Iteration   2: 3.784 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.151 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   5.317 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  18.088 ms/op
                 listUser·p0.9999: 23.483 ms/op
                 listUser·p1.00:   26.411 ms/op

Iteration   3: 3.900 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.639 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  14.580 ms/op
                 listUser·p0.9999: 22.595 ms/op
                 listUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249497
  mean =      3.847 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4881 
    [ 2.500,  5.000) = 225253 
    [ 5.000,  7.500) = 18290 
    [ 7.500, 10.000) = 528 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 170 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.639 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.768 ms/op
     p(95.0000) =      5.439 ms/op
     p(99.0000) =      6.619 ms/op
     p(99.9000) =     14.361 ms/op
     p(99.9900) =     22.808 ms/op
     p(99.9990) =     26.281 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.645 ± 2.268  ops/ms
ClientGrpc.existUser                       thrpt       3  11.247 ± 2.701  ops/ms
ClientGrpc.getUser                         thrpt       3  10.852 ± 3.861  ops/ms
ClientGrpc.listUser                        thrpt       3   8.258 ± 2.042  ops/ms
ClientGrpc.createUser                       avgt       3   2.988 ± 0.301   ms/op
ClientGrpc.existUser                        avgt       3   2.856 ± 0.884   ms/op
ClientGrpc.getUser                          avgt       3   2.965 ± 0.622   ms/op
ClientGrpc.listUser                         avgt       3   3.871 ± 0.477   ms/op
ClientGrpc.createUser                     sample  323989   2.961 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.635           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.957           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.490           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.707           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.399           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           6.767           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.799           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.364           ms/op
ClientGrpc.existUser                      sample  332396   2.887 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.618           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.428           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.670           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.424           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.347           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.883           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.446           ms/op
ClientGrpc.getUser                        sample  318423   3.012 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.674           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.006           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.580           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.789           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.242           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.894           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.768           ms/op
ClientGrpc.listUser                       sample  249497   3.847 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.639           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.719           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.768           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.439           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.619           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.361           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.808           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.411           ms/op
