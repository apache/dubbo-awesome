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
# Warmup Iteration   1: 4.990 ops/ms
# Warmup Iteration   2: 12.160 ops/ms
# Warmup Iteration   3: 12.522 ops/ms
Iteration   1: 12.632 ops/ms
Iteration   2: 12.561 ops/ms
Iteration   3: 12.538 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.577 ±(99.9%) 0.899 ops/ms [Average]
  (min, avg, max) = (12.538, 12.577, 12.632), stdev = 0.049
  CI (99.9%): [11.678, 13.476] (assumes normal distribution)


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
# Warmup Iteration   1: 7.773 ops/ms
# Warmup Iteration   2: 13.118 ops/ms
# Warmup Iteration   3: 13.072 ops/ms
Iteration   1: 13.138 ops/ms
Iteration   2: 13.208 ops/ms
Iteration   3: 13.159 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.168 ±(99.9%) 0.653 ops/ms [Average]
  (min, avg, max) = (13.138, 13.168, 13.208), stdev = 0.036
  CI (99.9%): [12.515, 13.821] (assumes normal distribution)


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
# Warmup Iteration   1: 8.196 ops/ms
# Warmup Iteration   2: 12.735 ops/ms
# Warmup Iteration   3: 12.981 ops/ms
Iteration   1: 13.054 ops/ms
Iteration   2: 13.035 ops/ms
Iteration   3: 12.907 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.999 ±(99.9%) 1.452 ops/ms [Average]
  (min, avg, max) = (12.907, 12.999, 13.054), stdev = 0.080
  CI (99.9%): [11.547, 14.450] (assumes normal distribution)


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
# Warmup Iteration   1: 6.417 ops/ms
# Warmup Iteration   2: 10.568 ops/ms
# Warmup Iteration   3: 10.347 ops/ms
Iteration   1: 10.437 ops/ms
Iteration   2: 10.463 ops/ms
Iteration   3: 10.388 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.429 ±(99.9%) 0.696 ops/ms [Average]
  (min, avg, max) = (10.388, 10.429, 10.463), stdev = 0.038
  CI (99.9%): [9.733, 11.125] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.059 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.555 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.004 ms/op
Iteration   1: 2.498 ±(99.9%) 0.004 ms/op
Iteration   2: 2.431 ±(99.9%) 0.004 ms/op
Iteration   3: 2.481 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.470 ±(99.9%) 0.630 ms/op [Average]
  (min, avg, max) = (2.431, 2.470, 2.498), stdev = 0.035
  CI (99.9%): [1.840, 3.100] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.716 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.448 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.400 ±(99.9%) 0.003 ms/op
Iteration   1: 2.412 ±(99.9%) 0.004 ms/op
Iteration   2: 2.425 ±(99.9%) 0.005 ms/op
Iteration   3: 2.413 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.417 ±(99.9%) 0.137 ms/op [Average]
  (min, avg, max) = (2.412, 2.417, 2.425), stdev = 0.008
  CI (99.9%): [2.280, 2.554] (assumes normal distribution)


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
# Warmup Iteration   1: 4.075 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.538 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.003 ms/op
Iteration   1: 2.462 ±(99.9%) 0.004 ms/op
Iteration   2: 2.474 ±(99.9%) 0.004 ms/op
Iteration   3: 2.467 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.468 ±(99.9%) 0.108 ms/op [Average]
  (min, avg, max) = (2.462, 2.468, 2.474), stdev = 0.006
  CI (99.9%): [2.360, 2.576] (assumes normal distribution)


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
# Warmup Iteration   1: 4.783 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.050 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.006 ms/op
Iteration   1: 3.069 ±(99.9%) 0.005 ms/op
Iteration   2: 3.039 ±(99.9%) 0.006 ms/op
Iteration   3: 3.040 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.049 ±(99.9%) 0.312 ms/op [Average]
  (min, avg, max) = (3.039, 3.049, 3.069), stdev = 0.017
  CI (99.9%): [2.737, 3.361] (assumes normal distribution)


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
# Warmup Iteration   1: 3.974 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.651 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.006 ms/op
Iteration   1: 2.485 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.660 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.899 ms/op
                 createUser·p0.999:  10.438 ms/op
                 createUser·p0.9999: 13.376 ms/op
                 createUser·p1.00:   13.763 ms/op

