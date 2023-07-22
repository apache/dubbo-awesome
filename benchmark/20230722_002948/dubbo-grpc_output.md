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
# Warmup Iteration   1: 4.251 ops/ms
# Warmup Iteration   2: 8.809 ops/ms
# Warmup Iteration   3: 9.827 ops/ms
Iteration   1: 10.405 ops/ms
Iteration   2: 10.408 ops/ms
Iteration   3: 10.378 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.397 ±(99.9%) 0.296 ops/ms [Average]
  (min, avg, max) = (10.378, 10.397, 10.408), stdev = 0.016
  CI (99.9%): [10.101, 10.693] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.351 ops/ms
# Warmup Iteration   2: 10.353 ops/ms
# Warmup Iteration   3: 11.118 ops/ms
Iteration   1: 10.860 ops/ms
Iteration   2: 11.022 ops/ms
Iteration   3: 10.920 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.934 ±(99.9%) 1.497 ops/ms [Average]
  (min, avg, max) = (10.860, 10.934, 11.022), stdev = 0.082
  CI (99.9%): [9.437, 12.431] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.932 ops/ms
# Warmup Iteration   2: 10.185 ops/ms
# Warmup Iteration   3: 10.383 ops/ms
Iteration   1: 10.459 ops/ms
Iteration   2: 10.430 ops/ms
Iteration   3: 10.583 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.491 ±(99.9%) 1.477 ops/ms [Average]
  (min, avg, max) = (10.430, 10.491, 10.583), stdev = 0.081
  CI (99.9%): [9.013, 11.968] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.666 ops/ms
# Warmup Iteration   2: 7.702 ops/ms
# Warmup Iteration   3: 8.000 ops/ms
Iteration   1: 7.912 ops/ms
Iteration   2: 8.075 ops/ms
Iteration   3: 8.092 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.026 ±(99.9%) 1.811 ops/ms [Average]
  (min, avg, max) = (7.912, 8.026, 8.092), stdev = 0.099
  CI (99.9%): [6.216, 9.837] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.526 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.164 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.144 ±(99.9%) 0.003 ms/op
Iteration   1: 3.084 ±(99.9%) 0.001 ms/op
Iteration   2: 3.103 ±(99.9%) 0.003 ms/op
Iteration   3: 3.086 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.091 ±(99.9%) 0.193 ms/op [Average]
  (min, avg, max) = (3.084, 3.091, 3.103), stdev = 0.011
  CI (99.9%): [2.898, 3.284] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.102 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.002 ms/op
Iteration   1: 2.924 ±(99.9%) 0.002 ms/op
Iteration   2: 2.917 ±(99.9%) 0.002 ms/op
Iteration   3: 2.903 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.915 ±(99.9%) 0.190 ms/op [Average]
  (min, avg, max) = (2.903, 2.915, 2.924), stdev = 0.010
  CI (99.9%): [2.725, 3.105] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.533 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.301 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.003 ms/op
Iteration   1: 3.092 ±(99.9%) 0.003 ms/op
Iteration   2: 3.096 ±(99.9%) 0.003 ms/op
Iteration   3: 3.108 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.099 ±(99.9%) 0.150 ms/op [Average]
  (min, avg, max) = (3.092, 3.099, 3.108), stdev = 0.008
  CI (99.9%): [2.949, 3.248] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.557 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.262 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 3.989 ±(99.9%) 0.010 ms/op
Iteration   1: 4.013 ±(99.9%) 0.009 ms/op
Iteration   2: 3.982 ±(99.9%) 0.025 ms/op
Iteration   3: 3.990 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.995 ±(99.9%) 0.293 ms/op [Average]
  (min, avg, max) = (3.982, 3.995, 4.013), stdev = 0.016
  CI (99.9%): [3.702, 4.287] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.724 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.296 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.006 ms/op
Iteration   1: 3.132 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.516 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.426 ms/op
                 createUser·p0.999:  6.406 ms/op
                 createUser·p0.9999: 14.325 ms/op
                 createUser·p1.00:   14.828 ms/op

Iteration   2: 3.055 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.725 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  7.719 ms/op
                 createUser·p0.9999: 17.924 ms/op
                 createUser·p1.00:   18.153 ms/op

