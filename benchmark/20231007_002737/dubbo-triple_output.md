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
# Warmup Iteration   1: 2.024 ops/ms
# Warmup Iteration   2: 5.180 ops/ms
# Warmup Iteration   3: 8.249 ops/ms
Iteration   1: 8.545 ops/ms
Iteration   2: 8.781 ops/ms
Iteration   3: 9.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.790 ±(99.9%) 4.560 ops/ms [Average]
  (min, avg, max) = (8.545, 8.790, 9.044), stdev = 0.250
  CI (99.9%): [4.230, 13.350] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.743 ops/ms
# Warmup Iteration   2: 8.575 ops/ms
# Warmup Iteration   3: 9.305 ops/ms
Iteration   1: 9.472 ops/ms
Iteration   2: 9.781 ops/ms
Iteration   3: 9.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.662 ±(99.9%) 3.030 ops/ms [Average]
  (min, avg, max) = (9.472, 9.662, 9.781), stdev = 0.166
  CI (99.9%): [6.632, 12.692] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.859 ops/ms
# Warmup Iteration   2: 8.521 ops/ms
# Warmup Iteration   3: 8.880 ops/ms
Iteration   1: 9.070 ops/ms
Iteration   2: 9.208 ops/ms
Iteration   3: 9.146 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.141 ±(99.9%) 1.257 ops/ms [Average]
  (min, avg, max) = (9.070, 9.141, 9.208), stdev = 0.069
  CI (99.9%): [7.884, 10.398] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.693 ops/ms
# Warmup Iteration   2: 7.267 ops/ms
# Warmup Iteration   3: 7.698 ops/ms
Iteration   1: 7.777 ops/ms
Iteration   2: 7.603 ops/ms
Iteration   3: 7.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.695 ±(99.9%) 1.591 ops/ms [Average]
  (min, avg, max) = (7.603, 7.695, 7.777), stdev = 0.087
  CI (99.9%): [6.104, 9.286] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 9.620 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 3.722 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.535 ±(99.9%) 0.004 ms/op
Iteration   1: 3.644 ±(99.9%) 0.003 ms/op
Iteration   2: 3.565 ±(99.9%) 0.005 ms/op
Iteration   3: 3.493 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.567 ±(99.9%) 1.373 ms/op [Average]
  (min, avg, max) = (3.493, 3.567, 3.644), stdev = 0.075
  CI (99.9%): [2.194, 4.941] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.193 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.475 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.537 ±(99.9%) 0.002 ms/op
Iteration   1: 3.416 ±(99.9%) 0.005 ms/op
Iteration   2: 3.409 ±(99.9%) 0.008 ms/op
Iteration   3: 3.450 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.425 ±(99.9%) 0.399 ms/op [Average]
  (min, avg, max) = (3.409, 3.425, 3.450), stdev = 0.022
  CI (99.9%): [3.027, 3.824] (assumes normal distribution)


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
# Warmup Iteration   1: 8.619 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.672 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.573 ±(99.9%) 0.002 ms/op
Iteration   1: 3.602 ±(99.9%) 0.005 ms/op
Iteration   2: 3.467 ±(99.9%) 0.006 ms/op
Iteration   3: 3.537 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.535 ±(99.9%) 1.227 ms/op [Average]
  (min, avg, max) = (3.467, 3.535, 3.602), stdev = 0.067
  CI (99.9%): [2.308, 4.762] (assumes normal distribution)


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
# Warmup Iteration   1: 10.949 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.283 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.131 ±(99.9%) 0.007 ms/op
Iteration   1: 4.113 ±(99.9%) 0.006 ms/op
Iteration   2: 4.125 ±(99.9%) 0.007 ms/op
Iteration   3: 4.126 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.122 ±(99.9%) 0.132 ms/op [Average]
  (min, avg, max) = (4.113, 4.122, 4.126), stdev = 0.007
  CI (99.9%): [3.990, 4.253] (assumes normal distribution)


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
# Warmup Iteration   1: 9.332 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 3.946 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.510 ±(99.9%) 0.011 ms/op
Iteration   1: 3.517 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.296 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   7.086 ms/op
                 createUser·p0.999:  21.138 ms/op
                 createUser·p0.9999: 36.504 ms/op
                 createUser·p1.00:   37.028 ms/op

Iteration   2: 3.530 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.432 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.022 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   6.636 ms/op
                 createUser·p0.999:  21.758 ms/op
                 createUser·p0.9999: 25.623 ms/op
                 createUser·p1.00:   26.280 ms/op

