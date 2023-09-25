# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.048 ops/ms
# Warmup Iteration   2: 2.335 ops/ms
# Warmup Iteration   3: 4.581 ops/ms
Iteration   1: 5.325 ops/ms
Iteration   2: 5.690 ops/ms
Iteration   3: 5.565 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.526 ±(99.9%) 3.379 ops/ms [Average]
  (min, avg, max) = (5.325, 5.526, 5.690), stdev = 0.185
  CI (99.9%): [2.147, 8.906] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.703 ops/ms
# Warmup Iteration   2: 4.772 ops/ms
# Warmup Iteration   3: 5.981 ops/ms
Iteration   1: 6.105 ops/ms
Iteration   2: 5.819 ops/ms
Iteration   3: 6.193 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.039 ±(99.9%) 3.567 ops/ms [Average]
  (min, avg, max) = (5.819, 6.039, 6.193), stdev = 0.196
  CI (99.9%): [2.472, 9.606] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.606 ops/ms
# Warmup Iteration   2: 4.679 ops/ms
# Warmup Iteration   3: 5.726 ops/ms
Iteration   1: 5.768 ops/ms
Iteration   2: 5.918 ops/ms
Iteration   3: 5.759 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.815 ±(99.9%) 1.630 ops/ms [Average]
  (min, avg, max) = (5.759, 5.815, 5.918), stdev = 0.089
  CI (99.9%): [4.185, 7.445] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.425 ops/ms
# Warmup Iteration   2: 4.193 ops/ms
# Warmup Iteration   3: 4.889 ops/ms
Iteration   1: 4.755 ops/ms
Iteration   2: 5.030 ops/ms
Iteration   3: 4.961 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.915 ±(99.9%) 2.609 ops/ms [Average]
  (min, avg, max) = (4.755, 4.915, 5.030), stdev = 0.143
  CI (99.9%): [2.306, 7.525] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 18.104 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 6.979 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 6.154 ±(99.9%) 0.011 ms/op
Iteration   1: 5.612 ±(99.9%) 0.007 ms/op
Iteration   2: 5.485 ±(99.9%) 0.008 ms/op
Iteration   3: 5.518 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.538 ±(99.9%) 1.198 ms/op [Average]
  (min, avg, max) = (5.485, 5.538, 5.612), stdev = 0.066
  CI (99.9%): [4.340, 6.737] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 17.555 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 6.354 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.562 ±(99.9%) 0.006 ms/op
Iteration   1: 5.336 ±(99.9%) 0.006 ms/op
Iteration   2: 5.168 ±(99.9%) 0.008 ms/op
Iteration   3: 5.204 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.236 ±(99.9%) 1.614 ms/op [Average]
  (min, avg, max) = (5.168, 5.236, 5.336), stdev = 0.088
  CI (99.9%): [3.622, 6.849] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 17.810 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 6.574 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.593 ±(99.9%) 0.008 ms/op
Iteration   1: 5.596 ±(99.9%) 0.006 ms/op
Iteration   2: 5.539 ±(99.9%) 0.008 ms/op
Iteration   3: 5.425 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.520 ±(99.9%) 1.591 ms/op [Average]
  (min, avg, max) = (5.425, 5.520, 5.596), stdev = 0.087
  CI (99.9%): [3.929, 7.111] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 22.529 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 8.366 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.766 ±(99.9%) 0.009 ms/op
Iteration   1: 6.478 ±(99.9%) 0.012 ms/op
Iteration   2: 6.399 ±(99.9%) 0.012 ms/op
Iteration   3: 6.583 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.487 ±(99.9%) 1.681 ms/op [Average]
  (min, avg, max) = (6.399, 6.487, 6.583), stdev = 0.092
  CI (99.9%): [4.806, 8.167] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 20.742 ±(99.9%) 0.390 ms/op
# Warmup Iteration   2: 7.779 ±(99.9%) 0.061 ms/op
# Warmup Iteration   3: 6.046 ±(99.9%) 0.028 ms/op
Iteration   1: 5.623 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.589 ms/op
                 createUser·p0.50:   5.349 ms/op
                 createUser·p0.90:   6.758 ms/op
                 createUser·p0.95:   7.684 ms/op
                 createUser·p0.99:   10.567 ms/op
                 createUser·p0.999:  26.826 ms/op
                 createUser·p0.9999: 29.632 ms/op
                 createUser·p1.00:   30.441 ms/op

