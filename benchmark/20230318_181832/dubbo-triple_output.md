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
# Warmup Iteration   1: 1.847 ops/ms
# Warmup Iteration   2: 4.927 ops/ms
# Warmup Iteration   3: 8.603 ops/ms
Iteration   1: 8.890 ops/ms
Iteration   2: 9.182 ops/ms
Iteration   3: 9.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.071 ±(99.9%) 2.884 ops/ms [Average]
  (min, avg, max) = (8.890, 9.071, 9.182), stdev = 0.158
  CI (99.9%): [6.187, 11.955] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.896 ops/ms
# Warmup Iteration   2: 8.557 ops/ms
# Warmup Iteration   3: 9.164 ops/ms
Iteration   1: 9.836 ops/ms
Iteration   2: 9.564 ops/ms
Iteration   3: 9.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.605 ±(99.9%) 3.913 ops/ms [Average]
  (min, avg, max) = (9.413, 9.605, 9.836), stdev = 0.214
  CI (99.9%): [5.692, 13.517] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.625 ops/ms
# Warmup Iteration   2: 7.271 ops/ms
# Warmup Iteration   3: 8.653 ops/ms
Iteration   1: 9.142 ops/ms
Iteration   2: 9.196 ops/ms
Iteration   3: 9.008 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.115 ±(99.9%) 1.768 ops/ms [Average]
  (min, avg, max) = (9.008, 9.115, 9.196), stdev = 0.097
  CI (99.9%): [7.347, 10.884] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.107 ops/ms
# Warmup Iteration   2: 6.954 ops/ms
# Warmup Iteration   3: 7.588 ops/ms
Iteration   1: 7.907 ops/ms
Iteration   2: 8.122 ops/ms
Iteration   3: 7.891 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.973 ±(99.9%) 2.351 ops/ms [Average]
  (min, avg, max) = (7.891, 7.973, 8.122), stdev = 0.129
  CI (99.9%): [5.622, 10.324] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 12.014 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.057 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.744 ±(99.9%) 0.008 ms/op
Iteration   1: 3.542 ±(99.9%) 0.007 ms/op
Iteration   2: 3.534 ±(99.9%) 0.005 ms/op
Iteration   3: 3.655 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.577 ±(99.9%) 1.231 ms/op [Average]
  (min, avg, max) = (3.534, 3.577, 3.655), stdev = 0.067
  CI (99.9%): [2.346, 4.808] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.643 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.822 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.394 ±(99.9%) 0.005 ms/op
Iteration   1: 3.283 ±(99.9%) 0.006 ms/op
Iteration   2: 3.364 ±(99.9%) 0.010 ms/op
Iteration   3: 3.347 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.331 ±(99.9%) 0.778 ms/op [Average]
  (min, avg, max) = (3.283, 3.331, 3.364), stdev = 0.043
  CI (99.9%): [2.553, 4.110] (assumes normal distribution)


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
# Warmup Iteration   1: 9.066 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.088 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.697 ±(99.9%) 0.004 ms/op
Iteration   1: 3.550 ±(99.9%) 0.007 ms/op
Iteration   2: 3.385 ±(99.9%) 0.007 ms/op
Iteration   3: 3.425 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.453 ±(99.9%) 1.568 ms/op [Average]
  (min, avg, max) = (3.385, 3.453, 3.550), stdev = 0.086
  CI (99.9%): [1.886, 5.021] (assumes normal distribution)


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
# Warmup Iteration   1: 12.538 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.177 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.183 ±(99.9%) 0.015 ms/op
Iteration   1: 4.266 ±(99.9%) 0.008 ms/op
Iteration   2: 4.019 ±(99.9%) 0.009 ms/op
Iteration   3: 3.989 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.092 ±(99.9%) 2.767 ms/op [Average]
  (min, avg, max) = (3.989, 4.092, 4.266), stdev = 0.152
  CI (99.9%): [1.325, 6.858] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.481 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.197 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.900 ±(99.9%) 0.015 ms/op
Iteration   1: 3.495 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.673 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   6.169 ms/op
                 createUser·p0.999:  21.070 ms/op
                 createUser·p0.9999: 24.374 ms/op
                 createUser·p1.00:   25.264 ms/op

Iteration   2: 3.514 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.350 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   4.063 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  23.245 ms/op
                 createUser·p0.9999: 27.683 ms/op
                 createUser·p1.00:   29.065 ms/op

Iteration   3: 3.641 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.460 ms/op
                 createUser·p0.50:   3.588 ms/op
                 createUser·p0.90:   4.129 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  21.178 ms/op
                 createUser·p0.9999: 29.327 ms/op
                 createUser·p1.00:   30.966 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270103
  mean =      3.549 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3208 
    [ 2.500,  5.000) = 260695 
    [ 5.000,  7.500) = 5282 
    [ 7.500, 10.000) = 458 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.460 ms/op
     p(50.0000) =      3.478 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     21.197 ms/op
     p(99.9900) =     28.639 ms/op
     p(99.9990) =     29.625 ms/op
     p(99.9999) =     30.966 ms/op
    p(100.0000) =     30.966 ms/op


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
# Warmup Iteration   1: 9.851 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 3.558 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.416 ±(99.9%) 0.009 ms/op
Iteration   1: 3.520 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.715 ms/op
                 existUser·p0.50:   3.375 ms/op
                 existUser·p0.90:   4.080 ms/op
                 existUser·p0.95:   4.432 ms/op
                 existUser·p0.99:   6.373 ms/op
                 existUser·p0.999:  22.184 ms/op
                 existUser·p0.9999: 25.523 ms/op
                 existUser·p1.00:   26.083 ms/op

