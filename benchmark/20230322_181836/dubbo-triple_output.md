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
# Warmup Iteration   1: 1.108 ops/ms
# Warmup Iteration   2: 2.680 ops/ms
# Warmup Iteration   3: 5.421 ops/ms
Iteration   1: 5.428 ops/ms
Iteration   2: 6.034 ops/ms
Iteration   3: 5.983 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.815 ±(99.9%) 6.132 ops/ms [Average]
  (min, avg, max) = (5.428, 5.815, 6.034), stdev = 0.336
  CI (99.9%): [≈ 0, 11.947] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.839 ops/ms
# Warmup Iteration   2: 4.762 ops/ms
# Warmup Iteration   3: 6.131 ops/ms
Iteration   1: 6.253 ops/ms
Iteration   2: 6.556 ops/ms
Iteration   3: 6.397 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.402 ±(99.9%) 2.763 ops/ms [Average]
  (min, avg, max) = (6.253, 6.402, 6.556), stdev = 0.151
  CI (99.9%): [3.639, 9.165] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.719 ops/ms
# Warmup Iteration   2: 5.042 ops/ms
# Warmup Iteration   3: 6.111 ops/ms
Iteration   1: 6.189 ops/ms
Iteration   2: 5.790 ops/ms
Iteration   3: 5.919 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.966 ±(99.9%) 3.712 ops/ms [Average]
  (min, avg, max) = (5.790, 5.966, 6.189), stdev = 0.203
  CI (99.9%): [2.254, 9.678] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.672 ops/ms
# Warmup Iteration   2: 4.441 ops/ms
# Warmup Iteration   3: 5.405 ops/ms
Iteration   1: 5.267 ops/ms
Iteration   2: 5.788 ops/ms
Iteration   3: 5.392 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.482 ±(99.9%) 4.963 ops/ms [Average]
  (min, avg, max) = (5.267, 5.482, 5.788), stdev = 0.272
  CI (99.9%): [0.519, 10.445] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 18.602 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 6.371 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.539 ±(99.9%) 0.012 ms/op
Iteration   1: 5.111 ±(99.9%) 0.020 ms/op
Iteration   2: 5.101 ±(99.9%) 0.024 ms/op
Iteration   3: 5.071 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.094 ±(99.9%) 0.374 ms/op [Average]
  (min, avg, max) = (5.071, 5.094, 5.111), stdev = 0.020
  CI (99.9%): [4.721, 5.468] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 17.468 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 5.824 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.127 ±(99.9%) 0.013 ms/op
Iteration   1: 4.907 ±(99.9%) 0.010 ms/op
Iteration   2: 4.831 ±(99.9%) 0.009 ms/op
Iteration   3: 4.769 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.836 ±(99.9%) 1.259 ms/op [Average]
  (min, avg, max) = (4.769, 4.836, 4.907), stdev = 0.069
  CI (99.9%): [3.577, 6.095] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 16.935 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.928 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.179 ±(99.9%) 0.006 ms/op
Iteration   1: 5.174 ±(99.9%) 0.010 ms/op
Iteration   2: 5.094 ±(99.9%) 0.007 ms/op
Iteration   3: 5.123 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.130 ±(99.9%) 0.746 ms/op [Average]
  (min, avg, max) = (5.094, 5.130, 5.174), stdev = 0.041
  CI (99.9%): [4.385, 5.876] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 17.736 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 7.154 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 6.169 ±(99.9%) 0.012 ms/op
Iteration   1: 5.992 ±(99.9%) 0.015 ms/op
Iteration   2: 5.924 ±(99.9%) 0.017 ms/op
Iteration   3: 6.088 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.001 ±(99.9%) 1.501 ms/op [Average]
  (min, avg, max) = (5.924, 6.001, 6.088), stdev = 0.082
  CI (99.9%): [4.501, 7.502] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 17.126 ±(99.9%) 0.253 ms/op
# Warmup Iteration   2: 6.692 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.577 ±(99.9%) 0.023 ms/op
Iteration   1: 5.225 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.700 ms/op
                 createUser·p0.50:   4.858 ms/op
                 createUser·p0.90:   6.488 ms/op
                 createUser·p0.95:   7.676 ms/op
                 createUser·p0.99:   10.453 ms/op
                 createUser·p0.999:  22.722 ms/op
                 createUser·p0.9999: 27.051 ms/op
                 createUser·p1.00:   28.246 ms/op

