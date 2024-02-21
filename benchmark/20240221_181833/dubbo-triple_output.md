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
# Warmup Iteration   1: 4.991 ops/ms
# Warmup Iteration   2: 12.058 ops/ms
# Warmup Iteration   3: 12.382 ops/ms
Iteration   1: 12.500 ops/ms
Iteration   2: 12.549 ops/ms
Iteration   3: 12.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.511 ±(99.9%) 0.626 ops/ms [Average]
  (min, avg, max) = (12.483, 12.511, 12.549), stdev = 0.034
  CI (99.9%): [11.885, 13.137] (assumes normal distribution)


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
# Warmup Iteration   1: 8.423 ops/ms
# Warmup Iteration   2: 13.184 ops/ms
# Warmup Iteration   3: 13.076 ops/ms
Iteration   1: 13.257 ops/ms
Iteration   2: 13.357 ops/ms
Iteration   3: 13.194 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.270 ±(99.9%) 1.500 ops/ms [Average]
  (min, avg, max) = (13.194, 13.270, 13.357), stdev = 0.082
  CI (99.9%): [11.770, 14.769] (assumes normal distribution)


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
# Warmup Iteration   1: 7.990 ops/ms
# Warmup Iteration   2: 12.672 ops/ms
# Warmup Iteration   3: 12.990 ops/ms
Iteration   1: 13.096 ops/ms
Iteration   2: 12.933 ops/ms
Iteration   3: 12.925 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.985 ±(99.9%) 1.757 ops/ms [Average]
  (min, avg, max) = (12.925, 12.985, 13.096), stdev = 0.096
  CI (99.9%): [11.228, 14.741] (assumes normal distribution)


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
# Warmup Iteration   1: 6.727 ops/ms
# Warmup Iteration   2: 10.751 ops/ms
# Warmup Iteration   3: 10.732 ops/ms
Iteration   1: 10.809 ops/ms
Iteration   2: 10.661 ops/ms
Iteration   3: 10.693 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.721 ±(99.9%) 1.425 ops/ms [Average]
  (min, avg, max) = (10.661, 10.721, 10.809), stdev = 0.078
  CI (99.9%): [9.295, 12.146] (assumes normal distribution)


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
# Warmup Iteration   1: 4.111 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.005 ms/op
Iteration   1: 2.494 ±(99.9%) 0.005 ms/op
Iteration   2: 2.523 ±(99.9%) 0.003 ms/op
Iteration   3: 2.494 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.504 ±(99.9%) 0.299 ms/op [Average]
  (min, avg, max) = (2.494, 2.504, 2.523), stdev = 0.016
  CI (99.9%): [2.205, 2.803] (assumes normal distribution)


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
# Warmup Iteration   1: 3.663 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.445 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.448 ±(99.9%) 0.004 ms/op
Iteration   1: 2.459 ±(99.9%) 0.004 ms/op
Iteration   2: 2.441 ±(99.9%) 0.004 ms/op
Iteration   3: 2.441 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.447 ±(99.9%) 0.191 ms/op [Average]
  (min, avg, max) = (2.441, 2.447, 2.459), stdev = 0.010
  CI (99.9%): [2.256, 2.638] (assumes normal distribution)


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
# Warmup Iteration   1: 3.753 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.502 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.004 ms/op
Iteration   1: 2.492 ±(99.9%) 0.004 ms/op
Iteration   2: 2.487 ±(99.9%) 0.003 ms/op
Iteration   3: 2.514 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.498 ±(99.9%) 0.267 ms/op [Average]
  (min, avg, max) = (2.487, 2.498, 2.514), stdev = 0.015
  CI (99.9%): [2.231, 2.765] (assumes normal distribution)


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
# Warmup Iteration   1: 4.636 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.007 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.006 ms/op
Iteration   1: 2.964 ±(99.9%) 0.005 ms/op
Iteration   2: 2.957 ±(99.9%) 0.005 ms/op
Iteration   3: 2.963 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.961 ±(99.9%) 0.072 ms/op [Average]
  (min, avg, max) = (2.957, 2.961, 2.964), stdev = 0.004
  CI (99.9%): [2.889, 3.034] (assumes normal distribution)


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
# Warmup Iteration   1: 4.129 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.628 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.006 ms/op
Iteration   1: 2.543 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.908 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.711 ms/op
                 createUser·p0.999:  11.239 ms/op
                 createUser·p0.9999: 13.802 ms/op
                 createUser·p1.00:   14.254 ms/op

Iteration   2: 2.535 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.098 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.838 ms/op
                 createUser·p0.999:  9.157 ms/op
                 createUser·p0.9999: 12.704 ms/op
                 createUser·p1.00:   12.960 ms/op