Iteration   2: 2.446 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.046 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   2.957 ms/op
                 createUser·p0.95:   3.056 ms/op
                 createUser·p0.99:   3.592 ms/op
                 createUser·p0.999:  6.423 ms/op
                 createUser·p0.9999: 11.303 ms/op
                 createUser·p1.00:   11.829 ms/op

Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.733 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.625 ms/op
                 createUser·p0.999:  8.567 ms/op
                 createUser·p0.9999: 10.148 ms/op
                 createUser·p1.00:   10.568 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 388770
  mean =      2.468 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 190931 
    [ 2.500,  3.750) = 194221 
    [ 3.750,  5.000) = 2759 
    [ 5.000,  6.250) = 309 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 142 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.700 ms/op
     p(99.9000) =      8.995 ms/op
     p(99.9900) =     12.669 ms/op
     p(99.9990) =     13.541 ms/op
     p(99.9999) =     13.763 ms/op
    p(100.0000) =     13.763 ms/op


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
# Warmup Iteration   1: 3.629 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.484 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.448 ±(99.9%) 0.005 ms/op
Iteration   1: 2.454 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.030 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.408 ms/op
                 existUser·p0.999:  5.793 ms/op
                 existUser·p0.9999: 13.877 ms/op
                 existUser·p1.00:   14.303 ms/op

Iteration   2: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.028 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.518 ms/op
                 existUser·p0.999:  6.698 ms/op
                 existUser·p0.9999: 13.075 ms/op
                 existUser·p1.00:   14.303 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.621 ms/op
                 existUser·p0.999:  6.686 ms/op
                 existUser·p0.9999: 11.864 ms/op
                 existUser·p1.00:   12.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388634
  mean =      2.468 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 24 
    [ 1.250,  2.500) = 191047 
    [ 2.500,  3.750) = 194961 
    [ 3.750,  5.000) = 1970 
    [ 5.000,  6.250) = 223 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 108 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.514 ms/op
     p(99.9000) =      6.639 ms/op
     p(99.9900) =     13.517 ms/op
     p(99.9990) =     14.145 ms/op
     p(99.9999) =     14.303 ms/op
    p(100.0000) =     14.303 ms/op


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
# Warmup Iteration   1: 3.857 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.552 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.006 ms/op
Iteration   1: 2.456 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.627 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.715 ms/op
                 getUser·p0.999:  6.200 ms/op
                 getUser·p0.9999: 13.663 ms/op
                 getUser·p1.00:   14.320 ms/op

Iteration   2: 2.511 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.796 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  9.886 ms/op
                 getUser·p0.9999: 13.418 ms/op
                 getUser·p1.00:   13.746 ms/op

Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.784 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.695 ms/op
                 getUser·p0.999:  5.703 ms/op
                 getUser·p0.9999: 11.567 ms/op
                 getUser·p1.00:   12.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387662
  mean =      2.474 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 94 
    [ 1.250,  2.500) = 194325 
    [ 2.500,  3.750) = 188505 
    [ 3.750,  5.000) = 3860 
    [ 5.000,  6.250) = 478 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 105 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.627 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.871 ms/op
     p(99.9000) =      6.881 ms/op
     p(99.9900) =     13.386 ms/op
     p(99.9990) =     14.092 ms/op
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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.634 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.009 ms/op
Iteration   1: 2.974 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.838 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  8.864 ms/op
                 listUser·p0.9999: 11.469 ms/op
                 listUser·p1.00:   12.272 ms/op

Iteration   2: 2.997 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.905 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  8.847 ms/op
                 listUser·p0.9999: 11.097 ms/op
                 listUser·p1.00:   12.517 ms/op

Iteration   3: 3.014 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.671 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.540 ms/op
                 listUser·p0.999:  9.516 ms/op
                 listUser·p0.9999: 11.990 ms/op
                 listUser·p1.00:   12.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320223
  mean =      2.995 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 165 
    [ 1.250,  2.500) = 95634 
    [ 2.500,  3.750) = 186891 
    [ 3.750,  5.000) = 30421 
    [ 5.000,  6.250) = 5765 
    [ 6.250,  7.500) = 703 
    [ 7.500,  8.750) = 264 
    [ 8.750, 10.000) = 192 
    [10.000, 11.250) = 126 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     11.698 ms/op
     p(99.9990) =     12.301 ms/op
     p(99.9999) =     12.517 ms/op
    p(100.0000) =     12.517 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.577 ± 0.899  ops/ms
ClientPb.existUser                       thrpt       3  13.168 ± 0.653  ops/ms
ClientPb.getUser                         thrpt       3  12.999 ± 1.452  ops/ms
ClientPb.listUser                        thrpt       3  10.429 ± 0.696  ops/ms
ClientPb.createUser                       avgt       3   2.470 ± 0.630   ms/op
ClientPb.existUser                        avgt       3   2.417 ± 0.137   ms/op
ClientPb.getUser                          avgt       3   2.468 ± 0.108   ms/op
ClientPb.listUser                         avgt       3   3.049 ± 0.312   ms/op
ClientPb.createUser                     sample  388770   2.468 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.660           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.540           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.994           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.700           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.995           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.669           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.763           ms/op
ClientPb.existUser                      sample  388634   2.468 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.813           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.514           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.639           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.517           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.303           ms/op
ClientPb.getUser                        sample  387662   2.474 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.627           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.494           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.881           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.386           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.320           ms/op
ClientPb.listUser                       sample  320223   2.995 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.671           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.044           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.698           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.517           ms/op
