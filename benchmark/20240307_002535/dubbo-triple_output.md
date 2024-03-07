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
# Warmup Iteration   1: 5.689 ops/ms
# Warmup Iteration   2: 12.593 ops/ms
# Warmup Iteration   3: 12.930 ops/ms
Iteration   1: 13.130 ops/ms
Iteration   2: 13.302 ops/ms
Iteration   3: 13.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  13.292 ±(99.9%) 2.848 ops/ms [Average]
  (min, avg, max) = (13.130, 13.292, 13.442), stdev = 0.156
  CI (99.9%): [10.444, 16.139] (assumes normal distribution)


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
# Warmup Iteration   1: 8.797 ops/ms
# Warmup Iteration   2: 13.739 ops/ms
# Warmup Iteration   3: 13.862 ops/ms
Iteration   1: 13.748 ops/ms
Iteration   2: 13.985 ops/ms
Iteration   3: 13.725 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.820 ±(99.9%) 2.627 ops/ms [Average]
  (min, avg, max) = (13.725, 13.820, 13.985), stdev = 0.144
  CI (99.9%): [11.193, 16.447] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.335 ops/ms
# Warmup Iteration   2: 12.923 ops/ms
# Warmup Iteration   3: 13.315 ops/ms
Iteration   1: 13.308 ops/ms
Iteration   2: 13.377 ops/ms
Iteration   3: 13.369 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.351 ±(99.9%) 0.688 ops/ms [Average]
  (min, avg, max) = (13.308, 13.351, 13.377), stdev = 0.038
  CI (99.9%): [12.663, 14.040] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.097 ops/ms
# Warmup Iteration   2: 10.956 ops/ms
# Warmup Iteration   3: 10.970 ops/ms
Iteration   1: 10.978 ops/ms
Iteration   2: 11.052 ops/ms
Iteration   3: 10.942 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.991 ±(99.9%) 1.028 ops/ms [Average]
  (min, avg, max) = (10.942, 10.991, 11.052), stdev = 0.056
  CI (99.9%): [9.963, 12.018] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.716 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.579 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.004 ms/op
Iteration   1: 2.475 ±(99.9%) 0.003 ms/op
Iteration   2: 2.479 ±(99.9%) 0.004 ms/op
Iteration   3: 2.475 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.477 ±(99.9%) 0.040 ms/op [Average]
  (min, avg, max) = (2.475, 2.477, 2.479), stdev = 0.002
  CI (99.9%): [2.436, 2.517] (assumes normal distribution)


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
# Warmup Iteration   1: 3.453 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.401 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.391 ±(99.9%) 0.003 ms/op
Iteration   1: 2.350 ±(99.9%) 0.004 ms/op
Iteration   2: 2.369 ±(99.9%) 0.003 ms/op
Iteration   3: 2.373 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.364 ±(99.9%) 0.222 ms/op [Average]
  (min, avg, max) = (2.350, 2.364, 2.373), stdev = 0.012
  CI (99.9%): [2.142, 2.586] (assumes normal distribution)


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
# Warmup Iteration   1: 3.724 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.440 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.450 ±(99.9%) 0.003 ms/op
Iteration   1: 2.427 ±(99.9%) 0.004 ms/op
Iteration   2: 2.447 ±(99.9%) 0.005 ms/op
Iteration   3: 2.413 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.429 ±(99.9%) 0.310 ms/op [Average]
  (min, avg, max) = (2.413, 2.429, 2.447), stdev = 0.017
  CI (99.9%): [2.119, 2.739] (assumes normal distribution)


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
# Warmup Iteration   1: 4.310 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.939 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.918 ±(99.9%) 0.006 ms/op
Iteration   1: 2.901 ±(99.9%) 0.005 ms/op
Iteration   2: 2.908 ±(99.9%) 0.005 ms/op
Iteration   3: 2.906 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.905 ±(99.9%) 0.063 ms/op [Average]
  (min, avg, max) = (2.901, 2.905, 2.908), stdev = 0.003
  CI (99.9%): [2.842, 2.968] (assumes normal distribution)


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
# Warmup Iteration   1: 3.923 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.622 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.006 ms/op
Iteration   1: 2.436 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.784 ms/op
                 createUser·p0.50:   2.511 ms/op
                 createUser·p0.90:   2.957 ms/op
                 createUser·p0.95:   3.068 ms/op
                 createUser·p0.99:   3.576 ms/op
                 createUser·p0.999:  7.570 ms/op
                 createUser·p0.9999: 15.907 ms/op
                 createUser·p1.00:   16.597 ms/op

Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.949 ms/op
                 createUser·p0.50:   2.511 ms/op
                 createUser·p0.90:   2.994 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.572 ms/op
                 createUser·p0.999:  7.898 ms/op
                 createUser·p0.9999: 15.500 ms/op
                 createUser·p1.00:   17.138 ms/op

Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.893 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   4.047 ms/op
                 createUser·p0.999:  8.507 ms/op
                 createUser·p0.9999: 11.735 ms/op
                 createUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 390556
  mean =      2.455 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 90 
    [ 1.250,  2.500) = 193240 
    [ 2.500,  3.750) = 193500 
    [ 3.750,  5.000) = 2923 
    [ 5.000,  6.250) = 337 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.723 ms/op
     p(99.9000) =      8.471 ms/op
     p(99.9900) =     15.711 ms/op
     p(99.9990) =     16.980 ms/op
     p(99.9999) =     17.138 ms/op
    p(100.0000) =     17.138 ms/op


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
# Warmup Iteration   1: 3.540 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.391 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.389 ±(99.9%) 0.005 ms/op
Iteration   1: 2.385 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.811 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.884 ms/op
                 existUser·p0.95:   2.982 ms/op
                 existUser·p0.99:   3.367 ms/op
                 existUser·p0.999:  5.192 ms/op
                 existUser·p0.9999: 14.214 ms/op
                 existUser·p1.00:   14.991 ms/op

