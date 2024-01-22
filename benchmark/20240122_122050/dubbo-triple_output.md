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
# Warmup Iteration   1: 4.918 ops/ms
# Warmup Iteration   2: 12.203 ops/ms
# Warmup Iteration   3: 12.491 ops/ms
Iteration   1: 12.818 ops/ms
Iteration   2: 12.691 ops/ms
Iteration   3: 12.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.772 ±(99.9%) 1.283 ops/ms [Average]
  (min, avg, max) = (12.691, 12.772, 12.818), stdev = 0.070
  CI (99.9%): [11.489, 14.055] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.092 ops/ms
# Warmup Iteration   2: 13.134 ops/ms
# Warmup Iteration   3: 13.054 ops/ms
Iteration   1: 13.216 ops/ms
Iteration   2: 12.987 ops/ms
Iteration   3: 13.117 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.107 ±(99.9%) 2.101 ops/ms [Average]
  (min, avg, max) = (12.987, 13.107, 13.216), stdev = 0.115
  CI (99.9%): [11.005, 15.208] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.210 ops/ms
# Warmup Iteration   2: 12.932 ops/ms
# Warmup Iteration   3: 12.851 ops/ms
Iteration   1: 12.963 ops/ms
Iteration   2: 13.030 ops/ms
Iteration   3: 13.027 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.007 ±(99.9%) 0.692 ops/ms [Average]
  (min, avg, max) = (12.963, 13.007, 13.030), stdev = 0.038
  CI (99.9%): [12.315, 13.699] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.817 ops/ms
# Warmup Iteration   2: 10.537 ops/ms
# Warmup Iteration   3: 10.700 ops/ms
Iteration   1: 10.812 ops/ms
Iteration   2: 10.801 ops/ms
Iteration   3: 10.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.804 ±(99.9%) 0.132 ops/ms [Average]
  (min, avg, max) = (10.799, 10.804, 10.812), stdev = 0.007
  CI (99.9%): [10.672, 10.936] (assumes normal distribution)


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
# Warmup Iteration   1: 3.959 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.563 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.464 ±(99.9%) 0.004 ms/op
Iteration   1: 2.484 ±(99.9%) 0.004 ms/op
Iteration   2: 2.470 ±(99.9%) 0.003 ms/op
Iteration   3: 2.470 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.475 ±(99.9%) 0.143 ms/op [Average]
  (min, avg, max) = (2.470, 2.475, 2.484), stdev = 0.008
  CI (99.9%): [2.331, 2.618] (assumes normal distribution)


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
# Warmup Iteration   1: 3.743 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.427 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.004 ms/op
Iteration   1: 2.427 ±(99.9%) 0.004 ms/op
Iteration   2: 2.443 ±(99.9%) 0.004 ms/op
Iteration   3: 2.432 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.434 ±(99.9%) 0.143 ms/op [Average]
  (min, avg, max) = (2.427, 2.434, 2.443), stdev = 0.008
  CI (99.9%): [2.291, 2.577] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.781 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.558 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.003 ms/op
Iteration   1: 2.457 ±(99.9%) 0.004 ms/op
Iteration   2: 2.470 ±(99.9%) 0.004 ms/op
Iteration   3: 2.453 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.460 ±(99.9%) 0.160 ms/op [Average]
  (min, avg, max) = (2.453, 2.460, 2.470), stdev = 0.009
  CI (99.9%): [2.300, 2.620] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.540 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.011 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.965 ±(99.9%) 0.004 ms/op
Iteration   1: 2.985 ±(99.9%) 0.007 ms/op
Iteration   2: 2.982 ±(99.9%) 0.006 ms/op
Iteration   3: 2.988 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.985 ±(99.9%) 0.058 ms/op [Average]
  (min, avg, max) = (2.982, 2.985, 2.988), stdev = 0.003
  CI (99.9%): [2.927, 3.043] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.097 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.639 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.551 ±(99.9%) 0.006 ms/op
Iteration   1: 2.537 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.061 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.731 ms/op
                 createUser·p0.999:  10.779 ms/op
                 createUser·p0.9999: 14.080 ms/op
                 createUser·p1.00:   14.303 ms/op

Iteration   2: 2.516 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.617 ms/op
                 createUser·p0.999:  8.716 ms/op
                 createUser·p0.9999: 13.741 ms/op
                 createUser·p1.00:   14.500 ms/op

Iteration   3: 2.537 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.972 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.879 ms/op
                 createUser·p0.999:  8.061 ms/op
                 createUser·p0.9999: 11.688 ms/op
                 createUser·p1.00:   14.189 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379056
  mean =      2.530 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 182552 
    [ 2.500,  3.750) = 192666 
    [ 3.750,  5.000) = 3062 
    [ 5.000,  6.250) = 320 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 109 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.972 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.752 ms/op
     p(99.9000) =      8.101 ms/op
     p(99.9900) =     13.469 ms/op
     p(99.9990) =     14.389 ms/op
     p(99.9999) =     14.500 ms/op
    p(100.0000) =     14.500 ms/op


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
# Warmup Iteration   1: 3.648 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.465 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
Iteration   1: 2.482 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.001 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  8.222 ms/op
                 existUser·p0.9999: 14.129 ms/op
                 existUser·p1.00:   14.680 ms/op

