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
# Warmup Iteration   1: 4.595 ops/ms
# Warmup Iteration   2: 12.007 ops/ms
# Warmup Iteration   3: 12.156 ops/ms
Iteration   1: 12.317 ops/ms
Iteration   2: 12.338 ops/ms
Iteration   3: 12.359 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.338 ±(99.9%) 0.381 ops/ms [Average]
  (min, avg, max) = (12.317, 12.338, 12.359), stdev = 0.021
  CI (99.9%): [11.957, 12.719] (assumes normal distribution)


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
# Warmup Iteration   1: 7.758 ops/ms
# Warmup Iteration   2: 12.569 ops/ms
# Warmup Iteration   3: 12.726 ops/ms
Iteration   1: 12.762 ops/ms
Iteration   2: 12.658 ops/ms
Iteration   3: 12.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.718 ±(99.9%) 0.978 ops/ms [Average]
  (min, avg, max) = (12.658, 12.718, 12.762), stdev = 0.054
  CI (99.9%): [11.740, 13.696] (assumes normal distribution)


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
# Warmup Iteration   1: 7.707 ops/ms
# Warmup Iteration   2: 11.944 ops/ms
# Warmup Iteration   3: 12.231 ops/ms
Iteration   1: 12.603 ops/ms
Iteration   2: 12.734 ops/ms
Iteration   3: 12.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.670 ±(99.9%) 1.197 ops/ms [Average]
  (min, avg, max) = (12.603, 12.670, 12.734), stdev = 0.066
  CI (99.9%): [11.473, 13.867] (assumes normal distribution)


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
# Warmup Iteration   1: 6.458 ops/ms
# Warmup Iteration   2: 10.477 ops/ms
# Warmup Iteration   3: 10.544 ops/ms
Iteration   1: 10.568 ops/ms
Iteration   2: 10.548 ops/ms
Iteration   3: 10.671 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.596 ±(99.9%) 1.206 ops/ms [Average]
  (min, avg, max) = (10.548, 10.596, 10.671), stdev = 0.066
  CI (99.9%): [9.390, 11.801] (assumes normal distribution)


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
# Warmup Iteration   1: 4.277 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.650 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.546 ±(99.9%) 0.005 ms/op
Iteration   1: 2.577 ±(99.9%) 0.004 ms/op
Iteration   2: 2.676 ±(99.9%) 0.005 ms/op
Iteration   3: 2.615 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.623 ±(99.9%) 0.915 ms/op [Average]
  (min, avg, max) = (2.577, 2.623, 2.676), stdev = 0.050
  CI (99.9%): [1.707, 3.538] (assumes normal distribution)


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
# Warmup Iteration   1: 3.851 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.457 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
Iteration   1: 2.504 ±(99.9%) 0.005 ms/op
Iteration   2: 2.456 ±(99.9%) 0.005 ms/op
Iteration   3: 2.470 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.477 ±(99.9%) 0.450 ms/op [Average]
  (min, avg, max) = (2.456, 2.477, 2.504), stdev = 0.025
  CI (99.9%): [2.026, 2.927] (assumes normal distribution)


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
# Warmup Iteration   1: 4.096 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.546 ±(99.9%) 0.004 ms/op
Iteration   1: 2.551 ±(99.9%) 0.005 ms/op
Iteration   2: 2.522 ±(99.9%) 0.003 ms/op
Iteration   3: 2.520 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.531 ±(99.9%) 0.319 ms/op [Average]
  (min, avg, max) = (2.520, 2.531, 2.551), stdev = 0.017
  CI (99.9%): [2.212, 2.850] (assumes normal distribution)


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
# Warmup Iteration   1: 4.768 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.005 ms/op
Iteration   1: 3.049 ±(99.9%) 0.007 ms/op
Iteration   2: 3.033 ±(99.9%) 0.005 ms/op
Iteration   3: 3.023 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.035 ±(99.9%) 0.234 ms/op [Average]
  (min, avg, max) = (3.023, 3.035, 3.049), stdev = 0.013
  CI (99.9%): [2.801, 3.269] (assumes normal distribution)


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
# Warmup Iteration   1: 4.619 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 2.753 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.610 ±(99.9%) 0.006 ms/op
Iteration   1: 2.559 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.846 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.768 ms/op
                 createUser·p0.999:  11.224 ms/op
                 createUser·p0.9999: 13.714 ms/op
                 createUser·p1.00:   14.483 ms/op

Iteration   2: 2.550 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.016 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.703 ms/op
                 createUser·p0.999:  9.867 ms/op
                 createUser·p0.9999: 12.829 ms/op
                 createUser·p1.00:   13.713 ms/op

