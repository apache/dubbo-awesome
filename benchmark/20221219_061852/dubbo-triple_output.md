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
# Warmup Iteration   1: 2.658 ops/ms
# Warmup Iteration   2: 6.154 ops/ms
# Warmup Iteration   3: 9.582 ops/ms
Iteration   1: 9.850 ops/ms
Iteration   2: 9.887 ops/ms
Iteration   3: 9.775 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.837 ±(99.9%) 1.041 ops/ms [Average]
  (min, avg, max) = (9.775, 9.837, 9.887), stdev = 0.057
  CI (99.9%): [8.796, 10.878] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.734 ops/ms
# Warmup Iteration   2: 9.287 ops/ms
# Warmup Iteration   3: 9.990 ops/ms
Iteration   1: 10.609 ops/ms
Iteration   2: 10.449 ops/ms
Iteration   3: 10.223 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.427 ±(99.9%) 3.535 ops/ms [Average]
  (min, avg, max) = (10.223, 10.427, 10.609), stdev = 0.194
  CI (99.9%): [6.892, 13.962] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.191 ops/ms
# Warmup Iteration   2: 8.958 ops/ms
# Warmup Iteration   3: 9.470 ops/ms
Iteration   1: 10.218 ops/ms
Iteration   2: 9.619 ops/ms
Iteration   3: 10.045 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.961 ±(99.9%) 5.619 ops/ms [Average]
  (min, avg, max) = (9.619, 9.961, 10.218), stdev = 0.308
  CI (99.9%): [4.342, 15.579] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.602 ops/ms
# Warmup Iteration   2: 7.732 ops/ms
# Warmup Iteration   3: 8.107 ops/ms
Iteration   1: 8.505 ops/ms
Iteration   2: 8.176 ops/ms
Iteration   3: 8.473 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.385 ±(99.9%) 3.305 ops/ms [Average]
  (min, avg, max) = (8.176, 8.385, 8.505), stdev = 0.181
  CI (99.9%): [5.080, 11.690] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.634 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.476 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.309 ±(99.9%) 0.005 ms/op
Iteration   1: 3.203 ±(99.9%) 0.007 ms/op
Iteration   2: 3.188 ±(99.9%) 0.003 ms/op
Iteration   3: 3.098 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.163 ±(99.9%) 1.035 ms/op [Average]
  (min, avg, max) = (3.098, 3.163, 3.203), stdev = 0.057
  CI (99.9%): [2.128, 4.198] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.113 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.373 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.003 ms/op
Iteration   1: 3.061 ±(99.9%) 0.006 ms/op
Iteration   2: 3.116 ±(99.9%) 0.005 ms/op
Iteration   3: 3.054 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.077 ±(99.9%) 0.629 ms/op [Average]
  (min, avg, max) = (3.054, 3.077, 3.116), stdev = 0.034
  CI (99.9%): [2.448, 3.706] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.407 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.487 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.273 ±(99.9%) 0.003 ms/op
Iteration   1: 3.110 ±(99.9%) 0.004 ms/op
Iteration   2: 3.155 ±(99.9%) 0.002 ms/op
Iteration   3: 3.230 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.165 ±(99.9%) 1.112 ms/op [Average]
  (min, avg, max) = (3.110, 3.165, 3.230), stdev = 0.061
  CI (99.9%): [2.053, 4.276] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 10.087 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.162 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.851 ±(99.9%) 0.005 ms/op
Iteration   1: 3.824 ±(99.9%) 0.007 ms/op
Iteration   2: 3.600 ±(99.9%) 0.012 ms/op
Iteration   3: 3.767 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.730 ±(99.9%) 2.127 ms/op [Average]
  (min, avg, max) = (3.600, 3.730, 3.824), stdev = 0.117
  CI (99.9%): [1.603, 5.858] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.234 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.738 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.422 ±(99.9%) 0.010 ms/op
Iteration   1: 3.154 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.608 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.297 ms/op
                 createUser·p0.95:   3.617 ms/op
                 createUser·p0.99:   5.366 ms/op
                 createUser·p0.999:  9.421 ms/op
                 createUser·p0.9999: 21.819 ms/op
                 createUser·p1.00:   23.036 ms/op

Iteration   2: 3.234 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.128 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   5.472 ms/op
                 createUser·p0.999:  10.421 ms/op
                 createUser·p0.9999: 23.072 ms/op
                 createUser·p1.00:   23.200 ms/op

Iteration   3: 3.194 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.403 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.379 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  16.630 ms/op
                 createUser·p0.9999: 20.185 ms/op
                 createUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300585
  mean =      3.194 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26623 
    [ 2.500,  5.000) = 267619 
    [ 5.000,  7.500) = 5531 
    [ 7.500, 10.000) = 463 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.128 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     16.283 ms/op
     p(99.9900) =     22.446 ms/op
     p(99.9990) =     23.200 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.793 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.341 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.008 ms/op
