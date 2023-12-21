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
# Warmup Iteration   1: 4.179 ops/ms
# Warmup Iteration   2: 11.498 ops/ms
# Warmup Iteration   3: 11.796 ops/ms
Iteration   1: 12.338 ops/ms
Iteration   2: 12.258 ops/ms
Iteration   3: 12.258 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.285 ±(99.9%) 0.840 ops/ms [Average]
  (min, avg, max) = (12.258, 12.285, 12.338), stdev = 0.046
  CI (99.9%): [11.444, 13.125] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.389 ops/ms
# Warmup Iteration   2: 12.641 ops/ms
# Warmup Iteration   3: 12.790 ops/ms
Iteration   1: 12.892 ops/ms
Iteration   2: 12.922 ops/ms
Iteration   3: 12.900 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.905 ±(99.9%) 0.284 ops/ms [Average]
  (min, avg, max) = (12.892, 12.905, 12.922), stdev = 0.016
  CI (99.9%): [12.621, 13.188] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.203 ops/ms
# Warmup Iteration   2: 12.342 ops/ms
# Warmup Iteration   3: 12.616 ops/ms
Iteration   1: 12.514 ops/ms
Iteration   2: 12.384 ops/ms
Iteration   3: 12.410 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.436 ±(99.9%) 1.253 ops/ms [Average]
  (min, avg, max) = (12.384, 12.436, 12.514), stdev = 0.069
  CI (99.9%): [11.183, 13.689] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.660 ops/ms
# Warmup Iteration   2: 10.347 ops/ms
# Warmup Iteration   3: 10.478 ops/ms
Iteration   1: 10.435 ops/ms
Iteration   2: 10.454 ops/ms
Iteration   3: 10.477 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.455 ±(99.9%) 0.389 ops/ms [Average]
  (min, avg, max) = (10.435, 10.455, 10.477), stdev = 0.021
  CI (99.9%): [10.067, 10.844] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.210 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.660 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.584 ±(99.9%) 0.004 ms/op
Iteration   1: 2.626 ±(99.9%) 0.004 ms/op
Iteration   2: 2.602 ±(99.9%) 0.004 ms/op
Iteration   3: 2.636 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.621 ±(99.9%) 0.314 ms/op [Average]
  (min, avg, max) = (2.602, 2.621, 2.636), stdev = 0.017
  CI (99.9%): [2.308, 2.935] (assumes normal distribution)


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
# Warmup Iteration   1: 4.065 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.472 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.005 ms/op
Iteration   1: 2.446 ±(99.9%) 0.003 ms/op
Iteration   2: 2.468 ±(99.9%) 0.003 ms/op
Iteration   3: 2.468 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.460 ±(99.9%) 0.231 ms/op [Average]
  (min, avg, max) = (2.446, 2.460, 2.468), stdev = 0.013
  CI (99.9%): [2.230, 2.691] (assumes normal distribution)


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
# Warmup Iteration   1: 3.921 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.601 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.577 ±(99.9%) 0.005 ms/op
Iteration   1: 2.501 ±(99.9%) 0.004 ms/op
Iteration   2: 2.543 ±(99.9%) 0.004 ms/op
Iteration   3: 2.543 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.529 ±(99.9%) 0.439 ms/op [Average]
  (min, avg, max) = (2.501, 2.529, 2.543), stdev = 0.024
  CI (99.9%): [2.090, 2.968] (assumes normal distribution)


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
# Warmup Iteration   1: 4.931 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.006 ms/op
Iteration   1: 3.030 ±(99.9%) 0.004 ms/op
Iteration   2: 3.056 ±(99.9%) 0.005 ms/op
Iteration   3: 3.052 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.046 ±(99.9%) 0.262 ms/op [Average]
  (min, avg, max) = (3.030, 3.046, 3.056), stdev = 0.014
  CI (99.9%): [2.784, 3.308] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.398 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.719 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.576 ±(99.9%) 0.006 ms/op
Iteration   1: 2.583 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.829 ms/op
                 createUser·p0.50:   2.654 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  11.158 ms/op
                 createUser·p0.9999: 12.943 ms/op
                 createUser·p1.00:   13.926 ms/op

Iteration   2: 2.602 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.955 ms/op
                 createUser·p0.50:   2.662 ms/op
                 createUser·p0.90:   3.158 ms/op
                 createUser·p0.95:   3.297 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  9.093 ms/op
                 createUser·p0.9999: 11.525 ms/op
                 createUser·p1.00:   13.369 ms/op

Iteration   3: 2.587 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.829 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.146 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   3.789 ms/op
                 createUser·p0.999:  8.545 ms/op
                 createUser·p0.9999: 11.746 ms/op
                 createUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 370205
  mean =      2.590 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 175544 
    [ 2.500,  3.750) = 189590 
    [ 3.750,  5.000) = 4000 
    [ 5.000,  6.250) = 539 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 114 
    [10.000, 11.250) = 121 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      2.658 ms/op
     p(90.0000) =      3.146 ms/op
     p(95.0000) =      3.265 ms/op
     p(99.0000) =      3.932 ms/op
     p(99.9000) =      9.028 ms/op
     p(99.9900) =     12.861 ms/op
     p(99.9990) =     13.687 ms/op
     p(99.9999) =     17.629 ms/op
    p(100.0000) =     17.629 ms/op


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
# Warmup Iteration   1: 3.972 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.471 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
Iteration   1: 2.488 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.048 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.539 ms/op
                 existUser·p0.999:  9.042 ms/op
                 existUser·p0.9999: 14.636 ms/op
                 existUser·p1.00:   15.598 ms/op

