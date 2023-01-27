# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.276 ops/ms
# Warmup Iteration   2: 5.978 ops/ms
# Warmup Iteration   3: 9.302 ops/ms
Iteration   1: 9.753 ops/ms
Iteration   2: 9.885 ops/ms
Iteration   3: 10.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.879 ±(99.9%) 2.261 ops/ms [Average]
  (min, avg, max) = (9.753, 9.879, 10.000), stdev = 0.124
  CI (99.9%): [7.619, 12.140] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.494 ops/ms
# Warmup Iteration   2: 9.032 ops/ms
# Warmup Iteration   3: 10.074 ops/ms
Iteration   1: 10.314 ops/ms
Iteration   2: 10.363 ops/ms
Iteration   3: 10.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.410 ±(99.9%) 2.319 ops/ms [Average]
  (min, avg, max) = (10.314, 10.410, 10.554), stdev = 0.127
  CI (99.9%): [8.091, 12.729] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.563 ops/ms
# Warmup Iteration   2: 9.372 ops/ms
# Warmup Iteration   3: 9.282 ops/ms
Iteration   1: 10.267 ops/ms
Iteration   2: 9.740 ops/ms
Iteration   3: 10.269 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.092 ±(99.9%) 5.559 ops/ms [Average]
  (min, avg, max) = (9.740, 10.092, 10.269), stdev = 0.305
  CI (99.9%): [4.533, 15.652] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.233 ops/ms
# Warmup Iteration   2: 7.914 ops/ms
# Warmup Iteration   3: 8.678 ops/ms
Iteration   1: 8.621 ops/ms
Iteration   2: 8.715 ops/ms
Iteration   3: 8.428 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.588 ±(99.9%) 2.664 ops/ms [Average]
  (min, avg, max) = (8.428, 8.588, 8.715), stdev = 0.146
  CI (99.9%): [5.924, 11.252] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.685 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 3.614 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.429 ±(99.9%) 0.003 ms/op
Iteration   1: 3.251 ±(99.9%) 0.003 ms/op
Iteration   2: 3.135 ±(99.9%) 0.005 ms/op
Iteration   3: 3.285 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.224 ±(99.9%) 1.438 ms/op [Average]
  (min, avg, max) = (3.135, 3.224, 3.285), stdev = 0.079
  CI (99.9%): [1.785, 4.662] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.807 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.340 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.252 ±(99.9%) 0.006 ms/op
Iteration   1: 3.103 ±(99.9%) 0.003 ms/op
Iteration   2: 3.001 ±(99.9%) 0.002 ms/op
Iteration   3: 3.033 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.046 ±(99.9%) 0.945 ms/op [Average]
  (min, avg, max) = (3.001, 3.046, 3.103), stdev = 0.052
  CI (99.9%): [2.101, 3.990] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.939 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.419 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.289 ±(99.9%) 0.008 ms/op
Iteration   1: 3.334 ±(99.9%) 0.003 ms/op
Iteration   2: 3.225 ±(99.9%) 0.005 ms/op
Iteration   3: 3.302 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.287 ±(99.9%) 1.017 ms/op [Average]
  (min, avg, max) = (3.225, 3.287, 3.334), stdev = 0.056
  CI (99.9%): [2.270, 4.304] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.733 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.014 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.850 ±(99.9%) 0.005 ms/op
Iteration   1: 3.725 ±(99.9%) 0.006 ms/op
Iteration   2: 3.766 ±(99.9%) 0.005 ms/op
Iteration   3: 3.688 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.726 ±(99.9%) 0.712 ms/op [Average]
  (min, avg, max) = (3.688, 3.726, 3.766), stdev = 0.039
  CI (99.9%): [3.015, 4.438] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.335 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.640 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.203 ±(99.9%) 0.009 ms/op
Iteration   1: 3.240 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.891 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  10.900 ms/op
                 createUser·p0.9999: 21.271 ms/op
                 createUser·p1.00:   22.282 ms/op

Iteration   2: 3.162 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.075 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  19.622 ms/op
                 createUser·p0.9999: 23.484 ms/op
                 createUser·p1.00:   24.674 ms/op

Iteration   3: 3.330 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.898 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   4.071 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   5.538 ms/op
                 createUser·p0.999:  16.283 ms/op
                 createUser·p0.9999: 21.181 ms/op
                 createUser·p1.00:   24.576 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295899
  mean =      3.242 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13117 
    [ 2.500,  5.000) = 276227 
    [ 5.000,  7.500) = 5778 
    [ 7.500, 10.000) = 363 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 159 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     17.498 ms/op
     p(99.9900) =     23.115 ms/op
     p(99.9990) =     24.042 ms/op
     p(99.9999) =     24.674 ms/op
    p(100.0000) =     24.674 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.260 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.397 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.243 ±(99.9%) 0.009 ms/op
