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
# Warmup Iteration   1: 5.147 ops/ms
# Warmup Iteration   2: 12.161 ops/ms
# Warmup Iteration   3: 12.519 ops/ms
Iteration   1: 12.770 ops/ms
Iteration   2: 12.667 ops/ms
Iteration   3: 12.634 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.690 ±(99.9%) 1.299 ops/ms [Average]
  (min, avg, max) = (12.634, 12.690, 12.770), stdev = 0.071
  CI (99.9%): [11.391, 13.989] (assumes normal distribution)


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
# Warmup Iteration   1: 8.053 ops/ms
# Warmup Iteration   2: 13.070 ops/ms
# Warmup Iteration   3: 13.204 ops/ms
Iteration   1: 13.152 ops/ms
Iteration   2: 13.298 ops/ms
Iteration   3: 13.304 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.251 ±(99.9%) 1.567 ops/ms [Average]
  (min, avg, max) = (13.152, 13.251, 13.304), stdev = 0.086
  CI (99.9%): [11.684, 14.819] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.138 ops/ms
# Warmup Iteration   2: 12.980 ops/ms
# Warmup Iteration   3: 12.654 ops/ms
Iteration   1: 13.119 ops/ms
Iteration   2: 13.036 ops/ms
Iteration   3: 12.944 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.033 ±(99.9%) 1.600 ops/ms [Average]
  (min, avg, max) = (12.944, 13.033, 13.119), stdev = 0.088
  CI (99.9%): [11.433, 14.633] (assumes normal distribution)


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
# Warmup Iteration   1: 6.648 ops/ms
# Warmup Iteration   2: 10.581 ops/ms
# Warmup Iteration   3: 10.752 ops/ms
Iteration   1: 10.695 ops/ms
Iteration   2: 10.811 ops/ms
Iteration   3: 10.647 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.717 ±(99.9%) 1.537 ops/ms [Average]
  (min, avg, max) = (10.647, 10.717, 10.811), stdev = 0.084
  CI (99.9%): [9.180, 12.255] (assumes normal distribution)


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
# Warmup Iteration   1: 3.969 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.003 ms/op
Iteration   1: 2.528 ±(99.9%) 0.004 ms/op
Iteration   2: 2.545 ±(99.9%) 0.003 ms/op
Iteration   3: 2.531 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.534 ±(99.9%) 0.165 ms/op [Average]
  (min, avg, max) = (2.528, 2.534, 2.545), stdev = 0.009
  CI (99.9%): [2.369, 2.699] (assumes normal distribution)


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
# Warmup Iteration   1: 3.745 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.443 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.441 ±(99.9%) 0.004 ms/op
Iteration   1: 2.424 ±(99.9%) 0.004 ms/op
Iteration   2: 2.440 ±(99.9%) 0.005 ms/op
Iteration   3: 2.431 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.432 ±(99.9%) 0.139 ms/op [Average]
  (min, avg, max) = (2.424, 2.432, 2.440), stdev = 0.008
  CI (99.9%): [2.293, 2.571] (assumes normal distribution)


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
# Warmup Iteration   1: 3.752 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.515 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.004 ms/op
Iteration   1: 2.473 ±(99.9%) 0.003 ms/op
Iteration   2: 2.472 ±(99.9%) 0.004 ms/op
Iteration   3: 2.472 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.473 ±(99.9%) 0.014 ms/op [Average]
  (min, avg, max) = (2.472, 2.473, 2.473), stdev = 0.001
  CI (99.9%): [2.458, 2.487] (assumes normal distribution)


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
# Warmup Iteration   1: 4.583 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.987 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.005 ms/op
Iteration   1: 3.012 ±(99.9%) 0.005 ms/op
Iteration   2: 2.966 ±(99.9%) 0.006 ms/op
Iteration   3: 2.983 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.987 ±(99.9%) 0.428 ms/op [Average]
  (min, avg, max) = (2.966, 2.987, 3.012), stdev = 0.023
  CI (99.9%): [2.559, 3.415] (assumes normal distribution)


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
# Warmup Iteration   1: 4.357 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.610 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.006 ms/op
Iteration   1: 2.466 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.946 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   2.994 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   3.576 ms/op
                 createUser·p0.999:  6.634 ms/op
                 createUser·p0.9999: 15.909 ms/op
                 createUser·p1.00:   16.695 ms/op

Iteration   2: 2.473 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.853 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   2.994 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   3.666 ms/op
                 createUser·p0.999:  9.540 ms/op
                 createUser·p0.9999: 17.271 ms/op
                 createUser·p1.00:   17.433 ms/op

Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.839 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   4.084 ms/op
                 createUser·p0.999:  7.378 ms/op
                 createUser·p0.9999: 10.308 ms/op
                 createUser·p1.00:   10.994 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 387357
  mean =      2.476 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 187938 
    [ 2.500,  3.750) = 195391 
    [ 3.750,  5.000) = 2891 
    [ 5.000,  6.250) = 616 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 76 
    [ 8.750, 10.000) = 132 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 37 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.768 ms/op
     p(99.9000) =      8.661 ms/op
     p(99.9900) =     16.069 ms/op
     p(99.9990) =     17.371 ms/op
     p(99.9999) =     17.433 ms/op
    p(100.0000) =     17.433 ms/op


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
# Warmup Iteration   1: 3.898 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.433 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.005 ms/op
Iteration   1: 2.419 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.048 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.379 ms/op
                 existUser·p0.999:  5.808 ms/op
                 existUser·p0.9999: 13.071 ms/op
                 existUser·p1.00:   13.763 ms/op

