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
# Warmup Iteration   1: 4.958 ops/ms
# Warmup Iteration   2: 12.100 ops/ms
# Warmup Iteration   3: 12.357 ops/ms
Iteration   1: 12.767 ops/ms
Iteration   2: 12.818 ops/ms
Iteration   3: 12.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.821 ±(99.9%) 1.028 ops/ms [Average]
  (min, avg, max) = (12.767, 12.821, 12.879), stdev = 0.056
  CI (99.9%): [11.793, 13.849] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.504 ops/ms
# Warmup Iteration   2: 13.004 ops/ms
# Warmup Iteration   3: 13.096 ops/ms
Iteration   1: 12.960 ops/ms
Iteration   2: 13.018 ops/ms
Iteration   3: 12.900 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.960 ±(99.9%) 1.075 ops/ms [Average]
  (min, avg, max) = (12.900, 12.960, 13.018), stdev = 0.059
  CI (99.9%): [11.885, 14.034] (assumes normal distribution)


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
# Warmup Iteration   1: 7.949 ops/ms
# Warmup Iteration   2: 12.490 ops/ms
# Warmup Iteration   3: 12.797 ops/ms
Iteration   1: 12.866 ops/ms
Iteration   2: 12.662 ops/ms
Iteration   3: 12.599 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.709 ±(99.9%) 2.542 ops/ms [Average]
  (min, avg, max) = (12.599, 12.709, 12.866), stdev = 0.139
  CI (99.9%): [10.166, 15.251] (assumes normal distribution)


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
# Warmup Iteration   1: 6.970 ops/ms
# Warmup Iteration   2: 10.707 ops/ms
# Warmup Iteration   3: 10.785 ops/ms
Iteration   1: 10.916 ops/ms
Iteration   2: 10.903 ops/ms
Iteration   3: 10.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.887 ±(99.9%) 0.732 ops/ms [Average]
  (min, avg, max) = (10.841, 10.887, 10.916), stdev = 0.040
  CI (99.9%): [10.155, 11.619] (assumes normal distribution)


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
# Warmup Iteration   1: 3.855 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.575 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.004 ms/op
Iteration   1: 2.517 ±(99.9%) 0.004 ms/op
Iteration   2: 2.507 ±(99.9%) 0.004 ms/op
Iteration   3: 2.493 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.506 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (2.493, 2.506, 2.517), stdev = 0.012
  CI (99.9%): [2.283, 2.729] (assumes normal distribution)


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
# Warmup Iteration   1: 3.848 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.478 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.454 ±(99.9%) 0.005 ms/op
Iteration   1: 2.430 ±(99.9%) 0.004 ms/op
Iteration   2: 2.454 ±(99.9%) 0.004 ms/op
Iteration   3: 2.461 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.449 ±(99.9%) 0.295 ms/op [Average]
  (min, avg, max) = (2.430, 2.449, 2.461), stdev = 0.016
  CI (99.9%): [2.153, 2.744] (assumes normal distribution)


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
# Warmup Iteration   1: 3.924 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.528 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.004 ms/op
Iteration   1: 2.476 ±(99.9%) 0.004 ms/op
Iteration   2: 2.466 ±(99.9%) 0.004 ms/op
Iteration   3: 2.465 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.469 ±(99.9%) 0.116 ms/op [Average]
  (min, avg, max) = (2.465, 2.469, 2.476), stdev = 0.006
  CI (99.9%): [2.353, 2.585] (assumes normal distribution)


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
# Warmup Iteration   1: 4.751 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.005 ms/op
Iteration   1: 2.974 ±(99.9%) 0.006 ms/op
Iteration   2: 2.975 ±(99.9%) 0.005 ms/op
Iteration   3: 2.969 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.973 ±(99.9%) 0.056 ms/op [Average]
  (min, avg, max) = (2.969, 2.973, 2.975), stdev = 0.003
  CI (99.9%): [2.917, 3.029] (assumes normal distribution)


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
# Warmup Iteration   1: 4.266 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.675 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.006 ms/op
Iteration   1: 2.553 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.408 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.273 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  11.898 ms/op
                 createUser·p0.9999: 13.695 ms/op
                 createUser·p1.00:   14.139 ms/op

Iteration   2: 2.515 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.049 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.755 ms/op
                 createUser·p0.999:  9.060 ms/op
                 createUser·p0.9999: 13.522 ms/op
                 createUser·p1.00:   14.221 ms/op

Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.860 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.531 ms/op
                 createUser·p0.999:  9.142 ms/op
                 createUser·p0.9999: 11.183 ms/op
                 createUser·p1.00:   11.387 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379603
  mean =      2.527 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 182686 
    [ 2.500,  3.750) = 192204 
    [ 3.750,  5.000) = 3813 
    [ 5.000,  6.250) = 433 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 124 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 97 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.408 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.899 ms/op
     p(99.9000) =      9.106 ms/op
     p(99.9900) =     13.517 ms/op
     p(99.9990) =     14.179 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.921 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.475 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.432 ±(99.9%) 0.005 ms/op
