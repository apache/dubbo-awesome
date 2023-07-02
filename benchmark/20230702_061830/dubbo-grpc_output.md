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
# Warmup Iteration   1: 4.228 ops/ms
# Warmup Iteration   2: 8.701 ops/ms
# Warmup Iteration   3: 10.155 ops/ms
Iteration   1: 10.377 ops/ms
Iteration   2: 10.607 ops/ms
Iteration   3: 10.632 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.539 ±(99.9%) 2.570 ops/ms [Average]
  (min, avg, max) = (10.377, 10.539, 10.632), stdev = 0.141
  CI (99.9%): [7.968, 13.109] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.598 ops/ms
# Warmup Iteration   2: 10.728 ops/ms
# Warmup Iteration   3: 11.153 ops/ms
Iteration   1: 11.159 ops/ms
Iteration   2: 10.989 ops/ms
Iteration   3: 11.080 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.076 ±(99.9%) 1.550 ops/ms [Average]
  (min, avg, max) = (10.989, 11.076, 11.159), stdev = 0.085
  CI (99.9%): [9.526, 12.626] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.885 ops/ms
# Warmup Iteration   2: 10.247 ops/ms
# Warmup Iteration   3: 10.573 ops/ms
Iteration   1: 10.750 ops/ms
Iteration   2: 10.759 ops/ms
Iteration   3: 10.785 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.765 ±(99.9%) 0.336 ops/ms [Average]
  (min, avg, max) = (10.750, 10.765, 10.785), stdev = 0.018
  CI (99.9%): [10.429, 11.101] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.059 ops/ms
# Warmup Iteration   2: 7.715 ops/ms
# Warmup Iteration   3: 8.038 ops/ms
Iteration   1: 8.167 ops/ms
Iteration   2: 8.297 ops/ms
Iteration   3: 8.314 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.259 ±(99.9%) 1.472 ops/ms [Average]
  (min, avg, max) = (8.167, 8.259, 8.314), stdev = 0.081
  CI (99.9%): [6.787, 9.731] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.167 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.002 ms/op
Iteration   1: 2.943 ±(99.9%) 0.003 ms/op
Iteration   2: 2.953 ±(99.9%) 0.002 ms/op
Iteration   3: 2.988 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.961 ±(99.9%) 0.437 ms/op [Average]
  (min, avg, max) = (2.943, 2.961, 2.988), stdev = 0.024
  CI (99.9%): [2.524, 3.399] (assumes normal distribution)


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
# Warmup Iteration   1: 3.931 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 2.999 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.883 ±(99.9%) 0.003 ms/op
Iteration   1: 2.946 ±(99.9%) 0.002 ms/op
Iteration   2: 2.896 ±(99.9%) 0.002 ms/op
Iteration   3: 2.837 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.893 ±(99.9%) 0.995 ms/op [Average]
  (min, avg, max) = (2.837, 2.893, 2.946), stdev = 0.055
  CI (99.9%): [1.899, 3.888] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.930 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.178 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.002 ms/op
Iteration   1: 3.025 ±(99.9%) 0.003 ms/op
Iteration   2: 2.988 ±(99.9%) 0.004 ms/op
Iteration   3: 3.048 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.020 ±(99.9%) 0.549 ms/op [Average]
  (min, avg, max) = (2.988, 3.020, 3.048), stdev = 0.030
  CI (99.9%): [2.471, 3.570] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.464 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.012 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.953 ±(99.9%) 0.040 ms/op
Iteration   1: 3.903 ±(99.9%) 0.010 ms/op
Iteration   2: 3.836 ±(99.9%) 0.011 ms/op
Iteration   3: 3.773 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.837 ±(99.9%) 1.184 ms/op [Average]
  (min, avg, max) = (3.773, 3.837, 3.903), stdev = 0.065
  CI (99.9%): [2.653, 5.021] (assumes normal distribution)


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
# Warmup Iteration   1: 4.327 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.163 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.005 ms/op
Iteration   1: 2.982 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.528 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  8.946 ms/op
                 createUser·p0.9999: 12.755 ms/op
                 createUser·p1.00:   13.091 ms/op

Iteration   2: 2.971 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.584 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  7.098 ms/op
                 createUser·p0.9999: 22.519 ms/op
                 createUser·p1.00:   23.101 ms/op

