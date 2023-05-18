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
# Warmup Iteration   1: 2.404 ops/ms
# Warmup Iteration   2: 5.800 ops/ms
# Warmup Iteration   3: 8.915 ops/ms
Iteration   1: 9.778 ops/ms
Iteration   2: 9.887 ops/ms
Iteration   3: 10.063 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.909 ±(99.9%) 2.627 ops/ms [Average]
  (min, avg, max) = (9.778, 9.909, 10.063), stdev = 0.144
  CI (99.9%): [7.282, 12.537] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.197 ops/ms
# Warmup Iteration   2: 9.193 ops/ms
# Warmup Iteration   3: 9.912 ops/ms
Iteration   1: 10.379 ops/ms
Iteration   2: 10.344 ops/ms
Iteration   3: 10.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.434 ±(99.9%) 2.298 ops/ms [Average]
  (min, avg, max) = (10.344, 10.434, 10.578), stdev = 0.126
  CI (99.9%): [8.135, 12.732] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.236 ops/ms
# Warmup Iteration   2: 9.091 ops/ms
# Warmup Iteration   3: 9.723 ops/ms
Iteration   1: 9.629 ops/ms
Iteration   2: 10.258 ops/ms
Iteration   3: 9.865 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.917 ±(99.9%) 5.802 ops/ms [Average]
  (min, avg, max) = (9.629, 9.917, 10.258), stdev = 0.318
  CI (99.9%): [4.115, 15.719] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.180 ops/ms
# Warmup Iteration   2: 7.428 ops/ms
# Warmup Iteration   3: 8.520 ops/ms
Iteration   1: 8.404 ops/ms
Iteration   2: 8.385 ops/ms
Iteration   3: 8.290 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.359 ±(99.9%) 1.117 ops/ms [Average]
  (min, avg, max) = (8.290, 8.359, 8.404), stdev = 0.061
  CI (99.9%): [7.242, 9.476] (assumes normal distribution)


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
# Warmup Iteration   1: 7.086 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.512 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.314 ±(99.9%) 0.004 ms/op
Iteration   1: 3.210 ±(99.9%) 0.004 ms/op
Iteration   2: 3.265 ±(99.9%) 0.008 ms/op
Iteration   3: 3.111 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.195 ±(99.9%) 1.420 ms/op [Average]
  (min, avg, max) = (3.111, 3.195, 3.265), stdev = 0.078
  CI (99.9%): [1.775, 4.616] (assumes normal distribution)


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
# Warmup Iteration   1: 8.032 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.399 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.002 ms/op
Iteration   1: 3.109 ±(99.9%) 0.006 ms/op
Iteration   2: 3.033 ±(99.9%) 0.009 ms/op
Iteration   3: 3.208 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.117 ±(99.9%) 1.595 ms/op [Average]
  (min, avg, max) = (3.033, 3.117, 3.208), stdev = 0.087
  CI (99.9%): [1.522, 4.712] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.600 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.577 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.309 ±(99.9%) 0.002 ms/op
Iteration   1: 3.244 ±(99.9%) 0.002 ms/op
Iteration   2: 3.239 ±(99.9%) 0.004 ms/op
Iteration   3: 3.232 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.238 ±(99.9%) 0.107 ms/op [Average]
  (min, avg, max) = (3.232, 3.238, 3.244), stdev = 0.006
  CI (99.9%): [3.132, 3.345] (assumes normal distribution)


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
# Warmup Iteration   1: 9.012 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.065 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.970 ±(99.9%) 0.005 ms/op
Iteration   1: 3.795 ±(99.9%) 0.006 ms/op
Iteration   2: 3.932 ±(99.9%) 0.003 ms/op
Iteration   3: 3.770 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.832 ±(99.9%) 1.586 ms/op [Average]
  (min, avg, max) = (3.770, 3.832, 3.932), stdev = 0.087
  CI (99.9%): [2.246, 5.419] (assumes normal distribution)


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
# Warmup Iteration   1: 8.374 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.914 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.185 ±(99.9%) 0.008 ms/op
Iteration   1: 3.221 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.468 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   4.170 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  14.610 ms/op
                 createUser·p0.9999: 21.201 ms/op
                 createUser·p1.00:   21.823 ms/op

Iteration   2: 3.131 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.354 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.285 ms/op
                 createUser·p0.95:   3.584 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  21.487 ms/op
                 createUser·p0.9999: 24.052 ms/op
                 createUser·p1.00:   24.576 ms/op

