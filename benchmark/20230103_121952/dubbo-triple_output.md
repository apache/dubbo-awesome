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
# Warmup Iteration   1: 0.979 ops/ms
# Warmup Iteration   2: 2.182 ops/ms
# Warmup Iteration   3: 4.558 ops/ms
Iteration   1: 4.828 ops/ms
Iteration   2: 5.025 ops/ms
Iteration   3: 5.366 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.073 ±(99.9%) 4.967 ops/ms [Average]
  (min, avg, max) = (4.828, 5.073, 5.366), stdev = 0.272
  CI (99.9%): [0.106, 10.040] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.405 ops/ms
# Warmup Iteration   2: 4.355 ops/ms
# Warmup Iteration   3: 5.628 ops/ms
Iteration   1: 5.827 ops/ms
Iteration   2: 5.701 ops/ms
Iteration   3: 5.428 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.652 ±(99.9%) 3.720 ops/ms [Average]
  (min, avg, max) = (5.428, 5.652, 5.827), stdev = 0.204
  CI (99.9%): [1.932, 9.372] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.372 ops/ms
# Warmup Iteration   2: 4.285 ops/ms
# Warmup Iteration   3: 5.404 ops/ms
Iteration   1: 5.548 ops/ms
Iteration   2: 5.385 ops/ms
Iteration   3: 5.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.431 ±(99.9%) 1.863 ops/ms [Average]
  (min, avg, max) = (5.360, 5.431, 5.548), stdev = 0.102
  CI (99.9%): [3.568, 7.293] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.494 ops/ms
# Warmup Iteration   2: 3.792 ops/ms
# Warmup Iteration   3: 4.676 ops/ms
Iteration   1: 4.417 ops/ms
Iteration   2: 4.769 ops/ms
Iteration   3: 4.691 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.626 ±(99.9%) 3.381 ops/ms [Average]
  (min, avg, max) = (4.417, 4.626, 4.769), stdev = 0.185
  CI (99.9%): [1.245, 8.007] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 20.316 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 7.141 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.990 ±(99.9%) 0.011 ms/op
Iteration   1: 6.197 ±(99.9%) 0.016 ms/op
Iteration   2: 6.115 ±(99.9%) 0.010 ms/op
Iteration   3: 5.992 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.101 ±(99.9%) 1.887 ms/op [Average]
  (min, avg, max) = (5.992, 6.101, 6.197), stdev = 0.103
  CI (99.9%): [4.214, 7.988] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 17.346 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 6.884 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.036 ±(99.9%) 0.011 ms/op
Iteration   1: 5.821 ±(99.9%) 0.008 ms/op
Iteration   2: 5.577 ±(99.9%) 0.011 ms/op
Iteration   3: 5.537 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.645 ±(99.9%) 2.801 ms/op [Average]
  (min, avg, max) = (5.537, 5.645, 5.821), stdev = 0.154
  CI (99.9%): [2.844, 8.445] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 18.133 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 7.146 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.982 ±(99.9%) 0.011 ms/op
Iteration   1: 5.938 ±(99.9%) 0.011 ms/op
Iteration   2: 5.957 ±(99.9%) 0.010 ms/op
Iteration   3: 5.825 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.907 ±(99.9%) 1.305 ms/op [Average]
  (min, avg, max) = (5.825, 5.907, 5.957), stdev = 0.072
  CI (99.9%): [4.602, 7.211] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 20.523 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 9.094 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 6.907 ±(99.9%) 0.015 ms/op
Iteration   1: 6.878 ±(99.9%) 0.016 ms/op
Iteration   2: 6.959 ±(99.9%) 0.013 ms/op
Iteration   3: 7.220 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.019 ±(99.9%) 3.265 ms/op [Average]
  (min, avg, max) = (6.878, 7.019, 7.220), stdev = 0.179
  CI (99.9%): [3.754, 10.284] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 22.580 ±(99.9%) 0.417 ms/op
# Warmup Iteration   2: 7.816 ±(99.9%) 0.058 ms/op
# Warmup Iteration   3: 6.742 ±(99.9%) 0.035 ms/op
Iteration   1: 6.043 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.744 ms/op
                 createUser·p0.50:   5.603 ms/op
                 createUser·p0.90:   7.856 ms/op
                 createUser·p0.95:   8.864 ms/op
                 createUser·p0.99:   11.862 ms/op
                 createUser·p0.999:  24.052 ms/op
                 createUser·p0.9999: 26.500 ms/op
                 createUser·p1.00:   26.837 ms/op

Iteration   2: 5.928 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.445 ms/op
                 createUser·p0.50:   5.587 ms/op
                 createUser·p0.90:   7.463 ms/op
                 createUser·p0.95:   8.372 ms/op
                 createUser·p0.99:   11.043 ms/op
                 createUser·p0.999:  25.530 ms/op
                 createUser·p0.9999: 37.199 ms/op
                 createUser·p1.00:   37.814 ms/op

