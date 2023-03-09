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
# Warmup Iteration   1: 2.268 ops/ms
# Warmup Iteration   2: 5.884 ops/ms
# Warmup Iteration   3: 9.052 ops/ms
Iteration   1: 9.522 ops/ms
Iteration   2: 9.358 ops/ms
Iteration   3: 9.071 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.317 ±(99.9%) 4.164 ops/ms [Average]
  (min, avg, max) = (9.071, 9.317, 9.522), stdev = 0.228
  CI (99.9%): [5.153, 13.481] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.124 ops/ms
# Warmup Iteration   2: 8.973 ops/ms
# Warmup Iteration   3: 9.419 ops/ms
Iteration   1: 9.861 ops/ms
Iteration   2: 9.915 ops/ms
Iteration   3: 9.955 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.910 ±(99.9%) 0.861 ops/ms [Average]
  (min, avg, max) = (9.861, 9.910, 9.955), stdev = 0.047
  CI (99.9%): [9.049, 10.771] (assumes normal distribution)


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
# Warmup Iteration   1: 2.627 ops/ms
# Warmup Iteration   2: 8.538 ops/ms
# Warmup Iteration   3: 8.721 ops/ms
Iteration   1: 9.372 ops/ms
Iteration   2: 9.393 ops/ms
Iteration   3: 9.644 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.469 ±(99.9%) 2.761 ops/ms [Average]
  (min, avg, max) = (9.372, 9.469, 9.644), stdev = 0.151
  CI (99.9%): [6.709, 12.230] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.630 ops/ms
# Warmup Iteration   2: 6.699 ops/ms
# Warmup Iteration   3: 8.012 ops/ms
Iteration   1: 7.808 ops/ms
Iteration   2: 8.083 ops/ms
Iteration   3: 8.468 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.119 ±(99.9%) 6.049 ops/ms [Average]
  (min, avg, max) = (7.808, 8.119, 8.468), stdev = 0.332
  CI (99.9%): [2.070, 14.169] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.243 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.812 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.435 ±(99.9%) 0.010 ms/op
Iteration   1: 3.334 ±(99.9%) 0.012 ms/op
Iteration   2: 3.283 ±(99.9%) 0.010 ms/op
Iteration   3: 3.385 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.334 ±(99.9%) 0.936 ms/op [Average]
  (min, avg, max) = (3.283, 3.334, 3.385), stdev = 0.051
  CI (99.9%): [2.398, 4.270] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.637 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.439 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.277 ±(99.9%) 0.008 ms/op
Iteration   1: 3.295 ±(99.9%) 0.005 ms/op
Iteration   2: 3.209 ±(99.9%) 0.006 ms/op
Iteration   3: 3.283 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.262 ±(99.9%) 0.846 ms/op [Average]
  (min, avg, max) = (3.209, 3.262, 3.295), stdev = 0.046
  CI (99.9%): [2.416, 4.108] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.755 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.663 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.605 ±(99.9%) 0.002 ms/op
Iteration   1: 3.405 ±(99.9%) 0.002 ms/op
Iteration   2: 3.335 ±(99.9%) 0.010 ms/op
Iteration   3: 3.347 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.362 ±(99.9%) 0.682 ms/op [Average]
  (min, avg, max) = (3.335, 3.362, 3.405), stdev = 0.037
  CI (99.9%): [2.680, 4.045] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.309 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.496 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.038 ±(99.9%) 0.010 ms/op
Iteration   1: 3.903 ±(99.9%) 0.013 ms/op
Iteration   2: 4.036 ±(99.9%) 0.008 ms/op
Iteration   3: 3.900 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.946 ±(99.9%) 1.414 ms/op [Average]
  (min, avg, max) = (3.900, 3.946, 4.036), stdev = 0.078
  CI (99.9%): [2.532, 5.361] (assumes normal distribution)


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
# Warmup Iteration   1: 9.661 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.915 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.512 ±(99.9%) 0.011 ms/op
Iteration   1: 3.368 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.520 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  21.863 ms/op
                 createUser·p0.9999: 23.987 ms/op
                 createUser·p1.00:   24.183 ms/op

Iteration   2: 3.394 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.561 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   6.062 ms/op
                 createUser·p0.999:  22.837 ms/op
                 createUser·p0.9999: 25.677 ms/op
                 createUser·p1.00:   26.313 ms/op

Iteration   3: 3.351 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.171 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   5.687 ms/op
                 createUser·p0.999:  24.740 ms/op
                 createUser·p0.9999: 29.048 ms/op
                 createUser·p1.00:   29.950 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 284418
  mean =      3.371 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12922 
    [ 2.500,  5.000) = 266093 
    [ 5.000,  7.500) = 4370 
    [ 7.500, 10.000) = 614 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 172 
    [25.000, 27.500) = 100 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     22.512 ms/op
     p(99.9900) =     26.640 ms/op
     p(99.9990) =     29.295 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


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
# Warmup Iteration   1: 8.679 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.469 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.246 ±(99.9%) 0.008 ms/op
Iteration   1: 3.265 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.180 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   5.813 ms/op
                 existUser·p0.999:  11.848 ms/op
                 existUser·p0.9999: 21.835 ms/op
                 existUser·p1.00:   23.233 ms/op

