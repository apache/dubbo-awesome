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
# Warmup Iteration   1: 4.702 ops/ms
# Warmup Iteration   2: 11.856 ops/ms
# Warmup Iteration   3: 12.378 ops/ms
Iteration   1: 12.537 ops/ms
Iteration   2: 12.654 ops/ms
Iteration   3: 12.837 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.676 ±(99.9%) 2.761 ops/ms [Average]
  (min, avg, max) = (12.537, 12.676, 12.837), stdev = 0.151
  CI (99.9%): [9.915, 15.437] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.325 ops/ms
# Warmup Iteration   2: 13.234 ops/ms
# Warmup Iteration   3: 13.153 ops/ms
Iteration   1: 13.013 ops/ms
Iteration   2: 13.111 ops/ms
Iteration   3: 12.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.952 ±(99.9%) 3.576 ops/ms [Average]
  (min, avg, max) = (12.733, 12.952, 13.111), stdev = 0.196
  CI (99.9%): [9.376, 16.528] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.705 ops/ms
# Warmup Iteration   2: 12.903 ops/ms
# Warmup Iteration   3: 12.877 ops/ms
Iteration   1: 13.009 ops/ms
Iteration   2: 13.058 ops/ms
Iteration   3: 12.936 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.001 ±(99.9%) 1.120 ops/ms [Average]
  (min, avg, max) = (12.936, 13.001, 13.058), stdev = 0.061
  CI (99.9%): [11.881, 14.121] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.734 ops/ms
# Warmup Iteration   2: 10.560 ops/ms
# Warmup Iteration   3: 10.685 ops/ms
Iteration   1: 10.755 ops/ms
Iteration   2: 10.646 ops/ms
Iteration   3: 10.585 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.662 ±(99.9%) 1.568 ops/ms [Average]
  (min, avg, max) = (10.585, 10.662, 10.755), stdev = 0.086
  CI (99.9%): [9.094, 12.230] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.251 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.556 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.004 ms/op
Iteration   1: 2.485 ±(99.9%) 0.003 ms/op
Iteration   2: 2.516 ±(99.9%) 0.004 ms/op
Iteration   3: 2.526 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.509 ±(99.9%) 0.389 ms/op [Average]
  (min, avg, max) = (2.485, 2.509, 2.526), stdev = 0.021
  CI (99.9%): [2.120, 2.898] (assumes normal distribution)


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
# Warmup Iteration   1: 3.565 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.434 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.451 ±(99.9%) 0.004 ms/op
Iteration   1: 2.440 ±(99.9%) 0.004 ms/op
Iteration   2: 2.443 ±(99.9%) 0.004 ms/op
Iteration   3: 2.426 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.437 ±(99.9%) 0.168 ms/op [Average]
  (min, avg, max) = (2.426, 2.437, 2.443), stdev = 0.009
  CI (99.9%): [2.269, 2.604] (assumes normal distribution)


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
# Warmup Iteration   1: 3.801 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.489 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.003 ms/op
Iteration   1: 2.443 ±(99.9%) 0.004 ms/op
Iteration   2: 2.417 ±(99.9%) 0.004 ms/op
Iteration   3: 2.422 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.427 ±(99.9%) 0.248 ms/op [Average]
  (min, avg, max) = (2.417, 2.427, 2.443), stdev = 0.014
  CI (99.9%): [2.180, 2.675] (assumes normal distribution)


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
# Warmup Iteration   1: 4.668 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.028 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.006 ms/op
Iteration   1: 2.991 ±(99.9%) 0.005 ms/op
Iteration   2: 2.995 ±(99.9%) 0.005 ms/op
Iteration   3: 2.976 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.988 ±(99.9%) 0.185 ms/op [Average]
  (min, avg, max) = (2.976, 2.988, 2.995), stdev = 0.010
  CI (99.9%): [2.803, 3.172] (assumes normal distribution)


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
# Warmup Iteration   1: 4.411 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.593 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
Iteration   1: 2.475 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.825 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   3.756 ms/op
                 createUser·p0.999:  6.973 ms/op
                 createUser·p0.9999: 13.484 ms/op
                 createUser·p1.00:   14.205 ms/op

Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.846 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   3.518 ms/op
                 createUser·p0.999:  7.028 ms/op
                 createUser·p0.9999: 12.106 ms/op
                 createUser·p1.00:   13.025 ms/op

