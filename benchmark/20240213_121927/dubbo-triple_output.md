# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.999 ops/ms
# Warmup Iteration   2: 11.921 ops/ms
# Warmup Iteration   3: 12.397 ops/ms
Iteration   1: 12.487 ops/ms
Iteration   2: 12.570 ops/ms
Iteration   3: 12.570 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.542 ±(99.9%) 0.872 ops/ms [Average]
  (min, avg, max) = (12.487, 12.542, 12.570), stdev = 0.048
  CI (99.9%): [11.670, 13.414] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.091 ops/ms
# Warmup Iteration   2: 12.768 ops/ms
# Warmup Iteration   3: 12.905 ops/ms
Iteration   1: 12.914 ops/ms
Iteration   2: 13.012 ops/ms
Iteration   3: 12.842 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.923 ±(99.9%) 1.559 ops/ms [Average]
  (min, avg, max) = (12.842, 12.923, 13.012), stdev = 0.085
  CI (99.9%): [11.364, 14.482] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.658 ops/ms
# Warmup Iteration   2: 12.680 ops/ms
# Warmup Iteration   3: 12.818 ops/ms
Iteration   1: 12.932 ops/ms
Iteration   2: 12.901 ops/ms
Iteration   3: 12.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.843 ±(99.9%) 2.358 ops/ms [Average]
  (min, avg, max) = (12.695, 12.843, 12.932), stdev = 0.129
  CI (99.9%): [10.485, 15.200] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.917 ops/ms
# Warmup Iteration   2: 10.541 ops/ms
# Warmup Iteration   3: 10.504 ops/ms
Iteration   1: 10.656 ops/ms
Iteration   2: 10.789 ops/ms
Iteration   3: 10.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.703 ±(99.9%) 1.360 ops/ms [Average]
  (min, avg, max) = (10.656, 10.703, 10.789), stdev = 0.075
  CI (99.9%): [9.343, 12.062] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.001 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.003 ms/op
Iteration   1: 2.507 ±(99.9%) 0.004 ms/op
Iteration   2: 2.509 ±(99.9%) 0.004 ms/op
Iteration   3: 2.518 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.512 ±(99.9%) 0.110 ms/op [Average]
  (min, avg, max) = (2.507, 2.512, 2.518), stdev = 0.006
  CI (99.9%): [2.402, 2.621] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.821 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.428 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.423 ±(99.9%) 0.004 ms/op
Iteration   1: 2.417 ±(99.9%) 0.004 ms/op
Iteration   2: 2.440 ±(99.9%) 0.004 ms/op
Iteration   3: 2.411 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.423 ±(99.9%) 0.284 ms/op [Average]
  (min, avg, max) = (2.411, 2.423, 2.440), stdev = 0.016
  CI (99.9%): [2.138, 2.707] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.820 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.528 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.004 ms/op
Iteration   1: 2.503 ±(99.9%) 0.005 ms/op
Iteration   2: 2.506 ±(99.9%) 0.004 ms/op
Iteration   3: 2.464 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.491 ±(99.9%) 0.426 ms/op [Average]
  (min, avg, max) = (2.464, 2.491, 2.506), stdev = 0.023
  CI (99.9%): [2.065, 2.917] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.534 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.040 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.004 ms/op
Iteration   1: 3.037 ±(99.9%) 0.005 ms/op
Iteration   2: 3.028 ±(99.9%) 0.006 ms/op
Iteration   3: 2.993 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.019 ±(99.9%) 0.419 ms/op [Average]
  (min, avg, max) = (2.993, 3.019, 3.037), stdev = 0.023
  CI (99.9%): [2.600, 3.438] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.102 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.638 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
Iteration   1: 2.541 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.787 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  11.586 ms/op
                 createUser·p0.9999: 13.409 ms/op
                 createUser·p1.00:   13.664 ms/op

Iteration   2: 2.495 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.012 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.604 ms/op
                 createUser·p0.999:  9.069 ms/op
                 createUser·p0.9999: 11.996 ms/op
                 createUser·p1.00:   13.140 ms/op

Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.838 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.834 ms/op
                 createUser·p0.999:  7.829 ms/op
                 createUser·p0.9999: 11.059 ms/op
                 createUser·p1.00:   12.075 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381691
  mean =      2.513 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 184914 
    [ 2.500,  3.750) = 192074 
    [ 3.750,  5.000) = 3635 
    [ 5.000,  6.250) = 501 
    [ 6.250,  7.500) = 88 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 137 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      8.700 ms/op
     p(99.9900) =     13.058 ms/op
     p(99.9990) =     13.648 ms/op
     p(99.9999) =     13.664 ms/op
    p(100.0000) =     13.664 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.708 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.471 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.429 ±(99.9%) 0.005 ms/op
