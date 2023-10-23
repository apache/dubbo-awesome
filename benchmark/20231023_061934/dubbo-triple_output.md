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
# Warmup Iteration   1: 2.200 ops/ms
# Warmup Iteration   2: 5.643 ops/ms
# Warmup Iteration   3: 8.269 ops/ms
Iteration   1: 8.990 ops/ms
Iteration   2: 9.250 ops/ms
Iteration   3: 9.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.108 ±(99.9%) 2.404 ops/ms [Average]
  (min, avg, max) = (8.990, 9.108, 9.250), stdev = 0.132
  CI (99.9%): [6.704, 11.511] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.968 ops/ms
# Warmup Iteration   2: 8.653 ops/ms
# Warmup Iteration   3: 9.603 ops/ms
Iteration   1: 9.634 ops/ms
Iteration   2: 9.648 ops/ms
Iteration   3: 9.738 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.673 ±(99.9%) 1.024 ops/ms [Average]
  (min, avg, max) = (9.634, 9.673, 9.738), stdev = 0.056
  CI (99.9%): [8.649, 10.697] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.375 ops/ms
# Warmup Iteration   2: 8.480 ops/ms
# Warmup Iteration   3: 9.118 ops/ms
Iteration   1: 9.169 ops/ms
Iteration   2: 9.466 ops/ms
Iteration   3: 9.371 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.335 ±(99.9%) 2.762 ops/ms [Average]
  (min, avg, max) = (9.169, 9.335, 9.466), stdev = 0.151
  CI (99.9%): [6.573, 12.098] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 2.847 ops/ms
# Warmup Iteration   2: 7.185 ops/ms
# Warmup Iteration   3: 7.678 ops/ms
Iteration   1: 7.697 ops/ms
Iteration   2: 7.901 ops/ms
Iteration   3: 7.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.732 ±(99.9%) 2.827 ops/ms [Average]
  (min, avg, max) = (7.597, 7.732, 7.901), stdev = 0.155
  CI (99.9%): [4.905, 10.559] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.216 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.782 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.692 ±(99.9%) 0.005 ms/op
Iteration   1: 3.545 ±(99.9%) 0.004 ms/op
Iteration   2: 3.428 ±(99.9%) 0.005 ms/op
Iteration   3: 3.468 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.481 ±(99.9%) 1.083 ms/op [Average]
  (min, avg, max) = (3.428, 3.481, 3.545), stdev = 0.059
  CI (99.9%): [2.397, 4.564] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 9.736 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.559 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.395 ±(99.9%) 0.005 ms/op
Iteration   1: 3.323 ±(99.9%) 0.005 ms/op
Iteration   2: 3.351 ±(99.9%) 0.004 ms/op
Iteration   3: 3.461 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.378 ±(99.9%) 1.328 ms/op [Average]
  (min, avg, max) = (3.323, 3.378, 3.461), stdev = 0.073
  CI (99.9%): [2.050, 4.706] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.645 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.704 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.546 ±(99.9%) 0.003 ms/op
Iteration   1: 3.527 ±(99.9%) 0.003 ms/op
Iteration   2: 3.442 ±(99.9%) 0.004 ms/op
Iteration   3: 3.425 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.465 ±(99.9%) 0.999 ms/op [Average]
  (min, avg, max) = (3.425, 3.465, 3.527), stdev = 0.055
  CI (99.9%): [2.465, 4.464] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.546 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.517 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.237 ±(99.9%) 0.004 ms/op
Iteration   1: 4.246 ±(99.9%) 0.005 ms/op
Iteration   2: 4.172 ±(99.9%) 0.008 ms/op
Iteration   3: 4.236 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.218 ±(99.9%) 0.737 ms/op [Average]
  (min, avg, max) = (4.172, 4.218, 4.246), stdev = 0.040
  CI (99.9%): [3.481, 4.955] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.461 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.097 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.646 ±(99.9%) 0.011 ms/op
Iteration   1: 3.511 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.005 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   6.627 ms/op
                 createUser·p0.999:  21.496 ms/op
                 createUser·p0.9999: 25.712 ms/op
                 createUser·p1.00:   29.000 ms/op

Iteration   2: 3.528 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.505 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   5.816 ms/op
                 createUser·p0.999:  24.084 ms/op
                 createUser·p0.9999: 26.737 ms/op
                 createUser·p1.00:   27.492 ms/op

Iteration   3: 3.469 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.208 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   5.947 ms/op
                 createUser·p0.999:  22.801 ms/op
                 createUser·p0.9999: 26.207 ms/op
                 createUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273872
  mean =      3.502 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4129 
    [ 2.500,  5.000) = 264080 
    [ 5.000,  7.500) = 4534 
    [ 7.500, 10.000) = 590 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 131 
    [25.000, 27.500) = 123 

  Percentiles, ms/op:
      p(0.0000) =      1.005 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.177 ms/op
     p(99.9000) =     21.996 ms/op
     p(99.9900) =     26.398 ms/op
     p(99.9990) =     27.444 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.984 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.596 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.403 ±(99.9%) 0.009 ms/op
