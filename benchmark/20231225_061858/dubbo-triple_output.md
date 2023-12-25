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
# Warmup Iteration   1: 4.763 ops/ms
# Warmup Iteration   2: 12.417 ops/ms
# Warmup Iteration   3: 12.589 ops/ms
Iteration   1: 12.828 ops/ms
Iteration   2: 12.849 ops/ms
Iteration   3: 12.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.841 ±(99.9%) 0.211 ops/ms [Average]
  (min, avg, max) = (12.828, 12.841, 12.849), stdev = 0.012
  CI (99.9%): [12.630, 13.052] (assumes normal distribution)


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
# Warmup Iteration   1: 8.348 ops/ms
# Warmup Iteration   2: 13.266 ops/ms
# Warmup Iteration   3: 13.409 ops/ms
Iteration   1: 13.338 ops/ms
Iteration   2: 13.350 ops/ms
Iteration   3: 13.384 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.357 ±(99.9%) 0.438 ops/ms [Average]
  (min, avg, max) = (13.338, 13.357, 13.384), stdev = 0.024
  CI (99.9%): [12.919, 13.795] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.932 ops/ms
# Warmup Iteration   2: 12.767 ops/ms
# Warmup Iteration   3: 13.113 ops/ms
Iteration   1: 13.186 ops/ms
Iteration   2: 12.976 ops/ms
Iteration   3: 13.175 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.112 ±(99.9%) 2.159 ops/ms [Average]
  (min, avg, max) = (12.976, 13.112, 13.186), stdev = 0.118
  CI (99.9%): [10.954, 15.271] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.723 ops/ms
# Warmup Iteration   2: 10.568 ops/ms
# Warmup Iteration   3: 10.701 ops/ms
Iteration   1: 10.742 ops/ms
Iteration   2: 10.881 ops/ms
Iteration   3: 10.776 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.799 ±(99.9%) 1.327 ops/ms [Average]
  (min, avg, max) = (10.742, 10.799, 10.881), stdev = 0.073
  CI (99.9%): [9.472, 12.126] (assumes normal distribution)


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
# Warmup Iteration   1: 3.884 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.518 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.004 ms/op
Iteration   1: 2.475 ±(99.9%) 0.004 ms/op
Iteration   2: 2.509 ±(99.9%) 0.004 ms/op
Iteration   3: 2.472 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.485 ±(99.9%) 0.374 ms/op [Average]
  (min, avg, max) = (2.472, 2.485, 2.509), stdev = 0.020
  CI (99.9%): [2.112, 2.859] (assumes normal distribution)


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
# Warmup Iteration   1: 3.548 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.389 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.397 ±(99.9%) 0.004 ms/op
Iteration   1: 2.392 ±(99.9%) 0.004 ms/op
Iteration   2: 2.394 ±(99.9%) 0.004 ms/op
Iteration   3: 2.411 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.399 ±(99.9%) 0.185 ms/op [Average]
  (min, avg, max) = (2.392, 2.399, 2.411), stdev = 0.010
  CI (99.9%): [2.214, 2.584] (assumes normal distribution)


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
# Warmup Iteration   1: 4.063 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.500 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.004 ms/op
Iteration   1: 2.467 ±(99.9%) 0.004 ms/op
Iteration   2: 2.492 ±(99.9%) 0.004 ms/op
Iteration   3: 2.474 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.478 ±(99.9%) 0.243 ms/op [Average]
  (min, avg, max) = (2.467, 2.478, 2.492), stdev = 0.013
  CI (99.9%): [2.235, 2.720] (assumes normal distribution)


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
# Warmup Iteration   1: 4.722 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.981 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.941 ±(99.9%) 0.005 ms/op
Iteration   1: 2.951 ±(99.9%) 0.006 ms/op
Iteration   2: 2.962 ±(99.9%) 0.006 ms/op
Iteration   3: 2.964 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.959 ±(99.9%) 0.126 ms/op [Average]
  (min, avg, max) = (2.951, 2.959, 2.964), stdev = 0.007
  CI (99.9%): [2.833, 3.085] (assumes normal distribution)


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
# Warmup Iteration   1: 4.025 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.614 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.005 ms/op
Iteration   1: 2.508 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.868 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.879 ms/op
                 createUser·p0.999:  11.209 ms/op
                 createUser·p0.9999: 13.029 ms/op
                 createUser·p1.00:   14.336 ms/op

Iteration   2: 2.504 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.850 ms/op
                 createUser·p0.999:  10.349 ms/op
                 createUser·p0.9999: 12.485 ms/op
                 createUser·p1.00:   13.615 ms/op

Iteration   3: 2.511 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.016 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.861 ms/op
                 createUser·p0.999:  7.921 ms/op
                 createUser·p0.9999: 10.986 ms/op
                 createUser·p1.00:   12.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382520
  mean =      2.508 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 186127 
    [ 2.500,  3.750) = 191762 
    [ 3.750,  5.000) = 3656 
    [ 5.000,  6.250) = 456 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 143 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.863 ms/op
     p(99.9000) =      8.946 ms/op
     p(99.9900) =     12.763 ms/op
     p(99.9990) =     13.348 ms/op
     p(99.9999) =     14.336 ms/op
    p(100.0000) =     14.336 ms/op


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
# Warmup Iteration   1: 3.664 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.489 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.450 ±(99.9%) 0.005 ms/op
Iteration   1: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.010 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.637 ms/op
                 existUser·p0.999:  5.473 ms/op
                 existUser·p0.9999: 14.483 ms/op
                 existUser·p1.00:   15.466 ms/op

