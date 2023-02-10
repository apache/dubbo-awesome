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
# Warmup Iteration   1: 1.109 ops/ms
# Warmup Iteration   2: 2.527 ops/ms
# Warmup Iteration   3: 5.408 ops/ms
Iteration   1: 5.605 ops/ms
Iteration   2: 5.756 ops/ms
Iteration   3: 5.823 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.728 ±(99.9%) 2.033 ops/ms [Average]
  (min, avg, max) = (5.605, 5.728, 5.823), stdev = 0.111
  CI (99.9%): [3.695, 7.761] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.813 ops/ms
# Warmup Iteration   2: 4.734 ops/ms
# Warmup Iteration   3: 5.761 ops/ms
Iteration   1: 6.076 ops/ms
Iteration   2: 6.273 ops/ms
Iteration   3: 6.337 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.229 ±(99.9%) 2.481 ops/ms [Average]
  (min, avg, max) = (6.076, 6.229, 6.337), stdev = 0.136
  CI (99.9%): [3.748, 8.710] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.537 ops/ms
# Warmup Iteration   2: 4.713 ops/ms
# Warmup Iteration   3: 5.665 ops/ms
Iteration   1: 5.784 ops/ms
Iteration   2: 5.899 ops/ms
Iteration   3: 5.960 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.881 ±(99.9%) 1.629 ops/ms [Average]
  (min, avg, max) = (5.784, 5.881, 5.960), stdev = 0.089
  CI (99.9%): [4.251, 7.510] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.535 ops/ms
# Warmup Iteration   2: 3.918 ops/ms
# Warmup Iteration   3: 5.002 ops/ms
Iteration   1: 4.905 ops/ms
Iteration   2: 5.018 ops/ms
Iteration   3: 5.119 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.014 ±(99.9%) 1.952 ops/ms [Average]
  (min, avg, max) = (4.905, 5.014, 5.119), stdev = 0.107
  CI (99.9%): [3.062, 6.966] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 17.958 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 6.315 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.607 ±(99.9%) 0.013 ms/op
Iteration   1: 5.496 ±(99.9%) 0.011 ms/op
Iteration   2: 5.499 ±(99.9%) 0.013 ms/op
Iteration   3: 5.330 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.442 ±(99.9%) 1.764 ms/op [Average]
  (min, avg, max) = (5.330, 5.442, 5.499), stdev = 0.097
  CI (99.9%): [3.677, 7.206] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 17.223 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 6.665 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.467 ±(99.9%) 0.005 ms/op
Iteration   1: 5.207 ±(99.9%) 0.009 ms/op
Iteration   2: 5.209 ±(99.9%) 0.010 ms/op
Iteration   3: 5.309 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.242 ±(99.9%) 1.054 ms/op [Average]
  (min, avg, max) = (5.207, 5.242, 5.309), stdev = 0.058
  CI (99.9%): [4.188, 6.296] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 16.846 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 6.267 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.639 ±(99.9%) 0.010 ms/op
Iteration   1: 5.694 ±(99.9%) 0.006 ms/op
Iteration   2: 5.484 ±(99.9%) 0.008 ms/op
Iteration   3: 5.509 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.562 ±(99.9%) 2.099 ms/op [Average]
  (min, avg, max) = (5.484, 5.562, 5.694), stdev = 0.115
  CI (99.9%): [3.463, 7.661] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 18.250 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 7.806 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.557 ±(99.9%) 0.016 ms/op
Iteration   1: 6.216 ±(99.9%) 0.014 ms/op
Iteration   2: 6.217 ±(99.9%) 0.025 ms/op
Iteration   3: 6.316 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.249 ±(99.9%) 1.044 ms/op [Average]
  (min, avg, max) = (6.216, 6.249, 6.316), stdev = 0.057
  CI (99.9%): [5.206, 7.293] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 16.918 ±(99.9%) 0.281 ms/op
# Warmup Iteration   2: 6.565 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 6.113 ±(99.9%) 0.030 ms/op
Iteration   1: 5.327 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   0.833 ms/op
                 createUser·p0.50:   5.054 ms/op
                 createUser·p0.90:   6.316 ms/op
                 createUser·p0.95:   7.381 ms/op
                 createUser·p0.99:   10.268 ms/op
                 createUser·p0.999:  22.149 ms/op
                 createUser·p0.9999: 30.376 ms/op
                 createUser·p1.00:   31.785 ms/op