Iteration   1: 2.432 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.992 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.600 ms/op
                 existUser·p0.999:  8.381 ms/op
                 existUser·p0.9999: 13.283 ms/op
                 existUser·p1.00:   14.270 ms/op

Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.975 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.449 ms/op
                 existUser·p0.999:  6.729 ms/op
                 existUser·p0.9999: 12.485 ms/op
                 existUser·p1.00:   13.353 ms/op

Iteration   3: 2.443 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.910 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.563 ms/op
                 existUser·p0.999:  6.504 ms/op
                 existUser·p0.9999: 12.042 ms/op
                 existUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392083
  mean =      2.446 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 199150 
    [ 2.500,  3.750) = 190207 
    [ 3.750,  5.000) = 2108 
    [ 5.000,  6.250) = 147 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 125 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      2.466 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.543 ms/op
     p(99.9000) =      8.167 ms/op
     p(99.9900) =     12.911 ms/op
     p(99.9990) =     13.898 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.035 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.589 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.006 ms/op
Iteration   1: 2.457 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.828 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.092 ms/op
                 getUser·p0.99:   3.543 ms/op
                 getUser·p0.999:  5.429 ms/op
                 getUser·p0.9999: 16.531 ms/op
                 getUser·p1.00:   17.400 ms/op

Iteration   2: 2.511 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.858 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.686 ms/op
                 getUser·p0.999:  9.580 ms/op
                 getUser·p0.9999: 11.948 ms/op
                 getUser·p1.00:   12.812 ms/op

Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.057 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.662 ms/op
                 getUser·p0.999:  6.194 ms/op
                 getUser·p0.9999: 10.638 ms/op
                 getUser·p1.00:   11.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387315
  mean =      2.476 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 193471 
    [ 2.500,  3.750) = 188840 
    [ 3.750,  5.000) = 3656 
    [ 5.000,  6.250) = 863 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 112 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.828 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.936 ms/op
     p(99.9000) =      7.141 ms/op
     p(99.9900) =     13.399 ms/op
     p(99.9990) =     17.117 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.565 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.008 ms/op
Iteration   1: 2.959 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.852 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  8.667 ms/op
                 listUser·p0.9999: 10.335 ms/op
                 listUser·p1.00:   10.797 ms/op

Iteration   2: 2.951 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.887 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.805 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.341 ms/op
                 listUser·p0.999:  9.273 ms/op
                 listUser·p0.9999: 10.409 ms/op
                 listUser·p1.00:   11.141 ms/op

Iteration   3: 2.979 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.918 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.171 ms/op
                 listUser·p0.9999: 11.186 ms/op
                 listUser·p1.00:   12.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323651
  mean =      2.963 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 168 
    [ 1.250,  2.500) = 100538 
    [ 2.500,  3.750) = 186091 
    [ 3.750,  5.000) = 30194 
    [ 5.000,  6.250) = 5337 
    [ 6.250,  7.500) = 669 
    [ 7.500,  8.750) = 288 
    [ 8.750, 10.000) = 273 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.852 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =      9.077 ms/op
     p(99.9900) =     10.463 ms/op
     p(99.9990) =     11.946 ms/op
     p(99.9999) =     12.255 ms/op
    p(100.0000) =     12.255 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.821 ± 1.028  ops/ms
ClientPb.existUser                       thrpt       3  12.960 ± 1.075  ops/ms
ClientPb.getUser                         thrpt       3  12.709 ± 2.542  ops/ms
ClientPb.listUser                        thrpt       3  10.887 ± 0.732  ops/ms
ClientPb.createUser                       avgt       3   2.506 ± 0.223   ms/op
ClientPb.existUser                        avgt       3   2.449 ± 0.295   ms/op
ClientPb.getUser                          avgt       3   2.469 ± 0.116   ms/op
ClientPb.listUser                         avgt       3   2.973 ± 0.056   ms/op
ClientPb.createUser                     sample  379603   2.527 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.408           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.068           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.899           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.106           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.517           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.221           ms/op
ClientPb.existUser                      sample  392083   2.446 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.910           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.466           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.543           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.167           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.911           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.270           ms/op
ClientPb.getUser                        sample  387315   2.476 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.828           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.011           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.141           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.399           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.400           ms/op
ClientPb.listUser                       sample  323651   2.963 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.852           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.900           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.513           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.077           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.463           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.255           ms/op
