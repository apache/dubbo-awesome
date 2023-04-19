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
# Warmup Iteration   1: 1.296 ops/ms
# Warmup Iteration   2: 2.893 ops/ms
# Warmup Iteration   3: 6.565 ops/ms
Iteration   1: 7.284 ops/ms
Iteration   2: 7.451 ops/ms
Iteration   3: 7.809 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.515 ±(99.9%) 4.893 ops/ms [Average]
  (min, avg, max) = (7.284, 7.515, 7.809), stdev = 0.268
  CI (99.9%): [2.621, 12.408] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.963 ops/ms
# Warmup Iteration   2: 5.946 ops/ms
# Warmup Iteration   3: 7.660 ops/ms
Iteration   1: 7.550 ops/ms
Iteration   2: 7.865 ops/ms
Iteration   3: 8.177 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.864 ±(99.9%) 5.715 ops/ms [Average]
  (min, avg, max) = (7.550, 7.864, 8.177), stdev = 0.313
  CI (99.9%): [2.148, 13.579] (assumes normal distribution)


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
# Warmup Iteration   1: 1.992 ops/ms
# Warmup Iteration   2: 5.224 ops/ms
# Warmup Iteration   3: 7.576 ops/ms
Iteration   1: 7.096 ops/ms
Iteration   2: 7.141 ops/ms
Iteration   3: 7.168 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.135 ±(99.9%) 0.664 ops/ms [Average]
  (min, avg, max) = (7.096, 7.135, 7.168), stdev = 0.036
  CI (99.9%): [6.471, 7.799] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.775 ops/ms
# Warmup Iteration   2: 5.229 ops/ms
# Warmup Iteration   3: 6.219 ops/ms
Iteration   1: 5.948 ops/ms
Iteration   2: 6.407 ops/ms
Iteration   3: 6.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.336 ±(99.9%) 6.524 ops/ms [Average]
  (min, avg, max) = (5.948, 6.336, 6.652), stdev = 0.358
  CI (99.9%): [≈ 0, 12.860] (assumes normal distribution)


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
# Warmup Iteration   1: 13.489 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.936 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.400 ±(99.9%) 0.007 ms/op
Iteration   1: 4.217 ±(99.9%) 0.008 ms/op
Iteration   2: 4.146 ±(99.9%) 0.007 ms/op
Iteration   3: 4.266 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.209 ±(99.9%) 1.100 ms/op [Average]
  (min, avg, max) = (4.146, 4.209, 4.266), stdev = 0.060
  CI (99.9%): [3.109, 5.309] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 11.506 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.758 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.037 ±(99.9%) 0.009 ms/op
Iteration   1: 3.932 ±(99.9%) 0.004 ms/op
Iteration   2: 3.895 ±(99.9%) 0.010 ms/op
Iteration   3: 4.017 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.948 ±(99.9%) 1.146 ms/op [Average]
  (min, avg, max) = (3.895, 3.948, 4.017), stdev = 0.063
  CI (99.9%): [2.802, 5.094] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 14.614 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 5.142 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.346 ±(99.9%) 0.006 ms/op
Iteration   1: 4.170 ±(99.9%) 0.010 ms/op
Iteration   2: 4.047 ±(99.9%) 0.011 ms/op
Iteration   3: 4.174 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.130 ±(99.9%) 1.315 ms/op [Average]
  (min, avg, max) = (4.047, 4.130, 4.174), stdev = 0.072
  CI (99.9%): [2.815, 5.446] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 14.357 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 6.178 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.180 ±(99.9%) 0.010 ms/op
Iteration   1: 4.899 ±(99.9%) 0.010 ms/op
Iteration   2: 4.942 ±(99.9%) 0.009 ms/op
Iteration   3: 4.852 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.898 ±(99.9%) 0.824 ms/op [Average]
  (min, avg, max) = (4.852, 4.898, 4.942), stdev = 0.045
  CI (99.9%): [4.073, 5.722] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 14.643 ±(99.9%) 0.257 ms/op
