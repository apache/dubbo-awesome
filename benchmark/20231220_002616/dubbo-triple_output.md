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
# Warmup Iteration   1: 5.321 ops/ms
# Warmup Iteration   2: 12.038 ops/ms
# Warmup Iteration   3: 12.349 ops/ms
Iteration   1: 12.581 ops/ms
Iteration   2: 12.455 ops/ms
Iteration   3: 12.688 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.575 ±(99.9%) 2.124 ops/ms [Average]
  (min, avg, max) = (12.455, 12.575, 12.688), stdev = 0.116
  CI (99.9%): [10.451, 14.699] (assumes normal distribution)


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
# Warmup Iteration   1: 8.178 ops/ms
# Warmup Iteration   2: 13.152 ops/ms
# Warmup Iteration   3: 13.123 ops/ms
Iteration   1: 13.120 ops/ms
Iteration   2: 13.191 ops/ms
Iteration   3: 13.156 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.156 ±(99.9%) 0.650 ops/ms [Average]
  (min, avg, max) = (13.120, 13.156, 13.191), stdev = 0.036
  CI (99.9%): [12.506, 13.806] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.084 ops/ms
# Warmup Iteration   2: 12.787 ops/ms
# Warmup Iteration   3: 12.992 ops/ms
Iteration   1: 12.886 ops/ms
Iteration   2: 13.239 ops/ms
Iteration   3: 13.131 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.085 ±(99.9%) 3.300 ops/ms [Average]
  (min, avg, max) = (12.886, 13.085, 13.239), stdev = 0.181
  CI (99.9%): [9.785, 16.385] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.497 ops/ms
# Warmup Iteration   2: 10.421 ops/ms
# Warmup Iteration   3: 10.598 ops/ms
Iteration   1: 10.659 ops/ms
Iteration   2: 10.623 ops/ms
Iteration   3: 10.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.659 ±(99.9%) 0.652 ops/ms [Average]
  (min, avg, max) = (10.623, 10.659, 10.695), stdev = 0.036
  CI (99.9%): [10.007, 11.311] (assumes normal distribution)


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
# Warmup Iteration   1: 4.251 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.611 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.550 ±(99.9%) 0.004 ms/op
Iteration   1: 2.578 ±(99.9%) 0.005 ms/op
Iteration   2: 2.542 ±(99.9%) 0.003 ms/op
Iteration   3: 2.554 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.558 ±(99.9%) 0.338 ms/op [Average]
  (min, avg, max) = (2.542, 2.558, 2.578), stdev = 0.019
  CI (99.9%): [2.220, 2.896] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.630 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.453 ±(99.9%) 0.005 ms/op
Iteration   1: 2.466 ±(99.9%) 0.004 ms/op
Iteration   2: 2.450 ±(99.9%) 0.005 ms/op
Iteration   3: 2.454 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.457 ±(99.9%) 0.148 ms/op [Average]
  (min, avg, max) = (2.450, 2.457, 2.466), stdev = 0.008
  CI (99.9%): [2.308, 2.605] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.960 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.527 ±(99.9%) 0.004 ms/op
Iteration   1: 2.474 ±(99.9%) 0.003 ms/op
Iteration   2: 2.440 ±(99.9%) 0.003 ms/op
Iteration   3: 2.461 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.458 ±(99.9%) 0.311 ms/op [Average]
  (min, avg, max) = (2.440, 2.458, 2.474), stdev = 0.017
  CI (99.9%): [2.148, 2.769] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.774 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.033 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.006 ms/op
Iteration   1: 3.003 ±(99.9%) 0.005 ms/op
Iteration   2: 2.985 ±(99.9%) 0.005 ms/op
Iteration   3: 2.979 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.989 ±(99.9%) 0.229 ms/op [Average]
  (min, avg, max) = (2.979, 2.989, 3.003), stdev = 0.013
  CI (99.9%): [2.760, 3.218] (assumes normal distribution)


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
# Warmup Iteration   1: 4.017 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.615 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.005 ms/op
Iteration   1: 2.504 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.063 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.723 ms/op
                 createUser·p0.999:  11.125 ms/op
                 createUser·p0.9999: 13.926 ms/op
                 createUser·p1.00:   14.598 ms/op

Iteration   2: 2.472 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   2.511 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.637 ms/op
                 createUser·p0.999:  5.693 ms/op
                 createUser·p0.9999: 12.372 ms/op
                 createUser·p1.00:   13.124 ms/op

Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.013 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.809 ms/op
                 createUser·p0.999:  8.021 ms/op
                 createUser·p0.9999: 10.902 ms/op
                 createUser·p1.00:   12.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385651
  mean =      2.487 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 189539 
    [ 2.500,  3.750) = 192487 
    [ 3.750,  5.000) = 2880 
    [ 5.000,  6.250) = 278 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.013 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.715 ms/op
     p(99.9000) =      7.702 ms/op
     p(99.9900) =     13.203 ms/op
     p(99.9990) =     14.060 ms/op
     p(99.9999) =     14.598 ms/op
    p(100.0000) =     14.598 ms/op


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
# Warmup Iteration   1: 3.632 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
Iteration   1: 2.454 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.845 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.469 ms/op
                 existUser·p0.999:  5.977 ms/op
                 existUser·p0.9999: 14.007 ms/op
                 existUser·p1.00:   14.828 ms/op