Iteration   2: 5.454 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.542 ms/op
                 createUser·p0.50:   5.030 ms/op
                 createUser·p0.90:   7.021 ms/op
                 createUser·p0.95:   8.356 ms/op
                 createUser·p0.99:   11.436 ms/op
                 createUser·p0.999:  24.093 ms/op
                 createUser·p0.9999: 28.665 ms/op
                 createUser·p1.00:   31.556 ms/op

Iteration   3: 5.298 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.868 ms/op
                 createUser·p0.50:   4.973 ms/op
                 createUser·p0.90:   6.447 ms/op
                 createUser·p0.95:   7.496 ms/op
                 createUser·p0.99:   10.846 ms/op
                 createUser·p0.999:  25.679 ms/op
                 createUser·p0.9999: 31.785 ms/op
                 createUser·p1.00:   32.506 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 180159
  mean =      5.324 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 94727 
    [ 5.000,  7.500) = 74492 
    [ 7.500, 10.000) = 8137 
    [10.000, 12.500) = 1851 
    [12.500, 15.000) = 439 
    [15.000, 17.500) = 249 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.542 ms/op
     p(50.0000) =      4.956 ms/op
     p(90.0000) =      6.619 ms/op
     p(95.0000) =      7.840 ms/op
     p(99.0000) =     10.928 ms/op
     p(99.9000) =     23.195 ms/op
     p(99.9900) =     30.539 ms/op
     p(99.9990) =     32.217 ms/op
     p(99.9999) =     32.506 ms/op
    p(100.0000) =     32.506 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.348 ±(99.9%) 0.265 ms/op
# Warmup Iteration   2: 5.755 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.936 ±(99.9%) 0.014 ms/op
Iteration   1: 5.008 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.056 ms/op
                 existUser·p0.50:   4.694 ms/op
                 existUser·p0.90:   6.193 ms/op
                 existUser·p0.95:   7.217 ms/op
                 existUser·p0.99:   9.011 ms/op
                 existUser·p0.999:  19.335 ms/op
                 existUser·p0.9999: 23.476 ms/op
                 existUser·p1.00:   24.216 ms/op

Iteration   2: 4.972 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.122 ms/op
                 existUser·p0.50:   4.661 ms/op
                 existUser·p0.90:   6.095 ms/op
                 existUser·p0.95:   7.053 ms/op
                 existUser·p0.99:   9.552 ms/op
                 existUser·p0.999:  20.950 ms/op
                 existUser·p0.9999: 27.183 ms/op
                 existUser·p1.00:   27.656 ms/op

Iteration   3: 5.066 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.692 ms/op
                 existUser·p0.50:   4.784 ms/op
                 existUser·p0.90:   6.365 ms/op
                 existUser·p0.95:   7.152 ms/op
                 existUser·p0.99:   9.058 ms/op
                 existUser·p0.999:  21.950 ms/op
                 existUser·p0.9999: 28.949 ms/op
                 existUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 191496
  mean =      5.015 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 130712 
    [ 5.000,  7.500) = 53359 
    [ 7.500, 10.000) = 6068 
    [10.000, 12.500) = 792 
    [12.500, 15.000) = 200 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.692 ms/op
     p(50.0000) =      4.710 ms/op
     p(90.0000) =      6.218 ms/op
     p(95.0000) =      7.135 ms/op
     p(99.0000) =      9.224 ms/op
     p(99.9000) =     20.070 ms/op
     p(99.9900) =     27.828 ms/op
     p(99.9990) =     30.327 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 16.046 ±(99.9%) 0.245 ms/op
# Warmup Iteration   2: 5.718 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.319 ±(99.9%) 0.020 ms/op
Iteration   1: 5.493 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.249 ms/op
                 getUser·p0.50:   5.038 ms/op
                 getUser·p0.90:   6.963 ms/op
                 getUser·p0.95:   8.421 ms/op
                 getUser·p0.99:   12.340 ms/op
                 getUser·p0.999:  23.116 ms/op
                 getUser·p0.9999: 30.179 ms/op
                 getUser·p1.00:   30.900 ms/op

Iteration   2: 5.215 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.728 ms/op
                 getUser·p0.50:   4.825 ms/op
                 getUser·p0.90:   6.521 ms/op
                 getUser·p0.95:   7.635 ms/op
                 getUser·p0.99:   10.811 ms/op
                 getUser·p0.999:  22.688 ms/op
                 getUser·p0.9999: 27.460 ms/op
                 getUser·p1.00:   27.918 ms/op

