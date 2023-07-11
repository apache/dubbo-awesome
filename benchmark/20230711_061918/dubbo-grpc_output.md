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
# Warmup Iteration   1: 4.756 ops/ms
# Warmup Iteration   2: 8.836 ops/ms
# Warmup Iteration   3: 10.255 ops/ms
Iteration   1: 10.541 ops/ms
Iteration   2: 10.768 ops/ms
Iteration   3: 10.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.661 ±(99.9%) 2.074 ops/ms [Average]
  (min, avg, max) = (10.541, 10.661, 10.768), stdev = 0.114
  CI (99.9%): [8.586, 12.735] (assumes normal distribution)


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
# Warmup Iteration   1: 7.933 ops/ms
# Warmup Iteration   2: 10.912 ops/ms
# Warmup Iteration   3: 11.097 ops/ms
Iteration   1: 11.109 ops/ms
Iteration   2: 11.203 ops/ms
Iteration   3: 11.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.179 ±(99.9%) 1.128 ops/ms [Average]
  (min, avg, max) = (11.109, 11.179, 11.226), stdev = 0.062
  CI (99.9%): [10.051, 12.308] (assumes normal distribution)


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
# Warmup Iteration   1: 7.361 ops/ms
# Warmup Iteration   2: 10.317 ops/ms
# Warmup Iteration   3: 10.593 ops/ms
Iteration   1: 10.760 ops/ms
Iteration   2: 10.665 ops/ms
Iteration   3: 10.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.695 ±(99.9%) 1.030 ops/ms [Average]
  (min, avg, max) = (10.659, 10.695, 10.760), stdev = 0.056
  CI (99.9%): [9.664, 11.725] (assumes normal distribution)


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
# Warmup Iteration   1: 5.929 ops/ms
# Warmup Iteration   2: 7.806 ops/ms
# Warmup Iteration   3: 7.993 ops/ms
Iteration   1: 8.366 ops/ms
Iteration   2: 8.267 ops/ms
Iteration   3: 8.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.258 ±(99.9%) 2.062 ops/ms [Average]
  (min, avg, max) = (8.141, 8.258, 8.366), stdev = 0.113
  CI (99.9%): [6.196, 10.319] (assumes normal distribution)


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
# Warmup Iteration   1: 3.996 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.164 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.003 ms/op
Iteration   1: 3.020 ±(99.9%) 0.002 ms/op
Iteration   2: 3.036 ±(99.9%) 0.002 ms/op
Iteration   3: 2.988 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.015 ±(99.9%) 0.447 ms/op [Average]
  (min, avg, max) = (2.988, 3.015, 3.036), stdev = 0.025
  CI (99.9%): [2.567, 3.462] (assumes normal distribution)


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
# Warmup Iteration   1: 3.514 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.930 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.928 ±(99.9%) 0.003 ms/op
Iteration   1: 2.855 ±(99.9%) 0.004 ms/op
Iteration   2: 2.899 ±(99.9%) 0.004 ms/op
Iteration   3: 2.884 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.879 ±(99.9%) 0.408 ms/op [Average]
  (min, avg, max) = (2.855, 2.879, 2.899), stdev = 0.022
  CI (99.9%): [2.471, 3.287] (assumes normal distribution)


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
# Warmup Iteration   1: 4.046 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.002 ms/op
Iteration   1: 2.989 ±(99.9%) 0.002 ms/op
Iteration   2: 3.023 ±(99.9%) 0.002 ms/op
Iteration   3: 2.966 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.993 ±(99.9%) 0.527 ms/op [Average]
  (min, avg, max) = (2.966, 2.993, 3.023), stdev = 0.029
  CI (99.9%): [2.466, 3.520] (assumes normal distribution)


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
# Warmup Iteration   1: 5.134 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.973 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.861 ±(99.9%) 0.027 ms/op
Iteration   1: 3.852 ±(99.9%) 0.013 ms/op
Iteration   2: 3.884 ±(99.9%) 0.020 ms/op
Iteration   3: 3.868 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.868 ±(99.9%) 0.287 ms/op [Average]
  (min, avg, max) = (3.852, 3.868, 3.884), stdev = 0.016
  CI (99.9%): [3.581, 4.156] (assumes normal distribution)


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
# Warmup Iteration   1: 4.114 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.007 ms/op
Iteration   1: 2.995 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.725 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  6.219 ms/op
                 createUser·p0.9999: 18.252 ms/op
                 createUser·p1.00:   19.399 ms/op

Iteration   2: 2.954 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.687 ms/op
                 createUser·p0.50:   2.920 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  8.536 ms/op
                 createUser·p0.9999: 21.016 ms/op
                 createUser·p1.00:   21.332 ms/op

