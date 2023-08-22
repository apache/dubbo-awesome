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
# Warmup Iteration   1: 1.973 ops/ms
# Warmup Iteration   2: 5.270 ops/ms
# Warmup Iteration   3: 8.409 ops/ms
Iteration   1: 9.010 ops/ms
Iteration   2: 9.421 ops/ms
Iteration   3: 9.459 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.296 ±(99.9%) 4.542 ops/ms [Average]
  (min, avg, max) = (9.010, 9.296, 9.459), stdev = 0.249
  CI (99.9%): [4.754, 13.839] (assumes normal distribution)


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
# Warmup Iteration   1: 2.791 ops/ms
# Warmup Iteration   2: 8.469 ops/ms
# Warmup Iteration   3: 9.461 ops/ms
Iteration   1: 9.502 ops/ms
Iteration   2: 9.654 ops/ms
Iteration   3: 9.507 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.554 ±(99.9%) 1.576 ops/ms [Average]
  (min, avg, max) = (9.502, 9.554, 9.654), stdev = 0.086
  CI (99.9%): [7.978, 11.130] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.719 ops/ms
# Warmup Iteration   2: 8.434 ops/ms
# Warmup Iteration   3: 8.926 ops/ms
Iteration   1: 9.121 ops/ms
Iteration   2: 9.158 ops/ms
Iteration   3: 9.105 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.128 ±(99.9%) 0.500 ops/ms [Average]
  (min, avg, max) = (9.105, 9.128, 9.158), stdev = 0.027
  CI (99.9%): [8.629, 9.628] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.809 ops/ms
# Warmup Iteration   2: 7.133 ops/ms
# Warmup Iteration   3: 7.656 ops/ms
Iteration   1: 7.555 ops/ms
Iteration   2: 7.748 ops/ms
Iteration   3: 7.938 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.747 ±(99.9%) 3.497 ops/ms [Average]
  (min, avg, max) = (7.555, 7.747, 7.938), stdev = 0.192
  CI (99.9%): [4.250, 11.244] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.528 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.844 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.758 ±(99.9%) 0.005 ms/op
Iteration   1: 3.426 ±(99.9%) 0.008 ms/op
Iteration   2: 3.615 ±(99.9%) 0.005 ms/op
Iteration   3: 3.434 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.492 ±(99.9%) 1.952 ms/op [Average]
  (min, avg, max) = (3.426, 3.492, 3.615), stdev = 0.107
  CI (99.9%): [1.540, 5.443] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 9.371 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.721 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.419 ±(99.9%) 0.006 ms/op
Iteration   1: 3.298 ±(99.9%) 0.004 ms/op
Iteration   2: 3.420 ±(99.9%) 0.003 ms/op
Iteration   3: 3.435 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.384 ±(99.9%) 1.369 ms/op [Average]
  (min, avg, max) = (3.298, 3.384, 3.435), stdev = 0.075
  CI (99.9%): [2.015, 4.753] (assumes normal distribution)


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
# Warmup Iteration   1: 9.887 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.042 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.520 ±(99.9%) 0.002 ms/op
Iteration   1: 3.502 ±(99.9%) 0.008 ms/op
Iteration   2: 3.604 ±(99.9%) 0.009 ms/op
Iteration   3: 3.772 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.626 ±(99.9%) 2.486 ms/op [Average]
  (min, avg, max) = (3.502, 3.626, 3.772), stdev = 0.136
  CI (99.9%): [1.139, 6.112] (assumes normal distribution)


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
# Warmup Iteration   1: 11.057 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.414 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.993 ±(99.9%) 0.013 ms/op
Iteration   1: 4.073 ±(99.9%) 0.009 ms/op
Iteration   2: 3.978 ±(99.9%) 0.010 ms/op
Iteration   3: 3.964 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.005 ±(99.9%) 1.088 ms/op [Average]
  (min, avg, max) = (3.964, 4.005, 4.073), stdev = 0.060
  CI (99.9%): [2.917, 5.093] (assumes normal distribution)


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
# Warmup Iteration   1: 10.290 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.270 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.500 ±(99.9%) 0.010 ms/op
Iteration   1: 3.951 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.589 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   6.611 ms/op
                 createUser·p0.95:   7.004 ms/op
                 createUser·p0.99:   8.053 ms/op
                 createUser·p0.999:  20.316 ms/op
                 createUser·p0.9999: 25.622 ms/op
                 createUser·p1.00:   25.985 ms/op

Iteration   2: 3.568 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.681 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.141 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   6.578 ms/op
                 createUser·p0.999:  23.280 ms/op
                 createUser·p0.9999: 28.941 ms/op
                 createUser·p1.00:   30.212 ms/op

Iteration   3: 3.517 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.348 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  23.233 ms/op
                 createUser·p0.9999: 28.654 ms/op
                 createUser·p1.00:   29.229 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 261460
  mean =      3.669 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4684 
    [ 2.500,  5.000) = 238849 
    [ 5.000,  7.500) = 15718 
    [ 7.500, 10.000) = 1500 
    [10.000, 12.500) = 279 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 113 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.348 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      7.340 ms/op
     p(99.9000) =     22.249 ms/op
     p(99.9900) =     28.045 ms/op
     p(99.9990) =     29.680 ms/op
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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.869 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 3.589 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.377 ±(99.9%) 0.010 ms/op
Iteration   1: 3.399 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.419 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.822 ms/op
                 existUser·p0.95:   4.170 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  19.127 ms/op
                 existUser·p0.9999: 22.675 ms/op
                 existUser·p1.00:   23.167 ms/op

