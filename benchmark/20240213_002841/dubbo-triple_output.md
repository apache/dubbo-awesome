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
# Warmup Iteration   1: 4.707 ops/ms
# Warmup Iteration   2: 12.297 ops/ms
# Warmup Iteration   3: 12.478 ops/ms
Iteration   1: 12.593 ops/ms
Iteration   2: 12.800 ops/ms
Iteration   3: 12.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.758 ±(99.9%) 2.719 ops/ms [Average]
  (min, avg, max) = (12.593, 12.758, 12.882), stdev = 0.149
  CI (99.9%): [10.039, 15.478] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.180 ops/ms
# Warmup Iteration   2: 13.094 ops/ms
# Warmup Iteration   3: 13.128 ops/ms
Iteration   1: 13.201 ops/ms
Iteration   2: 13.198 ops/ms
Iteration   3: 13.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.194 ±(99.9%) 0.182 ops/ms [Average]
  (min, avg, max) = (13.182, 13.194, 13.201), stdev = 0.010
  CI (99.9%): [13.012, 13.376] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.243 ops/ms
# Warmup Iteration   2: 12.697 ops/ms
# Warmup Iteration   3: 13.000 ops/ms
Iteration   1: 13.066 ops/ms
Iteration   2: 12.973 ops/ms
Iteration   3: 12.886 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.975 ±(99.9%) 1.648 ops/ms [Average]
  (min, avg, max) = (12.886, 12.975, 13.066), stdev = 0.090
  CI (99.9%): [11.327, 14.622] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.766 ops/ms
# Warmup Iteration   2: 10.474 ops/ms
# Warmup Iteration   3: 10.609 ops/ms
Iteration   1: 10.670 ops/ms
Iteration   2: 10.663 ops/ms
Iteration   3: 10.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.690 ±(99.9%) 0.742 ops/ms [Average]
  (min, avg, max) = (10.663, 10.690, 10.737), stdev = 0.041
  CI (99.9%): [9.949, 11.432] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 3.695 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.520 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.003 ms/op
Iteration   1: 2.502 ±(99.9%) 0.004 ms/op
Iteration   2: 2.515 ±(99.9%) 0.004 ms/op
Iteration   3: 2.488 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.502 ±(99.9%) 0.244 ms/op [Average]
  (min, avg, max) = (2.488, 2.502, 2.515), stdev = 0.013
  CI (99.9%): [2.258, 2.745] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.617 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.474 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.004 ms/op
Iteration   1: 2.458 ±(99.9%) 0.004 ms/op
Iteration   2: 2.458 ±(99.9%) 0.004 ms/op
Iteration   3: 2.435 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.450 ±(99.9%) 0.245 ms/op [Average]
  (min, avg, max) = (2.435, 2.450, 2.458), stdev = 0.013
  CI (99.9%): [2.205, 2.695] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.945 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.536 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.004 ms/op
Iteration   1: 2.502 ±(99.9%) 0.004 ms/op
Iteration   2: 2.483 ±(99.9%) 0.005 ms/op
Iteration   3: 2.515 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.500 ±(99.9%) 0.287 ms/op [Average]
  (min, avg, max) = (2.483, 2.500, 2.515), stdev = 0.016
  CI (99.9%): [2.213, 2.787] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.682 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.005 ms/op
Iteration   1: 2.992 ±(99.9%) 0.006 ms/op
Iteration   2: 3.001 ±(99.9%) 0.004 ms/op
Iteration   3: 3.023 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.005 ±(99.9%) 0.288 ms/op [Average]
  (min, avg, max) = (2.992, 3.005, 3.023), stdev = 0.016
  CI (99.9%): [2.718, 3.293] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.088 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.690 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.006 ms/op
Iteration   1: 2.520 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.823 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.588 ms/op
                 createUser·p0.999:  11.192 ms/op
                 createUser·p0.9999: 13.614 ms/op
                 createUser·p1.00:   14.139 ms/op

Iteration   2: 2.576 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.978 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  9.665 ms/op
                 createUser·p0.9999: 13.885 ms/op
                 createUser·p1.00:   14.909 ms/op

Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.978 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.695 ms/op
                 createUser·p0.999:  8.109 ms/op
                 createUser·p0.9999: 11.022 ms/op
                 createUser·p1.00:   13.844 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378105
  mean =      2.537 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 181142 
    [ 2.500,  3.750) = 192539 
    [ 3.750,  5.000) = 3005 
    [ 5.000,  6.250) = 801 
    [ 6.250,  7.500) = 116 
    [ 7.500,  8.750) = 98 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.823 ms/op
     p(50.0000) =      2.626 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.846 ms/op
     p(99.9000) =      8.618 ms/op
     p(99.9900) =     13.156 ms/op
     p(99.9990) =     14.345 ms/op
     p(99.9999) =     14.909 ms/op
    p(100.0000) =     14.909 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.857 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.488 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.450 ±(99.9%) 0.005 ms/op
