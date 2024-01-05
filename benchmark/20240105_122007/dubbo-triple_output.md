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
# Warmup Iteration   1: 4.515 ops/ms
# Warmup Iteration   2: 11.987 ops/ms
# Warmup Iteration   3: 12.268 ops/ms
Iteration   1: 12.547 ops/ms
Iteration   2: 12.581 ops/ms
Iteration   3: 12.564 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.564 ±(99.9%) 0.311 ops/ms [Average]
  (min, avg, max) = (12.547, 12.564, 12.581), stdev = 0.017
  CI (99.9%): [12.253, 12.875] (assumes normal distribution)


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
# Warmup Iteration   1: 8.293 ops/ms
# Warmup Iteration   2: 12.913 ops/ms
# Warmup Iteration   3: 13.075 ops/ms
Iteration   1: 12.922 ops/ms
Iteration   2: 12.998 ops/ms
Iteration   3: 12.950 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.957 ±(99.9%) 0.707 ops/ms [Average]
  (min, avg, max) = (12.922, 12.957, 12.998), stdev = 0.039
  CI (99.9%): [12.249, 13.664] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.808 ops/ms
# Warmup Iteration   2: 12.610 ops/ms
# Warmup Iteration   3: 12.586 ops/ms
Iteration   1: 12.700 ops/ms
Iteration   2: 12.796 ops/ms
Iteration   3: 12.666 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.721 ±(99.9%) 1.229 ops/ms [Average]
  (min, avg, max) = (12.666, 12.721, 12.796), stdev = 0.067
  CI (99.9%): [11.491, 13.950] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.668 ops/ms
# Warmup Iteration   2: 10.585 ops/ms
# Warmup Iteration   3: 10.736 ops/ms
Iteration   1: 10.819 ops/ms
Iteration   2: 10.746 ops/ms
Iteration   3: 10.750 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.772 ±(99.9%) 0.749 ops/ms [Average]
  (min, avg, max) = (10.746, 10.772, 10.819), stdev = 0.041
  CI (99.9%): [10.023, 11.521] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.036 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.551 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.003 ms/op
Iteration   1: 2.526 ±(99.9%) 0.004 ms/op
Iteration   2: 2.480 ±(99.9%) 0.003 ms/op
Iteration   3: 2.495 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.500 ±(99.9%) 0.426 ms/op [Average]
  (min, avg, max) = (2.480, 2.500, 2.526), stdev = 0.023
  CI (99.9%): [2.074, 2.926] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.692 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.489 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.464 ±(99.9%) 0.004 ms/op
Iteration   1: 2.444 ±(99.9%) 0.005 ms/op
Iteration   2: 2.454 ±(99.9%) 0.004 ms/op
Iteration   3: 2.452 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.450 ±(99.9%) 0.103 ms/op [Average]
  (min, avg, max) = (2.444, 2.450, 2.454), stdev = 0.006
  CI (99.9%): [2.347, 2.553] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.130 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.555 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.005 ms/op
Iteration   1: 2.490 ±(99.9%) 0.003 ms/op
Iteration   2: 2.497 ±(99.9%) 0.004 ms/op
Iteration   3: 2.501 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.496 ±(99.9%) 0.096 ms/op [Average]
  (min, avg, max) = (2.490, 2.496, 2.501), stdev = 0.005
  CI (99.9%): [2.400, 2.592] (assumes normal distribution)


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
# Warmup Iteration   1: 4.708 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.036 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.005 ms/op
Iteration   1: 3.027 ±(99.9%) 0.007 ms/op
Iteration   2: 3.033 ±(99.9%) 0.006 ms/op
Iteration   3: 3.004 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.021 ±(99.9%) 0.281 ms/op [Average]
  (min, avg, max) = (3.004, 3.021, 3.033), stdev = 0.015
  CI (99.9%): [2.740, 3.303] (assumes normal distribution)


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
# Warmup Iteration   1: 4.118 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.636 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.006 ms/op
Iteration   1: 2.493 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.805 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.727 ms/op
                 createUser·p0.999:  9.557 ms/op
                 createUser·p0.9999: 14.093 ms/op
                 createUser·p1.00:   14.402 ms/op

Iteration   2: 2.534 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.759 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.850 ms/op
                 createUser·p0.999:  9.006 ms/op
                 createUser·p0.9999: 13.929 ms/op
                 createUser·p1.00:   15.598 ms/op

Iteration   3: 2.521 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.904 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.805 ms/op
                 createUser·p0.999:  8.233 ms/op
                 createUser·p0.9999: 10.278 ms/op
                 createUser·p1.00:   11.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381196
  mean =      2.516 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 185042 
    [ 2.500,  3.750) = 191979 
    [ 3.750,  5.000) = 3283 
    [ 5.000,  6.250) = 308 
    [ 6.250,  7.500) = 114 
    [ 7.500,  8.750) = 70 
    [ 8.750, 10.000) = 117 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.759 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.793 ms/op
     p(99.9000) =      8.471 ms/op
     p(99.9900) =     13.793 ms/op
     p(99.9990) =     15.424 ms/op
     p(99.9999) =     15.598 ms/op
    p(100.0000) =     15.598 ms/op


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
# Warmup Iteration   1: 3.799 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.464 ±(99.9%) 0.005 ms/op
Iteration   1: 2.466 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.478 ms/op
                 existUser·p0.999:  5.983 ms/op
                 existUser·p0.9999: 14.567 ms/op
                 existUser·p1.00:   15.466 ms/op

