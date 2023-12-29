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
# Warmup Iteration   1: 4.562 ops/ms
# Warmup Iteration   2: 11.408 ops/ms
# Warmup Iteration   3: 12.053 ops/ms
Iteration   1: 12.050 ops/ms
Iteration   2: 12.158 ops/ms
Iteration   3: 12.287 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.165 ±(99.9%) 2.171 ops/ms [Average]
  (min, avg, max) = (12.050, 12.165, 12.287), stdev = 0.119
  CI (99.9%): [9.994, 14.336] (assumes normal distribution)


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
# Warmup Iteration   1: 7.565 ops/ms
# Warmup Iteration   2: 12.789 ops/ms
# Warmup Iteration   3: 12.877 ops/ms
Iteration   1: 12.938 ops/ms
Iteration   2: 12.894 ops/ms
Iteration   3: 12.829 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.887 ±(99.9%) 1.000 ops/ms [Average]
  (min, avg, max) = (12.829, 12.887, 12.938), stdev = 0.055
  CI (99.9%): [11.887, 13.887] (assumes normal distribution)


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
# Warmup Iteration   1: 7.365 ops/ms
# Warmup Iteration   2: 12.138 ops/ms
# Warmup Iteration   3: 12.468 ops/ms
Iteration   1: 12.630 ops/ms
Iteration   2: 12.466 ops/ms
Iteration   3: 12.679 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.592 ±(99.9%) 2.038 ops/ms [Average]
  (min, avg, max) = (12.466, 12.592, 12.679), stdev = 0.112
  CI (99.9%): [10.553, 14.630] (assumes normal distribution)


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
# Warmup Iteration   1: 6.607 ops/ms
# Warmup Iteration   2: 10.329 ops/ms
# Warmup Iteration   3: 10.471 ops/ms
Iteration   1: 10.585 ops/ms
Iteration   2: 10.504 ops/ms
Iteration   3: 10.487 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.525 ±(99.9%) 0.949 ops/ms [Average]
  (min, avg, max) = (10.487, 10.525, 10.585), stdev = 0.052
  CI (99.9%): [9.576, 11.474] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.251 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.658 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.597 ±(99.9%) 0.004 ms/op
Iteration   1: 2.608 ±(99.9%) 0.003 ms/op
Iteration   2: 2.626 ±(99.9%) 0.004 ms/op
Iteration   3: 2.613 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.616 ±(99.9%) 0.168 ms/op [Average]
  (min, avg, max) = (2.608, 2.616, 2.626), stdev = 0.009
  CI (99.9%): [2.448, 2.783] (assumes normal distribution)


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
# Warmup Iteration   1: 3.875 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.517 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.003 ms/op
Iteration   1: 2.497 ±(99.9%) 0.003 ms/op
Iteration   2: 2.490 ±(99.9%) 0.003 ms/op
Iteration   3: 2.493 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.494 ±(99.9%) 0.060 ms/op [Average]
  (min, avg, max) = (2.490, 2.494, 2.497), stdev = 0.003
  CI (99.9%): [2.434, 2.553] (assumes normal distribution)


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
# Warmup Iteration   1: 3.922 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.561 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.004 ms/op
Iteration   1: 2.557 ±(99.9%) 0.004 ms/op
Iteration   2: 2.537 ±(99.9%) 0.004 ms/op
Iteration   3: 2.562 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.552 ±(99.9%) 0.238 ms/op [Average]
  (min, avg, max) = (2.537, 2.552, 2.562), stdev = 0.013
  CI (99.9%): [2.314, 2.790] (assumes normal distribution)


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
# Warmup Iteration   1: 4.995 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.006 ms/op
Iteration   1: 3.062 ±(99.9%) 0.006 ms/op
Iteration   2: 3.051 ±(99.9%) 0.005 ms/op
Iteration   3: 3.028 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.047 ±(99.9%) 0.318 ms/op [Average]
  (min, avg, max) = (3.028, 3.047, 3.062), stdev = 0.017
  CI (99.9%): [2.729, 3.365] (assumes normal distribution)


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
# Warmup Iteration   1: 4.254 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.745 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.602 ±(99.9%) 0.006 ms/op
Iteration   1: 2.597 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.893 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.150 ms/op
                 createUser·p0.95:   3.273 ms/op
                 createUser·p0.99:   3.867 ms/op
                 createUser·p0.999:  12.091 ms/op
                 createUser·p0.9999: 14.261 ms/op
                 createUser·p1.00:   15.188 ms/op

Iteration   2: 2.590 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.081 ms/op
                 createUser·p0.50:   2.671 ms/op
                 createUser·p0.90:   3.138 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.731 ms/op
                 createUser·p0.999:  10.118 ms/op
                 createUser·p0.9999: 15.187 ms/op
                 createUser·p1.00:   17.170 ms/op

