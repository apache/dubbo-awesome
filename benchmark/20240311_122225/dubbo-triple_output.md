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
# Warmup Iteration   1: 5.281 ops/ms
# Warmup Iteration   2: 12.198 ops/ms
# Warmup Iteration   3: 12.560 ops/ms
Iteration   1: 12.690 ops/ms
Iteration   2: 12.788 ops/ms
Iteration   3: 12.717 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.731 ±(99.9%) 0.927 ops/ms [Average]
  (min, avg, max) = (12.690, 12.731, 12.788), stdev = 0.051
  CI (99.9%): [11.805, 13.658] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.613 ops/ms
# Warmup Iteration   2: 13.280 ops/ms
# Warmup Iteration   3: 13.388 ops/ms
Iteration   1: 13.392 ops/ms
Iteration   2: 13.374 ops/ms
Iteration   3: 13.204 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.323 ±(99.9%) 1.896 ops/ms [Average]
  (min, avg, max) = (13.204, 13.323, 13.392), stdev = 0.104
  CI (99.9%): [11.427, 15.219] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.172 ops/ms
# Warmup Iteration   2: 12.858 ops/ms
# Warmup Iteration   3: 13.189 ops/ms
Iteration   1: 13.237 ops/ms
Iteration   2: 13.148 ops/ms
Iteration   3: 13.319 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.235 ±(99.9%) 1.562 ops/ms [Average]
  (min, avg, max) = (13.148, 13.235, 13.319), stdev = 0.086
  CI (99.9%): [11.672, 14.797] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.562 ops/ms
# Warmup Iteration   2: 10.733 ops/ms
# Warmup Iteration   3: 10.715 ops/ms
Iteration   1: 10.755 ops/ms
Iteration   2: 10.745 ops/ms
Iteration   3: 10.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.765 ±(99.9%) 0.500 ops/ms [Average]
  (min, avg, max) = (10.745, 10.765, 10.796), stdev = 0.027
  CI (99.9%): [10.266, 11.265] (assumes normal distribution)


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
# Warmup Iteration   1: 4.007 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.542 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.004 ms/op
Iteration   1: 2.533 ±(99.9%) 0.004 ms/op
Iteration   2: 2.506 ±(99.9%) 0.003 ms/op
Iteration   3: 2.497 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.512 ±(99.9%) 0.343 ms/op [Average]
  (min, avg, max) = (2.497, 2.512, 2.533), stdev = 0.019
  CI (99.9%): [2.169, 2.855] (assumes normal distribution)


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
# Warmup Iteration   1: 3.612 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.417 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.419 ±(99.9%) 0.004 ms/op
Iteration   1: 2.417 ±(99.9%) 0.003 ms/op
Iteration   2: 2.427 ±(99.9%) 0.003 ms/op
Iteration   3: 2.420 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.421 ±(99.9%) 0.092 ms/op [Average]
  (min, avg, max) = (2.417, 2.421, 2.427), stdev = 0.005
  CI (99.9%): [2.330, 2.513] (assumes normal distribution)


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
# Warmup Iteration   1: 3.857 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.513 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.453 ±(99.9%) 0.004 ms/op
Iteration   1: 2.448 ±(99.9%) 0.004 ms/op
Iteration   2: 2.418 ±(99.9%) 0.004 ms/op
Iteration   3: 2.422 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.429 ±(99.9%) 0.297 ms/op [Average]
  (min, avg, max) = (2.418, 2.429, 2.448), stdev = 0.016
  CI (99.9%): [2.132, 2.726] (assumes normal distribution)


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
# Warmup Iteration   1: 4.608 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.988 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.006 ms/op
Iteration   1: 2.964 ±(99.9%) 0.004 ms/op
Iteration   2: 2.973 ±(99.9%) 0.005 ms/op
Iteration   3: 2.961 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.966 ±(99.9%) 0.114 ms/op [Average]
  (min, avg, max) = (2.961, 2.966, 2.973), stdev = 0.006
  CI (99.9%): [2.852, 3.080] (assumes normal distribution)


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
# Warmup Iteration   1: 4.004 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.598 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.006 ms/op
Iteration   1: 2.478 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.952 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.744 ms/op
                 createUser·p0.999:  10.519 ms/op
                 createUser·p0.9999: 15.804 ms/op
                 createUser·p1.00:   16.744 ms/op

Iteration   2: 2.473 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.869 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.625 ms/op
                 createUser·p0.999:  7.802 ms/op
                 createUser·p0.9999: 11.290 ms/op
                 createUser·p1.00:   11.616 ms/op

Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.865 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.768 ms/op
                 createUser·p0.999:  8.562 ms/op
                 createUser·p0.9999: 10.813 ms/op
                 createUser·p1.00:   14.828 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386747
  mean =      2.479 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 189331 
    [ 2.500,  3.750) = 193755 
    [ 3.750,  5.000) = 2900 
    [ 5.000,  6.250) = 225 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 112 
    [10.000, 11.250) = 137 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.865 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.707 ms/op
     p(99.9000) =      8.966 ms/op
     p(99.9900) =     13.833 ms/op
     p(99.9990) =     16.194 ms/op
     p(99.9999) =     16.744 ms/op
    p(100.0000) =     16.744 ms/op


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
# Warmup Iteration   1: 3.747 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.473 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.433 ±(99.9%) 0.005 ms/op
Iteration   1: 2.437 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  5.483 ms/op
                 existUser·p0.9999: 13.763 ms/op
                 existUser·p1.00:   14.598 ms/op

