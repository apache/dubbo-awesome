# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.717 ops/ms
# Warmup Iteration   2: 11.694 ops/ms
# Warmup Iteration   3: 12.111 ops/ms
Iteration   1: 12.328 ops/ms
Iteration   2: 12.423 ops/ms
Iteration   3: 12.439 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.397 ±(99.9%) 1.097 ops/ms [Average]
  (min, avg, max) = (12.328, 12.397, 12.439), stdev = 0.060
  CI (99.9%): [11.300, 13.494] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.528 ops/ms
# Warmup Iteration   2: 12.621 ops/ms
# Warmup Iteration   3: 12.675 ops/ms
Iteration   1: 12.724 ops/ms
Iteration   2: 12.838 ops/ms
Iteration   3: 12.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.815 ±(99.9%) 1.490 ops/ms [Average]
  (min, avg, max) = (12.724, 12.815, 12.882), stdev = 0.082
  CI (99.9%): [11.325, 14.304] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.002 ops/ms
# Warmup Iteration   2: 12.583 ops/ms
# Warmup Iteration   3: 12.518 ops/ms
Iteration   1: 12.878 ops/ms
Iteration   2: 12.744 ops/ms
Iteration   3: 12.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.783 ±(99.9%) 1.513 ops/ms [Average]
  (min, avg, max) = (12.726, 12.783, 12.878), stdev = 0.083
  CI (99.9%): [11.270, 14.296] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.591 ops/ms
# Warmup Iteration   2: 10.373 ops/ms
# Warmup Iteration   3: 10.332 ops/ms
Iteration   1: 10.634 ops/ms
Iteration   2: 10.701 ops/ms
Iteration   3: 10.649 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.661 ±(99.9%) 0.638 ops/ms [Average]
  (min, avg, max) = (10.634, 10.661, 10.701), stdev = 0.035
  CI (99.9%): [10.024, 11.299] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.977 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.652 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.004 ms/op
Iteration   1: 2.559 ±(99.9%) 0.005 ms/op
Iteration   2: 2.534 ±(99.9%) 0.004 ms/op
Iteration   3: 2.546 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.546 ±(99.9%) 0.230 ms/op [Average]
  (min, avg, max) = (2.534, 2.546, 2.559), stdev = 0.013
  CI (99.9%): [2.316, 2.776] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.783 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.004 ms/op
Iteration   1: 2.476 ±(99.9%) 0.004 ms/op
Iteration   2: 2.491 ±(99.9%) 0.003 ms/op
Iteration   3: 2.506 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.491 ±(99.9%) 0.275 ms/op [Average]
  (min, avg, max) = (2.476, 2.491, 2.506), stdev = 0.015
  CI (99.9%): [2.216, 2.766] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.034 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.586 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.004 ms/op
Iteration   1: 2.556 ±(99.9%) 0.004 ms/op
Iteration   2: 2.515 ±(99.9%) 0.003 ms/op
Iteration   3: 2.521 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.531 ±(99.9%) 0.404 ms/op [Average]
  (min, avg, max) = (2.515, 2.531, 2.556), stdev = 0.022
  CI (99.9%): [2.127, 2.935] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.945 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.004 ms/op
Iteration   1: 3.015 ±(99.9%) 0.005 ms/op
Iteration   2: 3.023 ±(99.9%) 0.005 ms/op
Iteration   3: 3.036 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.025 ±(99.9%) 0.197 ms/op [Average]
  (min, avg, max) = (3.015, 3.025, 3.036), stdev = 0.011
  CI (99.9%): [2.827, 3.222] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.414 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 2.675 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.555 ±(99.9%) 0.006 ms/op
Iteration   1: 2.543 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.893 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.719 ms/op
                 createUser·p0.999:  12.205 ms/op
                 createUser·p0.9999: 18.383 ms/op
                 createUser·p1.00:   18.678 ms/op

Iteration   2: 2.545 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.843 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.748 ms/op
                 createUser·p0.999:  5.513 ms/op
                 createUser·p0.9999: 12.541 ms/op
                 createUser·p1.00:   12.763 ms/op

Iteration   3: 2.561 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.431 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   4.014 ms/op
                 createUser·p0.999:  9.404 ms/op
                 createUser·p0.9999: 16.188 ms/op
                 createUser·p1.00:   16.597 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376058
  mean =      2.550 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 180340 
    [ 2.500,  3.750) = 191402 
    [ 3.750,  5.000) = 3347 
    [ 5.000,  6.250) = 454 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.431 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.822 ms/op
     p(99.9000) =      8.962 ms/op
     p(99.9900) =     16.358 ms/op
     p(99.9990) =     18.481 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.022 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.466 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
