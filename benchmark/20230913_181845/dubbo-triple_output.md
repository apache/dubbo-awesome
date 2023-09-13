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
# Warmup Iteration   1: 2.505 ops/ms
# Warmup Iteration   2: 5.884 ops/ms
# Warmup Iteration   3: 9.050 ops/ms
Iteration   1: 9.697 ops/ms
Iteration   2: 9.929 ops/ms
Iteration   3: 9.691 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.772 ±(99.9%) 2.475 ops/ms [Average]
  (min, avg, max) = (9.691, 9.772, 9.929), stdev = 0.136
  CI (99.9%): [7.297, 12.247] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.464 ops/ms
# Warmup Iteration   2: 8.702 ops/ms
# Warmup Iteration   3: 9.556 ops/ms
Iteration   1: 9.716 ops/ms
Iteration   2: 9.902 ops/ms
Iteration   3: 10.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.910 ±(99.9%) 3.624 ops/ms [Average]
  (min, avg, max) = (9.716, 9.910, 10.113), stdev = 0.199
  CI (99.9%): [6.286, 13.535] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.100 ops/ms
# Warmup Iteration   2: 8.538 ops/ms
# Warmup Iteration   3: 9.237 ops/ms
Iteration   1: 9.704 ops/ms
Iteration   2: 9.258 ops/ms
Iteration   3: 9.682 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.548 ±(99.9%) 4.587 ops/ms [Average]
  (min, avg, max) = (9.258, 9.548, 9.704), stdev = 0.251
  CI (99.9%): [4.961, 14.135] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.398 ops/ms
# Warmup Iteration   2: 7.129 ops/ms
# Warmup Iteration   3: 8.234 ops/ms
Iteration   1: 8.377 ops/ms
Iteration   2: 8.122 ops/ms
Iteration   3: 8.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.314 ±(99.9%) 3.104 ops/ms [Average]
  (min, avg, max) = (8.122, 8.314, 8.444), stdev = 0.170
  CI (99.9%): [5.210, 11.419] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.265 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.611 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.526 ±(99.9%) 0.004 ms/op
Iteration   1: 3.474 ±(99.9%) 0.003 ms/op
Iteration   2: 3.319 ±(99.9%) 0.005 ms/op
Iteration   3: 3.246 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.346 ±(99.9%) 2.129 ms/op [Average]
  (min, avg, max) = (3.246, 3.346, 3.474), stdev = 0.117
  CI (99.9%): [1.217, 5.476] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.956 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.382 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.267 ±(99.9%) 0.004 ms/op
Iteration   1: 3.190 ±(99.9%) 0.008 ms/op
Iteration   2: 3.229 ±(99.9%) 0.007 ms/op
Iteration   3: 3.194 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.204 ±(99.9%) 0.387 ms/op [Average]
  (min, avg, max) = (3.190, 3.204, 3.229), stdev = 0.021
  CI (99.9%): [2.817, 3.591] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.373 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.517 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.422 ±(99.9%) 0.006 ms/op
Iteration   1: 3.365 ±(99.9%) 0.003 ms/op
Iteration   2: 3.328 ±(99.9%) 0.003 ms/op
Iteration   3: 3.195 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.296 ±(99.9%) 1.631 ms/op [Average]
  (min, avg, max) = (3.195, 3.296, 3.365), stdev = 0.089
  CI (99.9%): [1.665, 4.927] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.836 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.244 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.949 ±(99.9%) 0.006 ms/op
Iteration   1: 3.813 ±(99.9%) 0.005 ms/op
Iteration   2: 3.819 ±(99.9%) 0.006 ms/op
Iteration   3: 3.831 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.821 ±(99.9%) 0.173 ms/op [Average]
  (min, avg, max) = (3.813, 3.821, 3.831), stdev = 0.009
  CI (99.9%): [3.648, 3.994] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.713 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.803 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.378 ±(99.9%) 0.010 ms/op
Iteration   1: 3.293 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.333 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  20.673 ms/op
                 createUser·p0.9999: 31.139 ms/op
                 createUser·p1.00:   34.210 ms/op

Iteration   2: 3.278 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.198 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  10.231 ms/op
                 createUser·p0.9999: 25.976 ms/op
                 createUser·p1.00:   27.001 ms/op

Iteration   3: 3.370 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.393 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.932 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   6.414 ms/op
                 createUser·p0.999:  18.387 ms/op
                 createUser·p0.9999: 29.541 ms/op
                 createUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 289507
  mean =      3.313 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13778 
    [ 2.500,  5.000) = 268072 
    [ 5.000,  7.500) = 6253 
    [ 7.500, 10.000) = 849 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.198 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     19.972 ms/op
     p(99.9900) =     29.032 ms/op
     p(99.9990) =     34.151 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.978 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.353 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.337 ±(99.9%) 0.011 ms/op