Iteration   3: 5.877 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.695 ms/op
                 createUser·p0.50:   5.423 ms/op
                 createUser·p0.90:   7.479 ms/op
                 createUser·p0.95:   8.569 ms/op
                 createUser·p0.99:   11.977 ms/op
                 createUser·p0.999:  24.904 ms/op
                 createUser·p0.9999: 33.278 ms/op
                 createUser·p1.00:   33.358 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 161233
  mean =      5.949 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 39016 
    [ 5.000,  7.500) = 104708 
    [ 7.500, 10.000) = 13781 
    [10.000, 12.500) = 2625 
    [12.500, 15.000) = 658 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      2.445 ms/op
     p(50.0000) =      5.530 ms/op
     p(90.0000) =      7.627 ms/op
     p(95.0000) =      8.618 ms/op
     p(99.0000) =     11.600 ms/op
     p(99.9000) =     24.740 ms/op
     p(99.9900) =     34.841 ms/op
     p(99.9990) =     37.654 ms/op
     p(99.9999) =     37.814 ms/op
    p(100.0000) =     37.814 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.682 ±(99.9%) 0.327 ms/op
# Warmup Iteration   2: 7.511 ±(99.9%) 0.055 ms/op
# Warmup Iteration   3: 5.845 ±(99.9%) 0.025 ms/op
Iteration   1: 5.840 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.466 ms/op
                 existUser·p0.50:   5.456 ms/op
                 existUser·p0.90:   7.684 ms/op
                 existUser·p0.95:   8.815 ms/op
                 existUser·p0.99:   11.665 ms/op
                 existUser·p0.999:  15.483 ms/op
                 existUser·p0.9999: 30.852 ms/op
                 existUser·p1.00:   31.621 ms/op

Iteration   2: 5.839 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   2.503 ms/op
                 existUser·p0.50:   5.579 ms/op
                 existUser·p0.90:   7.504 ms/op
                 existUser·p0.95:   8.471 ms/op
                 existUser·p0.99:   10.990 ms/op
                 existUser·p0.999:  31.492 ms/op
                 existUser·p0.9999: 37.855 ms/op
                 existUser·p1.00:   38.470 ms/op

