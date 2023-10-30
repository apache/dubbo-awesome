# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.608 ops/ms
# Warmup Iteration   2: 5.507 ops/ms
# Warmup Iteration   3: 9.047 ops/ms
Iteration   1: 9.873 ops/ms
Iteration   2: 9.902 ops/ms
Iteration   3: 9.571 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.782 ±(99.9%) 3.341 ops/ms [Average]
  (min, avg, max) = (9.571, 9.782, 9.902), stdev = 0.183
  CI (99.9%): [6.441, 13.123] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.197 ops/ms
# Warmup Iteration   2: 9.633 ops/ms
# Warmup Iteration   3: 9.943 ops/ms
Iteration   1: 10.230 ops/ms
Iteration   2: 10.396 ops/ms
Iteration   3: 9.941 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.189 ±(99.9%) 4.200 ops/ms [Average]
  (min, avg, max) = (9.941, 10.189, 10.396), stdev = 0.230
  CI (99.9%): [5.989, 14.389] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.548 ops/ms
# Warmup Iteration   2: 8.833 ops/ms
# Warmup Iteration   3: 9.703 ops/ms
Iteration   1: 9.850 ops/ms
Iteration   2: 9.848 ops/ms
Iteration   3: 9.884 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.861 ±(99.9%) 0.375 ops/ms [Average]
  (min, avg, max) = (9.848, 9.861, 9.884), stdev = 0.021
  CI (99.9%): [9.485, 10.236] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.361 ops/ms
# Warmup Iteration   2: 8.033 ops/ms
# Warmup Iteration   3: 8.461 ops/ms
Iteration   1: 8.380 ops/ms
Iteration   2: 8.512 ops/ms
Iteration   3: 8.404 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.432 ±(99.9%) 1.284 ops/ms [Average]
  (min, avg, max) = (8.380, 8.432, 8.512), stdev = 0.070
  CI (99.9%): [7.148, 9.716] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.753 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.863 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.298 ±(99.9%) 0.004 ms/op
Iteration   1: 3.288 ±(99.9%) 0.004 ms/op
Iteration   2: 3.393 ±(99.9%) 0.002 ms/op
Iteration   3: 3.204 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.295 ±(99.9%) 1.721 ms/op [Average]
  (min, avg, max) = (3.204, 3.295, 3.393), stdev = 0.094
  CI (99.9%): [1.574, 5.016] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.022 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.321 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.005 ms/op
Iteration   1: 3.128 ±(99.9%) 0.002 ms/op
Iteration   2: 3.071 ±(99.9%) 0.004 ms/op
Iteration   3: 3.141 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.113 ±(99.9%) 0.675 ms/op [Average]
  (min, avg, max) = (3.071, 3.113, 3.141), stdev = 0.037
  CI (99.9%): [2.438, 3.789] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.356 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.525 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.250 ±(99.9%) 0.002 ms/op
Iteration   1: 3.235 ±(99.9%) 0.004 ms/op
Iteration   2: 3.162 ±(99.9%) 0.003 ms/op
Iteration   3: 3.266 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.221 ±(99.9%) 0.982 ms/op [Average]
  (min, avg, max) = (3.162, 3.221, 3.266), stdev = 0.054
  CI (99.9%): [2.239, 4.203] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.378 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.059 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.813 ±(99.9%) 0.004 ms/op
Iteration   1: 3.824 ±(99.9%) 0.005 ms/op
Iteration   2: 3.841 ±(99.9%) 0.005 ms/op
Iteration   3: 3.776 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.814 ±(99.9%) 0.614 ms/op [Average]
  (min, avg, max) = (3.776, 3.814, 3.841), stdev = 0.034
  CI (99.9%): [3.200, 4.428] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.937 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.646 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.268 ±(99.9%) 0.009 ms/op
Iteration   1: 3.209 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.124 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   5.974 ms/op
                 createUser·p0.999:  13.883 ms/op
                 createUser·p0.9999: 21.700 ms/op
                 createUser·p1.00:   23.527 ms/op

Iteration   2: 3.259 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.348 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  17.596 ms/op
                 createUser·p0.9999: 22.157 ms/op
                 createUser·p1.00:   24.117 ms/op

