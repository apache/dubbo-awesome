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
# Warmup Iteration   1: 4.700 ops/ms
# Warmup Iteration   2: 11.753 ops/ms
# Warmup Iteration   3: 12.001 ops/ms
Iteration   1: 12.280 ops/ms
Iteration   2: 12.321 ops/ms
Iteration   3: 12.342 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.314 ±(99.9%) 0.576 ops/ms [Average]
  (min, avg, max) = (12.280, 12.314, 12.342), stdev = 0.032
  CI (99.9%): [11.739, 12.890] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.761 ops/ms
# Warmup Iteration   2: 12.614 ops/ms
# Warmup Iteration   3: 12.759 ops/ms
Iteration   1: 12.734 ops/ms
Iteration   2: 12.528 ops/ms
Iteration   3: 12.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.665 ±(99.9%) 2.169 ops/ms [Average]
  (min, avg, max) = (12.528, 12.665, 12.734), stdev = 0.119
  CI (99.9%): [10.496, 14.834] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.314 ops/ms
# Warmup Iteration   2: 12.038 ops/ms
# Warmup Iteration   3: 12.417 ops/ms
Iteration   1: 12.443 ops/ms
Iteration   2: 12.305 ops/ms
Iteration   3: 12.542 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.430 ±(99.9%) 2.167 ops/ms [Average]
  (min, avg, max) = (12.305, 12.430, 12.542), stdev = 0.119
  CI (99.9%): [10.263, 14.597] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.422 ops/ms
# Warmup Iteration   2: 10.174 ops/ms
# Warmup Iteration   3: 10.236 ops/ms
Iteration   1: 10.246 ops/ms
Iteration   2: 10.216 ops/ms
Iteration   3: 10.137 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.200 ±(99.9%) 1.021 ops/ms [Average]
  (min, avg, max) = (10.137, 10.200, 10.246), stdev = 0.056
  CI (99.9%): [9.178, 11.221] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.293 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 2.697 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.599 ±(99.9%) 0.004 ms/op
Iteration   1: 2.618 ±(99.9%) 0.004 ms/op
Iteration   2: 2.577 ±(99.9%) 0.004 ms/op
Iteration   3: 2.588 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.595 ±(99.9%) 0.384 ms/op [Average]
  (min, avg, max) = (2.577, 2.595, 2.618), stdev = 0.021
  CI (99.9%): [2.211, 2.978] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.981 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.529 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.005 ms/op
Iteration   1: 2.478 ±(99.9%) 0.003 ms/op
Iteration   2: 2.510 ±(99.9%) 0.004 ms/op
Iteration   3: 2.509 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.499 ±(99.9%) 0.336 ms/op [Average]
  (min, avg, max) = (2.478, 2.499, 2.510), stdev = 0.018
  CI (99.9%): [2.163, 2.835] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.067 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.664 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.600 ±(99.9%) 0.004 ms/op
Iteration   1: 2.606 ±(99.9%) 0.004 ms/op
Iteration   2: 2.581 ±(99.9%) 0.005 ms/op
Iteration   3: 2.620 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.603 ±(99.9%) 0.359 ms/op [Average]
  (min, avg, max) = (2.581, 2.603, 2.620), stdev = 0.020
  CI (99.9%): [2.244, 2.961] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 5.013 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.165 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.005 ms/op
Iteration   1: 3.109 ±(99.9%) 0.005 ms/op
Iteration   2: 3.143 ±(99.9%) 0.006 ms/op
Iteration   3: 3.121 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.124 ±(99.9%) 0.315 ms/op [Average]
  (min, avg, max) = (3.109, 3.124, 3.143), stdev = 0.017
  CI (99.9%): [2.809, 3.439] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.156 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.771 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.611 ±(99.9%) 0.006 ms/op
Iteration   1: 2.596 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.679 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.154 ms/op
                 createUser·p0.95:   3.269 ms/op
                 createUser·p0.99:   3.785 ms/op
                 createUser·p0.999:  11.928 ms/op
                 createUser·p0.9999: 15.128 ms/op
                 createUser·p1.00:   15.745 ms/op

Iteration   2: 2.631 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.100 ms/op
                 createUser·p0.50:   2.691 ms/op
                 createUser·p0.90:   3.191 ms/op
                 createUser·p0.95:   3.318 ms/op
                 createUser·p0.99:   4.153 ms/op
                 createUser·p0.999:  9.839 ms/op
                 createUser·p0.9999: 12.391 ms/op
                 createUser·p1.00:   13.156 ms/op

Iteration   3: 2.611 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.024 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.174 ms/op
                 createUser·p0.95:   3.293 ms/op
                 createUser·p0.99:   3.932 ms/op
                 createUser·p0.999:  8.454 ms/op
                 createUser·p0.9999: 13.779 ms/op
                 createUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 367088
  mean =      2.613 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 173664 
    [ 2.500,  3.750) = 188436 
    [ 3.750,  5.000) = 3774 
    [ 5.000,  6.250) = 648 
    [ 6.250,  7.500) = 123 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      2.662 ms/op
     p(90.0000) =      3.174 ms/op
     p(95.0000) =      3.293 ms/op
     p(99.0000) =      3.936 ms/op
     p(99.9000) =      8.847 ms/op
     p(99.9900) =     14.418 ms/op
     p(99.9990) =     15.679 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.765 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.581 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