Iteration   3: 5.950 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   2.343 ms/op
                 existUser·p0.50:   5.579 ms/op
                 existUser·p0.90:   7.717 ms/op
                 existUser·p0.95:   8.791 ms/op
                 existUser·p0.99:   11.633 ms/op
                 existUser·p0.999:  24.347 ms/op
                 existUser·p0.9999: 41.157 ms/op
                 existUser·p1.00:   41.419 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 163343
  mean =      5.876 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 51510 
    [ 5.000, 10.000) = 107836 
    [10.000, 15.000) = 3686 
    [15.000, 20.000) = 147 
    [20.000, 25.000) = 19 
    [25.000, 30.000) = 33 
    [30.000, 35.000) = 68 
    [35.000, 40.000) = 33 
    [40.000, 45.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      2.343 ms/op
     p(50.0000) =      5.538 ms/op
     p(90.0000) =      7.643 ms/op
     p(95.0000) =      8.684 ms/op
     p(99.0000) =     11.436 ms/op
     p(99.9000) =     20.107 ms/op
     p(99.9900) =     38.382 ms/op
     p(99.9990) =     41.294 ms/op
     p(99.9999) =     41.419 ms/op
    p(100.0000) =     41.419 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.569 ±(99.9%) 0.312 ms/op
# Warmup Iteration   2: 6.933 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 6.134 ±(99.9%) 0.028 ms/op
Iteration   1: 6.224 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   2.331 ms/op
                 getUser·p0.50:   5.759 ms/op
                 getUser·p0.90:   8.249 ms/op
                 getUser·p0.95:   9.552 ms/op
                 getUser·p0.99:   14.877 ms/op
                 getUser·p0.999:  31.551 ms/op
                 getUser·p0.9999: 36.504 ms/op
                 getUser·p1.00:   36.766 ms/op

Iteration   2: 5.847 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.736 ms/op
                 getUser·p0.50:   5.472 ms/op
                 getUser·p0.90:   7.463 ms/op
                 getUser·p0.95:   8.684 ms/op
                 getUser·p0.99:   11.244 ms/op
                 getUser·p0.999:  27.514 ms/op
                 getUser·p0.9999: 33.786 ms/op
                 getUser·p1.00:   34.341 ms/op

Iteration   3: 6.023 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.826 ms/op
                 getUser·p0.50:   5.554 ms/op
                 getUser·p0.90:   7.979 ms/op
                 getUser·p0.95:   9.404 ms/op
                 getUser·p0.99:   12.763 ms/op
                 getUser·p0.999:  23.495 ms/op
                 getUser·p0.9999: 35.198 ms/op
                 getUser·p1.00:   36.635 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 159092
  mean =      6.027 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 45932 
    [ 5.000,  7.500) = 93553 
    [ 7.500, 10.000) = 14355 
    [10.000, 12.500) = 3358 
    [12.500, 15.000) = 1085 
    [15.000, 17.500) = 391 
    [17.500, 20.000) = 134 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 60 
    [35.000, 37.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      5.579 ms/op
     p(90.0000) =      7.922 ms/op
     p(95.0000) =      9.191 ms/op
     p(99.0000) =     13.009 ms/op
     p(99.9000) =     27.131 ms/op
     p(99.9900) =     35.401 ms/op
     p(99.9990) =     36.688 ms/op
     p(99.9999) =     36.766 ms/op
    p(100.0000) =     36.766 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 23.577 ±(99.9%) 0.418 ms/op
# Warmup Iteration   2: 9.552 ±(99.9%) 0.080 ms/op
# Warmup Iteration   3: 7.337 ±(99.9%) 0.034 ms/op
Iteration   1: 7.104 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   2.589 ms/op
                 listUser·p0.50:   6.627 ms/op
                 listUser·p0.90:   9.241 ms/op
                 listUser·p0.95:   10.551 ms/op
                 listUser·p0.99:   14.106 ms/op
                 listUser·p0.999:  28.475 ms/op
                 listUser·p0.9999: 32.981 ms/op
                 listUser·p1.00:   33.554 ms/op

Iteration   2: 7.030 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   3.043 ms/op
                 listUser·p0.50:   6.554 ms/op
                 listUser·p0.90:   9.011 ms/op
                 listUser·p0.95:   10.240 ms/op
                 listUser·p0.99:   13.648 ms/op
                 listUser·p0.999:  28.392 ms/op
                 listUser·p0.9999: 35.661 ms/op
                 listUser·p1.00:   36.045 ms/op

Iteration   3: 7.033 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   0.587 ms/op
                 listUser·p0.50:   6.726 ms/op
                 listUser·p0.90:   8.831 ms/op
                 listUser·p0.95:   9.929 ms/op
                 listUser·p0.99:   12.993 ms/op
                 listUser·p0.999:  25.956 ms/op
                 listUser·p0.9999: 36.218 ms/op
                 listUser·p1.00:   39.125 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 135955
  mean =      7.055 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 2644 
    [ 5.000,  7.500) = 97794 
    [ 7.500, 10.000) = 27571 
    [10.000, 12.500) = 5573 
    [12.500, 15.000) = 1621 
    [15.000, 17.500) = 379 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.587 ms/op
     p(50.0000) =      6.636 ms/op
     p(90.0000) =      9.028 ms/op
     p(95.0000) =     10.256 ms/op
     p(99.0000) =     13.664 ms/op
     p(99.9000) =     27.984 ms/op
     p(99.9900) =     35.260 ms/op
     p(99.9990) =     38.253 ms/op
     p(99.9999) =     39.125 ms/op
    p(100.0000) =     39.125 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.073 ± 4.967  ops/ms
ClientPb.existUser                       thrpt       3   5.652 ± 3.720  ops/ms
ClientPb.getUser                         thrpt       3   5.431 ± 1.863  ops/ms
ClientPb.listUser                        thrpt       3   4.626 ± 3.381  ops/ms
ClientPb.createUser                       avgt       3   6.101 ± 1.887   ms/op
ClientPb.existUser                        avgt       3   5.645 ± 2.801   ms/op
ClientPb.getUser                          avgt       3   5.907 ± 1.305   ms/op
ClientPb.listUser                         avgt       3   7.019 ± 3.265   ms/op
ClientPb.createUser                     sample  161233   5.949 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.445           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.530           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.627           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.618           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.600           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.740           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.841           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.814           ms/op
ClientPb.existUser                      sample  163343   5.876 ± 0.014   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.343           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.538           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.643           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.684           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.436           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.107           ms/op
ClientPb.existUser:existUser·p0.9999    sample          38.382           ms/op
ClientPb.existUser:existUser·p1.00      sample          41.419           ms/op
ClientPb.getUser                        sample  159092   6.027 ± 0.016   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.826           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.579           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.922           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.191           ms/op
ClientPb.getUser:getUser·p0.99          sample          13.009           ms/op
ClientPb.getUser:getUser·p0.999         sample          27.131           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.401           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.766           ms/op
ClientPb.listUser                       sample  135955   7.055 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.587           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.636           ms/op
ClientPb.listUser:listUser·p0.90        sample           9.028           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.256           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.664           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.984           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.260           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.125           ms/op