Iteration   3: 3.034 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.848 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  7.154 ms/op
                 createUser·p0.9999: 25.559 ms/op
                 createUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320796
  mean =      2.994 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23526 
    [ 2.500,  5.000) = 296083 
    [ 5.000,  7.500) = 870 
    [ 7.500, 10.000) = 125 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.687 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      7.429 ms/op
     p(99.9900) =     23.081 ms/op
     p(99.9990) =     25.683 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


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
# Warmup Iteration   1: 3.791 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.040 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.896 ±(99.9%) 0.006 ms/op
Iteration   1: 2.948 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.664 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  5.931 ms/op
                 existUser·p0.9999: 12.698 ms/op
                 existUser·p1.00:   15.122 ms/op

Iteration   2: 2.863 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.502 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.628 ms/op
                 existUser·p0.999:  6.949 ms/op
                 existUser·p0.9999: 12.643 ms/op
                 existUser·p1.00:   12.927 ms/op

Iteration   3: 2.917 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.632 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  7.268 ms/op
                 existUser·p0.9999: 26.576 ms/op
                 existUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329974
  mean =      2.909 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40453 
    [ 2.500,  5.000) = 288229 
    [ 5.000,  7.500) = 1082 
    [ 7.500, 10.000) = 62 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.502 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      6.783 ms/op
     p(99.9900) =     15.150 ms/op
     p(99.9990) =     26.771 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


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
# Warmup Iteration   1: 3.779 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.007 ms/op
Iteration   1: 2.976 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.567 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.654 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  8.338 ms/op
                 getUser·p0.9999: 14.127 ms/op
                 getUser·p1.00:   15.221 ms/op

Iteration   2: 3.010 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.711 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  7.591 ms/op
                 getUser·p0.9999: 18.165 ms/op
                 getUser·p1.00:   18.743 ms/op

Iteration   3: 3.037 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.560 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.166 ms/op
                 getUser·p0.999:  6.142 ms/op
                 getUser·p0.9999: 17.872 ms/op
                 getUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319305
  mean =      3.007 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1094 
    [ 1.250,  2.500) = 23625 
    [ 2.500,  3.750) = 281248 
    [ 3.750,  5.000) = 12308 
    [ 5.000,  6.250) = 451 
    [ 6.250,  7.500) = 270 
    [ 7.500,  8.750) = 75 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 69 
    [17.500, 18.750) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      7.442 ms/op
     p(99.9900) =     17.664 ms/op
     p(99.9990) =     18.606 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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
# Warmup Iteration   1: 5.187 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.021 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.904 ±(99.9%) 0.010 ms/op
Iteration   1: 3.950 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.713 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  12.845 ms/op
                 listUser·p0.9999: 16.437 ms/op
                 listUser·p1.00:   17.138 ms/op

Iteration   2: 3.920 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.190 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  12.691 ms/op
                 listUser·p0.9999: 23.811 ms/op
                 listUser·p1.00:   25.199 ms/op

Iteration   3: 3.838 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.073 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   5.486 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  16.801 ms/op
                 listUser·p0.9999: 24.434 ms/op
                 listUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246148
  mean =      3.902 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4156 
    [ 2.500,  5.000) = 222016 
    [ 5.000,  7.500) = 19042 
    [ 7.500, 10.000) = 516 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.489 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     13.570 ms/op
     p(99.9900) =     24.216 ms/op
     p(99.9990) =     25.108 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.661 ± 2.074  ops/ms
ClientGrpc.existUser                       thrpt       3  11.179 ± 1.128  ops/ms
ClientGrpc.getUser                         thrpt       3  10.695 ± 1.030  ops/ms
ClientGrpc.listUser                        thrpt       3   8.258 ± 2.062  ops/ms
ClientGrpc.createUser                       avgt       3   3.015 ± 0.447   ms/op
ClientGrpc.existUser                        avgt       3   2.879 ± 0.408   ms/op
ClientGrpc.getUser                          avgt       3   2.993 ± 0.527   ms/op
ClientGrpc.listUser                         avgt       3   3.868 ± 0.287   ms/op
ClientGrpc.createUser                     sample  320796   2.994 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.687           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.970           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.469           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.703           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.429           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.081           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.756           ms/op
ClientGrpc.existUser                      sample  329974   2.909 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.502           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.412           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.637           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.497           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.783           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.150           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.837           ms/op
ClientGrpc.getUser                        sample  319305   3.007 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.560           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.518           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.442           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.664           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.743           ms/op
ClientGrpc.listUser                       sample  246148   3.902 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.713           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.764           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.792           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.489           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.644           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.570           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.216           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.116           ms/op
