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
# Warmup Iteration   1: 1.991 ops/ms
# Warmup Iteration   2: 4.858 ops/ms
# Warmup Iteration   3: 8.396 ops/ms
Iteration   1: 9.127 ops/ms
Iteration   2: 9.236 ops/ms
Iteration   3: 9.227 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.197 ±(99.9%) 1.109 ops/ms [Average]
  (min, avg, max) = (9.127, 9.197, 9.236), stdev = 0.061
  CI (99.9%): [8.087, 10.306] (assumes normal distribution)


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
# Warmup Iteration   1: 2.601 ops/ms
# Warmup Iteration   2: 8.320 ops/ms
# Warmup Iteration   3: 9.426 ops/ms
Iteration   1: 9.467 ops/ms
Iteration   2: 9.661 ops/ms
Iteration   3: 9.731 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.620 ±(99.9%) 2.493 ops/ms [Average]
  (min, avg, max) = (9.467, 9.620, 9.731), stdev = 0.137
  CI (99.9%): [7.127, 12.113] (assumes normal distribution)


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
# Warmup Iteration   1: 2.924 ops/ms
# Warmup Iteration   2: 8.294 ops/ms
# Warmup Iteration   3: 8.893 ops/ms
Iteration   1: 9.380 ops/ms
Iteration   2: 9.176 ops/ms
Iteration   3: 9.500 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.352 ±(99.9%) 2.983 ops/ms [Average]
  (min, avg, max) = (9.176, 9.352, 9.500), stdev = 0.164
  CI (99.9%): [6.369, 12.335] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.369 ops/ms
# Warmup Iteration   2: 6.894 ops/ms
# Warmup Iteration   3: 7.583 ops/ms
Iteration   1: 7.856 ops/ms
Iteration   2: 7.720 ops/ms
Iteration   3: 7.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.776 ±(99.9%) 1.307 ops/ms [Average]
  (min, avg, max) = (7.720, 7.776, 7.856), stdev = 0.072
  CI (99.9%): [6.469, 9.082] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 9.737 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.866 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.585 ±(99.9%) 0.007 ms/op
Iteration   1: 3.419 ±(99.9%) 0.009 ms/op
Iteration   2: 3.514 ±(99.9%) 0.005 ms/op
Iteration   3: 3.496 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.476 ±(99.9%) 0.927 ms/op [Average]
  (min, avg, max) = (3.419, 3.476, 3.514), stdev = 0.051
  CI (99.9%): [2.550, 4.403] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.808 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.661 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.342 ±(99.9%) 0.008 ms/op
Iteration   1: 3.317 ±(99.9%) 0.005 ms/op
Iteration   2: 3.228 ±(99.9%) 0.008 ms/op
Iteration   3: 3.288 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.278 ±(99.9%) 0.822 ms/op [Average]
  (min, avg, max) = (3.228, 3.278, 3.317), stdev = 0.045
  CI (99.9%): [2.455, 4.100] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.970 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.699 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.532 ±(99.9%) 0.004 ms/op
Iteration   1: 3.423 ±(99.9%) 0.004 ms/op
Iteration   2: 3.422 ±(99.9%) 0.007 ms/op
Iteration   3: 3.601 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.482 ±(99.9%) 1.878 ms/op [Average]
  (min, avg, max) = (3.422, 3.482, 3.601), stdev = 0.103
  CI (99.9%): [1.604, 5.359] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.908 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.394 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.103 ±(99.9%) 0.011 ms/op
Iteration   1: 4.154 ±(99.9%) 0.010 ms/op
Iteration   2: 3.967 ±(99.9%) 0.012 ms/op
Iteration   3: 3.990 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.037 ±(99.9%) 1.866 ms/op [Average]
  (min, avg, max) = (3.967, 4.037, 4.154), stdev = 0.102
  CI (99.9%): [2.171, 5.903] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 9.326 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.048 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.480 ±(99.9%) 0.010 ms/op
Iteration   1: 3.493 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.692 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   6.130 ms/op
                 createUser·p0.999:  22.807 ms/op
                 createUser·p0.9999: 24.739 ms/op
                 createUser·p1.00:   26.214 ms/op

Iteration   2: 3.348 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.370 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  24.936 ms/op
                 createUser·p0.9999: 28.621 ms/op
                 createUser·p1.00:   30.278 ms/op

Iteration   3: 3.513 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.774 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.998 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   6.327 ms/op
                 createUser·p0.999:  18.153 ms/op
                 createUser·p0.9999: 29.193 ms/op
                 createUser·p1.00:   29.917 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277872
  mean =      3.450 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4556 
    [ 2.500,  5.000) = 266888 
    [ 5.000,  7.500) = 5159 
    [ 7.500, 10.000) = 652 
    [10.000, 12.500) = 215 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.046 ms/op
     p(99.9000) =     19.173 ms/op
     p(99.9900) =     28.810 ms/op
     p(99.9990) =     30.033 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


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
# Warmup Iteration   1: 8.778 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.615 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.489 ±(99.9%) 0.009 ms/op
Iteration   1: 3.404 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.432 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.883 ms/op
                 existUser·p0.95:   4.702 ms/op
                 existUser·p0.99:   5.866 ms/op
                 existUser·p0.999:  20.877 ms/op
                 existUser·p0.9999: 24.674 ms/op
                 existUser·p1.00:   25.494 ms/op

