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
# Warmup Iteration   1: 2.132 ops/ms
# Warmup Iteration   2: 5.725 ops/ms
# Warmup Iteration   3: 8.588 ops/ms
Iteration   1: 9.185 ops/ms
Iteration   2: 8.973 ops/ms
Iteration   3: 9.490 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.216 ±(99.9%) 4.744 ops/ms [Average]
  (min, avg, max) = (8.973, 9.216, 9.490), stdev = 0.260
  CI (99.9%): [4.472, 13.960] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 2.911 ops/ms
# Warmup Iteration   2: 9.110 ops/ms
# Warmup Iteration   3: 9.626 ops/ms
Iteration   1: 9.887 ops/ms
Iteration   2: 9.542 ops/ms
Iteration   3: 9.776 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.735 ±(99.9%) 3.211 ops/ms [Average]
  (min, avg, max) = (9.542, 9.735, 9.887), stdev = 0.176
  CI (99.9%): [6.524, 12.946] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.909 ops/ms
# Warmup Iteration   2: 8.353 ops/ms
# Warmup Iteration   3: 9.247 ops/ms
Iteration   1: 9.639 ops/ms
Iteration   2: 9.643 ops/ms
Iteration   3: 9.429 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.570 ±(99.9%) 2.232 ops/ms [Average]
  (min, avg, max) = (9.429, 9.570, 9.643), stdev = 0.122
  CI (99.9%): [7.338, 11.803] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.861 ops/ms
# Warmup Iteration   2: 7.377 ops/ms
# Warmup Iteration   3: 7.727 ops/ms
Iteration   1: 8.105 ops/ms
Iteration   2: 8.105 ops/ms
Iteration   3: 8.343 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.184 ±(99.9%) 2.505 ops/ms [Average]
  (min, avg, max) = (8.105, 8.184, 8.343), stdev = 0.137
  CI (99.9%): [5.679, 10.689] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.651 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.842 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.589 ±(99.9%) 0.005 ms/op
Iteration   1: 3.414 ±(99.9%) 0.009 ms/op
Iteration   2: 3.305 ±(99.9%) 0.011 ms/op
Iteration   3: 3.304 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.341 ±(99.9%) 1.147 ms/op [Average]
  (min, avg, max) = (3.304, 3.341, 3.414), stdev = 0.063
  CI (99.9%): [2.194, 4.488] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.858 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.510 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.007 ms/op
Iteration   1: 3.237 ±(99.9%) 0.007 ms/op
Iteration   2: 3.280 ±(99.9%) 0.007 ms/op
Iteration   3: 3.203 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.240 ±(99.9%) 0.709 ms/op [Average]
  (min, avg, max) = (3.203, 3.240, 3.280), stdev = 0.039
  CI (99.9%): [2.531, 3.949] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 9.234 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.673 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.502 ±(99.9%) 0.005 ms/op
Iteration   1: 3.436 ±(99.9%) 0.006 ms/op
Iteration   2: 3.308 ±(99.9%) 0.005 ms/op
Iteration   3: 3.330 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.358 ±(99.9%) 1.249 ms/op [Average]
  (min, avg, max) = (3.308, 3.358, 3.436), stdev = 0.068
  CI (99.9%): [2.108, 4.607] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 10.239 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.505 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.058 ±(99.9%) 0.008 ms/op
Iteration   1: 4.007 ±(99.9%) 0.007 ms/op
Iteration   2: 3.965 ±(99.9%) 0.008 ms/op
Iteration   3: 3.917 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.963 ±(99.9%) 0.817 ms/op [Average]
  (min, avg, max) = (3.917, 3.963, 4.007), stdev = 0.045
  CI (99.9%): [3.147, 4.780] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 10.576 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.095 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.799 ±(99.9%) 0.014 ms/op
Iteration   1: 3.380 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.649 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  19.300 ms/op
                 createUser·p0.9999: 24.089 ms/op
                 createUser·p1.00:   24.576 ms/op

Iteration   2: 3.366 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.139 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   3.988 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  20.840 ms/op
                 createUser·p0.9999: 29.639 ms/op
                 createUser·p1.00:   30.441 ms/op

Iteration   3: 3.393 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.223 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  13.327 ms/op
                 createUser·p0.9999: 26.678 ms/op
                 createUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 284043
  mean =      3.379 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5812 
    [ 2.500,  5.000) = 272843 
    [ 5.000,  7.500) = 4343 
    [ 7.500, 10.000) = 578 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.139 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     16.071 ms/op
     p(99.9900) =     28.462 ms/op
     p(99.9990) =     30.107 ms/op
     p(99.9999) =     30.441 ms/op
    p(100.0000) =     30.441 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.359 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.723 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.435 ±(99.9%) 0.009 ms/op
