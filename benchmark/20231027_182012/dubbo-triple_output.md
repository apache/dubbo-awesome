# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.898 ops/ms
# Warmup Iteration   2: 3.519 ops/ms
# Warmup Iteration   3: 7.070 ops/ms
Iteration   1: 7.731 ops/ms
Iteration   2: 8.334 ops/ms
Iteration   3: 8.404 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.156 ±(99.9%) 6.747 ops/ms [Average]
  (min, avg, max) = (7.731, 8.156, 8.404), stdev = 0.370
  CI (99.9%): [1.410, 14.903] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.427 ops/ms
# Warmup Iteration   2: 7.851 ops/ms
# Warmup Iteration   3: 8.600 ops/ms
Iteration   1: 8.941 ops/ms
Iteration   2: 9.043 ops/ms
Iteration   3: 9.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.999 ±(99.9%) 0.954 ops/ms [Average]
  (min, avg, max) = (8.941, 8.999, 9.043), stdev = 0.052
  CI (99.9%): [8.045, 9.953] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.561 ops/ms
# Warmup Iteration   2: 7.522 ops/ms
# Warmup Iteration   3: 8.059 ops/ms
Iteration   1: 8.436 ops/ms
Iteration   2: 8.204 ops/ms
Iteration   3: 8.616 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.419 ±(99.9%) 3.771 ops/ms [Average]
  (min, avg, max) = (8.204, 8.419, 8.616), stdev = 0.207
  CI (99.9%): [4.648, 12.189] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.447 ops/ms
# Warmup Iteration   2: 6.449 ops/ms
# Warmup Iteration   3: 6.945 ops/ms
Iteration   1: 7.048 ops/ms
Iteration   2: 7.234 ops/ms
Iteration   3: 7.025 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.102 ±(99.9%) 2.091 ops/ms [Average]
  (min, avg, max) = (7.025, 7.102, 7.234), stdev = 0.115
  CI (99.9%): [5.011, 9.193] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 12.480 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.073 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.131 ±(99.9%) 0.003 ms/op
Iteration   1: 3.880 ±(99.9%) 0.004 ms/op
Iteration   2: 3.817 ±(99.9%) 0.003 ms/op
Iteration   3: 3.700 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.799 ±(99.9%) 1.665 ms/op [Average]
  (min, avg, max) = (3.700, 3.799, 3.880), stdev = 0.091
  CI (99.9%): [2.134, 5.464] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 11.217 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.901 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.583 ±(99.9%) 0.004 ms/op
Iteration   1: 3.523 ±(99.9%) 0.003 ms/op
Iteration   2: 3.664 ±(99.9%) 0.003 ms/op
Iteration   3: 3.616 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.601 ±(99.9%) 1.309 ms/op [Average]
  (min, avg, max) = (3.523, 3.601, 3.664), stdev = 0.072
  CI (99.9%): [2.292, 4.910] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.319 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.354 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.768 ±(99.9%) 0.007 ms/op
Iteration   1: 3.950 ±(99.9%) 0.005 ms/op
Iteration   2: 3.676 ±(99.9%) 0.006 ms/op
Iteration   3: 3.682 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.769 ±(99.9%) 2.858 ms/op [Average]
  (min, avg, max) = (3.676, 3.769, 3.950), stdev = 0.157
  CI (99.9%): [0.911, 6.627] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 12.623 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 5.154 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.494 ±(99.9%) 0.007 ms/op
Iteration   1: 4.460 ±(99.9%) 0.007 ms/op
Iteration   2: 4.400 ±(99.9%) 0.007 ms/op
Iteration   3: 4.421 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.427 ±(99.9%) 0.565 ms/op [Average]
  (min, avg, max) = (4.400, 4.427, 4.460), stdev = 0.031
  CI (99.9%): [3.862, 4.992] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.758 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.329 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.107 ±(99.9%) 0.016 ms/op
Iteration   1: 3.715 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.993 ms/op
                 createUser·p0.50:   3.711 ms/op
                 createUser·p0.90:   4.063 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   6.504 ms/op
                 createUser·p0.999:  20.870 ms/op
                 createUser·p0.9999: 25.585 ms/op
                 createUser·p1.00:   27.034 ms/op

Iteration   2: 3.792 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.755 ms/op
                 createUser·p0.50:   3.723 ms/op
                 createUser·p0.90:   4.358 ms/op
                 createUser·p0.95:   4.792 ms/op
                 createUser·p0.99:   6.965 ms/op
                 createUser·p0.999:  14.774 ms/op
                 createUser·p0.9999: 29.959 ms/op
                 createUser·p1.00:   30.867 ms/op

Iteration   3: 3.960 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.413 ms/op
                 createUser·p0.50:   3.858 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   4.882 ms/op
                 createUser·p0.99:   6.783 ms/op
                 createUser·p0.999:  26.493 ms/op
                 createUser·p0.9999: 32.340 ms/op
                 createUser·p1.00:   33.128 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 251080
  mean =      3.820 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2676 
    [ 2.500,  5.000) = 239930 
    [ 5.000,  7.500) = 6704 
    [ 7.500, 10.000) = 1076 
    [10.000, 12.500) = 217 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.993 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     22.378 ms/op
     p(99.9900) =     30.540 ms/op
     p(99.9990) =     32.554 ms/op
     p(99.9999) =     33.128 ms/op
    p(100.0000) =     33.128 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.752 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 3.818 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.615 ±(99.9%) 0.010 ms/op
