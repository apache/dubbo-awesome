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
# Warmup Iteration   1: 4.624 ops/ms
# Warmup Iteration   2: 11.962 ops/ms
# Warmup Iteration   3: 12.691 ops/ms
Iteration   1: 12.774 ops/ms
Iteration   2: 12.798 ops/ms
Iteration   3: 12.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.825 ±(99.9%) 1.244 ops/ms [Average]
  (min, avg, max) = (12.774, 12.825, 12.903), stdev = 0.068
  CI (99.9%): [11.581, 14.070] (assumes normal distribution)


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
# Warmup Iteration   1: 8.266 ops/ms
# Warmup Iteration   2: 13.211 ops/ms
# Warmup Iteration   3: 13.265 ops/ms
Iteration   1: 13.274 ops/ms
Iteration   2: 13.392 ops/ms
Iteration   3: 13.270 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.312 ±(99.9%) 1.267 ops/ms [Average]
  (min, avg, max) = (13.270, 13.312, 13.392), stdev = 0.069
  CI (99.9%): [12.045, 14.579] (assumes normal distribution)


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
# Warmup Iteration   1: 7.655 ops/ms
# Warmup Iteration   2: 12.947 ops/ms
# Warmup Iteration   3: 12.993 ops/ms
Iteration   1: 12.932 ops/ms
Iteration   2: 12.944 ops/ms
Iteration   3: 12.908 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.928 ±(99.9%) 0.337 ops/ms [Average]
  (min, avg, max) = (12.908, 12.928, 12.944), stdev = 0.018
  CI (99.9%): [12.591, 13.265] (assumes normal distribution)


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
# Warmup Iteration   1: 6.493 ops/ms
# Warmup Iteration   2: 10.469 ops/ms
# Warmup Iteration   3: 10.526 ops/ms
Iteration   1: 10.643 ops/ms
Iteration   2: 10.691 ops/ms
Iteration   3: 10.567 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.634 ±(99.9%) 1.136 ops/ms [Average]
  (min, avg, max) = (10.567, 10.634, 10.691), stdev = 0.062
  CI (99.9%): [9.497, 11.770] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 3.997 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.590 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.004 ms/op
Iteration   1: 2.494 ±(99.9%) 0.003 ms/op
Iteration   2: 2.505 ±(99.9%) 0.004 ms/op
Iteration   3: 2.515 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.505 ±(99.9%) 0.196 ms/op [Average]
  (min, avg, max) = (2.494, 2.505, 2.515), stdev = 0.011
  CI (99.9%): [2.308, 2.701] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.705 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.430 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.422 ±(99.9%) 0.004 ms/op
Iteration   1: 2.415 ±(99.9%) 0.005 ms/op
Iteration   2: 2.411 ±(99.9%) 0.004 ms/op
Iteration   3: 2.390 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.405 ±(99.9%) 0.241 ms/op [Average]
  (min, avg, max) = (2.390, 2.405, 2.415), stdev = 0.013
  CI (99.9%): [2.164, 2.646] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.967 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.528 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.004 ms/op
Iteration   1: 2.465 ±(99.9%) 0.005 ms/op
Iteration   2: 2.472 ±(99.9%) 0.004 ms/op
Iteration   3: 2.450 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.462 ±(99.9%) 0.211 ms/op [Average]
  (min, avg, max) = (2.450, 2.462, 2.472), stdev = 0.012
  CI (99.9%): [2.251, 2.673] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.813 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.037 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.958 ±(99.9%) 0.004 ms/op
Iteration   1: 2.987 ±(99.9%) 0.005 ms/op
Iteration   2: 2.963 ±(99.9%) 0.004 ms/op
Iteration   3: 2.965 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.972 ±(99.9%) 0.245 ms/op [Average]
  (min, avg, max) = (2.963, 2.972, 2.987), stdev = 0.013
  CI (99.9%): [2.727, 3.217] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.124 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.605 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.005 ms/op
Iteration   1: 2.491 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.780 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   4.088 ms/op
                 createUser·p0.999:  10.504 ms/op
                 createUser·p0.9999: 13.517 ms/op
                 createUser·p1.00:   14.893 ms/op

Iteration   2: 2.497 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.920 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.805 ms/op
                 createUser·p0.999:  9.103 ms/op
                 createUser·p0.9999: 14.100 ms/op
                 createUser·p1.00:   14.402 ms/op

Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.850 ms/op
                 createUser·p0.50:   2.523 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.805 ms/op
                 createUser·p0.999:  8.233 ms/op
                 createUser·p0.9999: 11.043 ms/op
                 createUser·p1.00:   12.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385080
  mean =      2.491 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 188691 
    [ 2.500,  3.750) = 191628 
    [ 3.750,  5.000) = 3817 
    [ 5.000,  6.250) = 407 
    [ 6.250,  7.500) = 70 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.780 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.883 ms/op
     p(99.9000) =      8.398 ms/op
     p(99.9900) =     13.320 ms/op
     p(99.9990) =     14.294 ms/op
     p(99.9999) =     14.893 ms/op
    p(100.0000) =     14.893 ms/op


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
# Warmup Iteration   1: 3.569 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.389 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.392 ±(99.9%) 0.005 ms/op
Iteration   1: 2.389 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.722 ms/op
                 existUser·p0.50:   2.429 ms/op
                 existUser·p0.90:   2.908 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.539 ms/op
                 existUser·p0.999:  6.859 ms/op
                 existUser·p0.9999: 23.233 ms/op
                 existUser·p1.00:   23.462 ms/op

