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
# Warmup Iteration   1: 4.182 ops/ms
# Warmup Iteration   2: 11.842 ops/ms
# Warmup Iteration   3: 12.089 ops/ms
Iteration   1: 12.273 ops/ms
Iteration   2: 12.375 ops/ms
Iteration   3: 12.359 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.336 ±(99.9%) 0.992 ops/ms [Average]
  (min, avg, max) = (12.273, 12.336, 12.375), stdev = 0.054
  CI (99.9%): [11.344, 13.327] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:54
# Fork: 1 of 1
# Warmup Iteration   1: 8.008 ops/ms
# Warmup Iteration   2: 12.920 ops/ms
# Warmup Iteration   3: 12.951 ops/ms
Iteration   1: 12.906 ops/ms
Iteration   2: 13.180 ops/ms
Iteration   3: 12.894 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.993 ±(99.9%) 2.951 ops/ms [Average]
  (min, avg, max) = (12.894, 12.993, 13.180), stdev = 0.162
  CI (99.9%): [10.042, 15.944] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.245 ops/ms
# Warmup Iteration   2: 12.439 ops/ms
# Warmup Iteration   3: 12.553 ops/ms
Iteration   1: 12.547 ops/ms
Iteration   2: 12.701 ops/ms
Iteration   3: 12.802 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.683 ±(99.9%) 2.347 ops/ms [Average]
  (min, avg, max) = (12.547, 12.683, 12.802), stdev = 0.129
  CI (99.9%): [10.337, 15.030] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.688 ops/ms
# Warmup Iteration   2: 10.103 ops/ms
# Warmup Iteration   3: 10.373 ops/ms
Iteration   1: 10.595 ops/ms
Iteration   2: 10.439 ops/ms
Iteration   3: 10.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.553 ±(99.9%) 1.828 ops/ms [Average]
  (min, avg, max) = (10.439, 10.553, 10.626), stdev = 0.100
  CI (99.9%): [8.725, 12.381] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.201 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.637 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.592 ±(99.9%) 0.004 ms/op
Iteration   1: 2.574 ±(99.9%) 0.005 ms/op
Iteration   2: 2.602 ±(99.9%) 0.004 ms/op
Iteration   3: 2.537 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.571 ±(99.9%) 0.593 ms/op [Average]
  (min, avg, max) = (2.537, 2.571, 2.602), stdev = 0.032
  CI (99.9%): [1.978, 3.164] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.991 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.559 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.004 ms/op
Iteration   1: 2.471 ±(99.9%) 0.004 ms/op
Iteration   2: 2.470 ±(99.9%) 0.004 ms/op
Iteration   3: 2.467 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.469 ±(99.9%) 0.033 ms/op [Average]
  (min, avg, max) = (2.467, 2.469, 2.471), stdev = 0.002
  CI (99.9%): [2.437, 2.502] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.720 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.574 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.003 ms/op
Iteration   1: 2.508 ±(99.9%) 0.004 ms/op
Iteration   2: 2.509 ±(99.9%) 0.003 ms/op
Iteration   3: 2.495 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.504 ±(99.9%) 0.140 ms/op [Average]
  (min, avg, max) = (2.495, 2.504, 2.509), stdev = 0.008
  CI (99.9%): [2.364, 2.644] (assumes normal distribution)


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
# Warmup Iteration   1: 4.936 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.005 ms/op
Iteration   1: 3.033 ±(99.9%) 0.007 ms/op
Iteration   2: 3.029 ±(99.9%) 0.005 ms/op
Iteration   3: 3.018 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.026 ±(99.9%) 0.142 ms/op [Average]
  (min, avg, max) = (3.018, 3.026, 3.033), stdev = 0.008
  CI (99.9%): [2.885, 3.168] (assumes normal distribution)


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
# Warmup Iteration   1: 4.471 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.678 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.589 ±(99.9%) 0.006 ms/op
Iteration   1: 2.544 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.663 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.703 ms/op
                 createUser·p0.999:  12.403 ms/op
                 createUser·p0.9999: 20.509 ms/op
                 createUser·p1.00:   21.103 ms/op

Iteration   2: 2.553 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.954 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   3.146 ms/op
                 createUser·p0.95:   3.326 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  10.682 ms/op
                 createUser·p0.9999: 15.671 ms/op
                 createUser·p1.00:   18.645 ms/op

Iteration   3: 2.546 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.800 ms/op
                 createUser·p0.50:   2.503 ms/op
                 createUser·p0.90:   3.187 ms/op
                 createUser·p0.95:   3.396 ms/op
                 createUser·p0.99:   4.153 ms/op
                 createUser·p0.999:  8.700 ms/op
                 createUser·p0.9999: 11.283 ms/op
                 createUser·p1.00:   11.813 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376450
  mean =      2.548 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 184353 
    [ 2.500,  5.000) = 190775 
    [ 5.000,  7.500) = 820 
    [ 7.500, 10.000) = 119 
    [10.000, 12.500) = 242 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.133 ms/op
     p(95.0000) =      3.301 ms/op
     p(99.0000) =      4.092 ms/op
     p(99.9000) =     10.167 ms/op
     p(99.9900) =     15.943 ms/op
     p(99.9990) =     20.896 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


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
# Warmup Iteration   1: 4.142 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.514 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
Iteration   1: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.919 ms/op
                 existUser·p0.50:   2.441 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.760 ms/op
                 existUser·p0.999:  6.090 ms/op
                 existUser·p0.9999: 14.599 ms/op
                 existUser·p1.00:   14.942 ms/op