Iteration   2: 3.448 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.386 ms/op
                 existUser·p0.50:   3.396 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   4.157 ms/op
                 existUser·p0.99:   6.865 ms/op
                 existUser·p0.999:  24.094 ms/op
                 existUser·p0.9999: 26.786 ms/op
                 existUser·p1.00:   27.099 ms/op

Iteration   3: 3.481 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.464 ms/op
                 existUser·p0.50:   3.391 ms/op
                 existUser·p0.90:   4.002 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   5.964 ms/op
                 existUser·p0.999:  9.781 ms/op
                 existUser·p0.9999: 28.606 ms/op
                 existUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 275566
  mean =      3.483 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13732 
    [ 2.500,  5.000) = 254695 
    [ 5.000,  7.500) = 5952 
    [ 7.500, 10.000) = 879 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 135 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      6.341 ms/op
     p(99.9000) =     10.680 ms/op
     p(99.9900) =     27.474 ms/op
     p(99.9990) =     31.055 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


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
# Warmup Iteration   1: 9.773 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.987 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.646 ±(99.9%) 0.012 ms/op
Iteration   1: 3.551 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.114 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   3.998 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   6.093 ms/op
                 getUser·p0.999:  22.543 ms/op
                 getUser·p0.9999: 27.099 ms/op
                 getUser·p1.00:   28.475 ms/op

Iteration   2: 3.503 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.890 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   4.170 ms/op
                 getUser·p0.99:   7.422 ms/op
                 getUser·p0.999:  24.248 ms/op
                 getUser·p0.9999: 39.903 ms/op
                 getUser·p1.00:   41.615 ms/op

Iteration   3: 3.550 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.839 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   4.035 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   6.201 ms/op
                 getUser·p0.999:  14.336 ms/op
                 getUser·p0.9999: 34.205 ms/op
                 getUser·p1.00:   35.586 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271544
  mean =      3.535 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 263499 
    [ 5.000, 10.000) = 7548 
    [10.000, 15.000) = 209 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 96 
    [25.000, 30.000) = 96 
    [30.000, 35.000) = 26 
    [35.000, 40.000) = 30 
    [40.000, 45.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     17.302 ms/op
     p(99.9900) =     38.056 ms/op
     p(99.9990) =     41.334 ms/op
     p(99.9999) =     41.615 ms/op
    p(100.0000) =     41.615 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.590 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.596 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.250 ±(99.9%) 0.015 ms/op
Iteration   1: 4.045 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.425 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  20.705 ms/op
                 listUser·p0.9999: 25.133 ms/op
                 listUser·p1.00:   25.788 ms/op

Iteration   2: 4.041 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.503 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  18.121 ms/op
                 listUser·p0.9999: 23.822 ms/op
                 listUser·p1.00:   23.888 ms/op

Iteration   3: 4.130 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.531 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.226 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  16.295 ms/op
                 listUser·p0.9999: 18.907 ms/op
                 listUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235694
  mean =      4.072 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 224024 
    [ 5.000,  7.500) = 9513 
    [ 7.500, 10.000) = 1409 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 201 
    [17.500, 20.000) = 126 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.425 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      7.315 ms/op
     p(99.9000) =     18.065 ms/op
     p(99.9900) =     23.855 ms/op
     p(99.9990) =     25.220 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.071 ± 2.884  ops/ms
ClientPb.existUser                       thrpt       3   9.605 ± 3.913  ops/ms
ClientPb.getUser                         thrpt       3   9.115 ± 1.768  ops/ms
ClientPb.listUser                        thrpt       3   7.973 ± 2.351  ops/ms
ClientPb.createUser                       avgt       3   3.577 ± 1.231   ms/op
ClientPb.existUser                        avgt       3   3.331 ± 0.778   ms/op
ClientPb.getUser                          avgt       3   3.453 ± 1.568   ms/op
ClientPb.listUser                         avgt       3   4.092 ± 2.767   ms/op
ClientPb.createUser                     sample  270103   3.549 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.460           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.478           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.051           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.366           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.939           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.197           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.639           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.966           ms/op
ClientPb.existUser                      sample  275566   3.483 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.715           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.391           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.973           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.342           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.341           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.680           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.474           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.392           ms/op
ClientPb.getUser                        sample  271544   3.535 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.839           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.383           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.949           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.301           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.094           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.302           ms/op
ClientPb.getUser:getUser·p0.9999        sample          38.056           ms/op
ClientPb.getUser:getUser·p1.00          sample          41.615           ms/op
ClientPb.listUser                       sample  235694   4.072 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.425           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.997           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.315           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.065           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.855           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.788           ms/op