Iteration   1: 2.432 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.015 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.514 ms/op
                 existUser·p0.999:  5.823 ms/op
                 existUser·p0.9999: 15.186 ms/op
                 existUser·p1.00:   16.368 ms/op

Iteration   2: 2.447 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.537 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.760 ms/op
                 existUser·p0.999:  8.903 ms/op
                 existUser·p0.9999: 14.253 ms/op
                 existUser·p1.00:   15.172 ms/op

Iteration   3: 2.434 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.864 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.633 ms/op
                 existUser·p0.999:  9.617 ms/op
                 existUser·p0.9999: 11.762 ms/op
                 existUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393311
  mean =      2.438 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 194651 
    [ 2.500,  3.750) = 195390 
    [ 3.750,  5.000) = 2409 
    [ 5.000,  6.250) = 283 
    [ 6.250,  7.500) = 81 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      3.629 ms/op
     p(99.9000) =      8.929 ms/op
     p(99.9900) =     14.232 ms/op
     p(99.9990) =     15.829 ms/op
     p(99.9999) =     16.368 ms/op
    p(100.0000) =     16.368 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.762 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.535 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
Iteration   1: 2.477 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.911 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.908 ms/op
                 getUser·p0.999:  7.052 ms/op
                 getUser·p0.9999: 13.063 ms/op
                 getUser·p1.00:   13.697 ms/op

Iteration   2: 2.500 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.905 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  9.348 ms/op
                 getUser·p0.9999: 12.197 ms/op
                 getUser·p1.00:   12.485 ms/op

Iteration   3: 2.468 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.967 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.699 ms/op
                 getUser·p0.999:  5.704 ms/op
                 getUser·p0.9999: 11.469 ms/op
                 getUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386530
  mean =      2.482 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 192996 
    [ 2.500,  3.750) = 188567 
    [ 3.750,  5.000) = 3907 
    [ 5.000,  6.250) = 528 
    [ 6.250,  7.500) = 73 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 53 
    [11.250, 12.500) = 156 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.905 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.903 ms/op
     p(99.9000) =      8.031 ms/op
     p(99.9900) =     12.796 ms/op
     p(99.9990) =     13.617 ms/op
     p(99.9999) =     13.697 ms/op
    p(100.0000) =     13.697 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.657 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.008 ms/op
Iteration   1: 2.970 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.847 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  8.869 ms/op
                 listUser·p0.9999: 10.497 ms/op
                 listUser·p1.00:   11.272 ms/op

Iteration   2: 2.934 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.871 ms/op
                 listUser·p0.50:   2.875 ms/op
                 listUser·p0.90:   3.740 ms/op
                 listUser·p0.95:   4.186 ms/op
                 listUser·p0.99:   5.366 ms/op
                 listUser·p0.999:  9.535 ms/op
                 listUser·p0.9999: 10.948 ms/op
                 listUser·p1.00:   11.928 ms/op

Iteration   3: 2.964 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.855 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.068 ms/op
                 listUser·p0.9999: 10.870 ms/op
                 listUser·p1.00:   11.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324465
  mean =      2.956 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 160 
    [ 1.250,  2.500) = 100514 
    [ 2.500,  3.750) = 188684 
    [ 3.750,  5.000) = 28823 
    [ 5.000,  6.250) = 5185 
    [ 6.250,  7.500) = 479 
    [ 7.500,  8.750) = 207 
    [ 8.750, 10.000) = 261 
    [10.000, 11.250) = 143 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =      9.102 ms/op
     p(99.9900) =     10.881 ms/op
     p(99.9990) =     11.612 ms/op
     p(99.9999) =     11.928 ms/op
    p(100.0000) =     11.928 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.758 ± 2.719  ops/ms
ClientPb.existUser                       thrpt       3  13.194 ± 0.182  ops/ms
ClientPb.getUser                         thrpt       3  12.975 ± 1.648  ops/ms
ClientPb.listUser                        thrpt       3  10.690 ± 0.742  ops/ms
ClientPb.createUser                       avgt       3   2.502 ± 0.244   ms/op
ClientPb.existUser                        avgt       3   2.450 ± 0.245   ms/op
ClientPb.getUser                          avgt       3   2.500 ± 0.287   ms/op
ClientPb.listUser                         avgt       3   3.005 ± 0.288   ms/op
ClientPb.createUser                     sample  378105   2.537 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.823           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.626           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.846           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.618           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.156           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.909           ms/op
ClientPb.existUser                      sample  393311   2.438 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.537           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.929           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.232           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.368           ms/op
ClientPb.getUser                        sample  386530   2.482 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.905           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.023           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.031           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.796           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.697           ms/op
ClientPb.listUser                       sample  324465   2.956 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.847           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.896           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.801           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.472           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.102           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.881           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.928           ms/op
