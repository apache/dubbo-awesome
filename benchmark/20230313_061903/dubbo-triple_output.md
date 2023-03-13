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
# Warmup Iteration   1: 2.371 ops/ms
# Warmup Iteration   2: 6.176 ops/ms
# Warmup Iteration   3: 9.005 ops/ms
Iteration   1: 9.297 ops/ms
Iteration   2: 9.549 ops/ms
Iteration   3: 9.059 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.301 ±(99.9%) 4.473 ops/ms [Average]
  (min, avg, max) = (9.059, 9.301, 9.549), stdev = 0.245
  CI (99.9%): [4.828, 13.775] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.816 ops/ms
# Warmup Iteration   2: 9.301 ops/ms
# Warmup Iteration   3: 9.788 ops/ms
Iteration   1: 9.941 ops/ms
Iteration   2: 10.064 ops/ms
Iteration   3: 9.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.943 ±(99.9%) 2.174 ops/ms [Average]
  (min, avg, max) = (9.825, 9.943, 10.064), stdev = 0.119
  CI (99.9%): [7.769, 12.117] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.090 ops/ms
# Warmup Iteration   2: 8.671 ops/ms
# Warmup Iteration   3: 9.199 ops/ms
Iteration   1: 9.469 ops/ms
Iteration   2: 9.411 ops/ms
Iteration   3: 9.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.525 ±(99.9%) 2.727 ops/ms [Average]
  (min, avg, max) = (9.411, 9.525, 9.694), stdev = 0.149
  CI (99.9%): [6.798, 12.252] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.886 ops/ms
# Warmup Iteration   2: 7.402 ops/ms
# Warmup Iteration   3: 7.842 ops/ms
Iteration   1: 7.874 ops/ms
Iteration   2: 8.247 ops/ms
Iteration   3: 8.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.091 ±(99.9%) 3.529 ops/ms [Average]
  (min, avg, max) = (7.874, 8.091, 8.247), stdev = 0.193
  CI (99.9%): [4.562, 11.619] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.793 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.776 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.582 ±(99.9%) 0.005 ms/op
Iteration   1: 3.503 ±(99.9%) 0.010 ms/op
Iteration   2: 3.379 ±(99.9%) 0.007 ms/op
Iteration   3: 3.371 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.418 ±(99.9%) 1.352 ms/op [Average]
  (min, avg, max) = (3.371, 3.418, 3.503), stdev = 0.074
  CI (99.9%): [2.066, 4.770] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 9.097 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.528 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.321 ±(99.9%) 0.007 ms/op
Iteration   1: 3.214 ±(99.9%) 0.004 ms/op
Iteration   2: 3.165 ±(99.9%) 0.011 ms/op
Iteration   3: 3.243 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.207 ±(99.9%) 0.723 ms/op [Average]
  (min, avg, max) = (3.165, 3.207, 3.243), stdev = 0.040
  CI (99.9%): [2.484, 3.930] (assumes normal distribution)


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
# Warmup Iteration   1: 8.637 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.712 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.466 ±(99.9%) 0.005 ms/op
Iteration   1: 3.386 ±(99.9%) 0.011 ms/op
Iteration   2: 3.443 ±(99.9%) 0.008 ms/op
Iteration   3: 3.479 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.436 ±(99.9%) 0.853 ms/op [Average]
  (min, avg, max) = (3.386, 3.436, 3.479), stdev = 0.047
  CI (99.9%): [2.583, 4.289] (assumes normal distribution)


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
# Warmup Iteration   1: 10.224 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.473 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.139 ±(99.9%) 0.005 ms/op
Iteration   1: 3.893 ±(99.9%) 0.012 ms/op
Iteration   2: 3.937 ±(99.9%) 0.014 ms/op
Iteration   3: 3.919 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.916 ±(99.9%) 0.402 ms/op [Average]
  (min, avg, max) = (3.893, 3.916, 3.937), stdev = 0.022
  CI (99.9%): [3.514, 4.318] (assumes normal distribution)


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
# Warmup Iteration   1: 10.812 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.833 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.766 ±(99.9%) 0.014 ms/op
Iteration   1: 3.327 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.413 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  18.874 ms/op
                 createUser·p0.9999: 23.462 ms/op
                 createUser·p1.00:   24.609 ms/op

Iteration   2: 3.372 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.206 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.149 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  22.667 ms/op
                 createUser·p0.9999: 27.442 ms/op
                 createUser·p1.00:   28.705 ms/op

Iteration   3: 3.376 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.614 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  18.350 ms/op
                 createUser·p0.9999: 26.315 ms/op
                 createUser·p1.00:   27.853 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 285818
  mean =      3.358 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10829 
    [ 2.500,  5.000) = 269077 
    [ 5.000,  7.500) = 5152 
    [ 7.500, 10.000) = 369 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 81 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     18.356 ms/op
     p(99.9900) =     26.509 ms/op
     p(99.9990) =     28.414 ms/op
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
# Warmup Iteration   1: 7.425 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.614 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.407 ±(99.9%) 0.009 ms/op
Iteration   1: 3.214 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.161 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.760 ms/op
                 existUser·p0.999:  7.917 ms/op
                 existUser·p0.9999: 23.824 ms/op
                 existUser·p1.00:   24.281 ms/op

