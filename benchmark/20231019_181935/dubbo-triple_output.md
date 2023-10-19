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
# Warmup Iteration   1: 0.941 ops/ms
# Warmup Iteration   2: 2.251 ops/ms
# Warmup Iteration   3: 4.514 ops/ms
Iteration   1: 5.442 ops/ms
Iteration   2: 5.470 ops/ms
Iteration   3: 5.425 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.446 ±(99.9%) 0.412 ops/ms [Average]
  (min, avg, max) = (5.425, 5.446, 5.470), stdev = 0.023
  CI (99.9%): [5.034, 5.858] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.600 ops/ms
# Warmup Iteration   2: 4.003 ops/ms
# Warmup Iteration   3: 5.754 ops/ms
Iteration   1: 5.884 ops/ms
Iteration   2: 6.031 ops/ms
Iteration   3: 5.859 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.925 ±(99.9%) 1.693 ops/ms [Average]
  (min, avg, max) = (5.859, 5.925, 6.031), stdev = 0.093
  CI (99.9%): [4.231, 7.618] (assumes normal distribution)


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
# Warmup Iteration   1: 1.440 ops/ms
# Warmup Iteration   2: 4.367 ops/ms
# Warmup Iteration   3: 5.685 ops/ms
Iteration   1: 5.783 ops/ms
Iteration   2: 5.634 ops/ms
Iteration   3: 5.342 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.587 ±(99.9%) 4.093 ops/ms [Average]
  (min, avg, max) = (5.342, 5.587, 5.783), stdev = 0.224
  CI (99.9%): [1.494, 9.679] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.436 ops/ms
# Warmup Iteration   2: 4.070 ops/ms
# Warmup Iteration   3: 4.839 ops/ms
Iteration   1: 4.958 ops/ms
Iteration   2: 4.735 ops/ms
Iteration   3: 4.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.800 ±(99.9%) 2.506 ops/ms [Average]
  (min, avg, max) = (4.707, 4.800, 4.958), stdev = 0.137
  CI (99.9%): [2.294, 7.306] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 18.171 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 6.916 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.090 ±(99.9%) 0.013 ms/op
Iteration   1: 5.569 ±(99.9%) 0.012 ms/op
Iteration   2: 6.155 ±(99.9%) 0.010 ms/op
Iteration   3: 5.587 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.770 ±(99.9%) 6.082 ms/op [Average]
  (min, avg, max) = (5.569, 5.770, 6.155), stdev = 0.333
  CI (99.9%): [≈ 0, 11.852] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 16.973 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 6.293 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.390 ±(99.9%) 0.010 ms/op
Iteration   1: 5.339 ±(99.9%) 0.009 ms/op
Iteration   2: 5.683 ±(99.9%) 0.011 ms/op
Iteration   3: 5.323 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.449 ±(99.9%) 3.714 ms/op [Average]
  (min, avg, max) = (5.323, 5.449, 5.683), stdev = 0.204
  CI (99.9%): [1.735, 9.162] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 18.602 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 6.589 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.583 ±(99.9%) 0.012 ms/op
Iteration   1: 5.773 ±(99.9%) 0.015 ms/op
Iteration   2: 5.798 ±(99.9%) 0.008 ms/op
Iteration   3: 5.588 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.720 ±(99.9%) 2.090 ms/op [Average]
  (min, avg, max) = (5.588, 5.720, 5.798), stdev = 0.115
  CI (99.9%): [3.629, 7.810] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 21.038 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 7.875 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.691 ±(99.9%) 0.014 ms/op
Iteration   1: 7.004 ±(99.9%) 0.011 ms/op
Iteration   2: 6.414 ±(99.9%) 0.017 ms/op
Iteration   3: 6.249 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.556 ±(99.9%) 7.238 ms/op [Average]
  (min, avg, max) = (6.249, 6.556, 7.004), stdev = 0.397
  CI (99.9%): [≈ 0, 13.794] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 18.649 ±(99.9%) 0.325 ms/op
# Warmup Iteration   2: 7.336 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.358 ±(99.9%) 0.034 ms/op
Iteration   1: 5.856 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   2.421 ms/op
                 createUser·p0.50:   5.382 ms/op
                 createUser·p0.90:   7.530 ms/op
                 createUser·p0.95:   8.897 ms/op
                 createUser·p0.99:   12.894 ms/op
                 createUser·p0.999:  26.162 ms/op
                 createUser·p0.9999: 30.197 ms/op
                 createUser·p1.00:   31.785 ms/op

