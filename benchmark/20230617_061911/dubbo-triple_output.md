# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.156 ops/ms
# Warmup Iteration   2: 6.101 ops/ms
# Warmup Iteration   3: 8.627 ops/ms
Iteration   1: 9.273 ops/ms
Iteration   2: 9.296 ops/ms
Iteration   3: 9.401 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.323 ±(99.9%) 1.242 ops/ms [Average]
  (min, avg, max) = (9.273, 9.323, 9.401), stdev = 0.068
  CI (99.9%): [8.082, 10.565] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.944 ops/ms
# Warmup Iteration   2: 8.919 ops/ms
# Warmup Iteration   3: 9.773 ops/ms
Iteration   1: 9.767 ops/ms
Iteration   2: 10.164 ops/ms
Iteration   3: 9.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.877 ±(99.9%) 4.574 ops/ms [Average]
  (min, avg, max) = (9.700, 9.877, 10.164), stdev = 0.251
  CI (99.9%): [5.303, 14.451] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.283 ops/ms
# Warmup Iteration   2: 8.315 ops/ms
# Warmup Iteration   3: 8.837 ops/ms
Iteration   1: 9.375 ops/ms
Iteration   2: 8.732 ops/ms
Iteration   3: 9.208 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.105 ±(99.9%) 6.092 ops/ms [Average]
  (min, avg, max) = (8.732, 9.105, 9.375), stdev = 0.334
  CI (99.9%): [3.013, 15.197] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.853 ops/ms
# Warmup Iteration   2: 6.823 ops/ms
# Warmup Iteration   3: 7.653 ops/ms
Iteration   1: 7.945 ops/ms
Iteration   2: 8.014 ops/ms
Iteration   3: 8.173 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.044 ±(99.9%) 2.134 ops/ms [Average]
  (min, avg, max) = (7.945, 8.044, 8.173), stdev = 0.117
  CI (99.9%): [5.910, 10.178] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.120 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.674 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.540 ±(99.9%) 0.009 ms/op
Iteration   1: 3.265 ±(99.9%) 0.009 ms/op
Iteration   2: 3.454 ±(99.9%) 0.006 ms/op
Iteration   3: 3.405 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.375 ±(99.9%) 1.792 ms/op [Average]
  (min, avg, max) = (3.265, 3.375, 3.454), stdev = 0.098
  CI (99.9%): [1.582, 5.167] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.271 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.577 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.466 ±(99.9%) 0.004 ms/op
Iteration   1: 3.354 ±(99.9%) 0.004 ms/op
Iteration   2: 3.357 ±(99.9%) 0.010 ms/op
Iteration   3: 3.425 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.379 ±(99.9%) 0.736 ms/op [Average]
  (min, avg, max) = (3.354, 3.379, 3.425), stdev = 0.040
  CI (99.9%): [2.643, 4.114] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.311 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.672 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.504 ±(99.9%) 0.005 ms/op
Iteration   1: 3.604 ±(99.9%) 0.007 ms/op
Iteration   2: 3.401 ±(99.9%) 0.009 ms/op
Iteration   3: 3.401 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.469 ±(99.9%) 2.137 ms/op [Average]
  (min, avg, max) = (3.401, 3.469, 3.604), stdev = 0.117
  CI (99.9%): [1.332, 5.605] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.486 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.483 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.108 ±(99.9%) 0.008 ms/op
Iteration   1: 3.937 ±(99.9%) 0.015 ms/op
Iteration   2: 3.928 ±(99.9%) 0.011 ms/op
Iteration   3: 4.129 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.998 ±(99.9%) 2.070 ms/op [Average]
  (min, avg, max) = (3.928, 3.998, 4.129), stdev = 0.113
  CI (99.9%): [1.928, 6.069] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.952 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.259 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.645 ±(99.9%) 0.012 ms/op
Iteration   1: 3.419 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.632 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   6.177 ms/op
                 createUser·p0.999:  22.086 ms/op
                 createUser·p0.9999: 26.301 ms/op
                 createUser·p1.00:   27.394 ms/op

Iteration   2: 3.417 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.366 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  23.634 ms/op
                 createUser·p0.9999: 27.937 ms/op
                 createUser·p1.00:   29.229 ms/op

Iteration   3: 3.515 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.567 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   4.071 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  16.090 ms/op
                 createUser·p0.9999: 27.063 ms/op
                 createUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278073
  mean =      3.450 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10418 
    [ 2.500,  5.000) = 261926 
    [ 5.000,  7.500) = 4935 
    [ 7.500, 10.000) = 441 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 124 

  Percentiles, ms/op:
      p(0.0000) =      1.366 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.769 ms/op
     p(99.9000) =     16.169 ms/op
     p(99.9900) =     27.269 ms/op
     p(99.9990) =     29.047 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.711 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.702 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.397 ±(99.9%) 0.008 ms/op
