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
# Warmup Iteration   1: 2.161 ops/ms
# Warmup Iteration   2: 5.950 ops/ms
# Warmup Iteration   3: 8.661 ops/ms
Iteration   1: 9.375 ops/ms
Iteration   2: 9.515 ops/ms
Iteration   3: 9.393 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.428 ±(99.9%) 1.391 ops/ms [Average]
  (min, avg, max) = (9.375, 9.428, 9.515), stdev = 0.076
  CI (99.9%): [8.037, 10.819] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.097 ops/ms
# Warmup Iteration   2: 8.961 ops/ms
# Warmup Iteration   3: 9.506 ops/ms
Iteration   1: 9.646 ops/ms
Iteration   2: 9.673 ops/ms
Iteration   3: 9.532 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.617 ±(99.9%) 1.362 ops/ms [Average]
  (min, avg, max) = (9.532, 9.617, 9.673), stdev = 0.075
  CI (99.9%): [8.255, 10.979] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.012 ops/ms
# Warmup Iteration   2: 8.678 ops/ms
# Warmup Iteration   3: 9.129 ops/ms
Iteration   1: 9.363 ops/ms
Iteration   2: 9.252 ops/ms
Iteration   3: 9.355 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.323 ±(99.9%) 1.130 ops/ms [Average]
  (min, avg, max) = (9.252, 9.323, 9.363), stdev = 0.062
  CI (99.9%): [8.193, 10.453] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.566 ops/ms
# Warmup Iteration   2: 7.330 ops/ms
# Warmup Iteration   3: 7.693 ops/ms
Iteration   1: 7.823 ops/ms
Iteration   2: 7.714 ops/ms
Iteration   3: 7.754 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.764 ±(99.9%) 1.003 ops/ms [Average]
  (min, avg, max) = (7.714, 7.764, 7.823), stdev = 0.055
  CI (99.9%): [6.761, 8.766] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.917 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.724 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.607 ±(99.9%) 0.004 ms/op
Iteration   1: 3.514 ±(99.9%) 0.005 ms/op
Iteration   2: 3.375 ±(99.9%) 0.006 ms/op
Iteration   3: 3.421 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.436 ±(99.9%) 1.289 ms/op [Average]
  (min, avg, max) = (3.375, 3.436, 3.514), stdev = 0.071
  CI (99.9%): [2.148, 4.725] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.112 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.579 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.354 ±(99.9%) 0.005 ms/op
Iteration   1: 3.254 ±(99.9%) 0.005 ms/op
Iteration   2: 3.240 ±(99.9%) 0.005 ms/op
Iteration   3: 3.278 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.257 ±(99.9%) 0.351 ms/op [Average]
  (min, avg, max) = (3.240, 3.257, 3.278), stdev = 0.019
  CI (99.9%): [2.906, 3.608] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.888 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.683 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.591 ±(99.9%) 0.003 ms/op
Iteration   1: 3.454 ±(99.9%) 0.004 ms/op
Iteration   2: 3.444 ±(99.9%) 0.004 ms/op
Iteration   3: 3.369 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.422 ±(99.9%) 0.841 ms/op [Average]
  (min, avg, max) = (3.369, 3.422, 3.454), stdev = 0.046
  CI (99.9%): [2.582, 4.263] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.139 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.454 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.157 ±(99.9%) 0.008 ms/op
Iteration   1: 4.041 ±(99.9%) 0.005 ms/op
Iteration   2: 4.116 ±(99.9%) 0.006 ms/op
Iteration   3: 4.104 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.087 ±(99.9%) 0.733 ms/op [Average]
  (min, avg, max) = (4.041, 4.087, 4.116), stdev = 0.040
  CI (99.9%): [3.354, 4.820] (assumes normal distribution)


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
# Warmup Iteration   1: 9.753 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.906 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.548 ±(99.9%) 0.009 ms/op
Iteration   1: 3.417 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.561 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  20.683 ms/op
                 createUser·p0.9999: 23.036 ms/op
                 createUser·p1.00:   23.953 ms/op

Iteration   2: 3.427 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.039 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.153 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  21.886 ms/op
                 createUser·p0.9999: 25.504 ms/op
                 createUser·p1.00:   27.197 ms/op

Iteration   3: 3.386 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.034 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   5.451 ms/op
                 createUser·p0.999:  20.385 ms/op
                 createUser·p0.9999: 29.335 ms/op
                 createUser·p1.00:   29.917 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281420
  mean =      3.410 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4813 
    [ 2.500,  5.000) = 271818 
    [ 5.000,  7.500) = 3638 
    [ 7.500, 10.000) = 544 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 135 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      1.034 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     20.532 ms/op
     p(99.9900) =     25.910 ms/op
     p(99.9990) =     29.661 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


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
# Warmup Iteration   1: 9.940 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.518 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.289 ±(99.9%) 0.007 ms/op
Iteration   1: 3.260 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.247 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.563 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   5.448 ms/op
                 existUser·p0.999:  19.975 ms/op
                 existUser·p0.9999: 22.446 ms/op
                 existUser·p1.00:   22.774 ms/op