Iteration   2: 2.385 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.969 ms/op
                 existUser·p0.50:   2.429 ms/op
                 existUser·p0.90:   2.904 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.777 ms/op
                 existUser·p0.999:  6.266 ms/op
                 existUser·p0.9999: 10.630 ms/op
                 existUser·p1.00:   12.009 ms/op

Iteration   3: 2.378 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.926 ms/op
                 existUser·p0.50:   2.425 ms/op
                 existUser·p0.90:   2.888 ms/op
                 existUser·p0.95:   2.994 ms/op
                 existUser·p0.99:   3.555 ms/op
                 existUser·p0.999:  8.145 ms/op
                 existUser·p0.9999: 11.625 ms/op
                 existUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 402499
  mean =      2.383 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 83 
    [ 1.250,  2.500) = 208114 
    [ 2.500,  3.750) = 191285 
    [ 3.750,  5.000) = 2227 
    [ 5.000,  6.250) = 371 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 99 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      2.445 ms/op
     p(90.0000) =      2.892 ms/op
     p(95.0000) =      3.002 ms/op
     p(99.0000) =      3.564 ms/op
     p(99.9000) =      6.427 ms/op
     p(99.9900) =     12.775 ms/op
     p(99.9990) =     14.778 ms/op
     p(99.9999) =     14.991 ms/op
    p(100.0000) =     14.991 ms/op


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
# Warmup Iteration   1: 3.714 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.508 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.006 ms/op
Iteration   1: 2.424 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.927 ms/op
                 getUser·p0.50:   2.445 ms/op
                 getUser·p0.90:   2.957 ms/op
                 getUser·p0.95:   3.084 ms/op
                 getUser·p0.99:   3.633 ms/op
                 getUser·p0.999:  5.657 ms/op
                 getUser·p0.9999: 13.415 ms/op
                 getUser·p1.00:   13.779 ms/op

Iteration   2: 2.529 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.810 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.445 ms/op
                 getUser·p0.99:   5.014 ms/op
                 getUser·p0.999:  9.063 ms/op
                 getUser·p0.9999: 14.123 ms/op
                 getUser·p1.00:   14.926 ms/op

Iteration   3: 2.434 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.839 ms/op
                 getUser·p0.50:   2.454 ms/op
                 getUser·p0.90:   2.974 ms/op
                 getUser·p0.95:   3.105 ms/op
                 getUser·p0.99:   3.666 ms/op
                 getUser·p0.999:  6.255 ms/op
                 getUser·p0.9999: 11.893 ms/op
                 getUser·p1.00:   12.403 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389629
  mean =      2.462 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 132 
    [ 1.250,  2.500) = 197082 
    [ 2.500,  3.750) = 185765 
    [ 3.750,  5.000) = 4984 
    [ 5.000,  6.250) = 1145 
    [ 6.250,  7.500) = 123 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 90 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      7.914 ms/op
     p(99.9900) =     13.468 ms/op
     p(99.9990) =     14.667 ms/op
     p(99.9999) =     14.926 ms/op
    p(100.0000) =     14.926 ms/op


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
# Warmup Iteration   1: 4.661 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.008 ms/op
Iteration   1: 2.976 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.798 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  8.831 ms/op
                 listUser·p0.9999: 10.154 ms/op
                 listUser·p1.00:   10.486 ms/op

Iteration   2: 2.967 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.815 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.756 ms/op
                 listUser·p0.9999: 11.554 ms/op
                 listUser·p1.00:   12.698 ms/op

Iteration   3: 2.977 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.023 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.254 ms/op
                 listUser·p0.9999: 11.346 ms/op
                 listUser·p1.00:   11.731 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322558
  mean =      2.974 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 156 
    [ 1.250,  2.500) = 100879 
    [ 2.500,  3.750) = 183400 
    [ 3.750,  5.000) = 30772 
    [ 5.000,  6.250) = 6059 
    [ 6.250,  7.500) = 627 
    [ 7.500,  8.750) = 242 
    [ 8.750, 10.000) = 254 
    [10.000, 11.250) = 131 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.257 ms/op
     p(99.9900) =     11.321 ms/op
     p(99.9990) =     12.154 ms/op
     p(99.9999) =     12.698 ms/op
    p(100.0000) =     12.698 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  13.292 ± 2.848  ops/ms
ClientPb.existUser                       thrpt       3  13.820 ± 2.627  ops/ms
ClientPb.getUser                         thrpt       3  13.351 ± 0.688  ops/ms
ClientPb.listUser                        thrpt       3  10.991 ± 1.028  ops/ms
ClientPb.createUser                       avgt       3   2.477 ± 0.040   ms/op
ClientPb.existUser                        avgt       3   2.364 ± 0.222   ms/op
ClientPb.getUser                          avgt       3   2.429 ± 0.310   ms/op
ClientPb.listUser                         avgt       3   2.905 ± 0.063   ms/op
ClientPb.createUser                     sample  390556   2.455 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.784           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.515           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.986           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.723           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.471           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.711           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.138           ms/op
ClientPb.existUser                      sample  402499   2.383 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.811           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.445           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.892           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.564           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.427           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.775           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.991           ms/op
ClientPb.getUser                        sample  389629   2.462 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.810           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.482           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.998           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.227           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.914           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.468           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.926           ms/op
ClientPb.listUser                       sample  322558   2.974 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.798           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.904           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.867           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.257           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.321           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.698           ms/op