Iteration   1: 3.473 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.921 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  9.028 ms/op
                 existUser·p0.9999: 22.275 ms/op
                 existUser·p1.00:   23.986 ms/op

Iteration   2: 3.275 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.473 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  10.076 ms/op
                 existUser·p0.9999: 24.969 ms/op
                 existUser·p1.00:   26.608 ms/op

Iteration   3: 3.398 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.391 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.875 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   6.373 ms/op
                 existUser·p0.999:  23.626 ms/op
                 existUser·p0.9999: 27.492 ms/op
                 existUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284069
  mean =      3.380 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8366 
    [ 2.500,  5.000) = 268621 
    [ 5.000,  7.500) = 6019 
    [ 7.500, 10.000) = 528 
    [10.000, 12.500) = 218 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 140 
    [25.000, 27.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      0.921 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     16.495 ms/op
     p(99.9900) =     26.194 ms/op
     p(99.9990) =     27.722 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 8.379 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.600 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.517 ±(99.9%) 0.011 ms/op
Iteration   1: 3.407 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.188 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   6.488 ms/op
                 getUser·p0.999:  17.503 ms/op
                 getUser·p0.9999: 20.546 ms/op
                 getUser·p1.00:   21.561 ms/op

Iteration   2: 3.378 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.182 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.186 ms/op
                 getUser·p0.99:   6.300 ms/op
                 getUser·p0.999:  20.132 ms/op
                 getUser·p0.9999: 25.877 ms/op
                 getUser·p1.00:   26.771 ms/op

Iteration   3: 3.437 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.343 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.201 ms/op
                 getUser·p0.999:  17.759 ms/op
                 getUser·p0.9999: 28.695 ms/op
                 getUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 281577
  mean =      3.407 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5814 
    [ 2.500,  5.000) = 268223 
    [ 5.000,  7.500) = 6156 
    [ 7.500, 10.000) = 833 
    [10.000, 12.500) = 227 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.182 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      6.332 ms/op
     p(99.9000) =     17.741 ms/op
     p(99.9900) =     27.510 ms/op
     p(99.9990) =     29.083 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


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
# Warmup Iteration   1: 10.506 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 4.427 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.054 ±(99.9%) 0.012 ms/op
Iteration   1: 4.005 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  18.028 ms/op
                 listUser·p0.9999: 22.185 ms/op
                 listUser·p1.00:   23.593 ms/op

Iteration   2: 4.083 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.948 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   7.922 ms/op
                 listUser·p0.999:  15.811 ms/op
                 listUser·p0.9999: 18.547 ms/op
                 listUser·p1.00:   19.038 ms/op

Iteration   3: 4.103 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.442 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.120 ms/op
                 listUser·p0.99:   7.655 ms/op
                 listUser·p0.999:  16.417 ms/op
                 listUser·p0.9999: 18.022 ms/op
                 listUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236081
  mean =      4.064 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 225397 
    [ 5.000,  7.500) = 8164 
    [ 7.500, 10.000) = 1515 
    [10.000, 12.500) = 390 
    [12.500, 15.000) = 199 
    [15.000, 17.500) = 253 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.442 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      7.602 ms/op
     p(99.9000) =     16.415 ms/op
     p(99.9900) =     20.939 ms/op
     p(99.9990) =     23.188 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.216 ± 4.744  ops/ms
ClientPb.existUser                       thrpt       3   9.735 ± 3.211  ops/ms
ClientPb.getUser                         thrpt       3   9.570 ± 2.232  ops/ms
ClientPb.listUser                        thrpt       3   8.184 ± 2.505  ops/ms
ClientPb.createUser                       avgt       3   3.341 ± 1.147   ms/op
ClientPb.existUser                        avgt       3   3.240 ± 0.709   ms/op
ClientPb.getUser                          avgt       3   3.358 ± 1.249   ms/op
ClientPb.listUser                         avgt       3   3.963 ± 0.817   ms/op
ClientPb.createUser                     sample  284043   3.379 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.139           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.273           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.035           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.734           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.071           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.462           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.441           ms/op
ClientPb.existUser                      sample  284069   3.380 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.921           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.248           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.879           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.350           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.767           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.495           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.194           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.787           ms/op
ClientPb.getUser                        sample  281577   3.407 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.182           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.281           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.332           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.741           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.510           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.590           ms/op
ClientPb.listUser                       sample  236081   4.064 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.442           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.923           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.602           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.415           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.939           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.593           ms/op
