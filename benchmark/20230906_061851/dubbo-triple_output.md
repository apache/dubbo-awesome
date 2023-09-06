# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.640 ops/ms
# Warmup Iteration   2: 3.405 ops/ms
# Warmup Iteration   3: 6.931 ops/ms
Iteration   1: 7.233 ops/ms
Iteration   2: 7.733 ops/ms
Iteration   3: 7.688 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.551 ±(99.9%) 5.046 ops/ms [Average]
  (min, avg, max) = (7.233, 7.551, 7.733), stdev = 0.277
  CI (99.9%): [2.505, 12.597] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.447 ops/ms
# Warmup Iteration   2: 6.435 ops/ms
# Warmup Iteration   3: 7.733 ops/ms
Iteration   1: 7.806 ops/ms
Iteration   2: 7.745 ops/ms
Iteration   3: 8.091 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.881 ±(99.9%) 3.367 ops/ms [Average]
  (min, avg, max) = (7.745, 7.881, 8.091), stdev = 0.185
  CI (99.9%): [4.514, 11.248] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.119 ops/ms
# Warmup Iteration   2: 6.309 ops/ms
# Warmup Iteration   3: 7.723 ops/ms
Iteration   1: 7.740 ops/ms
Iteration   2: 7.925 ops/ms
Iteration   3: 7.866 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.844 ±(99.9%) 1.723 ops/ms [Average]
  (min, avg, max) = (7.740, 7.844, 7.925), stdev = 0.094
  CI (99.9%): [6.121, 9.567] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.160 ops/ms
# Warmup Iteration   2: 6.105 ops/ms
# Warmup Iteration   3: 6.582 ops/ms
Iteration   1: 6.550 ops/ms
Iteration   2: 6.600 ops/ms
Iteration   3: 7.037 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.729 ±(99.9%) 4.882 ops/ms [Average]
  (min, avg, max) = (6.550, 6.729, 7.037), stdev = 0.268
  CI (99.9%): [1.847, 11.611] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 13.325 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.140 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.634 ±(99.9%) 0.006 ms/op
Iteration   1: 4.342 ±(99.9%) 0.005 ms/op
Iteration   2: 4.401 ±(99.9%) 0.006 ms/op
Iteration   3: 4.193 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.312 ±(99.9%) 1.955 ms/op [Average]
  (min, avg, max) = (4.193, 4.312, 4.401), stdev = 0.107
  CI (99.9%): [2.357, 6.266] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 13.439 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 5.060 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.947 ±(99.9%) 0.004 ms/op
Iteration   1: 3.908 ±(99.9%) 0.002 ms/op
Iteration   2: 3.976 ±(99.9%) 0.002 ms/op
Iteration   3: 3.852 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.912 ±(99.9%) 1.136 ms/op [Average]
  (min, avg, max) = (3.852, 3.912, 3.976), stdev = 0.062
  CI (99.9%): [2.776, 5.048] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 14.060 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.878 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.373 ±(99.9%) 0.008 ms/op
Iteration   1: 4.209 ±(99.9%) 0.005 ms/op
Iteration   2: 4.059 ±(99.9%) 0.004 ms/op
Iteration   3: 3.998 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.089 ±(99.9%) 1.986 ms/op [Average]
  (min, avg, max) = (3.998, 4.089, 4.209), stdev = 0.109
  CI (99.9%): [2.103, 6.075] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 14.732 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 5.589 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.074 ±(99.9%) 0.005 ms/op
Iteration   1: 4.814 ±(99.9%) 0.012 ms/op
Iteration   2: 4.597 ±(99.9%) 0.013 ms/op
Iteration   3: 4.613 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.675 ±(99.9%) 2.206 ms/op [Average]
  (min, avg, max) = (4.597, 4.675, 4.814), stdev = 0.121
  CI (99.9%): [2.469, 6.880] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 12.876 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 5.267 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.340 ±(99.9%) 0.018 ms/op
