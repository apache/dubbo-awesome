# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.094 ops/ms
# Warmup Iteration   2: 5.749 ops/ms
# Warmup Iteration   3: 8.422 ops/ms
Iteration   1: 9.441 ops/ms
Iteration   2: 9.211 ops/ms
Iteration   3: 9.356 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.336 ±(99.9%) 2.128 ops/ms [Average]
  (min, avg, max) = (9.211, 9.336, 9.441), stdev = 0.117
  CI (99.9%): [7.208, 11.464] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.277 ops/ms
# Warmup Iteration   2: 8.524 ops/ms
# Warmup Iteration   3: 9.762 ops/ms
Iteration   1: 9.945 ops/ms
Iteration   2: 9.669 ops/ms
Iteration   3: 9.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.805 ±(99.9%) 2.516 ops/ms [Average]
  (min, avg, max) = (9.669, 9.805, 9.945), stdev = 0.138
  CI (99.9%): [7.288, 12.321] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.803 ops/ms
# Warmup Iteration   2: 8.146 ops/ms
# Warmup Iteration   3: 9.277 ops/ms
Iteration   1: 9.762 ops/ms
Iteration   2: 9.631 ops/ms
Iteration   3: 9.424 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.606 ±(99.9%) 3.105 ops/ms [Average]
  (min, avg, max) = (9.424, 9.606, 9.762), stdev = 0.170
  CI (99.9%): [6.500, 12.711] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.069 ops/ms
# Warmup Iteration   2: 7.676 ops/ms
# Warmup Iteration   3: 7.731 ops/ms
Iteration   1: 8.196 ops/ms
Iteration   2: 8.113 ops/ms
Iteration   3: 8.329 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.213 ±(99.9%) 1.993 ops/ms [Average]
  (min, avg, max) = (8.113, 8.213, 8.329), stdev = 0.109
  CI (99.9%): [6.220, 10.206] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.349 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.665 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.493 ±(99.9%) 0.006 ms/op
Iteration   1: 3.424 ±(99.9%) 0.005 ms/op
Iteration   2: 3.402 ±(99.9%) 0.004 ms/op
Iteration   3: 3.342 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.389 ±(99.9%) 0.773 ms/op [Average]
  (min, avg, max) = (3.342, 3.389, 3.424), stdev = 0.042
  CI (99.9%): [2.616, 4.162] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.540 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.514 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.283 ±(99.9%) 0.007 ms/op
Iteration   1: 3.204 ±(99.9%) 0.009 ms/op
Iteration   2: 3.249 ±(99.9%) 0.003 ms/op
Iteration   3: 3.171 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.208 ±(99.9%) 0.713 ms/op [Average]
  (min, avg, max) = (3.171, 3.208, 3.249), stdev = 0.039
  CI (99.9%): [2.495, 3.920] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.697 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.608 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.443 ±(99.9%) 0.006 ms/op
Iteration   1: 3.341 ±(99.9%) 0.013 ms/op
Iteration   2: 3.517 ±(99.9%) 0.008 ms/op
Iteration   3: 3.330 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.396 ±(99.9%) 1.914 ms/op [Average]
  (min, avg, max) = (3.330, 3.396, 3.517), stdev = 0.105
  CI (99.9%): [1.482, 5.311] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.516 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.347 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.942 ±(99.9%) 0.010 ms/op
Iteration   1: 3.866 ±(99.9%) 0.013 ms/op
Iteration   2: 3.866 ±(99.9%) 0.013 ms/op
Iteration   3: 3.819 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.850 ±(99.9%) 0.491 ms/op [Average]
  (min, avg, max) = (3.819, 3.850, 3.866), stdev = 0.027
  CI (99.9%): [3.359, 4.342] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.972 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 4.032 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.584 ±(99.9%) 0.013 ms/op
Iteration   1: 3.452 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.057 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.973 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   6.183 ms/op
                 createUser·p0.999:  20.722 ms/op
                 createUser·p0.9999: 23.976 ms/op
                 createUser·p1.00:   24.871 ms/op

Iteration   2: 3.546 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.212 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   4.612 ms/op
                 createUser·p0.99:   6.382 ms/op
                 createUser·p0.999:  9.896 ms/op
                 createUser·p0.9999: 27.656 ms/op
                 createUser·p1.00:   28.574 ms/op

Iteration   3: 3.461 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.544 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  19.898 ms/op
                 createUser·p0.9999: 27.083 ms/op
                 createUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275154
  mean =      3.486 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15381 
    [ 2.500,  5.000) = 252522 
    [ 5.000,  7.500) = 6096 
    [ 7.500, 10.000) = 775 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     17.198 ms/op
     p(99.9900) =     27.099 ms/op
     p(99.9990) =     27.869 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.231 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.676 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.380 ±(99.9%) 0.009 ms/op
