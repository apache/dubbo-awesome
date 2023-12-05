# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.185 ops/ms
# Warmup Iteration   2: 12.326 ops/ms
# Warmup Iteration   3: 12.462 ops/ms
Iteration   1: 12.632 ops/ms
Iteration   2: 12.630 ops/ms
Iteration   3: 12.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.608 ±(99.9%) 0.718 ops/ms [Average]
  (min, avg, max) = (12.563, 12.608, 12.632), stdev = 0.039
  CI (99.9%): [11.890, 13.327] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.189 ops/ms
# Warmup Iteration   2: 12.969 ops/ms
# Warmup Iteration   3: 13.108 ops/ms
Iteration   1: 13.052 ops/ms
Iteration   2: 13.117 ops/ms
Iteration   3: 13.038 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.069 ±(99.9%) 0.769 ops/ms [Average]
  (min, avg, max) = (13.038, 13.069, 13.117), stdev = 0.042
  CI (99.9%): [12.300, 13.838] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.160 ops/ms
# Warmup Iteration   2: 12.500 ops/ms
# Warmup Iteration   3: 12.736 ops/ms
Iteration   1: 12.673 ops/ms
Iteration   2: 12.771 ops/ms
Iteration   3: 12.647 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.697 ±(99.9%) 1.194 ops/ms [Average]
  (min, avg, max) = (12.647, 12.697, 12.771), stdev = 0.065
  CI (99.9%): [11.503, 13.891] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.584 ops/ms
# Warmup Iteration   2: 10.278 ops/ms
# Warmup Iteration   3: 10.469 ops/ms
Iteration   1: 10.421 ops/ms
Iteration   2: 10.446 ops/ms
Iteration   3: 10.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.468 ±(99.9%) 1.112 ops/ms [Average]
  (min, avg, max) = (10.421, 10.468, 10.537), stdev = 0.061
  CI (99.9%): [9.356, 11.581] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.197 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.636 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.571 ±(99.9%) 0.003 ms/op
Iteration   1: 2.610 ±(99.9%) 0.004 ms/op
Iteration   2: 2.580 ±(99.9%) 0.004 ms/op
Iteration   3: 2.569 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.586 ±(99.9%) 0.390 ms/op [Average]
  (min, avg, max) = (2.569, 2.586, 2.610), stdev = 0.021
  CI (99.9%): [2.196, 2.976] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.709 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.475 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.003 ms/op
Iteration   1: 2.479 ±(99.9%) 0.004 ms/op
Iteration   2: 2.470 ±(99.9%) 0.004 ms/op
Iteration   3: 2.466 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.472 ±(99.9%) 0.122 ms/op [Average]
  (min, avg, max) = (2.466, 2.472, 2.479), stdev = 0.007
  CI (99.9%): [2.350, 2.593] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.887 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.576 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.545 ±(99.9%) 0.003 ms/op
Iteration   1: 2.547 ±(99.9%) 0.004 ms/op
Iteration   2: 2.498 ±(99.9%) 0.004 ms/op
Iteration   3: 2.510 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.518 ±(99.9%) 0.464 ms/op [Average]
  (min, avg, max) = (2.498, 2.518, 2.547), stdev = 0.025
  CI (99.9%): [2.054, 2.983] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.701 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.085 ±(99.9%) 0.004 ms/op
Iteration   1: 3.029 ±(99.9%) 0.005 ms/op
Iteration   2: 3.064 ±(99.9%) 0.005 ms/op
Iteration   3: 3.069 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.054 ±(99.9%) 0.401 ms/op [Average]
  (min, avg, max) = (3.029, 3.054, 3.069), stdev = 0.022
  CI (99.9%): [2.653, 3.454] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.188 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.674 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.006 ms/op
Iteration   1: 2.559 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.026 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   3.856 ms/op
                 createUser·p0.999:  11.879 ms/op
                 createUser·p0.9999: 13.918 ms/op
                 createUser·p1.00:   14.516 ms/op

Iteration   2: 2.534 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.786 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.690 ms/op
                 createUser·p0.999:  9.500 ms/op
                 createUser·p0.9999: 12.671 ms/op
                 createUser·p1.00:   13.009 ms/op

Iteration   3: 2.577 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.758 ms/op
                 createUser·p0.50:   2.662 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.289 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  9.208 ms/op
                 createUser·p0.9999: 10.928 ms/op
                 createUser·p1.00:   11.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375176
  mean =      2.556 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 178461 
    [ 2.500,  3.750) = 191314 
    [ 3.750,  5.000) = 4337 
    [ 5.000,  6.250) = 470 
    [ 6.250,  7.500) = 83 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 119 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      3.973 ms/op
     p(99.9000) =      9.254 ms/op
     p(99.9900) =     13.263 ms/op
     p(99.9990) =     14.414 ms/op
     p(99.9999) =     14.516 ms/op
    p(100.0000) =     14.516 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.817 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.507 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.005 ms/op
