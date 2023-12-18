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
# Warmup Iteration   1: 4.676 ops/ms
# Warmup Iteration   2: 11.885 ops/ms
# Warmup Iteration   3: 12.385 ops/ms
Iteration   1: 12.454 ops/ms
Iteration   2: 12.507 ops/ms
Iteration   3: 12.569 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.510 ±(99.9%) 1.049 ops/ms [Average]
  (min, avg, max) = (12.454, 12.510, 12.569), stdev = 0.057
  CI (99.9%): [11.461, 13.558] (assumes normal distribution)


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
# Warmup Iteration   1: 8.386 ops/ms
# Warmup Iteration   2: 12.893 ops/ms
# Warmup Iteration   3: 12.884 ops/ms
Iteration   1: 12.856 ops/ms
Iteration   2: 12.886 ops/ms
Iteration   3: 12.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.863 ±(99.9%) 0.369 ops/ms [Average]
  (min, avg, max) = (12.847, 12.863, 12.886), stdev = 0.020
  CI (99.9%): [12.494, 13.232] (assumes normal distribution)


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
# Warmup Iteration   1: 7.889 ops/ms
# Warmup Iteration   2: 12.622 ops/ms
# Warmup Iteration   3: 12.661 ops/ms
Iteration   1: 12.964 ops/ms
Iteration   2: 12.709 ops/ms
Iteration   3: 12.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.837 ±(99.9%) 2.326 ops/ms [Average]
  (min, avg, max) = (12.709, 12.837, 12.964), stdev = 0.128
  CI (99.9%): [10.511, 15.164] (assumes normal distribution)


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
# Warmup Iteration   1: 6.610 ops/ms
# Warmup Iteration   2: 10.386 ops/ms
# Warmup Iteration   3: 10.503 ops/ms
Iteration   1: 10.446 ops/ms
Iteration   2: 10.496 ops/ms
Iteration   3: 10.488 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.477 ±(99.9%) 0.491 ops/ms [Average]
  (min, avg, max) = (10.446, 10.477, 10.496), stdev = 0.027
  CI (99.9%): [9.985, 10.968] (assumes normal distribution)


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
# Warmup Iteration   1: 3.840 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.604 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.004 ms/op
Iteration   1: 2.527 ±(99.9%) 0.004 ms/op
Iteration   2: 2.498 ±(99.9%) 0.004 ms/op
Iteration   3: 2.486 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.504 ±(99.9%) 0.376 ms/op [Average]
  (min, avg, max) = (2.486, 2.504, 2.527), stdev = 0.021
  CI (99.9%): [2.127, 2.880] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.671 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.444 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.443 ±(99.9%) 0.004 ms/op
Iteration   1: 2.423 ±(99.9%) 0.003 ms/op
Iteration   2: 2.437 ±(99.9%) 0.004 ms/op
Iteration   3: 2.448 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.436 ±(99.9%) 0.220 ms/op [Average]
  (min, avg, max) = (2.423, 2.436, 2.448), stdev = 0.012
  CI (99.9%): [2.215, 2.656] (assumes normal distribution)


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
# Warmup Iteration   1: 4.101 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.584 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.004 ms/op
Iteration   1: 2.535 ±(99.9%) 0.004 ms/op
Iteration   2: 2.508 ±(99.9%) 0.004 ms/op
Iteration   3: 2.544 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.529 ±(99.9%) 0.344 ms/op [Average]
  (min, avg, max) = (2.508, 2.529, 2.544), stdev = 0.019
  CI (99.9%): [2.185, 2.874] (assumes normal distribution)


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
# Warmup Iteration   1: 4.772 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.005 ms/op
Iteration   1: 3.060 ±(99.9%) 0.007 ms/op
Iteration   2: 3.023 ±(99.9%) 0.005 ms/op
Iteration   3: 3.016 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.033 ±(99.9%) 0.433 ms/op [Average]
  (min, avg, max) = (3.016, 3.033, 3.060), stdev = 0.024
  CI (99.9%): [2.600, 3.466] (assumes normal distribution)


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
# Warmup Iteration   1: 3.957 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.693 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.005 ms/op
Iteration   1: 2.547 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.612 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.690 ms/op
                 createUser·p0.999:  11.547 ms/op
                 createUser·p0.9999: 13.475 ms/op
                 createUser·p1.00:   14.041 ms/op

Iteration   2: 2.540 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.009 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.617 ms/op
                 createUser·p0.999:  8.997 ms/op
                 createUser·p0.9999: 18.849 ms/op
                 createUser·p1.00:   19.333 ms/op

