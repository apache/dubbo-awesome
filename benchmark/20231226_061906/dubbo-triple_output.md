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
# Warmup Iteration   1: 5.007 ops/ms
# Warmup Iteration   2: 12.003 ops/ms
# Warmup Iteration   3: 12.164 ops/ms
Iteration   1: 12.426 ops/ms
Iteration   2: 12.442 ops/ms
Iteration   3: 12.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.470 ±(99.9%) 1.166 ops/ms [Average]
  (min, avg, max) = (12.426, 12.470, 12.544), stdev = 0.064
  CI (99.9%): [11.304, 13.637] (assumes normal distribution)


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
# Warmup Iteration   1: 8.314 ops/ms
# Warmup Iteration   2: 12.932 ops/ms
# Warmup Iteration   3: 12.901 ops/ms
Iteration   1: 13.022 ops/ms
Iteration   2: 13.091 ops/ms
Iteration   3: 13.011 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.041 ±(99.9%) 0.784 ops/ms [Average]
  (min, avg, max) = (13.011, 13.041, 13.091), stdev = 0.043
  CI (99.9%): [12.258, 13.825] (assumes normal distribution)


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
# Warmup Iteration   1: 7.617 ops/ms
# Warmup Iteration   2: 12.385 ops/ms
# Warmup Iteration   3: 12.580 ops/ms
Iteration   1: 12.729 ops/ms
Iteration   2: 12.931 ops/ms
Iteration   3: 12.653 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.771 ±(99.9%) 2.626 ops/ms [Average]
  (min, avg, max) = (12.653, 12.771, 12.931), stdev = 0.144
  CI (99.9%): [10.145, 15.397] (assumes normal distribution)


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
# Warmup Iteration   1: 6.570 ops/ms
# Warmup Iteration   2: 10.484 ops/ms
# Warmup Iteration   3: 10.473 ops/ms
Iteration   1: 10.590 ops/ms
Iteration   2: 10.594 ops/ms
Iteration   3: 10.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.595 ±(99.9%) 0.090 ops/ms [Average]
  (min, avg, max) = (10.590, 10.595, 10.600), stdev = 0.005
  CI (99.9%): [10.505, 10.685] (assumes normal distribution)


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
# Warmup Iteration   1: 4.310 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.658 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.004 ms/op
Iteration   1: 2.555 ±(99.9%) 0.004 ms/op
Iteration   2: 2.535 ±(99.9%) 0.004 ms/op
Iteration   3: 2.508 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.533 ±(99.9%) 0.425 ms/op [Average]
  (min, avg, max) = (2.508, 2.533, 2.555), stdev = 0.023
  CI (99.9%): [2.107, 2.958] (assumes normal distribution)


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
# Warmup Iteration   1: 3.670 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.467 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.004 ms/op
Iteration   1: 2.478 ±(99.9%) 0.003 ms/op
Iteration   2: 2.483 ±(99.9%) 0.004 ms/op
Iteration   3: 2.458 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.473 ±(99.9%) 0.243 ms/op [Average]
  (min, avg, max) = (2.458, 2.473, 2.483), stdev = 0.013
  CI (99.9%): [2.230, 2.716] (assumes normal distribution)


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
# Warmup Iteration   1: 4.073 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.567 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.004 ms/op
Iteration   1: 2.539 ±(99.9%) 0.003 ms/op
Iteration   2: 2.555 ±(99.9%) 0.004 ms/op
Iteration   3: 2.538 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.544 ±(99.9%) 0.174 ms/op [Average]
  (min, avg, max) = (2.538, 2.544, 2.555), stdev = 0.010
  CI (99.9%): [2.370, 2.718] (assumes normal distribution)


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
# Warmup Iteration   1: 4.730 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.005 ms/op
Iteration   1: 3.083 ±(99.9%) 0.006 ms/op
Iteration   2: 3.067 ±(99.9%) 0.004 ms/op
Iteration   3: 3.056 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.068 ±(99.9%) 0.248 ms/op [Average]
  (min, avg, max) = (3.056, 3.068, 3.083), stdev = 0.014
  CI (99.9%): [2.820, 3.316] (assumes normal distribution)


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
# Warmup Iteration   1: 4.268 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.676 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.006 ms/op
Iteration   1: 2.512 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.995 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.711 ms/op
                 createUser·p0.999:  11.956 ms/op
                 createUser·p0.9999: 14.242 ms/op
                 createUser·p1.00:   15.516 ms/op

Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.012 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.740 ms/op
                 createUser·p0.999:  9.533 ms/op
                 createUser·p0.9999: 12.470 ms/op
                 createUser·p1.00:   13.025 ms/op

Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.819 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.879 ms/op
                 createUser·p0.999:  8.585 ms/op
                 createUser·p0.9999: 11.092 ms/op
                 createUser·p1.00:   11.174 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382034
  mean =      2.511 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 183154 
    [ 2.500,  3.750) = 194787 
    [ 3.750,  5.000) = 3216 
    [ 5.000,  6.250) = 376 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 125 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.785 ms/op
     p(99.9000) =      9.797 ms/op
     p(99.9900) =     13.130 ms/op
     p(99.9990) =     14.926 ms/op
     p(99.9999) =     15.516 ms/op
    p(100.0000) =     15.516 ms/op


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
# Warmup Iteration   1: 3.707 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.496 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.005 ms/op
Iteration   1: 2.482 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.835 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.699 ms/op
                 existUser·p0.999:  8.421 ms/op
                 existUser·p0.9999: 13.572 ms/op
                 existUser·p1.00:   14.762 ms/op

Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.007 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.559 ms/op
                 existUser·p0.999:  7.040 ms/op
                 existUser·p0.9999: 13.091 ms/op
                 existUser·p1.00:   14.451 ms/op

Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.809 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.879 ms/op
                 existUser·p0.999:  6.520 ms/op
                 existUser·p0.9999: 14.624 ms/op
                 existUser·p1.00:   15.090 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387677
  mean =      2.474 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 192864 
    [ 2.500,  3.750) = 191018 
    [ 3.750,  5.000) = 2882 
    [ 5.000,  6.250) = 413 
    [ 6.250,  7.500) = 72 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =      6.928 ms/op
     p(99.9900) =     13.730 ms/op
     p(99.9990) =     15.001 ms/op
     p(99.9999) =     15.090 ms/op
    p(100.0000) =     15.090 ms/op


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
# Warmup Iteration   1: 4.167 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.671 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.006 ms/op
Iteration   1: 2.528 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.757 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.629 ms/op
                 getUser·p0.999:  11.445 ms/op
                 getUser·p0.9999: 14.025 ms/op
                 getUser·p1.00:   14.664 ms/op