Iteration   1: 2.472 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.893 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.740 ms/op
                 existUser·p0.999:  11.878 ms/op
                 existUser·p0.9999: 13.790 ms/op
                 existUser·p1.00:   16.581 ms/op

Iteration   2: 2.419 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.002 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.518 ms/op
                 existUser·p0.999:  6.813 ms/op
                 existUser·p0.9999: 12.923 ms/op
                 existUser·p1.00:   13.894 ms/op

Iteration   3: 2.436 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.911 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.658 ms/op
                 existUser·p0.999:  5.845 ms/op
                 existUser·p0.9999: 19.694 ms/op
                 existUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392761
  mean =      2.442 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 195704 
    [ 2.500,  5.000) = 196002 
    [ 5.000,  7.500) = 626 
    [ 7.500, 10.000) = 87 
    [10.000, 12.500) = 221 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.650 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     14.139 ms/op
     p(99.9990) =     20.187 ms/op
     p(99.9999) =     20.382 ms/op
    p(100.0000) =     20.382 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.732 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.536 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.006 ms/op
Iteration   1: 2.475 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.592 ms/op
                 getUser·p0.999:  6.046 ms/op
                 getUser·p0.9999: 20.909 ms/op
                 getUser·p1.00:   21.332 ms/op

Iteration   2: 2.491 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.049 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   4.098 ms/op
                 getUser·p0.999:  7.977 ms/op
                 getUser·p0.9999: 11.799 ms/op
                 getUser·p1.00:   12.370 ms/op

Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.839 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.977 ms/op
                 getUser·p0.999:  8.520 ms/op
                 getUser·p0.9999: 10.735 ms/op
                 getUser·p1.00:   11.010 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385295
  mean =      2.490 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 192161 
    [ 2.500,  5.000) = 192209 
    [ 5.000,  7.500) = 541 
    [ 7.500, 10.000) = 142 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.903 ms/op
     p(99.9000) =      7.040 ms/op
     p(99.9900) =     13.647 ms/op
     p(99.9990) =     21.238 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.495 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.008 ms/op
Iteration   1: 3.022 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.723 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.545 ms/op
                 listUser·p0.999:  9.145 ms/op
                 listUser·p0.9999: 10.886 ms/op
                 listUser·p1.00:   11.125 ms/op

Iteration   2: 3.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.831 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.558 ms/op
                 listUser·p0.999:  9.978 ms/op
                 listUser·p0.9999: 16.222 ms/op
                 listUser·p1.00:   16.564 ms/op

Iteration   3: 3.017 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.857 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.093 ms/op
                 listUser·p0.9999: 12.675 ms/op
                 listUser·p1.00:   13.287 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318053
  mean =      3.015 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 111 
    [ 1.250,  2.500) = 92033 
    [ 2.500,  3.750) = 187550 
    [ 3.750,  5.000) = 31290 
    [ 5.000,  6.250) = 5929 
    [ 6.250,  7.500) = 504 
    [ 7.500,  8.750) = 201 
    [ 8.750, 10.000) = 228 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     15.024 ms/op
     p(99.9990) =     16.397 ms/op
     p(99.9999) =     16.564 ms/op
    p(100.0000) =     16.564 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.542 ± 0.872  ops/ms
ClientPb.existUser                       thrpt       3  12.923 ± 1.559  ops/ms
ClientPb.getUser                         thrpt       3  12.843 ± 2.358  ops/ms
ClientPb.listUser                        thrpt       3  10.703 ± 1.360  ops/ms
ClientPb.createUser                       avgt       3   2.512 ± 0.110   ms/op
ClientPb.existUser                        avgt       3   2.423 ± 0.284   ms/op
ClientPb.getUser                          avgt       3   2.491 ± 0.426   ms/op
ClientPb.listUser                         avgt       3   3.019 ± 0.419   ms/op
ClientPb.createUser                     sample  381691   2.513 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.787           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.700           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.058           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.664           ms/op
ClientPb.existUser                      sample  392761   2.442 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.893           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.970           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.650           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.044           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.139           ms/op
ClientPb.existUser:existUser·p1.00      sample          20.382           ms/op
ClientPb.getUser                        sample  385295   2.490 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.839           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.040           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.647           ms/op
ClientPb.getUser:getUser·p1.00          sample          21.332           ms/op
ClientPb.listUser                       sample  318053   3.015 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.723           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.538           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.339           ms/op
ClientPb.listUser:listUser·p0.9999      sample          15.024           ms/op
ClientPb.listUser:listUser·p1.00        sample          16.564           ms/op