Iteration   1: 4.078 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.513 ms/op
                 createUser·p0.50:   3.801 ms/op
                 createUser·p0.90:   4.760 ms/op
                 createUser·p0.95:   5.579 ms/op
                 createUser·p0.99:   8.847 ms/op
                 createUser·p0.999:  22.693 ms/op
                 createUser·p0.9999: 25.105 ms/op
                 createUser·p1.00:   26.870 ms/op

Iteration   2: 4.063 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.890 ms/op
                 createUser·p0.50:   3.871 ms/op
                 createUser·p0.90:   4.727 ms/op
                 createUser·p0.95:   5.489 ms/op
                 createUser·p0.99:   8.380 ms/op
                 createUser·p0.999:  12.737 ms/op
                 createUser·p0.9999: 27.333 ms/op
                 createUser·p1.00:   27.984 ms/op

Iteration   3: 4.050 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.950 ms/op
                 createUser·p0.50:   3.846 ms/op
                 createUser·p0.90:   4.645 ms/op
                 createUser·p0.95:   5.112 ms/op
                 createUser·p0.99:   7.356 ms/op
                 createUser·p0.999:  28.152 ms/op
                 createUser·p0.9999: 32.575 ms/op
                 createUser·p1.00:   33.194 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 235986
  mean =      4.064 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 469 
    [ 2.500,  5.000) = 219141 
    [ 5.000,  7.500) = 13134 
    [ 7.500, 10.000) = 2175 
    [10.000, 12.500) = 606 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.513 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.390 ms/op
     p(99.0000) =      8.217 ms/op
     p(99.9000) =     22.741 ms/op
     p(99.9900) =     31.359 ms/op
     p(99.9990) =     32.942 ms/op
     p(99.9999) =     33.194 ms/op
    p(100.0000) =     33.194 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 12.588 ±(99.9%) 0.220 ms/op
# Warmup Iteration   2: 4.522 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.104 ±(99.9%) 0.014 ms/op
Iteration   1: 4.011 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.681 ms/op
                 existUser·p0.50:   3.736 ms/op
                 existUser·p0.90:   4.809 ms/op
                 existUser·p0.95:   6.087 ms/op
                 existUser·p0.99:   8.004 ms/op
                 existUser·p0.999:  15.319 ms/op
                 existUser·p0.9999: 25.101 ms/op
                 existUser·p1.00:   25.788 ms/op

Iteration   2: 3.865 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.015 ms/op
                 existUser·p0.50:   3.678 ms/op
                 existUser·p0.90:   4.235 ms/op
                 existUser·p0.95:   4.751 ms/op
                 existUser·p0.99:   7.414 ms/op
                 existUser·p0.999:  28.063 ms/op
                 existUser·p0.9999: 34.781 ms/op
                 existUser·p1.00:   36.176 ms/op

Iteration   3: 4.094 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.911 ms/op
                 existUser·p0.50:   3.830 ms/op
                 existUser·p0.90:   4.858 ms/op
                 existUser·p0.95:   5.964 ms/op
                 existUser·p0.99:   8.552 ms/op
                 existUser·p0.999:  13.713 ms/op
                 existUser·p0.9999: 33.212 ms/op
                 existUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 240666
  mean =      3.988 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 309 
    [ 2.500,  5.000) = 223263 
    [ 5.000,  7.500) = 13375 
    [ 7.500, 10.000) = 2924 
    [10.000, 12.500) = 449 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 49 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.681 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      8.217 ms/op
     p(99.9000) =     15.352 ms/op
     p(99.9900) =     33.686 ms/op
     p(99.9990) =     35.441 ms/op
     p(99.9999) =     36.176 ms/op
    p(100.0000) =     36.176 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 11.682 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.820 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.156 ±(99.9%) 0.014 ms/op
Iteration   1: 4.388 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.606 ms/op
                 getUser·p0.50:   3.949 ms/op
                 getUser·p0.90:   5.915 ms/op
                 getUser·p0.95:   6.963 ms/op
                 getUser·p0.99:   10.928 ms/op
                 getUser·p0.999:  22.778 ms/op
                 getUser·p0.9999: 25.882 ms/op
                 getUser·p1.00:   26.509 ms/op