Iteration   1: 3.384 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.262 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.842 ms/op
                 existUser·p0.95:   4.080 ms/op
                 existUser·p0.99:   5.038 ms/op
                 existUser·p0.999:  20.349 ms/op
                 existUser·p0.9999: 24.430 ms/op
                 existUser·p1.00:   27.853 ms/op

Iteration   2: 3.411 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.257 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   6.971 ms/op
                 existUser·p0.999:  22.813 ms/op
                 existUser·p0.9999: 25.960 ms/op
                 existUser·p1.00:   26.477 ms/op

Iteration   3: 3.381 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.090 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   5.964 ms/op
                 existUser·p0.999:  20.432 ms/op
                 existUser·p0.9999: 29.116 ms/op
                 existUser·p1.00:   29.852 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282915
  mean =      3.392 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10303 
    [ 2.500,  5.000) = 266668 
    [ 5.000,  7.500) = 4687 
    [ 7.500, 10.000) = 688 
    [10.000, 12.500) = 206 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 116 
    [25.000, 27.500) = 59 

  Percentiles, ms/op:
      p(0.0000) =      1.090 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =     20.417 ms/op
     p(99.9900) =     27.608 ms/op
     p(99.9990) =     29.400 ms/op
     p(99.9999) =     29.852 ms/op
    p(100.0000) =     29.852 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.630 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.701 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.556 ±(99.9%) 0.010 ms/op
Iteration   1: 3.506 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.858 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.145 ms/op
                 getUser·p0.99:   7.037 ms/op
                 getUser·p0.999:  20.897 ms/op
                 getUser·p0.9999: 23.425 ms/op
                 getUser·p1.00:   23.855 ms/op

Iteration   2: 3.431 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.563 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   5.513 ms/op
                 getUser·p0.999:  21.999 ms/op
                 getUser·p0.9999: 25.974 ms/op
                 getUser·p1.00:   27.034 ms/op

Iteration   3: 3.597 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.346 ms/op
                 getUser·p0.50:   3.473 ms/op
                 getUser·p0.90:   4.022 ms/op
                 getUser·p0.95:   4.317 ms/op
                 getUser·p0.99:   6.455 ms/op
                 getUser·p0.999:  19.632 ms/op
                 getUser·p0.9999: 27.984 ms/op
                 getUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273343
  mean =      3.510 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6590 
    [ 2.500,  5.000) = 260428 
    [ 5.000,  7.500) = 5035 
    [ 7.500, 10.000) = 718 
    [10.000, 12.500) = 206 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 89 

  Percentiles, ms/op:
      p(0.0000) =      0.346 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     20.338 ms/op
     p(99.9900) =     26.378 ms/op
     p(99.9990) =     29.535 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.503 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.429 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.232 ±(99.9%) 0.012 ms/op
Iteration   1: 4.276 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.866 ms/op
                 listUser·p0.50:   4.080 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.095 ms/op
                 listUser·p0.99:   7.430 ms/op
                 listUser·p0.999:  22.222 ms/op
                 listUser·p0.9999: 24.530 ms/op
                 listUser·p1.00:   26.116 ms/op

Iteration   2: 4.204 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.581 ms/op
                 listUser·p0.50:   4.084 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  15.958 ms/op
                 listUser·p0.9999: 18.625 ms/op
                 listUser·p1.00:   21.070 ms/op

Iteration   3: 4.145 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.712 ms/op
                 listUser·p0.50:   4.063 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  15.420 ms/op
                 listUser·p0.9999: 20.129 ms/op
                 listUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 228125
  mean =      4.207 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45 
    [ 2.500,  5.000) = 218075 
    [ 5.000,  7.500) = 8126 
    [ 7.500, 10.000) = 1127 
    [10.000, 12.500) = 175 
    [12.500, 15.000) = 255 
    [15.000, 17.500) = 142 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.581 ms/op
     p(50.0000) =      4.076 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     16.237 ms/op
     p(99.9900) =     23.867 ms/op
     p(99.9990) =     25.838 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.108 ± 2.404  ops/ms
ClientPb.existUser                       thrpt       3   9.673 ± 1.024  ops/ms
ClientPb.getUser                         thrpt       3   9.335 ± 2.762  ops/ms
ClientPb.listUser                        thrpt       3   7.732 ± 2.827  ops/ms
ClientPb.createUser                       avgt       3   3.481 ± 1.083   ms/op
ClientPb.existUser                        avgt       3   3.378 ± 1.328   ms/op
ClientPb.getUser                          avgt       3   3.465 ± 0.999   ms/op
ClientPb.listUser                         avgt       3   4.218 ± 0.737   ms/op
ClientPb.createUser                     sample  273872   3.502 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.005           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.375           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.940           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.243           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.177           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.996           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.398           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.000           ms/op
ClientPb.existUser                      sample  282915   3.392 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.090           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.310           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.071           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.275           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.417           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.608           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.852           ms/op
ClientPb.getUser                        sample  273343   3.510 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.346           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.400           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.932           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.373           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.338           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.378           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.721           ms/op
ClientPb.listUser                       sample  228125   4.207 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.581           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.076           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.915           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.225           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.237           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.867           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.116           ms/op