Iteration   3: 2.553 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.037 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.977 ms/op
                 createUser·p0.999:  8.602 ms/op
                 createUser·p0.9999: 10.591 ms/op
                 createUser·p1.00:   10.994 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376607
  mean =      2.547 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 182536 
    [ 2.500,  3.750) = 190245 
    [ 3.750,  5.000) = 2940 
    [ 5.000,  6.250) = 381 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 138 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.612 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.752 ms/op
     p(99.9000) =      8.752 ms/op
     p(99.9900) =     13.916 ms/op
     p(99.9990) =     19.268 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


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
# Warmup Iteration   1: 3.618 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.479 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.005 ms/op
Iteration   1: 2.442 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.977 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.539 ms/op
                 existUser·p0.999:  6.701 ms/op
                 existUser·p0.9999: 13.648 ms/op
                 existUser·p1.00:   14.287 ms/op

Iteration   2: 2.443 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.974 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.535 ms/op
                 existUser·p0.999:  6.980 ms/op
                 existUser·p0.9999: 13.876 ms/op
                 existUser·p1.00:   14.680 ms/op

Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.991 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.170 ms/op
                 existUser·p0.99:   3.908 ms/op
                 existUser·p0.999:  5.962 ms/op
                 existUser·p0.9999: 11.289 ms/op
                 existUser·p1.00:   11.551 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391799
  mean =      2.449 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 197742 
    [ 2.500,  3.750) = 190537 
    [ 3.750,  5.000) = 2634 
    [ 5.000,  6.250) = 408 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.974 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.678 ms/op
     p(99.9000) =      6.781 ms/op
     p(99.9900) =     13.481 ms/op
     p(99.9990) =     14.339 ms/op
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
# Warmup Iteration   1: 3.878 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.557 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.006 ms/op
Iteration   1: 2.490 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.090 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.559 ms/op
                 getUser·p0.999:  4.994 ms/op
                 getUser·p0.9999: 13.353 ms/op
                 getUser·p1.00:   13.730 ms/op

Iteration   2: 2.492 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.979 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   4.137 ms/op
                 getUser·p0.999:  8.831 ms/op
                 getUser·p0.9999: 15.085 ms/op
                 getUser·p1.00:   15.876 ms/op

Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.815 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.781 ms/op
                 getUser·p0.999:  7.924 ms/op
                 getUser·p0.9999: 12.452 ms/op
                 getUser·p1.00:   13.484 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385089
  mean =      2.491 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 190308 
    [ 2.500,  3.750) = 190670 
    [ 3.750,  5.000) = 3076 
    [ 5.000,  6.250) = 578 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =      6.820 ms/op
     p(99.9900) =     13.541 ms/op
     p(99.9990) =     15.319 ms/op
     p(99.9999) =     15.876 ms/op
    p(100.0000) =     15.876 ms/op


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
# Warmup Iteration   1: 4.916 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.008 ms/op
Iteration   1: 3.051 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.644 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  9.404 ms/op
                 listUser·p0.9999: 10.937 ms/op
                 listUser·p1.00:   12.534 ms/op

Iteration   2: 3.052 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.915 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  9.814 ms/op
                 listUser·p0.9999: 12.444 ms/op
                 listUser·p1.00:   12.960 ms/op

Iteration   3: 3.041 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.933 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  8.648 ms/op
                 listUser·p0.9999: 10.739 ms/op
                 listUser·p1.00:   11.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314667
  mean =      3.048 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 155 
    [ 1.250,  2.500) = 87411 
    [ 2.500,  3.750) = 185540 
    [ 3.750,  5.000) = 33399 
    [ 5.000,  6.250) = 6594 
    [ 6.250,  7.500) = 866 
    [ 7.500,  8.750) = 302 
    [ 8.750, 10.000) = 207 
    [10.000, 11.250) = 142 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =      9.279 ms/op
     p(99.9900) =     11.691 ms/op
     p(99.9990) =     12.892 ms/op
     p(99.9999) =     12.960 ms/op
    p(100.0000) =     12.960 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.510 ± 1.049  ops/ms
ClientPb.existUser                       thrpt       3  12.863 ± 0.369  ops/ms
ClientPb.getUser                         thrpt       3  12.837 ± 2.326  ops/ms
ClientPb.listUser                        thrpt       3  10.477 ± 0.491  ops/ms
ClientPb.createUser                       avgt       3   2.504 ± 0.376   ms/op
ClientPb.existUser                        avgt       3   2.436 ± 0.220   ms/op
ClientPb.getUser                          avgt       3   2.529 ± 0.344   ms/op
ClientPb.listUser                         avgt       3   3.033 ± 0.433   ms/op
ClientPb.createUser                     sample  376607   2.547 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.612           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.752           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.916           ms/op
ClientPb.createUser:createUser·p1.00    sample          19.333           ms/op
ClientPb.existUser                      sample  391799   2.449 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.974           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.482           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.781           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.481           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.680           ms/op
ClientPb.getUser                        sample  385089   2.491 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.815           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.781           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.820           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.541           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.876           ms/op
ClientPb.listUser                       sample  314667   3.048 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.644           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.986           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.936           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.718           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.279           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.691           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.960           ms/op