Iteration   3: 2.604 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.909 ms/op
                 createUser·p0.50:   2.666 ms/op
                 createUser·p0.90:   3.166 ms/op
                 createUser·p0.95:   3.285 ms/op
                 createUser·p0.99:   3.953 ms/op
                 createUser·p0.999:  6.599 ms/op
                 createUser·p0.9999: 11.649 ms/op
                 createUser·p1.00:   14.860 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 369287
  mean =      2.597 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 174340 
    [ 2.500,  3.750) = 190457 
    [ 3.750,  5.000) = 3512 
    [ 5.000,  6.250) = 497 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      2.666 ms/op
     p(90.0000) =      3.150 ms/op
     p(95.0000) =      3.265 ms/op
     p(99.0000) =      3.850 ms/op
     p(99.9000) =      9.269 ms/op
     p(99.9900) =     14.289 ms/op
     p(99.9990) =     17.059 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


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
# Warmup Iteration   1: 3.839 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.539 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
Iteration   1: 2.521 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.925 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.064 ms/op
                 existUser·p0.95:   3.183 ms/op
                 existUser·p0.99:   3.822 ms/op
                 existUser·p0.999:  10.903 ms/op
                 existUser·p0.9999: 14.287 ms/op
                 existUser·p1.00:   14.402 ms/op

Iteration   2: 2.507 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.017 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.469 ms/op
                 existUser·p0.999:  5.863 ms/op
                 existUser·p0.9999: 13.488 ms/op
                 existUser·p1.00:   14.189 ms/op

Iteration   3: 2.536 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.161 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.084 ms/op
                 existUser·p0.95:   3.232 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  9.272 ms/op
                 existUser·p0.9999: 12.648 ms/op
                 existUser·p1.00:   13.025 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 380335
  mean =      2.521 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 186234 
    [ 2.500,  3.750) = 189415 
    [ 3.750,  5.000) = 3359 
    [ 5.000,  6.250) = 775 
    [ 6.250,  7.500) = 85 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 143 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 109 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.925 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.895 ms/op
     p(99.9000) =      8.744 ms/op
     p(99.9900) =     13.631 ms/op
     p(99.9990) =     14.323 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


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
# Warmup Iteration   1: 3.928 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.611 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.006 ms/op
Iteration   1: 2.542 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.015 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   3.801 ms/op
                 getUser·p0.999:  12.079 ms/op
                 getUser·p0.9999: 14.364 ms/op
                 getUser·p1.00:   15.024 ms/op

Iteration   2: 2.556 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.881 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.121 ms/op
                 getUser·p0.95:   3.285 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  9.696 ms/op
                 getUser·p0.9999: 14.467 ms/op
                 getUser·p1.00:   15.532 ms/op

Iteration   3: 2.552 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.961 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.125 ms/op
                 getUser·p0.95:   3.285 ms/op
                 getUser·p0.99:   3.953 ms/op
                 getUser·p0.999:  9.437 ms/op
                 getUser·p0.9999: 11.895 ms/op
                 getUser·p1.00:   12.190 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376134
  mean =      2.550 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 180714 
    [ 2.500,  3.750) = 189783 
    [ 3.750,  5.000) = 4494 
    [ 5.000,  6.250) = 601 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 80 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      3.265 ms/op
     p(99.0000) =      3.961 ms/op
     p(99.9000) =      9.695 ms/op
     p(99.9900) =     14.195 ms/op
     p(99.9990) =     14.946 ms/op
     p(99.9999) =     15.532 ms/op
    p(100.0000) =     15.532 ms/op


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
# Warmup Iteration   1: 4.920 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.156 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.009 ms/op
Iteration   1: 3.036 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.899 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.379 ms/op
                 listUser·p0.9999: 13.410 ms/op
                 listUser·p1.00:   14.647 ms/op

Iteration   2: 3.053 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.862 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.601 ms/op
                 listUser·p0.9999: 13.018 ms/op
                 listUser·p1.00:   13.206 ms/op

Iteration   3: 3.017 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.845 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.491 ms/op
                 listUser·p0.999:  9.617 ms/op
                 listUser·p0.9999: 11.315 ms/op
                 listUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315953
  mean =      3.035 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 107 
    [ 1.250,  2.500) = 86290 
    [ 2.500,  3.750) = 189914 
    [ 3.750,  5.000) = 32466 
    [ 5.000,  6.250) = 5833 
    [ 6.250,  7.500) = 659 
    [ 7.500,  8.750) = 193 
    [ 8.750, 10.000) = 240 
    [10.000, 11.250) = 173 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.568 ms/op
     p(99.9900) =     12.881 ms/op
     p(99.9990) =     14.192 ms/op
     p(99.9999) =     14.647 ms/op
    p(100.0000) =     14.647 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.165 ± 2.171  ops/ms
ClientPb.existUser                       thrpt       3  12.887 ± 1.000  ops/ms
ClientPb.getUser                         thrpt       3  12.592 ± 2.038  ops/ms
ClientPb.listUser                        thrpt       3  10.525 ± 0.949  ops/ms
ClientPb.createUser                       avgt       3   2.616 ± 0.168   ms/op
ClientPb.existUser                        avgt       3   2.494 ± 0.060   ms/op
ClientPb.getUser                          avgt       3   2.552 ± 0.238   ms/op
ClientPb.listUser                         avgt       3   3.047 ± 0.318   ms/op
ClientPb.createUser                     sample  369287   2.597 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.893           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.666           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.265           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.850           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.269           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.289           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.170           ms/op
ClientPb.existUser                      sample  380335   2.521 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.925           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.552           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.183           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.895           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.744           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.631           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.402           ms/op
ClientPb.getUser                        sample  376134   2.550 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.881           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.572           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.265           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.961           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.695           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.195           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.532           ms/op
ClientPb.listUser                       sample  315953   3.035 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.845           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.568           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.881           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.647           ms/op