Iteration   2: 2.475 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.690 ms/op
                 existUser·p0.999:  6.156 ms/op
                 existUser·p0.9999: 12.755 ms/op
                 existUser·p1.00:   13.402 ms/op

Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.613 ms/op
                 existUser·p0.999:  9.209 ms/op
                 existUser·p0.9999: 11.813 ms/op
                 existUser·p1.00:   11.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386819
  mean =      2.480 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 189629 
    [ 2.500,  3.750) = 193916 
    [ 3.750,  5.000) = 2494 
    [ 5.000,  6.250) = 346 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.001 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.633 ms/op
     p(99.9000) =      6.414 ms/op
     p(99.9900) =     13.789 ms/op
     p(99.9990) =     14.649 ms/op
     p(99.9999) =     14.680 ms/op
    p(100.0000) =     14.680 ms/op


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
# Warmup Iteration   1: 3.917 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.548 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.006 ms/op
Iteration   1: 2.456 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.843 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   2.982 ms/op
                 getUser·p0.95:   3.084 ms/op
                 getUser·p0.99:   3.670 ms/op
                 getUser·p0.999:  6.634 ms/op
                 getUser·p0.9999: 13.270 ms/op
                 getUser·p1.00:   13.599 ms/op

Iteration   2: 2.526 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.894 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  9.248 ms/op
                 getUser·p0.9999: 13.539 ms/op
                 getUser·p1.00:   14.713 ms/op

Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.760 ms/op
                 getUser·p0.999:  8.053 ms/op
                 getUser·p0.9999: 11.590 ms/op
                 getUser·p1.00:   11.862 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384679
  mean =      2.493 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 189177 
    [ 2.500,  3.750) = 189533 
    [ 3.750,  5.000) = 4719 
    [ 5.000,  6.250) = 753 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      4.104 ms/op
     p(99.9000) =      7.830 ms/op
     p(99.9900) =     13.109 ms/op
     p(99.9990) =     13.964 ms/op
     p(99.9999) =     14.713 ms/op
    p(100.0000) =     14.713 ms/op


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
# Warmup Iteration   1: 4.603 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.008 ms/op
Iteration   1: 3.043 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.931 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.833 ms/op
                 listUser·p0.999:  9.110 ms/op
                 listUser·p0.9999: 11.624 ms/op
                 listUser·p1.00:   12.698 ms/op

Iteration   2: 2.992 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.855 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  9.423 ms/op
                 listUser·p0.9999: 10.654 ms/op
                 listUser·p1.00:   11.665 ms/op

Iteration   3: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.913 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  8.885 ms/op
                 listUser·p0.9999: 11.941 ms/op
                 listUser·p1.00:   12.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317774
  mean =      3.018 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 109 
    [ 1.250,  2.500) = 91997 
    [ 2.500,  3.750) = 185766 
    [ 3.750,  5.000) = 31813 
    [ 5.000,  6.250) = 6594 
    [ 6.250,  7.500) = 776 
    [ 7.500,  8.750) = 322 
    [ 8.750, 10.000) = 261 
    [10.000, 11.250) = 97 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =      9.159 ms/op
     p(99.9900) =     11.538 ms/op
     p(99.9990) =     12.593 ms/op
     p(99.9999) =     12.698 ms/op
    p(100.0000) =     12.698 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.772 ± 1.283  ops/ms
ClientPb.existUser                       thrpt       3  13.107 ± 2.101  ops/ms
ClientPb.getUser                         thrpt       3  13.007 ± 0.692  ops/ms
ClientPb.listUser                        thrpt       3  10.804 ± 0.132  ops/ms
ClientPb.createUser                       avgt       3   2.475 ± 0.143   ms/op
ClientPb.existUser                        avgt       3   2.434 ± 0.143   ms/op
ClientPb.getUser                          avgt       3   2.460 ± 0.160   ms/op
ClientPb.listUser                         avgt       3   2.985 ± 0.058   ms/op
ClientPb.createUser                     sample  379056   2.530 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.972           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.068           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.101           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.469           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.500           ms/op
ClientPb.existUser                      sample  386819   2.480 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.001           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.552           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.414           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.789           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.680           ms/op
ClientPb.getUser                        sample  384679   2.493 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.843           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.023           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.104           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.830           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.109           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.713           ms/op
ClientPb.listUser                       sample  317774   3.018 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.855           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.652           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.159           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.538           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.698           ms/op
