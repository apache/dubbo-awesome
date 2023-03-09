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
# Warmup Iteration   1: 2.527 ops/ms
# Warmup Iteration   2: 6.284 ops/ms
# Warmup Iteration   3: 9.529 ops/ms
Iteration   1: 10.137 ops/ms
Iteration   2: 9.632 ops/ms
Iteration   3: 9.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.882 ±(99.9%) 4.602 ops/ms [Average]
  (min, avg, max) = (9.632, 9.882, 10.137), stdev = 0.252
  CI (99.9%): [5.280, 14.484] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.887 ops/ms
# Warmup Iteration   2: 9.254 ops/ms
# Warmup Iteration   3: 10.217 ops/ms
Iteration   1: 10.129 ops/ms
Iteration   2: 10.699 ops/ms
Iteration   3: 10.258 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.362 ±(99.9%) 5.449 ops/ms [Average]
  (min, avg, max) = (10.129, 10.362, 10.699), stdev = 0.299
  CI (99.9%): [4.913, 15.812] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.468 ops/ms
# Warmup Iteration   2: 8.903 ops/ms
# Warmup Iteration   3: 9.954 ops/ms
Iteration   1: 9.838 ops/ms
Iteration   2: 9.878 ops/ms
Iteration   3: 10.256 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.991 ±(99.9%) 4.216 ops/ms [Average]
  (min, avg, max) = (9.838, 9.991, 10.256), stdev = 0.231
  CI (99.9%): [5.775, 14.206] (assumes normal distribution)


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
# Warmup Iteration   1: 3.345 ops/ms
# Warmup Iteration   2: 7.756 ops/ms
# Warmup Iteration   3: 8.438 ops/ms
Iteration   1: 8.590 ops/ms
Iteration   2: 8.336 ops/ms
Iteration   3: 8.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.498 ±(99.9%) 2.564 ops/ms [Average]
  (min, avg, max) = (8.336, 8.498, 8.590), stdev = 0.141
  CI (99.9%): [5.933, 11.062] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.462 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.393 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.352 ±(99.9%) 0.008 ms/op
Iteration   1: 3.171 ±(99.9%) 0.007 ms/op
Iteration   2: 3.152 ±(99.9%) 0.010 ms/op
Iteration   3: 3.131 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.151 ±(99.9%) 0.364 ms/op [Average]
  (min, avg, max) = (3.131, 3.151, 3.171), stdev = 0.020
  CI (99.9%): [2.787, 3.516] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.264 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.283 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.004 ms/op
Iteration   1: 2.992 ±(99.9%) 0.002 ms/op
Iteration   2: 3.065 ±(99.9%) 0.005 ms/op
Iteration   3: 3.029 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.028 ±(99.9%) 0.672 ms/op [Average]
  (min, avg, max) = (2.992, 3.028, 3.065), stdev = 0.037
  CI (99.9%): [2.357, 3.700] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.206 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.416 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.368 ±(99.9%) 0.002 ms/op
Iteration   1: 3.107 ±(99.9%) 0.005 ms/op
Iteration   2: 3.165 ±(99.9%) 0.004 ms/op
Iteration   3: 3.116 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.129 ±(99.9%) 0.568 ms/op [Average]
  (min, avg, max) = (3.107, 3.129, 3.165), stdev = 0.031
  CI (99.9%): [2.561, 3.698] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 10.089 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.155 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.853 ±(99.9%) 0.004 ms/op
Iteration   1: 3.713 ±(99.9%) 0.005 ms/op
Iteration   2: 3.779 ±(99.9%) 0.007 ms/op
Iteration   3: 3.714 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.735 ±(99.9%) 0.687 ms/op [Average]
  (min, avg, max) = (3.713, 3.735, 3.779), stdev = 0.038
  CI (99.9%): [3.048, 4.422] (assumes normal distribution)


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
# Warmup Iteration   1: 7.882 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.679 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.248 ±(99.9%) 0.009 ms/op
Iteration   1: 3.206 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.139 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   6.021 ms/op
                 createUser·p0.999:  17.990 ms/op
                 createUser·p0.9999: 20.644 ms/op
                 createUser·p1.00:   22.151 ms/op

Iteration   2: 3.134 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.278 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  12.714 ms/op
                 createUser·p0.9999: 22.472 ms/op
                 createUser·p1.00:   24.478 ms/op