Iteration   2: 2.484 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.559 ms/op
                 existUser·p0.999:  6.929 ms/op
                 existUser·p0.9999: 12.716 ms/op
                 existUser·p1.00:   13.173 ms/op

Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  9.077 ms/op
                 existUser·p0.9999: 12.632 ms/op
                 existUser·p1.00:   13.484 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386910
  mean =      2.480 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 187100 
    [ 2.500,  3.750) = 196009 
    [ 3.750,  5.000) = 2818 
    [ 5.000,  6.250) = 455 
    [ 6.250,  7.500) = 92 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 97 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.727 ms/op
     p(99.9000) =      7.651 ms/op
     p(99.9900) =     13.173 ms/op
     p(99.9990) =     14.668 ms/op
     p(99.9999) =     14.828 ms/op
    p(100.0000) =     14.828 ms/op


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
# Warmup Iteration   1: 3.765 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.552 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.005 ms/op
Iteration   1: 2.518 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.785 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.984 ms/op
                 getUser·p0.999:  11.143 ms/op
                 getUser·p0.9999: 14.051 ms/op
                 getUser·p1.00:   14.860 ms/op

Iteration   2: 2.508 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.699 ms/op
                 getUser·p0.999:  9.536 ms/op
                 getUser·p0.9999: 14.537 ms/op
                 getUser·p1.00:   14.975 ms/op

Iteration   3: 2.520 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.602 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.875 ms/op
                 getUser·p0.999:  8.142 ms/op
                 getUser·p0.9999: 11.614 ms/op
                 getUser·p1.00:   12.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381279
  mean =      2.515 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 76 
    [ 1.250,  2.500) = 188295 
    [ 2.500,  3.750) = 188331 
    [ 3.750,  5.000) = 3743 
    [ 5.000,  6.250) = 435 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.858 ms/op
     p(99.9000) =      8.421 ms/op
     p(99.9900) =     14.025 ms/op
     p(99.9990) =     14.909 ms/op
     p(99.9999) =     14.975 ms/op
    p(100.0000) =     14.975 ms/op


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
# Warmup Iteration   1: 4.622 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.050 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.009 ms/op
Iteration   1: 3.027 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.893 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.775 ms/op
                 listUser·p0.999:  9.257 ms/op
                 listUser·p0.9999: 11.059 ms/op
                 listUser·p1.00:   11.600 ms/op

Iteration   2: 3.037 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.888 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  10.317 ms/op
                 listUser·p0.9999: 11.878 ms/op
                 listUser·p1.00:   12.534 ms/op

Iteration   3: 2.996 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.923 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  8.759 ms/op
                 listUser·p0.9999: 11.250 ms/op
                 listUser·p1.00:   12.190 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317625
  mean =      3.020 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 128 
    [ 1.250,  2.500) = 91097 
    [ 2.500,  3.750) = 186712 
    [ 3.750,  5.000) = 31900 
    [ 5.000,  6.250) = 6273 
    [ 6.250,  7.500) = 821 
    [ 7.500,  8.750) = 244 
    [ 8.750, 10.000) = 217 
    [10.000, 11.250) = 194 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =      9.437 ms/op
     p(99.9900) =     11.424 ms/op
     p(99.9990) =     12.190 ms/op
     p(99.9999) =     12.534 ms/op
    p(100.0000) =     12.534 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.575 ± 2.124  ops/ms
ClientPb.existUser                       thrpt       3  13.156 ± 0.650  ops/ms
ClientPb.getUser                         thrpt       3  13.085 ± 3.300  ops/ms
ClientPb.listUser                        thrpt       3  10.659 ± 0.652  ops/ms
ClientPb.createUser                       avgt       3   2.558 ± 0.338   ms/op
ClientPb.existUser                        avgt       3   2.457 ± 0.148   ms/op
ClientPb.getUser                          avgt       3   2.458 ± 0.311   ms/op
ClientPb.listUser                         avgt       3   2.989 ± 0.229   ms/op
ClientPb.createUser                     sample  385651   2.487 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.013           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.535           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.023           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.715           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.702           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.203           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.598           ms/op
ClientPb.existUser                      sample  386910   2.480 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.845           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.580           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.727           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.651           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.173           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.828           ms/op
ClientPb.getUser                        sample  381279   2.515 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.602           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.421           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.025           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.975           ms/op
ClientPb.listUser                       sample  317625   3.020 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.888           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.669           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.437           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.424           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.534           ms/op
