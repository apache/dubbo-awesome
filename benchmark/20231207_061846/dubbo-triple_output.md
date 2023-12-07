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
# Warmup Iteration   1: 4.579 ops/ms
# Warmup Iteration   2: 12.047 ops/ms
# Warmup Iteration   3: 12.293 ops/ms
Iteration   1: 12.614 ops/ms
Iteration   2: 12.465 ops/ms
Iteration   3: 12.515 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.531 ±(99.9%) 1.389 ops/ms [Average]
  (min, avg, max) = (12.465, 12.531, 12.614), stdev = 0.076
  CI (99.9%): [11.143, 13.920] (assumes normal distribution)


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
# Warmup Iteration   1: 8.114 ops/ms
# Warmup Iteration   2: 12.966 ops/ms
# Warmup Iteration   3: 12.821 ops/ms
Iteration   1: 12.876 ops/ms
Iteration   2: 12.859 ops/ms
Iteration   3: 12.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.865 ±(99.9%) 0.172 ops/ms [Average]
  (min, avg, max) = (12.859, 12.865, 12.876), stdev = 0.009
  CI (99.9%): [12.693, 13.037] (assumes normal distribution)


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
# Warmup Iteration   1: 7.735 ops/ms
# Warmup Iteration   2: 12.678 ops/ms
# Warmup Iteration   3: 12.902 ops/ms
Iteration   1: 12.910 ops/ms
Iteration   2: 12.699 ops/ms
Iteration   3: 12.526 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.712 ±(99.9%) 3.506 ops/ms [Average]
  (min, avg, max) = (12.526, 12.712, 12.910), stdev = 0.192
  CI (99.9%): [9.206, 16.218] (assumes normal distribution)


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
# Warmup Iteration   1: 6.475 ops/ms
# Warmup Iteration   2: 10.527 ops/ms
# Warmup Iteration   3: 10.485 ops/ms
Iteration   1: 10.653 ops/ms
Iteration   2: 10.583 ops/ms
Iteration   3: 10.551 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.596 ±(99.9%) 0.953 ops/ms [Average]
  (min, avg, max) = (10.551, 10.596, 10.653), stdev = 0.052
  CI (99.9%): [9.643, 11.549] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.912 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
Iteration   1: 2.525 ±(99.9%) 0.004 ms/op
Iteration   2: 2.500 ±(99.9%) 0.004 ms/op
Iteration   3: 2.487 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.504 ±(99.9%) 0.356 ms/op [Average]
  (min, avg, max) = (2.487, 2.504, 2.525), stdev = 0.020
  CI (99.9%): [2.148, 2.860] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.657 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.516 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.003 ms/op
Iteration   1: 2.495 ±(99.9%) 0.003 ms/op
Iteration   2: 2.565 ±(99.9%) 0.005 ms/op
Iteration   3: 2.509 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.523 ±(99.9%) 0.676 ms/op [Average]
  (min, avg, max) = (2.495, 2.523, 2.565), stdev = 0.037
  CI (99.9%): [1.847, 3.199] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.018 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
Iteration   1: 2.494 ±(99.9%) 0.004 ms/op
Iteration   2: 2.494 ±(99.9%) 0.004 ms/op
Iteration   3: 2.485 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.491 ±(99.9%) 0.101 ms/op [Average]
  (min, avg, max) = (2.485, 2.491, 2.494), stdev = 0.006
  CI (99.9%): [2.390, 2.591] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.729 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.005 ms/op
Iteration   1: 3.061 ±(99.9%) 0.006 ms/op
Iteration   2: 2.988 ±(99.9%) 0.005 ms/op
Iteration   3: 3.011 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.020 ±(99.9%) 0.682 ms/op [Average]
  (min, avg, max) = (2.988, 3.020, 3.061), stdev = 0.037
  CI (99.9%): [2.338, 3.701] (assumes normal distribution)


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
# Warmup Iteration   1: 4.110 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.690 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.559 ±(99.9%) 0.006 ms/op
Iteration   1: 2.567 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.854 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   3.981 ms/op
                 createUser·p0.999:  11.662 ms/op
                 createUser·p0.9999: 22.370 ms/op
                 createUser·p1.00:   23.495 ms/op

Iteration   2: 2.549 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.005 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.834 ms/op
                 createUser·p0.999:  10.451 ms/op
                 createUser·p0.9999: 12.108 ms/op
                 createUser·p1.00:   12.354 ms/op

