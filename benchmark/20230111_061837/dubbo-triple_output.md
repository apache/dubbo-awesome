# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.549 ops/ms
# Warmup Iteration   2: 6.094 ops/ms
# Warmup Iteration   3: 9.084 ops/ms
Iteration   1: 9.996 ops/ms
Iteration   2: 9.892 ops/ms
Iteration   3: 10.065 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.984 ±(99.9%) 1.590 ops/ms [Average]
  (min, avg, max) = (9.892, 9.984, 10.065), stdev = 0.087
  CI (99.9%): [8.394, 11.574] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.555 ops/ms
# Warmup Iteration   2: 9.514 ops/ms
# Warmup Iteration   3: 10.138 ops/ms
Iteration   1: 10.424 ops/ms
Iteration   2: 10.698 ops/ms
Iteration   3: 10.390 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.504 ±(99.9%) 3.078 ops/ms [Average]
  (min, avg, max) = (10.390, 10.504, 10.698), stdev = 0.169
  CI (99.9%): [7.426, 13.582] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.683 ops/ms
# Warmup Iteration   2: 8.834 ops/ms
# Warmup Iteration   3: 9.980 ops/ms
Iteration   1: 9.833 ops/ms
Iteration   2: 10.084 ops/ms
Iteration   3: 9.901 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.939 ±(99.9%) 2.373 ops/ms [Average]
  (min, avg, max) = (9.833, 9.939, 10.084), stdev = 0.130
  CI (99.9%): [7.566, 12.313] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.255 ops/ms
# Warmup Iteration   2: 7.836 ops/ms
# Warmup Iteration   3: 8.149 ops/ms
Iteration   1: 8.306 ops/ms
Iteration   2: 8.613 ops/ms
Iteration   3: 8.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.542 ±(99.9%) 3.826 ops/ms [Average]
  (min, avg, max) = (8.306, 8.542, 8.707), stdev = 0.210
  CI (99.9%): [4.716, 12.368] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.297 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.423 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.182 ±(99.9%) 0.006 ms/op
Iteration   1: 3.117 ±(99.9%) 0.002 ms/op
Iteration   2: 3.214 ±(99.9%) 0.005 ms/op
Iteration   3: 3.302 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.211 ±(99.9%) 1.685 ms/op [Average]
  (min, avg, max) = (3.117, 3.211, 3.302), stdev = 0.092
  CI (99.9%): [1.526, 4.896] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.960 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.329 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.123 ±(99.9%) 0.005 ms/op
Iteration   1: 3.096 ±(99.9%) 0.005 ms/op
Iteration   2: 2.978 ±(99.9%) 0.004 ms/op
Iteration   3: 3.072 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.049 ±(99.9%) 1.137 ms/op [Average]
  (min, avg, max) = (2.978, 3.049, 3.096), stdev = 0.062
  CI (99.9%): [1.912, 4.186] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.199 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.388 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.260 ±(99.9%) 0.004 ms/op
Iteration   1: 3.224 ±(99.9%) 0.008 ms/op
Iteration   2: 3.171 ±(99.9%) 0.004 ms/op
Iteration   3: 3.232 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.209 ±(99.9%) 0.612 ms/op [Average]
  (min, avg, max) = (3.171, 3.209, 3.232), stdev = 0.034
  CI (99.9%): [2.597, 3.821] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.744 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.184 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.817 ±(99.9%) 0.007 ms/op
Iteration   1: 3.780 ±(99.9%) 0.009 ms/op
Iteration   2: 3.680 ±(99.9%) 0.012 ms/op
Iteration   3: 3.767 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.742 ±(99.9%) 0.996 ms/op [Average]
  (min, avg, max) = (3.680, 3.742, 3.780), stdev = 0.055
  CI (99.9%): [2.746, 4.738] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.550 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.654 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.315 ±(99.9%) 0.009 ms/op
Iteration   1: 3.178 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.852 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   5.516 ms/op
                 createUser·p0.999:  11.993 ms/op
                 createUser·p0.9999: 21.234 ms/op
                 createUser·p1.00:   22.184 ms/op

Iteration   2: 3.155 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.227 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  11.511 ms/op
                 createUser·p0.9999: 23.195 ms/op
                 createUser·p1.00:   24.478 ms/op

