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
# Warmup Iteration   1: 1.509 ops/ms
# Warmup Iteration   2: 3.362 ops/ms
# Warmup Iteration   3: 6.537 ops/ms
Iteration   1: 7.143 ops/ms
Iteration   2: 7.836 ops/ms
Iteration   3: 7.399 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.460 ±(99.9%) 6.395 ops/ms [Average]
  (min, avg, max) = (7.143, 7.460, 7.836), stdev = 0.351
  CI (99.9%): [1.065, 13.854] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 2.072 ops/ms
# Warmup Iteration   2: 6.235 ops/ms
# Warmup Iteration   3: 7.706 ops/ms
Iteration   1: 7.908 ops/ms
Iteration   2: 8.737 ops/ms
Iteration   3: 8.381 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.342 ±(99.9%) 7.588 ops/ms [Average]
  (min, avg, max) = (7.908, 8.342, 8.737), stdev = 0.416
  CI (99.9%): [0.754, 15.929] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.046 ops/ms
# Warmup Iteration   2: 5.752 ops/ms
# Warmup Iteration   3: 7.821 ops/ms
Iteration   1: 7.813 ops/ms
Iteration   2: 7.672 ops/ms
Iteration   3: 7.900 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.795 ±(99.9%) 2.097 ops/ms [Average]
  (min, avg, max) = (7.672, 7.795, 7.900), stdev = 0.115
  CI (99.9%): [5.697, 9.892] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.820 ops/ms
# Warmup Iteration   2: 5.472 ops/ms
# Warmup Iteration   3: 6.471 ops/ms
Iteration   1: 6.533 ops/ms
Iteration   2: 6.473 ops/ms
Iteration   3: 6.054 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.353 ±(99.9%) 4.754 ops/ms [Average]
  (min, avg, max) = (6.054, 6.353, 6.533), stdev = 0.261
  CI (99.9%): [1.600, 11.107] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 15.294 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 6.383 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.491 ±(99.9%) 0.006 ms/op
Iteration   1: 4.090 ±(99.9%) 0.010 ms/op
Iteration   2: 3.954 ±(99.9%) 0.009 ms/op
Iteration   3: 4.049 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.031 ±(99.9%) 1.270 ms/op [Average]
  (min, avg, max) = (3.954, 4.031, 4.090), stdev = 0.070
  CI (99.9%): [2.761, 5.301] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 12.844 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.737 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.167 ±(99.9%) 0.003 ms/op
Iteration   1: 4.022 ±(99.9%) 0.004 ms/op
Iteration   2: 3.864 ±(99.9%) 0.013 ms/op
Iteration   3: 3.852 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.913 ±(99.9%) 1.731 ms/op [Average]
  (min, avg, max) = (3.852, 3.913, 4.022), stdev = 0.095
  CI (99.9%): [2.182, 5.644] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 14.869 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.699 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.481 ±(99.9%) 0.008 ms/op
Iteration   1: 4.063 ±(99.9%) 0.012 ms/op
Iteration   2: 4.152 ±(99.9%) 0.009 ms/op
Iteration   3: 4.358 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.191 ±(99.9%) 2.762 ms/op [Average]
  (min, avg, max) = (4.063, 4.191, 4.358), stdev = 0.151
  CI (99.9%): [1.429, 6.953] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 14.591 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 5.729 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.066 ±(99.9%) 0.014 ms/op
Iteration   1: 4.885 ±(99.9%) 0.014 ms/op
Iteration   2: 4.763 ±(99.9%) 0.018 ms/op
Iteration   3: 4.827 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.825 ±(99.9%) 1.115 ms/op [Average]
  (min, avg, max) = (4.763, 4.825, 4.885), stdev = 0.061
  CI (99.9%): [3.710, 5.940] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 13.868 ±(99.9%) 0.193 ms/op
# Warmup Iteration   2: 5.334 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.064 ±(99.9%) 0.025 ms/op
Iteration   1: 4.378 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.933 ms/op
                 createUser·p0.50:   4.076 ms/op
                 createUser·p0.90:   5.300 ms/op
                 createUser·p0.95:   6.480 ms/op
                 createUser·p0.99:   9.142 ms/op
                 createUser·p0.999:  13.827 ms/op
                 createUser·p0.9999: 32.135 ms/op
                 createUser·p1.00:   33.751 ms/op

