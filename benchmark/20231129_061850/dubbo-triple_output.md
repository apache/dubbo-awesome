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
# Warmup Iteration   1: 4.728 ops/ms
# Warmup Iteration   2: 11.801 ops/ms
# Warmup Iteration   3: 12.022 ops/ms
Iteration   1: 12.455 ops/ms
Iteration   2: 12.491 ops/ms
Iteration   3: 12.469 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.472 ±(99.9%) 0.330 ops/ms [Average]
  (min, avg, max) = (12.455, 12.472, 12.491), stdev = 0.018
  CI (99.9%): [12.142, 12.802] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 7.122 ops/ms
# Warmup Iteration   2: 12.774 ops/ms
# Warmup Iteration   3: 12.779 ops/ms
Iteration   1: 12.737 ops/ms
Iteration   2: 12.870 ops/ms
Iteration   3: 12.771 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.793 ±(99.9%) 1.261 ops/ms [Average]
  (min, avg, max) = (12.737, 12.793, 12.870), stdev = 0.069
  CI (99.9%): [11.531, 14.054] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.440 ops/ms
# Warmup Iteration   2: 12.223 ops/ms
# Warmup Iteration   3: 12.674 ops/ms
Iteration   1: 12.801 ops/ms
Iteration   2: 12.560 ops/ms
Iteration   3: 12.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.675 ±(99.9%) 2.211 ops/ms [Average]
  (min, avg, max) = (12.560, 12.675, 12.801), stdev = 0.121
  CI (99.9%): [10.464, 14.886] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.879 ops/ms
# Warmup Iteration   2: 10.422 ops/ms
# Warmup Iteration   3: 10.403 ops/ms
Iteration   1: 10.614 ops/ms
Iteration   2: 10.641 ops/ms
Iteration   3: 10.519 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.591 ±(99.9%) 1.172 ops/ms [Average]
  (min, avg, max) = (10.519, 10.591, 10.641), stdev = 0.064
  CI (99.9%): [9.419, 11.763] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.162 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.584 ±(99.9%) 0.003 ms/op
Iteration   1: 2.615 ±(99.9%) 0.005 ms/op
Iteration   2: 2.546 ±(99.9%) 0.004 ms/op
Iteration   3: 2.550 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.570 ±(99.9%) 0.707 ms/op [Average]
  (min, avg, max) = (2.546, 2.570, 2.615), stdev = 0.039
  CI (99.9%): [1.863, 3.278] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.801 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.498 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.004 ms/op
Iteration   1: 2.490 ±(99.9%) 0.004 ms/op
Iteration   2: 2.503 ±(99.9%) 0.004 ms/op
Iteration   3: 2.496 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.496 ±(99.9%) 0.128 ms/op [Average]
  (min, avg, max) = (2.490, 2.496, 2.503), stdev = 0.007
  CI (99.9%): [2.369, 2.624] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.909 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.561 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.003 ms/op
Iteration   1: 2.510 ±(99.9%) 0.004 ms/op
Iteration   2: 2.498 ±(99.9%) 0.004 ms/op
Iteration   3: 2.512 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.506 ±(99.9%) 0.138 ms/op [Average]
  (min, avg, max) = (2.498, 2.506, 2.512), stdev = 0.008
  CI (99.9%): [2.369, 2.644] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.639 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.005 ms/op
Iteration   1: 3.019 ±(99.9%) 0.005 ms/op
Iteration   2: 2.992 ±(99.9%) 0.006 ms/op
Iteration   3: 3.029 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.013 ±(99.9%) 0.343 ms/op [Average]
  (min, avg, max) = (2.992, 3.013, 3.029), stdev = 0.019
  CI (99.9%): [2.670, 3.357] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.284 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.679 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.006 ms/op
Iteration   1: 2.522 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.943 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.928 ms/op
                 createUser·p0.999:  12.348 ms/op
                 createUser·p0.9999: 14.292 ms/op
                 createUser·p1.00:   14.975 ms/op

Iteration   2: 2.529 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.904 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.862 ms/op
                 createUser·p0.999:  10.030 ms/op
                 createUser·p0.9999: 13.381 ms/op
                 createUser·p1.00:   14.516 ms/op

Iteration   3: 2.544 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.992 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   4.043 ms/op
                 createUser·p0.999:  8.373 ms/op
                 createUser·p0.9999: 9.969 ms/op
                 createUser·p1.00:   10.781 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378844
  mean =      2.532 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 181793 
    [ 2.500,  3.750) = 191722 
    [ 3.750,  5.000) = 4214 
    [ 5.000,  6.250) = 628 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.944 ms/op
     p(99.9000) =      8.391 ms/op
     p(99.9900) =     13.977 ms/op
     p(99.9990) =     14.629 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.778 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.559 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.006 ms/op
