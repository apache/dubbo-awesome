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
# Warmup Iteration   1: 4.817 ops/ms
# Warmup Iteration   2: 11.858 ops/ms
# Warmup Iteration   3: 12.191 ops/ms
Iteration   1: 12.336 ops/ms
Iteration   2: 12.283 ops/ms
Iteration   3: 12.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.357 ±(99.9%) 1.585 ops/ms [Average]
  (min, avg, max) = (12.283, 12.357, 12.453), stdev = 0.087
  CI (99.9%): [10.773, 13.942] (assumes normal distribution)


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
# Warmup Iteration   1: 8.070 ops/ms
# Warmup Iteration   2: 12.719 ops/ms
# Warmup Iteration   3: 12.850 ops/ms
Iteration   1: 12.810 ops/ms
Iteration   2: 12.866 ops/ms
Iteration   3: 12.915 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.864 ±(99.9%) 0.958 ops/ms [Average]
  (min, avg, max) = (12.810, 12.864, 12.915), stdev = 0.052
  CI (99.9%): [11.906, 13.821] (assumes normal distribution)


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
# Warmup Iteration   1: 7.338 ops/ms
# Warmup Iteration   2: 12.507 ops/ms
# Warmup Iteration   3: 12.498 ops/ms
Iteration   1: 12.753 ops/ms
Iteration   2: 12.636 ops/ms
Iteration   3: 12.702 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.697 ±(99.9%) 1.075 ops/ms [Average]
  (min, avg, max) = (12.636, 12.697, 12.753), stdev = 0.059
  CI (99.9%): [11.622, 13.772] (assumes normal distribution)


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
# Warmup Iteration   1: 6.885 ops/ms
# Warmup Iteration   2: 10.355 ops/ms
# Warmup Iteration   3: 10.480 ops/ms
Iteration   1: 10.532 ops/ms
Iteration   2: 10.561 ops/ms
Iteration   3: 10.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.552 ±(99.9%) 0.314 ops/ms [Average]
  (min, avg, max) = (10.532, 10.552, 10.563), stdev = 0.017
  CI (99.9%): [10.238, 10.866] (assumes normal distribution)


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
# Warmup Iteration   1: 4.050 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.625 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.570 ±(99.9%) 0.004 ms/op
Iteration   1: 2.562 ±(99.9%) 0.004 ms/op
Iteration   2: 2.577 ±(99.9%) 0.005 ms/op
Iteration   3: 2.547 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.562 ±(99.9%) 0.269 ms/op [Average]
  (min, avg, max) = (2.547, 2.562, 2.577), stdev = 0.015
  CI (99.9%): [2.293, 2.831] (assumes normal distribution)


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
# Warmup Iteration   1: 3.771 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.488 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.004 ms/op
Iteration   1: 2.491 ±(99.9%) 0.004 ms/op
Iteration   2: 2.501 ±(99.9%) 0.004 ms/op
Iteration   3: 2.483 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.492 ±(99.9%) 0.170 ms/op [Average]
  (min, avg, max) = (2.483, 2.492, 2.501), stdev = 0.009
  CI (99.9%): [2.322, 2.661] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.891 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.583 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.004 ms/op
Iteration   1: 2.530 ±(99.9%) 0.005 ms/op
Iteration   2: 2.531 ±(99.9%) 0.005 ms/op
Iteration   3: 2.541 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.534 ±(99.9%) 0.111 ms/op [Average]
  (min, avg, max) = (2.530, 2.534, 2.541), stdev = 0.006
  CI (99.9%): [2.423, 2.645] (assumes normal distribution)


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
# Warmup Iteration   1: 4.889 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.006 ms/op
Iteration   1: 3.065 ±(99.9%) 0.006 ms/op
Iteration   2: 3.070 ±(99.9%) 0.006 ms/op
Iteration   3: 3.038 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.057 ±(99.9%) 0.314 ms/op [Average]
  (min, avg, max) = (3.038, 3.057, 3.070), stdev = 0.017
  CI (99.9%): [2.744, 3.371] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.243 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.648 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.563 ±(99.9%) 0.006 ms/op
Iteration   1: 2.538 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.597 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.781 ms/op
                 createUser·p0.999:  11.191 ms/op
                 createUser·p0.9999: 13.671 ms/op
                 createUser·p1.00:   13.976 ms/op

Iteration   2: 2.559 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.230 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  8.980 ms/op
                 createUser·p0.9999: 12.059 ms/op
                 createUser·p1.00:   12.485 ms/op

Iteration   3: 2.560 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.858 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   3.903 ms/op
                 createUser·p0.999:  7.745 ms/op
                 createUser·p0.9999: 11.346 ms/op
                 createUser·p1.00:   13.156 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375767
  mean =      2.552 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 177967 
    [ 2.500,  3.750) = 192675 
    [ 3.750,  5.000) = 3955 
    [ 5.000,  6.250) = 688 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 139 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      2.634 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      3.936 ms/op
     p(99.9000) =      8.087 ms/op
     p(99.9900) =     13.074 ms/op
     p(99.9990) =     13.852 ms/op
     p(99.9999) =     13.976 ms/op
    p(100.0000) =     13.976 ms/op


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
# Warmup Iteration   1: 3.787 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.532 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
Iteration   1: 2.506 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.795 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   3.572 ms/op
                 existUser·p0.999:  11.017 ms/op
                 existUser·p0.9999: 13.783 ms/op
                 existUser·p1.00:   14.828 ms/op

