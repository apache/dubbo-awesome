# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.048 ops/ms
# Warmup Iteration   2: 11.960 ops/ms
# Warmup Iteration   3: 12.512 ops/ms
Iteration   1: 12.659 ops/ms
Iteration   2: 12.790 ops/ms
Iteration   3: 12.657 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.702 ±(99.9%) 1.389 ops/ms [Average]
  (min, avg, max) = (12.657, 12.702, 12.790), stdev = 0.076
  CI (99.9%): [11.313, 14.091] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.098 ops/ms
# Warmup Iteration   2: 13.193 ops/ms
# Warmup Iteration   3: 13.107 ops/ms
Iteration   1: 13.293 ops/ms
Iteration   2: 13.110 ops/ms
Iteration   3: 13.210 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.205 ±(99.9%) 1.672 ops/ms [Average]
  (min, avg, max) = (13.110, 13.205, 13.293), stdev = 0.092
  CI (99.9%): [11.533, 14.876] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.175 ops/ms
# Warmup Iteration   2: 12.468 ops/ms
# Warmup Iteration   3: 12.718 ops/ms
Iteration   1: 12.934 ops/ms
Iteration   2: 12.901 ops/ms
Iteration   3: 12.863 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.899 ±(99.9%) 0.645 ops/ms [Average]
  (min, avg, max) = (12.863, 12.899, 12.934), stdev = 0.035
  CI (99.9%): [12.254, 13.544] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.681 ops/ms
# Warmup Iteration   2: 10.440 ops/ms
# Warmup Iteration   3: 10.563 ops/ms
Iteration   1: 10.481 ops/ms
Iteration   2: 10.517 ops/ms
Iteration   3: 10.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.533 ±(99.9%) 1.115 ops/ms [Average]
  (min, avg, max) = (10.481, 10.533, 10.600), stdev = 0.061
  CI (99.9%): [9.418, 11.648] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.960 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.563 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.004 ms/op
Iteration   1: 2.524 ±(99.9%) 0.005 ms/op
Iteration   2: 2.511 ±(99.9%) 0.005 ms/op
Iteration   3: 2.552 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.529 ±(99.9%) 0.387 ms/op [Average]
  (min, avg, max) = (2.511, 2.529, 2.552), stdev = 0.021
  CI (99.9%): [2.142, 2.916] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.582 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.451 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.401 ±(99.9%) 0.004 ms/op
Iteration   1: 2.409 ±(99.9%) 0.003 ms/op
Iteration   2: 2.420 ±(99.9%) 0.004 ms/op
Iteration   3: 2.452 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.427 ±(99.9%) 0.413 ms/op [Average]
  (min, avg, max) = (2.409, 2.427, 2.452), stdev = 0.023
  CI (99.9%): [2.014, 2.839] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.979 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.494 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.004 ms/op
Iteration   1: 2.468 ±(99.9%) 0.004 ms/op
Iteration   2: 2.493 ±(99.9%) 0.005 ms/op
Iteration   3: 2.482 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.481 ±(99.9%) 0.226 ms/op [Average]
  (min, avg, max) = (2.468, 2.481, 2.493), stdev = 0.012
  CI (99.9%): [2.255, 2.707] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.589 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.005 ms/op
Iteration   1: 3.019 ±(99.9%) 0.006 ms/op
Iteration   2: 3.050 ±(99.9%) 0.006 ms/op
Iteration   3: 3.010 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.026 ±(99.9%) 0.382 ms/op [Average]
  (min, avg, max) = (3.010, 3.026, 3.050), stdev = 0.021
  CI (99.9%): [2.644, 3.409] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.131 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.679 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.005 ms/op
Iteration   1: 2.524 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.954 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   4.059 ms/op
                 createUser·p0.999:  11.440 ms/op
                 createUser·p0.9999: 13.823 ms/op
                 createUser·p1.00:   14.516 ms/op

Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.811 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.715 ms/op
                 createUser·p0.999:  10.080 ms/op
                 createUser·p0.9999: 11.893 ms/op
                 createUser·p1.00:   12.501 ms/op

Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   3.518 ms/op
                 createUser·p0.999:  7.962 ms/op
                 createUser·p0.9999: 13.420 ms/op
                 createUser·p1.00:   15.827 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383510
  mean =      2.501 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 185440 
    [ 2.500,  3.750) = 193987 
    [ 3.750,  5.000) = 3131 
    [ 5.000,  6.250) = 436 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 123 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.777 ms/op
     p(99.9000) =      8.356 ms/op
     p(99.9900) =     13.369 ms/op
     p(99.9990) =     14.530 ms/op
     p(99.9999) =     15.827 ms/op
    p(100.0000) =     15.827 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.670 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.473 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.419 ±(99.9%) 0.005 ms/op
