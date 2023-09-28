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
# Warmup Iteration   1: 2.121 ops/ms
# Warmup Iteration   2: 4.966 ops/ms
# Warmup Iteration   3: 8.288 ops/ms
Iteration   1: 8.416 ops/ms
Iteration   2: 8.932 ops/ms
Iteration   3: 8.756 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.701 ±(99.9%) 4.790 ops/ms [Average]
  (min, avg, max) = (8.416, 8.701, 8.932), stdev = 0.263
  CI (99.9%): [3.912, 13.491] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.536 ops/ms
# Warmup Iteration   2: 8.196 ops/ms
# Warmup Iteration   3: 8.992 ops/ms
Iteration   1: 9.202 ops/ms
Iteration   2: 9.244 ops/ms
Iteration   3: 9.076 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.174 ±(99.9%) 1.597 ops/ms [Average]
  (min, avg, max) = (9.076, 9.174, 9.244), stdev = 0.088
  CI (99.9%): [7.577, 10.771] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.375 ops/ms
# Warmup Iteration   2: 8.011 ops/ms
# Warmup Iteration   3: 8.755 ops/ms
Iteration   1: 8.831 ops/ms
Iteration   2: 8.522 ops/ms
Iteration   3: 9.052 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.802 ±(99.9%) 4.858 ops/ms [Average]
  (min, avg, max) = (8.522, 8.802, 9.052), stdev = 0.266
  CI (99.9%): [3.944, 13.659] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.452 ops/ms
# Warmup Iteration   2: 6.802 ops/ms
# Warmup Iteration   3: 7.406 ops/ms
Iteration   1: 7.228 ops/ms
Iteration   2: 7.367 ops/ms
Iteration   3: 7.384 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.326 ±(99.9%) 1.562 ops/ms [Average]
  (min, avg, max) = (7.228, 7.326, 7.384), stdev = 0.086
  CI (99.9%): [5.765, 8.888] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 11.088 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 3.894 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.816 ±(99.9%) 0.004 ms/op
Iteration   1: 3.627 ±(99.9%) 0.006 ms/op
Iteration   2: 3.520 ±(99.9%) 0.005 ms/op
Iteration   3: 3.685 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.611 ±(99.9%) 1.525 ms/op [Average]
  (min, avg, max) = (3.520, 3.611, 3.685), stdev = 0.084
  CI (99.9%): [2.086, 5.136] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 10.291 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.784 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.436 ±(99.9%) 0.004 ms/op
Iteration   1: 3.467 ±(99.9%) 0.006 ms/op
Iteration   2: 3.515 ±(99.9%) 0.006 ms/op
Iteration   3: 3.571 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.517 ±(99.9%) 0.951 ms/op [Average]
  (min, avg, max) = (3.467, 3.517, 3.571), stdev = 0.052
  CI (99.9%): [2.567, 4.468] (assumes normal distribution)


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
# Warmup Iteration   1: 9.772 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.886 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.679 ±(99.9%) 0.004 ms/op
Iteration   1: 3.574 ±(99.9%) 0.003 ms/op
Iteration   2: 3.570 ±(99.9%) 0.005 ms/op
Iteration   3: 3.571 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.572 ±(99.9%) 0.038 ms/op [Average]
  (min, avg, max) = (3.570, 3.572, 3.574), stdev = 0.002
  CI (99.9%): [3.534, 3.609] (assumes normal distribution)


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
# Warmup Iteration   1: 13.027 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.900 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.387 ±(99.9%) 0.007 ms/op
Iteration   1: 4.454 ±(99.9%) 0.007 ms/op
Iteration   2: 4.217 ±(99.9%) 0.011 ms/op
Iteration   3: 4.256 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.309 ±(99.9%) 2.313 ms/op [Average]
  (min, avg, max) = (4.217, 4.309, 4.454), stdev = 0.127
  CI (99.9%): [1.996, 6.622] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 11.825 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.211 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.969 ±(99.9%) 0.015 ms/op
Iteration   1: 3.665 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.737 ms/op
                 createUser·p0.50:   3.478 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.678 ms/op
                 createUser·p0.99:   7.381 ms/op
                 createUser·p0.999:  21.577 ms/op
                 createUser·p0.9999: 24.740 ms/op
                 createUser·p1.00:   25.854 ms/op

Iteration   2: 3.730 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.380 ms/op
                 createUser·p0.50:   3.588 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.555 ms/op
                 createUser·p0.99:   6.504 ms/op
                 createUser·p0.999:  24.478 ms/op
                 createUser·p0.9999: 43.741 ms/op
                 createUser·p1.00:   44.433 ms/op

Iteration   3: 3.694 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.430 ms/op
                 createUser·p0.50:   3.531 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.702 ms/op
                 createUser·p0.99:   7.619 ms/op
                 createUser·p0.999:  21.168 ms/op
                 createUser·p0.9999: 30.289 ms/op
                 createUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 259449
  mean =      3.696 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 249895 
    [ 5.000, 10.000) = 8671 
    [10.000, 15.000) = 459 
    [15.000, 20.000) = 96 
    [20.000, 25.000) = 193 
    [25.000, 30.000) = 93 
    [30.000, 35.000) = 10 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.380 ms/op
     p(50.0000) =      3.527 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     21.878 ms/op
     p(99.9900) =     41.629 ms/op
     p(99.9990) =     44.173 ms/op
     p(99.9999) =     44.433 ms/op
    p(100.0000) =     44.433 ms/op


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
# Warmup Iteration   1: 11.111 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 3.936 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.522 ±(99.9%) 0.010 ms/op
Iteration   1: 3.486 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.198 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.883 ms/op
                 existUser·p0.95:   4.563 ms/op
                 existUser·p0.99:   7.496 ms/op
                 existUser·p0.999:  17.400 ms/op
                 existUser·p0.9999: 19.917 ms/op
                 existUser·p1.00:   20.972 ms/op

