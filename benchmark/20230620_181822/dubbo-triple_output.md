# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.792 ops/ms
# Warmup Iteration   2: 4.363 ops/ms
# Warmup Iteration   3: 8.362 ops/ms
Iteration   1: 8.444 ops/ms
Iteration   2: 8.930 ops/ms
Iteration   3: 9.035 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.803 ±(99.9%) 5.750 ops/ms [Average]
  (min, avg, max) = (8.444, 8.803, 9.035), stdev = 0.315
  CI (99.9%): [3.053, 14.554] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.596 ops/ms
# Warmup Iteration   2: 8.097 ops/ms
# Warmup Iteration   3: 9.154 ops/ms
Iteration   1: 9.028 ops/ms
Iteration   2: 9.593 ops/ms
Iteration   3: 9.085 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.235 ±(99.9%) 5.676 ops/ms [Average]
  (min, avg, max) = (9.028, 9.235, 9.593), stdev = 0.311
  CI (99.9%): [3.560, 14.911] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.667 ops/ms
# Warmup Iteration   2: 8.294 ops/ms
# Warmup Iteration   3: 8.799 ops/ms
Iteration   1: 9.019 ops/ms
Iteration   2: 9.386 ops/ms
Iteration   3: 9.213 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.206 ±(99.9%) 3.353 ops/ms [Average]
  (min, avg, max) = (9.019, 9.206, 9.386), stdev = 0.184
  CI (99.9%): [5.853, 12.559] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.062 ops/ms
# Warmup Iteration   2: 6.570 ops/ms
# Warmup Iteration   3: 7.669 ops/ms
Iteration   1: 7.826 ops/ms
Iteration   2: 7.843 ops/ms
Iteration   3: 7.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.848 ±(99.9%) 0.472 ops/ms [Average]
  (min, avg, max) = (7.826, 7.848, 7.877), stdev = 0.026
  CI (99.9%): [7.376, 8.321] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.181 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 3.871 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.509 ±(99.9%) 0.012 ms/op
Iteration   1: 3.564 ±(99.9%) 0.008 ms/op
Iteration   2: 3.507 ±(99.9%) 0.012 ms/op
Iteration   3: 3.408 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.493 ±(99.9%) 1.444 ms/op [Average]
  (min, avg, max) = (3.408, 3.493, 3.564), stdev = 0.079
  CI (99.9%): [2.049, 4.937] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 9.486 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.838 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.361 ±(99.9%) 0.005 ms/op
Iteration   1: 3.472 ±(99.9%) 0.007 ms/op
Iteration   2: 3.567 ±(99.9%) 0.005 ms/op
Iteration   3: 3.291 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.444 ±(99.9%) 2.559 ms/op [Average]
  (min, avg, max) = (3.291, 3.444, 3.567), stdev = 0.140
  CI (99.9%): [0.885, 6.002] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.766 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.612 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.678 ±(99.9%) 0.004 ms/op
Iteration   1: 3.506 ±(99.9%) 0.008 ms/op
Iteration   2: 3.463 ±(99.9%) 0.012 ms/op
Iteration   3: 3.370 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.446 ±(99.9%) 1.264 ms/op [Average]
  (min, avg, max) = (3.370, 3.446, 3.506), stdev = 0.069
  CI (99.9%): [2.183, 4.710] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 12.188 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.734 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.168 ±(99.9%) 0.010 ms/op
Iteration   1: 4.140 ±(99.9%) 0.010 ms/op
Iteration   2: 4.032 ±(99.9%) 0.015 ms/op
Iteration   3: 4.253 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.142 ±(99.9%) 2.011 ms/op [Average]
  (min, avg, max) = (4.032, 4.142, 4.253), stdev = 0.110
  CI (99.9%): [2.130, 6.153] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 11.028 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.270 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.804 ±(99.9%) 0.015 ms/op
Iteration   1: 3.587 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.569 ms/op
                 createUser·p0.50:   3.420 ms/op
                 createUser·p0.90:   4.170 ms/op
                 createUser·p0.95:   4.669 ms/op
                 createUser·p0.99:   6.283 ms/op
                 createUser·p0.999:  19.674 ms/op
                 createUser·p0.9999: 26.001 ms/op
                 createUser·p1.00:   27.427 ms/op

Iteration   2: 3.500 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.309 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  20.677 ms/op
                 createUser·p0.9999: 26.378 ms/op
                 createUser·p1.00:   28.901 ms/op

Iteration   3: 3.597 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.483 ms/op
                 createUser·p0.50:   3.490 ms/op
                 createUser·p0.90:   4.112 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   6.398 ms/op
                 createUser·p0.999:  23.474 ms/op
                 createUser·p0.9999: 29.029 ms/op
                 createUser·p1.00:   32.997 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 269550
  mean =      3.561 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6112 
    [ 2.500,  5.000) = 255600 
    [ 5.000,  7.500) = 6607 
    [ 7.500, 10.000) = 796 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 118 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.309 ms/op
     p(50.0000) =      3.449 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     20.134 ms/op
     p(99.9900) =     27.918 ms/op
     p(99.9990) =     32.909 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.496 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.850 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.657 ±(99.9%) 0.010 ms/op
