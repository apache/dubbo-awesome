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
# Warmup Iteration   1: 2.222 ops/ms
# Warmup Iteration   2: 5.806 ops/ms
# Warmup Iteration   3: 8.406 ops/ms
Iteration   1: 8.921 ops/ms
Iteration   2: 9.029 ops/ms
Iteration   3: 9.281 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.077 ±(99.9%) 3.367 ops/ms [Average]
  (min, avg, max) = (8.921, 9.077, 9.281), stdev = 0.185
  CI (99.9%): [5.710, 12.444] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.496 ops/ms
# Warmup Iteration   2: 8.827 ops/ms
# Warmup Iteration   3: 8.980 ops/ms
Iteration   1: 9.693 ops/ms
Iteration   2: 9.577 ops/ms
Iteration   3: 9.482 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.584 ±(99.9%) 1.929 ops/ms [Average]
  (min, avg, max) = (9.482, 9.584, 9.693), stdev = 0.106
  CI (99.9%): [7.655, 11.513] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.925 ops/ms
# Warmup Iteration   2: 8.534 ops/ms
# Warmup Iteration   3: 8.948 ops/ms
Iteration   1: 9.347 ops/ms
Iteration   2: 9.428 ops/ms
Iteration   3: 9.064 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.279 ±(99.9%) 3.483 ops/ms [Average]
  (min, avg, max) = (9.064, 9.279, 9.428), stdev = 0.191
  CI (99.9%): [5.796, 12.763] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.929 ops/ms
# Warmup Iteration   2: 7.095 ops/ms
# Warmup Iteration   3: 7.666 ops/ms
Iteration   1: 7.658 ops/ms
Iteration   2: 7.735 ops/ms
Iteration   3: 7.935 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.776 ±(99.9%) 2.607 ops/ms [Average]
  (min, avg, max) = (7.658, 7.776, 7.935), stdev = 0.143
  CI (99.9%): [5.169, 10.383] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.891 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.842 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.661 ±(99.9%) 0.004 ms/op
Iteration   1: 3.474 ±(99.9%) 0.005 ms/op
Iteration   2: 3.454 ±(99.9%) 0.006 ms/op
Iteration   3: 3.348 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.425 ±(99.9%) 1.236 ms/op [Average]
  (min, avg, max) = (3.348, 3.425, 3.474), stdev = 0.068
  CI (99.9%): [2.190, 4.661] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.577 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.642 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.472 ±(99.9%) 0.007 ms/op
Iteration   1: 3.450 ±(99.9%) 0.006 ms/op
Iteration   2: 3.338 ±(99.9%) 0.004 ms/op
Iteration   3: 3.442 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.410 ±(99.9%) 1.132 ms/op [Average]
  (min, avg, max) = (3.338, 3.410, 3.450), stdev = 0.062
  CI (99.9%): [2.278, 4.542] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.755 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.712 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.599 ±(99.9%) 0.004 ms/op
Iteration   1: 3.464 ±(99.9%) 0.004 ms/op
Iteration   2: 3.530 ±(99.9%) 0.004 ms/op
Iteration   3: 3.456 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.483 ±(99.9%) 0.738 ms/op [Average]
  (min, avg, max) = (3.456, 3.483, 3.530), stdev = 0.040
  CI (99.9%): [2.746, 4.221] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 10.186 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.421 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.116 ±(99.9%) 0.006 ms/op
Iteration   1: 4.082 ±(99.9%) 0.006 ms/op
Iteration   2: 4.085 ±(99.9%) 0.006 ms/op
Iteration   3: 3.992 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.053 ±(99.9%) 0.970 ms/op [Average]
  (min, avg, max) = (3.992, 4.053, 4.085), stdev = 0.053
  CI (99.9%): [3.083, 5.023] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.755 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.005 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.534 ±(99.9%) 0.010 ms/op
Iteration   1: 3.400 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.008 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   6.316 ms/op
                 createUser·p0.999:  20.771 ms/op
                 createUser·p0.9999: 29.563 ms/op
                 createUser·p1.00:   30.179 ms/op

Iteration   2: 3.438 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.741 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   7.111 ms/op
                 createUser·p0.999:  21.665 ms/op
                 createUser·p0.9999: 24.983 ms/op
                 createUser·p1.00:   26.378 ms/op

Iteration   3: 3.475 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.505 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   6.840 ms/op
                 createUser·p0.999:  17.891 ms/op
                 createUser·p0.9999: 27.944 ms/op
                 createUser·p1.00:   30.212 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278977
  mean =      3.437 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7191 
    [ 2.500,  5.000) = 264191 
    [ 5.000,  7.500) = 5645 
    [ 7.500, 10.000) = 1340 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.008 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     18.809 ms/op
     p(99.9900) =     28.380 ms/op
     p(99.9990) =     29.972 ms/op
     p(99.9999) =     30.212 ms/op
    p(100.0000) =     30.212 ms/op


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
# Warmup Iteration   1: 8.515 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.739 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.320 ±(99.9%) 0.009 ms/op
Iteration   1: 3.322 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.694 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   5.882 ms/op
                 existUser·p0.999:  9.699 ms/op
                 existUser·p0.9999: 21.016 ms/op
                 existUser·p1.00:   21.955 ms/op

