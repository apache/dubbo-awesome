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
# Warmup Iteration   1: 1.756 ops/ms
# Warmup Iteration   2: 4.061 ops/ms
# Warmup Iteration   3: 7.585 ops/ms
Iteration   1: 7.631 ops/ms
Iteration   2: 8.115 ops/ms
Iteration   3: 8.398 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.048 ±(99.9%) 7.074 ops/ms [Average]
  (min, avg, max) = (7.631, 8.048, 8.398), stdev = 0.388
  CI (99.9%): [0.974, 15.122] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.445 ops/ms
# Warmup Iteration   2: 7.346 ops/ms
# Warmup Iteration   3: 8.166 ops/ms
Iteration   1: 8.420 ops/ms
Iteration   2: 8.350 ops/ms
Iteration   3: 8.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.317 ±(99.9%) 2.239 ops/ms [Average]
  (min, avg, max) = (8.182, 8.317, 8.420), stdev = 0.123
  CI (99.9%): [6.079, 10.556] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.311 ops/ms
# Warmup Iteration   2: 6.666 ops/ms
# Warmup Iteration   3: 8.147 ops/ms
Iteration   1: 8.097 ops/ms
Iteration   2: 8.348 ops/ms
Iteration   3: 7.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.146 ±(99.9%) 3.332 ops/ms [Average]
  (min, avg, max) = (7.992, 8.146, 8.348), stdev = 0.183
  CI (99.9%): [4.813, 11.478] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 1.915 ops/ms
# Warmup Iteration   2: 5.822 ops/ms
# Warmup Iteration   3: 6.840 ops/ms
Iteration   1: 6.858 ops/ms
Iteration   2: 7.016 ops/ms
Iteration   3: 6.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.873 ±(99.9%) 2.477 ops/ms [Average]
  (min, avg, max) = (6.745, 6.873, 7.016), stdev = 0.136
  CI (99.9%): [4.396, 9.350] (assumes normal distribution)


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
# Warmup Iteration   1: 12.382 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.667 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.234 ±(99.9%) 0.005 ms/op
Iteration   1: 3.889 ±(99.9%) 0.013 ms/op
Iteration   2: 3.910 ±(99.9%) 0.007 ms/op
Iteration   3: 3.928 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.909 ±(99.9%) 0.356 ms/op [Average]
  (min, avg, max) = (3.889, 3.909, 3.928), stdev = 0.020
  CI (99.9%): [3.553, 4.265] (assumes normal distribution)


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
# Warmup Iteration   1: 11.733 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.245 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.950 ±(99.9%) 0.006 ms/op
Iteration   1: 3.750 ±(99.9%) 0.011 ms/op
Iteration   2: 3.770 ±(99.9%) 0.004 ms/op
Iteration   3: 3.739 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.753 ±(99.9%) 0.287 ms/op [Average]
  (min, avg, max) = (3.739, 3.753, 3.770), stdev = 0.016
  CI (99.9%): [3.466, 4.040] (assumes normal distribution)


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
# Warmup Iteration   1: 11.808 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.827 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.101 ±(99.9%) 0.008 ms/op
Iteration   1: 4.091 ±(99.9%) 0.005 ms/op
Iteration   2: 3.906 ±(99.9%) 0.007 ms/op
Iteration   3: 3.785 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.928 ±(99.9%) 2.811 ms/op [Average]
  (min, avg, max) = (3.785, 3.928, 4.091), stdev = 0.154
  CI (99.9%): [1.117, 6.738] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 14.702 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.263 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.632 ±(99.9%) 0.013 ms/op
Iteration   1: 4.683 ±(99.9%) 0.010 ms/op
Iteration   2: 4.663 ±(99.9%) 0.016 ms/op
Iteration   3: 4.598 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.648 ±(99.9%) 0.811 ms/op [Average]
  (min, avg, max) = (4.598, 4.648, 4.683), stdev = 0.044
  CI (99.9%): [3.837, 5.460] (assumes normal distribution)


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
# Warmup Iteration   1: 11.916 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.816 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.409 ±(99.9%) 0.021 ms/op
Iteration   1: 3.812 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.712 ms/op
                 createUser·p0.50:   3.731 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.489 ms/op
                 createUser·p0.99:   6.416 ms/op
                 createUser·p0.999:  23.986 ms/op
                 createUser·p0.9999: 26.680 ms/op
                 createUser·p1.00:   27.197 ms/op

Iteration   2: 3.851 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.722 ms/op
                 createUser·p0.50:   3.719 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.596 ms/op
                 createUser·p0.99:   7.182 ms/op
                 createUser·p0.999:  12.829 ms/op
                 createUser·p0.9999: 27.539 ms/op
                 createUser·p1.00:   28.344 ms/op

Iteration   3: 3.880 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.591 ms/op
                 createUser·p0.50:   3.695 ms/op
                 createUser·p0.90:   4.383 ms/op
                 createUser·p0.95:   4.841 ms/op
                 createUser·p0.99:   7.291 ms/op
                 createUser·p0.999:  29.510 ms/op
                 createUser·p0.9999: 33.186 ms/op
                 createUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 249220
  mean =      3.848 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 340 
    [ 2.500,  5.000) = 240506 
    [ 5.000,  7.500) = 6576 
    [ 7.500, 10.000) = 1148 
    [10.000, 12.500) = 278 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 119 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.591 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     23.808 ms/op
     p(99.9900) =     32.413 ms/op
     p(99.9990) =     33.751 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.358 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.417 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.999 ±(99.9%) 0.013 ms/op
