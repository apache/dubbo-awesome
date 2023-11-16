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
# Warmup Iteration   1: 4.944 ops/ms
# Warmup Iteration   2: 11.992 ops/ms
# Warmup Iteration   3: 12.158 ops/ms
Iteration   1: 12.563 ops/ms
Iteration   2: 12.474 ops/ms
Iteration   3: 12.416 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.485 ±(99.9%) 1.353 ops/ms [Average]
  (min, avg, max) = (12.416, 12.485, 12.563), stdev = 0.074
  CI (99.9%): [11.131, 13.838] (assumes normal distribution)


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
# Warmup Iteration   1: 8.004 ops/ms
# Warmup Iteration   2: 13.044 ops/ms
# Warmup Iteration   3: 13.071 ops/ms
Iteration   1: 13.033 ops/ms
Iteration   2: 13.127 ops/ms
Iteration   3: 13.038 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.066 ±(99.9%) 0.967 ops/ms [Average]
  (min, avg, max) = (13.033, 13.066, 13.127), stdev = 0.053
  CI (99.9%): [12.099, 14.033] (assumes normal distribution)


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
# Warmup Iteration   1: 7.663 ops/ms
# Warmup Iteration   2: 12.565 ops/ms
# Warmup Iteration   3: 12.616 ops/ms
Iteration   1: 12.644 ops/ms
Iteration   2: 12.722 ops/ms
Iteration   3: 12.782 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.716 ±(99.9%) 1.263 ops/ms [Average]
  (min, avg, max) = (12.644, 12.716, 12.782), stdev = 0.069
  CI (99.9%): [11.453, 13.979] (assumes normal distribution)


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
# Warmup Iteration   1: 6.533 ops/ms
# Warmup Iteration   2: 10.479 ops/ms
# Warmup Iteration   3: 10.463 ops/ms
Iteration   1: 10.670 ops/ms
Iteration   2: 10.647 ops/ms
Iteration   3: 10.615 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.644 ±(99.9%) 0.502 ops/ms [Average]
  (min, avg, max) = (10.615, 10.644, 10.670), stdev = 0.027
  CI (99.9%): [10.143, 11.146] (assumes normal distribution)


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
# Warmup Iteration   1: 4.061 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.579 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.004 ms/op
Iteration   1: 2.545 ±(99.9%) 0.005 ms/op
Iteration   2: 2.518 ±(99.9%) 0.004 ms/op
Iteration   3: 2.525 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.530 ±(99.9%) 0.256 ms/op [Average]
  (min, avg, max) = (2.518, 2.530, 2.545), stdev = 0.014
  CI (99.9%): [2.274, 2.785] (assumes normal distribution)


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
# Warmup Iteration   1: 3.898 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.489 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
Iteration   1: 2.473 ±(99.9%) 0.004 ms/op
Iteration   2: 2.462 ±(99.9%) 0.003 ms/op
Iteration   3: 2.450 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.462 ±(99.9%) 0.211 ms/op [Average]
  (min, avg, max) = (2.450, 2.462, 2.473), stdev = 0.012
  CI (99.9%): [2.251, 2.673] (assumes normal distribution)


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
# Warmup Iteration   1: 4.042 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.591 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.004 ms/op
Iteration   1: 2.492 ±(99.9%) 0.004 ms/op
Iteration   2: 2.504 ±(99.9%) 0.005 ms/op
Iteration   3: 2.536 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.511 ±(99.9%) 0.417 ms/op [Average]
  (min, avg, max) = (2.492, 2.511, 2.536), stdev = 0.023
  CI (99.9%): [2.094, 2.927] (assumes normal distribution)


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
# Warmup Iteration   1: 4.578 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.022 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.005 ms/op
Iteration   1: 3.008 ±(99.9%) 0.005 ms/op
Iteration   2: 3.008 ±(99.9%) 0.007 ms/op
Iteration   3: 3.005 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.007 ±(99.9%) 0.038 ms/op [Average]
  (min, avg, max) = (3.005, 3.007, 3.008), stdev = 0.002
  CI (99.9%): [2.969, 3.045] (assumes normal distribution)


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
# Warmup Iteration   1: 4.223 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.670 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.527 ±(99.9%) 0.005 ms/op
Iteration   1: 2.559 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.038 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  11.666 ms/op
                 createUser·p0.9999: 13.910 ms/op
                 createUser·p1.00:   14.270 ms/op

Iteration   2: 2.536 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.934 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.813 ms/op
                 createUser·p0.999:  9.748 ms/op
                 createUser·p0.9999: 14.031 ms/op
                 createUser·p1.00:   14.287 ms/op

