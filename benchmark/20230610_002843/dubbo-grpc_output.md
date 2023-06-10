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
# Warmup Iteration   1: 4.347 ops/ms
# Warmup Iteration   2: 9.113 ops/ms
# Warmup Iteration   3: 10.195 ops/ms
Iteration   1: 10.330 ops/ms
Iteration   2: 10.491 ops/ms
Iteration   3: 10.481 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.434 ±(99.9%) 1.645 ops/ms [Average]
  (min, avg, max) = (10.330, 10.434, 10.491), stdev = 0.090
  CI (99.9%): [8.789, 12.079] (assumes normal distribution)


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
# Warmup Iteration   1: 7.735 ops/ms
# Warmup Iteration   2: 10.700 ops/ms
# Warmup Iteration   3: 11.129 ops/ms
Iteration   1: 11.020 ops/ms
Iteration   2: 11.144 ops/ms
Iteration   3: 11.072 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.079 ±(99.9%) 1.136 ops/ms [Average]
  (min, avg, max) = (11.020, 11.079, 11.144), stdev = 0.062
  CI (99.9%): [9.943, 12.215] (assumes normal distribution)


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
# Warmup Iteration   1: 6.789 ops/ms
# Warmup Iteration   2: 10.258 ops/ms
# Warmup Iteration   3: 10.597 ops/ms
Iteration   1: 10.560 ops/ms
Iteration   2: 10.576 ops/ms
Iteration   3: 10.516 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.551 ±(99.9%) 0.571 ops/ms [Average]
  (min, avg, max) = (10.516, 10.551, 10.576), stdev = 0.031
  CI (99.9%): [9.980, 11.121] (assumes normal distribution)


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
# Warmup Iteration   1: 5.833 ops/ms
# Warmup Iteration   2: 7.866 ops/ms
# Warmup Iteration   3: 8.148 ops/ms
Iteration   1: 8.268 ops/ms
Iteration   2: 8.176 ops/ms
Iteration   3: 8.212 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.219 ±(99.9%) 0.844 ops/ms [Average]
  (min, avg, max) = (8.176, 8.219, 8.268), stdev = 0.046
  CI (99.9%): [7.375, 9.062] (assumes normal distribution)


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
# Warmup Iteration   1: 4.241 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.221 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.003 ms/op
Iteration   1: 3.043 ±(99.9%) 0.003 ms/op
Iteration   2: 3.069 ±(99.9%) 0.002 ms/op
Iteration   3: 3.096 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.069 ±(99.9%) 0.490 ms/op [Average]
  (min, avg, max) = (3.043, 3.069, 3.096), stdev = 0.027
  CI (99.9%): [2.580, 3.559] (assumes normal distribution)


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
# Warmup Iteration   1: 3.702 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.910 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.896 ±(99.9%) 0.002 ms/op
Iteration   1: 2.946 ±(99.9%) 0.003 ms/op
Iteration   2: 2.923 ±(99.9%) 0.001 ms/op
Iteration   3: 2.883 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.917 ±(99.9%) 0.579 ms/op [Average]
  (min, avg, max) = (2.883, 2.917, 2.946), stdev = 0.032
  CI (99.9%): [2.339, 3.496] (assumes normal distribution)


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
# Warmup Iteration   1: 4.159 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.004 ms/op
Iteration   1: 3.040 ±(99.9%) 0.003 ms/op
Iteration   2: 3.018 ±(99.9%) 0.003 ms/op
Iteration   3: 3.010 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.022 ±(99.9%) 0.285 ms/op [Average]
  (min, avg, max) = (3.010, 3.022, 3.040), stdev = 0.016
  CI (99.9%): [2.737, 3.308] (assumes normal distribution)


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
# Warmup Iteration   1: 4.955 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.094 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.870 ±(99.9%) 0.018 ms/op
Iteration   1: 3.851 ±(99.9%) 0.014 ms/op
Iteration   2: 3.853 ±(99.9%) 0.006 ms/op
Iteration   3: 3.894 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.866 ±(99.9%) 0.447 ms/op [Average]
  (min, avg, max) = (3.851, 3.866, 3.894), stdev = 0.024
  CI (99.9%): [3.419, 4.313] (assumes normal distribution)


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
# Warmup Iteration   1: 4.338 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.223 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.006 ms/op
Iteration   1: 3.066 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.902 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  7.796 ms/op
                 createUser·p0.9999: 14.839 ms/op
                 createUser·p1.00:   15.270 ms/op

Iteration   2: 2.999 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.881 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.379 ms/op
                 createUser·p0.95:   3.506 ms/op
                 createUser·p0.99:   4.100 ms/op
                 createUser·p0.999:  8.847 ms/op
                 createUser·p0.9999: 25.362 ms/op
                 createUser·p1.00:   25.690 ms/op