Iteration   3: 3.131 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.561 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.637 ms/op
                 createUser·p0.999:  14.840 ms/op
                 createUser·p0.9999: 20.447 ms/op
                 createUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 304184
  mean =      3.155 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13368 
    [ 2.500,  5.000) = 285813 
    [ 5.000,  7.500) = 4132 
    [ 7.500, 10.000) = 404 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 134 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.852 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     14.677 ms/op
     p(99.9900) =     22.170 ms/op
     p(99.9990) =     23.557 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.281 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.366 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.007 ms/op
Iteration   1: 3.081 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.241 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  10.691 ms/op
                 existUser·p0.9999: 22.217 ms/op
                 existUser·p1.00:   23.790 ms/op

Iteration   2: 3.222 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.982 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.740 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   5.489 ms/op
                 existUser·p0.999:  15.528 ms/op
                 existUser·p0.9999: 21.398 ms/op
                 existUser·p1.00:   22.544 ms/op

Iteration   3: 3.113 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.626 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  12.861 ms/op
                 existUser·p0.9999: 22.536 ms/op
                 existUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305770
  mean =      3.138 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21125 
    [ 2.500,  5.000) = 279285 
    [ 5.000,  7.500) = 4614 
    [ 7.500, 10.000) = 331 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 141 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.982 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =     15.483 ms/op
     p(99.9900) =     22.086 ms/op
     p(99.9990) =     23.558 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.489 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.255 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.302 ±(99.9%) 0.010 ms/op
Iteration   1: 3.181 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.503 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  17.234 ms/op
                 getUser·p0.9999: 21.875 ms/op
                 getUser·p1.00:   22.577 ms/op

Iteration   2: 3.312 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   5.939 ms/op
                 getUser·p0.999:  14.832 ms/op
                 getUser·p0.9999: 23.071 ms/op
                 getUser·p1.00:   24.052 ms/op

Iteration   3: 3.212 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.386 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   5.161 ms/op
                 getUser·p0.999:  10.233 ms/op
                 getUser·p0.9999: 21.596 ms/op
                 getUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296498
  mean =      3.234 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18484 
    [ 2.500,  5.000) = 271369 
    [ 5.000,  7.500) = 5834 
    [ 7.500, 10.000) = 363 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 167 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     17.121 ms/op
     p(99.9900) =     22.097 ms/op
     p(99.9990) =     23.987 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.642 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.223 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.874 ±(99.9%) 0.013 ms/op
Iteration   1: 3.840 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.755 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  17.203 ms/op
                 listUser·p0.9999: 19.694 ms/op
                 listUser·p1.00:   20.644 ms/op

Iteration   2: 3.790 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   7.584 ms/op
                 listUser·p0.999:  13.418 ms/op
                 listUser·p0.9999: 19.038 ms/op
                 listUser·p1.00:   19.104 ms/op

Iteration   3: 3.848 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.366 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.527 ms/op
                 listUser·p0.99:   7.470 ms/op
                 listUser·p0.999:  13.238 ms/op
                 listUser·p0.9999: 21.103 ms/op
                 listUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250711
  mean =      3.826 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 135 
    [ 2.500,  5.000) = 241152 
    [ 5.000,  7.500) = 7084 
    [ 7.500, 10.000) = 1733 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 241 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.366 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      7.381 ms/op
     p(99.9000) =     14.139 ms/op
     p(99.9900) =     20.152 ms/op
     p(99.9990) =     21.135 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.984 ± 1.590  ops/ms
ClientPb.existUser                       thrpt       3  10.504 ± 3.078  ops/ms
ClientPb.getUser                         thrpt       3   9.939 ± 2.373  ops/ms
ClientPb.listUser                        thrpt       3   8.542 ± 3.826  ops/ms
ClientPb.createUser                       avgt       3   3.211 ± 1.685   ms/op
ClientPb.existUser                        avgt       3   3.049 ± 1.137   ms/op
ClientPb.getUser                          avgt       3   3.209 ± 0.612   ms/op
ClientPb.listUser                         avgt       3   3.742 ± 0.996   ms/op
ClientPb.createUser                     sample  304184   3.155 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.852           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.514           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.772           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.439           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.677           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.170           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.478           ms/op
ClientPb.existUser                      sample  305770   3.138 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.982           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.453           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.944           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.358           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.483           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.086           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.790           ms/op
ClientPb.getUser                        sample  296498   3.234 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.055           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.670           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.669           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.121           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.097           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.052           ms/op
ClientPb.listUser                       sample  250711   3.826 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.366           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.686           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.194           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.381           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.139           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.152           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.135           ms/op