Iteration   2: 3.385 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.462 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   4.018 ms/op
                 existUser·p0.99:   5.807 ms/op
                 existUser·p0.999:  22.839 ms/op
                 existUser·p0.9999: 26.953 ms/op
                 existUser·p1.00:   27.656 ms/op

Iteration   3: 3.426 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.784 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.838 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   6.007 ms/op
                 existUser·p0.999:  10.289 ms/op
                 existUser·p0.9999: 29.710 ms/op
                 existUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281681
  mean =      3.405 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3620 
    [ 2.500,  5.000) = 271618 
    [ 5.000,  7.500) = 5383 
    [ 7.500, 10.000) = 639 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 112 
    [25.000, 27.500) = 84 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     10.796 ms/op
     p(99.9900) =     28.639 ms/op
     p(99.9990) =     30.275 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.303 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 3.901 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.697 ±(99.9%) 0.012 ms/op
Iteration   1: 3.457 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.968 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   6.087 ms/op
                 getUser·p0.999:  21.331 ms/op
                 getUser·p0.9999: 25.592 ms/op
                 getUser·p1.00:   26.903 ms/op

Iteration   2: 3.679 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.395 ms/op
                 getUser·p0.50:   3.523 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   4.776 ms/op
                 getUser·p0.99:   6.562 ms/op
                 getUser·p0.999:  23.072 ms/op
                 getUser·p0.9999: 28.069 ms/op
                 getUser·p1.00:   29.262 ms/op

Iteration   3: 3.593 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.421 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   4.653 ms/op
                 getUser·p0.99:   6.971 ms/op
                 getUser·p0.999:  15.172 ms/op
                 getUser·p0.9999: 40.501 ms/op
                 getUser·p1.00:   40.960 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 268453
  mean =      3.574 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 259319 
    [ 5.000, 10.000) = 8694 
    [10.000, 15.000) = 156 
    [15.000, 20.000) = 28 
    [20.000, 25.000) = 130 
    [25.000, 30.000) = 94 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 17 
    [40.000, 45.000) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.395 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =     15.222 ms/op
     p(99.9900) =     37.300 ms/op
     p(99.9990) =     40.632 ms/op
     p(99.9999) =     40.960 ms/op
    p(100.0000) =     40.960 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.817 ±(99.9%) 0.180 ms/op
# Warmup Iteration   2: 4.997 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.135 ±(99.9%) 0.014 ms/op
Iteration   1: 4.131 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.077 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   4.907 ms/op
                 listUser·p0.99:   7.520 ms/op
                 listUser·p0.999:  21.934 ms/op
                 listUser·p0.9999: 25.740 ms/op
                 listUser·p1.00:   26.116 ms/op

Iteration   2: 4.137 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.105 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   7.447 ms/op
                 listUser·p0.999:  16.068 ms/op
                 listUser·p0.9999: 25.133 ms/op
                 listUser·p1.00:   25.133 ms/op

Iteration   3: 4.149 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.933 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   7.594 ms/op
                 listUser·p0.999:  14.792 ms/op
                 listUser·p0.9999: 16.744 ms/op
                 listUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 231857
  mean =      4.139 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 221647 
    [ 5.000,  7.500) = 7836 
    [ 7.500, 10.000) = 1451 
    [10.000, 12.500) = 268 
    [12.500, 15.000) = 220 
    [15.000, 17.500) = 207 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.933 ms/op
     p(50.0000) =      3.973 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      7.512 ms/op
     p(99.9000) =     16.424 ms/op
     p(99.9900) =     25.133 ms/op
     p(99.9990) =     26.073 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.197 ± 1.109  ops/ms
ClientPb.existUser                       thrpt       3   9.620 ± 2.493  ops/ms
ClientPb.getUser                         thrpt       3   9.352 ± 2.983  ops/ms
ClientPb.listUser                        thrpt       3   7.776 ± 1.307  ops/ms
ClientPb.createUser                       avgt       3   3.476 ± 0.927   ms/op
ClientPb.existUser                        avgt       3   3.278 ± 0.822   ms/op
ClientPb.getUser                          avgt       3   3.482 ± 1.878   ms/op
ClientPb.listUser                         avgt       3   4.037 ± 1.866   ms/op
ClientPb.createUser                     sample  277872   3.450 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.774           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.297           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.912           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.046           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.173           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.810           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.278           ms/op
ClientPb.existUser                      sample  281681   3.405 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.784           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.281           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.366           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.898           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.796           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.639           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.507           ms/op
ClientPb.getUser                        sample  268453   3.574 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.395           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.416           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.157           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.588           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.504           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.222           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.300           ms/op
ClientPb.getUser:getUser·p1.00          sample          40.960           ms/op
ClientPb.listUser                       sample  231857   4.139 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.933           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.973           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.891           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.512           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.424           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.133           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.116           ms/op
