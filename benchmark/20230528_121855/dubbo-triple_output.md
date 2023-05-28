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
# Warmup Iteration   1: 2.309 ops/ms
# Warmup Iteration   2: 5.336 ops/ms
# Warmup Iteration   3: 8.716 ops/ms
Iteration   1: 9.391 ops/ms
Iteration   2: 9.475 ops/ms
Iteration   3: 9.687 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.518 ±(99.9%) 2.786 ops/ms [Average]
  (min, avg, max) = (9.391, 9.518, 9.687), stdev = 0.153
  CI (99.9%): [6.731, 12.304] (assumes normal distribution)


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
# Warmup Iteration   1: 3.639 ops/ms
# Warmup Iteration   2: 8.992 ops/ms
# Warmup Iteration   3: 9.624 ops/ms
Iteration   1: 9.675 ops/ms
Iteration   2: 9.736 ops/ms
Iteration   3: 9.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.705 ±(99.9%) 0.555 ops/ms [Average]
  (min, avg, max) = (9.675, 9.705, 9.736), stdev = 0.030
  CI (99.9%): [9.150, 10.260] (assumes normal distribution)


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
# Warmup Iteration   1: 2.795 ops/ms
# Warmup Iteration   2: 8.911 ops/ms
# Warmup Iteration   3: 9.445 ops/ms
Iteration   1: 9.601 ops/ms
Iteration   2: 9.823 ops/ms
Iteration   3: 9.592 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.672 ±(99.9%) 2.383 ops/ms [Average]
  (min, avg, max) = (9.592, 9.672, 9.823), stdev = 0.131
  CI (99.9%): [7.289, 12.055] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.011 ops/ms
# Warmup Iteration   2: 7.254 ops/ms
# Warmup Iteration   3: 8.073 ops/ms
Iteration   1: 8.241 ops/ms
Iteration   2: 8.079 ops/ms
Iteration   3: 7.935 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.085 ±(99.9%) 2.794 ops/ms [Average]
  (min, avg, max) = (7.935, 8.085, 8.241), stdev = 0.153
  CI (99.9%): [5.291, 10.879] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 10.404 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.014 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.739 ±(99.9%) 0.005 ms/op
Iteration   1: 3.571 ±(99.9%) 0.005 ms/op
Iteration   2: 3.411 ±(99.9%) 0.004 ms/op
Iteration   3: 3.360 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.447 ±(99.9%) 2.008 ms/op [Average]
  (min, avg, max) = (3.360, 3.447, 3.571), stdev = 0.110
  CI (99.9%): [1.439, 5.455] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.890 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.503 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.301 ±(99.9%) 0.004 ms/op
Iteration   1: 3.259 ±(99.9%) 0.008 ms/op
Iteration   2: 3.222 ±(99.9%) 0.007 ms/op
Iteration   3: 3.178 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.220 ±(99.9%) 0.745 ms/op [Average]
  (min, avg, max) = (3.178, 3.220, 3.259), stdev = 0.041
  CI (99.9%): [2.475, 3.964] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.132 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.679 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.548 ±(99.9%) 0.008 ms/op
Iteration   1: 3.485 ±(99.9%) 0.004 ms/op
Iteration   2: 3.393 ±(99.9%) 0.008 ms/op
Iteration   3: 3.444 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.441 ±(99.9%) 0.838 ms/op [Average]
  (min, avg, max) = (3.393, 3.441, 3.485), stdev = 0.046
  CI (99.9%): [2.603, 4.279] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.821 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.196 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.071 ±(99.9%) 0.006 ms/op
Iteration   1: 3.979 ±(99.9%) 0.009 ms/op
Iteration   2: 3.829 ±(99.9%) 0.015 ms/op
Iteration   3: 3.850 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.886 ±(99.9%) 1.483 ms/op [Average]
  (min, avg, max) = (3.829, 3.886, 3.979), stdev = 0.081
  CI (99.9%): [2.403, 5.369] (assumes normal distribution)


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
# Warmup Iteration   1: 9.787 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.877 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.595 ±(99.9%) 0.011 ms/op
Iteration   1: 3.398 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.706 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  20.604 ms/op
                 createUser·p0.9999: 25.400 ms/op
                 createUser·p1.00:   26.149 ms/op

Iteration   2: 3.385 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.372 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   5.685 ms/op
                 createUser·p0.999:  21.079 ms/op
                 createUser·p0.9999: 23.628 ms/op
                 createUser·p1.00:   24.510 ms/op