Iteration   2: 2.505 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.126 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   3.604 ms/op
                 existUser·p0.999:  5.839 ms/op
                 existUser·p0.9999: 13.525 ms/op
                 existUser·p1.00:   14.402 ms/op

Iteration   3: 2.516 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.416 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.072 ms/op
                 existUser·p0.95:   3.228 ms/op
                 existUser·p0.99:   4.076 ms/op
                 existUser·p0.999:  8.700 ms/op
                 existUser·p0.9999: 11.998 ms/op
                 existUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 382183
  mean =      2.509 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 186185 
    [ 2.500,  3.750) = 192152 
    [ 3.750,  5.000) = 2879 
    [ 5.000,  6.250) = 505 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.416 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.744 ms/op
     p(99.9000) =      6.469 ms/op
     p(99.9900) =     13.582 ms/op
     p(99.9990) =     14.665 ms/op
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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.801 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.585 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.562 ±(99.9%) 0.006 ms/op
Iteration   1: 2.530 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.994 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.723 ms/op
                 getUser·p0.999:  11.747 ms/op
                 getUser·p0.9999: 13.670 ms/op
                 getUser·p1.00:   14.418 ms/op

Iteration   2: 2.525 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.087 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.727 ms/op
                 getUser·p0.999:  8.434 ms/op
                 getUser·p0.9999: 12.998 ms/op
                 getUser·p1.00:   13.959 ms/op

Iteration   3: 2.585 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.887 ms/op
                 getUser·p0.50:   2.613 ms/op
                 getUser·p0.90:   3.138 ms/op
                 getUser·p0.95:   3.338 ms/op
                 getUser·p0.99:   4.833 ms/op
                 getUser·p0.999:  8.684 ms/op
                 getUser·p0.9999: 17.760 ms/op
                 getUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376671
  mean =      2.546 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 183954 
    [ 2.500,  3.750) = 186889 
    [ 3.750,  5.000) = 4262 
    [ 5.000,  6.250) = 1005 
    [ 6.250,  7.500) = 117 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      4.092 ms/op
     p(99.9000) =      8.623 ms/op
     p(99.9900) =     13.926 ms/op
     p(99.9990) =     18.128 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


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
# Warmup Iteration   1: 4.558 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.008 ms/op
Iteration   1: 3.041 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.893 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  9.568 ms/op
                 listUser·p0.9999: 12.493 ms/op
                 listUser·p1.00:   13.238 ms/op

Iteration   2: 3.037 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.962 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.650 ms/op
                 listUser·p0.9999: 11.141 ms/op
                 listUser·p1.00:   11.665 ms/op

Iteration   3: 3.007 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.727 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  8.716 ms/op
                 listUser·p0.9999: 10.154 ms/op
                 listUser·p1.00:   10.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316755
  mean =      3.028 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 111 
    [ 1.250,  2.500) = 88690 
    [ 2.500,  3.750) = 187058 
    [ 3.750,  5.000) = 33241 
    [ 5.000,  6.250) = 6136 
    [ 6.250,  7.500) = 776 
    [ 7.500,  8.750) = 320 
    [ 8.750, 10.000) = 257 
    [10.000, 11.250) = 141 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      9.372 ms/op
     p(99.9900) =     11.179 ms/op
     p(99.9990) =     13.003 ms/op
     p(99.9999) =     13.238 ms/op
    p(100.0000) =     13.238 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.357 ± 1.585  ops/ms
ClientPb.existUser                       thrpt       3  12.864 ± 0.958  ops/ms
ClientPb.getUser                         thrpt       3  12.697 ± 1.075  ops/ms
ClientPb.listUser                        thrpt       3  10.552 ± 0.314  ops/ms
ClientPb.createUser                       avgt       3   2.562 ± 0.269   ms/op
ClientPb.existUser                        avgt       3   2.492 ± 0.170   ms/op
ClientPb.getUser                          avgt       3   2.534 ± 0.111   ms/op
ClientPb.listUser                         avgt       3   3.057 ± 0.314   ms/op
ClientPb.createUser                     sample  375767   2.552 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.597           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.634           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.224           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.936           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.087           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.074           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.976           ms/op
ClientPb.existUser                      sample  382183   2.509 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.416           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.552           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.183           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.744           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.469           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.582           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.828           ms/op
ClientPb.getUser                        sample  376671   2.546 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.887           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.568           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.224           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.092           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.623           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.926           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.874           ms/op
ClientPb.listUser                       sample  316755   3.028 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.727           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.372           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.179           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.238           ms/op