Iteration   2: 2.427 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.781 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.666 ms/op
                 existUser·p0.999:  7.093 ms/op
                 existUser·p0.9999: 13.317 ms/op
                 existUser·p1.00:   14.238 ms/op

Iteration   3: 2.440 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.816 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.572 ms/op
                 existUser·p0.999:  8.282 ms/op
                 existUser·p0.9999: 12.010 ms/op
                 existUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393104
  mean =      2.439 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 75 
    [ 1.250,  2.500) = 196933 
    [ 2.500,  3.750) = 192827 
    [ 3.750,  5.000) = 2589 
    [ 5.000,  6.250) = 305 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      3.625 ms/op
     p(99.9000) =      5.947 ms/op
     p(99.9900) =     13.533 ms/op
     p(99.9990) =     14.894 ms/op
     p(99.9999) =     15.466 ms/op
    p(100.0000) =     15.466 ms/op


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
# Warmup Iteration   1: 3.901 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.569 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.006 ms/op
Iteration   1: 2.443 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.770 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.974 ms/op
                 getUser·p0.95:   3.084 ms/op
                 getUser·p0.99:   3.555 ms/op
                 getUser·p0.999:  5.868 ms/op
                 getUser·p0.9999: 13.926 ms/op
                 getUser·p1.00:   15.991 ms/op

Iteration   2: 2.492 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.944 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   4.251 ms/op
                 getUser·p0.999:  8.573 ms/op
                 getUser·p0.9999: 12.239 ms/op
                 getUser·p1.00:   12.960 ms/op

Iteration   3: 2.465 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.841 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.101 ms/op
                 getUser·p0.99:   3.727 ms/op
                 getUser·p0.999:  7.913 ms/op
                 getUser·p0.9999: 12.715 ms/op
                 getUser·p1.00:   13.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388917
  mean =      2.466 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 81 
    [ 1.250,  2.500) = 195402 
    [ 2.500,  3.750) = 188969 
    [ 3.750,  5.000) = 3652 
    [ 5.000,  6.250) = 392 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 120 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.841 ms/op
     p(99.9000) =      7.624 ms/op
     p(99.9900) =     13.468 ms/op
     p(99.9990) =     14.398 ms/op
     p(99.9999) =     15.991 ms/op
    p(100.0000) =     15.991 ms/op


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
# Warmup Iteration   1: 4.560 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.006 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.955 ±(99.9%) 0.008 ms/op
Iteration   1: 2.937 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.926 ms/op
                 listUser·p0.50:   2.875 ms/op
                 listUser·p0.90:   3.801 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  9.131 ms/op
                 listUser·p0.9999: 11.456 ms/op
                 listUser·p1.00:   11.977 ms/op

Iteration   2: 2.928 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.949 ms/op
                 listUser·p0.50:   2.863 ms/op
                 listUser·p0.90:   3.772 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   5.358 ms/op
                 listUser·p0.999:  9.246 ms/op
                 listUser·p0.9999: 10.897 ms/op
                 listUser·p1.00:   12.272 ms/op

Iteration   3: 2.918 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.846 ms/op
                 listUser·p0.50:   2.859 ms/op
                 listUser·p0.90:   3.756 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.411 ms/op
                 listUser·p0.9999: 10.635 ms/op
                 listUser·p1.00:   11.387 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 327612
  mean =      2.927 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 152 
    [ 1.250,  2.500) = 107373 
    [ 2.500,  3.750) = 185952 
    [ 3.750,  5.000) = 27845 
    [ 5.000,  6.250) = 5196 
    [ 6.250,  7.500) = 390 
    [ 7.500,  8.750) = 264 
    [ 8.750, 10.000) = 281 
    [10.000, 11.250) = 142 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      5.430 ms/op
     p(99.9000) =      9.290 ms/op
     p(99.9900) =     10.977 ms/op
     p(99.9990) =     11.905 ms/op
     p(99.9999) =     12.272 ms/op
    p(100.0000) =     12.272 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.841 ± 0.211  ops/ms
ClientPb.existUser                       thrpt       3  13.357 ± 0.438  ops/ms
ClientPb.getUser                         thrpt       3  13.112 ± 2.159  ops/ms
ClientPb.listUser                        thrpt       3  10.799 ± 1.327  ops/ms
ClientPb.createUser                       avgt       3   2.485 ± 0.374   ms/op
ClientPb.existUser                        avgt       3   2.399 ± 0.185   ms/op
ClientPb.getUser                          avgt       3   2.478 ± 0.243   ms/op
ClientPb.listUser                         avgt       3   2.959 ± 0.126   ms/op
ClientPb.createUser                     sample  382520   2.508 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.868           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.043           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.863           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.946           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.763           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.336           ms/op
ClientPb.existUser                      sample  393104   2.439 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.781           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.494           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.947           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.533           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.466           ms/op
ClientPb.getUser                        sample  388917   2.466 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.770           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.490           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.002           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.125           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.841           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.624           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.468           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.991           ms/op
ClientPb.listUser                       sample  327612   2.927 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.846           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.867           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.777           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.268           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.430           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.290           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.977           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.272           ms/op
