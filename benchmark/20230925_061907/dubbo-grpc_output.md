# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.894 ops/ms
# Warmup Iteration   2: 8.296 ops/ms
# Warmup Iteration   3: 9.784 ops/ms
Iteration   1: 10.296 ops/ms
Iteration   2: 10.683 ops/ms
Iteration   3: 10.488 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.489 ±(99.9%) 3.535 ops/ms [Average]
  (min, avg, max) = (10.296, 10.489, 10.683), stdev = 0.194
  CI (99.9%): [6.955, 14.024] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.792 ops/ms
# Warmup Iteration   2: 10.790 ops/ms
# Warmup Iteration   3: 10.733 ops/ms
Iteration   1: 10.848 ops/ms
Iteration   2: 10.905 ops/ms
Iteration   3: 11.025 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.926 ±(99.9%) 1.645 ops/ms [Average]
  (min, avg, max) = (10.848, 10.926, 11.025), stdev = 0.090
  CI (99.9%): [9.281, 12.571] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.439 ops/ms
# Warmup Iteration   2: 10.067 ops/ms
# Warmup Iteration   3: 10.324 ops/ms
Iteration   1: 10.466 ops/ms
Iteration   2: 10.542 ops/ms
Iteration   3: 10.409 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.472 ±(99.9%) 1.210 ops/ms [Average]
  (min, avg, max) = (10.409, 10.472, 10.542), stdev = 0.066
  CI (99.9%): [9.263, 11.682] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.999 ops/ms
# Warmup Iteration   2: 8.340 ops/ms
# Warmup Iteration   3: 8.475 ops/ms
Iteration   1: 8.461 ops/ms
Iteration   2: 8.511 ops/ms
Iteration   3: 8.489 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.487 ±(99.9%) 0.461 ops/ms [Average]
  (min, avg, max) = (8.461, 8.487, 8.511), stdev = 0.025
  CI (99.9%): [8.026, 8.948] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.789 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.014 ms/op
Iteration   1: 3.106 ±(99.9%) 0.003 ms/op
Iteration   2: 3.078 ±(99.9%) 0.003 ms/op
Iteration   3: 3.119 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.101 ±(99.9%) 0.382 ms/op [Average]
  (min, avg, max) = (3.078, 3.101, 3.119), stdev = 0.021
  CI (99.9%): [2.719, 3.483] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.746 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.936 ±(99.9%) 0.003 ms/op
Iteration   1: 2.986 ±(99.9%) 0.003 ms/op
Iteration   2: 2.905 ±(99.9%) 0.002 ms/op
Iteration   3: 2.982 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.958 ±(99.9%) 0.831 ms/op [Average]
  (min, avg, max) = (2.905, 2.958, 2.986), stdev = 0.046
  CI (99.9%): [2.127, 3.789] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.987 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.002 ms/op
Iteration   1: 3.074 ±(99.9%) 0.002 ms/op
Iteration   2: 3.091 ±(99.9%) 0.002 ms/op
Iteration   3: 3.044 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.070 ±(99.9%) 0.429 ms/op [Average]
  (min, avg, max) = (3.044, 3.070, 3.091), stdev = 0.024
  CI (99.9%): [2.641, 3.499] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.843 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.883 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.793 ±(99.9%) 0.059 ms/op
Iteration   1: 3.770 ±(99.9%) 0.042 ms/op
Iteration   2: 3.683 ±(99.9%) 0.010 ms/op
Iteration   3: 3.745 ±(99.9%) 0.041 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.733 ±(99.9%) 0.816 ms/op [Average]
  (min, avg, max) = (3.683, 3.733, 3.770), stdev = 0.045
  CI (99.9%): [2.917, 4.549] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.929 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.252 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.006 ms/op
Iteration   1: 3.036 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.820 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  10.003 ms/op
                 createUser·p0.9999: 15.113 ms/op
                 createUser·p1.00:   15.876 ms/op

Iteration   2: 2.996 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.654 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.338 ms/op
                 createUser·p0.95:   3.523 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  8.427 ms/op
                 createUser·p0.9999: 14.489 ms/op
                 createUser·p1.00:   14.746 ms/op

Iteration   3: 3.108 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.665 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.500 ms/op
                 createUser·p0.999:  8.932 ms/op
                 createUser·p0.9999: 17.138 ms/op
                 createUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315151
  mean =      3.046 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 938 
    [ 1.250,  2.500) = 16952 
    [ 2.500,  3.750) = 280831 
    [ 3.750,  5.000) = 14601 
    [ 5.000,  6.250) = 900 
    [ 6.250,  7.500) = 401 
    [ 7.500,  8.750) = 174 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 98 
    [15.000, 16.250) = 65 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      9.266 ms/op
     p(99.9900) =     15.581 ms/op
     p(99.9990) =     17.395 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.827 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.005 ms/op