Iteration   2: 5.569 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.208 ms/op
                 createUser·p0.50:   5.382 ms/op
                 createUser·p0.90:   6.595 ms/op
                 createUser·p0.95:   7.340 ms/op
                 createUser·p0.99:   10.040 ms/op
                 createUser·p0.999:  16.482 ms/op
                 createUser·p0.9999: 30.823 ms/op
                 createUser·p1.00:   31.621 ms/op

Iteration   3: 5.648 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.568 ms/op
                 createUser·p0.50:   5.399 ms/op
                 createUser·p0.90:   6.734 ms/op
                 createUser·p0.95:   7.832 ms/op
                 createUser·p0.99:   11.027 ms/op
                 createUser·p0.999:  28.784 ms/op
                 createUser·p0.9999: 32.779 ms/op
                 createUser·p1.00:   33.030 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 170915
  mean =      5.613 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 45211 
    [ 5.000,  7.500) = 116599 
    [ 7.500, 10.000) = 6794 
    [10.000, 12.500) = 1598 
    [12.500, 15.000) = 403 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 87 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.208 ms/op
     p(50.0000) =      5.374 ms/op
     p(90.0000) =      6.701 ms/op
     p(95.0000) =      7.619 ms/op
     p(99.0000) =     10.568 ms/op
     p(99.9000) =     19.008 ms/op
     p(99.9900) =     32.166 ms/op
     p(99.9990) =     32.937 ms/op
     p(99.9999) =     33.030 ms/op
    p(100.0000) =     33.030 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.586 ±(99.9%) 0.256 ms/op
# Warmup Iteration   2: 7.048 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 5.351 ±(99.9%) 0.021 ms/op
Iteration   1: 5.253 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.380 ms/op
                 existUser·p0.50:   4.997 ms/op
                 existUser·p0.90:   6.291 ms/op
                 existUser·p0.95:   7.193 ms/op
                 existUser·p0.99:   9.765 ms/op
                 existUser·p0.999:  15.338 ms/op
                 existUser·p0.9999: 29.262 ms/op
                 existUser·p1.00:   30.147 ms/op

Iteration   2: 5.272 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.421 ms/op
                 existUser·p0.50:   4.997 ms/op
                 existUser·p0.90:   6.275 ms/op
                 existUser·p0.95:   7.553 ms/op
                 existUser·p0.99:   10.217 ms/op
                 existUser·p0.999:  25.559 ms/op
                 existUser·p0.9999: 29.122 ms/op
                 existUser·p1.00:   30.147 ms/op

Iteration   3: 5.283 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.499 ms/op
                 existUser·p0.50:   4.981 ms/op
                 existUser·p0.90:   6.324 ms/op
                 existUser·p0.95:   7.463 ms/op
                 existUser·p0.99:   11.583 ms/op
                 existUser·p0.999:  27.770 ms/op
                 existUser·p0.9999: 30.047 ms/op
                 existUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 182020
  mean =      5.270 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 92313 
    [ 5.000,  7.500) = 81029 
    [ 7.500, 10.000) = 6286 
    [10.000, 12.500) = 1592 
    [12.500, 15.000) = 484 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 98 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.380 ms/op
     p(50.0000) =      4.989 ms/op
     p(90.0000) =      6.300 ms/op
     p(95.0000) =      7.373 ms/op
     p(99.0000) =     10.650 ms/op
     p(99.9000) =     19.169 ms/op
     p(99.9900) =     29.747 ms/op
     p(99.9990) =     30.655 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 19.185 ±(99.9%) 0.284 ms/op
# Warmup Iteration   2: 6.876 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.738 ±(99.9%) 0.024 ms/op
Iteration   1: 5.491 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.183 ms/op
                 getUser·p0.50:   5.120 ms/op
                 getUser·p0.90:   6.750 ms/op
                 getUser·p0.95:   8.651 ms/op
                 getUser·p0.99:   11.960 ms/op
                 getUser·p0.999:  26.312 ms/op
                 getUser·p0.9999: 30.819 ms/op
                 getUser·p1.00:   31.490 ms/op

Iteration   2: 5.759 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   1.911 ms/op
                 getUser·p0.50:   5.267 ms/op
                 getUser·p0.90:   7.201 ms/op
                 getUser·p0.95:   9.241 ms/op
                 getUser·p0.99:   14.352 ms/op
                 getUser·p0.999:  29.327 ms/op
                 getUser·p0.9999: 36.241 ms/op
                 getUser·p1.00:   42.926 ms/op

