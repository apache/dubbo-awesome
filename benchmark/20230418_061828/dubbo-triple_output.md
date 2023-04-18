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
# Warmup Iteration   1: 2.599 ops/ms
# Warmup Iteration   2: 6.694 ops/ms
# Warmup Iteration   3: 9.134 ops/ms
Iteration   1: 9.646 ops/ms
Iteration   2: 10.066 ops/ms
Iteration   3: 10.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.908 ±(99.9%) 4.163 ops/ms [Average]
  (min, avg, max) = (9.646, 9.908, 10.066), stdev = 0.228
  CI (99.9%): [5.744, 14.071] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.401 ops/ms
# Warmup Iteration   2: 9.228 ops/ms
# Warmup Iteration   3: 9.826 ops/ms
Iteration   1: 10.689 ops/ms
Iteration   2: 10.617 ops/ms
Iteration   3: 10.146 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.484 ±(99.9%) 5.377 ops/ms [Average]
  (min, avg, max) = (10.146, 10.484, 10.689), stdev = 0.295
  CI (99.9%): [5.107, 15.861] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.498 ops/ms
# Warmup Iteration   2: 9.186 ops/ms
# Warmup Iteration   3: 9.460 ops/ms
Iteration   1: 10.069 ops/ms
Iteration   2: 10.370 ops/ms
Iteration   3: 10.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.181 ±(99.9%) 3.001 ops/ms [Average]
  (min, avg, max) = (10.069, 10.181, 10.370), stdev = 0.164
  CI (99.9%): [7.180, 13.182] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.752 ops/ms
# Warmup Iteration   2: 7.897 ops/ms
# Warmup Iteration   3: 8.406 ops/ms
Iteration   1: 8.389 ops/ms
Iteration   2: 8.687 ops/ms
Iteration   3: 8.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.550 ±(99.9%) 2.739 ops/ms [Average]
  (min, avg, max) = (8.389, 8.550, 8.687), stdev = 0.150
  CI (99.9%): [5.811, 11.289] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.259 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.435 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.179 ±(99.9%) 0.005 ms/op
Iteration   1: 3.218 ±(99.9%) 0.010 ms/op
Iteration   2: 3.129 ±(99.9%) 0.006 ms/op
Iteration   3: 3.165 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.170 ±(99.9%) 0.818 ms/op [Average]
  (min, avg, max) = (3.129, 3.170, 3.218), stdev = 0.045
  CI (99.9%): [2.352, 3.989] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 6.464 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.279 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.306 ±(99.9%) 0.001 ms/op
Iteration   1: 3.004 ±(99.9%) 0.001 ms/op
Iteration   2: 3.166 ±(99.9%) 0.006 ms/op
Iteration   3: 3.015 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.062 ±(99.9%) 1.653 ms/op [Average]
  (min, avg, max) = (3.004, 3.062, 3.166), stdev = 0.091
  CI (99.9%): [1.409, 4.715] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.214 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.342 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.186 ±(99.9%) 0.005 ms/op
Iteration   1: 3.204 ±(99.9%) 0.006 ms/op
Iteration   2: 3.272 ±(99.9%) 0.003 ms/op
Iteration   3: 3.184 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.220 ±(99.9%) 0.839 ms/op [Average]
  (min, avg, max) = (3.184, 3.220, 3.272), stdev = 0.046
  CI (99.9%): [2.382, 4.059] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.479 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.913 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.720 ±(99.9%) 0.009 ms/op
Iteration   1: 3.613 ±(99.9%) 0.012 ms/op
Iteration   2: 3.708 ±(99.9%) 0.008 ms/op
Iteration   3: 3.726 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.682 ±(99.9%) 1.106 ms/op [Average]
  (min, avg, max) = (3.613, 3.682, 3.726), stdev = 0.061
  CI (99.9%): [2.577, 4.788] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.722 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.696 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.267 ±(99.9%) 0.010 ms/op
Iteration   1: 3.276 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.309 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.738 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  18.722 ms/op
                 createUser·p0.9999: 20.283 ms/op
                 createUser·p1.00:   20.513 ms/op

Iteration   2: 3.214 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.893 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  21.627 ms/op
                 createUser·p0.9999: 30.051 ms/op
                 createUser·p1.00:   30.736 ms/op

Iteration   3: 3.200 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.384 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  16.372 ms/op
                 createUser·p0.9999: 23.429 ms/op
                 createUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297077
  mean =      3.230 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22895 
    [ 2.500,  5.000) = 267499 
    [ 5.000,  7.500) = 5818 
    [ 7.500, 10.000) = 306 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     17.808 ms/op
     p(99.9900) =     27.521 ms/op
     p(99.9990) =     30.247 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.015 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.493 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.007 ms/op