Iteration   1: 3.613 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.092 ms/op
                 existUser·p0.50:   3.539 ms/op
                 existUser·p0.90:   4.026 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   6.365 ms/op
                 existUser·p0.999:  21.968 ms/op
                 existUser·p0.9999: 24.389 ms/op
                 existUser·p1.00:   25.100 ms/op

Iteration   2: 3.670 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.546 ms/op
                 existUser·p0.50:   3.551 ms/op
                 existUser·p0.90:   4.162 ms/op
                 existUser·p0.95:   4.579 ms/op
                 existUser·p0.99:   7.299 ms/op
                 existUser·p0.999:  13.631 ms/op
                 existUser·p0.9999: 35.408 ms/op
                 existUser·p1.00:   36.962 ms/op

Iteration   3: 3.746 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.118 ms/op
                 existUser·p0.50:   3.641 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.702 ms/op
                 existUser·p0.99:   6.438 ms/op
                 existUser·p0.999:  25.857 ms/op
                 existUser·p0.9999: 31.225 ms/op
                 existUser·p1.00:   31.818 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 261142
  mean =      3.675 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2305 
    [ 2.500,  5.000) = 250856 
    [ 5.000,  7.500) = 6237 
    [ 7.500, 10.000) = 1109 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 193 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.186 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     17.212 ms/op
     p(99.9900) =     34.669 ms/op
     p(99.9990) =     36.372 ms/op
     p(99.9999) =     36.962 ms/op
    p(100.0000) =     36.962 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 11.833 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.229 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.967 ±(99.9%) 0.014 ms/op
Iteration   1: 3.745 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.225 ms/op
                 getUser·p0.50:   3.654 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   6.783 ms/op
                 getUser·p0.999:  15.008 ms/op
                 getUser·p0.9999: 24.165 ms/op
                 getUser·p1.00:   24.871 ms/op

Iteration   2: 3.785 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.466 ms/op
                 getUser·p0.50:   3.658 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   4.579 ms/op
                 getUser·p0.99:   7.447 ms/op
                 getUser·p0.999:  23.902 ms/op
                 getUser·p0.9999: 28.034 ms/op
                 getUser·p1.00:   28.639 ms/op

Iteration   3: 3.765 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.122 ms/op
                 getUser·p0.50:   3.678 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   6.160 ms/op
                 getUser·p0.999:  25.697 ms/op
                 getUser·p0.9999: 28.280 ms/op
                 getUser·p1.00:   29.753 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 254737
  mean =      3.765 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1310 
    [ 2.500,  5.000) = 245559 
    [ 5.000,  7.500) = 6128 
    [ 7.500, 10.000) = 950 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 260 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 106 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     21.440 ms/op
     p(99.9900) =     27.951 ms/op
     p(99.9990) =     29.011 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 13.383 ±(99.9%) 0.183 ms/op
# Warmup Iteration   2: 5.041 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.706 ±(99.9%) 0.013 ms/op
Iteration   1: 4.594 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.679 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   8.126 ms/op
                 listUser·p0.999:  19.333 ms/op
                 listUser·p0.9999: 21.712 ms/op
                 listUser·p1.00:   22.315 ms/op

Iteration   2: 4.493 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.319 ms/op
                 listUser·p0.50:   4.383 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.333 ms/op
                 listUser·p0.99:   7.988 ms/op
                 listUser·p0.999:  16.761 ms/op
                 listUser·p0.9999: 19.523 ms/op
                 listUser·p1.00:   19.890 ms/op

Iteration   3: 4.487 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.294 ms/op
                 listUser·p0.50:   4.334 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   8.143 ms/op
                 listUser·p0.999:  18.637 ms/op
                 listUser·p0.9999: 21.909 ms/op
                 listUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 211951
  mean =      4.524 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49 
    [ 2.500,  5.000) = 181509 
    [ 5.000,  7.500) = 27328 
    [ 7.500, 10.000) = 1876 
    [10.000, 12.500) = 330 
    [12.500, 15.000) = 302 
    [15.000, 17.500) = 332 
    [17.500, 20.000) = 140 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.294 ms/op
     p(50.0000) =      4.383 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      5.480 ms/op
     p(99.0000) =      8.110 ms/op
     p(99.9000) =     18.027 ms/op
     p(99.9900) =     21.188 ms/op
     p(99.9990) =     22.990 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.156 ± 6.747  ops/ms
ClientPb.existUser                       thrpt       3   8.999 ± 0.954  ops/ms
ClientPb.getUser                         thrpt       3   8.419 ± 3.771  ops/ms
ClientPb.listUser                        thrpt       3   7.102 ± 2.091  ops/ms
ClientPb.createUser                       avgt       3   3.799 ± 1.665   ms/op
ClientPb.existUser                        avgt       3   3.601 ± 1.309   ms/op
ClientPb.getUser                          avgt       3   3.769 ± 2.858   ms/op
ClientPb.listUser                         avgt       3   4.427 ± 0.565   ms/op
ClientPb.createUser                     sample  251080   3.820 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.993           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.342           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.743           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.717           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.378           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.540           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.128           ms/op
ClientPb.existUser                      sample  261142   3.675 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.092           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.186           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.571           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.734           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.212           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.669           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.962           ms/op
ClientPb.getUser                        sample  254737   3.765 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.122           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.662           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.276           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.588           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.750           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.440           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.951           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.753           ms/op
ClientPb.listUser                       sample  211951   4.524 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.294           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.145           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.480           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.110           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.027           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.188           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.298           ms/op