Iteration   2: 5.404 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.298 ms/op
                 createUser·p0.50:   5.202 ms/op
                 createUser·p0.90:   6.431 ms/op
                 createUser·p0.95:   7.332 ms/op
                 createUser·p0.99:   10.600 ms/op
                 createUser·p0.999:  23.959 ms/op
                 createUser·p0.9999: 27.102 ms/op
                 createUser·p1.00:   28.574 ms/op

Iteration   3: 5.380 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.864 ms/op
                 createUser·p0.50:   5.153 ms/op
                 createUser·p0.90:   6.382 ms/op
                 createUser·p0.95:   7.643 ms/op
                 createUser·p0.99:   10.207 ms/op
                 createUser·p0.999:  25.612 ms/op
                 createUser·p0.9999: 33.697 ms/op
                 createUser·p1.00:   34.341 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 178635
  mean =      5.370 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 67433 
    [ 5.000,  7.500) = 102627 
    [ 7.500, 10.000) = 6428 
    [10.000, 12.500) = 1403 
    [12.500, 15.000) = 377 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      5.136 ms/op
     p(90.0000) =      6.390 ms/op
     p(95.0000) =      7.422 ms/op
     p(99.0000) =     10.338 ms/op
     p(99.9000) =     23.519 ms/op
     p(99.9900) =     31.597 ms/op
     p(99.9990) =     34.238 ms/op
     p(99.9999) =     34.341 ms/op
    p(100.0000) =     34.341 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.692 ±(99.9%) 0.272 ms/op
# Warmup Iteration   2: 6.736 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.333 ±(99.9%) 0.018 ms/op
Iteration   1: 5.409 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.195 ms/op
                 existUser·p0.50:   5.046 ms/op
                 existUser·p0.90:   6.758 ms/op
                 existUser·p0.95:   8.102 ms/op
                 existUser·p0.99:   10.699 ms/op
                 existUser·p0.999:  25.095 ms/op
                 existUser·p0.9999: 40.010 ms/op
                 existUser·p1.00:   41.943 ms/op

Iteration   2: 5.270 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.298 ms/op
                 existUser·p0.50:   4.866 ms/op
                 existUser·p0.90:   6.922 ms/op
                 existUser·p0.95:   7.840 ms/op
                 existUser·p0.99:   10.256 ms/op
                 existUser·p0.999:  15.078 ms/op
                 existUser·p0.9999: 30.275 ms/op
                 existUser·p1.00:   31.031 ms/op

Iteration   3: 5.139 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.445 ms/op
                 existUser·p0.50:   4.809 ms/op
                 existUser·p0.90:   6.078 ms/op
                 existUser·p0.95:   7.315 ms/op
                 existUser·p0.99:   10.535 ms/op
                 existUser·p0.999:  23.336 ms/op
                 existUser·p0.9999: 27.613 ms/op
                 existUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 182101
  mean =      5.270 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 102932 
    [ 5.000, 10.000) = 76785 
    [10.000, 15.000) = 2117 
    [15.000, 20.000) = 83 
    [20.000, 25.000) = 55 
    [25.000, 30.000) = 86 
    [30.000, 35.000) = 26 
    [35.000, 40.000) = 12 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      2.195 ms/op
     p(50.0000) =      4.899 ms/op
     p(90.0000) =      6.636 ms/op
     p(95.0000) =      7.864 ms/op
     p(99.0000) =     10.502 ms/op
     p(99.9000) =     22.243 ms/op
     p(99.9900) =     34.727 ms/op
     p(99.9990) =     41.835 ms/op
     p(99.9999) =     41.943 ms/op
    p(100.0000) =     41.943 ms/op


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
# Warmup Iteration   1: 17.397 ±(99.9%) 0.280 ms/op
# Warmup Iteration   2: 6.289 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.741 ±(99.9%) 0.020 ms/op
Iteration   1: 5.557 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.789 ms/op
                 getUser·p0.50:   5.267 ms/op
                 getUser·p0.90:   6.488 ms/op
                 getUser·p0.95:   7.553 ms/op
                 getUser·p0.99:   11.158 ms/op
                 getUser·p0.999:  24.479 ms/op
                 getUser·p0.9999: 28.008 ms/op
                 getUser·p1.00:   28.475 ms/op

Iteration   2: 5.697 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.507 ms/op
                 getUser·p0.50:   5.259 ms/op
                 getUser·p0.90:   7.135 ms/op
                 getUser·p0.95:   8.667 ms/op
                 getUser·p0.99:   12.747 ms/op
                 getUser·p0.999:  19.758 ms/op
                 getUser·p0.9999: 30.101 ms/op
                 getUser·p1.00:   30.671 ms/op

