# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.066 ops/ms
# Warmup Iteration   2: 4.750 ops/ms
# Warmup Iteration   3: 8.153 ops/ms
Iteration   1: 8.966 ops/ms
Iteration   2: 9.566 ops/ms
Iteration   3: 9.680 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.404 ±(99.9%) 6.992 ops/ms [Average]
  (min, avg, max) = (8.966, 9.404, 9.680), stdev = 0.383
  CI (99.9%): [2.412, 16.396] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.548 ops/ms
# Warmup Iteration   2: 9.118 ops/ms
# Warmup Iteration   3: 9.654 ops/ms
Iteration   1: 9.852 ops/ms
Iteration   2: 9.721 ops/ms
Iteration   3: 9.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.809 ±(99.9%) 1.388 ops/ms [Average]
  (min, avg, max) = (9.721, 9.809, 9.854), stdev = 0.076
  CI (99.9%): [8.421, 11.197] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.861 ops/ms
# Warmup Iteration   2: 8.396 ops/ms
# Warmup Iteration   3: 8.973 ops/ms
Iteration   1: 9.224 ops/ms
Iteration   2: 9.394 ops/ms
Iteration   3: 9.134 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.251 ±(99.9%) 2.407 ops/ms [Average]
  (min, avg, max) = (9.134, 9.251, 9.394), stdev = 0.132
  CI (99.9%): [6.844, 11.657] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.201 ops/ms
# Warmup Iteration   2: 7.103 ops/ms
# Warmup Iteration   3: 7.851 ops/ms
Iteration   1: 8.082 ops/ms
Iteration   2: 8.033 ops/ms
Iteration   3: 8.172 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.096 ±(99.9%) 1.287 ops/ms [Average]
  (min, avg, max) = (8.033, 8.096, 8.172), stdev = 0.071
  CI (99.9%): [6.809, 9.383] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.869 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.668 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.687 ±(99.9%) 0.005 ms/op
Iteration   1: 3.309 ±(99.9%) 0.009 ms/op
Iteration   2: 3.292 ±(99.9%) 0.008 ms/op
Iteration   3: 3.514 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.372 ±(99.9%) 2.254 ms/op [Average]
  (min, avg, max) = (3.292, 3.372, 3.514), stdev = 0.124
  CI (99.9%): [1.118, 5.625] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.865 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.511 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.246 ±(99.9%) 0.007 ms/op
Iteration   1: 3.305 ±(99.9%) 0.010 ms/op
Iteration   2: 3.251 ±(99.9%) 0.006 ms/op
Iteration   3: 3.205 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.254 ±(99.9%) 0.917 ms/op [Average]
  (min, avg, max) = (3.205, 3.254, 3.305), stdev = 0.050
  CI (99.9%): [2.337, 4.171] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.888 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.754 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.702 ±(99.9%) 0.002 ms/op
Iteration   1: 3.394 ±(99.9%) 0.006 ms/op
Iteration   2: 3.449 ±(99.9%) 0.007 ms/op
Iteration   3: 3.407 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.417 ±(99.9%) 0.524 ms/op [Average]
  (min, avg, max) = (3.394, 3.417, 3.449), stdev = 0.029
  CI (99.9%): [2.893, 3.940] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.070 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.327 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.972 ±(99.9%) 0.013 ms/op
Iteration   1: 4.026 ±(99.9%) 0.008 ms/op
Iteration   2: 3.974 ±(99.9%) 0.009 ms/op
Iteration   3: 3.941 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.980 ±(99.9%) 0.780 ms/op [Average]
  (min, avg, max) = (3.941, 3.980, 4.026), stdev = 0.043
  CI (99.9%): [3.200, 4.760] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.677 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.031 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.779 ±(99.9%) 0.015 ms/op
Iteration   1: 3.275 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.374 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   5.054 ms/op
                 createUser·p0.999:  9.855 ms/op
                 createUser·p0.9999: 26.779 ms/op
                 createUser·p1.00:   28.017 ms/op

Iteration   2: 3.486 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.317 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   4.178 ms/op
                 createUser·p0.95:   4.653 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  21.495 ms/op
                 createUser·p0.9999: 25.389 ms/op
                 createUser·p1.00:   26.739 ms/op

Iteration   3: 3.412 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.013 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.579 ms/op
                 createUser·p0.999:  19.202 ms/op
                 createUser·p0.9999: 40.108 ms/op
                 createUser·p1.00:   40.632 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283271
  mean =      3.389 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 278104 
    [ 5.000, 10.000) = 4725 
    [10.000, 15.000) = 76 
    [15.000, 20.000) = 83 
    [20.000, 25.000) = 185 
    [25.000, 30.000) = 66 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 17 
    [40.000, 45.000) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.013 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     19.995 ms/op
     p(99.9900) =     39.323 ms/op
     p(99.9990) =     40.381 ms/op
     p(99.9999) =     40.632 ms/op
    p(100.0000) =     40.632 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.399 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.586 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.345 ±(99.9%) 0.009 ms/op