Iteration   2: 5.577 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.288 ms/op
                 createUser·p0.50:   5.169 ms/op
                 createUser·p0.90:   6.922 ms/op
                 createUser·p0.95:   8.025 ms/op
                 createUser·p0.99:   11.207 ms/op
                 createUser·p0.999:  27.293 ms/op
                 createUser·p0.9999: 33.145 ms/op
                 createUser·p1.00:   34.734 ms/op

Iteration   3: 5.649 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.269 ms/op
                 createUser·p0.50:   5.300 ms/op
                 createUser·p0.90:   6.832 ms/op
                 createUser·p0.95:   7.750 ms/op
                 createUser·p0.99:   11.583 ms/op
                 createUser·p0.999:  27.597 ms/op
                 createUser·p0.9999: 31.588 ms/op
                 createUser·p1.00:   31.785 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 168596
  mean =      5.692 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 54631 
    [ 5.000,  7.500) = 101124 
    [ 7.500, 10.000) = 9253 
    [10.000, 12.500) = 2146 
    [12.500, 15.000) = 713 
    [15.000, 17.500) = 296 
    [17.500, 20.000) = 155 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 96 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.288 ms/op
     p(50.0000) =      5.276 ms/op
     p(90.0000) =      7.045 ms/op
     p(95.0000) =      8.290 ms/op
     p(99.0000) =     11.928 ms/op
     p(99.9000) =     26.497 ms/op
     p(99.9900) =     31.988 ms/op
     p(99.9990) =     34.374 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


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
# Warmup Iteration   1: 17.491 ±(99.9%) 0.260 ms/op
# Warmup Iteration   2: 6.825 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.910 ±(99.9%) 0.028 ms/op
Iteration   1: 5.671 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.028 ms/op
                 existUser·p0.50:   5.341 ms/op
                 existUser·p0.90:   7.135 ms/op
                 existUser·p0.95:   8.143 ms/op
                 existUser·p0.99:   11.686 ms/op
                 existUser·p0.999:  20.959 ms/op
                 existUser·p0.9999: 26.882 ms/op
                 existUser·p1.00:   28.869 ms/op

Iteration   2: 5.410 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.028 ms/op
                 existUser·p0.50:   5.038 ms/op
                 existUser·p0.90:   6.816 ms/op
                 existUser·p0.95:   7.746 ms/op
                 existUser·p0.99:   10.486 ms/op
                 existUser·p0.999:  24.674 ms/op
                 existUser·p0.9999: 28.714 ms/op
                 existUser·p1.00:   29.229 ms/op

Iteration   3: 5.335 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.538 ms/op
                 existUser·p0.50:   4.989 ms/op
                 existUser·p0.90:   6.578 ms/op
                 existUser·p0.95:   7.709 ms/op
                 existUser·p0.99:   10.109 ms/op
                 existUser·p0.999:  26.739 ms/op
                 existUser·p0.9999: 30.671 ms/op
                 existUser·p1.00:   31.916 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 175406
  mean =      5.468 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 77897 
    [ 5.000,  7.500) = 86007 
    [ 7.500, 10.000) = 9189 
    [10.000, 12.500) = 1352 
    [12.500, 15.000) = 501 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.538 ms/op
     p(50.0000) =      5.104 ms/op
     p(90.0000) =      6.857 ms/op
     p(95.0000) =      7.864 ms/op
     p(99.0000) =     10.617 ms/op
     p(99.9000) =     23.449 ms/op
     p(99.9900) =     29.695 ms/op
     p(99.9990) =     31.669 ms/op
     p(99.9999) =     31.916 ms/op
    p(100.0000) =     31.916 ms/op


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
# Warmup Iteration   1: 18.548 ±(99.9%) 0.303 ms/op
# Warmup Iteration   2: 6.566 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.807 ±(99.9%) 0.026 ms/op
Iteration   1: 5.537 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.490 ms/op
                 getUser·p0.50:   5.120 ms/op
                 getUser·p0.90:   6.881 ms/op
                 getUser·p0.95:   7.971 ms/op
                 getUser·p0.99:   12.084 ms/op
                 getUser·p0.999:  23.069 ms/op
                 getUser·p0.9999: 27.733 ms/op
                 getUser·p1.00:   28.639 ms/op

Iteration   2: 5.773 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   1.212 ms/op
                 getUser·p0.50:   5.243 ms/op
                 getUser·p0.90:   7.496 ms/op
                 getUser·p0.95:   9.011 ms/op
                 getUser·p0.99:   13.606 ms/op
                 getUser·p0.999:  25.646 ms/op
                 getUser·p0.9999: 28.718 ms/op
                 getUser·p1.00:   30.704 ms/op

