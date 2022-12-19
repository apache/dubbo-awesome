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
# Warmup Iteration   1: 2.035 ops/ms
# Warmup Iteration   2: 5.697 ops/ms
# Warmup Iteration   3: 8.472 ops/ms
Iteration   1: 9.280 ops/ms
Iteration   2: 9.660 ops/ms
Iteration   3: 9.456 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.465 ±(99.9%) 3.468 ops/ms [Average]
  (min, avg, max) = (9.280, 9.465, 9.660), stdev = 0.190
  CI (99.9%): [5.997, 12.933] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.392 ops/ms
# Warmup Iteration   2: 8.155 ops/ms
# Warmup Iteration   3: 9.338 ops/ms
Iteration   1: 9.730 ops/ms
Iteration   2: 9.969 ops/ms
Iteration   3: 9.875 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.858 ±(99.9%) 2.191 ops/ms [Average]
  (min, avg, max) = (9.730, 9.858, 9.969), stdev = 0.120
  CI (99.9%): [7.666, 12.049] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.866 ops/ms
# Warmup Iteration   2: 8.550 ops/ms
# Warmup Iteration   3: 9.185 ops/ms
Iteration   1: 9.703 ops/ms
Iteration   2: 9.442 ops/ms
Iteration   3: 9.505 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.550 ±(99.9%) 2.478 ops/ms [Average]
  (min, avg, max) = (9.442, 9.550, 9.703), stdev = 0.136
  CI (99.9%): [7.073, 12.028] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.018 ops/ms
# Warmup Iteration   2: 7.124 ops/ms
# Warmup Iteration   3: 7.905 ops/ms
Iteration   1: 8.013 ops/ms
Iteration   2: 8.025 ops/ms
Iteration   3: 7.994 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.011 ±(99.9%) 0.284 ops/ms [Average]
  (min, avg, max) = (7.994, 8.011, 8.025), stdev = 0.016
  CI (99.9%): [7.727, 8.294] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 11.450 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.151 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.435 ±(99.9%) 0.006 ms/op
Iteration   1: 3.356 ±(99.9%) 0.009 ms/op
Iteration   2: 3.362 ±(99.9%) 0.012 ms/op
Iteration   3: 3.291 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.337 ±(99.9%) 0.722 ms/op [Average]
  (min, avg, max) = (3.291, 3.337, 3.362), stdev = 0.040
  CI (99.9%): [2.614, 4.059] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.727 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.638 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.285 ±(99.9%) 0.003 ms/op
Iteration   1: 3.187 ±(99.9%) 0.010 ms/op
Iteration   2: 3.331 ±(99.9%) 0.007 ms/op
Iteration   3: 3.207 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.241 ±(99.9%) 1.427 ms/op [Average]
  (min, avg, max) = (3.187, 3.241, 3.331), stdev = 0.078
  CI (99.9%): [1.815, 4.668] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.650 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.685 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.506 ±(99.9%) 0.013 ms/op
Iteration   1: 3.432 ±(99.9%) 0.008 ms/op
Iteration   2: 3.408 ±(99.9%) 0.008 ms/op
Iteration   3: 3.413 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.418 ±(99.9%) 0.236 ms/op [Average]
  (min, avg, max) = (3.408, 3.418, 3.432), stdev = 0.013
  CI (99.9%): [3.182, 3.654] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.182 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.392 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.207 ±(99.9%) 0.006 ms/op
Iteration   1: 4.129 ±(99.9%) 0.010 ms/op
Iteration   2: 3.855 ±(99.9%) 0.016 ms/op
Iteration   3: 3.899 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.961 ±(99.9%) 2.688 ms/op [Average]
  (min, avg, max) = (3.855, 3.961, 4.129), stdev = 0.147
  CI (99.9%): [1.273, 6.648] (assumes normal distribution)


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
# Warmup Iteration   1: 10.091 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 4.225 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.474 ±(99.9%) 0.009 ms/op
Iteration   1: 3.675 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.430 ms/op
                 createUser·p0.50:   3.453 ms/op
                 createUser·p0.90:   4.358 ms/op
                 createUser·p0.95:   5.985 ms/op
                 createUser·p0.99:   7.193 ms/op
                 createUser·p0.999:  21.689 ms/op
                 createUser·p0.9999: 24.969 ms/op
                 createUser·p1.00:   25.461 ms/op

Iteration   2: 3.348 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.354 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   5.428 ms/op
                 createUser·p0.999:  22.869 ms/op
                 createUser·p0.9999: 25.508 ms/op
                 createUser·p1.00:   25.887 ms/op

