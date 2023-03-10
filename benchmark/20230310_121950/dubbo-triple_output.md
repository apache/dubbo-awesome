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
# Warmup Iteration   1: 2.504 ops/ms
# Warmup Iteration   2: 6.880 ops/ms
# Warmup Iteration   3: 8.568 ops/ms
Iteration   1: 9.361 ops/ms
Iteration   2: 10.290 ops/ms
Iteration   3: 10.459 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.037 ±(99.9%) 10.780 ops/ms [Average]
  (min, avg, max) = (9.361, 10.037, 10.459), stdev = 0.591
  CI (99.9%): [≈ 0, 20.816] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.705 ops/ms
# Warmup Iteration   2: 9.646 ops/ms
# Warmup Iteration   3: 10.232 ops/ms
Iteration   1: 10.781 ops/ms
Iteration   2: 10.416 ops/ms
Iteration   3: 10.366 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.521 ±(99.9%) 4.136 ops/ms [Average]
  (min, avg, max) = (10.366, 10.521, 10.781), stdev = 0.227
  CI (99.9%): [6.385, 14.657] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.606 ops/ms
# Warmup Iteration   2: 8.818 ops/ms
# Warmup Iteration   3: 10.108 ops/ms
Iteration   1: 9.981 ops/ms
Iteration   2: 10.040 ops/ms
Iteration   3: 10.092 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.037 ±(99.9%) 1.017 ops/ms [Average]
  (min, avg, max) = (9.981, 10.037, 10.092), stdev = 0.056
  CI (99.9%): [9.020, 11.054] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 3.600 ops/ms
# Warmup Iteration   2: 8.078 ops/ms
# Warmup Iteration   3: 8.549 ops/ms
Iteration   1: 8.483 ops/ms
Iteration   2: 8.703 ops/ms
Iteration   3: 8.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.644 ±(99.9%) 2.563 ops/ms [Average]
  (min, avg, max) = (8.483, 8.644, 8.745), stdev = 0.140
  CI (99.9%): [6.081, 11.207] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 7.460 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.370 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.203 ±(99.9%) 0.002 ms/op
Iteration   1: 3.292 ±(99.9%) 0.007 ms/op
Iteration   2: 3.211 ±(99.9%) 0.010 ms/op
Iteration   3: 3.266 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.257 ±(99.9%) 0.750 ms/op [Average]
  (min, avg, max) = (3.211, 3.257, 3.292), stdev = 0.041
  CI (99.9%): [2.506, 4.007] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.251 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.241 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.003 ms/op
Iteration   1: 3.069 ±(99.9%) 0.010 ms/op
Iteration   2: 3.094 ±(99.9%) 0.007 ms/op
Iteration   3: 3.035 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.066 ±(99.9%) 0.535 ms/op [Average]
  (min, avg, max) = (3.035, 3.066, 3.094), stdev = 0.029
  CI (99.9%): [2.530, 3.601] (assumes normal distribution)


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
# Warmup Iteration   1: 7.938 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.471 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.431 ±(99.9%) 0.004 ms/op
Iteration   1: 3.034 ±(99.9%) 0.005 ms/op
Iteration   2: 3.074 ±(99.9%) 0.006 ms/op
Iteration   3: 3.154 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.087 ±(99.9%) 1.121 ms/op [Average]
  (min, avg, max) = (3.034, 3.087, 3.154), stdev = 0.061
  CI (99.9%): [1.966, 4.208] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.346 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.079 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.788 ±(99.9%) 0.005 ms/op
Iteration   1: 3.658 ±(99.9%) 0.010 ms/op
Iteration   2: 3.732 ±(99.9%) 0.008 ms/op
Iteration   3: 3.739 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.710 ±(99.9%) 0.817 ms/op [Average]
  (min, avg, max) = (3.658, 3.710, 3.739), stdev = 0.045
  CI (99.9%): [2.893, 4.527] (assumes normal distribution)


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
# Warmup Iteration   1: 7.824 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.601 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.302 ±(99.9%) 0.009 ms/op
Iteration   1: 3.119 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.184 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  13.046 ms/op
                 createUser·p0.9999: 19.521 ms/op
                 createUser·p1.00:   19.890 ms/op

Iteration   2: 3.218 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.934 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   4.162 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  19.501 ms/op
                 createUser·p0.9999: 28.251 ms/op
                 createUser·p1.00:   30.507 ms/op

Iteration   3: 3.098 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.506 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   4.658 ms/op
                 createUser·p0.999:  14.615 ms/op
                 createUser·p0.9999: 19.726 ms/op
                 createUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 304986
  mean =      3.144 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16165 
    [ 2.500,  5.000) = 283551 
    [ 5.000,  7.500) = 4444 
    [ 7.500, 10.000) = 355 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 172 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.506 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =     15.008 ms/op
     p(99.9900) =     26.608 ms/op
     p(99.9990) =     28.900 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.313 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 3.304 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.111 ±(99.9%) 0.007 ms/op
Iteration   1: 3.074 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.069 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  8.388 ms/op
                 existUser·p0.9999: 24.562 ms/op
                 existUser·p1.00:   25.526 ms/op

Iteration   2: 3.020 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.031 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.465 ms/op
                 existUser·p0.99:   5.218 ms/op
                 existUser·p0.999:  16.090 ms/op
                 existUser·p0.9999: 24.059 ms/op
                 existUser·p1.00:   24.478 ms/op