Iteration   2: 3.340 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.237 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   4.108 ms/op
                 existUser·p0.99:   5.693 ms/op
                 existUser·p0.999:  21.447 ms/op
                 existUser·p0.9999: 24.426 ms/op
                 existUser·p1.00:   26.018 ms/op

Iteration   3: 3.236 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.356 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   4.841 ms/op
                 existUser·p0.999:  13.396 ms/op
                 existUser·p0.9999: 25.759 ms/op
                 existUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 292619
  mean =      3.280 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10260 
    [ 2.500,  5.000) = 276764 
    [ 5.000,  7.500) = 4611 
    [ 7.500, 10.000) = 599 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =     13.319 ms/op
     p(99.9900) =     24.755 ms/op
     p(99.9990) =     26.706 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


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
# Warmup Iteration   1: 9.500 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.574 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.462 ±(99.9%) 0.010 ms/op
Iteration   1: 3.529 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.210 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   4.030 ms/op
                 getUser·p0.95:   5.267 ms/op
                 getUser·p0.99:   6.963 ms/op
                 getUser·p0.999:  20.362 ms/op
                 getUser·p0.9999: 26.324 ms/op
                 getUser·p1.00:   26.542 ms/op

Iteration   2: 3.275 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.636 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   5.448 ms/op
                 getUser·p0.999:  9.863 ms/op
                 getUser·p0.9999: 27.525 ms/op
                 getUser·p1.00:   28.377 ms/op

Iteration   3: 3.437 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.953 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   6.889 ms/op
                 getUser·p0.999:  17.433 ms/op
                 getUser·p0.9999: 27.566 ms/op
                 getUser·p1.00:   28.541 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 281340
  mean =      3.410 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6501 
    [ 2.500,  5.000) = 264821 
    [ 5.000,  7.500) = 8550 
    [ 7.500, 10.000) = 920 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 60 

  Percentiles, ms/op:
      p(0.0000) =      0.953 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =     19.584 ms/op
     p(99.9900) =     27.095 ms/op
     p(99.9990) =     28.402 ms/op
     p(99.9999) =     28.541 ms/op
    p(100.0000) =     28.541 ms/op


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
# Warmup Iteration   1: 11.402 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.465 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.201 ±(99.9%) 0.014 ms/op
Iteration   1: 4.089 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.499 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.995 ms/op
                 listUser·p0.999:  20.831 ms/op
                 listUser·p0.9999: 24.855 ms/op
                 listUser·p1.00:   25.526 ms/op

Iteration   2: 4.046 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.310 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   4.989 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  16.024 ms/op
                 listUser·p0.9999: 23.072 ms/op
                 listUser·p1.00:   23.396 ms/op

Iteration   3: 3.991 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.040 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   7.717 ms/op
                 listUser·p0.999:  16.302 ms/op
                 listUser·p0.9999: 20.644 ms/op
                 listUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237561
  mean =      4.042 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 227377 
    [ 5.000,  7.500) = 7527 
    [ 7.500, 10.000) = 1569 
    [10.000, 12.500) = 427 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 278 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.499 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      7.692 ms/op
     p(99.9000) =     16.792 ms/op
     p(99.9900) =     23.806 ms/op
     p(99.9990) =     25.342 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.317 ± 4.164  ops/ms
ClientPb.existUser                       thrpt       3   9.910 ± 0.861  ops/ms
ClientPb.getUser                         thrpt       3   9.469 ± 2.761  ops/ms
ClientPb.listUser                        thrpt       3   8.119 ± 6.049  ops/ms
ClientPb.createUser                       avgt       3   3.334 ± 0.936   ms/op
ClientPb.existUser                        avgt       3   3.262 ± 0.846   ms/op
ClientPb.getUser                          avgt       3   3.362 ± 0.682   ms/op
ClientPb.listUser                         avgt       3   3.946 ± 1.414   ms/op
ClientPb.createUser                     sample  284418   3.371 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.171           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.310           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.731           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.035           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.825           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.512           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.640           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.950           ms/op
ClientPb.existUser                      sample  292619   3.280 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.180           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.174           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.957           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.538           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.319           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.755           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.968           ms/op
ClientPb.getUser                        sample  281340   3.410 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.953           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.260           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.325           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.562           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.584           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.095           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.541           ms/op
ClientPb.listUser                       sample  237561   4.042 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.499           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.817           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.692           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.792           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.806           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.526           ms/op