Iteration   3: 3.098 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.690 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  7.811 ms/op
                 createUser·p0.9999: 16.286 ms/op
                 createUser·p1.00:   16.744 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310279
  mean =      3.094 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 560 
    [ 1.250,  2.500) = 15933 
    [ 2.500,  3.750) = 274474 
    [ 3.750,  5.000) = 17962 
    [ 5.000,  6.250) = 786 
    [ 6.250,  7.500) = 296 
    [ 7.500,  8.750) = 77 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 85 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.516 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.291 ms/op
     p(99.9900) =     16.302 ms/op
     p(99.9990) =     18.121 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


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
# Warmup Iteration   1: 4.153 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.009 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.005 ms/op
Iteration   1: 2.984 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.754 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  7.475 ms/op
                 existUser·p0.9999: 12.384 ms/op
                 existUser·p1.00:   12.714 ms/op

Iteration   2: 2.904 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.908 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.379 ms/op
                 existUser·p0.99:   3.867 ms/op
                 existUser·p0.999:  5.240 ms/op
                 existUser·p0.9999: 15.351 ms/op
                 existUser·p1.00:   15.745 ms/op

Iteration   3: 2.960 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.568 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  12.573 ms/op
                 existUser·p0.9999: 18.219 ms/op
                 existUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325599
  mean =      2.949 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1070 
    [ 1.250,  2.500) = 31124 
    [ 2.500,  3.750) = 282282 
    [ 3.750,  5.000) = 10008 
    [ 5.000,  6.250) = 520 
    [ 6.250,  7.500) = 249 
    [ 7.500,  8.750) = 117 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 42 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      4.190 ms/op
     p(99.9000) =      7.719 ms/op
     p(99.9900) =     17.421 ms/op
     p(99.9990) =     18.440 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


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
# Warmup Iteration   1: 4.504 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.222 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.160 ±(99.9%) 0.007 ms/op
Iteration   1: 3.129 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.836 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  8.660 ms/op
                 getUser·p0.9999: 16.206 ms/op
                 getUser·p1.00:   16.515 ms/op

Iteration   2: 3.091 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.794 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  7.091 ms/op
                 getUser·p0.9999: 24.663 ms/op
                 getUser·p1.00:   24.773 ms/op

Iteration   3: 3.116 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.744 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  7.215 ms/op
                 getUser·p0.9999: 17.784 ms/op
                 getUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308310
  mean =      3.112 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8161 
    [ 2.500,  5.000) = 299019 
    [ 5.000,  7.500) = 832 
    [ 7.500, 10.000) = 74 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      7.438 ms/op
     p(99.9900) =     22.321 ms/op
     p(99.9990) =     24.773 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


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
# Warmup Iteration   1: 6.225 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.074 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.080 ±(99.9%) 0.012 ms/op
Iteration   1: 3.933 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.452 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  14.134 ms/op
                 listUser·p0.9999: 17.695 ms/op
                 listUser·p1.00:   18.153 ms/op

Iteration   2: 3.930 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.327 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  15.471 ms/op
                 listUser·p0.9999: 17.236 ms/op
                 listUser·p1.00:   18.612 ms/op

Iteration   3: 3.984 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.768 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  17.957 ms/op
                 listUser·p0.9999: 20.511 ms/op
                 listUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243067
  mean =      3.949 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4048 
    [ 2.500,  5.000) = 216511 
    [ 5.000,  7.500) = 20825 
    [ 7.500, 10.000) = 1036 
    [10.000, 12.500) = 220 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 178 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     15.531 ms/op
     p(99.9900) =     19.903 ms/op
     p(99.9990) =     20.779 ms/op
     p(99.9999) =     20.906 ms/op
    p(100.0000) =     20.906 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.397 ± 0.296  ops/ms
ClientGrpc.existUser                       thrpt       3  10.934 ± 1.497  ops/ms
ClientGrpc.getUser                         thrpt       3  10.491 ± 1.477  ops/ms
ClientGrpc.listUser                        thrpt       3   8.026 ± 1.811  ops/ms
ClientGrpc.createUser                       avgt       3   3.091 ± 0.193   ms/op
ClientGrpc.existUser                        avgt       3   2.915 ± 0.190   ms/op
ClientGrpc.getUser                          avgt       3   3.099 ± 0.150   ms/op
ClientGrpc.listUser                         avgt       3   3.995 ± 0.293   ms/op
ClientGrpc.createUser                     sample  310279   3.094 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.516           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.072           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.629           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.291           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.302           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.153           ms/op
ClientGrpc.existUser                      sample  325599   2.949 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.568           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.412           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.637           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.190           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.719           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.421           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.547           ms/op
ClientGrpc.getUser                        sample  308310   3.112 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.744           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.084           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.572           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.438           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.321           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.773           ms/op
ClientGrpc.listUser                       sample  243067   3.949 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.768           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.797           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.915           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.751           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.062           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.531           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.903           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.906           ms/op