Iteration   3: 3.227 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.946 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   6.119 ms/op
                 existUser·p0.999:  13.270 ms/op
                 existUser·p0.9999: 19.935 ms/op
                 existUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309170
  mean =      3.104 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13239 
    [ 2.500,  5.000) = 289928 
    [ 5.000,  7.500) = 5179 
    [ 7.500, 10.000) = 425 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.946 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     13.511 ms/op
     p(99.9900) =     24.117 ms/op
     p(99.9990) =     25.338 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


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
# Warmup Iteration   1: 6.818 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.511 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.232 ±(99.9%) 0.010 ms/op
Iteration   1: 3.193 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.227 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  11.875 ms/op
                 getUser·p0.9999: 21.626 ms/op
                 getUser·p1.00:   22.315 ms/op

Iteration   2: 3.089 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.346 ms/op
                 getUser·p0.95:   3.465 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  14.074 ms/op
                 getUser·p0.9999: 23.931 ms/op
                 getUser·p1.00:   24.805 ms/op

Iteration   3: 3.157 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.961 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   6.070 ms/op
                 getUser·p0.999:  12.976 ms/op
                 getUser·p0.9999: 24.899 ms/op
                 getUser·p1.00:   25.330 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 305087
  mean =      3.146 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13351 
    [ 2.500,  5.000) = 285361 
    [ 5.000,  7.500) = 5332 
    [ 7.500, 10.000) = 648 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 122 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     12.960 ms/op
     p(99.9900) =     23.855 ms/op
     p(99.9990) =     25.259 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


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
# Warmup Iteration   1: 8.151 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 4.110 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.794 ±(99.9%) 0.011 ms/op
Iteration   1: 3.633 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.800 ms/op
                 listUser·p0.50:   3.506 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.149 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  14.254 ms/op
                 listUser·p0.9999: 22.753 ms/op
                 listUser·p1.00:   23.658 ms/op

Iteration   2: 3.765 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.980 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  13.517 ms/op
                 listUser·p0.9999: 16.908 ms/op
                 listUser·p1.00:   16.974 ms/op

Iteration   3: 3.791 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.138 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   7.487 ms/op
                 listUser·p0.999:  15.679 ms/op
                 listUser·p0.9999: 18.630 ms/op
                 listUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257644
  mean =      3.728 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 80 
    [ 2.500,  5.000) = 249705 
    [ 5.000,  7.500) = 5665 
    [ 7.500, 10.000) = 1407 
    [10.000, 12.500) = 263 
    [12.500, 15.000) = 308 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.800 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     14.468 ms/op
     p(99.9900) =     21.752 ms/op
     p(99.9990) =     22.938 ms/op
     p(99.9999) =     23.658 ms/op
    p(100.0000) =     23.658 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3  10.037 ± 10.780  ops/ms
ClientPb.existUser                       thrpt       3  10.521 ±  4.136  ops/ms
ClientPb.getUser                         thrpt       3  10.037 ±  1.017  ops/ms
ClientPb.listUser                        thrpt       3   8.644 ±  2.563  ops/ms
ClientPb.createUser                       avgt       3   3.257 ±  0.750   ms/op
ClientPb.existUser                        avgt       3   3.066 ±  0.535   ms/op
ClientPb.getUser                          avgt       3   3.087 ±  1.121   ms/op
ClientPb.listUser                         avgt       3   3.710 ±  0.817   ms/op
ClientPb.createUser                     sample  304986   3.144 ±  0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.506            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.047            ms/op
ClientPb.createUser:createUser·p0.90    sample           3.539            ms/op
ClientPb.createUser:createUser·p0.95    sample           3.953            ms/op
ClientPb.createUser:createUser·p0.99    sample           5.358            ms/op
ClientPb.createUser:createUser·p0.999   sample          15.008            ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.608            ms/op
ClientPb.createUser:createUser·p1.00    sample          30.507            ms/op
ClientPb.existUser                      sample  309170   3.104 ±  0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.946            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.006            ms/op
ClientPb.existUser:existUser·p0.90      sample           3.445            ms/op
ClientPb.existUser:existUser·p0.95      sample           3.813            ms/op
ClientPb.existUser:existUser·p0.99      sample           5.415            ms/op
ClientPb.existUser:existUser·p0.999     sample          13.511            ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.117            ms/op
ClientPb.existUser:existUser·p1.00      sample          25.526            ms/op
ClientPb.getUser                        sample  305087   3.146 ±  0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.949            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.039            ms/op
ClientPb.getUser:getUser·p0.90          sample           3.449            ms/op
ClientPb.getUser:getUser·p0.95          sample           3.756            ms/op
ClientPb.getUser:getUser·p0.99          sample           5.702            ms/op
ClientPb.getUser:getUser·p0.999         sample          12.960            ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.855            ms/op
ClientPb.getUser:getUser·p1.00          sample          25.330            ms/op
ClientPb.listUser                       sample  257644   3.728 ±  0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.800            ms/op
ClientPb.listUser:listUser·p0.50        sample           3.621            ms/op
ClientPb.listUser:listUser·p0.90        sample           4.026            ms/op
ClientPb.listUser:listUser·p0.95        sample           4.268            ms/op
ClientPb.listUser:listUser·p0.99        sample           7.201            ms/op
ClientPb.listUser:listUser·p0.999       sample          14.468            ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.752            ms/op
ClientPb.listUser:listUser·p1.00        sample          23.658            ms/op
