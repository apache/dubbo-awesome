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
# Warmup Iteration   1: 4.869 ops/ms
# Warmup Iteration   2: 11.981 ops/ms
# Warmup Iteration   3: 12.132 ops/ms
Iteration   1: 12.416 ops/ms
Iteration   2: 12.315 ops/ms
Iteration   3: 12.468 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.400 ±(99.9%) 1.418 ops/ms [Average]
  (min, avg, max) = (12.315, 12.400, 12.468), stdev = 0.078
  CI (99.9%): [10.982, 13.817] (assumes normal distribution)


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
# Warmup Iteration   1: 8.089 ops/ms
# Warmup Iteration   2: 13.157 ops/ms
# Warmup Iteration   3: 13.103 ops/ms
Iteration   1: 12.981 ops/ms
Iteration   2: 13.177 ops/ms
Iteration   3: 13.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.086 ±(99.9%) 1.797 ops/ms [Average]
  (min, avg, max) = (12.981, 13.086, 13.177), stdev = 0.098
  CI (99.9%): [11.289, 14.882] (assumes normal distribution)


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
# Warmup Iteration   1: 7.869 ops/ms
# Warmup Iteration   2: 12.364 ops/ms
# Warmup Iteration   3: 12.549 ops/ms
Iteration   1: 12.772 ops/ms
Iteration   2: 12.794 ops/ms
Iteration   3: 12.768 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.778 ±(99.9%) 0.257 ops/ms [Average]
  (min, avg, max) = (12.768, 12.778, 12.794), stdev = 0.014
  CI (99.9%): [12.521, 13.035] (assumes normal distribution)


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
# Warmup Iteration   1: 6.409 ops/ms
# Warmup Iteration   2: 10.217 ops/ms
# Warmup Iteration   3: 10.533 ops/ms
Iteration   1: 10.539 ops/ms
Iteration   2: 10.597 ops/ms
Iteration   3: 10.378 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.505 ±(99.9%) 2.075 ops/ms [Average]
  (min, avg, max) = (10.378, 10.505, 10.597), stdev = 0.114
  CI (99.9%): [8.430, 12.580] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.029 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.611 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.577 ±(99.9%) 0.004 ms/op
Iteration   1: 2.568 ±(99.9%) 0.004 ms/op
Iteration   2: 2.570 ±(99.9%) 0.004 ms/op
Iteration   3: 2.570 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.570 ±(99.9%) 0.021 ms/op [Average]
  (min, avg, max) = (2.568, 2.570, 2.570), stdev = 0.001
  CI (99.9%): [2.549, 2.590] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.670 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.457 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.416 ±(99.9%) 0.004 ms/op
Iteration   1: 2.427 ±(99.9%) 0.003 ms/op
Iteration   2: 2.437 ±(99.9%) 0.003 ms/op
Iteration   3: 2.416 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.426 ±(99.9%) 0.194 ms/op [Average]
  (min, avg, max) = (2.416, 2.426, 2.437), stdev = 0.011
  CI (99.9%): [2.233, 2.620] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.961 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.617 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.005 ms/op
Iteration   1: 2.521 ±(99.9%) 0.005 ms/op
Iteration   2: 2.507 ±(99.9%) 0.004 ms/op
Iteration   3: 2.543 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.524 ±(99.9%) 0.335 ms/op [Average]
  (min, avg, max) = (2.507, 2.524, 2.543), stdev = 0.018
  CI (99.9%): [2.188, 2.859] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.735 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.005 ms/op
Iteration   1: 3.052 ±(99.9%) 0.005 ms/op
Iteration   2: 3.022 ±(99.9%) 0.005 ms/op
Iteration   3: 3.048 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.041 ±(99.9%) 0.304 ms/op [Average]
  (min, avg, max) = (3.022, 3.041, 3.052), stdev = 0.017
  CI (99.9%): [2.737, 3.344] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.206 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.660 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.006 ms/op
Iteration   1: 2.547 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.854 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.850 ms/op
                 createUser·p0.999:  11.018 ms/op
                 createUser·p0.9999: 13.533 ms/op
                 createUser·p1.00:   14.336 ms/op

Iteration   2: 2.518 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.899 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.555 ms/op
                 createUser·p0.999:  9.373 ms/op
                 createUser·p0.9999: 11.741 ms/op
                 createUser·p1.00:   12.763 ms/op

Iteration   3: 2.536 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.974 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.744 ms/op
                 createUser·p0.999:  8.487 ms/op
                 createUser·p0.9999: 10.240 ms/op
                 createUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378339
  mean =      2.534 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 182855 
    [ 2.500,  3.750) = 191787 
    [ 3.750,  5.000) = 2931 
    [ 5.000,  6.250) = 226 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 105 
    [ 8.750, 10.000) = 109 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =      8.520 ms/op
     p(99.9900) =     12.911 ms/op
     p(99.9990) =     14.258 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


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
# Warmup Iteration   1: 3.760 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.485 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
Iteration   1: 2.439 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.750 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.482 ms/op
                 existUser·p0.999:  6.435 ms/op
                 existUser·p0.9999: 19.300 ms/op
                 existUser·p1.00:   20.218 ms/op