Iteration   1: 3.431 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.163 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.858 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   6.111 ms/op
                 existUser·p0.999:  18.723 ms/op
                 existUser·p0.9999: 29.798 ms/op
                 existUser·p1.00:   30.638 ms/op

Iteration   2: 3.483 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.421 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   3.961 ms/op
                 existUser·p0.95:   4.432 ms/op
                 existUser·p0.99:   6.201 ms/op
                 existUser·p0.999:  19.317 ms/op
                 existUser·p0.9999: 23.620 ms/op
                 existUser·p1.00:   24.117 ms/op

Iteration   3: 3.377 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.135 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   4.030 ms/op
                 existUser·p0.99:   5.964 ms/op
                 existUser·p0.999:  8.323 ms/op
                 existUser·p0.9999: 26.021 ms/op
                 existUser·p1.00:   28.475 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 279793
  mean =      3.429 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8870 
    [ 2.500,  5.000) = 264489 
    [ 5.000,  7.500) = 5328 
    [ 7.500, 10.000) = 615 
    [10.000, 12.500) = 199 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     13.831 ms/op
     p(99.9900) =     29.131 ms/op
     p(99.9990) =     30.481 ms/op
     p(99.9999) =     30.638 ms/op
    p(100.0000) =     30.638 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.817 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.081 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.613 ±(99.9%) 0.010 ms/op
Iteration   1: 3.578 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.214 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   5.546 ms/op
                 getUser·p0.99:   7.250 ms/op
                 getUser·p0.999:  20.513 ms/op
                 getUser·p0.9999: 25.663 ms/op
                 getUser·p1.00:   26.804 ms/op

Iteration   2: 3.437 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.298 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   5.792 ms/op
                 getUser·p0.999:  21.919 ms/op
                 getUser·p0.9999: 24.495 ms/op
                 getUser·p1.00:   25.395 ms/op

Iteration   3: 3.559 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.374 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   6.212 ms/op
                 getUser·p0.999:  10.224 ms/op
                 getUser·p0.9999: 26.247 ms/op
                 getUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272411
  mean =      3.523 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7377 
    [ 2.500,  5.000) = 254876 
    [ 5.000,  7.500) = 8739 
    [ 7.500, 10.000) = 917 
    [10.000, 12.500) = 181 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 69 

  Percentiles, ms/op:
      p(0.0000) =      1.214 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      6.660 ms/op
     p(99.9000) =     17.596 ms/op
     p(99.9900) =     25.944 ms/op
     p(99.9990) =     26.686 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.487 ±(99.9%) 0.180 ms/op
# Warmup Iteration   2: 4.564 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.329 ±(99.9%) 0.015 ms/op
Iteration   1: 4.182 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.624 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   8.257 ms/op
                 listUser·p0.999:  19.660 ms/op
                 listUser·p0.9999: 27.220 ms/op
                 listUser·p1.00:   28.213 ms/op

Iteration   2: 4.187 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.769 ms/op
                 listUser·p0.50:   4.067 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   4.907 ms/op
                 listUser·p0.99:   7.823 ms/op
                 listUser·p0.999:  15.581 ms/op
                 listUser·p0.9999: 20.426 ms/op
                 listUser·p1.00:   20.513 ms/op

Iteration   3: 4.348 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.122 ms/op
                 listUser·p0.50:   4.186 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   8.225 ms/op
                 listUser·p0.999:  15.745 ms/op
                 listUser·p0.9999: 18.622 ms/op
                 listUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 226340
  mean =      4.238 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 213447 
    [ 5.000,  7.500) = 9289 
    [ 7.500, 10.000) = 2647 
    [10.000, 12.500) = 419 
    [12.500, 15.000) = 162 
    [15.000, 17.500) = 163 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      1.624 ms/op
     p(50.0000) =      4.080 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.136 ms/op
     p(99.0000) =      8.176 ms/op
     p(99.9000) =     16.908 ms/op
     p(99.9900) =     26.280 ms/op
     p(99.9990) =     27.867 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.803 ± 5.750  ops/ms
ClientPb.existUser                       thrpt       3   9.235 ± 5.676  ops/ms
ClientPb.getUser                         thrpt       3   9.206 ± 3.353  ops/ms
ClientPb.listUser                        thrpt       3   7.848 ± 0.472  ops/ms
ClientPb.createUser                       avgt       3   3.493 ± 1.444   ms/op
ClientPb.existUser                        avgt       3   3.444 ± 2.559   ms/op
ClientPb.getUser                          avgt       3   3.446 ± 1.264   ms/op
ClientPb.listUser                         avgt       3   4.142 ± 2.011   ms/op
ClientPb.createUser                     sample  269550   3.561 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.309           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.449           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.067           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.432           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.111           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.134           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.918           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.997           ms/op
ClientPb.existUser                      sample  279793   3.429 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.135           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.322           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.850           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.235           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.029           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.831           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.131           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.638           ms/op
ClientPb.getUser                        sample  272411   3.523 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.214           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.363           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.071           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.547           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.660           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.596           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.944           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.804           ms/op
ClientPb.listUser                       sample  226340   4.238 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.624           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.080           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.669           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.136           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.176           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.908           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.280           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.213           ms/op