Iteration   2: 2.421 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.882 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.494 ms/op
                 existUser·p0.999:  6.018 ms/op
                 existUser·p0.9999: 12.376 ms/op
                 existUser·p1.00:   13.107 ms/op

Iteration   3: 2.429 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.970 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.670 ms/op
                 existUser·p0.999:  7.135 ms/op
                 existUser·p0.9999: 10.715 ms/op
                 existUser·p1.00:   11.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394815
  mean =      2.429 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 196906 
    [ 2.500,  3.750) = 194955 
    [ 3.750,  5.000) = 2258 
    [ 5.000,  6.250) = 204 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 97 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.945 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      3.584 ms/op
     p(99.9000) =      7.058 ms/op
     p(99.9900) =     13.157 ms/op
     p(99.9990) =     14.057 ms/op
     p(99.9999) =     14.598 ms/op
    p(100.0000) =     14.598 ms/op


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
# Warmup Iteration   1: 3.741 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.499 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
Iteration   1: 2.430 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.972 ms/op
                 getUser·p0.50:   2.429 ms/op
                 getUser·p0.90:   2.961 ms/op
                 getUser·p0.95:   3.072 ms/op
                 getUser·p0.99:   3.518 ms/op
                 getUser·p0.999:  6.627 ms/op
                 getUser·p0.9999: 12.927 ms/op
                 getUser·p1.00:   13.894 ms/op

Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.706 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   2.982 ms/op
                 getUser·p0.95:   3.101 ms/op
                 getUser·p0.99:   3.813 ms/op
                 getUser·p0.999:  6.674 ms/op
                 getUser·p0.9999: 12.058 ms/op
                 getUser·p1.00:   12.730 ms/op

Iteration   3: 2.434 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.988 ms/op
                 getUser·p0.50:   2.445 ms/op
                 getUser·p0.90:   2.970 ms/op
                 getUser·p0.95:   3.084 ms/op
                 getUser·p0.99:   3.604 ms/op
                 getUser·p0.999:  6.387 ms/op
                 getUser·p0.9999: 10.784 ms/op
                 getUser·p1.00:   11.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 392994
  mean =      2.441 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 95 
    [ 1.250,  2.500) = 200023 
    [ 2.500,  3.750) = 189710 
    [ 3.750,  5.000) = 2331 
    [ 5.000,  6.250) = 428 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 127 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      2.458 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.633 ms/op
     p(99.9000) =      6.595 ms/op
     p(99.9900) =     12.660 ms/op
     p(99.9990) =     13.115 ms/op
     p(99.9999) =     13.894 ms/op
    p(100.0000) =     13.894 ms/op


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
# Warmup Iteration   1: 4.600 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.023 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.008 ms/op
Iteration   1: 2.971 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.768 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.346 ms/op
                 listUser·p0.9999: 11.030 ms/op
                 listUser·p1.00:   11.534 ms/op

Iteration   2: 2.963 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.939 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.423 ms/op
                 listUser·p0.999:  9.111 ms/op
                 listUser·p0.9999: 10.584 ms/op
                 listUser·p1.00:   10.994 ms/op

Iteration   3: 2.981 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.981 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.568 ms/op
                 listUser·p0.9999: 11.232 ms/op
                 listUser·p1.00:   12.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322725
  mean =      2.972 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 173 
    [ 1.250,  2.500) = 98212 
    [ 2.500,  3.750) = 187401 
    [ 3.750,  5.000) = 30547 
    [ 5.000,  6.250) = 5105 
    [ 6.250,  7.500) = 602 
    [ 7.500,  8.750) = 213 
    [ 8.750, 10.000) = 307 
    [10.000, 11.250) = 153 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     11.026 ms/op
     p(99.9990) =     12.084 ms/op
     p(99.9999) =     12.222 ms/op
    p(100.0000) =     12.222 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.731 ± 0.927  ops/ms
ClientPb.existUser                       thrpt       3  13.323 ± 1.896  ops/ms
ClientPb.getUser                         thrpt       3  13.235 ± 1.562  ops/ms
ClientPb.listUser                        thrpt       3  10.765 ± 0.500  ops/ms
ClientPb.createUser                       avgt       3   2.512 ± 0.343   ms/op
ClientPb.existUser                        avgt       3   2.421 ± 0.092   ms/op
ClientPb.getUser                          avgt       3   2.429 ± 0.297   ms/op
ClientPb.listUser                         avgt       3   2.966 ± 0.114   ms/op
ClientPb.createUser                     sample  386747   2.479 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.865           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.548           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.011           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.707           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.966           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.833           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.744           ms/op
ClientPb.existUser                      sample  394815   2.429 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.882           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.945           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.584           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.058           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.157           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.598           ms/op
ClientPb.getUser                        sample  392994   2.441 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.706           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.458           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.970           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.633           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.595           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.660           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.894           ms/op
ClientPb.listUser                       sample  322725   2.972 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.768           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.480           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.339           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.026           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.222           ms/op