Iteration   1: 2.430 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.885 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.645 ms/op
                 existUser·p0.999:  5.852 ms/op
                 existUser·p0.9999: 13.403 ms/op
                 existUser·p1.00:   14.270 ms/op

Iteration   2: 2.438 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.007 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.662 ms/op
                 existUser·p0.999:  7.951 ms/op
                 existUser·p0.9999: 13.810 ms/op
                 existUser·p1.00:   14.516 ms/op

Iteration   3: 2.445 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.899 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.633 ms/op
                 existUser·p0.999:  6.374 ms/op
                 existUser·p0.9999: 10.844 ms/op
                 existUser·p1.00:   11.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393341
  mean =      2.438 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 197067 
    [ 2.500,  3.750) = 192976 
    [ 3.750,  5.000) = 2513 
    [ 5.000,  6.250) = 333 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 108 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.650 ms/op
     p(99.9000) =      7.780 ms/op
     p(99.9900) =     13.222 ms/op
     p(99.9990) =     14.270 ms/op
     p(99.9999) =     14.516 ms/op
    p(100.0000) =     14.516 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.870 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.555 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.006 ms/op
Iteration   1: 2.497 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.943 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.797 ms/op
                 getUser·p0.999:  10.381 ms/op
                 getUser·p0.9999: 12.927 ms/op
                 getUser·p1.00:   13.615 ms/op

Iteration   2: 2.495 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.081 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   4.071 ms/op
                 getUser·p0.999:  9.126 ms/op
                 getUser·p0.9999: 12.648 ms/op
                 getUser·p1.00:   13.173 ms/op

Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.703 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.920 ms/op
                 getUser·p0.999:  7.150 ms/op
                 getUser·p0.9999: 11.296 ms/op
                 getUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384732
  mean =      2.493 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 112 
    [ 1.250,  2.500) = 191690 
    [ 2.500,  3.750) = 188067 
    [ 3.750,  5.000) = 3754 
    [ 5.000,  6.250) = 616 
    [ 6.250,  7.500) = 96 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 111 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.703 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.903 ms/op
     p(99.9000) =      8.194 ms/op
     p(99.9900) =     12.714 ms/op
     p(99.9990) =     13.185 ms/op
     p(99.9999) =     13.615 ms/op
    p(100.0000) =     13.615 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.768 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.009 ms/op
Iteration   1: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.959 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.751 ms/op
                 listUser·p0.999:  8.749 ms/op
                 listUser·p0.9999: 10.591 ms/op
                 listUser·p1.00:   11.272 ms/op

Iteration   2: 3.019 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.785 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.420 ms/op
                 listUser·p0.9999: 12.108 ms/op
                 listUser·p1.00:   12.845 ms/op

Iteration   3: 3.039 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.720 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  10.057 ms/op
                 listUser·p0.9999: 11.788 ms/op
                 listUser·p1.00:   13.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316713
  mean =      3.029 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 140 
    [ 1.250,  2.500) = 89346 
    [ 2.500,  3.750) = 185756 
    [ 3.750,  5.000) = 34070 
    [ 5.000,  6.250) = 5820 
    [ 6.250,  7.500) = 952 
    [ 7.500,  8.750) = 242 
    [ 8.750, 10.000) = 154 
    [10.000, 11.250) = 150 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =      9.372 ms/op
     p(99.9900) =     11.785 ms/op
     p(99.9990) =     12.703 ms/op
     p(99.9999) =     13.042 ms/op
    p(100.0000) =     13.042 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.702 ± 1.389  ops/ms
ClientPb.existUser                       thrpt       3  13.205 ± 1.672  ops/ms
ClientPb.getUser                         thrpt       3  12.899 ± 0.645  ops/ms
ClientPb.listUser                        thrpt       3  10.533 ± 1.115  ops/ms
ClientPb.createUser                       avgt       3   2.529 ± 0.387   ms/op
ClientPb.existUser                        avgt       3   2.427 ± 0.413   ms/op
ClientPb.getUser                          avgt       3   2.481 ± 0.226   ms/op
ClientPb.listUser                         avgt       3   3.026 ± 0.382   ms/op
ClientPb.createUser                     sample  383510   2.501 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.811           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.356           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.369           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.827           ms/op
ClientPb.existUser                      sample  393341   2.438 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.885           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.494           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.650           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.780           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.222           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.516           ms/op
ClientPb.getUser                        sample  384732   2.493 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.703           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.194           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.714           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.615           ms/op
ClientPb.listUser                       sample  316713   3.029 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.720           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.936           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.669           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.372           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.785           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.042           ms/op
