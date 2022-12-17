# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.323 ops/ms
# Warmup Iteration   2: 6.095 ops/ms
# Warmup Iteration   3: 8.661 ops/ms
Iteration   1: 10.114 ops/ms
Iteration   2: 9.818 ops/ms
Iteration   3: 9.254 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.729 ±(99.9%) 7.968 ops/ms [Average]
  (min, avg, max) = (9.254, 9.729, 10.114), stdev = 0.437
  CI (99.9%): [1.760, 17.697] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.656 ops/ms
# Warmup Iteration   2: 8.559 ops/ms
# Warmup Iteration   3: 9.163 ops/ms
Iteration   1: 9.563 ops/ms
Iteration   2: 9.677 ops/ms
Iteration   3: 9.720 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.653 ±(99.9%) 1.475 ops/ms [Average]
  (min, avg, max) = (9.563, 9.653, 9.720), stdev = 0.081
  CI (99.9%): [8.178, 11.128] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.698 ops/ms
# Warmup Iteration   2: 8.167 ops/ms
# Warmup Iteration   3: 9.626 ops/ms
Iteration   1: 9.841 ops/ms
Iteration   2: 9.455 ops/ms
Iteration   3: 9.203 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.500 ±(99.9%) 5.858 ops/ms [Average]
  (min, avg, max) = (9.203, 9.500, 9.841), stdev = 0.321
  CI (99.9%): [3.641, 15.358] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 3.076 ops/ms
# Warmup Iteration   2: 7.587 ops/ms
# Warmup Iteration   3: 8.300 ops/ms
Iteration   1: 8.160 ops/ms
Iteration   2: 8.089 ops/ms
Iteration   3: 8.149 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.133 ±(99.9%) 0.696 ops/ms [Average]
  (min, avg, max) = (8.089, 8.133, 8.160), stdev = 0.038
  CI (99.9%): [7.437, 8.828] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.339 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.420 ±(99.9%) 0.005 ms/op
Iteration   1: 3.187 ±(99.9%) 0.009 ms/op
Iteration   2: 3.224 ±(99.9%) 0.007 ms/op
Iteration   3: 3.250 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.220 ±(99.9%) 0.578 ms/op [Average]
  (min, avg, max) = (3.187, 3.220, 3.250), stdev = 0.032
  CI (99.9%): [2.642, 3.799] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.296 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.536 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.359 ±(99.9%) 0.007 ms/op
Iteration   1: 3.350 ±(99.9%) 0.005 ms/op
Iteration   2: 3.259 ±(99.9%) 0.004 ms/op
Iteration   3: 3.254 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.288 ±(99.9%) 0.991 ms/op [Average]
  (min, avg, max) = (3.254, 3.288, 3.350), stdev = 0.054
  CI (99.9%): [2.297, 4.279] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.976 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.554 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.569 ±(99.9%) 0.006 ms/op
Iteration   1: 3.478 ±(99.9%) 0.006 ms/op
Iteration   2: 3.582 ±(99.9%) 0.005 ms/op
Iteration   3: 3.385 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.482 ±(99.9%) 1.798 ms/op [Average]
  (min, avg, max) = (3.385, 3.482, 3.582), stdev = 0.099
  CI (99.9%): [1.683, 5.280] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.538 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.305 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.989 ±(99.9%) 0.008 ms/op
Iteration   1: 4.081 ±(99.9%) 0.007 ms/op
Iteration   2: 3.961 ±(99.9%) 0.011 ms/op
Iteration   3: 3.812 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.952 ±(99.9%) 2.461 ms/op [Average]
  (min, avg, max) = (3.812, 3.952, 4.081), stdev = 0.135
  CI (99.9%): [1.490, 6.413] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.295 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.025 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.568 ±(99.9%) 0.012 ms/op
Iteration   1: 3.451 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.491 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   4.157 ms/op
                 createUser·p0.95:   5.663 ms/op
                 createUser·p0.99:   6.881 ms/op
                 createUser·p0.999:  19.934 ms/op
                 createUser·p0.9999: 25.509 ms/op
                 createUser·p1.00:   27.230 ms/op

Iteration   2: 3.210 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.462 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  12.339 ms/op
                 createUser·p0.9999: 30.020 ms/op
                 createUser·p1.00:   30.966 ms/op

Iteration   3: 3.356 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.927 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  21.846 ms/op
                 createUser·p0.9999: 27.719 ms/op
                 createUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 287660
  mean =      3.336 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8833 
    [ 2.500,  5.000) = 270095 
    [ 5.000,  7.500) = 7357 
    [ 7.500, 10.000) = 770 
    [10.000, 12.500) = 261 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.927 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     19.672 ms/op
     p(99.9900) =     28.982 ms/op
     p(99.9990) =     30.937 ms/op
     p(99.9999) =     30.966 ms/op
    p(100.0000) =     30.966 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.657 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.661 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.307 ±(99.9%) 0.009 ms/op