Iteration   1: 2.534 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.770 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.092 ms/op
                 existUser·p0.95:   3.232 ms/op
                 existUser·p0.99:   4.041 ms/op
                 existUser·p0.999:  11.223 ms/op
                 existUser·p0.9999: 14.572 ms/op
                 existUser·p1.00:   15.073 ms/op

Iteration   2: 2.536 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.834 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   3.088 ms/op
                 existUser·p0.95:   3.211 ms/op
                 existUser·p0.99:   3.864 ms/op
                 existUser·p0.999:  5.881 ms/op
                 existUser·p0.9999: 14.099 ms/op
                 existUser·p1.00:   14.942 ms/op

Iteration   3: 2.536 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.026 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.097 ms/op
                 existUser·p0.95:   3.215 ms/op
                 existUser·p0.99:   3.719 ms/op
                 existUser·p0.999:  8.322 ms/op
                 existUser·p0.9999: 11.885 ms/op
                 existUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 378217
  mean =      2.535 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 183380 
    [ 2.500,  3.750) = 190200 
    [ 3.750,  5.000) = 3764 
    [ 5.000,  6.250) = 414 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.879 ms/op
     p(99.9000) =      7.568 ms/op
     p(99.9900) =     14.090 ms/op
     p(99.9990) =     15.024 ms/op
     p(99.9999) =     15.073 ms/op
    p(100.0000) =     15.073 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.286 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.635 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.591 ±(99.9%) 0.006 ms/op
Iteration   1: 2.552 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.969 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   4.026 ms/op
                 getUser·p0.999:  11.731 ms/op
                 getUser·p0.9999: 13.648 ms/op
                 getUser·p1.00:   14.402 ms/op

Iteration   2: 2.551 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.838 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   3.871 ms/op
                 getUser·p0.999:  9.841 ms/op
                 getUser·p0.9999: 13.570 ms/op
                 getUser·p1.00:   14.631 ms/op

Iteration   3: 2.576 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.000 ms/op
                 getUser·p0.50:   2.626 ms/op
                 getUser·p0.90:   3.138 ms/op
                 getUser·p0.95:   3.265 ms/op
                 getUser·p0.99:   4.084 ms/op
                 getUser·p0.999:  8.714 ms/op
                 getUser·p0.9999: 10.892 ms/op
                 getUser·p1.00:   11.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 374693
  mean =      2.560 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 180708 
    [ 2.500,  3.750) = 188462 
    [ 3.750,  5.000) = 4398 
    [ 5.000,  6.250) = 681 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 112 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.252 ms/op
     p(99.0000) =      3.981 ms/op
     p(99.9000) =      8.880 ms/op
     p(99.9900) =     13.500 ms/op
     p(99.9990) =     14.439 ms/op
     p(99.9999) =     14.631 ms/op
    p(100.0000) =     14.631 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.004 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.222 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.009 ms/op
Iteration   1: 3.133 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.997 ms/op
                 listUser·p0.50:   3.072 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.784 ms/op
                 listUser·p0.999:  10.240 ms/op
                 listUser·p0.9999: 14.490 ms/op
                 listUser·p1.00:   14.811 ms/op

Iteration   2: 3.128 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.042 ms/op
                 listUser·p0.50:   3.068 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  9.912 ms/op
                 listUser·p0.9999: 11.420 ms/op
                 listUser·p1.00:   11.911 ms/op

Iteration   3: 3.117 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.820 ms/op
                 listUser·p0.50:   3.060 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  10.018 ms/op
                 listUser·p0.9999: 11.796 ms/op
                 listUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 306852
  mean =      3.126 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 79 
    [ 1.250,  2.500) = 69003 
    [ 2.500,  3.750) = 191230 
    [ 3.750,  5.000) = 38432 
    [ 5.000,  6.250) = 6463 
    [ 6.250,  7.500) = 939 
    [ 7.500,  8.750) = 148 
    [ 8.750, 10.000) = 236 
    [10.000, 11.250) = 231 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     10.076 ms/op
     p(99.9900) =     12.080 ms/op
     p(99.9990) =     14.795 ms/op
     p(99.9999) =     14.811 ms/op
    p(100.0000) =     14.811 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.314 ± 0.576  ops/ms
ClientPb.existUser                       thrpt       3  12.665 ± 2.169  ops/ms
ClientPb.getUser                         thrpt       3  12.430 ± 2.167  ops/ms
ClientPb.listUser                        thrpt       3  10.200 ± 1.021  ops/ms
ClientPb.createUser                       avgt       3   2.595 ± 0.384   ms/op
ClientPb.existUser                        avgt       3   2.499 ± 0.336   ms/op
ClientPb.getUser                          avgt       3   2.603 ± 0.359   ms/op
ClientPb.listUser                         avgt       3   3.124 ± 0.315   ms/op
ClientPb.createUser                     sample  367088   2.613 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.679           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.662           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.293           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.936           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.847           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.418           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.859           ms/op
ClientPb.existUser                      sample  378217   2.535 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.770           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.576           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.879           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.568           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.090           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.073           ms/op
ClientPb.getUser                        sample  374693   2.560 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.838           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.589           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.252           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.981           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.880           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.500           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.631           ms/op
ClientPb.listUser                       sample  306852   3.126 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.820           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.068           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.010           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.726           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.076           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.080           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.811           ms/op