Iteration   2: 3.407 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.912 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   4.190 ms/op
                 existUser·p0.99:   6.898 ms/op
                 existUser·p0.999:  14.131 ms/op
                 existUser·p0.9999: 21.483 ms/op
                 existUser·p1.00:   22.774 ms/op

Iteration   3: 3.501 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.296 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.944 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   7.012 ms/op
                 existUser·p0.999:  21.903 ms/op
                 existUser·p0.9999: 26.140 ms/op
                 existUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 276837
  mean =      3.464 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4340 
    [ 2.500,  5.000) = 262545 
    [ 5.000,  7.500) = 8065 
    [ 7.500, 10.000) = 1058 
    [10.000, 12.500) = 372 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      7.168 ms/op
     p(99.9000) =     16.520 ms/op
     p(99.9900) =     25.526 ms/op
     p(99.9990) =     26.485 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


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
# Warmup Iteration   1: 9.871 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.020 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.686 ±(99.9%) 0.012 ms/op
Iteration   1: 3.716 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.292 ms/op
                 getUser·p0.50:   3.494 ms/op
                 getUser·p0.90:   4.051 ms/op
                 getUser·p0.95:   5.079 ms/op
                 getUser·p0.99:   7.922 ms/op
                 getUser·p0.999:  19.235 ms/op
                 getUser·p0.9999: 27.291 ms/op
                 getUser·p1.00:   29.360 ms/op

Iteration   2: 3.613 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.229 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   4.047 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   7.397 ms/op
                 getUser·p0.999:  19.710 ms/op
                 getUser·p0.9999: 24.286 ms/op
                 getUser·p1.00:   25.068 ms/op

Iteration   3: 3.641 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.217 ms/op
                 getUser·p0.50:   3.461 ms/op
                 getUser·p0.90:   4.067 ms/op
                 getUser·p0.95:   4.545 ms/op
                 getUser·p0.99:   7.004 ms/op
                 getUser·p0.999:  22.807 ms/op
                 getUser·p0.9999: 28.209 ms/op
                 getUser·p1.00:   29.032 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 262586
  mean =      3.656 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 915 
    [ 2.500,  5.000) = 250712 
    [ 5.000,  7.500) = 8148 
    [ 7.500, 10.000) = 2041 
    [10.000, 12.500) = 251 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 53 

  Percentiles, ms/op:
      p(0.0000) =      1.217 ms/op
     p(50.0000) =      3.465 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      7.561 ms/op
     p(99.9000) =     19.510 ms/op
     p(99.9900) =     27.082 ms/op
     p(99.9990) =     29.032 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


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
# Warmup Iteration   1: 13.622 ±(99.9%) 0.223 ms/op
# Warmup Iteration   2: 4.704 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.357 ±(99.9%) 0.015 ms/op
Iteration   1: 4.402 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.231 ms/op
                 listUser·p0.50:   4.219 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   8.782 ms/op
                 listUser·p0.999:  21.955 ms/op
                 listUser·p0.9999: 23.331 ms/op
                 listUser·p1.00:   24.478 ms/op

Iteration   2: 4.320 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.025 ms/op
                 listUser·p0.50:   4.129 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  16.870 ms/op
                 listUser·p0.9999: 26.037 ms/op
                 listUser·p1.00:   26.870 ms/op

Iteration   3: 4.193 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.102 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.210 ms/op
                 listUser·p0.99:   7.889 ms/op
                 listUser·p0.999:  17.106 ms/op
                 listUser·p0.9999: 18.874 ms/op
                 listUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 222982
  mean =      4.303 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 206446 
    [ 5.000,  7.500) = 12292 
    [ 7.500, 10.000) = 3044 
    [10.000, 12.500) = 481 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 242 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.102 ms/op
     p(50.0000) =      4.092 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.300 ms/op
     p(99.0000) =      8.536 ms/op
     p(99.9000) =     18.121 ms/op
     p(99.9900) =     23.429 ms/op
     p(99.9990) =     26.429 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.701 ± 4.790  ops/ms
ClientPb.existUser                       thrpt       3   9.174 ± 1.597  ops/ms
ClientPb.getUser                         thrpt       3   8.802 ± 4.858  ops/ms
ClientPb.listUser                        thrpt       3   7.326 ± 1.562  ops/ms
ClientPb.createUser                       avgt       3   3.611 ± 1.525   ms/op
ClientPb.existUser                        avgt       3   3.517 ± 0.951   ms/op
ClientPb.getUser                          avgt       3   3.572 ± 0.038   ms/op
ClientPb.listUser                         avgt       3   4.309 ± 2.313   ms/op
ClientPb.createUser                     sample  259449   3.696 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.380           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.527           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.243           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.620           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.217           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.878           ms/op
ClientPb.createUser:createUser·p0.9999  sample          41.629           ms/op
ClientPb.createUser:createUser·p1.00    sample          44.433           ms/op
ClientPb.existUser                      sample  276837   3.464 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.912           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.281           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.867           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.424           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.168           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.520           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.526           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.361           ms/op
ClientPb.getUser                        sample  262586   3.656 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.217           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.465           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.055           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.645           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.561           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.510           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.082           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.360           ms/op
ClientPb.listUser                       sample  222982   4.303 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.102           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.092           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.850           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.300           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.536           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.121           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.429           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.870           ms/op
