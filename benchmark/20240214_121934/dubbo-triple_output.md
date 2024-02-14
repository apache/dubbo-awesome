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
# Warmup Iteration   1: 4.998 ops/ms
# Warmup Iteration   2: 12.400 ops/ms
# Warmup Iteration   3: 12.678 ops/ms
Iteration   1: 12.741 ops/ms
Iteration   2: 12.665 ops/ms
Iteration   3: 12.960 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.789 ±(99.9%) 2.791 ops/ms [Average]
  (min, avg, max) = (12.665, 12.789, 12.960), stdev = 0.153
  CI (99.9%): [9.998, 15.580] (assumes normal distribution)


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
# Warmup Iteration   1: 7.968 ops/ms
# Warmup Iteration   2: 12.893 ops/ms
# Warmup Iteration   3: 12.872 ops/ms
Iteration   1: 13.061 ops/ms
Iteration   2: 12.834 ops/ms
Iteration   3: 12.985 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.960 ±(99.9%) 2.107 ops/ms [Average]
  (min, avg, max) = (12.834, 12.960, 13.061), stdev = 0.115
  CI (99.9%): [10.853, 15.067] (assumes normal distribution)


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
# Warmup Iteration   1: 7.232 ops/ms
# Warmup Iteration   2: 12.734 ops/ms
# Warmup Iteration   3: 12.978 ops/ms
Iteration   1: 12.869 ops/ms
Iteration   2: 12.926 ops/ms
Iteration   3: 13.105 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.967 ±(99.9%) 2.240 ops/ms [Average]
  (min, avg, max) = (12.869, 12.967, 13.105), stdev = 0.123
  CI (99.9%): [10.727, 15.207] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.863 ops/ms
# Warmup Iteration   2: 10.554 ops/ms
# Warmup Iteration   3: 10.369 ops/ms
Iteration   1: 10.446 ops/ms
Iteration   2: 10.605 ops/ms
Iteration   3: 10.601 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.551 ±(99.9%) 1.649 ops/ms [Average]
  (min, avg, max) = (10.446, 10.551, 10.605), stdev = 0.090
  CI (99.9%): [8.902, 12.199] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.097 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.549 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.004 ms/op
Iteration   1: 2.517 ±(99.9%) 0.004 ms/op
Iteration   2: 2.527 ±(99.9%) 0.003 ms/op
Iteration   3: 2.510 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.518 ±(99.9%) 0.155 ms/op [Average]
  (min, avg, max) = (2.510, 2.518, 2.527), stdev = 0.009
  CI (99.9%): [2.363, 2.673] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.713 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.440 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.437 ±(99.9%) 0.004 ms/op
Iteration   1: 2.423 ±(99.9%) 0.005 ms/op
Iteration   2: 2.431 ±(99.9%) 0.003 ms/op
Iteration   3: 2.415 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.423 ±(99.9%) 0.141 ms/op [Average]
  (min, avg, max) = (2.415, 2.423, 2.431), stdev = 0.008
  CI (99.9%): [2.282, 2.564] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.982 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.555 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.004 ms/op
Iteration   1: 2.453 ±(99.9%) 0.004 ms/op
Iteration   2: 2.469 ±(99.9%) 0.004 ms/op
Iteration   3: 2.487 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.470 ±(99.9%) 0.313 ms/op [Average]
  (min, avg, max) = (2.453, 2.470, 2.487), stdev = 0.017
  CI (99.9%): [2.157, 2.783] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.579 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.032 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.985 ±(99.9%) 0.005 ms/op
Iteration   1: 2.986 ±(99.9%) 0.004 ms/op
Iteration   2: 2.956 ±(99.9%) 0.005 ms/op
Iteration   3: 2.949 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.964 ±(99.9%) 0.359 ms/op [Average]
  (min, avg, max) = (2.949, 2.964, 2.986), stdev = 0.020
  CI (99.9%): [2.605, 3.323] (assumes normal distribution)


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
# Warmup Iteration   1: 4.049 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.610 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.006 ms/op
Iteration   1: 2.471 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   2.511 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.596 ms/op
                 createUser·p0.999:  6.239 ms/op
                 createUser·p0.9999: 13.829 ms/op
                 createUser·p1.00:   14.057 ms/op

Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.965 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.772 ms/op
                 createUser·p0.999:  9.795 ms/op
                 createUser·p0.9999: 12.288 ms/op
                 createUser·p1.00:   12.567 ms/op

Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.845 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.674 ms/op
                 createUser·p0.999:  7.933 ms/op
                 createUser·p0.9999: 10.717 ms/op
                 createUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386220
  mean =      2.483 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 189230 
    [ 2.500,  5.000) = 196279 
    [ 5.000,  7.500) = 283 
    [ 7.500, 10.000) = 160 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.686 ms/op
     p(99.9000) =      8.438 ms/op
     p(99.9900) =     12.943 ms/op
     p(99.9990) =     14.011 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


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
# Warmup Iteration   1: 3.668 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.447 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.420 ±(99.9%) 0.005 ms/op
Iteration   1: 2.434 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.061 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.640 ms/op
                 existUser·p0.999:  7.935 ms/op
                 existUser·p0.9999: 13.599 ms/op
                 existUser·p1.00:   14.205 ms/op