# Warmup Iteration   2: 5.508 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.767 ±(99.9%) 0.020 ms/op
Iteration   1: 4.236 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.124 ms/op
                 createUser·p0.50:   3.936 ms/op
                 createUser·p0.90:   4.923 ms/op
                 createUser·p0.95:   5.612 ms/op
                 createUser·p0.99:   8.733 ms/op
                 createUser·p0.999:  20.388 ms/op
                 createUser·p0.9999: 29.000 ms/op
                 createUser·p1.00:   31.097 ms/op

Iteration   2: 4.077 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   2.021 ms/op
                 createUser·p0.50:   4.039 ms/op
                 createUser·p0.90:   4.383 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   6.799 ms/op
                 createUser·p0.999:  24.150 ms/op
                 createUser·p0.9999: 26.646 ms/op
                 createUser·p1.00:   27.558 ms/op

Iteration   3: 4.201 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   2.073 ms/op
                 createUser·p0.50:   4.092 ms/op
                 createUser·p0.90:   4.686 ms/op
                 createUser·p0.95:   5.366 ms/op
                 createUser·p0.99:   7.767 ms/op
                 createUser·p0.999:  16.509 ms/op
                 createUser·p0.9999: 29.398 ms/op
                 createUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 230083
  mean =      4.170 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 112 
    [ 2.500,  5.000) = 214897 
    [ 5.000,  7.500) = 11911 
    [ 7.500, 10.000) = 2287 
    [10.000, 12.500) = 369 
    [12.500, 15.000) = 152 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 103 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      4.039 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.243 ms/op
     p(99.0000) =      8.094 ms/op
     p(99.9000) =     21.687 ms/op
     p(99.9900) =     28.999 ms/op
     p(99.9990) =     30.717 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.955 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 4.877 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.257 ±(99.9%) 0.015 ms/op
Iteration   1: 4.136 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.671 ms/op
                 existUser·p0.50:   3.912 ms/op
                 existUser·p0.90:   4.522 ms/op
                 existUser·p0.95:   5.431 ms/op
                 existUser·p0.99:   9.159 ms/op
                 existUser·p0.999:  19.815 ms/op
                 existUser·p0.9999: 26.453 ms/op
                 existUser·p1.00:   27.001 ms/op

Iteration   2: 3.990 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.968 ms/op
                 existUser·p0.50:   3.846 ms/op
                 existUser·p0.90:   4.391 ms/op
                 existUser·p0.95:   4.882 ms/op
                 existUser·p0.99:   7.553 ms/op
                 existUser·p0.999:  16.941 ms/op
                 existUser·p0.9999: 27.034 ms/op
                 existUser·p1.00:   27.984 ms/op

Iteration   3: 3.965 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   2.062 ms/op
                 existUser·p0.50:   3.883 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.645 ms/op
                 existUser·p0.99:   6.742 ms/op
                 existUser·p0.999:  28.672 ms/op
                 existUser·p0.9999: 32.471 ms/op
                 existUser·p1.00:   32.866 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 238029
  mean =      4.029 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 140 
    [ 2.500,  5.000) = 226746 
    [ 5.000,  7.500) = 8362 
    [ 7.500, 10.000) = 1686 
    [10.000, 12.500) = 512 
    [12.500, 15.000) = 212 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.671 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      7.807 ms/op
     p(99.9000) =     19.856 ms/op
     p(99.9900) =     30.585 ms/op
     p(99.9990) =     32.821 ms/op
     p(99.9999) =     32.866 ms/op
    p(100.0000) =     32.866 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.553 ±(99.9%) 0.189 ms/op
# Warmup Iteration   2: 5.034 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.489 ±(99.9%) 0.015 ms/op
Iteration   1: 4.541 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.028 ms/op
                 getUser·p0.50:   4.211 ms/op
                 getUser·p0.90:   5.399 ms/op
                 getUser·p0.95:   6.840 ms/op
                 getUser·p0.99:   9.814 ms/op
                 getUser·p0.999:  22.774 ms/op
                 getUser·p0.9999: 29.523 ms/op
                 getUser·p1.00:   30.114 ms/op

Iteration   2: 4.172 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.952 ms/op
                 getUser·p0.50:   4.035 ms/op
                 getUser·p0.90:   4.588 ms/op
                 getUser·p0.95:   4.866 ms/op
                 getUser·p0.99:   7.449 ms/op
                 getUser·p0.999:  26.608 ms/op
                 getUser·p0.9999: 29.950 ms/op
                 getUser·p1.00:   30.736 ms/op