Iteration   1: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.929 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.711 ms/op
                 existUser·p0.999:  6.123 ms/op
                 existUser·p0.9999: 15.106 ms/op
                 existUser·p1.00:   15.696 ms/op

Iteration   2: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.553 ms/op
                 existUser·p0.999:  5.870 ms/op
                 existUser·p0.9999: 12.993 ms/op
                 existUser·p1.00:   13.697 ms/op

Iteration   3: 2.437 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.849 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.703 ms/op
                 existUser·p0.999:  8.314 ms/op
                 existUser·p0.9999: 13.009 ms/op
                 existUser·p1.00:   13.533 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391121
  mean =      2.452 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 194700 
    [ 2.500,  3.750) = 192987 
    [ 3.750,  5.000) = 2652 
    [ 5.000,  6.250) = 334 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.654 ms/op
     p(99.9000) =      6.225 ms/op
     p(99.9900) =     13.925 ms/op
     p(99.9990) =     15.387 ms/op
     p(99.9999) =     15.696 ms/op
    p(100.0000) =     15.696 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.038 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.590 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.006 ms/op
Iteration   1: 2.500 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.840 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.699 ms/op
                 getUser·p0.999:  5.326 ms/op
                 getUser·p0.9999: 13.615 ms/op
                 getUser·p1.00:   14.418 ms/op

Iteration   2: 2.517 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.989 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   4.314 ms/op
                 getUser·p0.999:  8.781 ms/op
                 getUser·p0.9999: 19.320 ms/op
                 getUser·p1.00:   21.135 ms/op

Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.974 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.670 ms/op
                 getUser·p0.999:  7.537 ms/op
                 getUser·p0.9999: 11.862 ms/op
                 getUser·p1.00:   13.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382925
  mean =      2.505 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 189222 
    [ 2.500,  5.000) = 192733 
    [ 5.000,  7.500) = 613 
    [ 7.500, 10.000) = 97 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.863 ms/op
     p(99.9000) =      6.717 ms/op
     p(99.9900) =     13.730 ms/op
     p(99.9990) =     20.115 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.764 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.009 ms/op
Iteration   1: 3.048 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.998 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.066 ms/op
                 listUser·p0.9999: 10.289 ms/op
                 listUser·p1.00:   10.732 ms/op

Iteration   2: 3.061 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.797 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.161 ms/op
                 listUser·p0.9999: 11.026 ms/op
                 listUser·p1.00:   12.993 ms/op

Iteration   3: 3.066 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.886 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  9.498 ms/op
                 listUser·p0.9999: 11.075 ms/op
                 listUser·p1.00:   13.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313627
  mean =      3.058 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 108 
    [ 1.250,  2.500) = 79552 
    [ 2.500,  3.750) = 192597 
    [ 3.750,  5.000) = 34040 
    [ 5.000,  6.250) = 6002 
    [ 6.250,  7.500) = 595 
    [ 7.500,  8.750) = 281 
    [ 8.750, 10.000) = 316 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.797 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      9.224 ms/op
     p(99.9900) =     10.732 ms/op
     p(99.9990) =     12.952 ms/op
     p(99.9999) =     13.255 ms/op
    p(100.0000) =     13.255 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.397 ± 1.097  ops/ms
ClientPb.existUser                       thrpt       3  12.815 ± 1.490  ops/ms
ClientPb.getUser                         thrpt       3  12.783 ± 1.513  ops/ms
ClientPb.listUser                        thrpt       3  10.661 ± 0.638  ops/ms
ClientPb.createUser                       avgt       3   2.546 ± 0.230   ms/op
ClientPb.existUser                        avgt       3   2.491 ± 0.275   ms/op
ClientPb.getUser                          avgt       3   2.531 ± 0.404   ms/op
ClientPb.listUser                         avgt       3   3.025 ± 0.197   ms/op
ClientPb.createUser                     sample  376058   2.550 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.431           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.962           ms/op
ClientPb.createUser:createUser·p0.9999  sample          16.358           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.678           ms/op
ClientPb.existUser                      sample  391121   2.452 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.849           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.225           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.925           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.696           ms/op
ClientPb.getUser                        sample  382925   2.505 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.840           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.527           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.717           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.730           ms/op
ClientPb.getUser:getUser·p1.00          sample          21.135           ms/op
ClientPb.listUser                       sample  313627   3.058 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.797           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.994           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.224           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.732           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.255           ms/op