Iteration   2: 4.307 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.980 ms/op
                 createUser·p0.50:   4.022 ms/op
                 createUser·p0.90:   5.276 ms/op
                 createUser·p0.95:   5.956 ms/op
                 createUser·p0.99:   8.765 ms/op
                 createUser·p0.999:  26.313 ms/op
                 createUser·p0.9999: 31.738 ms/op
                 createUser·p1.00:   32.637 ms/op

Iteration   3: 4.167 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.370 ms/op
                 createUser·p0.50:   3.891 ms/op
                 createUser·p0.90:   4.989 ms/op
                 createUser·p0.95:   5.497 ms/op
                 createUser·p0.99:   8.364 ms/op
                 createUser·p0.999:  16.247 ms/op
                 createUser·p0.9999: 32.481 ms/op
                 createUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 224147
  mean =      4.282 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 217 
    [ 2.500,  5.000) = 195840 
    [ 5.000,  7.500) = 23185 
    [ 7.500, 10.000) = 3883 
    [10.000, 12.500) = 636 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 90 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.370 ms/op
     p(50.0000) =      3.994 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.956 ms/op
     p(99.0000) =      8.749 ms/op
     p(99.9000) =     24.491 ms/op
     p(99.9900) =     32.263 ms/op
     p(99.9990) =     33.670 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.004 ±(99.9%) 0.196 ms/op
# Warmup Iteration   2: 4.332 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.117 ±(99.9%) 0.014 ms/op
Iteration   1: 4.064 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.561 ms/op
                 existUser·p0.50:   3.871 ms/op
                 existUser·p0.90:   4.661 ms/op
                 existUser·p0.95:   5.423 ms/op
                 existUser·p0.99:   7.864 ms/op
                 existUser·p0.999:  20.611 ms/op
                 existUser·p0.9999: 26.149 ms/op
                 existUser·p1.00:   27.296 ms/op

Iteration   2: 4.071 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.993 ms/op
                 existUser·p0.50:   3.899 ms/op
                 existUser·p0.90:   4.727 ms/op
                 existUser·p0.95:   5.530 ms/op
                 existUser·p0.99:   8.323 ms/op
                 existUser·p0.999:  26.557 ms/op
                 existUser·p0.9999: 31.280 ms/op
                 existUser·p1.00:   32.145 ms/op

Iteration   3: 4.252 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.907 ms/op
                 existUser·p0.50:   4.039 ms/op
                 existUser·p0.90:   5.063 ms/op
                 existUser·p0.95:   5.841 ms/op
                 existUser·p0.99:   7.946 ms/op
                 existUser·p0.999:  12.845 ms/op
                 existUser·p0.9999: 31.407 ms/op
                 existUser·p1.00:   32.768 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 232563
  mean =      4.127 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 360 
    [ 2.500,  5.000) = 212388 
    [ 5.000,  7.500) = 16830 
    [ 7.500, 10.000) = 2083 
    [10.000, 12.500) = 529 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.561 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.587 ms/op
     p(99.0000) =      8.061 ms/op
     p(99.9000) =     21.707 ms/op
     p(99.9900) =     30.999 ms/op
     p(99.9990) =     32.388 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 15.858 ±(99.9%) 0.230 ms/op
# Warmup Iteration   2: 5.205 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.218 ±(99.9%) 0.014 ms/op
Iteration   1: 4.132 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.204 ms/op
                 getUser·p0.50:   3.957 ms/op
                 getUser·p0.90:   4.768 ms/op
                 getUser·p0.95:   5.612 ms/op
                 getUser·p0.99:   8.094 ms/op
                 getUser·p0.999:  15.950 ms/op
                 getUser·p0.9999: 31.326 ms/op
                 getUser·p1.00:   33.554 ms/op

