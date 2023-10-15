# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.788 ops/ms
# Warmup Iteration   2: 4.543 ops/ms
# Warmup Iteration   3: 7.957 ops/ms
Iteration   1: 8.298 ops/ms
Iteration   2: 8.696 ops/ms
Iteration   3: 8.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.563 ±(99.9%) 4.193 ops/ms [Average]
  (min, avg, max) = (8.298, 8.563, 8.696), stdev = 0.230
  CI (99.9%): [4.371, 12.756] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.414 ops/ms
# Warmup Iteration   2: 7.576 ops/ms
# Warmup Iteration   3: 9.054 ops/ms
Iteration   1: 8.976 ops/ms
Iteration   2: 9.130 ops/ms
Iteration   3: 9.382 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.162 ±(99.9%) 3.743 ops/ms [Average]
  (min, avg, max) = (8.976, 9.162, 9.382), stdev = 0.205
  CI (99.9%): [5.419, 12.906] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.420 ops/ms
# Warmup Iteration   2: 7.536 ops/ms
# Warmup Iteration   3: 8.607 ops/ms
Iteration   1: 8.458 ops/ms
Iteration   2: 8.643 ops/ms
Iteration   3: 8.523 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.542 ±(99.9%) 1.712 ops/ms [Average]
  (min, avg, max) = (8.458, 8.542, 8.643), stdev = 0.094
  CI (99.9%): [6.830, 10.254] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.417 ops/ms
# Warmup Iteration   2: 6.605 ops/ms
# Warmup Iteration   3: 7.421 ops/ms
Iteration   1: 7.292 ops/ms
Iteration   2: 7.192 ops/ms
Iteration   3: 7.322 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.268 ±(99.9%) 1.236 ops/ms [Average]
  (min, avg, max) = (7.192, 7.268, 7.322), stdev = 0.068
  CI (99.9%): [6.032, 8.505] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 13.012 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.064 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.845 ±(99.9%) 0.003 ms/op
Iteration   1: 3.669 ±(99.9%) 0.006 ms/op
Iteration   2: 3.688 ±(99.9%) 0.003 ms/op
Iteration   3: 3.656 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.671 ±(99.9%) 0.295 ms/op [Average]
  (min, avg, max) = (3.656, 3.671, 3.688), stdev = 0.016
  CI (99.9%): [3.376, 3.966] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.550 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.897 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.466 ±(99.9%) 0.002 ms/op
Iteration   1: 3.553 ±(99.9%) 0.004 ms/op
Iteration   2: 3.438 ±(99.9%) 0.004 ms/op
Iteration   3: 3.486 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.493 ±(99.9%) 1.054 ms/op [Average]
  (min, avg, max) = (3.438, 3.493, 3.553), stdev = 0.058
  CI (99.9%): [2.439, 4.547] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 10.690 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.099 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.722 ±(99.9%) 0.006 ms/op
Iteration   1: 3.678 ±(99.9%) 0.005 ms/op
Iteration   2: 3.597 ±(99.9%) 0.005 ms/op
Iteration   3: 3.570 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.615 ±(99.9%) 1.028 ms/op [Average]
  (min, avg, max) = (3.570, 3.615, 3.678), stdev = 0.056
  CI (99.9%): [2.588, 4.643] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 12.876 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.638 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.368 ±(99.9%) 0.006 ms/op
Iteration   1: 4.324 ±(99.9%) 0.009 ms/op
Iteration   2: 4.401 ±(99.9%) 0.005 ms/op
Iteration   3: 4.318 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.348 ±(99.9%) 0.842 ms/op [Average]
  (min, avg, max) = (4.318, 4.348, 4.401), stdev = 0.046
  CI (99.9%): [3.506, 5.190] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 9.807 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 4.369 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.617 ±(99.9%) 0.011 ms/op
Iteration   1: 3.698 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.262 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   5.177 ms/op
                 createUser·p0.99:   7.504 ms/op
                 createUser·p0.999:  23.720 ms/op
                 createUser·p0.9999: 26.095 ms/op
                 createUser·p1.00:   26.739 ms/op

Iteration   2: 3.631 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.513 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   4.071 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   7.635 ms/op
                 createUser·p0.999:  23.949 ms/op
                 createUser·p0.9999: 28.357 ms/op
                 createUser·p1.00:   29.032 ms/op

Iteration   3: 3.610 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.799 ms/op
                 createUser·p0.50:   3.465 ms/op
                 createUser·p0.90:   4.157 ms/op
                 createUser·p0.95:   4.465 ms/op
                 createUser·p0.99:   6.660 ms/op
                 createUser·p0.999:  20.118 ms/op
                 createUser·p0.9999: 30.015 ms/op
                 createUser·p1.00:   30.278 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 263193
  mean =      3.646 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3419 
    [ 2.500,  5.000) = 249474 
    [ 5.000,  7.500) = 8068 
    [ 7.500, 10.000) = 1293 
    [10.000, 12.500) = 336 
    [12.500, 15.000) = 195 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 121 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      3.449 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      7.324 ms/op
     p(99.9000) =     22.794 ms/op
     p(99.9900) =     28.770 ms/op
     p(99.9990) =     30.191 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 9.704 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 3.870 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.581 ±(99.9%) 0.011 ms/op
Iteration   1: 3.509 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.120 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   7.070 ms/op
                 existUser·p0.999:  21.754 ms/op
                 existUser·p0.9999: 24.867 ms/op
                 existUser·p1.00:   25.068 ms/op