Iteration   2: 2.433 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.964 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.432 ms/op
                 existUser·p0.999:  5.251 ms/op
                 existUser·p0.9999: 12.054 ms/op
                 existUser·p1.00:   12.517 ms/op

Iteration   3: 2.422 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.812 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.550 ms/op
                 existUser·p0.999:  5.369 ms/op
                 existUser·p0.9999: 11.473 ms/op
                 existUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394674
  mean =      2.430 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 195683 
    [ 2.500,  3.750) = 196042 
    [ 3.750,  5.000) = 2225 
    [ 5.000,  6.250) = 314 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 165 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      2.941 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      3.539 ms/op
     p(99.9000) =      5.966 ms/op
     p(99.9900) =     12.452 ms/op
     p(99.9990) =     13.995 ms/op
     p(99.9999) =     14.205 ms/op
    p(100.0000) =     14.205 ms/op


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
# Warmup Iteration   1: 3.917 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.568 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.006 ms/op
Iteration   1: 2.458 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.616 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   2.978 ms/op
                 getUser·p0.95:   3.076 ms/op
                 getUser·p0.99:   3.555 ms/op
                 getUser·p0.999:  7.980 ms/op
                 getUser·p0.9999: 13.287 ms/op
                 getUser·p1.00:   14.008 ms/op

Iteration   2: 2.489 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.926 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   4.141 ms/op
                 getUser·p0.999:  8.613 ms/op
                 getUser·p0.9999: 12.075 ms/op
                 getUser·p1.00:   13.107 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.866 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.809 ms/op
                 getUser·p0.999:  5.526 ms/op
                 getUser·p0.9999: 9.801 ms/op
                 getUser·p1.00:   10.191 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387380
  mean =      2.476 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 192804 
    [ 2.500,  3.750) = 190278 
    [ 3.750,  5.000) = 3182 
    [ 5.000,  6.250) = 598 
    [ 6.250,  7.500) = 96 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.809 ms/op
     p(99.9000) =      6.665 ms/op
     p(99.9900) =     13.058 ms/op
     p(99.9990) =     13.474 ms/op
     p(99.9999) =     14.008 ms/op
    p(100.0000) =     14.008 ms/op


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
# Warmup Iteration   1: 4.657 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 2.989 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.008 ms/op
Iteration   1: 2.958 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.889 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.159 ms/op
                 listUser·p0.9999: 10.948 ms/op
                 listUser·p1.00:   11.108 ms/op

Iteration   2: 2.951 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.872 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.793 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  8.880 ms/op
                 listUser·p0.9999: 10.983 ms/op
                 listUser·p1.00:   11.715 ms/op

Iteration   3: 2.944 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.065 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.760 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   5.415 ms/op
                 listUser·p0.999:  9.231 ms/op
                 listUser·p0.9999: 11.040 ms/op
                 listUser·p1.00:   11.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 325059
  mean =      2.951 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 129 
    [ 1.250,  2.500) = 103505 
    [ 2.500,  3.750) = 186620 
    [ 3.750,  5.000) = 28401 
    [ 5.000,  6.250) = 5212 
    [ 6.250,  7.500) = 529 
    [ 7.500,  8.750) = 212 
    [ 8.750, 10.000) = 337 
    [10.000, 11.250) = 97 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.872 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =      9.142 ms/op
     p(99.9900) =     10.961 ms/op
     p(99.9990) =     11.497 ms/op
     p(99.9999) =     11.715 ms/op
    p(100.0000) =     11.715 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.789 ± 2.791  ops/ms
ClientPb.existUser                       thrpt       3  12.960 ± 2.107  ops/ms
ClientPb.getUser                         thrpt       3  12.967 ± 2.240  ops/ms
ClientPb.listUser                        thrpt       3  10.551 ± 1.649  ops/ms
ClientPb.createUser                       avgt       3   2.518 ± 0.155   ms/op
ClientPb.existUser                        avgt       3   2.423 ± 0.141   ms/op
ClientPb.getUser                          avgt       3   2.470 ± 0.313   ms/op
ClientPb.listUser                         avgt       3   2.964 ± 0.359   ms/op
ClientPb.createUser                     sample  386220   2.483 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.845           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.540           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.019           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.686           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.438           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.943           ms/op
ClientPb.createUser:createUser·p1.00    sample          20.087           ms/op
ClientPb.existUser                      sample  394674   2.430 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.812           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.941           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.539           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.966           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.452           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.205           ms/op
ClientPb.getUser                        sample  387380   2.476 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.616           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.006           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.809           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.665           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.058           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.008           ms/op
ClientPb.listUser                       sample  325059   2.951 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.872           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.892           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.797           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.480           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.142           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.961           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.715           ms/op