Iteration   1: 3.198 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.462 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  11.058 ms/op
                 existUser·p0.9999: 20.906 ms/op
                 existUser·p1.00:   21.430 ms/op

Iteration   2: 3.085 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.270 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.269 ms/op
                 existUser·p0.99:   5.128 ms/op
                 existUser·p0.999:  9.765 ms/op
                 existUser·p0.9999: 23.036 ms/op
                 existUser·p1.00:   24.216 ms/op

Iteration   3: 3.221 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.118 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   5.382 ms/op
                 existUser·p0.999:  13.856 ms/op
                 existUser·p0.9999: 20.550 ms/op
                 existUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302970
  mean =      3.167 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28991 
    [ 2.500,  5.000) = 269958 
    [ 5.000,  7.500) = 3400 
    [ 7.500, 10.000) = 264 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.462 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      5.218 ms/op
     p(99.9000) =     13.812 ms/op
     p(99.9900) =     22.332 ms/op
     p(99.9990) =     23.593 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.243 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.573 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.383 ±(99.9%) 0.010 ms/op
Iteration   1: 3.140 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.642 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   5.480 ms/op
                 getUser·p0.999:  20.003 ms/op
                 getUser·p0.9999: 21.955 ms/op
                 getUser·p1.00:   22.381 ms/op

Iteration   2: 3.346 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.141 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   5.972 ms/op
                 getUser·p0.999:  19.988 ms/op
                 getUser·p0.9999: 22.887 ms/op
                 getUser·p1.00:   25.494 ms/op

Iteration   3: 3.235 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.399 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   6.078 ms/op
                 getUser·p0.999:  10.032 ms/op
                 getUser·p0.9999: 30.609 ms/op
                 getUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296349
  mean =      3.238 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16882 
    [ 2.500,  5.000) = 271989 
    [ 5.000,  7.500) = 6609 
    [ 7.500, 10.000) = 497 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 180 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      4.116 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     19.268 ms/op
     p(99.9900) =     29.048 ms/op
     p(99.9990) =     31.100 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.194 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.240 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.841 ±(99.9%) 0.012 ms/op
Iteration   1: 3.872 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.868 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  19.562 ms/op
                 listUser·p0.9999: 21.266 ms/op
                 listUser·p1.00:   21.365 ms/op

Iteration   2: 3.771 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.011 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  14.074 ms/op
                 listUser·p0.9999: 17.334 ms/op
                 listUser·p1.00:   17.596 ms/op

Iteration   3: 3.723 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.577 ms/op
                 listUser·p0.50:   3.584 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  13.435 ms/op
                 listUser·p0.9999: 16.433 ms/op
                 listUser·p1.00:   16.630 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253438
  mean =      3.788 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 57 
    [ 2.500,  5.000) = 244940 
    [ 5.000,  7.500) = 6676 
    [ 7.500, 10.000) = 1038 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 286 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.577 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.137 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     13.952 ms/op
     p(99.9900) =     20.939 ms/op
     p(99.9990) =     21.365 ms/op
     p(99.9999) =     21.365 ms/op
    p(100.0000) =     21.365 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.879 ± 2.261  ops/ms
ClientPb.existUser                       thrpt       3  10.410 ± 2.319  ops/ms
ClientPb.getUser                         thrpt       3  10.092 ± 5.559  ops/ms
ClientPb.listUser                        thrpt       3   8.588 ± 2.664  ops/ms
ClientPb.createUser                       avgt       3   3.224 ± 1.438   ms/op
ClientPb.existUser                        avgt       3   3.046 ± 0.945   ms/op
ClientPb.getUser                          avgt       3   3.287 ± 1.017   ms/op
ClientPb.listUser                         avgt       3   3.726 ± 0.712   ms/op
ClientPb.createUser                     sample  295899   3.242 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.891           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.603           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.498           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.115           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.674           ms/op
ClientPb.existUser                      sample  302970   3.167 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.462           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.162           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.428           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.777           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.218           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.812           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.332           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.216           ms/op
ClientPb.getUser                        sample  296349   3.238 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.141           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.658           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.116           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.874           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.268           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.048           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.293           ms/op
ClientPb.listUser                       sample  253438   3.788 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.577           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.645           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.137           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.898           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.952           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.939           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.365           ms/op