Iteration   2: 3.460 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.194 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   3.846 ms/op
                 existUser·p0.95:   4.440 ms/op
                 existUser·p0.99:   6.619 ms/op
                 existUser·p0.999:  20.283 ms/op
                 existUser·p0.9999: 25.517 ms/op
                 existUser·p1.00:   26.673 ms/op

Iteration   3: 3.411 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.333 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.875 ms/op
                 existUser·p0.95:   4.424 ms/op
                 existUser·p0.99:   6.595 ms/op
                 existUser·p0.999:  18.350 ms/op
                 existUser·p0.9999: 30.644 ms/op
                 existUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282476
  mean =      3.397 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7887 
    [ 2.500,  5.000) = 266645 
    [ 5.000,  7.500) = 6304 
    [ 7.500, 10.000) = 1287 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.194 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.406 ms/op
     p(99.9000) =     11.911 ms/op
     p(99.9900) =     28.795 ms/op
     p(99.9990) =     33.971 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


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
# Warmup Iteration   1: 9.310 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.705 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.733 ±(99.9%) 0.013 ms/op
Iteration   1: 3.710 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.423 ms/op
                 getUser·p0.50:   3.449 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   5.571 ms/op
                 getUser·p0.99:   7.651 ms/op
                 getUser·p0.999:  20.447 ms/op
                 getUser·p0.9999: 22.491 ms/op
                 getUser·p1.00:   23.429 ms/op

Iteration   2: 3.494 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.647 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   3.994 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   5.752 ms/op
                 getUser·p0.999:  21.444 ms/op
                 getUser·p0.9999: 29.579 ms/op
                 getUser·p1.00:   30.114 ms/op

Iteration   3: 3.523 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.755 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.330 ms/op
                 getUser·p0.99:   6.889 ms/op
                 getUser·p0.999:  17.826 ms/op
                 getUser·p0.9999: 27.357 ms/op
                 getUser·p1.00:   27.984 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 268514
  mean =      3.573 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8284 
    [ 2.500,  5.000) = 249445 
    [ 5.000,  7.500) = 8438 
    [ 7.500, 10.000) = 1782 
    [10.000, 12.500) = 268 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.423 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     18.776 ms/op
     p(99.9900) =     28.008 ms/op
     p(99.9990) =     30.081 ms/op
     p(99.9999) =     30.114 ms/op
    p(100.0000) =     30.114 ms/op


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
# Warmup Iteration   1: 9.738 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 4.437 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.131 ±(99.9%) 0.014 ms/op
Iteration   1: 4.067 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.028 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   5.087 ms/op
                 listUser·p0.99:   8.192 ms/op
                 listUser·p0.999:  21.311 ms/op
                 listUser·p0.9999: 23.910 ms/op
                 listUser·p1.00:   26.903 ms/op

Iteration   2: 3.926 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   7.660 ms/op
                 listUser·p0.999:  15.090 ms/op
                 listUser·p0.9999: 16.335 ms/op
                 listUser·p1.00:   16.384 ms/op

Iteration   3: 3.897 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.978 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   7.471 ms/op
                 listUser·p0.999:  14.631 ms/op
                 listUser·p0.9999: 18.252 ms/op
                 listUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242156
  mean =      3.962 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 232573 
    [ 5.000,  7.500) = 6833 
    [ 7.500, 10.000) = 1832 
    [10.000, 12.500) = 397 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 156 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.028 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      7.758 ms/op
     p(99.9000) =     15.499 ms/op
     p(99.9900) =     23.094 ms/op
     p(99.9990) =     26.856 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.077 ± 3.367  ops/ms
ClientPb.existUser                       thrpt       3   9.584 ± 1.929  ops/ms
ClientPb.getUser                         thrpt       3   9.279 ± 3.483  ops/ms
ClientPb.listUser                        thrpt       3   7.776 ± 2.607  ops/ms
ClientPb.createUser                       avgt       3   3.425 ± 1.236   ms/op
ClientPb.existUser                        avgt       3   3.410 ± 1.132   ms/op
ClientPb.getUser                          avgt       3   3.483 ± 0.738   ms/op
ClientPb.listUser                         avgt       3   4.053 ± 0.970   ms/op
ClientPb.createUser                     sample  278977   3.437 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.008           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.310           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.850           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.873           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.809           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.380           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.212           ms/op
ClientPb.existUser                      sample  282476   3.397 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.194           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.785           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.276           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.406           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.911           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.795           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.144           ms/op
ClientPb.getUser                        sample  268514   3.573 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.423           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.428           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.096           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.612           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.348           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.776           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.008           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.114           ms/op
ClientPb.listUser                       sample  242156   3.962 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.028           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.764           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.686           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.758           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.499           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.094           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.903           ms/op