Iteration   2: 4.196 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.042 ms/op
                 getUser·p0.50:   3.924 ms/op
                 getUser·p0.90:   5.153 ms/op
                 getUser·p0.95:   5.808 ms/op
                 getUser·p0.99:   8.086 ms/op
                 getUser·p0.999:  24.030 ms/op
                 getUser·p0.9999: 27.988 ms/op
                 getUser·p1.00:   29.590 ms/op

Iteration   3: 4.045 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.191 ms/op
                 getUser·p0.50:   3.826 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   5.497 ms/op
                 getUser·p0.99:   8.102 ms/op
                 getUser·p0.999:  13.681 ms/op
                 getUser·p0.9999: 30.278 ms/op
                 getUser·p1.00:   30.933 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 228151
  mean =      4.205 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 133 
    [ 2.500,  5.000) = 202601 
    [ 5.000,  7.500) = 20322 
    [ 7.500, 10.000) = 3375 
    [10.000, 12.500) = 1130 
    [12.500, 15.000) = 228 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.606 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      6.300 ms/op
     p(99.0000) =      9.224 ms/op
     p(99.9000) =     22.834 ms/op
     p(99.9900) =     29.464 ms/op
     p(99.9990) =     30.563 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.130 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 6.407 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.161 ±(99.9%) 0.021 ms/op
Iteration   1: 4.989 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.359 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.898 ms/op
                 listUser·p0.95:   7.381 ms/op
                 listUser·p0.99:   9.929 ms/op
                 listUser·p0.999:  26.100 ms/op
                 listUser·p0.9999: 28.901 ms/op
                 listUser·p1.00:   30.048 ms/op

Iteration   2: 4.841 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.747 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   6.750 ms/op
                 listUser·p0.99:   10.109 ms/op
                 listUser·p0.999:  21.350 ms/op
                 listUser·p0.9999: 33.068 ms/op
                 listUser·p1.00:   35.062 ms/op

Iteration   3: 5.113 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.907 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   6.382 ms/op
                 listUser·p0.95:   7.987 ms/op
                 listUser·p0.99:   11.420 ms/op
                 listUser·p0.999:  18.842 ms/op
                 listUser·p0.9999: 21.595 ms/op
                 listUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 192676
  mean =      4.978 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 141775 
    [ 5.000,  7.500) = 41787 
    [ 7.500, 10.000) = 6614 
    [10.000, 12.500) = 1555 
    [12.500, 15.000) = 430 
    [15.000, 17.500) = 156 
    [17.500, 20.000) = 131 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.747 ms/op
     p(50.0000) =      4.628 ms/op
     p(90.0000) =      5.808 ms/op
     p(95.0000) =      7.397 ms/op
     p(99.0000) =     10.568 ms/op
     p(99.9000) =     22.107 ms/op
     p(99.9900) =     32.054 ms/op
     p(99.9990) =     34.697 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.551 ± 5.046  ops/ms
ClientPb.existUser                       thrpt       3   7.881 ± 3.367  ops/ms
ClientPb.getUser                         thrpt       3   7.844 ± 1.723  ops/ms
ClientPb.listUser                        thrpt       3   6.729 ± 4.882  ops/ms
ClientPb.createUser                       avgt       3   4.312 ± 1.955   ms/op
ClientPb.existUser                        avgt       3   3.912 ± 1.136   ms/op
ClientPb.getUser                          avgt       3   4.089 ± 1.986   ms/op
ClientPb.listUser                         avgt       3   4.675 ± 2.206   ms/op
ClientPb.createUser                     sample  235986   4.064 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.513           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.846           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.710           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.390           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.217           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.741           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.359           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.194           ms/op
ClientPb.existUser                      sample  240666   3.988 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.681           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.748           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.628           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.603           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.217           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.352           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.686           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.176           ms/op
ClientPb.getUser                        sample  228151   4.205 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.606           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.145           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.300           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.224           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.834           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.464           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.933           ms/op
ClientPb.listUser                       sample  192676   4.978 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.747           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.808           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.397           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.568           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.107           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.054           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.062           ms/op