Iteration   1: 3.287 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.229 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   5.923 ms/op
                 existUser·p0.999:  9.389 ms/op
                 existUser·p0.9999: 23.062 ms/op
                 existUser·p1.00:   23.888 ms/op

Iteration   2: 3.224 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.745 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  9.658 ms/op
                 existUser·p0.9999: 23.530 ms/op
                 existUser·p1.00:   23.953 ms/op

Iteration   3: 3.421 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.214 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.826 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   6.504 ms/op
                 existUser·p0.999:  22.727 ms/op
                 existUser·p0.9999: 25.483 ms/op
                 existUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289937
  mean =      3.308 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12828 
    [ 2.500,  5.000) = 271375 
    [ 5.000,  7.500) = 4844 
    [ 7.500, 10.000) = 525 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 141 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.214 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     10.699 ms/op
     p(99.9900) =     24.576 ms/op
     p(99.9990) =     25.841 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.693 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.759 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.407 ±(99.9%) 0.010 ms/op
Iteration   1: 3.408 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.724 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   6.726 ms/op
                 getUser·p0.999:  21.660 ms/op
                 getUser·p0.9999: 24.268 ms/op
                 getUser·p1.00:   24.707 ms/op

Iteration   2: 3.329 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.597 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   5.382 ms/op
                 getUser·p0.999:  27.427 ms/op
                 getUser·p0.9999: 29.773 ms/op
                 getUser·p1.00:   34.669 ms/op

Iteration   3: 3.505 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.657 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   4.014 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   6.423 ms/op
                 getUser·p0.999:  19.557 ms/op
                 getUser·p0.9999: 29.279 ms/op
                 getUser·p1.00:   31.228 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 281240
  mean =      3.413 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3997 
    [ 2.500,  5.000) = 270405 
    [ 5.000,  7.500) = 5548 
    [ 7.500, 10.000) = 781 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 114 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.597 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      6.144 ms/op
     p(99.9000) =     20.860 ms/op
     p(99.9900) =     29.327 ms/op
     p(99.9990) =     30.509 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.215 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.513 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.148 ±(99.9%) 0.013 ms/op
Iteration   1: 4.026 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.792 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  17.991 ms/op
                 listUser·p0.9999: 24.021 ms/op
                 listUser·p1.00:   24.871 ms/op

Iteration   2: 4.039 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.980 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.471 ms/op
                 listUser·p0.999:  18.055 ms/op
                 listUser·p0.9999: 31.883 ms/op
                 listUser·p1.00:   32.244 ms/op

Iteration   3: 4.068 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.741 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   8.374 ms/op
                 listUser·p0.999:  15.686 ms/op
                 listUser·p0.9999: 18.874 ms/op
                 listUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237365
  mean =      4.044 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59 
    [ 2.500,  5.000) = 227961 
    [ 5.000,  7.500) = 6870 
    [ 7.500, 10.000) = 1492 
    [10.000, 12.500) = 363 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 245 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.980 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      7.578 ms/op
     p(99.9000) =     17.334 ms/op
     p(99.9900) =     24.060 ms/op
     p(99.9990) =     32.211 ms/op
     p(99.9999) =     32.244 ms/op
    p(100.0000) =     32.244 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.729 ± 7.968  ops/ms
ClientPb.existUser                       thrpt       3   9.653 ± 1.475  ops/ms
ClientPb.getUser                         thrpt       3   9.500 ± 5.858  ops/ms
ClientPb.listUser                        thrpt       3   8.133 ± 0.696  ops/ms
ClientPb.createUser                       avgt       3   3.220 ± 0.578   ms/op
ClientPb.existUser                        avgt       3   3.288 ± 0.991   ms/op
ClientPb.getUser                          avgt       3   3.482 ± 1.798   ms/op
ClientPb.listUser                         avgt       3   3.952 ± 2.461   ms/op
ClientPb.createUser                     sample  287660   3.336 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.927           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.463           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.672           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.982           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.966           ms/op
ClientPb.existUser                      sample  289937   3.308 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.214           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.232           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.908           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.906           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.699           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.576           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.509           ms/op
ClientPb.getUser                        sample  281240   3.413 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.597           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.269           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.809           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.125           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.144           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.860           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.327           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.669           ms/op
ClientPb.listUser                       sample  237365   4.044 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.980           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.784           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.578           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.334           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.060           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.244           ms/op