Iteration   3: 2.552 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.035 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.781 ms/op
                 createUser·p0.999:  8.598 ms/op
                 createUser·p0.9999: 10.443 ms/op
                 createUser·p1.00:   11.174 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377091
  mean =      2.543 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 180823 
    [ 2.500,  3.750) = 192340 
    [ 3.750,  5.000) = 2862 
    [ 5.000,  6.250) = 548 
    [ 6.250,  7.500) = 76 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 118 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.768 ms/op
     p(99.9000) =      8.649 ms/op
     p(99.9900) =     13.456 ms/op
     p(99.9990) =     14.139 ms/op
     p(99.9999) =     14.254 ms/op
    p(100.0000) =     14.254 ms/op


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
# Warmup Iteration   1: 3.621 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.473 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.439 ±(99.9%) 0.005 ms/op
Iteration   1: 2.437 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.891 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.498 ms/op
                 existUser·p0.999:  5.062 ms/op
                 existUser·p0.9999: 13.580 ms/op
                 existUser·p1.00:   14.369 ms/op

Iteration   2: 2.414 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.867 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.531 ms/op
                 existUser·p0.999:  7.047 ms/op
                 existUser·p0.9999: 12.694 ms/op
                 existUser·p1.00:   13.779 ms/op

Iteration   3: 2.433 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.011 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.518 ms/op
                 existUser·p0.999:  9.409 ms/op
                 existUser·p0.9999: 11.289 ms/op
                 existUser·p1.00:   12.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394868
  mean =      2.428 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 198835 
    [ 2.500,  3.750) = 193379 
    [ 3.750,  5.000) = 2047 
    [ 5.000,  6.250) = 151 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 116 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      3.510 ms/op
     p(99.9000) =      6.743 ms/op
     p(99.9900) =     13.287 ms/op
     p(99.9990) =     14.124 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


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
# Warmup Iteration   1: 3.921 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.575 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
Iteration   1: 2.478 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.937 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.682 ms/op
                 getUser·p0.999:  7.603 ms/op
                 getUser·p0.9999: 13.944 ms/op
                 getUser·p1.00:   14.320 ms/op

Iteration   2: 2.493 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.953 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.855 ms/op
                 getUser·p0.999:  8.405 ms/op
                 getUser·p0.9999: 12.534 ms/op
                 getUser·p1.00:   12.747 ms/op

Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.810 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.830 ms/op
                 getUser·p0.999:  5.710 ms/op
                 getUser·p0.9999: 11.166 ms/op
                 getUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384970
  mean =      2.491 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 191894 
    [ 2.500,  3.750) = 189017 
    [ 3.750,  5.000) = 3074 
    [ 5.000,  6.250) = 535 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 90 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.772 ms/op
     p(99.9000) =      6.252 ms/op
     p(99.9900) =     13.181 ms/op
     p(99.9990) =     14.189 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


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
# Warmup Iteration   1: 4.750 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.007 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.008 ms/op
Iteration   1: 2.960 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.018 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  8.896 ms/op
                 listUser·p0.9999: 10.587 ms/op
                 listUser·p1.00:   11.403 ms/op

Iteration   2: 2.975 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.014 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  9.708 ms/op
                 listUser·p0.9999: 11.605 ms/op
                 listUser·p1.00:   13.140 ms/op

Iteration   3: 2.947 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.838 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.793 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  9.405 ms/op
                 listUser·p0.9999: 11.338 ms/op
                 listUser·p1.00:   12.141 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323964
  mean =      2.961 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 150 
    [ 1.250,  2.500) = 100387 
    [ 2.500,  3.750) = 187943 
    [ 3.750,  5.000) = 29338 
    [ 5.000,  6.250) = 4909 
    [ 6.250,  7.500) = 609 
    [ 7.500,  8.750) = 157 
    [ 8.750, 10.000) = 302 
    [10.000, 11.250) = 138 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =      9.372 ms/op
     p(99.9900) =     11.141 ms/op
     p(99.9990) =     12.240 ms/op
     p(99.9999) =     13.140 ms/op
    p(100.0000) =     13.140 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.511 ± 0.626  ops/ms
ClientPb.existUser                       thrpt       3  13.270 ± 1.500  ops/ms
ClientPb.getUser                         thrpt       3  12.985 ± 1.757  ops/ms
ClientPb.listUser                        thrpt       3  10.721 ± 1.425  ops/ms
ClientPb.createUser                       avgt       3   2.504 ± 0.299   ms/op
ClientPb.existUser                        avgt       3   2.447 ± 0.191   ms/op
ClientPb.getUser                          avgt       3   2.498 ± 0.267   ms/op
ClientPb.listUser                         avgt       3   2.961 ± 0.072   ms/op
ClientPb.createUser                     sample  377091   2.543 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.908           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.621           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.080           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.649           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.456           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.254           ms/op
ClientPb.existUser                      sample  394868   2.428 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.867           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.486           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.953           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.510           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.743           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.287           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.369           ms/op
ClientPb.getUser                        sample  384970   2.491 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.810           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.772           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.252           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.181           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.320           ms/op
ClientPb.listUser                       sample  323964   2.961 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.838           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.904           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.809           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.276           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.472           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.372           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.141           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.140           ms/op