Iteration   3: 3.418 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.370 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  19.152 ms/op
                 createUser·p0.9999: 26.945 ms/op
                 createUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276181
  mean =      3.475 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11371 
    [ 2.500,  5.000) = 254894 
    [ 5.000,  7.500) = 8794 
    [ 7.500, 10.000) = 683 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 162 
    [25.000, 27.500) = 67 

  Percentiles, ms/op:
      p(0.0000) =      1.354 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     20.146 ms/op
     p(99.9900) =     25.642 ms/op
     p(99.9990) =     27.984 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


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
# Warmup Iteration   1: 7.490 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.449 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.477 ±(99.9%) 0.011 ms/op
Iteration   1: 3.210 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.606 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  9.896 ms/op
                 existUser·p0.9999: 27.037 ms/op
                 existUser·p1.00:   27.984 ms/op

Iteration   2: 3.316 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.282 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.641 ms/op
                 existUser·p0.95:   4.059 ms/op
                 existUser·p0.99:   6.054 ms/op
                 existUser·p0.999:  19.042 ms/op
                 existUser·p0.9999: 25.910 ms/op
                 existUser·p1.00:   26.575 ms/op

Iteration   3: 3.428 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.323 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   4.162 ms/op
                 existUser·p0.95:   4.481 ms/op
                 existUser·p0.99:   5.979 ms/op
                 existUser·p0.999:  19.890 ms/op
                 existUser·p0.9999: 27.197 ms/op
                 existUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289321
  mean =      3.316 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16534 
    [ 2.500,  5.000) = 266229 
    [ 5.000,  7.500) = 5770 
    [ 7.500, 10.000) = 473 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 91 

  Percentiles, ms/op:
      p(0.0000) =      1.282 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     11.300 ms/op
     p(99.9900) =     26.640 ms/op
     p(99.9990) =     28.045 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


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
# Warmup Iteration   1: 9.045 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.729 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.537 ±(99.9%) 0.011 ms/op
Iteration   1: 3.340 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.657 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  20.409 ms/op
                 getUser·p0.9999: 23.607 ms/op
                 getUser·p1.00:   25.199 ms/op

Iteration   2: 3.386 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.475 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  22.237 ms/op
                 getUser·p0.9999: 29.659 ms/op
                 getUser·p1.00:   30.507 ms/op

Iteration   3: 3.530 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.696 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   4.104 ms/op
                 getUser·p0.95:   4.850 ms/op
                 getUser·p0.99:   7.070 ms/op
                 getUser·p0.999:  14.162 ms/op
                 getUser·p0.9999: 24.869 ms/op
                 getUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280824
  mean =      3.417 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5541 
    [ 2.500,  5.000) = 267987 
    [ 5.000,  7.500) = 6168 
    [ 7.500, 10.000) = 723 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 112 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.475 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      6.339 ms/op
     p(99.9000) =     14.172 ms/op
     p(99.9900) =     27.522 ms/op
     p(99.9990) =     30.217 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


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
# Warmup Iteration   1: 10.214 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.267 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.304 ±(99.9%) 0.014 ms/op
Iteration   1: 4.219 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.393 ms/op
                 listUser·p0.50:   4.076 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   7.578 ms/op
                 listUser·p0.999:  22.741 ms/op
                 listUser·p0.9999: 27.441 ms/op
                 listUser·p1.00:   27.656 ms/op

Iteration   2: 4.021 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.384 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  15.831 ms/op
                 listUser·p0.9999: 23.725 ms/op
                 listUser·p1.00:   25.068 ms/op

Iteration   3: 4.074 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   8.069 ms/op
                 listUser·p0.999:  15.122 ms/op
                 listUser·p0.9999: 23.724 ms/op
                 listUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234064
  mean =      4.103 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 224656 
    [ 5.000,  7.500) = 6827 
    [ 7.500, 10.000) = 1547 
    [10.000, 12.500) = 405 
    [12.500, 15.000) = 271 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      1.393 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      7.643 ms/op
     p(99.9000) =     16.726 ms/op
     p(99.9900) =     26.252 ms/op
     p(99.9990) =     27.579 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.465 ± 3.468  ops/ms
ClientPb.existUser                       thrpt       3   9.858 ± 2.191  ops/ms
ClientPb.getUser                         thrpt       3   9.550 ± 2.478  ops/ms
ClientPb.listUser                        thrpt       3   8.011 ± 0.284  ops/ms
ClientPb.createUser                       avgt       3   3.337 ± 0.722   ms/op
ClientPb.existUser                        avgt       3   3.241 ± 1.427   ms/op
ClientPb.getUser                          avgt       3   3.418 ± 0.236   ms/op
ClientPb.listUser                         avgt       3   3.961 ± 2.688   ms/op
ClientPb.createUser                     sample  276181   3.475 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.354           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.351           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.875           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.325           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.824           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.146           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.642           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.213           ms/op
ClientPb.existUser                      sample  289321   3.316 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.282           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.232           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.276           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.898           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.300           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.640           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.279           ms/op
ClientPb.getUser                        sample  280824   3.417 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.475           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.289           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.108           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.339           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.172           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.522           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.507           ms/op
ClientPb.listUser                       sample  234064   4.103 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.393           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.809           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.643           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.726           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.252           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.656           ms/op