Iteration   2: 2.561 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.967 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.129 ms/op
                 getUser·p0.95:   3.318 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  9.801 ms/op
                 getUser·p0.9999: 13.329 ms/op
                 getUser·p1.00:   14.008 ms/op

Iteration   3: 2.534 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.729 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   3.934 ms/op
                 getUser·p0.999:  8.405 ms/op
                 getUser·p0.9999: 11.764 ms/op
                 getUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377414
  mean =      2.541 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 82 
    [ 1.250,  2.500) = 184214 
    [ 2.500,  3.750) = 187623 
    [ 3.750,  5.000) = 4228 
    [ 5.000,  6.250) = 797 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 67 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      4.022 ms/op
     p(99.9000) =      8.457 ms/op
     p(99.9900) =     13.636 ms/op
     p(99.9990) =     14.553 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


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
# Warmup Iteration   1: 4.821 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.008 ms/op
Iteration   1: 2.987 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.029 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  8.487 ms/op
                 listUser·p0.9999: 10.322 ms/op
                 listUser·p1.00:   11.977 ms/op

Iteration   2: 2.978 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.849 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.563 ms/op
                 listUser·p0.9999: 10.965 ms/op
                 listUser·p1.00:   12.124 ms/op

Iteration   3: 2.989 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.721 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  9.978 ms/op
                 listUser·p0.9999: 11.692 ms/op
                 listUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321336
  mean =      2.985 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 146 
    [ 1.250,  2.500) = 98034 
    [ 2.500,  3.750) = 186483 
    [ 3.750,  5.000) = 29962 
    [ 5.000,  6.250) = 5483 
    [ 6.250,  7.500) = 586 
    [ 7.500,  8.750) = 188 
    [ 8.750, 10.000) = 262 
    [10.000, 11.250) = 173 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      9.350 ms/op
     p(99.9900) =     11.022 ms/op
     p(99.9990) =     11.956 ms/op
     p(99.9999) =     12.206 ms/op
    p(100.0000) =     12.206 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.470 ± 1.166  ops/ms
ClientPb.existUser                       thrpt       3  13.041 ± 0.784  ops/ms
ClientPb.getUser                         thrpt       3  12.771 ± 2.626  ops/ms
ClientPb.listUser                        thrpt       3  10.595 ± 0.090  ops/ms
ClientPb.createUser                       avgt       3   2.533 ± 0.425   ms/op
ClientPb.existUser                        avgt       3   2.473 ± 0.243   ms/op
ClientPb.getUser                          avgt       3   2.544 ± 0.174   ms/op
ClientPb.listUser                         avgt       3   3.068 ± 0.248   ms/op
ClientPb.createUser                     sample  382034   2.511 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.819           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.785           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.797           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.130           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.516           ms/op
ClientPb.existUser                      sample  387677   2.474 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.809           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.928           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.730           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.090           ms/op
ClientPb.getUser                        sample  377414   2.541 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.729           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.556           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.232           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.022           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.457           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.636           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.664           ms/op
ClientPb.listUser                       sample  321336   2.985 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.721           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.838           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.350           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.022           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.206           ms/op