Iteration   3: 3.390 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.417 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   6.054 ms/op
                 createUser·p0.999:  20.731 ms/op
                 createUser·p0.9999: 26.710 ms/op
                 createUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283257
  mean =      3.391 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12071 
    [ 2.500,  5.000) = 265344 
    [ 5.000,  7.500) = 4918 
    [ 7.500, 10.000) = 522 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 140 
    [25.000, 27.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      1.372 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      5.844 ms/op
     p(99.9000) =     20.709 ms/op
     p(99.9900) =     25.516 ms/op
     p(99.9990) =     27.083 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


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
# Warmup Iteration   1: 8.295 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.583 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.006 ms/op
Iteration   1: 3.270 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.536 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  9.751 ms/op
                 existUser·p0.9999: 26.642 ms/op
                 existUser·p1.00:   27.656 ms/op

Iteration   2: 3.262 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.620 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   4.133 ms/op
                 existUser·p0.99:   5.751 ms/op
                 existUser·p0.999:  13.981 ms/op
                 existUser·p0.9999: 23.533 ms/op
                 existUser·p1.00:   24.543 ms/op

Iteration   3: 3.290 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.528 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.641 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   6.070 ms/op
                 existUser·p0.999:  10.568 ms/op
                 existUser·p0.9999: 27.085 ms/op
                 existUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293271
  mean =      3.274 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17475 
    [ 2.500,  5.000) = 268884 
    [ 5.000,  7.500) = 6087 
    [ 7.500, 10.000) = 461 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      1.528 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     13.852 ms/op
     p(99.9900) =     26.434 ms/op
     p(99.9990) =     28.082 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


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
# Warmup Iteration   1: 8.551 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.622 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.491 ±(99.9%) 0.010 ms/op
Iteration   1: 3.542 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.401 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   5.120 ms/op
                 getUser·p0.99:   7.430 ms/op
                 getUser·p0.999:  20.010 ms/op
                 getUser·p0.9999: 22.740 ms/op
                 getUser·p1.00:   30.573 ms/op

Iteration   2: 3.329 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.868 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  21.240 ms/op
                 getUser·p0.9999: 23.861 ms/op
                 getUser·p1.00:   25.035 ms/op

Iteration   3: 3.496 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.350 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   6.480 ms/op
                 getUser·p0.999:  17.239 ms/op
                 getUser·p0.9999: 24.084 ms/op
                 getUser·p1.00:   24.674 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277850
  mean =      3.453 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3651 
    [ 2.500,  5.000) = 263530 
    [ 5.000,  7.500) = 9070 
    [ 7.500, 10.000) = 1007 
    [10.000, 12.500) = 215 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 135 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.350 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     18.879 ms/op
     p(99.9900) =     23.790 ms/op
     p(99.9990) =     24.754 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


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
# Warmup Iteration   1: 13.027 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.654 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.030 ±(99.9%) 0.013 ms/op
Iteration   1: 3.977 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.767 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   7.525 ms/op
                 listUser·p0.999:  22.905 ms/op
                 listUser·p0.9999: 26.270 ms/op
                 listUser·p1.00:   26.870 ms/op

Iteration   2: 3.983 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.138 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   7.666 ms/op
                 listUser·p0.999:  14.959 ms/op
                 listUser·p0.9999: 15.450 ms/op
                 listUser·p1.00:   15.581 ms/op

Iteration   3: 4.003 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  16.220 ms/op
                 listUser·p0.9999: 19.497 ms/op
                 listUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240644
  mean =      3.988 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 231148 
    [ 5.000,  7.500) = 7281 
    [ 7.500, 10.000) = 1322 
    [10.000, 12.500) = 329 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 208 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.767 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     15.548 ms/op
     p(99.9900) =     25.031 ms/op
     p(99.9990) =     26.745 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.518 ± 2.786  ops/ms
ClientPb.existUser                       thrpt       3   9.705 ± 0.555  ops/ms
ClientPb.getUser                         thrpt       3   9.672 ± 2.383  ops/ms
ClientPb.listUser                        thrpt       3   8.085 ± 2.794  ops/ms
ClientPb.createUser                       avgt       3   3.447 ± 2.008   ms/op
ClientPb.existUser                        avgt       3   3.220 ± 0.745   ms/op
ClientPb.getUser                          avgt       3   3.441 ± 0.838   ms/op
ClientPb.listUser                         avgt       3   3.886 ± 1.483   ms/op
ClientPb.createUser                     sample  283257   3.391 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.372           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.318           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.235           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.844           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.709           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.516           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.148           ms/op
ClientPb.existUser                      sample  293271   3.274 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.528           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.199           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.588           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.059           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.734           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.852           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.434           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.082           ms/op
ClientPb.getUser                        sample  277850   3.453 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.350           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.281           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.813           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.301           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.799           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.879           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.790           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.573           ms/op
ClientPb.listUser                       sample  240644   3.988 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.767           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.825           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.266           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.548           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.031           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.870           ms/op