Iteration   3: 5.280 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.634 ms/op
                 getUser·p0.50:   5.128 ms/op
                 getUser·p0.90:   6.095 ms/op
                 getUser·p0.95:   6.889 ms/op
                 getUser·p0.99:   10.174 ms/op
                 getUser·p0.999:  28.523 ms/op
                 getUser·p0.9999: 32.171 ms/op
                 getUser·p1.00:   33.161 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 174308
  mean =      5.503 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 66792 
    [ 5.000, 10.000) = 103473 
    [10.000, 15.000) = 3299 
    [15.000, 20.000) = 413 
    [20.000, 25.000) = 97 
    [25.000, 30.000) = 131 
    [30.000, 35.000) = 95 
    [35.000, 40.000) = 6 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.634 ms/op
     p(50.0000) =      5.169 ms/op
     p(90.0000) =      6.619 ms/op
     p(95.0000) =      8.348 ms/op
     p(99.0000) =     12.337 ms/op
     p(99.9000) =     28.173 ms/op
     p(99.9900) =     33.839 ms/op
     p(99.9990) =     42.926 ms/op
     p(99.9999) =     42.926 ms/op
    p(100.0000) =     42.926 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 21.742 ±(99.9%) 0.370 ms/op
# Warmup Iteration   2: 7.814 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 6.644 ±(99.9%) 0.027 ms/op
Iteration   1: 6.609 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.393 ms/op
                 listUser·p0.50:   6.144 ms/op
                 listUser·p0.90:   8.159 ms/op
                 listUser·p0.95:   10.142 ms/op
                 listUser·p0.99:   13.779 ms/op
                 listUser·p0.999:  27.925 ms/op
                 listUser·p0.9999: 30.561 ms/op
                 listUser·p1.00:   30.900 ms/op

Iteration   2: 6.474 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.437 ms/op
                 listUser·p0.50:   6.095 ms/op
                 listUser·p0.90:   7.643 ms/op
                 listUser·p0.95:   9.208 ms/op
                 listUser·p0.99:   12.763 ms/op
                 listUser·p0.999:  31.823 ms/op
                 listUser·p0.9999: 34.287 ms/op
                 listUser·p1.00:   35.127 ms/op

Iteration   3: 6.282 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   5.890 ms/op
                 listUser·p0.90:   7.586 ms/op
                 listUser·p0.95:   9.044 ms/op
                 listUser·p0.99:   12.468 ms/op
                 listUser·p0.999:  24.417 ms/op
                 listUser·p0.9999: 30.540 ms/op
                 listUser·p1.00:   32.342 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 148658
  mean =      6.453 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 5030 
    [ 5.000,  7.500) = 126204 
    [ 7.500, 10.000) = 11368 
    [10.000, 12.500) = 4159 
    [12.500, 15.000) = 1163 
    [15.000, 17.500) = 306 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 91 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 35 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.393 ms/op
     p(50.0000) =      6.021 ms/op
     p(90.0000) =      7.766 ms/op
     p(95.0000) =      9.470 ms/op
     p(99.0000) =     13.074 ms/op
     p(99.9000) =     28.334 ms/op
     p(99.9900) =     33.948 ms/op
     p(99.9990) =     34.968 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.526 ± 3.379  ops/ms
ClientPb.existUser                       thrpt       3   6.039 ± 3.567  ops/ms
ClientPb.getUser                         thrpt       3   5.815 ± 1.630  ops/ms
ClientPb.listUser                        thrpt       3   4.915 ± 2.609  ops/ms
ClientPb.createUser                       avgt       3   5.538 ± 1.198   ms/op
ClientPb.existUser                        avgt       3   5.236 ± 1.614   ms/op
ClientPb.getUser                          avgt       3   5.520 ± 1.591   ms/op
ClientPb.listUser                         avgt       3   6.487 ± 1.681   ms/op
ClientPb.createUser                     sample  170915   5.613 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.208           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.374           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.701           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.619           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.568           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.008           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.166           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.030           ms/op
ClientPb.existUser                      sample  182020   5.270 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.380           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.989           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.300           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.373           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.650           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.169           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.747           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.031           ms/op
ClientPb.getUser                        sample  174308   5.503 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.634           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.169           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.619           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.348           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.337           ms/op
ClientPb.getUser:getUser·p0.999         sample          28.173           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.839           ms/op
ClientPb.getUser:getUser·p1.00          sample          42.926           ms/op
ClientPb.listUser                       sample  148658   6.453 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.393           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.021           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.766           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.470           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.074           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.334           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.948           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.127           ms/op