Iteration   1: 2.536 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.956 ms/op
                 existUser·p0.50:   2.609 ms/op
                 existUser·p0.90:   3.080 ms/op
                 existUser·p0.95:   3.187 ms/op
                 existUser·p0.99:   3.781 ms/op
                 existUser·p0.999:  5.578 ms/op
                 existUser·p0.9999: 14.041 ms/op
                 existUser·p1.00:   14.975 ms/op

Iteration   2: 2.521 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.971 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.174 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  8.943 ms/op
                 existUser·p0.9999: 13.915 ms/op
                 existUser·p1.00:   14.762 ms/op

Iteration   3: 2.526 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.940 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.068 ms/op
                 existUser·p0.95:   3.183 ms/op
                 existUser·p0.99:   3.916 ms/op
                 existUser·p0.999:  6.906 ms/op
                 existUser·p0.9999: 12.239 ms/op
                 existUser·p1.00:   12.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 379397
  mean =      2.528 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 184194 
    [ 2.500,  3.750) = 190292 
    [ 3.750,  5.000) = 3529 
    [ 5.000,  6.250) = 893 
    [ 6.250,  7.500) = 100 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.936 ms/op
     p(99.9000) =      6.760 ms/op
     p(99.9900) =     13.812 ms/op
     p(99.9990) =     14.736 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.906 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.613 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.006 ms/op
Iteration   1: 2.542 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.714 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   3.969 ms/op
                 getUser·p0.999:  11.895 ms/op
                 getUser·p0.9999: 13.763 ms/op
                 getUser·p1.00:   13.910 ms/op

Iteration   2: 2.546 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.679 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.256 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  10.321 ms/op
                 getUser·p0.9999: 15.441 ms/op
                 getUser·p1.00:   15.696 ms/op

Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.738 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.690 ms/op
                 getUser·p0.999:  8.194 ms/op
                 getUser·p0.9999: 11.179 ms/op
                 getUser·p1.00:   11.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378994
  mean =      2.531 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 82 
    [ 1.250,  2.500) = 185104 
    [ 2.500,  3.750) = 188176 
    [ 3.750,  5.000) = 4526 
    [ 5.000,  6.250) = 691 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      4.014 ms/op
     p(99.9000) =      8.405 ms/op
     p(99.9900) =     13.844 ms/op
     p(99.9990) =     15.588 ms/op
     p(99.9999) =     15.696 ms/op
    p(100.0000) =     15.696 ms/op


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
# Warmup Iteration   1: 4.758 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.009 ms/op
Iteration   1: 3.029 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.844 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.132 ms/op
                 listUser·p0.9999: 11.174 ms/op
                 listUser·p1.00:   12.108 ms/op

Iteration   2: 3.035 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.972 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.241 ms/op
                 listUser·p0.9999: 13.630 ms/op
                 listUser·p1.00:   14.729 ms/op

Iteration   3: 3.070 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.061 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   5.915 ms/op
                 listUser·p0.999:  10.093 ms/op
                 listUser·p0.9999: 12.232 ms/op
                 listUser·p1.00:   12.943 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315074
  mean =      3.045 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 112 
    [ 1.250,  2.500) = 87547 
    [ 2.500,  3.750) = 185373 
    [ 3.750,  5.000) = 33525 
    [ 5.000,  6.250) = 6997 
    [ 6.250,  7.500) = 810 
    [ 7.500,  8.750) = 263 
    [ 8.750, 10.000) = 210 
    [10.000, 11.250) = 160 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =      9.404 ms/op
     p(99.9900) =     12.614 ms/op
     p(99.9990) =     14.112 ms/op
     p(99.9999) =     14.729 ms/op
    p(100.0000) =     14.729 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.472 ± 0.330  ops/ms
ClientPb.existUser                       thrpt       3  12.793 ± 1.261  ops/ms
ClientPb.getUser                         thrpt       3  12.675 ± 2.211  ops/ms
ClientPb.listUser                        thrpt       3  10.591 ± 1.172  ops/ms
ClientPb.createUser                       avgt       3   2.570 ± 0.707   ms/op
ClientPb.existUser                        avgt       3   2.496 ± 0.128   ms/op
ClientPb.getUser                          avgt       3   2.506 ± 0.138   ms/op
ClientPb.listUser                         avgt       3   3.013 ± 0.343   ms/op
ClientPb.createUser                     sample  378844   2.532 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.904           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.944           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.391           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.977           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.975           ms/op
ClientPb.existUser                      sample  379397   2.528 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.940           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.585           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.178           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.936           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.760           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.812           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.975           ms/op
ClientPb.getUser                        sample  378994   2.531 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.679           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.556           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.224           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.014           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.405           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.844           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.696           ms/op
ClientPb.listUser                       sample  315074   3.045 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.844           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.949           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.726           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.404           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.614           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.729           ms/op
