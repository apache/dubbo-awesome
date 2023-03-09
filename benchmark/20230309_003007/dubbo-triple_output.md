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
# Warmup Iteration   1: 2.169 ops/ms
# Warmup Iteration   2: 5.460 ops/ms
# Warmup Iteration   3: 8.471 ops/ms
Iteration   1: 8.841 ops/ms
Iteration   2: 9.351 ops/ms
Iteration   3: 9.425 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.206 ±(99.9%) 5.803 ops/ms [Average]
  (min, avg, max) = (8.841, 9.206, 9.425), stdev = 0.318
  CI (99.9%): [3.403, 15.008] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.079 ops/ms
# Warmup Iteration   2: 8.837 ops/ms
# Warmup Iteration   3: 9.507 ops/ms
Iteration   1: 9.669 ops/ms
Iteration   2: 10.010 ops/ms
Iteration   3: 9.470 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.716 ±(99.9%) 4.978 ops/ms [Average]
  (min, avg, max) = (9.470, 9.716, 10.010), stdev = 0.273
  CI (99.9%): [4.739, 14.694] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.739 ops/ms
# Warmup Iteration   2: 8.339 ops/ms
# Warmup Iteration   3: 8.942 ops/ms
Iteration   1: 9.193 ops/ms
Iteration   2: 9.397 ops/ms
Iteration   3: 9.630 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.407 ±(99.9%) 3.993 ops/ms [Average]
  (min, avg, max) = (9.193, 9.407, 9.630), stdev = 0.219
  CI (99.9%): [5.414, 13.399] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.621 ops/ms
# Warmup Iteration   2: 6.941 ops/ms
# Warmup Iteration   3: 7.606 ops/ms
Iteration   1: 7.833 ops/ms
Iteration   2: 7.860 ops/ms
Iteration   3: 8.028 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.907 ±(99.9%) 1.928 ops/ms [Average]
  (min, avg, max) = (7.833, 7.907, 8.028), stdev = 0.106
  CI (99.9%): [5.979, 9.835] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.484 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 3.744 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.664 ±(99.9%) 0.006 ms/op
Iteration   1: 3.519 ±(99.9%) 0.008 ms/op
Iteration   2: 3.480 ±(99.9%) 0.010 ms/op
Iteration   3: 3.320 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.439 ±(99.9%) 1.924 ms/op [Average]
  (min, avg, max) = (3.320, 3.439, 3.519), stdev = 0.105
  CI (99.9%): [1.515, 5.364] (assumes normal distribution)


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
# Warmup Iteration   1: 8.672 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.611 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.250 ±(99.9%) 0.008 ms/op
Iteration   1: 3.330 ±(99.9%) 0.007 ms/op
Iteration   2: 3.296 ±(99.9%) 0.002 ms/op
Iteration   3: 3.210 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.279 ±(99.9%) 1.132 ms/op [Average]
  (min, avg, max) = (3.210, 3.279, 3.330), stdev = 0.062
  CI (99.9%): [2.147, 4.411] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.206 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.739 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.570 ±(99.9%) 0.004 ms/op
Iteration   1: 3.537 ±(99.9%) 0.004 ms/op
Iteration   2: 3.480 ±(99.9%) 0.005 ms/op
Iteration   3: 3.385 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.467 ±(99.9%) 1.408 ms/op [Average]
  (min, avg, max) = (3.385, 3.467, 3.537), stdev = 0.077
  CI (99.9%): [2.060, 4.875] (assumes normal distribution)


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
# Warmup Iteration   1: 10.275 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.474 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.058 ±(99.9%) 0.012 ms/op
Iteration   1: 3.966 ±(99.9%) 0.011 ms/op
Iteration   2: 3.896 ±(99.9%) 0.012 ms/op
Iteration   3: 4.028 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.963 ±(99.9%) 1.200 ms/op [Average]
  (min, avg, max) = (3.896, 3.963, 4.028), stdev = 0.066
  CI (99.9%): [2.763, 5.163] (assumes normal distribution)


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
# Warmup Iteration   1: 8.807 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.853 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.453 ±(99.9%) 0.010 ms/op
Iteration   1: 3.325 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.769 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  19.012 ms/op
                 createUser·p0.9999: 23.638 ms/op
                 createUser·p1.00:   24.642 ms/op

Iteration   2: 3.391 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.029 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  22.895 ms/op
                 createUser·p0.9999: 25.362 ms/op
                 createUser·p1.00:   25.854 ms/op