Iteration   3: 3.082 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.780 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.359 ms/op
                 createUser·p0.95:   3.621 ms/op
                 createUser·p0.99:   4.891 ms/op
                 createUser·p0.999:  15.028 ms/op
                 createUser·p0.9999: 26.780 ms/op
                 createUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 305438
  mean =      3.140 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10425 
    [ 2.500,  5.000) = 290356 
    [ 5.000,  7.500) = 3460 
    [ 7.500, 10.000) = 727 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 142 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.780 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     16.040 ms/op
     p(99.9900) =     24.606 ms/op
     p(99.9990) =     27.523 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


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
# Warmup Iteration   1: 6.883 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.276 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.007 ms/op
Iteration   1: 3.065 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.165 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.170 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  13.189 ms/op
                 existUser·p0.9999: 18.344 ms/op
                 existUser·p1.00:   18.940 ms/op

Iteration   2: 3.133 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.405 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  9.306 ms/op
                 existUser·p0.9999: 19.530 ms/op
                 existUser·p1.00:   20.611 ms/op

Iteration   3: 3.079 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.933 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.256 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  8.585 ms/op
                 existUser·p0.9999: 19.898 ms/op
                 existUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310340
  mean =      3.092 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34848 
    [ 2.500,  5.000) = 269832 
    [ 5.000,  7.500) = 4969 
    [ 7.500, 10.000) = 326 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 140 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.933 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.260 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     13.140 ms/op
     p(99.9900) =     19.235 ms/op
     p(99.9990) =     20.513 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


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
# Warmup Iteration   1: 8.464 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.493 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.319 ±(99.9%) 0.009 ms/op
Iteration   1: 3.273 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.524 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   6.150 ms/op
                 getUser·p0.999:  15.516 ms/op
                 getUser·p0.9999: 19.536 ms/op
                 getUser·p1.00:   23.233 ms/op

Iteration   2: 3.082 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.788 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.359 ms/op
                 getUser·p0.95:   3.506 ms/op
                 getUser·p0.99:   4.968 ms/op
                 getUser·p0.999:  10.720 ms/op
                 getUser·p0.9999: 21.811 ms/op
                 getUser·p1.00:   22.741 ms/op

Iteration   3: 3.196 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.554 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  12.780 ms/op
                 getUser·p0.9999: 18.940 ms/op
                 getUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 301469
  mean =      3.182 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9436 
    [ 2.500,  5.000) = 285637 
    [ 5.000,  7.500) = 5319 
    [ 7.500, 10.000) = 526 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     13.890 ms/op
     p(99.9900) =     21.065 ms/op
     p(99.9990) =     23.096 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


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
# Warmup Iteration   1: 9.599 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.947 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.816 ±(99.9%) 0.013 ms/op
Iteration   1: 3.706 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.544 ms/op
                 listUser·p0.50:   3.555 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  15.167 ms/op
                 listUser·p0.9999: 26.849 ms/op
                 listUser·p1.00:   29.524 ms/op

Iteration   2: 3.726 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.898 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   6.821 ms/op
                 listUser·p0.999:  12.501 ms/op
                 listUser·p0.9999: 14.270 ms/op
                 listUser·p1.00:   14.303 ms/op

Iteration   3: 3.766 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.880 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.178 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  13.418 ms/op
                 listUser·p0.9999: 19.596 ms/op
                 listUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257062
  mean =      3.732 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 77 
    [ 2.500,  5.000) = 249049 
    [ 5.000,  7.500) = 6140 
    [ 7.500, 10.000) = 1070 
    [10.000, 12.500) = 284 
    [12.500, 15.000) = 321 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.544 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     13.810 ms/op
     p(99.9900) =     24.773 ms/op
     p(99.9990) =     29.337 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.882 ± 4.602  ops/ms
ClientPb.existUser                       thrpt       3  10.362 ± 5.449  ops/ms
ClientPb.getUser                         thrpt       3   9.991 ± 4.216  ops/ms
ClientPb.listUser                        thrpt       3   8.498 ± 2.564  ops/ms
ClientPb.createUser                       avgt       3   3.151 ± 0.364   ms/op
ClientPb.existUser                        avgt       3   3.028 ± 0.672   ms/op
ClientPb.getUser                          avgt       3   3.129 ± 0.568   ms/op
ClientPb.listUser                         avgt       3   3.735 ± 0.687   ms/op
ClientPb.createUser                     sample  305438   3.140 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.780           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.015           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.502           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.439           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.040           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.606           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.705           ms/op
ClientPb.existUser                      sample  310340   3.092 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.933           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.641           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.448           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.140           ms/op
ClientPb.existUser:existUser·p0.9999    sample          19.235           ms/op
ClientPb.existUser:existUser·p1.00      sample          20.611           ms/op
ClientPb.getUser                        sample  301469   3.182 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.788           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.498           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.752           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.784           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.890           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.065           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.233           ms/op
ClientPb.listUser                       sample  257062   3.732 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.544           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.637           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.063           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.791           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.810           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.773           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.524           ms/op