Iteration   1: 3.351 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.278 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.805 ms/op
                 existUser·p0.95:   4.489 ms/op
                 existUser·p0.99:   6.357 ms/op
                 existUser·p0.999:  18.763 ms/op
                 existUser·p0.9999: 22.994 ms/op
                 existUser·p1.00:   23.462 ms/op

Iteration   2: 3.197 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.495 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  14.795 ms/op
                 existUser·p0.9999: 25.067 ms/op
                 existUser·p1.00:   25.985 ms/op

Iteration   3: 3.246 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.509 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  10.158 ms/op
                 existUser·p0.9999: 23.434 ms/op
                 existUser·p1.00:   23.822 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294071
  mean =      3.263 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15590 
    [ 2.500,  5.000) = 272755 
    [ 5.000,  7.500) = 4945 
    [ 7.500, 10.000) = 411 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.278 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     14.794 ms/op
     p(99.9900) =     24.478 ms/op
     p(99.9990) =     25.530 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.405 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.753 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.473 ±(99.9%) 0.011 ms/op
Iteration   1: 3.479 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.733 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   7.119 ms/op
                 getUser·p0.999:  11.534 ms/op
                 getUser·p0.9999: 28.816 ms/op
                 getUser·p1.00:   30.245 ms/op

Iteration   2: 3.354 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.653 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   5.214 ms/op
                 getUser·p0.999:  10.109 ms/op
                 getUser·p0.9999: 24.296 ms/op
                 getUser·p1.00:   24.773 ms/op

Iteration   3: 3.474 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.876 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   4.010 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   6.316 ms/op
                 getUser·p0.999:  20.447 ms/op
                 getUser·p0.9999: 26.994 ms/op
                 getUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279449
  mean =      3.434 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6420 
    [ 2.500,  5.000) = 265214 
    [ 5.000,  7.500) = 6702 
    [ 7.500, 10.000) = 739 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.653 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =     10.830 ms/op
     p(99.9900) =     27.596 ms/op
     p(99.9990) =     29.524 ms/op
     p(99.9999) =     30.245 ms/op
    p(100.0000) =     30.245 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.839 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.390 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.100 ±(99.9%) 0.012 ms/op
Iteration   1: 4.001 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.874 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  19.894 ms/op
                 listUser·p0.9999: 23.101 ms/op
                 listUser·p1.00:   23.593 ms/op

Iteration   2: 3.940 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.118 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  15.019 ms/op
                 listUser·p0.9999: 16.136 ms/op
                 listUser·p1.00:   17.007 ms/op

Iteration   3: 3.992 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.339 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   7.300 ms/op
                 listUser·p0.999:  17.826 ms/op
                 listUser·p0.9999: 25.166 ms/op
                 listUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241179
  mean =      3.977 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 234579 
    [ 5.000,  7.500) = 4565 
    [ 7.500, 10.000) = 1039 
    [10.000, 12.500) = 393 
    [12.500, 15.000) = 209 
    [15.000, 17.500) = 155 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.874 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      7.250 ms/op
     p(99.9000) =     16.613 ms/op
     p(99.9900) =     23.724 ms/op
     p(99.9990) =     25.906 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.404 ± 6.992  ops/ms
ClientPb.existUser                       thrpt       3   9.809 ± 1.388  ops/ms
ClientPb.getUser                         thrpt       3   9.251 ± 2.407  ops/ms
ClientPb.listUser                        thrpt       3   8.096 ± 1.287  ops/ms
ClientPb.createUser                       avgt       3   3.372 ± 2.254   ms/op
ClientPb.existUser                        avgt       3   3.254 ± 0.917   ms/op
ClientPb.getUser                          avgt       3   3.417 ± 0.524   ms/op
ClientPb.listUser                         avgt       3   3.980 ± 0.780   ms/op
ClientPb.createUser                     sample  283271   3.389 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.013           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.281           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.846           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.268           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.595           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.995           ms/op
ClientPb.createUser:createUser·p0.9999  sample          39.323           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.632           ms/op
ClientPb.existUser                      sample  294071   3.263 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.278           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.191           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.531           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.867           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.759           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.794           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.478           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.985           ms/op
ClientPb.getUser                        sample  279449   3.434 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.653           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.326           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.817           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.157           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.562           ms/op
ClientPb.getUser:getUser·p0.999         sample          10.830           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.596           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.245           ms/op
ClientPb.listUser                       sample  241179   3.977 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.874           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.571           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.250           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.613           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.724           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.182           ms/op