Iteration   3: 3.109 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.778 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  11.686 ms/op
                 createUser·p0.9999: 30.685 ms/op
                 createUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313842
  mean =      3.057 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18561 
    [ 2.500,  5.000) = 293669 
    [ 5.000,  7.500) = 1061 
    [ 7.500, 10.000) = 221 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =     10.584 ms/op
     p(99.9900) =     25.534 ms/op
     p(99.9990) =     30.928 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


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
# Warmup Iteration   1: 3.957 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.019 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.855 ±(99.9%) 0.006 ms/op
Iteration   1: 2.874 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.607 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.469 ms/op
                 existUser·p0.99:   4.043 ms/op
                 existUser·p0.999:  6.278 ms/op
                 existUser·p0.9999: 12.854 ms/op
                 existUser·p1.00:   13.009 ms/op

Iteration   2: 2.912 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.718 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   3.924 ms/op
                 existUser·p0.999:  6.955 ms/op
                 existUser·p0.9999: 18.024 ms/op
                 existUser·p1.00:   19.169 ms/op

Iteration   3: 2.924 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.662 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  7.733 ms/op
                 existUser·p0.9999: 27.134 ms/op
                 existUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330643
  mean =      2.903 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33103 
    [ 2.500,  5.000) = 296553 
    [ 5.000,  7.500) = 703 
    [ 7.500, 10.000) = 124 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.293 ms/op
     p(95.0000) =      3.490 ms/op
     p(99.0000) =      4.076 ms/op
     p(99.9000) =      7.135 ms/op
     p(99.9900) =     19.161 ms/op
     p(99.9990) =     27.919 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


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
# Warmup Iteration   1: 3.795 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.006 ms/op
Iteration   1: 3.025 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.472 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.682 ms/op
                 getUser·p0.999:  7.399 ms/op
                 getUser·p0.9999: 18.855 ms/op
                 getUser·p1.00:   19.038 ms/op

Iteration   2: 3.003 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.940 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.751 ms/op
                 getUser·p0.999:  7.668 ms/op
                 getUser·p0.9999: 15.729 ms/op
                 getUser·p1.00:   16.007 ms/op

Iteration   3: 3.011 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.811 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  8.342 ms/op
                 getUser·p0.9999: 17.302 ms/op
                 getUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318838
  mean =      3.013 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 840 
    [ 1.250,  2.500) = 26680 
    [ 2.500,  3.750) = 275504 
    [ 3.750,  5.000) = 13981 
    [ 5.000,  6.250) = 959 
    [ 6.250,  7.500) = 468 
    [ 7.500,  8.750) = 219 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 49 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.472 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.686 ms/op
     p(99.9000) =      7.841 ms/op
     p(99.9900) =     17.939 ms/op
     p(99.9990) =     18.999 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


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
# Warmup Iteration   1: 5.911 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.129 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.014 ±(99.9%) 0.012 ms/op
Iteration   1: 3.864 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.395 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.731 ms/op
                 listUser·p0.999:  13.517 ms/op
                 listUser·p0.9999: 16.262 ms/op
                 listUser·p1.00:   16.564 ms/op

Iteration   2: 3.947 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.751 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  16.777 ms/op
                 listUser·p0.9999: 25.228 ms/op
                 listUser·p1.00:   26.345 ms/op

Iteration   3: 4.001 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.771 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   7.091 ms/op
                 listUser·p0.999:  15.630 ms/op
                 listUser·p0.9999: 19.399 ms/op
                 listUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244123
  mean =      3.936 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2867 
    [ 2.500,  5.000) = 217085 
    [ 5.000,  7.500) = 22691 
    [ 7.500, 10.000) = 986 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.989 ms/op
     p(95.0000) =      5.661 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     14.809 ms/op
     p(99.9900) =     24.647 ms/op
     p(99.9990) =     25.479 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.434 ± 1.645  ops/ms
ClientGrpc.existUser                       thrpt       3  11.079 ± 1.136  ops/ms
ClientGrpc.getUser                         thrpt       3  10.551 ± 0.571  ops/ms
ClientGrpc.listUser                        thrpt       3   8.219 ± 0.844  ops/ms
ClientGrpc.createUser                       avgt       3   3.069 ± 0.490   ms/op
ClientGrpc.existUser                        avgt       3   2.917 ± 0.579   ms/op
ClientGrpc.getUser                          avgt       3   3.022 ± 0.285   ms/op
ClientGrpc.listUser                         avgt       3   3.866 ± 0.447   ms/op
ClientGrpc.createUser                     sample  313842   3.057 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.778           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.539           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.727           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.584           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.534           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.031           ms/op
ClientGrpc.existUser                      sample  330643   2.903 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.607           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.293           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.490           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.076           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.135           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.161           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.115           ms/op
ClientGrpc.getUser                        sample  318838   3.013 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.472           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.539           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.748           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.686           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.841           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.939           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.038           ms/op
ClientGrpc.listUser                       sample  244123   3.936 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.751           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.760           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.989           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.661           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.037           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.809           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.647           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.345           ms/op