Iteration   3: 5.641 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.845 ms/op
                 getUser·p0.50:   5.399 ms/op
                 getUser·p0.90:   6.758 ms/op
                 getUser·p0.95:   7.553 ms/op
                 getUser·p0.99:   10.879 ms/op
                 getUser·p0.999:  15.297 ms/op
                 getUser·p0.9999: 29.808 ms/op
                 getUser·p1.00:   30.343 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 169767
  mean =      5.649 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 61713 
    [ 5.000,  7.500) = 95881 
    [ 7.500, 10.000) = 8647 
    [10.000, 12.500) = 1988 
    [12.500, 15.000) = 898 
    [15.000, 17.500) = 296 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.212 ms/op
     p(50.0000) =      5.259 ms/op
     p(90.0000) =      6.980 ms/op
     p(95.0000) =      8.282 ms/op
     p(99.0000) =     12.239 ms/op
     p(99.9000) =     23.469 ms/op
     p(99.9900) =     28.777 ms/op
     p(99.9990) =     30.452 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


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
# Warmup Iteration   1: 21.125 ±(99.9%) 0.366 ms/op
# Warmup Iteration   2: 8.621 ±(99.9%) 0.072 ms/op
# Warmup Iteration   3: 6.668 ±(99.9%) 0.028 ms/op
Iteration   1: 6.698 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   2.781 ms/op
                 listUser·p0.50:   6.210 ms/op
                 listUser·p0.90:   8.282 ms/op
                 listUser·p0.95:   10.191 ms/op
                 listUser·p0.99:   14.615 ms/op
                 listUser·p0.999:  27.329 ms/op
                 listUser·p0.9999: 30.920 ms/op
                 listUser·p1.00:   32.178 ms/op

Iteration   2: 6.559 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.585 ms/op
                 listUser·p0.50:   6.193 ms/op
                 listUser·p0.90:   7.946 ms/op
                 listUser·p0.95:   8.913 ms/op
                 listUser·p0.99:   12.255 ms/op
                 listUser·p0.999:  29.833 ms/op
                 listUser·p0.9999: 33.096 ms/op
                 listUser·p1.00:   33.686 ms/op

Iteration   3: 6.737 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.433 ms/op
                 listUser·p0.50:   6.185 ms/op
                 listUser·p0.90:   8.487 ms/op
                 listUser·p0.95:   10.027 ms/op
                 listUser·p0.99:   13.746 ms/op
                 listUser·p0.999:  26.176 ms/op
                 listUser·p0.9999: 32.400 ms/op
                 listUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 143991
  mean =      6.664 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 4115 
    [ 5.000,  7.500) = 115948 
    [ 7.500, 10.000) = 17658 
    [10.000, 12.500) = 4022 
    [12.500, 15.000) = 1334 
    [15.000, 17.500) = 479 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 93 
    [30.000, 32.500) = 64 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.433 ms/op
     p(50.0000) =      6.201 ms/op
     p(90.0000) =      8.217 ms/op
     p(95.0000) =      9.699 ms/op
     p(99.0000) =     13.566 ms/op
     p(99.9000) =     28.246 ms/op
     p(99.9900) =     32.545 ms/op
     p(99.9990) =     33.657 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.446 ± 0.412  ops/ms
ClientPb.existUser                       thrpt       3   5.925 ± 1.693  ops/ms
ClientPb.getUser                         thrpt       3   5.587 ± 4.093  ops/ms
ClientPb.listUser                        thrpt       3   4.800 ± 2.506  ops/ms
ClientPb.createUser                       avgt       3   5.770 ± 6.082   ms/op
ClientPb.existUser                        avgt       3   5.449 ± 3.714   ms/op
ClientPb.getUser                          avgt       3   5.720 ± 2.090   ms/op
ClientPb.listUser                         avgt       3   6.556 ± 7.238   ms/op
ClientPb.createUser                     sample  168596   5.692 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.288           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.276           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.045           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.290           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.928           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.497           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.988           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.734           ms/op
ClientPb.existUser                      sample  175406   5.468 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.538           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.104           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.857           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.864           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.617           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.449           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.695           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.916           ms/op
ClientPb.getUser                        sample  169767   5.649 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.212           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.259           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.980           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.282           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.239           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.469           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.777           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.704           ms/op
ClientPb.listUser                       sample  143991   6.664 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.433           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.201           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.217           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.699           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.566           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.246           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.545           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.686           ms/op