Iteration   1: 3.015 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.174 ms/op
                 existUser·p0.95:   3.346 ms/op
                 existUser·p0.99:   5.194 ms/op
                 existUser·p0.999:  9.322 ms/op
                 existUser·p0.9999: 19.542 ms/op
                 existUser·p1.00:   20.152 ms/op

Iteration   2: 3.041 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.393 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  10.546 ms/op
                 existUser·p0.9999: 22.020 ms/op
                 existUser·p1.00:   23.003 ms/op

Iteration   3: 3.095 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.940 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   6.032 ms/op
                 existUser·p0.999:  9.011 ms/op
                 existUser·p0.9999: 19.411 ms/op
                 existUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 314436
  mean =      3.050 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14822 
    [ 2.500,  5.000) = 294097 
    [ 5.000,  7.500) = 4767 
    [ 7.500, 10.000) = 430 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 166 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.289 ms/op
     p(95.0000) =      3.510 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     10.315 ms/op
     p(99.9900) =     21.481 ms/op
     p(99.9990) =     22.086 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.482 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.308 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.367 ±(99.9%) 0.012 ms/op
Iteration   1: 3.155 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.497 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  8.937 ms/op
                 getUser·p0.9999: 24.150 ms/op
                 getUser·p1.00:   24.510 ms/op

Iteration   2: 3.127 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.978 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   5.284 ms/op
                 getUser·p0.999:  8.917 ms/op
                 getUser·p0.9999: 22.708 ms/op
                 getUser·p1.00:   23.331 ms/op

Iteration   3: 3.212 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.556 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   5.775 ms/op
                 getUser·p0.999:  13.435 ms/op
                 getUser·p0.9999: 19.202 ms/op
                 getUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 303599
  mean =      3.164 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18528 
    [ 2.500,  5.000) = 278647 
    [ 5.000,  7.500) = 5726 
    [ 7.500, 10.000) = 349 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.978 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =     12.698 ms/op
     p(99.9900) =     23.724 ms/op
     p(99.9990) =     24.444 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.035 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.278 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.690 ±(99.9%) 0.011 ms/op
Iteration   1: 3.770 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.321 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.153 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   7.330 ms/op
                 listUser·p0.999:  16.694 ms/op
                 listUser·p0.9999: 20.742 ms/op
                 listUser·p1.00:   21.398 ms/op

Iteration   2: 3.666 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.129 ms/op
                 listUser·p0.99:   6.406 ms/op
                 listUser·p0.999:  13.615 ms/op
                 listUser·p0.9999: 21.758 ms/op
                 listUser·p1.00:   21.791 ms/op

Iteration   3: 3.726 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  14.487 ms/op
                 listUser·p0.9999: 18.252 ms/op
                 listUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257831
  mean =      3.720 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 68 
    [ 2.500,  5.000) = 249832 
    [ 5.000,  7.500) = 6111 
    [ 7.500, 10.000) = 1088 
    [10.000, 12.500) = 272 
    [12.500, 15.000) = 253 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.321 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     14.189 ms/op
     p(99.9900) =     20.946 ms/op
     p(99.9990) =     21.791 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.908 ± 4.163  ops/ms
ClientPb.existUser                       thrpt       3  10.484 ± 5.377  ops/ms
ClientPb.getUser                         thrpt       3  10.181 ± 3.001  ops/ms
ClientPb.listUser                        thrpt       3   8.550 ± 2.739  ops/ms
ClientPb.createUser                       avgt       3   3.170 ± 0.818   ms/op
ClientPb.existUser                        avgt       3   3.062 ± 1.653   ms/op
ClientPb.getUser                          avgt       3   3.220 ± 0.839   ms/op
ClientPb.listUser                         avgt       3   3.682 ± 1.106   ms/op
ClientPb.createUser                     sample  297077   3.230 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.893           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.641           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.030           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.677           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.808           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.521           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.736           ms/op
ClientPb.existUser                      sample  314436   3.050 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.940           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.289           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.510           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.382           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.315           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.481           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.003           ms/op
ClientPb.getUser                        sample  303599   3.164 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.978           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.543           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.579           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.698           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.724           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.510           ms/op
ClientPb.listUser                       sample  257831   3.720 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.321           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.633           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.035           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.963           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.189           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.946           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.791           ms/op