Iteration   3: 4.219 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.780 ms/op
                 getUser·p0.50:   4.039 ms/op
                 getUser·p0.90:   4.710 ms/op
                 getUser·p0.95:   5.251 ms/op
                 getUser·p0.99:   8.618 ms/op
                 getUser·p0.999:  13.292 ms/op
                 getUser·p0.9999: 30.104 ms/op
                 getUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 222878
  mean =      4.305 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 203266 
    [ 5.000,  7.500) = 14979 
    [ 7.500, 10.000) = 3351 
    [10.000, 12.500) = 828 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 114 
    [27.500, 30.000) = 122 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.780 ms/op
     p(50.0000) =      4.092 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      8.962 ms/op
     p(99.9000) =     25.825 ms/op
     p(99.9900) =     29.777 ms/op
     p(99.9990) =     30.835 ms/op
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
# Warmup Iteration   1: 15.936 ±(99.9%) 0.223 ms/op
# Warmup Iteration   2: 6.522 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.130 ±(99.9%) 0.019 ms/op
Iteration   1: 5.005 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.819 ms/op
                 listUser·p0.50:   4.719 ms/op
                 listUser·p0.90:   5.480 ms/op
                 listUser·p0.95:   6.996 ms/op
                 listUser·p0.99:   9.880 ms/op
                 listUser·p0.999:  26.215 ms/op
                 listUser·p0.9999: 28.784 ms/op
                 listUser·p1.00:   29.098 ms/op

Iteration   2: 5.363 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.802 ms/op
                 listUser·p0.50:   5.038 ms/op
                 listUser·p0.90:   6.193 ms/op
                 listUser·p0.95:   7.578 ms/op
                 listUser·p0.99:   10.928 ms/op
                 listUser·p0.999:  25.715 ms/op
                 listUser·p0.9999: 34.084 ms/op
                 listUser·p1.00:   34.603 ms/op

Iteration   3: 5.030 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.789 ms/op
                 listUser·p0.50:   4.809 ms/op
                 listUser·p0.90:   5.792 ms/op
                 listUser·p0.95:   6.398 ms/op
                 listUser·p0.99:   9.339 ms/op
                 listUser·p0.999:  17.968 ms/op
                 listUser·p0.9999: 21.037 ms/op
                 listUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 187272
  mean =      5.127 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 122985 
    [ 5.000,  7.500) = 56550 
    [ 7.500, 10.000) = 5794 
    [10.000, 12.500) = 1145 
    [12.500, 15.000) = 242 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 108 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.819 ms/op
     p(50.0000) =      4.833 ms/op
     p(90.0000) =      5.849 ms/op
     p(95.0000) =      6.988 ms/op
     p(99.0000) =     10.109 ms/op
     p(99.9000) =     24.573 ms/op
     p(99.9900) =     32.515 ms/op
     p(99.9990) =     34.431 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.515 ± 4.893  ops/ms
ClientPb.existUser                       thrpt       3   7.864 ± 5.715  ops/ms
ClientPb.getUser                         thrpt       3   7.135 ± 0.664  ops/ms
ClientPb.listUser                        thrpt       3   6.336 ± 6.524  ops/ms
ClientPb.createUser                       avgt       3   4.209 ± 1.100   ms/op
ClientPb.existUser                        avgt       3   3.948 ± 1.146   ms/op
ClientPb.getUser                          avgt       3   4.130 ± 1.315   ms/op
ClientPb.listUser                         avgt       3   4.898 ± 0.824   ms/op
ClientPb.createUser                     sample  230083   4.170 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.124           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.039           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.694           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.243           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.094           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.687           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.999           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.097           ms/op
ClientPb.existUser                      sample  238029   4.029 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.671           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.875           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.399           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.923           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.807           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.856           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.585           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.866           ms/op
ClientPb.getUser                        sample  222878   4.305 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.780           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.092           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.907           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.571           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.962           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.825           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.777           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.293           ms/op
ClientPb.listUser                       sample  187272   5.127 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.819           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.833           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.849           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.988           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.109           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.573           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.515           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.603           ms/op
