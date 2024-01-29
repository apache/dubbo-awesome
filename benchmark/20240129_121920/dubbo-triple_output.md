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
# Warmup Iteration   1: 4.703 ops/ms
# Warmup Iteration   2: 12.050 ops/ms
# Warmup Iteration   3: 12.403 ops/ms
Iteration   1: 12.608 ops/ms
Iteration   2: 12.777 ops/ms
Iteration   3: 12.797 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.727 ±(99.9%) 1.890 ops/ms [Average]
  (min, avg, max) = (12.608, 12.727, 12.797), stdev = 0.104
  CI (99.9%): [10.837, 14.617] (assumes normal distribution)


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
# Warmup Iteration   1: 8.325 ops/ms
# Warmup Iteration   2: 12.974 ops/ms
# Warmup Iteration   3: 13.139 ops/ms
Iteration   1: 13.087 ops/ms
Iteration   2: 13.012 ops/ms
Iteration   3: 12.880 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.993 ±(99.9%) 1.912 ops/ms [Average]
  (min, avg, max) = (12.880, 12.993, 13.087), stdev = 0.105
  CI (99.9%): [11.082, 14.905] (assumes normal distribution)


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
# Warmup Iteration   1: 7.479 ops/ms
# Warmup Iteration   2: 12.652 ops/ms
# Warmup Iteration   3: 12.891 ops/ms
Iteration   1: 12.861 ops/ms
Iteration   2: 12.968 ops/ms
Iteration   3: 12.925 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.918 ±(99.9%) 0.974 ops/ms [Average]
  (min, avg, max) = (12.861, 12.918, 12.968), stdev = 0.053
  CI (99.9%): [11.944, 13.892] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.376 ops/ms
# Warmup Iteration   2: 10.479 ops/ms
# Warmup Iteration   3: 10.672 ops/ms
Iteration   1: 10.792 ops/ms
Iteration   2: 10.702 ops/ms
Iteration   3: 10.661 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.719 ±(99.9%) 1.224 ops/ms [Average]
  (min, avg, max) = (10.661, 10.719, 10.792), stdev = 0.067
  CI (99.9%): [9.494, 11.943] (assumes normal distribution)


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
# Warmup Iteration   1: 3.943 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 2.552 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.004 ms/op
Iteration   1: 2.532 ±(99.9%) 0.003 ms/op
Iteration   2: 2.513 ±(99.9%) 0.003 ms/op
Iteration   3: 2.490 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.512 ±(99.9%) 0.381 ms/op [Average]
  (min, avg, max) = (2.490, 2.512, 2.532), stdev = 0.021
  CI (99.9%): [2.130, 2.893] (assumes normal distribution)


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
# Warmup Iteration   1: 3.757 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.509 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.004 ms/op
Iteration   1: 2.479 ±(99.9%) 0.006 ms/op
Iteration   2: 2.472 ±(99.9%) 0.004 ms/op
Iteration   3: 2.504 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.485 ±(99.9%) 0.304 ms/op [Average]
  (min, avg, max) = (2.472, 2.485, 2.504), stdev = 0.017
  CI (99.9%): [2.181, 2.789] (assumes normal distribution)


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
# Warmup Iteration   1: 3.905 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.548 ±(99.9%) 0.005 ms/op
Iteration   1: 2.530 ±(99.9%) 0.004 ms/op
Iteration   2: 2.520 ±(99.9%) 0.005 ms/op
Iteration   3: 2.516 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.522 ±(99.9%) 0.128 ms/op [Average]
  (min, avg, max) = (2.516, 2.522, 2.530), stdev = 0.007
  CI (99.9%): [2.394, 2.650] (assumes normal distribution)


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
# Warmup Iteration   1: 4.666 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.005 ms/op
Iteration   1: 3.013 ±(99.9%) 0.004 ms/op
Iteration   2: 3.025 ±(99.9%) 0.006 ms/op
Iteration   3: 3.010 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.016 ±(99.9%) 0.144 ms/op [Average]
  (min, avg, max) = (3.010, 3.016, 3.025), stdev = 0.008
  CI (99.9%): [2.872, 3.160] (assumes normal distribution)


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
# Warmup Iteration   1: 3.885 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.645 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.005 ms/op
Iteration   1: 2.545 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.947 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.778 ms/op
                 createUser·p0.999:  12.261 ms/op
                 createUser·p0.9999: 13.753 ms/op
                 createUser·p1.00:   14.729 ms/op

Iteration   2: 2.542 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.686 ms/op
                 createUser·p0.999:  8.651 ms/op
                 createUser·p0.9999: 12.010 ms/op
                 createUser·p1.00:   12.878 ms/op