Iteration   1: 3.161 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.217 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   5.939 ms/op
                 existUser·p0.999:  11.502 ms/op
                 existUser·p0.9999: 22.905 ms/op
                 existUser·p1.00:   24.084 ms/op

Iteration   2: 3.280 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.286 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   6.693 ms/op
                 existUser·p0.999:  16.436 ms/op
                 existUser·p0.9999: 29.696 ms/op
                 existUser·p1.00:   30.638 ms/op

Iteration   3: 3.278 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.063 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   4.092 ms/op
                 existUser·p0.99:   6.308 ms/op
                 existUser·p0.999:  9.615 ms/op
                 existUser·p0.9999: 23.739 ms/op
                 existUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 296299
  mean =      3.238 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12758 
    [ 2.500,  5.000) = 275239 
    [ 5.000,  7.500) = 7035 
    [ 7.500, 10.000) = 795 
    [10.000, 12.500) = 178 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     12.324 ms/op
     p(99.9900) =     28.479 ms/op
     p(99.9990) =     30.574 ms/op
     p(99.9999) =     30.638 ms/op
    p(100.0000) =     30.638 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.338 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.641 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.470 ±(99.9%) 0.011 ms/op
Iteration   1: 3.512 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.591 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   4.366 ms/op
                 getUser·p0.95:   5.243 ms/op
                 getUser·p0.99:   6.988 ms/op
                 getUser·p0.999:  20.217 ms/op
                 getUser·p0.9999: 33.456 ms/op
                 getUser·p1.00:   34.472 ms/op

Iteration   2: 3.193 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.427 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   5.689 ms/op
                 getUser·p0.999:  12.083 ms/op
                 getUser·p0.9999: 23.462 ms/op
                 getUser·p1.00:   24.674 ms/op

Iteration   3: 3.371 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.595 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   6.627 ms/op
                 getUser·p0.999:  16.736 ms/op
                 getUser·p0.9999: 31.885 ms/op
                 getUser·p1.00:   32.375 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 285990
  mean =      3.354 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12121 
    [ 2.500,  5.000) = 263986 
    [ 5.000,  7.500) = 8472 
    [ 7.500, 10.000) = 900 
    [10.000, 12.500) = 208 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.427 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     16.810 ms/op
     p(99.9900) =     32.965 ms/op
     p(99.9990) =     34.285 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.945 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.236 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.872 ±(99.9%) 0.012 ms/op
Iteration   1: 3.816 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.831 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.125 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   7.291 ms/op
                 listUser·p0.999:  15.839 ms/op
                 listUser·p0.9999: 23.187 ms/op
                 listUser·p1.00:   23.495 ms/op

Iteration   2: 3.935 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.396 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   7.833 ms/op
                 listUser·p0.999:  13.779 ms/op
                 listUser·p0.9999: 14.836 ms/op
                 listUser·p1.00:   16.024 ms/op

Iteration   3: 3.886 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   7.633 ms/op
                 listUser·p0.999:  14.893 ms/op
                 listUser·p0.9999: 25.494 ms/op
                 listUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 247290
  mean =      3.879 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 238573 
    [ 5.000,  7.500) = 6020 
    [ 7.500, 10.000) = 1670 
    [10.000, 12.500) = 447 
    [12.500, 15.000) = 367 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.831 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      7.660 ms/op
     p(99.9000) =     14.191 ms/op
     p(99.9900) =     23.244 ms/op
     p(99.9990) =     25.609 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.772 ± 2.475  ops/ms
ClientPb.existUser                       thrpt       3   9.910 ± 3.624  ops/ms
ClientPb.getUser                         thrpt       3   9.548 ± 4.587  ops/ms
ClientPb.listUser                        thrpt       3   8.314 ± 3.104  ops/ms
ClientPb.createUser                       avgt       3   3.346 ± 2.129   ms/op
ClientPb.existUser                        avgt       3   3.204 ± 0.387   ms/op
ClientPb.getUser                          avgt       3   3.296 ± 1.631   ms/op
ClientPb.listUser                         avgt       3   3.821 ± 0.173   ms/op
ClientPb.createUser                     sample  289507   3.313 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.198           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.756           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.194           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.078           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.972           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.032           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.210           ms/op
ClientPb.existUser                      sample  296299   3.238 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.063           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.621           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.014           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.463           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.324           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.479           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.638           ms/op
ClientPb.getUser                        sample  285990   3.354 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.427           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.817           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.538           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.767           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.810           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.965           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.472           ms/op
ClientPb.listUser                       sample  247290   3.879 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.831           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.740           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.227           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.660           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.191           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.244           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.756           ms/op