Iteration   2: 3.379 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.149 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   4.047 ms/op
                 existUser·p0.99:   5.571 ms/op
                 existUser·p0.999:  21.968 ms/op
                 existUser·p0.9999: 25.005 ms/op
                 existUser·p1.00:   25.821 ms/op

Iteration   3: 3.416 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.686 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.846 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   7.053 ms/op
                 existUser·p0.999:  10.346 ms/op
                 existUser·p0.9999: 25.842 ms/op
                 existUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282288
  mean =      3.398 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8999 
    [ 2.500,  5.000) = 265671 
    [ 5.000,  7.500) = 6213 
    [ 7.500, 10.000) = 1057 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =     10.530 ms/op
     p(99.9900) =     25.060 ms/op
     p(99.9990) =     26.637 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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
# Warmup Iteration   1: 9.774 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 3.870 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.518 ±(99.9%) 0.012 ms/op
Iteration   1: 3.639 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.585 ms/op
                 getUser·p0.50:   3.453 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   5.063 ms/op
                 getUser·p0.99:   7.111 ms/op
                 getUser·p0.999:  20.152 ms/op
                 getUser·p0.9999: 21.699 ms/op
                 getUser·p1.00:   22.184 ms/op

Iteration   2: 3.533 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.716 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   6.758 ms/op
                 getUser·p0.999:  21.108 ms/op
                 getUser·p0.9999: 24.181 ms/op
                 getUser·p1.00:   26.083 ms/op

Iteration   3: 3.650 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.706 ms/op
                 getUser·p0.50:   3.502 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   5.014 ms/op
                 getUser·p0.99:   6.644 ms/op
                 getUser·p0.999:  16.269 ms/op
                 getUser·p0.9999: 26.550 ms/op
                 getUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 266261
  mean =      3.607 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4667 
    [ 2.500,  5.000) = 249756 
    [ 5.000,  7.500) = 10195 
    [ 7.500, 10.000) = 1213 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.585 ms/op
     p(50.0000) =      3.465 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     19.578 ms/op
     p(99.9900) =     25.244 ms/op
     p(99.9990) =     27.438 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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
# Warmup Iteration   1: 12.363 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.548 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.298 ±(99.9%) 0.015 ms/op
Iteration   1: 4.136 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.708 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   7.748 ms/op
                 listUser·p0.999:  21.941 ms/op
                 listUser·p0.9999: 35.734 ms/op
                 listUser·p1.00:   35.914 ms/op

Iteration   2: 4.187 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.310 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.441 ms/op
                 listUser·p0.99:   8.389 ms/op
                 listUser·p0.999:  20.283 ms/op
                 listUser·p0.9999: 28.148 ms/op
                 listUser·p1.00:   28.213 ms/op

Iteration   3: 4.081 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.095 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.186 ms/op
                 listUser·p0.99:   8.143 ms/op
                 listUser·p0.999:  14.877 ms/op
                 listUser·p0.9999: 18.612 ms/op
                 listUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232269
  mean =      4.134 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 218616 
    [ 5.000,  7.500) = 10392 
    [ 7.500, 10.000) = 2338 
    [10.000, 12.500) = 380 
    [12.500, 15.000) = 159 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.708 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.202 ms/op
     p(99.0000) =      8.151 ms/op
     p(99.9000) =     18.448 ms/op
     p(99.9900) =     35.098 ms/op
     p(99.9990) =     35.914 ms/op
     p(99.9999) =     35.914 ms/op
    p(100.0000) =     35.914 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.296 ± 4.542  ops/ms
ClientPb.existUser                       thrpt       3   9.554 ± 1.576  ops/ms
ClientPb.getUser                         thrpt       3   9.128 ± 0.500  ops/ms
ClientPb.listUser                        thrpt       3   7.747 ± 3.497  ops/ms
ClientPb.createUser                       avgt       3   3.492 ± 1.952   ms/op
ClientPb.existUser                        avgt       3   3.384 ± 1.369   ms/op
ClientPb.getUser                          avgt       3   3.626 ± 2.486   ms/op
ClientPb.listUser                         avgt       3   4.005 ± 1.088   ms/op
ClientPb.createUser                     sample  261460   3.669 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.348           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.400           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.293           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.816           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.340           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.249           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.045           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.212           ms/op
ClientPb.existUser                      sample  282288   3.398 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.149           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.301           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.801           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.202           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.169           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.530           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.060           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.263           ms/op
ClientPb.getUser                        sample  266261   3.607 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.585           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.465           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.182           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.850           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.865           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.578           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.244           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.525           ms/op
ClientPb.listUser                       sample  232269   4.134 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.708           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.653           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.202           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.151           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.448           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.098           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.914           ms/op