Iteration   3: 3.174 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.108 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.326 ms/op
                 createUser·p0.95:   3.609 ms/op
                 createUser·p0.99:   6.021 ms/op
                 createUser·p0.999:  15.816 ms/op
                 createUser·p0.9999: 19.263 ms/op
                 createUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302190
  mean =      3.175 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24080 
    [ 2.500,  5.000) = 272080 
    [ 5.000,  7.500) = 5031 
    [ 7.500, 10.000) = 468 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 131 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.334 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     17.617 ms/op
     p(99.9900) =     23.495 ms/op
     p(99.9990) =     24.445 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


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
# Warmup Iteration   1: 7.253 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.325 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.190 ±(99.9%) 0.008 ms/op
Iteration   1: 3.098 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.405 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  12.201 ms/op
                 existUser·p0.9999: 20.393 ms/op
                 existUser·p1.00:   20.808 ms/op

Iteration   2: 3.248 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.690 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  10.511 ms/op
                 existUser·p0.9999: 27.951 ms/op
                 existUser·p1.00:   28.705 ms/op

Iteration   3: 3.084 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.421 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.449 ms/op
                 existUser·p0.99:   5.438 ms/op
                 existUser·p0.999:  15.308 ms/op
                 existUser·p0.9999: 22.446 ms/op
                 existUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305491
  mean =      3.141 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17404 
    [ 2.500,  5.000) = 282803 
    [ 5.000,  7.500) = 4354 
    [ 7.500, 10.000) = 520 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     12.554 ms/op
     p(99.9900) =     27.194 ms/op
     p(99.9990) =     28.146 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


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
# Warmup Iteration   1: 7.469 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.406 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.409 ±(99.9%) 0.011 ms/op
Iteration   1: 3.215 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.526 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   6.332 ms/op
                 getUser·p0.999:  13.048 ms/op
                 getUser·p0.9999: 21.039 ms/op
                 getUser·p1.00:   22.577 ms/op

Iteration   2: 3.100 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.716 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.334 ms/op
                 getUser·p0.95:   3.625 ms/op
                 getUser·p0.99:   5.439 ms/op
                 getUser·p0.999:  10.839 ms/op
                 getUser·p0.9999: 25.418 ms/op
                 getUser·p1.00:   26.313 ms/op

Iteration   3: 3.253 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.348 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   5.194 ms/op
                 getUser·p0.999:  9.896 ms/op
                 getUser·p0.9999: 23.014 ms/op
                 getUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 301039
  mean =      3.188 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22617 
    [ 2.500,  5.000) = 272712 
    [ 5.000,  7.500) = 4909 
    [ 7.500, 10.000) = 432 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.348 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =     12.201 ms/op
     p(99.9900) =     23.936 ms/op
     p(99.9990) =     26.083 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


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
# Warmup Iteration   1: 9.231 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.224 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.859 ±(99.9%) 0.012 ms/op
Iteration   1: 3.824 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.249 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.576 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  15.761 ms/op
                 listUser·p0.9999: 19.277 ms/op
                 listUser·p1.00:   19.956 ms/op

Iteration   2: 3.745 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.421 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   6.586 ms/op
                 listUser·p0.999:  13.464 ms/op
                 listUser·p0.9999: 19.771 ms/op
                 listUser·p1.00:   21.725 ms/op

Iteration   3: 3.715 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.134 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.170 ms/op
                 listUser·p0.99:   6.529 ms/op
                 listUser·p0.999:  13.238 ms/op
                 listUser·p0.9999: 15.270 ms/op
                 listUser·p1.00:   15.335 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255044
  mean =      3.761 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 84 
    [ 2.500,  5.000) = 248182 
    [ 5.000,  7.500) = 5113 
    [ 7.500, 10.000) = 986 
    [10.000, 12.500) = 241 
    [12.500, 15.000) = 279 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.249 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     13.582 ms/op
     p(99.9900) =     19.153 ms/op
     p(99.9990) =     21.674 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.909 ± 2.627  ops/ms
ClientPb.existUser                       thrpt       3  10.434 ± 2.298  ops/ms
ClientPb.getUser                         thrpt       3   9.917 ± 5.802  ops/ms
ClientPb.listUser                        thrpt       3   8.359 ± 1.117  ops/ms
ClientPb.createUser                       avgt       3   3.195 ± 1.420   ms/op
ClientPb.existUser                        avgt       3   3.117 ± 1.595   ms/op
ClientPb.getUser                          avgt       3   3.238 ± 0.107   ms/op
ClientPb.listUser                         avgt       3   3.832 ± 1.586   ms/op
ClientPb.createUser                     sample  302190   3.175 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.108           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.334           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.695           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.947           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.617           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.495           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.576           ms/op
ClientPb.existUser                      sample  305491   3.141 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.690           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.375           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.637           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.382           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.554           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.194           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.705           ms/op
ClientPb.getUser                        sample  301039   3.188 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.348           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.625           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.579           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.201           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.936           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.313           ms/op
ClientPb.listUser                       sample  255044   3.761 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.249           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.674           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.039           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.881           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.582           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.153           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.725           ms/op