Iteration   3: 2.513 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.906 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.797 ms/op
                 createUser·p0.999:  8.910 ms/op
                 createUser·p0.9999: 11.998 ms/op
                 createUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378211
  mean =      2.536 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 181268 
    [ 2.500,  3.750) = 191926 
    [ 3.750,  5.000) = 3865 
    [ 5.000,  6.250) = 621 
    [ 6.250,  7.500) = 73 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 109 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.906 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.944 ms/op
     p(99.9000) =      8.929 ms/op
     p(99.9900) =     13.877 ms/op
     p(99.9990) =     14.225 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


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
# Warmup Iteration   1: 4.008 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.526 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
Iteration   1: 2.484 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.083 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.703 ms/op
                 existUser·p0.999:  8.710 ms/op
                 existUser·p0.9999: 13.568 ms/op
                 existUser·p1.00:   13.959 ms/op

Iteration   2: 2.491 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.876 ms/op
                 existUser·p0.50:   2.609 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.929 ms/op
                 existUser·p0.999:  5.871 ms/op
                 existUser·p0.9999: 13.978 ms/op
                 existUser·p1.00:   14.303 ms/op

Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.824 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   4.006 ms/op
                 existUser·p0.999:  7.495 ms/op
                 existUser·p0.9999: 10.468 ms/op
                 existUser·p1.00:   11.436 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385175
  mean =      2.491 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 186144 
    [ 2.500,  3.750) = 194478 
    [ 3.750,  5.000) = 3420 
    [ 5.000,  6.250) = 677 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 112 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.863 ms/op
     p(99.9000) =      6.691 ms/op
     p(99.9900) =     13.508 ms/op
     p(99.9990) =     14.060 ms/op
     p(99.9999) =     14.303 ms/op
    p(100.0000) =     14.303 ms/op


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
# Warmup Iteration   1: 4.078 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.605 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.006 ms/op
Iteration   1: 2.541 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.944 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.162 ms/op
                 getUser·p0.999:  12.467 ms/op
                 getUser·p0.9999: 14.418 ms/op
                 getUser·p1.00:   14.565 ms/op

Iteration   2: 2.502 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.678 ms/op
                 getUser·p0.999:  9.924 ms/op
                 getUser·p0.9999: 12.951 ms/op
                 getUser·p1.00:   13.844 ms/op

Iteration   3: 2.544 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.997 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.125 ms/op
                 getUser·p0.95:   3.297 ms/op
                 getUser·p0.99:   4.055 ms/op
                 getUser·p0.999:  8.667 ms/op
                 getUser·p0.9999: 10.312 ms/op
                 getUser·p1.00:   11.043 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379228
  mean =      2.529 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 184819 
    [ 2.500,  3.750) = 188822 
    [ 3.750,  5.000) = 4513 
    [ 5.000,  6.250) = 569 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 107 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 110 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      3.969 ms/op
     p(99.9000) =      8.684 ms/op
     p(99.9900) =     13.945 ms/op
     p(99.9990) =     14.503 ms/op
     p(99.9999) =     14.565 ms/op
    p(100.0000) =     14.565 ms/op


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
# Warmup Iteration   1: 4.706 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.008 ms/op
Iteration   1: 3.048 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.854 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  8.505 ms/op
                 listUser·p0.9999: 12.780 ms/op
                 listUser·p1.00:   13.795 ms/op

Iteration   2: 3.007 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.654 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  8.842 ms/op
                 listUser·p0.9999: 11.032 ms/op
                 listUser·p1.00:   11.698 ms/op

Iteration   3: 2.987 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.914 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.793 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  10.288 ms/op
                 listUser·p0.9999: 12.157 ms/op
                 listUser·p1.00:   13.926 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318284
  mean =      3.014 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 117 
    [ 1.250,  2.500) = 92239 
    [ 2.500,  3.750) = 186975 
    [ 3.750,  5.000) = 31310 
    [ 5.000,  6.250) = 6314 
    [ 6.250,  7.500) = 691 
    [ 7.500,  8.750) = 235 
    [ 8.750, 10.000) = 197 
    [10.000, 11.250) = 145 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =      9.220 ms/op
     p(99.9900) =     12.103 ms/op
     p(99.9990) =     13.757 ms/op
     p(99.9999) =     13.926 ms/op
    p(100.0000) =     13.926 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.485 ± 1.353  ops/ms
ClientPb.existUser                       thrpt       3  13.066 ± 0.967  ops/ms
ClientPb.getUser                         thrpt       3  12.716 ± 1.263  ops/ms
ClientPb.listUser                        thrpt       3  10.644 ± 0.502  ops/ms
ClientPb.createUser                       avgt       3   2.530 ± 0.256   ms/op
ClientPb.existUser                        avgt       3   2.462 ± 0.211   ms/op
ClientPb.getUser                          avgt       3   2.511 ± 0.417   ms/op
ClientPb.listUser                         avgt       3   3.007 ± 0.038   ms/op
ClientPb.createUser                     sample  378211   2.536 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.906           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.068           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.944           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.929           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.877           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.287           ms/op
ClientPb.existUser                      sample  385175   2.491 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.824           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.576           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.863           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.691           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.508           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.303           ms/op
ClientPb.getUser                        sample  379228   2.529 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.892           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.556           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.232           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.969           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.684           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.945           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.565           ms/op
ClientPb.listUser                       sample  318284   3.014 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.654           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.612           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.220           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.103           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.926           ms/op
