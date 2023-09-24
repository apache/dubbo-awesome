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
# Warmup Iteration   1: 2.101 ops/ms
# Warmup Iteration   2: 5.792 ops/ms
# Warmup Iteration   3: 8.836 ops/ms
Iteration   1: 9.106 ops/ms
Iteration   2: 9.047 ops/ms
Iteration   3: 9.015 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.056 ±(99.9%) 0.845 ops/ms [Average]
  (min, avg, max) = (9.015, 9.056, 9.106), stdev = 0.046
  CI (99.9%): [8.211, 9.901] (assumes normal distribution)


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
# Warmup Iteration   1: 2.610 ops/ms
# Warmup Iteration   2: 8.594 ops/ms
# Warmup Iteration   3: 9.393 ops/ms
Iteration   1: 9.798 ops/ms
Iteration   2: 9.543 ops/ms
Iteration   3: 9.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.640 ±(99.9%) 2.518 ops/ms [Average]
  (min, avg, max) = (9.543, 9.640, 9.798), stdev = 0.138
  CI (99.9%): [7.122, 12.157] (assumes normal distribution)


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
# Warmup Iteration   1: 2.820 ops/ms
# Warmup Iteration   2: 8.384 ops/ms
# Warmup Iteration   3: 8.576 ops/ms
Iteration   1: 8.925 ops/ms
Iteration   2: 9.336 ops/ms
Iteration   3: 8.999 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.086 ±(99.9%) 3.999 ops/ms [Average]
  (min, avg, max) = (8.925, 9.086, 9.336), stdev = 0.219
  CI (99.9%): [5.088, 13.085] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.322 ops/ms
# Warmup Iteration   2: 6.643 ops/ms
# Warmup Iteration   3: 7.289 ops/ms
Iteration   1: 7.287 ops/ms
Iteration   2: 7.407 ops/ms
Iteration   3: 7.534 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.410 ±(99.9%) 2.253 ops/ms [Average]
  (min, avg, max) = (7.287, 7.410, 7.534), stdev = 0.124
  CI (99.9%): [5.157, 9.663] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 11.228 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.857 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.683 ±(99.9%) 0.004 ms/op
Iteration   1: 3.734 ±(99.9%) 0.004 ms/op
Iteration   2: 3.567 ±(99.9%) 0.003 ms/op
Iteration   3: 3.446 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.583 ±(99.9%) 2.638 ms/op [Average]
  (min, avg, max) = (3.446, 3.583, 3.734), stdev = 0.145
  CI (99.9%): [0.944, 6.221] (assumes normal distribution)


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
# Warmup Iteration   1: 9.352 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.661 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.426 ±(99.9%) 0.004 ms/op
Iteration   1: 3.368 ±(99.9%) 0.003 ms/op
Iteration   2: 3.329 ±(99.9%) 0.003 ms/op
Iteration   3: 3.382 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.359 ±(99.9%) 0.502 ms/op [Average]
  (min, avg, max) = (3.329, 3.359, 3.382), stdev = 0.027
  CI (99.9%): [2.858, 3.861] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.326 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.872 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.538 ±(99.9%) 0.006 ms/op
Iteration   1: 3.563 ±(99.9%) 0.002 ms/op
Iteration   2: 3.478 ±(99.9%) 0.006 ms/op
Iteration   3: 3.539 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.527 ±(99.9%) 0.798 ms/op [Average]
  (min, avg, max) = (3.478, 3.527, 3.563), stdev = 0.044
  CI (99.9%): [2.729, 4.325] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 12.202 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.456 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.292 ±(99.9%) 0.007 ms/op
Iteration   1: 4.140 ±(99.9%) 0.008 ms/op
Iteration   2: 4.163 ±(99.9%) 0.005 ms/op
Iteration   3: 4.205 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.170 ±(99.9%) 0.602 ms/op [Average]
  (min, avg, max) = (4.140, 4.170, 4.205), stdev = 0.033
  CI (99.9%): [3.568, 4.771] (assumes normal distribution)


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
# Warmup Iteration   1: 8.382 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.144 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.541 ±(99.9%) 0.010 ms/op
Iteration   1: 3.583 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.468 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   4.166 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   6.349 ms/op
                 createUser·p0.999:  20.437 ms/op
                 createUser·p0.9999: 23.530 ms/op
                 createUser·p1.00:   24.379 ms/op

Iteration   2: 3.574 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.971 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   4.121 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   5.939 ms/op
                 createUser·p0.999:  12.755 ms/op
                 createUser·p0.9999: 24.742 ms/op
                 createUser·p1.00:   26.444 ms/op