Iteration   2: 2.401 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.992 ms/op
                 existUser·p0.50:   2.437 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.609 ms/op
                 existUser·p0.999:  6.166 ms/op
                 existUser·p0.9999: 14.380 ms/op
                 existUser·p1.00:   15.499 ms/op

Iteration   3: 2.419 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.681 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.690 ms/op
                 existUser·p0.999:  8.667 ms/op
                 existUser·p0.9999: 12.714 ms/op
                 existUser·p1.00:   13.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 399023
  mean =      2.403 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 206909 
    [ 2.500,  5.000) = 191478 
    [ 5.000,  7.500) = 220 
    [ 7.500, 10.000) = 123 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      2.445 ms/op
     p(90.0000) =      2.929 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      3.609 ms/op
     p(99.9000) =      8.536 ms/op
     p(99.9900) =     14.508 ms/op
     p(99.9990) =     23.364 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


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
# Warmup Iteration   1: 3.829 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.500 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
Iteration   1: 2.435 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.698 ms/op
                 getUser·p0.50:   2.454 ms/op
                 getUser·p0.90:   2.966 ms/op
                 getUser·p0.95:   3.076 ms/op
                 getUser·p0.99:   3.572 ms/op
                 getUser·p0.999:  5.814 ms/op
                 getUser·p0.9999: 14.903 ms/op
                 getUser·p1.00:   15.827 ms/op

Iteration   2: 2.469 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.856 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  6.617 ms/op
                 getUser·p0.9999: 11.521 ms/op
                 getUser·p1.00:   12.452 ms/op

Iteration   3: 2.452 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.963 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.658 ms/op
                 getUser·p0.999:  6.195 ms/op
                 getUser·p0.9999: 11.419 ms/op
                 getUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 391137
  mean =      2.452 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 86 
    [ 1.250,  2.500) = 198328 
    [ 2.500,  3.750) = 188367 
    [ 3.750,  5.000) = 3584 
    [ 5.000,  6.250) = 385 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 90 
    [10.000, 11.250) = 116 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.698 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.822 ms/op
     p(99.9000) =      6.138 ms/op
     p(99.9900) =     12.861 ms/op
     p(99.9990) =     15.794 ms/op
     p(99.9999) =     15.827 ms/op
    p(100.0000) =     15.827 ms/op


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
# Warmup Iteration   1: 4.704 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.008 ms/op
Iteration   1: 2.973 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.976 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  8.815 ms/op
                 listUser·p0.9999: 10.240 ms/op
                 listUser·p1.00:   11.698 ms/op

Iteration   2: 2.980 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.791 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.367 ms/op
                 listUser·p0.9999: 11.228 ms/op
                 listUser·p1.00:   12.419 ms/op

Iteration   3: 2.966 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.883 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  9.424 ms/op
                 listUser·p0.9999: 10.906 ms/op
                 listUser·p1.00:   11.715 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322568
  mean =      2.973 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 134 
    [ 1.250,  2.500) = 100032 
    [ 2.500,  3.750) = 185323 
    [ 3.750,  5.000) = 30163 
    [ 5.000,  6.250) = 5589 
    [ 6.250,  7.500) = 654 
    [ 7.500,  8.750) = 278 
    [ 8.750, 10.000) = 235 
    [10.000, 11.250) = 147 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      9.191 ms/op
     p(99.9900) =     10.932 ms/op
     p(99.9990) =     11.753 ms/op
     p(99.9999) =     12.419 ms/op
    p(100.0000) =     12.419 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.825 ± 1.244  ops/ms
ClientPb.existUser                       thrpt       3  13.312 ± 1.267  ops/ms
ClientPb.getUser                         thrpt       3  12.928 ± 0.337  ops/ms
ClientPb.listUser                        thrpt       3  10.634 ± 1.136  ops/ms
ClientPb.createUser                       avgt       3   2.505 ± 0.196   ms/op
ClientPb.existUser                        avgt       3   2.405 ± 0.241   ms/op
ClientPb.getUser                          avgt       3   2.462 ± 0.211   ms/op
ClientPb.listUser                         avgt       3   2.972 ± 0.245   ms/op
ClientPb.createUser                     sample  385080   2.491 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.780           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.540           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.023           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.398           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.320           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.893           ms/op
ClientPb.existUser                      sample  399023   2.403 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.681           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.445           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.929           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.536           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.508           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.462           ms/op
ClientPb.getUser                        sample  391137   2.452 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.698           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.470           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.986           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.822           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.138           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.861           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.827           ms/op
ClientPb.listUser                       sample  322568   2.973 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.791           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.191           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.932           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.419           ms/op