Iteration   2: 2.441 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.502 ms/op
                 existUser·p0.999:  5.546 ms/op
                 existUser·p0.9999: 13.926 ms/op
                 existUser·p1.00:   15.155 ms/op

Iteration   3: 2.446 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.770 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.588 ms/op
                 existUser·p0.999:  6.832 ms/op
                 existUser·p0.9999: 12.384 ms/op
                 existUser·p1.00:   12.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393863
  mean =      2.435 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 196500 
    [ 2.500,  3.750) = 194700 
    [ 3.750,  5.000) = 1953 
    [ 5.000,  6.250) = 267 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 126 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      3.486 ms/op
     p(99.9000) =      6.303 ms/op
     p(99.9900) =     13.127 ms/op
     p(99.9990) =     14.609 ms/op
     p(99.9999) =     15.155 ms/op
    p(100.0000) =     15.155 ms/op


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
# Warmup Iteration   1: 3.983 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.582 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.006 ms/op
Iteration   1: 2.466 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.009 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.531 ms/op
                 getUser·p0.999:  5.945 ms/op
                 getUser·p0.9999: 13.550 ms/op
                 getUser·p1.00:   13.861 ms/op

Iteration   2: 2.478 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.708 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.105 ms/op
                 getUser·p0.99:   3.686 ms/op
                 getUser·p0.999:  7.020 ms/op
                 getUser·p0.9999: 12.650 ms/op
                 getUser·p1.00:   13.337 ms/op

Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.675 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.793 ms/op
                 getUser·p0.999:  7.878 ms/op
                 getUser·p0.9999: 10.906 ms/op
                 getUser·p1.00:   11.469 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386504
  mean =      2.481 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 192400 
    [ 2.500,  3.750) = 190720 
    [ 3.750,  5.000) = 2574 
    [ 5.000,  6.250) = 334 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 127 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.674 ms/op
     p(99.9000) =      7.802 ms/op
     p(99.9900) =     12.971 ms/op
     p(99.9990) =     13.781 ms/op
     p(99.9999) =     13.861 ms/op
    p(100.0000) =     13.861 ms/op


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
# Warmup Iteration   1: 4.685 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.008 ms/op
Iteration   1: 3.016 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.920 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  10.011 ms/op
                 listUser·p0.9999: 11.616 ms/op
                 listUser·p1.00:   11.862 ms/op

Iteration   2: 3.004 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.842 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.634 ms/op
                 listUser·p0.999:  8.922 ms/op
                 listUser·p0.9999: 10.667 ms/op
                 listUser·p1.00:   11.092 ms/op

Iteration   3: 2.985 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.814 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  8.700 ms/op
                 listUser·p0.9999: 10.257 ms/op
                 listUser·p1.00:   11.289 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319536
  mean =      3.002 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 125 
    [ 1.250,  2.500) = 95237 
    [ 2.500,  3.750) = 184651 
    [ 3.750,  5.000) = 31999 
    [ 5.000,  6.250) = 6289 
    [ 6.250,  7.500) = 595 
    [ 7.500,  8.750) = 232 
    [ 8.750, 10.000) = 255 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.814 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.110 ms/op
     p(99.9900) =     11.322 ms/op
     p(99.9990) =     11.777 ms/op
     p(99.9999) =     11.862 ms/op
    p(100.0000) =     11.862 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.690 ± 1.299  ops/ms
ClientPb.existUser                       thrpt       3  13.251 ± 1.567  ops/ms
ClientPb.getUser                         thrpt       3  13.033 ± 1.600  ops/ms
ClientPb.listUser                        thrpt       3  10.717 ± 1.537  ops/ms
ClientPb.createUser                       avgt       3   2.534 ± 0.165   ms/op
ClientPb.existUser                        avgt       3   2.432 ± 0.139   ms/op
ClientPb.getUser                          avgt       3   2.473 ± 0.014   ms/op
ClientPb.listUser                         avgt       3   2.987 ± 0.428   ms/op
ClientPb.createUser                     sample  387357   2.476 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.839           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.002           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.661           ms/op
ClientPb.createUser:createUser·p0.9999  sample          16.069           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.433           ms/op
ClientPb.existUser                      sample  393863   2.435 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.770           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.953           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.486           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.303           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.127           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.155           ms/op
ClientPb.getUser                        sample  386504   2.481 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.675           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.125           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.674           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.802           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.971           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.861           ms/op
ClientPb.listUser                       sample  319536   3.002 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.814           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.110           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.322           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.862           ms/op