Iteration   2: 3.469 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.626 ms/op
                 existUser·p0.50:   3.375 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   3.981 ms/op
                 existUser·p0.99:   7.348 ms/op
                 existUser·p0.999:  15.958 ms/op
                 existUser·p0.9999: 23.684 ms/op
                 existUser·p1.00:   24.773 ms/op

Iteration   3: 3.581 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.708 ms/op
                 existUser·p0.50:   3.412 ms/op
                 existUser·p0.90:   4.026 ms/op
                 existUser·p0.95:   4.563 ms/op
                 existUser·p0.99:   7.545 ms/op
                 existUser·p0.999:  26.267 ms/op
                 existUser·p0.9999: 29.198 ms/op
                 existUser·p1.00:   30.245 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 272672
  mean =      3.519 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4047 
    [ 2.500,  5.000) = 259730 
    [ 5.000,  7.500) = 6539 
    [ 7.500, 10.000) = 1710 
    [10.000, 12.500) = 259 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 136 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.120 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.295 ms/op
     p(99.0000) =      7.299 ms/op
     p(99.9000) =     21.244 ms/op
     p(99.9900) =     28.738 ms/op
     p(99.9990) =     29.837 ms/op
     p(99.9999) =     30.245 ms/op
    p(100.0000) =     30.245 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.079 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 3.962 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.666 ±(99.9%) 0.010 ms/op
Iteration   1: 3.623 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.974 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   4.014 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   7.637 ms/op
                 getUser·p0.999:  20.036 ms/op
                 getUser·p0.9999: 23.604 ms/op
                 getUser·p1.00:   24.609 ms/op

Iteration   2: 3.786 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.386 ms/op
                 getUser·p0.50:   3.543 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   5.284 ms/op
                 getUser·p0.99:   7.840 ms/op
                 getUser·p0.999:  22.202 ms/op
                 getUser·p0.9999: 24.379 ms/op
                 getUser·p1.00:   24.740 ms/op

Iteration   3: 3.645 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.069 ms/op
                 getUser·p0.50:   3.514 ms/op
                 getUser·p0.90:   4.055 ms/op
                 getUser·p0.95:   4.366 ms/op
                 getUser·p0.99:   7.455 ms/op
                 getUser·p0.999:  17.164 ms/op
                 getUser·p0.9999: 28.308 ms/op
                 getUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 260489
  mean =      3.683 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2107 
    [ 2.500,  5.000) = 247389 
    [ 5.000,  7.500) = 7973 
    [ 7.500, 10.000) = 2285 
    [10.000, 12.500) = 332 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.069 ms/op
     p(50.0000) =      3.498 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      7.660 ms/op
     p(99.9000) =     20.447 ms/op
     p(99.9900) =     27.427 ms/op
     p(99.9990) =     29.470 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.444 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 4.740 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.394 ±(99.9%) 0.016 ms/op
Iteration   1: 4.418 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.708 ms/op
                 listUser·p0.50:   4.162 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   8.831 ms/op
                 listUser·p0.999:  21.058 ms/op
                 listUser·p0.9999: 27.297 ms/op
                 listUser·p1.00:   27.918 ms/op

Iteration   2: 4.297 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   4.088 ms/op
                 listUser·p0.90:   4.854 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   9.126 ms/op
                 listUser·p0.999:  16.302 ms/op
                 listUser·p0.9999: 17.231 ms/op
                 listUser·p1.00:   17.891 ms/op

Iteration   3: 4.490 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.003 ms/op
                 listUser·p0.50:   4.366 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.308 ms/op
                 listUser·p0.99:   8.864 ms/op
                 listUser·p0.999:  15.270 ms/op
                 listUser·p0.9999: 27.881 ms/op
                 listUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 218110
  mean =      4.400 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 199185 
    [ 5.000,  7.500) = 14009 
    [ 7.500, 10.000) = 3634 
    [10.000, 12.500) = 617 
    [12.500, 15.000) = 226 
    [15.000, 17.500) = 257 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 58 

  Percentiles, ms/op:
      p(0.0000) =      1.708 ms/op
     p(50.0000) =      4.211 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      8.913 ms/op
     p(99.9000) =     16.515 ms/op
     p(99.9900) =     27.026 ms/op
     p(99.9990) =     28.794 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.563 ± 4.193  ops/ms
ClientPb.existUser                       thrpt       3   9.162 ± 3.743  ops/ms
ClientPb.getUser                         thrpt       3   8.542 ± 1.712  ops/ms
ClientPb.listUser                        thrpt       3   7.268 ± 1.236  ops/ms
ClientPb.createUser                       avgt       3   3.671 ± 0.295   ms/op
ClientPb.existUser                        avgt       3   3.493 ± 1.054   ms/op
ClientPb.getUser                          avgt       3   3.615 ± 1.028   ms/op
ClientPb.listUser                         avgt       3   4.348 ± 0.842   ms/op
ClientPb.createUser                     sample  263193   3.646 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.799           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.449           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.162           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.612           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.324           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.794           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.770           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.278           ms/op
ClientPb.existUser                      sample  272672   3.519 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.120           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.383           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.850           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.295           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.299           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.244           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.738           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.245           ms/op
ClientPb.getUser                        sample  260489   3.683 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.069           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.498           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.190           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.710           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.660           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.447           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.427           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.275           ms/op
ClientPb.listUser                       sample  218110   4.400 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.708           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.211           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.932           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.423           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.913           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.515           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.026           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.869           ms/op