Iteration   2: 2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.918 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  8.231 ms/op
                 existUser·p0.9999: 16.562 ms/op
                 existUser·p1.00:   17.367 ms/op

Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.030 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.973 ms/op
                 existUser·p0.999:  8.239 ms/op
                 existUser·p0.9999: 11.719 ms/op
                 existUser·p1.00:   14.352 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390606
  mean =      2.455 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 194065 
    [ 2.500,  5.000) = 195621 
    [ 5.000,  7.500) = 513 
    [ 7.500, 10.000) = 133 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.670 ms/op
     p(99.9000) =      8.190 ms/op
     p(99.9900) =     16.876 ms/op
     p(99.9990) =     20.093 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


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
# Warmup Iteration   1: 4.187 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 2.627 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.006 ms/op
Iteration   1: 2.510 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.399 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.719 ms/op
                 getUser·p0.999:  5.218 ms/op
                 getUser·p0.9999: 14.209 ms/op
                 getUser·p1.00:   15.008 ms/op

Iteration   2: 2.548 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.699 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.269 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  10.027 ms/op
                 getUser·p0.9999: 14.072 ms/op
                 getUser·p1.00:   14.516 ms/op

Iteration   3: 2.549 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.670 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.256 ms/op
                 getUser·p0.99:   4.216 ms/op
                 getUser·p0.999:  8.833 ms/op
                 getUser·p0.9999: 12.367 ms/op
                 getUser·p1.00:   13.681 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378289
  mean =      2.535 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 185004 
    [ 2.500,  3.750) = 186935 
    [ 3.750,  5.000) = 5060 
    [ 5.000,  6.250) = 811 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 114 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.399 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      4.141 ms/op
     p(99.9000) =      6.414 ms/op
     p(99.9900) =     14.011 ms/op
     p(99.9990) =     14.893 ms/op
     p(99.9999) =     15.008 ms/op
    p(100.0000) =     15.008 ms/op


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
# Warmup Iteration   1: 4.685 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.009 ms/op
Iteration   1: 3.082 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.005 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   4.035 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  9.261 ms/op
                 listUser·p0.9999: 11.053 ms/op
                 listUser·p1.00:   11.141 ms/op

Iteration   2: 3.084 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.911 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.800 ms/op
                 listUser·p0.999:  9.803 ms/op
                 listUser·p0.9999: 11.521 ms/op
                 listUser·p1.00:   12.960 ms/op

Iteration   3: 3.108 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.963 ms/op
                 listUser·p0.50:   3.039 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   5.775 ms/op
                 listUser·p0.999:  9.816 ms/op
                 listUser·p0.9999: 11.366 ms/op
                 listUser·p1.00:   11.862 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 310250
  mean =      3.091 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 112 
    [ 1.250,  2.500) = 78838 
    [ 2.500,  3.750) = 185556 
    [ 3.750,  5.000) = 36695 
    [ 5.000,  6.250) = 7528 
    [ 6.250,  7.500) = 839 
    [ 7.500,  8.750) = 217 
    [ 8.750, 10.000) = 241 
    [10.000, 11.250) = 189 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =      9.601 ms/op
     p(99.9900) =     11.289 ms/op
     p(99.9990) =     12.228 ms/op
     p(99.9999) =     12.960 ms/op
    p(100.0000) =     12.960 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.400 ± 1.418  ops/ms
ClientPb.existUser                       thrpt       3  13.086 ± 1.797  ops/ms
ClientPb.getUser                         thrpt       3  12.778 ± 0.257  ops/ms
ClientPb.listUser                        thrpt       3  10.505 ± 2.075  ops/ms
ClientPb.createUser                       avgt       3   2.570 ± 0.021   ms/op
ClientPb.existUser                        avgt       3   2.426 ± 0.194   ms/op
ClientPb.getUser                          avgt       3   2.524 ± 0.335   ms/op
ClientPb.listUser                         avgt       3   3.041 ± 0.304   ms/op
ClientPb.createUser                     sample  378339   2.534 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.854           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.731           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.520           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.911           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.547           ms/op
ClientPb.existUser                      sample  390606   2.455 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.750           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.190           ms/op
ClientPb.existUser:existUser·p0.9999    sample          16.876           ms/op
ClientPb.existUser:existUser·p1.00      sample          20.218           ms/op
ClientPb.getUser                        sample  378289   2.535 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.399           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.228           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.141           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.414           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.011           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.008           ms/op
ClientPb.listUser                       sample  310250   3.091 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.911           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.023           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.022           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.767           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.601           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.289           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.960           ms/op
