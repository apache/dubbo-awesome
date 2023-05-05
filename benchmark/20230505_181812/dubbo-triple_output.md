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
# Warmup Iteration   1: 2.482 ops/ms
# Warmup Iteration   2: 6.759 ops/ms
# Warmup Iteration   3: 9.660 ops/ms
Iteration   1: 9.875 ops/ms
Iteration   2: 10.291 ops/ms
Iteration   3: 10.198 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.121 ±(99.9%) 3.979 ops/ms [Average]
  (min, avg, max) = (9.875, 10.121, 10.291), stdev = 0.218
  CI (99.9%): [6.143, 14.100] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.890 ops/ms
# Warmup Iteration   2: 9.635 ops/ms
# Warmup Iteration   3: 9.823 ops/ms
Iteration   1: 10.213 ops/ms
Iteration   2: 10.438 ops/ms
Iteration   3: 10.381 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.344 ±(99.9%) 2.130 ops/ms [Average]
  (min, avg, max) = (10.213, 10.344, 10.438), stdev = 0.117
  CI (99.9%): [8.214, 12.474] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.046 ops/ms
# Warmup Iteration   2: 9.110 ops/ms
# Warmup Iteration   3: 9.935 ops/ms
Iteration   1: 10.239 ops/ms
Iteration   2: 10.003 ops/ms
Iteration   3: 9.973 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.072 ±(99.9%) 2.654 ops/ms [Average]
  (min, avg, max) = (9.973, 10.072, 10.239), stdev = 0.145
  CI (99.9%): [7.418, 12.726] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.297 ops/ms
# Warmup Iteration   2: 7.977 ops/ms
# Warmup Iteration   3: 8.374 ops/ms
Iteration   1: 8.489 ops/ms
Iteration   2: 8.303 ops/ms
Iteration   3: 8.275 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.356 ±(99.9%) 2.123 ops/ms [Average]
  (min, avg, max) = (8.275, 8.356, 8.489), stdev = 0.116
  CI (99.9%): [6.232, 10.479] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.299 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.481 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.345 ±(99.9%) 0.006 ms/op
Iteration   1: 3.214 ±(99.9%) 0.009 ms/op
Iteration   2: 3.174 ±(99.9%) 0.005 ms/op
Iteration   3: 3.250 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.213 ±(99.9%) 0.696 ms/op [Average]
  (min, avg, max) = (3.174, 3.213, 3.250), stdev = 0.038
  CI (99.9%): [2.517, 3.909] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.001 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.340 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.003 ms/op
Iteration   1: 3.098 ±(99.9%) 0.005 ms/op
Iteration   2: 3.033 ±(99.9%) 0.001 ms/op
Iteration   3: 2.988 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.040 ±(99.9%) 1.014 ms/op [Average]
  (min, avg, max) = (2.988, 3.040, 3.098), stdev = 0.056
  CI (99.9%): [2.026, 4.054] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.688 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.552 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.331 ±(99.9%) 0.002 ms/op
Iteration   1: 3.247 ±(99.9%) 0.005 ms/op
Iteration   2: 3.204 ±(99.9%) 0.004 ms/op
Iteration   3: 3.203 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.218 ±(99.9%) 0.462 ms/op [Average]
  (min, avg, max) = (3.203, 3.218, 3.247), stdev = 0.025
  CI (99.9%): [2.756, 3.680] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.546 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.860 ±(99.9%) 0.005 ms/op
Iteration   1: 3.631 ±(99.9%) 0.010 ms/op
Iteration   2: 3.748 ±(99.9%) 0.005 ms/op
Iteration   3: 3.682 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.687 ±(99.9%) 1.073 ms/op [Average]
  (min, avg, max) = (3.631, 3.687, 3.748), stdev = 0.059
  CI (99.9%): [2.614, 4.760] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.368 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.662 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.367 ±(99.9%) 0.010 ms/op
Iteration   1: 3.198 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.366 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   5.366 ms/op
                 createUser·p0.999:  8.929 ms/op
                 createUser·p0.9999: 19.825 ms/op
                 createUser·p1.00:   20.578 ms/op

Iteration   2: 3.081 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.229 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  9.247 ms/op
                 createUser·p0.9999: 23.036 ms/op
                 createUser·p1.00:   24.150 ms/op

Iteration   3: 3.210 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.735 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   4.007 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  16.539 ms/op
                 createUser·p0.9999: 21.692 ms/op
                 createUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303638
  mean =      3.162 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18499 
    [ 2.500,  5.000) = 279920 
    [ 5.000,  7.500) = 4346 
    [ 7.500, 10.000) = 451 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 158 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =     16.271 ms/op
     p(99.9900) =     22.381 ms/op
     p(99.9990) =     23.622 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.648 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.367 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.007 ms/op