Iteration   2: 3.317 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.159 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   6.152 ms/op
                 existUser·p0.999:  16.544 ms/op
                 existUser·p0.9999: 24.206 ms/op
                 existUser·p1.00:   25.068 ms/op

Iteration   3: 3.369 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.405 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   4.092 ms/op
                 existUser·p0.99:   6.939 ms/op
                 existUser·p0.999:  15.139 ms/op
                 existUser·p0.9999: 24.265 ms/op
                 existUser·p1.00:   25.526 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289563
  mean =      3.315 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5856 
    [ 2.500,  5.000) = 277488 
    [ 5.000,  7.500) = 5114 
    [ 7.500, 10.000) = 650 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 145 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.159 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      6.250 ms/op
     p(99.9000) =     15.195 ms/op
     p(99.9900) =     23.955 ms/op
     p(99.9990) =     25.428 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


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
# Warmup Iteration   1: 8.828 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.630 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.490 ±(99.9%) 0.009 ms/op
Iteration   1: 3.577 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.327 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   3.969 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   7.315 ms/op
                 getUser·p0.999:  17.072 ms/op
                 getUser·p0.9999: 19.464 ms/op
                 getUser·p1.00:   20.906 ms/op

Iteration   2: 3.479 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.544 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   5.562 ms/op
                 getUser·p0.999:  18.330 ms/op
                 getUser·p0.9999: 21.418 ms/op
                 getUser·p1.00:   22.118 ms/op

Iteration   3: 3.444 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.939 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  14.005 ms/op
                 getUser·p0.9999: 23.729 ms/op
                 getUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274117
  mean =      3.499 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4510 
    [ 2.500,  5.000) = 262745 
    [ 5.000,  7.500) = 5527 
    [ 7.500, 10.000) = 627 
    [10.000, 12.500) = 283 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 141 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.327 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      6.619 ms/op
     p(99.9000) =     15.643 ms/op
     p(99.9900) =     22.832 ms/op
     p(99.9990) =     24.660 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


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
# Warmup Iteration   1: 10.301 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.361 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.200 ±(99.9%) 0.011 ms/op
Iteration   1: 4.262 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.796 ms/op
                 listUser·p0.50:   4.096 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.186 ms/op
                 listUser·p0.99:   8.118 ms/op
                 listUser·p0.999:  21.133 ms/op
                 listUser·p0.9999: 41.779 ms/op
                 listUser·p1.00:   42.074 ms/op

Iteration   2: 4.015 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.679 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  15.716 ms/op
                 listUser·p0.9999: 16.876 ms/op
                 listUser·p1.00:   17.990 ms/op

Iteration   3: 4.145 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.710 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.038 ms/op
                 listUser·p0.99:   7.407 ms/op
                 listUser·p0.999:  15.925 ms/op
                 listUser·p0.9999: 19.759 ms/op
                 listUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 231870
  mean =      4.138 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 220710 
    [ 5.000, 10.000) = 10341 
    [10.000, 15.000) = 375 
    [15.000, 20.000) = 356 
    [20.000, 25.000) = 56 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 5 
    [35.000, 40.000) = 16 
    [40.000, 45.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.679 ms/op
     p(50.0000) =      3.949 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      7.539 ms/op
     p(99.9000) =     16.187 ms/op
     p(99.9900) =     35.193 ms/op
     p(99.9990) =     42.009 ms/op
     p(99.9999) =     42.074 ms/op
    p(100.0000) =     42.074 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.428 ± 1.391  ops/ms
ClientPb.existUser                       thrpt       3   9.617 ± 1.362  ops/ms
ClientPb.getUser                         thrpt       3   9.323 ± 1.130  ops/ms
ClientPb.listUser                        thrpt       3   7.764 ± 1.003  ops/ms
ClientPb.createUser                       avgt       3   3.436 ± 1.289   ms/op
ClientPb.existUser                        avgt       3   3.257 ± 0.351   ms/op
ClientPb.getUser                          avgt       3   3.422 ± 0.841   ms/op
ClientPb.listUser                         avgt       3   4.087 ± 0.733   ms/op
ClientPb.createUser                     sample  281420   3.410 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.034           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.281           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.838           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.104           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.718           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.532           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.910           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.917           ms/op
ClientPb.existUser                      sample  289563   3.315 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.159           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.183           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.641           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.936           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.250           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.195           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.955           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.526           ms/op
ClientPb.getUser                        sample  274117   3.499 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.327           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.375           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.619           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.643           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.832           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.788           ms/op
ClientPb.listUser                       sample  231870   4.138 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.679           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.661           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.981           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.539           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.187           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.193           ms/op
ClientPb.listUser:listUser·p1.00        sample          42.074           ms/op