Iteration   2: 4.198 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.896 ms/op
                 getUser·p0.50:   4.022 ms/op
                 getUser·p0.90:   4.751 ms/op
                 getUser·p0.95:   5.401 ms/op
                 getUser·p0.99:   8.258 ms/op
                 getUser·p0.999:  24.524 ms/op
                 getUser·p0.9999: 28.664 ms/op
                 getUser·p1.00:   29.917 ms/op

Iteration   3: 4.059 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.597 ms/op
                 getUser·p0.50:   3.903 ms/op
                 getUser·p0.90:   4.571 ms/op
                 getUser·p0.95:   5.317 ms/op
                 getUser·p0.99:   7.676 ms/op
                 getUser·p0.999:  12.730 ms/op
                 getUser·p0.9999: 30.773 ms/op
                 getUser·p1.00:   32.014 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 232475
  mean =      4.129 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 216026 
    [ 5.000,  7.500) = 13375 
    [ 7.500, 10.000) = 2284 
    [10.000, 12.500) = 375 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.597 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      7.987 ms/op
     p(99.9000) =     16.371 ms/op
     p(99.9900) =     30.736 ms/op
     p(99.9990) =     32.357 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 16.058 ±(99.9%) 0.229 ms/op
# Warmup Iteration   2: 6.297 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.007 ±(99.9%) 0.020 ms/op
Iteration   1: 4.960 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.744 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   5.579 ms/op
                 listUser·p0.95:   6.652 ms/op
                 listUser·p0.99:   9.912 ms/op
                 listUser·p0.999:  25.625 ms/op
                 listUser·p0.9999: 30.579 ms/op
                 listUser·p1.00:   31.359 ms/op

Iteration   2: 5.113 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.294 ms/op
                 listUser·p0.50:   4.841 ms/op
                 listUser·p0.90:   6.038 ms/op
                 listUser·p0.95:   7.168 ms/op
                 listUser·p0.99:   9.601 ms/op
                 listUser·p0.999:  22.396 ms/op
                 listUser·p0.9999: 27.123 ms/op
                 listUser·p1.00:   27.492 ms/op

Iteration   3: 4.832 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.445 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   5.480 ms/op
                 listUser·p0.95:   6.218 ms/op
                 listUser·p0.99:   8.847 ms/op
                 listUser·p0.999:  17.624 ms/op
                 listUser·p0.9999: 22.622 ms/op
                 listUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 193236
  mean =      4.965 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 138922 
    [ 5.000,  7.500) = 48087 
    [ 7.500, 10.000) = 4783 
    [10.000, 12.500) = 806 
    [12.500, 15.000) = 225 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.294 ms/op
     p(50.0000) =      4.702 ms/op
     p(90.0000) =      5.677 ms/op
     p(95.0000) =      6.742 ms/op
     p(99.0000) =      9.421 ms/op
     p(99.9000) =     22.610 ms/op
     p(99.9900) =     29.132 ms/op
     p(99.9990) =     31.267 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.460 ± 6.395  ops/ms
ClientPb.existUser                       thrpt       3   8.342 ± 7.588  ops/ms
ClientPb.getUser                         thrpt       3   7.795 ± 2.097  ops/ms
ClientPb.listUser                        thrpt       3   6.353 ± 4.754  ops/ms
ClientPb.createUser                       avgt       3   4.031 ± 1.270   ms/op
ClientPb.existUser                        avgt       3   3.913 ± 1.731   ms/op
ClientPb.getUser                          avgt       3   4.191 ± 2.762   ms/op
ClientPb.listUser                         avgt       3   4.825 ± 1.115   ms/op
ClientPb.createUser                     sample  224147   4.282 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.370           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.994           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.177           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.956           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.749           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.491           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.263           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.751           ms/op
ClientPb.existUser                      sample  232563   4.127 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.561           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.928           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.841           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.587           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.061           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.707           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.999           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.768           ms/op
ClientPb.getUser                        sample  232475   4.129 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.597           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.953           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.710           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.472           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.987           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.371           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.736           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.554           ms/op
ClientPb.listUser                       sample  193236   4.965 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.294           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.677           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.742           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.421           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.610           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.132           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.359           ms/op