Iteration   3: 3.545 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.456 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   4.125 ms/op
                 createUser·p0.95:   4.964 ms/op
                 createUser·p0.99:   6.352 ms/op
                 createUser·p0.999:  17.001 ms/op
                 createUser·p0.9999: 24.575 ms/op
                 createUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280706
  mean =      3.418 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11054 
    [ 2.500,  5.000) = 262604 
    [ 5.000,  7.500) = 6170 
    [ 7.500, 10.000) = 399 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 181 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.029 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     17.049 ms/op
     p(99.9900) =     24.869 ms/op
     p(99.9990) =     25.722 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


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
# Warmup Iteration   1: 8.699 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.740 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.429 ±(99.9%) 0.011 ms/op
Iteration   1: 3.327 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.311 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   4.104 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  20.775 ms/op
                 existUser·p0.9999: 24.445 ms/op
                 existUser·p1.00:   25.100 ms/op

Iteration   2: 3.315 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.210 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   4.084 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  20.063 ms/op
                 existUser·p0.9999: 27.082 ms/op
                 existUser·p1.00:   28.180 ms/op

Iteration   3: 3.387 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.696 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  20.073 ms/op
                 existUser·p0.9999: 27.001 ms/op
                 existUser·p1.00:   27.853 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286875
  mean =      3.343 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9773 
    [ 2.500,  5.000) = 271543 
    [ 5.000,  7.500) = 4527 
    [ 7.500, 10.000) = 542 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 131 
    [25.000, 27.500) = 88 

  Percentiles, ms/op:
      p(0.0000) =      1.210 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     20.058 ms/op
     p(99.9900) =     26.649 ms/op
     p(99.9990) =     28.148 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


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
# Warmup Iteration   1: 9.285 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.757 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.473 ±(99.9%) 0.010 ms/op
Iteration   1: 3.498 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.149 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   4.002 ms/op
                 getUser·p0.95:   5.194 ms/op
                 getUser·p0.99:   6.955 ms/op
                 getUser·p0.999:  21.987 ms/op
                 getUser·p0.9999: 31.612 ms/op
                 getUser·p1.00:   32.932 ms/op

Iteration   2: 3.542 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.266 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   4.051 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   7.250 ms/op
                 getUser·p0.999:  11.649 ms/op
                 getUser·p0.9999: 34.800 ms/op
                 getUser·p1.00:   35.324 ms/op

Iteration   3: 3.468 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.337 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.998 ms/op
                 getUser·p0.95:   4.366 ms/op
                 getUser·p0.99:   5.910 ms/op
                 getUser·p0.999:  21.097 ms/op
                 getUser·p0.9999: 30.933 ms/op
                 getUser·p1.00:   32.211 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273944
  mean =      3.502 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12146 
    [ 2.500,  5.000) = 250588 
    [ 5.000,  7.500) = 9517 
    [ 7.500, 10.000) = 1123 
    [10.000, 12.500) = 248 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 37 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     16.045 ms/op
     p(99.9900) =     33.856 ms/op
     p(99.9990) =     35.065 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


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
# Warmup Iteration   1: 11.592 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.592 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.198 ±(99.9%) 0.016 ms/op
Iteration   1: 4.053 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.749 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  23.233 ms/op
                 listUser·p0.9999: 26.280 ms/op
                 listUser·p1.00:   26.771 ms/op

Iteration   2: 4.116 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.063 ms/op
                 listUser·p0.99:   8.184 ms/op
                 listUser·p0.999:  19.497 ms/op
                 listUser·p0.9999: 21.725 ms/op
                 listUser·p1.00:   23.003 ms/op

Iteration   3: 4.026 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.482 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   7.692 ms/op
                 listUser·p0.999:  15.172 ms/op
                 listUser·p0.9999: 19.302 ms/op
                 listUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236001
  mean =      4.065 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 226820 
    [ 5.000,  7.500) = 6227 
    [ 7.500, 10.000) = 1869 
    [10.000, 12.500) = 463 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.749 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      7.905 ms/op
     p(99.9000) =     18.776 ms/op
     p(99.9900) =     25.323 ms/op
     p(99.9990) =     26.465 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.206 ± 5.803  ops/ms
ClientPb.existUser                       thrpt       3   9.716 ± 4.978  ops/ms
ClientPb.getUser                         thrpt       3   9.407 ± 3.993  ops/ms
ClientPb.listUser                        thrpt       3   7.907 ± 1.928  ops/ms
ClientPb.createUser                       avgt       3   3.439 ± 1.924   ms/op
ClientPb.existUser                        avgt       3   3.279 ± 1.132   ms/op
ClientPb.getUser                          avgt       3   3.467 ± 1.408   ms/op
ClientPb.listUser                         avgt       3   3.963 ± 1.200   ms/op
ClientPb.createUser                     sample  280706   3.418 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.029           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.330           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.792           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.049           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.869           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.854           ms/op
ClientPb.existUser                      sample  286875   3.343 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.210           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.228           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.677           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.058           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.649           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.180           ms/op
ClientPb.getUser                        sample  273944   3.502 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.149           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.342           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.018           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.555           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.889           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.045           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.856           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.324           ms/op
ClientPb.listUser                       sample  236001   4.065 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.749           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.727           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.905           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.776           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.323           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.771           ms/op