Iteration   1: 3.061 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.499 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  9.028 ms/op
                 existUser·p0.9999: 22.267 ms/op
                 existUser·p1.00:   23.069 ms/op

Iteration   2: 3.116 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.278 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   5.005 ms/op
                 existUser·p0.999:  9.077 ms/op
                 existUser·p0.9999: 22.479 ms/op
                 existUser·p1.00:   22.839 ms/op

Iteration   3: 3.043 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.499 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   5.250 ms/op
                 existUser·p0.999:  11.729 ms/op
                 existUser·p0.9999: 20.578 ms/op
                 existUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 312154
  mean =      3.073 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18859 
    [ 2.500,  5.000) = 288327 
    [ 5.000,  7.500) = 4391 
    [ 7.500, 10.000) = 301 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.278 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.310 ms/op
     p(95.0000) =      3.564 ms/op
     p(99.0000) =      5.300 ms/op
     p(99.9000) =      9.191 ms/op
     p(99.9900) =     22.151 ms/op
     p(99.9990) =     22.774 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.693 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.389 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.232 ±(99.9%) 0.009 ms/op
Iteration   1: 3.167 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.303 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   6.201 ms/op
                 getUser·p0.999:  15.283 ms/op
                 getUser·p0.9999: 19.452 ms/op
                 getUser·p1.00:   20.251 ms/op

Iteration   2: 3.114 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.257 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.342 ms/op
                 getUser·p0.95:   3.510 ms/op
                 getUser·p0.99:   5.450 ms/op
                 getUser·p0.999:  13.271 ms/op
                 getUser·p0.9999: 23.158 ms/op
                 getUser·p1.00:   24.805 ms/op

Iteration   3: 3.243 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.503 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   5.890 ms/op
                 getUser·p0.999:  10.920 ms/op
                 getUser·p0.9999: 20.546 ms/op
                 getUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 302489
  mean =      3.174 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13678 
    [ 2.500,  5.000) = 281287 
    [ 5.000,  7.500) = 6347 
    [ 7.500, 10.000) = 634 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 130 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.257 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      5.931 ms/op
     p(99.9000) =     14.075 ms/op
     p(99.9900) =     21.815 ms/op
     p(99.9990) =     23.887 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


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
# Warmup Iteration   1: 8.839 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.992 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.798 ±(99.9%) 0.011 ms/op
Iteration   1: 3.748 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.618 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   6.472 ms/op
                 listUser·p0.999:  14.795 ms/op
                 listUser·p0.9999: 19.021 ms/op
                 listUser·p1.00:   20.152 ms/op

Iteration   2: 3.793 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   6.867 ms/op
                 listUser·p0.999:  14.348 ms/op
                 listUser·p0.9999: 16.286 ms/op
                 listUser·p1.00:   16.335 ms/op

Iteration   3: 3.856 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  13.142 ms/op
                 listUser·p0.9999: 15.298 ms/op
                 listUser·p1.00:   15.368 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252482
  mean =      3.798 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 66 
    [ 2.500,  5.000) = 243258 
    [ 5.000,  7.500) = 7551 
    [ 7.500, 10.000) = 970 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 304 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.618 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     14.139 ms/op
     p(99.9900) =     18.399 ms/op
     p(99.9990) =     19.523 ms/op
     p(99.9999) =     20.152 ms/op
    p(100.0000) =     20.152 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.837 ± 1.041  ops/ms
ClientPb.existUser                       thrpt       3  10.427 ± 3.535  ops/ms
ClientPb.getUser                         thrpt       3   9.961 ± 5.619  ops/ms
ClientPb.listUser                        thrpt       3   8.385 ± 3.305  ops/ms
ClientPb.createUser                       avgt       3   3.163 ± 1.035   ms/op
ClientPb.existUser                        avgt       3   3.077 ± 0.629   ms/op
ClientPb.getUser                          avgt       3   3.165 ± 1.112   ms/op
ClientPb.listUser                         avgt       3   3.730 ± 2.127   ms/op
ClientPb.createUser                     sample  300585   3.194 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.128           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.445           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.521           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.283           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.446           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.200           ms/op
ClientPb.existUser                      sample  312154   3.073 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.278           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.310           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.564           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.300           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.191           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.151           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.069           ms/op
ClientPb.getUser                        sample  302489   3.174 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.257           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.478           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.826           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.931           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.075           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.815           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.805           ms/op
ClientPb.listUser                       sample  252482   3.798 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.618           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.719           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.219           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.571           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.758           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.139           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.399           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.152           ms/op