Iteration   1: 3.472 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.217 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   3.953 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   5.857 ms/op
                 existUser·p0.999:  19.920 ms/op
                 existUser·p0.9999: 23.488 ms/op
                 existUser·p1.00:   24.019 ms/op

Iteration   2: 3.319 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.397 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   5.816 ms/op
                 existUser·p0.999:  18.779 ms/op
                 existUser·p0.9999: 25.472 ms/op
                 existUser·p1.00:   27.034 ms/op

Iteration   3: 3.428 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.327 ms/op
                 existUser·p0.50:   3.359 ms/op
                 existUser·p0.90:   3.846 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  18.931 ms/op
                 existUser·p0.9999: 29.153 ms/op
                 existUser·p1.00:   33.227 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281818
  mean =      3.405 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11626 
    [ 2.500,  5.000) = 263511 
    [ 5.000,  7.500) = 5609 
    [ 7.500, 10.000) = 558 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.217 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     19.056 ms/op
     p(99.9900) =     27.743 ms/op
     p(99.9990) =     30.090 ms/op
     p(99.9999) =     33.227 ms/op
    p(100.0000) =     33.227 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.598 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.783 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.586 ±(99.9%) 0.012 ms/op
Iteration   1: 3.500 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.309 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   4.076 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   5.751 ms/op
                 getUser·p0.999:  20.054 ms/op
                 getUser·p0.9999: 31.097 ms/op
                 getUser·p1.00:   31.949 ms/op

Iteration   2: 3.509 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.901 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   4.141 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  11.944 ms/op
                 getUser·p0.9999: 25.388 ms/op
                 getUser·p1.00:   26.608 ms/op

Iteration   3: 3.348 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.608 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   5.620 ms/op
                 getUser·p0.999:  22.969 ms/op
                 getUser·p0.9999: 40.960 ms/op
                 getUser·p1.00:   41.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278019
  mean =      3.451 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 270921 
    [ 5.000, 10.000) = 6534 
    [10.000, 15.000) = 266 
    [15.000, 20.000) = 46 
    [20.000, 25.000) = 116 
    [25.000, 30.000) = 72 
    [30.000, 35.000) = 32 
    [35.000, 40.000) = 8 
    [40.000, 45.000) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.901 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     19.169 ms/op
     p(99.9900) =     39.400 ms/op
     p(99.9990) =     41.091 ms/op
     p(99.9999) =     41.222 ms/op
    p(100.0000) =     41.222 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.307 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.377 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.117 ±(99.9%) 0.014 ms/op
Iteration   1: 3.913 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.565 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  17.879 ms/op
                 listUser·p0.9999: 25.345 ms/op
                 listUser·p1.00:   25.854 ms/op

Iteration   2: 4.039 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.642 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  15.265 ms/op
                 listUser·p0.9999: 19.497 ms/op
                 listUser·p1.00:   19.726 ms/op

Iteration   3: 3.828 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.468 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  15.507 ms/op
                 listUser·p0.9999: 17.990 ms/op
                 listUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 244496
  mean =      3.925 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 237882 
    [ 5.000,  7.500) = 4747 
    [ 7.500, 10.000) = 1171 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 195 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.468 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      7.078 ms/op
     p(99.9000) =     16.073 ms/op
     p(99.9900) =     23.254 ms/op
     p(99.9990) =     25.661 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.323 ± 1.242  ops/ms
ClientPb.existUser                       thrpt       3   9.877 ± 4.574  ops/ms
ClientPb.getUser                         thrpt       3   9.105 ± 6.092  ops/ms
ClientPb.listUser                        thrpt       3   8.044 ± 2.134  ops/ms
ClientPb.createUser                       avgt       3   3.375 ± 1.792   ms/op
ClientPb.existUser                        avgt       3   3.379 ± 0.736   ms/op
ClientPb.getUser                          avgt       3   3.469 ± 2.137   ms/op
ClientPb.listUser                         avgt       3   3.998 ± 2.070   ms/op
ClientPb.createUser                     sample  278073   3.450 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.366           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.379           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.895           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.252           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.769           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.169           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.269           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.229           ms/op
ClientPb.existUser                      sample  281818   3.405 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.217           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.326           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.801           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.211           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.825           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.056           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.743           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.227           ms/op
ClientPb.getUser                        sample  278019   3.451 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.901           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.346           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.985           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.301           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.784           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.169           ms/op
ClientPb.getUser:getUser·p0.9999        sample          39.400           ms/op
ClientPb.getUser:getUser·p1.00          sample          41.222           ms/op
ClientPb.listUser                       sample  244496   3.925 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.468           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.793           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.235           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.078           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.073           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.254           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.854           ms/op