Iteration   1: 3.149 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.192 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   4.129 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  8.323 ms/op
                 existUser·p0.9999: 20.601 ms/op
                 existUser·p1.00:   21.332 ms/op

Iteration   2: 2.993 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.034 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.162 ms/op
                 existUser·p0.95:   3.346 ms/op
                 existUser·p0.99:   5.235 ms/op
                 existUser·p0.999:  11.993 ms/op
                 existUser·p0.9999: 22.685 ms/op
                 existUser·p1.00:   23.396 ms/op

Iteration   3: 3.131 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.257 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  10.449 ms/op
                 existUser·p0.9999: 22.938 ms/op
                 existUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310757
  mean =      3.089 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27898 
    [ 2.500,  5.000) = 277747 
    [ 5.000,  7.500) = 4326 
    [ 7.500, 10.000) = 352 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 184 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.034 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =     11.993 ms/op
     p(99.9900) =     22.741 ms/op
     p(99.9990) =     23.317 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.916 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.462 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.421 ±(99.9%) 0.010 ms/op
Iteration   1: 3.291 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.069 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   4.010 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   6.136 ms/op
                 getUser·p0.999:  17.950 ms/op
                 getUser·p0.9999: 21.074 ms/op
                 getUser·p1.00:   21.987 ms/op

Iteration   2: 3.154 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.804 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.584 ms/op
                 getUser·p0.99:   5.343 ms/op
                 getUser·p0.999:  12.059 ms/op
                 getUser·p0.9999: 24.838 ms/op
                 getUser·p1.00:   25.526 ms/op

Iteration   3: 3.273 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.321 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   4.141 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  10.030 ms/op
                 getUser·p0.9999: 34.093 ms/op
                 getUser·p1.00:   34.996 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296466
  mean =      3.238 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12311 
    [ 2.500,  5.000) = 275626 
    [ 5.000,  7.500) = 7283 
    [ 7.500, 10.000) = 764 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     14.795 ms/op
     p(99.9900) =     32.747 ms/op
     p(99.9990) =     34.931 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.068 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 4.066 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.825 ±(99.9%) 0.013 ms/op
Iteration   1: 3.788 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.589 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.129 ms/op
                 listUser·p0.95:   4.973 ms/op
                 listUser·p0.99:   7.619 ms/op
                 listUser·p0.999:  16.335 ms/op
                 listUser·p0.9999: 19.482 ms/op
                 listUser·p1.00:   19.562 ms/op

Iteration   2: 3.747 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.303 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   7.218 ms/op
                 listUser·p0.999:  12.845 ms/op
                 listUser·p0.9999: 17.990 ms/op
                 listUser·p1.00:   18.743 ms/op

Iteration   3: 3.722 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.718 ms/op
                 listUser·p0.50:   3.498 ms/op
                 listUser·p0.90:   4.174 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  13.502 ms/op
                 listUser·p0.9999: 16.368 ms/op
                 listUser·p1.00:   16.450 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255675
  mean =      3.752 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 145 
    [ 2.500,  3.750) = 182693 
    [ 3.750,  5.000) = 62653 
    [ 5.000,  6.250) = 3692 
    [ 6.250,  7.500) = 4160 
    [ 7.500,  8.750) = 1219 
    [ 8.750, 10.000) = 322 
    [10.000, 11.250) = 143 
    [11.250, 12.500) = 160 
    [12.500, 13.750) = 220 
    [13.750, 15.000) = 74 
    [15.000, 16.250) = 53 
    [16.250, 17.500) = 58 
    [17.500, 18.750) = 61 

  Percentiles, ms/op:
      p(0.0000) =      1.303 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     13.844 ms/op
     p(99.9900) =     18.743 ms/op
     p(99.9990) =     19.530 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.121 ± 3.979  ops/ms
ClientPb.existUser                       thrpt       3  10.344 ± 2.130  ops/ms
ClientPb.getUser                         thrpt       3  10.072 ± 2.654  ops/ms
ClientPb.listUser                        thrpt       3   8.356 ± 2.123  ops/ms
ClientPb.createUser                       avgt       3   3.213 ± 0.696   ms/op
ClientPb.existUser                        avgt       3   3.040 ± 1.014   ms/op
ClientPb.getUser                          avgt       3   3.218 ± 0.462   ms/op
ClientPb.listUser                         avgt       3   3.687 ± 1.073   ms/op
ClientPb.createUser                     sample  303638   3.162 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.735           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.568           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.407           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.271           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.381           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.150           ms/op
ClientPb.existUser                      sample  310757   3.089 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.034           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.387           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.871           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.308           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.993           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.741           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.396           ms/op
ClientPb.getUser                        sample  296466   3.238 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.804           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.125           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.629           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.833           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.795           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.747           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.996           ms/op
ClientPb.listUser                       sample  255675   3.752 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.303           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.576           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.133           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.653           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.389           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.844           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.743           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.562           ms/op