Iteration   1: 3.297 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.384 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  11.160 ms/op
                 existUser·p0.9999: 23.537 ms/op
                 existUser·p1.00:   24.510 ms/op

Iteration   2: 3.180 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.667 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.661 ms/op
                 existUser·p0.999:  12.583 ms/op
                 existUser·p0.9999: 27.817 ms/op
                 existUser·p1.00:   29.295 ms/op

Iteration   3: 3.342 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.153 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   4.522 ms/op
                 existUser·p0.99:   5.898 ms/op
                 existUser·p0.999:  20.496 ms/op
                 existUser·p0.9999: 25.625 ms/op
                 existUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293268
  mean =      3.272 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11669 
    [ 2.500,  5.000) = 275964 
    [ 5.000,  7.500) = 4677 
    [ 7.500, 10.000) = 486 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 112 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.153 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     13.238 ms/op
     p(99.9900) =     27.252 ms/op
     p(99.9990) =     29.137 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.507 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.845 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.451 ±(99.9%) 0.009 ms/op
Iteration   1: 3.423 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.632 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   6.808 ms/op
                 getUser·p0.999:  19.825 ms/op
                 getUser·p0.9999: 22.031 ms/op
                 getUser·p1.00:   23.101 ms/op

Iteration   2: 3.389 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.659 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   6.554 ms/op
                 getUser·p0.999:  20.843 ms/op
                 getUser·p0.9999: 30.759 ms/op
                 getUser·p1.00:   31.064 ms/op

Iteration   3: 3.499 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.550 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.977 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   6.775 ms/op
                 getUser·p0.999:  17.069 ms/op
                 getUser·p0.9999: 25.849 ms/op
                 getUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279024
  mean =      3.436 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4536 
    [ 2.500,  5.000) = 264958 
    [ 5.000,  7.500) = 8143 
    [ 7.500, 10.000) = 933 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 142 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.550 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     18.280 ms/op
     p(99.9900) =     28.544 ms/op
     p(99.9990) =     30.907 ms/op
     p(99.9999) =     31.064 ms/op
    p(100.0000) =     31.064 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.160 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.315 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.044 ±(99.9%) 0.013 ms/op
Iteration   1: 4.034 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.665 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   7.208 ms/op
                 listUser·p0.999:  21.548 ms/op
                 listUser·p0.9999: 23.429 ms/op
                 listUser·p1.00:   24.084 ms/op

Iteration   2: 3.968 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.509 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  15.057 ms/op
                 listUser·p0.9999: 16.776 ms/op
                 listUser·p1.00:   18.776 ms/op

Iteration   3: 3.955 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.347 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  14.270 ms/op
                 listUser·p0.9999: 17.397 ms/op
                 listUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240610
  mean =      3.985 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53 
    [ 2.500,  5.000) = 232470 
    [ 5.000,  7.500) = 5835 
    [ 7.500, 10.000) = 1449 
    [10.000, 12.500) = 265 
    [12.500, 15.000) = 265 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.665 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      7.340 ms/op
     p(99.9000) =     15.162 ms/op
     p(99.9900) =     22.872 ms/op
     p(99.9990) =     23.952 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.336 ± 2.128  ops/ms
ClientPb.existUser                       thrpt       3   9.805 ± 2.516  ops/ms
ClientPb.getUser                         thrpt       3   9.606 ± 3.105  ops/ms
ClientPb.listUser                        thrpt       3   8.213 ± 1.993  ops/ms
ClientPb.createUser                       avgt       3   3.389 ± 0.773   ms/op
ClientPb.existUser                        avgt       3   3.208 ± 0.713   ms/op
ClientPb.getUser                          avgt       3   3.396 ± 1.914   ms/op
ClientPb.listUser                         avgt       3   3.850 ± 0.491   ms/op
ClientPb.createUser                     sample  275154   3.486 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.057           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.375           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.104           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.407           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.111           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.198           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.099           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.574           ms/op
ClientPb.existUser                      sample  293268   3.272 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.153           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.183           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.043           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.628           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.238           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.252           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.295           ms/op
ClientPb.getUser                        sample  279024   3.436 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.550           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.293           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.190           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.685           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.280           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.544           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.064           ms/op
ClientPb.listUser                       sample  240610   3.985 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.665           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.340           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.162           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.872           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.084           ms/op