Iteration   3: 2.550 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.039 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   4.026 ms/op
                 createUser·p0.999:  9.142 ms/op
                 createUser·p0.9999: 11.026 ms/op
                 createUser·p1.00:   11.895 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375401
  mean =      2.555 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 177091 
    [ 2.500,  5.000) = 197193 
    [ 5.000,  7.500) = 692 
    [ 7.500, 10.000) = 99 
    [10.000, 12.500) = 220 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      2.638 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.936 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     15.067 ms/op
     p(99.9990) =     23.059 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


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
# Warmup Iteration   1: 3.672 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.483 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.006 ms/op
Iteration   1: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.016 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.441 ms/op
                 existUser·p0.999:  4.924 ms/op
                 existUser·p0.9999: 13.943 ms/op
                 existUser·p1.00:   14.451 ms/op

Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.126 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.654 ms/op
                 existUser·p0.999:  7.438 ms/op
                 existUser·p0.9999: 14.665 ms/op
                 existUser·p1.00:   15.532 ms/op

Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.935 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.158 ms/op
                 existUser·p0.99:   3.963 ms/op
                 existUser·p0.999:  7.234 ms/op
                 existUser·p0.9999: 11.880 ms/op
                 existUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388943
  mean =      2.466 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 191936 
    [ 2.500,  3.750) = 193461 
    [ 3.750,  5.000) = 2858 
    [ 5.000,  6.250) = 267 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.690 ms/op
     p(99.9000) =      6.178 ms/op
     p(99.9900) =     13.894 ms/op
     p(99.9990) =     15.261 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.749 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.560 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.006 ms/op
Iteration   1: 2.500 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.927 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.180 ms/op
                 getUser·p0.99:   3.777 ms/op
                 getUser·p0.999:  11.665 ms/op
                 getUser·p0.9999: 15.257 ms/op
                 getUser·p1.00:   16.810 ms/op

Iteration   2: 2.475 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.975 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.793 ms/op
                 getUser·p0.999:  5.626 ms/op
                 getUser·p0.9999: 13.124 ms/op
                 getUser·p1.00:   14.303 ms/op

Iteration   3: 2.519 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.651 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.265 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  6.726 ms/op
                 getUser·p0.9999: 12.522 ms/op
                 getUser·p1.00:   13.320 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383994
  mean =      2.498 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 190349 
    [ 2.500,  3.750) = 188174 
    [ 3.750,  5.000) = 4068 
    [ 5.000,  6.250) = 932 
    [ 6.250,  7.500) = 73 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.998 ms/op
     p(99.9000) =      6.464 ms/op
     p(99.9900) =     14.182 ms/op
     p(99.9990) =     16.777 ms/op
     p(99.9999) =     16.810 ms/op
    p(100.0000) =     16.810 ms/op


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
# Warmup Iteration   1: 4.599 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.009 ms/op
Iteration   1: 3.029 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.721 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.751 ms/op
                 listUser·p0.999:  9.470 ms/op
                 listUser·p0.9999: 11.298 ms/op
                 listUser·p1.00:   12.747 ms/op

Iteration   2: 3.033 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.851 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.775 ms/op
                 listUser·p0.999:  9.470 ms/op
                 listUser·p0.9999: 11.354 ms/op
                 listUser·p1.00:   11.715 ms/op

Iteration   3: 2.996 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.850 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  8.602 ms/op
                 listUser·p0.9999: 10.895 ms/op
                 listUser·p1.00:   11.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317669
  mean =      3.019 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 143 
    [ 1.250,  2.500) = 92887 
    [ 2.500,  3.750) = 183916 
    [ 3.750,  5.000) = 32508 
    [ 5.000,  6.250) = 6766 
    [ 6.250,  7.500) = 704 
    [ 7.500,  8.750) = 317 
    [ 8.750, 10.000) = 257 
    [10.000, 11.250) = 145 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =      9.273 ms/op
     p(99.9900) =     11.178 ms/op
     p(99.9990) =     12.683 ms/op
     p(99.9999) =     12.747 ms/op
    p(100.0000) =     12.747 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.531 ± 1.389  ops/ms
ClientPb.existUser                       thrpt       3  12.865 ± 0.172  ops/ms
ClientPb.getUser                         thrpt       3  12.712 ± 3.506  ops/ms
ClientPb.listUser                        thrpt       3  10.596 ± 0.953  ops/ms
ClientPb.createUser                       avgt       3   2.504 ± 0.356   ms/op
ClientPb.existUser                        avgt       3   2.523 ± 0.676   ms/op
ClientPb.getUser                          avgt       3   2.491 ± 0.101   ms/op
ClientPb.listUser                         avgt       3   3.020 ± 0.682   ms/op
ClientPb.createUser                     sample  375401   2.555 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.854           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.638           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.936           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.241           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.067           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.495           ms/op
ClientPb.existUser                      sample  388943   2.466 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.935           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.690           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.178           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.894           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.532           ms/op
ClientPb.getUser                        sample  383994   2.498 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.651           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.998           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.464           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.182           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.810           ms/op
ClientPb.listUser                       sample  317669   3.019 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.721           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.661           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.273           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.178           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.747           ms/op