Iteration   2: 2.454 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.820 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.432 ms/op
                 existUser·p0.999:  6.316 ms/op
                 existUser·p0.9999: 12.205 ms/op
                 existUser·p1.00:   13.484 ms/op

Iteration   3: 2.479 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.754 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.785 ms/op
                 existUser·p0.999:  7.434 ms/op
                 existUser·p0.9999: 15.172 ms/op
                 existUser·p1.00:   15.794 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388919
  mean =      2.466 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 193647 
    [ 2.500,  3.750) = 192472 
    [ 3.750,  5.000) = 2132 
    [ 5.000,  6.250) = 245 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.551 ms/op
     p(99.9000) =      6.451 ms/op
     p(99.9900) =     14.503 ms/op
     p(99.9990) =     15.599 ms/op
     p(99.9999) =     15.794 ms/op
    p(100.0000) =     15.794 ms/op


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
# Warmup Iteration   1: 3.941 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.535 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
Iteration   1: 2.516 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.866 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   4.751 ms/op
                 getUser·p0.999:  11.434 ms/op
                 getUser·p0.9999: 13.194 ms/op
                 getUser·p1.00:   13.812 ms/op

Iteration   2: 2.470 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.014 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.518 ms/op
                 getUser·p0.999:  6.167 ms/op
                 getUser·p0.9999: 12.370 ms/op
                 getUser·p1.00:   12.943 ms/op

Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.838 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.719 ms/op
                 getUser·p0.999:  6.938 ms/op
                 getUser·p0.9999: 10.813 ms/op
                 getUser·p1.00:   11.731 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385523
  mean =      2.488 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 192778 
    [ 2.500,  3.750) = 188147 
    [ 3.750,  5.000) = 3292 
    [ 5.000,  6.250) = 814 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 142 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.890 ms/op
     p(99.9000) =      6.865 ms/op
     p(99.9900) =     12.836 ms/op
     p(99.9990) =     13.435 ms/op
     p(99.9999) =     13.812 ms/op
    p(100.0000) =     13.812 ms/op


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
# Warmup Iteration   1: 4.574 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.008 ms/op
Iteration   1: 2.979 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.725 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.372 ms/op
                 listUser·p0.9999: 15.335 ms/op
                 listUser·p1.00:   16.089 ms/op

Iteration   2: 2.989 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.878 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.814 ms/op
                 listUser·p0.9999: 11.446 ms/op
                 listUser·p1.00:   12.730 ms/op

Iteration   3: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.840 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  9.205 ms/op
                 listUser·p0.9999: 11.849 ms/op
                 listUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320337
  mean =      2.994 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 96 
    [ 1.250,  2.500) = 95955 
    [ 2.500,  3.750) = 186384 
    [ 3.750,  5.000) = 30647 
    [ 5.000,  6.250) = 6015 
    [ 6.250,  7.500) = 609 
    [ 7.500,  8.750) = 201 
    [ 8.750, 10.000) = 216 
    [10.000, 11.250) = 132 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      9.448 ms/op
     p(99.9900) =     14.282 ms/op
     p(99.9990) =     15.594 ms/op
     p(99.9999) =     16.089 ms/op
    p(100.0000) =     16.089 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.564 ± 0.311  ops/ms
ClientPb.existUser                       thrpt       3  12.957 ± 0.707  ops/ms
ClientPb.getUser                         thrpt       3  12.721 ± 1.229  ops/ms
ClientPb.listUser                        thrpt       3  10.772 ± 0.749  ops/ms
ClientPb.createUser                       avgt       3   2.500 ± 0.426   ms/op
ClientPb.existUser                        avgt       3   2.450 ± 0.103   ms/op
ClientPb.getUser                          avgt       3   2.496 ± 0.096   ms/op
ClientPb.listUser                         avgt       3   3.021 ± 0.281   ms/op
ClientPb.createUser                     sample  381196   2.516 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.759           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.471           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.793           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.598           ms/op
ClientPb.existUser                      sample  388919   2.466 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.754           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.551           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.451           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.503           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.794           ms/op
ClientPb.getUser                        sample  385523   2.488 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.838           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.499           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.023           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.890           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.865           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.836           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.812           ms/op
ClientPb.listUser                       sample  320337   2.994 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.725           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.448           ms/op
ClientPb.listUser:listUser·p0.9999      sample          14.282           ms/op
ClientPb.listUser:listUser·p1.00        sample          16.089           ms/op