Iteration   3: 3.558 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.341 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   7.340 ms/op
                 createUser·p0.999:  17.925 ms/op
                 createUser·p0.9999: 25.526 ms/op
                 createUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271482
  mean =      3.535 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5496 
    [ 2.500,  5.000) = 258121 
    [ 5.000,  7.500) = 5944 
    [ 7.500, 10.000) = 1179 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 230 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 124 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.296 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     20.958 ms/op
     p(99.9900) =     35.183 ms/op
     p(99.9990) =     36.756 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


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
# Warmup Iteration   1: 8.623 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.678 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.422 ±(99.9%) 0.010 ms/op
Iteration   1: 3.365 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.742 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   4.018 ms/op
                 existUser·p0.99:   6.308 ms/op
                 existUser·p0.999:  12.409 ms/op
                 existUser·p0.9999: 20.627 ms/op
                 existUser·p1.00:   21.398 ms/op

Iteration   2: 3.462 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.877 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   3.858 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   6.832 ms/op
                 existUser·p0.999:  20.840 ms/op
                 existUser·p0.9999: 31.761 ms/op
                 existUser·p1.00:   37.945 ms/op

Iteration   3: 3.369 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.292 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   4.149 ms/op
                 existUser·p0.99:   6.922 ms/op
                 existUser·p0.999:  19.366 ms/op
                 existUser·p0.9999: 25.379 ms/op
                 existUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282557
  mean =      3.398 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9938 
    [ 2.500,  5.000) = 265381 
    [ 5.000,  7.500) = 5907 
    [ 7.500, 10.000) = 831 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 143 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.742 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      6.545 ms/op
     p(99.9000) =     19.137 ms/op
     p(99.9900) =     27.895 ms/op
     p(99.9990) =     37.760 ms/op
     p(99.9999) =     37.945 ms/op
    p(100.0000) =     37.945 ms/op


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
# Warmup Iteration   1: 10.200 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.747 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.550 ±(99.9%) 0.010 ms/op
Iteration   1: 3.476 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.499 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   7.266 ms/op
                 getUser·p0.999:  20.055 ms/op
                 getUser·p0.9999: 22.873 ms/op
                 getUser·p1.00:   23.790 ms/op

Iteration   2: 3.525 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.364 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   6.939 ms/op
                 getUser·p0.999:  21.908 ms/op
                 getUser·p0.9999: 24.934 ms/op
                 getUser·p1.00:   27.197 ms/op

Iteration   3: 3.454 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.161 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   6.463 ms/op
                 getUser·p0.999:  18.776 ms/op
                 getUser·p0.9999: 26.229 ms/op
                 getUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275390
  mean =      3.485 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3927 
    [ 2.500,  5.000) = 262986 
    [ 5.000,  7.500) = 6867 
    [ 7.500, 10.000) = 990 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     19.169 ms/op
     p(99.9900) =     25.655 ms/op
     p(99.9990) =     27.310 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


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
# Warmup Iteration   1: 11.673 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.568 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.121 ±(99.9%) 0.012 ms/op
Iteration   1: 4.160 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.405 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   7.954 ms/op
                 listUser·p0.999:  18.034 ms/op
                 listUser·p0.9999: 22.302 ms/op
                 listUser·p1.00:   23.396 ms/op

Iteration   2: 4.168 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.905 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   7.717 ms/op
                 listUser·p0.999:  14.778 ms/op
                 listUser·p0.9999: 28.093 ms/op
                 listUser·p1.00:   28.639 ms/op

Iteration   3: 4.129 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.829 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   7.594 ms/op
                 listUser·p0.999:  14.631 ms/op
                 listUser·p0.9999: 16.354 ms/op
                 listUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 231225
  mean =      4.152 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 220229 
    [ 5.000,  7.500) = 7901 
    [ 7.500, 10.000) = 2176 
    [10.000, 12.500) = 196 
    [12.500, 15.000) = 348 
    [15.000, 17.500) = 199 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.405 ms/op
     p(50.0000) =      4.006 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      7.766 ms/op
     p(99.9000) =     15.725 ms/op
     p(99.9900) =     22.573 ms/op
     p(99.9990) =     28.566 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.790 ± 4.560  ops/ms
ClientPb.existUser                       thrpt       3   9.662 ± 3.030  ops/ms
ClientPb.getUser                         thrpt       3   9.141 ± 1.257  ops/ms
ClientPb.listUser                        thrpt       3   7.695 ± 1.591  ops/ms
ClientPb.createUser                       avgt       3   3.567 ± 1.373   ms/op
ClientPb.existUser                        avgt       3   3.425 ± 0.399   ms/op
ClientPb.getUser                          avgt       3   3.535 ± 1.227   ms/op
ClientPb.listUser                         avgt       3   4.122 ± 0.132   ms/op
ClientPb.createUser                     sample  271482   3.535 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.296           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.404           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.973           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.293           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.086           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.958           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.183           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.028           ms/op
ClientPb.existUser                      sample  282557   3.398 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.742           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.301           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.545           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.137           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.895           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.945           ms/op
ClientPb.getUser                        sample  275390   3.485 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.161           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.334           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.227           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.816           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.169           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.655           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.115           ms/op
ClientPb.listUser                       sample  231225   4.152 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.405           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.006           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.940           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.766           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.725           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.573           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.639           ms/op