Iteration   2: 2.492 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.014 ms/op
                 existUser·p0.50:   2.597 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.535 ms/op
                 existUser·p0.999:  8.118 ms/op
                 existUser·p0.9999: 13.394 ms/op
                 existUser·p1.00:   14.221 ms/op

Iteration   3: 2.509 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.851 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.727 ms/op
                 existUser·p0.999:  8.405 ms/op
                 existUser·p0.9999: 12.354 ms/op
                 existUser·p1.00:   12.894 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384245
  mean =      2.496 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 187898 
    [ 2.500,  3.750) = 193361 
    [ 3.750,  5.000) = 2082 
    [ 5.000,  6.250) = 375 
    [ 6.250,  7.500) = 70 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.592 ms/op
     p(99.9000) =      8.370 ms/op
     p(99.9900) =     13.526 ms/op
     p(99.9990) =     14.775 ms/op
     p(99.9999) =     15.598 ms/op
    p(100.0000) =     15.598 ms/op


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
# Warmup Iteration   1: 4.279 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.005 ms/op
Iteration   1: 2.570 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.129 ms/op
                 getUser·p0.95:   3.305 ms/op
                 getUser·p0.99:   4.710 ms/op
                 getUser·p0.999:  11.425 ms/op
                 getUser·p0.9999: 13.586 ms/op
                 getUser·p1.00:   14.352 ms/op

Iteration   2: 2.556 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.937 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   3.748 ms/op
                 getUser·p0.999:  9.630 ms/op
                 getUser·p0.9999: 13.803 ms/op
                 getUser·p1.00:   14.795 ms/op

Iteration   3: 2.557 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   3.875 ms/op
                 getUser·p0.999:  9.142 ms/op
                 getUser·p0.9999: 11.616 ms/op
                 getUser·p1.00:   12.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 374510
  mean =      2.561 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 181355 
    [ 2.500,  3.750) = 187377 
    [ 3.750,  5.000) = 4070 
    [ 5.000,  6.250) = 1241 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.256 ms/op
     p(99.0000) =      4.055 ms/op
     p(99.9000) =      9.469 ms/op
     p(99.9900) =     13.460 ms/op
     p(99.9990) =     14.493 ms/op
     p(99.9999) =     14.795 ms/op
    p(100.0000) =     14.795 ms/op


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
# Warmup Iteration   1: 4.954 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.009 ms/op
Iteration   1: 3.046 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.999 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.652 ms/op
                 listUser·p0.9999: 12.558 ms/op
                 listUser·p1.00:   14.582 ms/op

Iteration   2: 3.024 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.568 ms/op
                 listUser·p0.9999: 11.221 ms/op
                 listUser·p1.00:   11.715 ms/op

Iteration   3: 3.035 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.967 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.241 ms/op
                 listUser·p0.9999: 10.608 ms/op
                 listUser·p1.00:   11.420 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316063
  mean =      3.035 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 120 
    [ 1.250,  2.500) = 86706 
    [ 2.500,  3.750) = 188640 
    [ 3.750,  5.000) = 33664 
    [ 5.000,  6.250) = 5648 
    [ 6.250,  7.500) = 634 
    [ 7.500,  8.750) = 180 
    [ 8.750, 10.000) = 249 
    [10.000, 11.250) = 186 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.967 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.485 ms/op
     p(99.9900) =     11.387 ms/op
     p(99.9990) =     14.432 ms/op
     p(99.9999) =     14.582 ms/op
    p(100.0000) =     14.582 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.285 ± 0.840  ops/ms
ClientPb.existUser                       thrpt       3  12.905 ± 0.284  ops/ms
ClientPb.getUser                         thrpt       3  12.436 ± 1.253  ops/ms
ClientPb.listUser                        thrpt       3  10.455 ± 0.389  ops/ms
ClientPb.createUser                       avgt       3   2.621 ± 0.314   ms/op
ClientPb.existUser                        avgt       3   2.460 ± 0.231   ms/op
ClientPb.getUser                          avgt       3   2.529 ± 0.439   ms/op
ClientPb.listUser                         avgt       3   3.046 ± 0.262   ms/op
ClientPb.createUser                     sample  370205   2.590 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.829           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.658           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.265           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.932           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.028           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.861           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.629           ms/op
ClientPb.existUser                      sample  384245   2.496 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.851           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.560           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.138           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.592           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.370           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.526           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.598           ms/op
ClientPb.getUser                        sample  374510   2.561 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.936           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.580           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.256           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.055           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.469           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.460           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.795           ms/op
ClientPb.listUser                       sample  316063   3.035 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.967           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.978           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.485           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.387           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.582           ms/op