Iteration   1: 2.957 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.696 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   4.743 ms/op
                 existUser·p0.999:  7.306 ms/op
                 existUser·p0.9999: 13.894 ms/op
                 existUser·p1.00:   13.910 ms/op

Iteration   2: 2.998 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.722 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  8.421 ms/op
                 existUser·p0.9999: 19.245 ms/op
                 existUser·p1.00:   19.628 ms/op

Iteration   3: 2.930 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.649 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  7.520 ms/op
                 existUser·p0.9999: 16.631 ms/op
                 existUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324166
  mean =      2.961 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2476 
    [ 1.250,  2.500) = 33492 
    [ 2.500,  3.750) = 272978 
    [ 3.750,  5.000) = 13418 
    [ 5.000,  6.250) = 881 
    [ 6.250,  7.500) = 520 
    [ 7.500,  8.750) = 135 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.649 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      8.092 ms/op
     p(99.9900) =     17.970 ms/op
     p(99.9990) =     19.514 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.123 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.193 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.006 ms/op
Iteration   1: 3.162 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.684 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.458 ms/op
                 getUser·p0.9999: 11.285 ms/op
                 getUser·p1.00:   11.682 ms/op

Iteration   2: 3.108 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.941 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  10.107 ms/op
                 getUser·p0.9999: 12.512 ms/op
                 getUser·p1.00:   12.861 ms/op

Iteration   3: 3.098 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.590 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.209 ms/op
                 getUser·p0.9999: 16.020 ms/op
                 getUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307363
  mean =      3.122 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 186 
    [ 1.250,  2.500) = 7411 
    [ 2.500,  3.750) = 282944 
    [ 3.750,  5.000) = 15280 
    [ 5.000,  6.250) = 752 
    [ 6.250,  7.500) = 441 
    [ 7.500,  8.750) = 73 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.842 ms/op
     p(99.9900) =     15.341 ms/op
     p(99.9990) =     17.231 ms/op
     p(99.9999) =     19.268 ms/op
    p(100.0000) =     19.268 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.751 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.859 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.797 ±(99.9%) 0.010 ms/op
Iteration   1: 3.735 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.682 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   5.235 ms/op
                 listUser·p0.99:   6.398 ms/op
                 listUser·p0.999:  13.628 ms/op
                 listUser·p0.9999: 16.445 ms/op
                 listUser·p1.00:   16.876 ms/op

Iteration   2: 3.692 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.853 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   6.250 ms/op
                 listUser·p0.999:  12.501 ms/op
                 listUser·p0.9999: 14.576 ms/op
                 listUser·p1.00:   15.270 ms/op

Iteration   3: 3.813 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.057 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.989 ms/op
                 listUser·p0.99:   6.275 ms/op
                 listUser·p0.999:  13.548 ms/op
                 listUser·p0.9999: 15.329 ms/op
                 listUser·p1.00:   16.056 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 256332
  mean =      3.746 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 21 
    [ 1.250,  2.500) = 5591 
    [ 2.500,  3.750) = 146163 
    [ 3.750,  5.000) = 90536 
    [ 5.000,  6.250) = 11091 
    [ 6.250,  7.500) = 2032 
    [ 7.500,  8.750) = 305 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 167 
    [13.750, 15.000) = 132 
    [15.000, 16.250) = 48 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      5.112 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     13.227 ms/op
     p(99.9900) =     15.785 ms/op
     p(99.9990) =     16.764 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.489 ± 3.535  ops/ms
ClientGrpc.existUser                       thrpt       3  10.926 ± 1.645  ops/ms
ClientGrpc.getUser                         thrpt       3  10.472 ± 1.210  ops/ms
ClientGrpc.listUser                        thrpt       3   8.487 ± 0.461  ops/ms
ClientGrpc.createUser                       avgt       3   3.101 ± 0.382   ms/op
ClientGrpc.existUser                        avgt       3   2.958 ± 0.831   ms/op
ClientGrpc.getUser                          avgt       3   3.070 ± 0.429   ms/op
ClientGrpc.listUser                         avgt       3   3.733 ± 0.816   ms/op
ClientGrpc.createUser                     sample  315151   3.046 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.654           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.015           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.547           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.760           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.266           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.581           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.531           ms/op
ClientGrpc.existUser                      sample  324166   2.961 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.649           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.518           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.731           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.530           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.092           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.970           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.628           ms/op
ClientGrpc.getUser                        sample  307363   3.122 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.590           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.084           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.633           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.842           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.341           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.268           ms/op
ClientGrpc.listUser                       sample  256332   3.746 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.682           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.662           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.317           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.112           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.308           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.227           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          15.785           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          16.876           ms/op
