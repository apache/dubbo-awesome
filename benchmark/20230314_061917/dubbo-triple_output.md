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
# Warmup Iteration   1: 2.688 ops/ms
# Warmup Iteration   2: 6.383 ops/ms
# Warmup Iteration   3: 9.277 ops/ms
Iteration   1: 9.714 ops/ms
Iteration   2: 9.653 ops/ms
Iteration   3: 9.952 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.773 ±(99.9%) 2.877 ops/ms [Average]
  (min, avg, max) = (9.653, 9.773, 9.952), stdev = 0.158
  CI (99.9%): [6.896, 12.650] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.717 ops/ms
# Warmup Iteration   2: 9.417 ops/ms
# Warmup Iteration   3: 9.831 ops/ms
Iteration   1: 10.826 ops/ms
Iteration   2: 10.660 ops/ms
Iteration   3: 10.423 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.636 ±(99.9%) 3.698 ops/ms [Average]
  (min, avg, max) = (10.423, 10.636, 10.826), stdev = 0.203
  CI (99.9%): [6.938, 14.335] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.676 ops/ms
# Warmup Iteration   2: 9.117 ops/ms
# Warmup Iteration   3: 9.768 ops/ms
Iteration   1: 10.234 ops/ms
Iteration   2: 10.045 ops/ms
Iteration   3: 10.295 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.191 ±(99.9%) 2.379 ops/ms [Average]
  (min, avg, max) = (10.045, 10.191, 10.295), stdev = 0.130
  CI (99.9%): [7.812, 12.570] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.753 ops/ms
# Warmup Iteration   2: 7.857 ops/ms
# Warmup Iteration   3: 8.461 ops/ms
Iteration   1: 8.655 ops/ms
Iteration   2: 8.756 ops/ms
Iteration   3: 8.891 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.767 ±(99.9%) 2.166 ops/ms [Average]
  (min, avg, max) = (8.655, 8.767, 8.891), stdev = 0.119
  CI (99.9%): [6.601, 10.933] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.860 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.529 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.330 ±(99.9%) 0.006 ms/op
Iteration   1: 3.395 ±(99.9%) 0.005 ms/op
Iteration   2: 3.216 ±(99.9%) 0.008 ms/op
Iteration   3: 3.089 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.233 ±(99.9%) 2.800 ms/op [Average]
  (min, avg, max) = (3.089, 3.233, 3.395), stdev = 0.153
  CI (99.9%): [0.434, 6.033] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 6.654 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.227 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.004 ms/op
Iteration   1: 3.134 ±(99.9%) 0.006 ms/op
Iteration   2: 2.952 ±(99.9%) 0.003 ms/op
Iteration   3: 2.927 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.004 ±(99.9%) 2.058 ms/op [Average]
  (min, avg, max) = (2.927, 3.004, 3.134), stdev = 0.113
  CI (99.9%): [0.947, 5.062] (assumes normal distribution)


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
# Warmup Iteration   1: 7.715 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.410 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.317 ±(99.9%) 0.006 ms/op
Iteration   1: 3.214 ±(99.9%) 0.005 ms/op
Iteration   2: 3.136 ±(99.9%) 0.007 ms/op
Iteration   3: 3.215 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.188 ±(99.9%) 0.832 ms/op [Average]
  (min, avg, max) = (3.136, 3.188, 3.215), stdev = 0.046
  CI (99.9%): [2.357, 4.020] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 8.495 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.056 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.692 ±(99.9%) 0.008 ms/op
Iteration   1: 3.588 ±(99.9%) 0.011 ms/op
Iteration   2: 3.604 ±(99.9%) 0.008 ms/op
Iteration   3: 3.611 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.601 ±(99.9%) 0.211 ms/op [Average]
  (min, avg, max) = (3.588, 3.601, 3.611), stdev = 0.012
  CI (99.9%): [3.390, 3.812] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.235 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.564 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.217 ±(99.9%) 0.008 ms/op
Iteration   1: 3.176 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.092 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  11.403 ms/op
                 createUser·p0.9999: 20.245 ms/op
                 createUser·p1.00:   20.906 ms/op

Iteration   2: 3.078 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.327 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.244 ms/op
                 createUser·p0.95:   3.596 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  16.681 ms/op
                 createUser·p0.9999: 21.581 ms/op
                 createUser·p1.00:   22.053 ms/op

Iteration   3: 3.149 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.317 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   5.816 ms/op
                 createUser·p0.999:  10.502 ms/op
                 createUser·p0.9999: 14.828 ms/op
                 createUser·p1.00:   15.712 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 306186
  mean =      3.134 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13224 
    [ 2.500,  5.000) = 286657 
    [ 5.000,  7.500) = 5482 
    [ 7.500, 10.000) = 334 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     13.822 ms/op
     p(99.9900) =     21.082 ms/op
     p(99.9990) =     21.987 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


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
# Warmup Iteration   1: 6.855 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 3.361 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.008 ms/op
Iteration   1: 3.059 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   5.386 ms/op
                 existUser·p0.999:  11.207 ms/op
                 existUser·p0.9999: 23.545 ms/op
                 existUser·p1.00:   24.150 ms/op