Iteration   3: 3.202 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.167 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  15.552 ms/op
                 createUser·p0.9999: 21.663 ms/op
                 createUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297658
  mean =      3.223 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10489 
    [ 2.500,  5.000) = 282715 
    [ 5.000,  7.500) = 3287 
    [ 7.500, 10.000) = 453 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 206 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 156 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     16.548 ms/op
     p(99.9900) =     22.028 ms/op
     p(99.9990) =     24.130 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.970 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.328 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.234 ±(99.9%) 0.008 ms/op
Iteration   1: 3.215 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.069 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   5.300 ms/op
                 existUser·p0.999:  17.367 ms/op
                 existUser·p0.9999: 21.204 ms/op
                 existUser·p1.00:   22.020 ms/op

Iteration   2: 3.142 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.014 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   5.702 ms/op
                 existUser·p0.999:  13.418 ms/op
                 existUser·p0.9999: 23.155 ms/op
                 existUser·p1.00:   23.396 ms/op

Iteration   3: 3.183 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.102 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  7.606 ms/op
                 existUser·p0.9999: 21.199 ms/op
                 existUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301892
  mean =      3.180 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23071 
    [ 2.500,  5.000) = 273964 
    [ 5.000,  7.500) = 3893 
    [ 7.500, 10.000) = 358 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.014 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     14.305 ms/op
     p(99.9900) =     22.735 ms/op
     p(99.9990) =     23.297 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.650 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.380 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.309 ±(99.9%) 0.009 ms/op
Iteration   1: 3.326 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.251 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   5.243 ms/op
                 getUser·p0.99:   6.554 ms/op
                 getUser·p0.999:  14.531 ms/op
                 getUser·p0.9999: 18.711 ms/op
                 getUser·p1.00:   19.169 ms/op

Iteration   2: 3.230 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.323 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   5.554 ms/op
                 getUser·p0.999:  14.887 ms/op
                 getUser·p0.9999: 20.558 ms/op
                 getUser·p1.00:   22.577 ms/op

Iteration   3: 3.183 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.241 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   5.947 ms/op
                 getUser·p0.999:  12.445 ms/op
                 getUser·p0.9999: 21.037 ms/op
                 getUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296028
  mean =      3.245 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13994 
    [ 2.500,  5.000) = 273022 
    [ 5.000,  7.500) = 7918 
    [ 7.500, 10.000) = 559 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.241 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      6.300 ms/op
     p(99.9000) =     14.385 ms/op
     p(99.9900) =     20.755 ms/op
     p(99.9990) =     22.225 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.972 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.067 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.936 ±(99.9%) 0.012 ms/op
Iteration   1: 3.765 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.262 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.211 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  15.188 ms/op
                 listUser·p0.9999: 19.972 ms/op
                 listUser·p1.00:   22.610 ms/op

Iteration   2: 3.798 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.343 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  13.088 ms/op
                 listUser·p0.9999: 16.814 ms/op
                 listUser·p1.00:   18.022 ms/op

Iteration   3: 3.777 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   6.357 ms/op
                 listUser·p0.999:  13.588 ms/op
                 listUser·p0.9999: 14.975 ms/op
                 listUser·p1.00:   15.778 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253743
  mean =      3.780 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 247927 
    [ 5.000,  7.500) = 4563 
    [ 7.500, 10.000) = 489 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 425 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.262 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.496 ms/op
     p(99.9000) =     14.172 ms/op
     p(99.9900) =     18.285 ms/op
     p(99.9990) =     20.879 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.782 ± 3.341  ops/ms
ClientPb.existUser                       thrpt       3  10.189 ± 4.200  ops/ms
ClientPb.getUser                         thrpt       3   9.861 ± 0.375  ops/ms
ClientPb.listUser                        thrpt       3   8.432 ± 1.284  ops/ms
ClientPb.createUser                       avgt       3   3.295 ± 1.721   ms/op
ClientPb.existUser                        avgt       3   3.113 ± 0.675   ms/op
ClientPb.getUser                          avgt       3   3.221 ± 0.982   ms/op
ClientPb.listUser                         avgt       3   3.814 ± 0.614   ms/op
ClientPb.createUser                     sample  297658   3.223 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.124           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.572           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.817           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.587           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.548           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.028           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.707           ms/op
ClientPb.existUser                      sample  301892   3.180 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.014           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.461           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.464           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.305           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.735           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.396           ms/op
ClientPb.getUser                        sample  296028   3.245 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.241           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.572           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.981           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.300           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.385           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.755           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.577           ms/op
ClientPb.listUser                       sample  253743   3.780 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.262           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.699           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.051           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.235           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.496           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.172           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.285           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.610           ms/op