Iteration   2: 2.422 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.854 ms/op
                 existUser·p0.50:   2.363 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.801 ms/op
                 existUser·p0.999:  6.307 ms/op
                 existUser·p0.9999: 16.525 ms/op
                 existUser·p1.00:   17.039 ms/op

Iteration   3: 2.496 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.998 ms/op
                 existUser·p0.50:   2.445 ms/op
                 existUser·p0.90:   3.084 ms/op
                 existUser·p0.95:   3.310 ms/op
                 existUser·p0.99:   4.588 ms/op
                 existUser·p0.999:  8.878 ms/op
                 existUser·p0.9999: 16.374 ms/op
                 existUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389911
  mean =      2.460 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 87 
    [ 1.250,  2.500) = 207545 
    [ 2.500,  3.750) = 176629 
    [ 3.750,  5.000) = 4225 
    [ 5.000,  6.250) = 967 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 38 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      2.413 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      4.014 ms/op
     p(99.9000) =      7.522 ms/op
     p(99.9900) =     16.237 ms/op
     p(99.9990) =     17.072 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


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
# Warmup Iteration   1: 4.020 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.595 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.555 ±(99.9%) 0.006 ms/op
Iteration   1: 2.565 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.476 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.142 ms/op
                 getUser·p0.95:   3.314 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  11.851 ms/op
                 getUser·p0.9999: 14.279 ms/op
                 getUser·p1.00:   14.680 ms/op

Iteration   2: 2.593 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.004 ms/op
                 getUser·p0.50:   2.626 ms/op
                 getUser·p0.90:   3.170 ms/op
                 getUser·p0.95:   3.334 ms/op
                 getUser·p0.99:   4.129 ms/op
                 getUser·p0.999:  11.105 ms/op
                 getUser·p0.9999: 15.647 ms/op
                 getUser·p1.00:   15.876 ms/op

Iteration   3: 2.543 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.948 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.233 ms/op
                 getUser·p0.99:   3.924 ms/op
                 getUser·p0.999:  9.175 ms/op
                 getUser·p0.9999: 10.975 ms/op
                 getUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 373721
  mean =      2.566 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 75 
    [ 1.250,  2.500) = 180108 
    [ 2.500,  3.750) = 187165 
    [ 3.750,  5.000) = 5059 
    [ 5.000,  6.250) = 877 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 93 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.476 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.138 ms/op
     p(95.0000) =      3.297 ms/op
     p(99.0000) =      4.121 ms/op
     p(99.9000) =      9.212 ms/op
     p(99.9900) =     14.795 ms/op
     p(99.9990) =     15.827 ms/op
     p(99.9999) =     15.876 ms/op
    p(100.0000) =     15.876 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.919 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.009 ms/op
Iteration   1: 3.011 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.844 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.385 ms/op
                 listUser·p0.9999: 11.901 ms/op
                 listUser·p1.00:   12.550 ms/op

Iteration   2: 3.048 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.825 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   5.892 ms/op
                 listUser·p0.999:  9.683 ms/op
                 listUser·p0.9999: 13.281 ms/op
                 listUser·p1.00:   13.926 ms/op

Iteration   3: 3.055 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.464 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.784 ms/op
                 listUser·p0.999:  10.224 ms/op
                 listUser·p0.9999: 13.255 ms/op
                 listUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315556
  mean =      3.038 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 89756 
    [ 2.500,  5.000) = 217390 
    [ 5.000,  7.500) = 7629 
    [ 7.500, 10.000) = 504 
    [10.000, 12.500) = 225 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.464 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =      9.847 ms/op
     p(99.9900) =     13.049 ms/op
     p(99.9990) =     13.921 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.336 ± 0.992  ops/ms
ClientPb.existUser                       thrpt       3  12.993 ± 2.951  ops/ms
ClientPb.getUser                         thrpt       3  12.683 ± 2.347  ops/ms
ClientPb.listUser                        thrpt       3  10.553 ± 1.828  ops/ms
ClientPb.createUser                       avgt       3   2.571 ± 0.593   ms/op
ClientPb.existUser                        avgt       3   2.469 ± 0.033   ms/op
ClientPb.getUser                          avgt       3   2.504 ± 0.140   ms/op
ClientPb.listUser                         avgt       3   3.026 ± 0.142   ms/op
ClientPb.createUser                     sample  376450   2.548 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.663           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.535           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.301           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.092           ms/op
ClientPb.createUser:createUser·p0.999   sample          10.167           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.943           ms/op
ClientPb.createUser:createUser·p1.00    sample          21.103           ms/op
ClientPb.existUser                      sample  389911   2.460 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.854           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.413           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.183           ms/op
ClientPb.existUser:existUser·p0.99      sample           4.014           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.522           ms/op
ClientPb.existUser:existUser·p0.9999    sample          16.237           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.170           ms/op
ClientPb.getUser                        sample  373721   2.566 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.476           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.576           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.297           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.121           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.212           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.795           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.876           ms/op
ClientPb.listUser                       sample  315556   3.038 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.464           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.966           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.932           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.759           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.847           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.049           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.087           ms/op