Iteration   3: 2.509 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.915 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.777 ms/op
                 createUser·p0.999:  8.353 ms/op
                 createUser·p0.9999: 10.741 ms/op
                 createUser·p1.00:   11.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385749
  mean =      2.486 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 188116 
    [ 2.500,  3.750) = 194138 
    [ 3.750,  5.000) = 2707 
    [ 5.000,  6.250) = 294 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 111 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.686 ms/op
     p(99.9000) =      8.325 ms/op
     p(99.9900) =     12.803 ms/op
     p(99.9990) =     13.641 ms/op
     p(99.9999) =     14.205 ms/op
    p(100.0000) =     14.205 ms/op


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
# Warmup Iteration   1: 3.659 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.445 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.461 ±(99.9%) 0.005 ms/op
Iteration   1: 2.475 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.914 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   4.043 ms/op
                 existUser·p0.999:  7.916 ms/op
                 existUser·p0.9999: 14.206 ms/op
                 existUser·p1.00:   14.680 ms/op

Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.938 ms/op
                 existUser·p0.50:   2.585 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  5.628 ms/op
                 existUser·p0.9999: 12.094 ms/op
                 existUser·p1.00:   12.960 ms/op

Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.030 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.690 ms/op
                 existUser·p0.999:  8.880 ms/op
                 existUser·p0.9999: 11.846 ms/op
                 existUser·p1.00:   12.419 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387447
  mean =      2.476 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 191805 
    [ 2.500,  3.750) = 191662 
    [ 3.750,  5.000) = 3038 
    [ 5.000,  6.250) = 476 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 130 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.914 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.758 ms/op
     p(99.9000) =      6.563 ms/op
     p(99.9900) =     13.009 ms/op
     p(99.9990) =     14.635 ms/op
     p(99.9999) =     14.680 ms/op
    p(100.0000) =     14.680 ms/op


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
# Warmup Iteration   1: 3.901 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.565 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.006 ms/op
Iteration   1: 2.480 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.731 ms/op
                 getUser·p0.999:  6.857 ms/op
                 getUser·p0.9999: 13.992 ms/op
                 getUser·p1.00:   14.254 ms/op

Iteration   2: 2.489 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.682 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.793 ms/op
                 getUser·p0.999:  5.969 ms/op
                 getUser·p0.9999: 12.151 ms/op
                 getUser·p1.00:   12.730 ms/op

Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.937 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   4.121 ms/op
                 getUser·p0.999:  5.563 ms/op
                 getUser·p0.9999: 10.539 ms/op
                 getUser·p1.00:   10.715 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384824
  mean =      2.492 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 108 
    [ 1.250,  2.500) = 191638 
    [ 2.500,  3.750) = 188194 
    [ 3.750,  5.000) = 4138 
    [ 5.000,  6.250) = 400 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.895 ms/op
     p(99.9000) =      5.808 ms/op
     p(99.9900) =     13.435 ms/op
     p(99.9990) =     14.172 ms/op
     p(99.9999) =     14.254 ms/op
    p(100.0000) =     14.254 ms/op


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
# Warmup Iteration   1: 4.653 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.009 ms/op
Iteration   1: 2.981 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.775 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  8.794 ms/op
                 listUser·p0.9999: 11.342 ms/op
                 listUser·p1.00:   11.944 ms/op

Iteration   2: 2.973 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.799 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.805 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.494 ms/op
                 listUser·p0.9999: 11.293 ms/op
                 listUser·p1.00:   12.632 ms/op

Iteration   3: 2.957 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.784 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.805 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   5.292 ms/op
                 listUser·p0.999:  9.159 ms/op
                 listUser·p0.9999: 10.607 ms/op
                 listUser·p1.00:   11.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322928
  mean =      2.970 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 150 
    [ 1.250,  2.500) = 97687 
    [ 2.500,  3.750) = 188912 
    [ 3.750,  5.000) = 29747 
    [ 5.000,  6.250) = 5242 
    [ 6.250,  7.500) = 527 
    [ 7.500,  8.750) = 267 
    [ 8.750, 10.000) = 248 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =      9.126 ms/op
     p(99.9900) =     11.078 ms/op
     p(99.9990) =     12.285 ms/op
     p(99.9999) =     12.632 ms/op
    p(100.0000) =     12.632 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.676 ± 2.761  ops/ms
ClientPb.existUser                       thrpt       3  12.952 ± 3.576  ops/ms
ClientPb.getUser                         thrpt       3  13.001 ± 1.120  ops/ms
ClientPb.listUser                        thrpt       3  10.662 ± 1.568  ops/ms
ClientPb.createUser                       avgt       3   2.509 ± 0.389   ms/op
ClientPb.existUser                        avgt       3   2.437 ± 0.168   ms/op
ClientPb.getUser                          avgt       3   2.427 ± 0.248   ms/op
ClientPb.listUser                         avgt       3   2.988 ± 0.185   ms/op
ClientPb.createUser                     sample  385749   2.486 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.825           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.556           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.019           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.686           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.325           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.803           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.205           ms/op
ClientPb.existUser                      sample  387447   2.476 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.914           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.758           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.563           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.009           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.680           ms/op
ClientPb.getUser                        sample  384824   2.492 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.682           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.895           ms/op
ClientPb.getUser:getUser·p0.999         sample           5.808           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.435           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.254           ms/op
ClientPb.listUser                       sample  322928   2.970 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.775           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.826           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.464           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.126           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.078           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.632           ms/op