Iteration   3: 5.488 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.618 ms/op
                 getUser·p0.50:   5.161 ms/op
                 getUser·p0.90:   6.504 ms/op
                 getUser·p0.95:   7.741 ms/op
                 getUser·p0.99:   11.117 ms/op
                 getUser·p0.999:  27.984 ms/op
                 getUser·p0.9999: 34.341 ms/op
                 getUser·p1.00:   34.800 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 171946
  mean =      5.579 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 58430 
    [ 5.000,  7.500) = 102783 
    [ 7.500, 10.000) = 7357 
    [10.000, 12.500) = 2107 
    [12.500, 15.000) = 766 
    [15.000, 17.500) = 215 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.618 ms/op
     p(50.0000) =      5.226 ms/op
     p(90.0000) =      6.685 ms/op
     p(95.0000) =      7.979 ms/op
     p(99.0000) =     11.698 ms/op
     p(99.9000) =     22.643 ms/op
     p(99.9900) =     33.334 ms/op
     p(99.9990) =     34.705 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


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
# Warmup Iteration   1: 17.716 ±(99.9%) 0.300 ms/op
# Warmup Iteration   2: 7.856 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 6.502 ±(99.9%) 0.024 ms/op
Iteration   1: 6.256 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   3.080 ms/op
                 listUser·p0.50:   5.964 ms/op
                 listUser·p0.90:   7.070 ms/op
                 listUser·p0.95:   8.520 ms/op
                 listUser·p0.99:   11.502 ms/op
                 listUser·p0.999:  25.354 ms/op
                 listUser·p0.9999: 27.845 ms/op
                 listUser·p1.00:   29.032 ms/op

Iteration   2: 6.411 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.503 ms/op
                 listUser·p0.50:   6.103 ms/op
                 listUser·p0.90:   7.422 ms/op
                 listUser·p0.95:   8.815 ms/op
                 listUser·p0.99:   11.977 ms/op
                 listUser·p0.999:  28.620 ms/op
                 listUser·p0.9999: 31.130 ms/op
                 listUser·p1.00:   31.261 ms/op

Iteration   3: 6.678 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.911 ms/op
                 listUser·p0.50:   6.226 ms/op
                 listUser·p0.90:   8.454 ms/op
                 listUser·p0.95:   10.273 ms/op
                 listUser·p0.99:   13.386 ms/op
                 listUser·p0.999:  22.479 ms/op
                 listUser·p0.9999: 27.794 ms/op
                 listUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 148962
  mean =      6.444 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 3454 
    [ 5.000,  7.500) = 130140 
    [ 7.500, 10.000) = 9648 
    [10.000, 12.500) = 4411 
    [12.500, 15.000) = 738 
    [15.000, 17.500) = 186 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 103 
    [27.500, 30.000) = 77 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.911 ms/op
     p(50.0000) =      6.087 ms/op
     p(90.0000) =      7.561 ms/op
     p(95.0000) =      9.421 ms/op
     p(99.0000) =     12.190 ms/op
     p(99.9000) =     25.987 ms/op
     p(99.9900) =     29.960 ms/op
     p(99.9990) =     31.261 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.728 ± 2.033  ops/ms
ClientPb.existUser                       thrpt       3   6.229 ± 2.481  ops/ms
ClientPb.getUser                         thrpt       3   5.881 ± 1.629  ops/ms
ClientPb.listUser                        thrpt       3   5.014 ± 1.952  ops/ms
ClientPb.createUser                       avgt       3   5.442 ± 1.764   ms/op
ClientPb.existUser                        avgt       3   5.242 ± 1.054   ms/op
ClientPb.getUser                          avgt       3   5.562 ± 2.099   ms/op
ClientPb.listUser                         avgt       3   6.249 ± 1.044   ms/op
ClientPb.createUser                     sample  178635   5.370 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.833           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.136           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.390           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.422           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.338           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.519           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.597           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.341           ms/op
ClientPb.existUser                      sample  182101   5.270 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.195           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.899           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.636           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.864           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.502           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.243           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.727           ms/op
ClientPb.existUser:existUser·p1.00      sample          41.943           ms/op
ClientPb.getUser                        sample  171946   5.579 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.618           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.226           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.685           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.979           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.698           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.643           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.334           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.800           ms/op
ClientPb.listUser                       sample  148962   6.444 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.911           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.087           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.561           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.421           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.190           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.987           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.960           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.261           ms/op