Iteration   2: 3.340 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.726 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   4.792 ms/op
                 existUser·p0.99:   5.898 ms/op
                 existUser·p0.999:  22.291 ms/op
                 existUser·p0.9999: 28.017 ms/op
                 existUser·p1.00:   28.344 ms/op

Iteration   3: 3.311 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.348 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   5.489 ms/op
                 existUser·p0.999:  18.137 ms/op
                 existUser·p0.9999: 26.980 ms/op
                 existUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291734
  mean =      3.287 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9409 
    [ 2.500,  5.000) = 276602 
    [ 5.000,  7.500) = 5086 
    [ 7.500, 10.000) = 354 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 138 
    [25.000, 27.500) = 49 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =      9.798 ms/op
     p(99.9900) =     27.230 ms/op
     p(99.9990) =     28.281 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


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
# Warmup Iteration   1: 10.103 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.843 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.492 ±(99.9%) 0.009 ms/op
Iteration   1: 3.539 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.274 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   4.108 ms/op
                 getUser·p0.95:   4.915 ms/op
                 getUser·p0.99:   7.070 ms/op
                 getUser·p0.999:  20.196 ms/op
                 getUser·p0.9999: 22.248 ms/op
                 getUser·p1.00:   23.396 ms/op

Iteration   2: 3.494 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.647 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   4.030 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   5.792 ms/op
                 getUser·p0.999:  22.135 ms/op
                 getUser·p0.9999: 24.899 ms/op
                 getUser·p1.00:   26.345 ms/op

Iteration   3: 3.339 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.858 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   5.448 ms/op
                 getUser·p0.999:  18.650 ms/op
                 getUser·p0.9999: 28.260 ms/op
                 getUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277773
  mean =      3.455 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8564 
    [ 2.500,  5.000) = 261794 
    [ 5.000,  7.500) = 6109 
    [ 7.500, 10.000) = 716 
    [10.000, 12.500) = 217 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      1.274 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.267 ms/op
     p(99.9000) =     19.352 ms/op
     p(99.9900) =     26.804 ms/op
     p(99.9990) =     29.153 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


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
# Warmup Iteration   1: 9.931 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.251 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.059 ±(99.9%) 0.014 ms/op
Iteration   1: 4.141 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.714 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.349 ms/op
                 listUser·p0.99:   8.258 ms/op
                 listUser·p0.999:  16.602 ms/op
                 listUser·p0.9999: 22.955 ms/op
                 listUser·p1.00:   24.183 ms/op

Iteration   2: 4.146 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.273 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   7.714 ms/op
                 listUser·p0.999:  15.148 ms/op
                 listUser·p0.9999: 20.190 ms/op
                 listUser·p1.00:   21.365 ms/op

Iteration   3: 4.099 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.605 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  15.598 ms/op
                 listUser·p0.9999: 19.681 ms/op
                 listUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232409
  mean =      4.128 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 222349 
    [ 5.000,  7.500) = 7254 
    [ 7.500, 10.000) = 1891 
    [10.000, 12.500) = 360 
    [12.500, 15.000) = 233 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.714 ms/op
     p(50.0000) =      3.981 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      7.766 ms/op
     p(99.9000) =     16.010 ms/op
     p(99.9900) =     22.340 ms/op
     p(99.9990) =     24.063 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.301 ± 4.473  ops/ms
ClientPb.existUser                       thrpt       3   9.943 ± 2.174  ops/ms
ClientPb.getUser                         thrpt       3   9.525 ± 2.727  ops/ms
ClientPb.listUser                        thrpt       3   8.091 ± 3.529  ops/ms
ClientPb.createUser                       avgt       3   3.418 ± 1.352   ms/op
ClientPb.existUser                        avgt       3   3.207 ± 0.723   ms/op
ClientPb.getUser                          avgt       3   3.436 ± 0.853   ms/op
ClientPb.listUser                         avgt       3   3.916 ± 0.402   ms/op
ClientPb.createUser                     sample  285818   3.358 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.206           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.285           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.084           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.718           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.356           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.509           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.705           ms/op
ClientPb.existUser                      sample  291734   3.287 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.161           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.199           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.596           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.903           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.472           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.798           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.230           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.344           ms/op
ClientPb.getUser                        sample  277773   3.455 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.274           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.305           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.953           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.317           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.267           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.352           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.804           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.295           ms/op
ClientPb.listUser                       sample  232409   4.128 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.714           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.981           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.882           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.766           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.010           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.340           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.183           ms/op