Iteration   1: 2.490 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.956 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.588 ms/op
                 existUser·p0.999:  11.698 ms/op
                 existUser·p0.9999: 13.536 ms/op
                 existUser·p1.00:   14.483 ms/op

Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.843 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.842 ms/op
                 existUser·p0.999:  6.069 ms/op
                 existUser·p0.9999: 12.501 ms/op
                 existUser·p1.00:   13.599 ms/op

Iteration   3: 2.468 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.980 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.658 ms/op
                 existUser·p0.999:  8.462 ms/op
                 existUser·p0.9999: 12.599 ms/op
                 existUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387044
  mean =      2.478 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 189478 
    [ 2.500,  3.750) = 193959 
    [ 3.750,  5.000) = 2563 
    [ 5.000,  6.250) = 530 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 132 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.690 ms/op
     p(99.9000) =      8.486 ms/op
     p(99.9900) =     13.091 ms/op
     p(99.9990) =     13.902 ms/op
     p(99.9999) =     14.483 ms/op
    p(100.0000) =     14.483 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.879 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.552 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.006 ms/op
Iteration   1: 2.468 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.902 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.707 ms/op
                 getUser·p0.999:  6.454 ms/op
                 getUser·p0.9999: 14.303 ms/op
                 getUser·p1.00:   15.155 ms/op

Iteration   2: 2.492 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.815 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.051 ms/op
                 getUser·p0.999:  7.992 ms/op
                 getUser·p0.9999: 17.170 ms/op
                 getUser·p1.00:   17.596 ms/op

Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.716 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.850 ms/op
                 getUser·p0.999:  5.464 ms/op
                 getUser·p0.9999: 12.153 ms/op
                 getUser·p1.00:   13.058 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386984
  mean =      2.479 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 115 
    [ 1.250,  2.500) = 193322 
    [ 2.500,  3.750) = 188695 
    [ 3.750,  5.000) = 3910 
    [ 5.000,  6.250) = 571 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.716 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.879 ms/op
     p(99.9000) =      5.915 ms/op
     p(99.9900) =     14.493 ms/op
     p(99.9990) =     17.314 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.581 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.008 ms/op
Iteration   1: 3.009 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.744 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.792 ms/op
                 listUser·p0.999:  8.695 ms/op
                 listUser·p0.9999: 10.324 ms/op
                 listUser·p1.00:   10.617 ms/op

Iteration   2: 2.987 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.766 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.503 ms/op
                 listUser·p0.999:  9.568 ms/op
                 listUser·p0.9999: 13.733 ms/op
                 listUser·p1.00:   15.417 ms/op

Iteration   3: 2.982 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.673 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  9.352 ms/op
                 listUser·p0.9999: 10.453 ms/op
                 listUser·p1.00:   10.666 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320520
  mean =      2.993 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 175 
    [ 1.250,  2.500) = 97573 
    [ 2.500,  3.750) = 183380 
    [ 3.750,  5.000) = 31909 
    [ 5.000,  6.250) = 6125 
    [ 6.250,  7.500) = 682 
    [ 7.500,  8.750) = 213 
    [ 8.750, 10.000) = 318 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.355 ms/op
     p(99.9900) =     11.827 ms/op
     p(99.9990) =     14.493 ms/op
     p(99.9999) =     15.417 ms/op
    p(100.0000) =     15.417 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.608 ± 0.718  ops/ms
ClientPb.existUser                       thrpt       3  13.069 ± 0.769  ops/ms
ClientPb.getUser                         thrpt       3  12.697 ± 1.194  ops/ms
ClientPb.listUser                        thrpt       3  10.468 ± 1.112  ops/ms
ClientPb.createUser                       avgt       3   2.586 ± 0.390   ms/op
ClientPb.existUser                        avgt       3   2.472 ± 0.122   ms/op
ClientPb.getUser                          avgt       3   2.518 ± 0.464   ms/op
ClientPb.listUser                         avgt       3   3.054 ± 0.401   ms/op
ClientPb.createUser                     sample  375176   2.556 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.758           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.240           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.973           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.254           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.263           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.516           ms/op
ClientPb.existUser                      sample  387044   2.478 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.843           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.548           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.690           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.486           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.091           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.483           ms/op
ClientPb.getUser                        sample  386984   2.479 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.716           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.879           ms/op
ClientPb.getUser:getUser·p0.999         sample           5.915           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.493           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.596           ms/op
ClientPb.listUser                       sample  320520   2.993 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.673           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.925           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.355           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.827           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.417           ms/op