Iteration   1: 3.814 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.354 ms/op
                 existUser·p0.50:   3.686 ms/op
                 existUser·p0.90:   4.194 ms/op
                 existUser·p0.95:   4.555 ms/op
                 existUser·p0.99:   6.740 ms/op
                 existUser·p0.999:  11.010 ms/op
                 existUser·p0.9999: 25.317 ms/op
                 existUser·p1.00:   25.952 ms/op

Iteration   2: 3.714 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.585 ms/op
                 existUser·p0.50:   3.613 ms/op
                 existUser·p0.90:   4.076 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  24.558 ms/op
                 existUser·p0.9999: 27.747 ms/op
                 existUser·p1.00:   28.115 ms/op

Iteration   3: 3.708 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.286 ms/op
                 existUser·p0.50:   3.625 ms/op
                 existUser·p0.90:   4.022 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   6.119 ms/op
                 existUser·p0.999:  13.926 ms/op
                 existUser·p0.9999: 28.959 ms/op
                 existUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 256280
  mean =      3.745 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 464 
    [ 2.500,  5.000) = 249740 
    [ 5.000,  7.500) = 4631 
    [ 7.500, 10.000) = 734 
    [10.000, 12.500) = 370 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 113 

  Percentiles, ms/op:
      p(0.0000) =      1.286 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.357 ms/op
     p(99.9000) =     13.910 ms/op
     p(99.9900) =     27.975 ms/op
     p(99.9990) =     29.520 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


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
# Warmup Iteration   1: 12.657 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 4.466 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.157 ±(99.9%) 0.016 ms/op
Iteration   1: 4.061 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.663 ms/op
                 getUser·p0.50:   3.826 ms/op
                 getUser·p0.90:   4.866 ms/op
                 getUser·p0.95:   5.603 ms/op
                 getUser·p0.99:   7.627 ms/op
                 getUser·p0.999:  17.531 ms/op
                 getUser·p0.9999: 23.274 ms/op
                 getUser·p1.00:   23.626 ms/op

Iteration   2: 3.946 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.870 ms/op
                 getUser·p0.50:   3.854 ms/op
                 getUser·p0.90:   4.276 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   7.135 ms/op
                 getUser·p0.999:  21.758 ms/op
                 getUser·p0.9999: 25.064 ms/op
                 getUser·p1.00:   25.723 ms/op

Iteration   3: 3.864 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.411 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.284 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   6.964 ms/op
                 getUser·p0.999:  11.207 ms/op
                 getUser·p0.9999: 26.697 ms/op
                 getUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 242480
  mean =      3.955 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 168 
    [ 2.500,  5.000) = 230476 
    [ 5.000,  7.500) = 9694 
    [ 7.500, 10.000) = 1614 
    [10.000, 12.500) = 213 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 118 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.411 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.973 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     15.679 ms/op
     p(99.9900) =     25.387 ms/op
     p(99.9990) =     27.418 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


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
# Warmup Iteration   1: 13.843 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 5.309 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.750 ±(99.9%) 0.016 ms/op
Iteration   1: 4.668 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.884 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   9.044 ms/op
                 listUser·p0.999:  22.297 ms/op
                 listUser·p0.9999: 24.941 ms/op
                 listUser·p1.00:   26.673 ms/op

Iteration   2: 4.703 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   6.308 ms/op
                 listUser·p0.99:   8.913 ms/op
                 listUser·p0.999:  18.547 ms/op
                 listUser·p0.9999: 22.224 ms/op
                 listUser·p1.00:   27.886 ms/op

Iteration   3: 4.601 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.314 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   8.069 ms/op
                 listUser·p0.999:  16.368 ms/op
                 listUser·p0.9999: 20.414 ms/op
                 listUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 205867
  mean =      4.657 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 178172 
    [ 5.000,  7.500) = 22334 
    [ 7.500, 10.000) = 4347 
    [10.000, 12.500) = 520 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 181 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.884 ms/op
     p(50.0000) =      4.473 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      8.618 ms/op
     p(99.9000) =     18.518 ms/op
     p(99.9900) =     23.803 ms/op
     p(99.9990) =     26.644 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.048 ± 7.074  ops/ms
ClientPb.existUser                       thrpt       3   8.317 ± 2.239  ops/ms
ClientPb.getUser                         thrpt       3   8.146 ± 3.332  ops/ms
ClientPb.listUser                        thrpt       3   6.873 ± 2.477  ops/ms
ClientPb.createUser                       avgt       3   3.909 ± 0.356   ms/op
ClientPb.existUser                        avgt       3   3.753 ± 0.287   ms/op
ClientPb.getUser                          avgt       3   3.928 ± 2.811   ms/op
ClientPb.listUser                         avgt       3   4.648 ± 0.811   ms/op
ClientPb.createUser                     sample  249220   3.848 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.591           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.715           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.252           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.628           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.004           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.808           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.413           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.931           ms/op
ClientPb.existUser                      sample  256280   3.745 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.286           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.637           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.104           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.366           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.357           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.910           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.975           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.590           ms/op
ClientPb.getUser                        sample  242480   3.955 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.411           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.448           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.973           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.266           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.679           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.387           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.820           ms/op
ClientPb.listUser                       sample  205867   4.657 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.884           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.128           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.644           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.618           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.518           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.803           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.886           ms/op