Iteration   3: 2.591 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.835 ms/op
                 createUser·p0.50:   2.662 ms/op
                 createUser·p0.90:   3.150 ms/op
                 createUser·p0.95:   3.273 ms/op
                 createUser·p0.99:   3.916 ms/op
                 createUser·p0.999:  8.995 ms/op
                 createUser·p0.9999: 11.474 ms/op
                 createUser·p1.00:   14.189 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 373633
  mean =      2.566 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 29 
    [ 1.250,  2.500) = 176806 
    [ 2.500,  3.750) = 192749 
    [ 3.750,  5.000) = 3184 
    [ 5.000,  6.250) = 372 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 146 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      2.642 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      3.789 ms/op
     p(99.9000) =      9.492 ms/op
     p(99.9900) =     13.042 ms/op
     p(99.9990) =     14.164 ms/op
     p(99.9999) =     14.483 ms/op
    p(100.0000) =     14.483 ms/op


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
# Warmup Iteration   1: 3.646 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.500 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
Iteration   1: 2.498 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.112 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.158 ms/op
                 existUser·p0.99:   3.621 ms/op
                 existUser·p0.999:  11.142 ms/op
                 existUser·p0.9999: 16.368 ms/op
                 existUser·p1.00:   17.203 ms/op

Iteration   2: 2.480 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.683 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.613 ms/op
                 existUser·p0.999:  9.142 ms/op
                 existUser·p0.9999: 13.027 ms/op
                 existUser·p1.00:   13.386 ms/op

Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.862 ms/op
                 existUser·p0.50:   2.597 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.723 ms/op
                 existUser·p0.999:  8.906 ms/op
                 existUser·p0.9999: 12.785 ms/op
                 existUser·p1.00:   13.533 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385257
  mean =      2.489 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 186420 
    [ 2.500,  3.750) = 195586 
    [ 3.750,  5.000) = 2445 
    [ 5.000,  6.250) = 309 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 99 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.650 ms/op
     p(99.9000) =      8.958 ms/op
     p(99.9900) =     14.909 ms/op
     p(99.9990) =     17.044 ms/op
     p(99.9999) =     17.203 ms/op
    p(100.0000) =     17.203 ms/op


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
# Warmup Iteration   1: 4.087 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.595 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.572 ±(99.9%) 0.006 ms/op
Iteration   1: 2.521 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.923 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.654 ms/op
                 getUser·p0.999:  11.272 ms/op
                 getUser·p0.9999: 13.631 ms/op
                 getUser·p1.00:   14.205 ms/op

Iteration   2: 2.544 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.765 ms/op
                 getUser·p0.50:   2.617 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  9.486 ms/op
                 getUser·p0.9999: 11.672 ms/op
                 getUser·p1.00:   12.648 ms/op

Iteration   3: 2.542 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.923 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   3.936 ms/op
                 getUser·p0.999:  5.378 ms/op
                 getUser·p0.9999: 11.928 ms/op
                 getUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378383
  mean =      2.536 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 184419 
    [ 2.500,  3.750) = 188927 
    [ 3.750,  5.000) = 3714 
    [ 5.000,  6.250) = 849 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 115 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.928 ms/op
     p(99.9000) =      7.599 ms/op
     p(99.9900) =     13.435 ms/op
     p(99.9990) =     14.088 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.759 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.009 ms/op
Iteration   1: 3.010 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.839 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.419 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  8.864 ms/op
                 listUser·p0.9999: 10.797 ms/op
                 listUser·p1.00:   11.141 ms/op

Iteration   2: 3.014 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.890 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.650 ms/op
                 listUser·p0.9999: 11.226 ms/op
                 listUser·p1.00:   11.583 ms/op

Iteration   3: 2.985 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.886 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   5.382 ms/op
                 listUser·p0.999:  9.253 ms/op
                 listUser·p0.9999: 11.026 ms/op
                 listUser·p1.00:   12.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319418
  mean =      3.003 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 102 
    [ 1.250,  2.500) = 93866 
    [ 2.500,  3.750) = 187489 
    [ 3.750,  5.000) = 31147 
    [ 5.000,  6.250) = 5448 
    [ 6.250,  7.500) = 722 
    [ 7.500,  8.750) = 233 
    [ 8.750, 10.000) = 226 
    [10.000, 11.250) = 168 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =      9.234 ms/op
     p(99.9900) =     11.010 ms/op
     p(99.9990) =     11.659 ms/op
     p(99.9999) =     12.272 ms/op
    p(100.0000) =     12.272 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.338 ± 0.381  ops/ms
ClientPb.existUser                       thrpt       3  12.718 ± 0.978  ops/ms
ClientPb.getUser                         thrpt       3  12.670 ± 1.197  ops/ms
ClientPb.listUser                        thrpt       3  10.596 ± 1.206  ops/ms
ClientPb.createUser                       avgt       3   2.623 ± 0.915   ms/op
ClientPb.existUser                        avgt       3   2.477 ± 0.450   ms/op
ClientPb.getUser                          avgt       3   2.531 ± 0.319   ms/op
ClientPb.listUser                         avgt       3   3.035 ± 0.234   ms/op
ClientPb.createUser                     sample  373633   2.566 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.835           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.642           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.240           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.492           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.042           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.483           ms/op
ClientPb.existUser                      sample  385257   2.489 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.683           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.572           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.650           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.958           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.909           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.203           ms/op
ClientPb.getUser                        sample  378383   2.536 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.765           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.580           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.599           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.435           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.205           ms/op
ClientPb.listUser                       sample  319418   3.003 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.839           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.538           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.234           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.010           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.272           ms/op