Iteration   2: 3.014 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.044 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  12.976 ms/op
                 existUser·p0.9999: 21.594 ms/op
                 existUser·p1.00:   22.086 ms/op

Iteration   3: 3.102 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.116 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   4.076 ms/op
                 existUser·p0.99:   5.286 ms/op
                 existUser·p0.999:  13.484 ms/op
                 existUser·p0.9999: 21.158 ms/op
                 existUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 313532
  mean =      3.058 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18459 
    [ 2.500,  5.000) = 290346 
    [ 5.000,  7.500) = 3653 
    [ 7.500, 10.000) = 468 
    [10.000, 12.500) = 244 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 122 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.044 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.326 ms/op
     p(95.0000) =      3.770 ms/op
     p(99.0000) =      5.267 ms/op
     p(99.9000) =     13.090 ms/op
     p(99.9900) =     22.041 ms/op
     p(99.9990) =     24.047 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


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
# Warmup Iteration   1: 7.559 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.412 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.212 ±(99.9%) 0.010 ms/op
Iteration   1: 3.293 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.346 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   5.095 ms/op
                 getUser·p0.99:   6.447 ms/op
                 getUser·p0.999:  14.467 ms/op
                 getUser·p0.9999: 20.316 ms/op
                 getUser·p1.00:   21.299 ms/op

Iteration   2: 3.096 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.282 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.363 ms/op
                 getUser·p0.95:   3.510 ms/op
                 getUser·p0.99:   5.197 ms/op
                 getUser·p0.999:  12.824 ms/op
                 getUser·p0.9999: 25.637 ms/op
                 getUser·p1.00:   27.427 ms/op

Iteration   3: 3.058 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.632 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.305 ms/op
                 getUser·p0.95:   3.449 ms/op
                 getUser·p0.99:   4.993 ms/op
                 getUser·p0.999:  9.368 ms/op
                 getUser·p0.9999: 23.382 ms/op
                 getUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 304812
  mean =      3.146 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8437 
    [ 2.500,  5.000) = 289000 
    [ 5.000,  7.500) = 6465 
    [ 7.500, 10.000) = 533 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.282 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.700 ms/op
     p(99.0000) =      5.782 ms/op
     p(99.9000) =     14.365 ms/op
     p(99.9900) =     24.347 ms/op
     p(99.9990) =     27.358 ms/op
     p(99.9999) =     27.427 ms/op
    p(100.0000) =     27.427 ms/op


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
# Warmup Iteration   1: 8.443 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.929 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.766 ±(99.9%) 0.013 ms/op
Iteration   1: 3.628 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.663 ms/op
                 listUser·p0.50:   3.551 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.149 ms/op
                 listUser·p0.99:   6.201 ms/op
                 listUser·p0.999:  14.762 ms/op
                 listUser·p0.9999: 18.618 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   2: 3.744 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.733 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   7.290 ms/op
                 listUser·p0.999:  13.582 ms/op
                 listUser·p0.9999: 22.150 ms/op
                 listUser·p1.00:   26.313 ms/op

Iteration   3: 3.638 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.108 ms/op
                 listUser·p0.99:   6.352 ms/op
                 listUser·p0.999:  12.370 ms/op
                 listUser·p0.9999: 14.713 ms/op
                 listUser·p1.00:   15.712 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 261406
  mean =      3.669 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 72 
    [ 2.500,  5.000) = 255452 
    [ 5.000,  7.500) = 4173 
    [ 7.500, 10.000) = 1010 
    [10.000, 12.500) = 321 
    [12.500, 15.000) = 253 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.663 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     13.359 ms/op
     p(99.9900) =     18.566 ms/op
     p(99.9990) =     26.139 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.773 ± 2.877  ops/ms
ClientPb.existUser                       thrpt       3  10.636 ± 3.698  ops/ms
ClientPb.getUser                         thrpt       3  10.191 ± 2.379  ops/ms
ClientPb.listUser                        thrpt       3   8.767 ± 2.166  ops/ms
ClientPb.createUser                       avgt       3   3.233 ± 2.800   ms/op
ClientPb.existUser                        avgt       3   3.004 ± 2.058   ms/op
ClientPb.getUser                          avgt       3   3.188 ± 0.832   ms/op
ClientPb.listUser                         avgt       3   3.601 ± 0.211   ms/op
ClientPb.createUser                     sample  306186   3.134 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.092           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.002           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.514           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.636           ms/op
ClientPb.createUser:createUser·p0.999   sample          13.822           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.082           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.053           ms/op
ClientPb.existUser                      sample  313532   3.058 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.044           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.326           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.770           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.267           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.090           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.041           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.150           ms/op
ClientPb.getUser                        sample  304812   3.146 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.282           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.023           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.449           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.700           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.782           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.365           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.347           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.427           ms/op
ClientPb.listUser                       sample  261406   3.669 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.663           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.584           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.965           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.190           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.709           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.359           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.566           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.313           ms/op