Iteration   3: 2.973 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.640 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.391 ms/op
                 createUser·p0.95:   3.600 ms/op
                 createUser·p0.99:   4.145 ms/op
                 createUser·p0.999:  8.080 ms/op
                 createUser·p0.9999: 18.898 ms/op
                 createUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 322789
  mean =      2.975 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33450 
    [ 2.500,  5.000) = 287986 
    [ 5.000,  7.500) = 967 
    [ 7.500, 10.000) = 159 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.989 ms/op
     p(99.9900) =     20.749 ms/op
     p(99.9990) =     22.930 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


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
# Warmup Iteration   1: 4.083 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.919 ±(99.9%) 0.005 ms/op
Iteration   1: 2.871 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.773 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  6.452 ms/op
                 existUser·p0.9999: 12.152 ms/op
                 existUser·p1.00:   12.370 ms/op

Iteration   2: 2.993 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.849 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  9.078 ms/op
                 existUser·p0.9999: 19.169 ms/op
                 existUser·p1.00:   20.808 ms/op

Iteration   3: 2.939 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.922 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   3.928 ms/op
                 existUser·p0.999:  6.503 ms/op
                 existUser·p0.9999: 16.822 ms/op
                 existUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327151
  mean =      2.933 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40144 
    [ 2.500,  5.000) = 285846 
    [ 5.000,  7.500) = 912 
    [ 7.500, 10.000) = 25 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      6.798 ms/op
     p(99.9900) =     17.708 ms/op
     p(99.9990) =     20.593 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


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
# Warmup Iteration   1: 4.072 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.006 ms/op
Iteration   1: 2.960 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.624 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.355 ms/op
                 getUser·p0.95:   3.551 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  7.086 ms/op
                 getUser·p0.9999: 13.667 ms/op
                 getUser·p1.00:   14.238 ms/op

Iteration   2: 2.987 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.920 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  6.798 ms/op
                 getUser·p0.9999: 15.202 ms/op
                 getUser·p1.00:   15.614 ms/op

Iteration   3: 3.003 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.855 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.438 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.185 ms/op
                 getUser·p0.9999: 17.072 ms/op
                 getUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321605
  mean =      2.983 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 795 
    [ 1.250,  2.500) = 21856 
    [ 2.500,  3.750) = 282941 
    [ 3.750,  5.000) = 14793 
    [ 5.000,  6.250) = 786 
    [ 6.250,  7.500) = 233 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.624 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      6.726 ms/op
     p(99.9900) =     16.425 ms/op
     p(99.9990) =     17.236 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


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
# Warmup Iteration   1: 5.474 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.020 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.756 ±(99.9%) 0.009 ms/op
Iteration   1: 3.843 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.401 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  13.087 ms/op
                 listUser·p0.9999: 19.530 ms/op
                 listUser·p1.00:   19.759 ms/op

Iteration   2: 3.795 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.947 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.586 ms/op
                 listUser·p0.999:  15.499 ms/op
                 listUser·p0.9999: 25.071 ms/op
                 listUser·p1.00:   25.592 ms/op

Iteration   3: 3.831 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.430 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.784 ms/op
                 listUser·p0.999:  17.170 ms/op
                 listUser·p0.9999: 21.286 ms/op
                 listUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 251155
  mean =      3.823 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4418 
    [ 2.500,  5.000) = 225734 
    [ 5.000,  7.500) = 20016 
    [ 7.500, 10.000) = 573 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.768 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     15.529 ms/op
     p(99.9900) =     23.360 ms/op
     p(99.9990) =     25.592 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.539 ± 2.570  ops/ms
ClientGrpc.existUser                       thrpt       3  11.076 ± 1.550  ops/ms
ClientGrpc.getUser                         thrpt       3  10.765 ± 0.336  ops/ms
ClientGrpc.listUser                        thrpt       3   8.259 ± 1.472  ops/ms
ClientGrpc.createUser                       avgt       3   2.961 ± 0.437   ms/op
ClientGrpc.existUser                        avgt       3   2.893 ± 0.995   ms/op
ClientGrpc.getUser                          avgt       3   3.020 ± 0.549   ms/op
ClientGrpc.listUser                         avgt       3   3.837 ± 1.184   ms/op
ClientGrpc.createUser                     sample  322789   2.975 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.528           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.957           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.494           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.989           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.749           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.101           ms/op
ClientGrpc.existUser                      sample  327151   2.933 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.773           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.432           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.641           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.798           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.708           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.808           ms/op
ClientGrpc.getUser                        sample  321605   2.983 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.624           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.957           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.465           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.748           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.726           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.425           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.465           ms/op
ClientGrpc.listUser                       sample  251155   3.823 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.947           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.670           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.768           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.758           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.529           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.360           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.592           ms/op