Iteration   3: 5.061 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.540 ms/op
                 getUser·p0.50:   4.850 ms/op
                 getUser·p0.90:   6.046 ms/op
                 getUser·p0.95:   6.652 ms/op
                 getUser·p0.99:   8.471 ms/op
                 getUser·p0.999:  26.227 ms/op
                 getUser·p0.9999: 29.866 ms/op
                 getUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 182622
  mean =      5.250 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 102949 
    [ 5.000,  7.500) = 70525 
    [ 7.500, 10.000) = 6996 
    [10.000, 12.500) = 1166 
    [12.500, 15.000) = 454 
    [15.000, 17.500) = 237 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 69 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.540 ms/op
     p(50.0000) =      4.882 ms/op
     p(90.0000) =      6.529 ms/op
     p(95.0000) =      7.504 ms/op
     p(99.0000) =     10.568 ms/op
     p(99.9000) =     23.036 ms/op
     p(99.9900) =     29.819 ms/op
     p(99.9990) =     30.846 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


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
# Warmup Iteration   1: 18.423 ±(99.9%) 0.277 ms/op
# Warmup Iteration   2: 7.119 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.898 ±(99.9%) 0.023 ms/op
Iteration   1: 6.292 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.826 ms/op
                 listUser·p0.50:   5.784 ms/op
                 listUser·p0.90:   8.307 ms/op
                 listUser·p0.95:   9.667 ms/op
                 listUser·p0.99:   12.828 ms/op
                 listUser·p0.999:  25.670 ms/op
                 listUser·p0.9999: 29.423 ms/op
                 listUser·p1.00:   29.819 ms/op

Iteration   2: 6.199 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.946 ms/op
                 listUser·p0.50:   5.816 ms/op
                 listUser·p0.90:   7.561 ms/op
                 listUser·p0.95:   8.880 ms/op
                 listUser·p0.99:   13.094 ms/op
                 listUser·p0.999:  27.525 ms/op
                 listUser·p0.9999: 29.964 ms/op
                 listUser·p1.00:   31.064 ms/op

Iteration   3: 6.051 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.974 ms/op
                 listUser·p0.50:   5.751 ms/op
                 listUser·p0.90:   7.127 ms/op
                 listUser·p0.95:   8.290 ms/op
                 listUser·p0.99:   11.698 ms/op
                 listUser·p0.999:  20.457 ms/op
                 listUser·p0.9999: 26.069 ms/op
                 listUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 155236
  mean =      6.179 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 12009 
    [ 5.000,  7.500) = 126663 
    [ 7.500, 10.000) = 11801 
    [10.000, 12.500) = 3139 
    [12.500, 15.000) = 977 
    [15.000, 17.500) = 245 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 98 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.946 ms/op
     p(50.0000) =      5.784 ms/op
     p(90.0000) =      7.619 ms/op
     p(95.0000) =      9.028 ms/op
     p(99.0000) =     12.599 ms/op
     p(99.9000) =     25.486 ms/op
     p(99.9900) =     29.491 ms/op
     p(99.9990) =     30.992 ms/op
     p(99.9999) =     31.064 ms/op
    p(100.0000) =     31.064 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.815 ± 6.132  ops/ms
ClientPb.existUser                       thrpt       3   6.402 ± 2.763  ops/ms
ClientPb.getUser                         thrpt       3   5.966 ± 3.712  ops/ms
ClientPb.listUser                        thrpt       3   5.482 ± 4.963  ops/ms
ClientPb.createUser                       avgt       3   5.094 ± 0.374   ms/op
ClientPb.existUser                        avgt       3   4.836 ± 1.259   ms/op
ClientPb.getUser                          avgt       3   5.130 ± 0.746   ms/op
ClientPb.listUser                         avgt       3   6.001 ± 1.501   ms/op
ClientPb.createUser                     sample  180159   5.324 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.542           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.956           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.619           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.840           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.928           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.195           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.539           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.506           ms/op
ClientPb.existUser                      sample  191496   5.015 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.692           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.710           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.218           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.135           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.224           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.070           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.828           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.507           ms/op
ClientPb.getUser                        sample  182622   5.250 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.540           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.882           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.529           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.504           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.568           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.036           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.819           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.900           ms/op
ClientPb.listUser                       sample  155236   6.179 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.946           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.784           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.619           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.028           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.599           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.486           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.491           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.064           ms/op