Iteration   3: 2.561 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.954 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   4.178 ms/op
                 createUser·p0.999:  8.710 ms/op
                 createUser·p0.9999: 12.919 ms/op
                 createUser·p1.00:   14.467 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376268
  mean =      2.549 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 27 
    [ 1.250,  2.500) = 180059 
    [ 2.500,  3.750) = 191353 
    [ 3.750,  5.000) = 3629 
    [ 5.000,  6.250) = 657 
    [ 6.250,  7.500) = 86 
    [ 7.500,  8.750) = 84 
    [ 8.750, 10.000) = 102 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 105 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      2.617 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.909 ms/op
     p(99.9000) =      8.716 ms/op
     p(99.9900) =     13.349 ms/op
     p(99.9990) =     14.510 ms/op
     p(99.9999) =     14.729 ms/op
    p(100.0000) =     14.729 ms/op


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
# Warmup Iteration   1: 3.791 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.509 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
Iteration   1: 2.482 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.894 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.703 ms/op
                 existUser·p0.999:  7.932 ms/op
                 existUser·p0.9999: 13.076 ms/op
                 existUser·p1.00:   13.926 ms/op

Iteration   2: 2.449 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.231 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.326 ms/op
                 existUser·p0.999:  5.271 ms/op
                 existUser·p0.9999: 12.564 ms/op
                 existUser·p1.00:   13.124 ms/op

Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.073 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   3.064 ms/op
                 existUser·p0.95:   3.183 ms/op
                 existUser·p0.99:   3.805 ms/op
                 existUser·p0.999:  7.852 ms/op
                 existUser·p0.9999: 12.537 ms/op
                 existUser·p1.00:   13.615 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387029
  mean =      2.478 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 191523 
    [ 2.500,  3.750) = 192283 
    [ 3.750,  5.000) = 2450 
    [ 5.000,  6.250) = 310 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 127 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.894 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.629 ms/op
     p(99.9000) =      7.151 ms/op
     p(99.9900) =     12.911 ms/op
     p(99.9990) =     13.387 ms/op
     p(99.9999) =     13.926 ms/op
    p(100.0000) =     13.926 ms/op


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
# Warmup Iteration   1: 3.756 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.572 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.006 ms/op
Iteration   1: 2.485 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.965 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.711 ms/op
                 getUser·p0.999:  9.049 ms/op
                 getUser·p0.9999: 13.552 ms/op
                 getUser·p1.00:   14.320 ms/op

Iteration   2: 2.516 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.032 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   3.773 ms/op
                 getUser·p0.999:  9.346 ms/op
                 getUser·p0.9999: 15.443 ms/op
                 getUser·p1.00:   16.187 ms/op

Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.854 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.903 ms/op
                 getUser·p0.999:  7.452 ms/op
                 getUser·p0.9999: 10.897 ms/op
                 getUser·p1.00:   11.682 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383954
  mean =      2.498 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 189715 
    [ 2.500,  3.750) = 190055 
    [ 3.750,  5.000) = 3423 
    [ 5.000,  6.250) = 286 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 53 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 129 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.789 ms/op
     p(99.9000) =      7.947 ms/op
     p(99.9900) =     14.232 ms/op
     p(99.9990) =     16.155 ms/op
     p(99.9999) =     16.187 ms/op
    p(100.0000) =     16.187 ms/op


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
# Warmup Iteration   1: 4.635 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.009 ms/op
Iteration   1: 3.058 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.862 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   5.849 ms/op
                 listUser·p0.999:  8.871 ms/op
                 listUser·p0.9999: 10.020 ms/op
                 listUser·p1.00:   11.534 ms/op

Iteration   2: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.903 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  8.978 ms/op
                 listUser·p0.9999: 12.783 ms/op
                 listUser·p1.00:   14.008 ms/op

Iteration   3: 3.041 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.790 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.450 ms/op
                 listUser·p0.99:   5.767 ms/op
                 listUser·p0.999:  9.503 ms/op
                 listUser·p0.9999: 11.886 ms/op
                 listUser·p1.00:   12.288 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315696
  mean =      3.038 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 110 
    [ 1.250,  2.500) = 88676 
    [ 2.500,  3.750) = 186233 
    [ 3.750,  5.000) = 32256 
    [ 5.000,  6.250) = 6775 
    [ 6.250,  7.500) = 962 
    [ 7.500,  8.750) = 298 
    [ 8.750, 10.000) = 242 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.790 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =      9.147 ms/op
     p(99.9900) =     11.719 ms/op
     p(99.9990) =     13.793 ms/op
     p(99.9999) =     14.008 ms/op
    p(100.0000) =     14.008 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.727 ± 1.890  ops/ms
ClientPb.existUser                       thrpt       3  12.993 ± 1.912  ops/ms
ClientPb.getUser                         thrpt       3  12.918 ± 0.974  ops/ms
ClientPb.listUser                        thrpt       3  10.719 ± 1.224  ops/ms
ClientPb.createUser                       avgt       3   2.512 ± 0.381   ms/op
ClientPb.existUser                        avgt       3   2.485 ± 0.304   ms/op
ClientPb.getUser                          avgt       3   2.522 ± 0.128   ms/op
ClientPb.listUser                         avgt       3   3.016 ± 0.144   ms/op
ClientPb.createUser                     sample  376268   2.549 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.947           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.617           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.909           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.716           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.349           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.729           ms/op
ClientPb.existUser                      sample  387029   2.478 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.894           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.151           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.911           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.926           ms/op
ClientPb.getUser                        sample  383954   2.498 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.854           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.531           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.789           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.947           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.232           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.187           ms/op
ClientPb.listUser                       sample  315696   3.038 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.790           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.978           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.710           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.147           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.719           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.008           ms/op