Iteration   3: 3.594 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.212 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   4.129 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  18.678 ms/op
                 createUser·p0.9999: 26.818 ms/op
                 createUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 267753
  mean =      3.583 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2221 
    [ 2.500,  5.000) = 259288 
    [ 5.000,  7.500) = 4905 
    [ 7.500, 10.000) = 582 
    [10.000, 12.500) = 381 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.971 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     17.539 ms/op
     p(99.9900) =     26.149 ms/op
     p(99.9990) =     28.081 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


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
# Warmup Iteration   1: 8.100 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.591 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.429 ±(99.9%) 0.008 ms/op
Iteration   1: 3.441 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.579 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   3.826 ms/op
                 existUser·p0.95:   4.182 ms/op
                 existUser·p0.99:   5.773 ms/op
                 existUser·p0.999:  20.181 ms/op
                 existUser·p0.9999: 22.525 ms/op
                 existUser·p1.00:   23.331 ms/op

Iteration   2: 3.422 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.352 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.830 ms/op
                 existUser·p0.95:   4.149 ms/op
                 existUser·p0.99:   6.398 ms/op
                 existUser·p0.999:  16.843 ms/op
                 existUser·p0.9999: 24.869 ms/op
                 existUser·p1.00:   26.051 ms/op

Iteration   3: 3.375 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.567 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.039 ms/op
                 existUser·p0.99:   6.570 ms/op
                 existUser·p0.999:  21.183 ms/op
                 existUser·p0.9999: 30.475 ms/op
                 existUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281378
  mean =      3.412 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3498 
    [ 2.500,  5.000) = 272917 
    [ 5.000,  7.500) = 3728 
    [ 7.500, 10.000) = 543 
    [10.000, 12.500) = 291 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.352 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      6.128 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     27.296 ms/op
     p(99.9990) =     31.140 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


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
# Warmup Iteration   1: 9.428 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.735 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.578 ±(99.9%) 0.010 ms/op
Iteration   1: 3.647 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.438 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   5.554 ms/op
                 getUser·p0.99:   7.520 ms/op
                 getUser·p0.999:  20.611 ms/op
                 getUser·p0.9999: 23.731 ms/op
                 getUser·p1.00:   24.379 ms/op

Iteration   2: 3.475 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.589 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.129 ms/op
                 getUser·p0.99:   6.070 ms/op
                 getUser·p0.999:  21.791 ms/op
                 getUser·p0.9999: 25.094 ms/op
                 getUser·p1.00:   26.247 ms/op

Iteration   3: 3.496 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.145 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   5.972 ms/op
                 getUser·p0.999:  20.072 ms/op
                 getUser·p0.9999: 24.407 ms/op
                 getUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271243
  mean =      3.538 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2488 
    [ 2.500,  5.000) = 259697 
    [ 5.000,  7.500) = 7241 
    [ 7.500, 10.000) = 1093 
    [10.000, 12.500) = 293 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 145 
    [22.500, 25.000) = 122 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     20.480 ms/op
     p(99.9900) =     24.379 ms/op
     p(99.9990) =     25.494 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


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
# Warmup Iteration   1: 10.578 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.497 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.244 ±(99.9%) 0.013 ms/op
Iteration   1: 4.222 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.567 ms/op
                 listUser·p0.50:   4.129 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  17.772 ms/op
                 listUser·p0.9999: 20.310 ms/op
                 listUser·p1.00:   21.201 ms/op

Iteration   2: 4.141 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.400 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   7.651 ms/op
                 listUser·p0.999:  14.696 ms/op
                 listUser·p0.9999: 19.104 ms/op
                 listUser·p1.00:   19.464 ms/op

Iteration   3: 4.068 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.372 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   7.145 ms/op
                 listUser·p0.999:  14.720 ms/op
                 listUser·p0.9999: 19.890 ms/op
                 listUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 231808
  mean =      4.143 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 223907 
    [ 5.000,  7.500) = 5804 
    [ 7.500, 10.000) = 1237 
    [10.000, 12.500) = 256 
    [12.500, 15.000) = 322 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.567 ms/op
     p(50.0000) =      4.018 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     15.204 ms/op
     p(99.9900) =     19.890 ms/op
     p(99.9990) =     21.018 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.056 ± 0.845  ops/ms
ClientPb.existUser                       thrpt       3   9.640 ± 2.518  ops/ms
ClientPb.getUser                         thrpt       3   9.086 ± 3.999  ops/ms
ClientPb.listUser                        thrpt       3   7.410 ± 2.253  ops/ms
ClientPb.createUser                       avgt       3   3.583 ± 2.638   ms/op
ClientPb.existUser                        avgt       3   3.359 ± 0.502   ms/op
ClientPb.getUser                          avgt       3   3.527 ± 0.798   ms/op
ClientPb.listUser                         avgt       3   4.170 ± 0.602   ms/op
ClientPb.createUser                     sample  267753   3.583 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.971           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.432           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.141           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.440           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.078           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.539           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.149           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.213           ms/op
ClientPb.existUser                      sample  281378   3.412 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.352           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.277           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.801           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.129           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.128           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.876           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.296           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.752           ms/op
ClientPb.getUser                        sample  271243   3.538 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.145           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.387           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.227           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.152           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.480           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.379           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.247           ms/op
ClientPb.listUser                       sample  231808   4.143 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.567           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.018           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.743           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.348           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.204           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.890           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.201           ms/op
