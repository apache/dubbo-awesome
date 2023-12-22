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
# Warmup Iteration   1: 4.633 ops/ms
# Warmup Iteration   2: 11.936 ops/ms
# Warmup Iteration   3: 12.259 ops/ms
Iteration   1: 12.463 ops/ms
Iteration   2: 12.409 ops/ms
Iteration   3: 12.429 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.434 ±(99.9%) 0.496 ops/ms [Average]
  (min, avg, max) = (12.409, 12.434, 12.463), stdev = 0.027
  CI (99.9%): [11.938, 12.930] (assumes normal distribution)


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
# Warmup Iteration   1: 8.316 ops/ms
# Warmup Iteration   2: 12.860 ops/ms
# Warmup Iteration   3: 13.034 ops/ms
Iteration   1: 12.942 ops/ms
Iteration   2: 13.095 ops/ms
Iteration   3: 13.018 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.018 ±(99.9%) 1.400 ops/ms [Average]
  (min, avg, max) = (12.942, 13.018, 13.095), stdev = 0.077
  CI (99.9%): [11.618, 14.418] (assumes normal distribution)


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
# Warmup Iteration   1: 7.930 ops/ms
# Warmup Iteration   2: 12.687 ops/ms
# Warmup Iteration   3: 12.851 ops/ms
Iteration   1: 12.803 ops/ms
Iteration   2: 12.774 ops/ms
Iteration   3: 12.739 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.772 ±(99.9%) 0.586 ops/ms [Average]
  (min, avg, max) = (12.739, 12.772, 12.803), stdev = 0.032
  CI (99.9%): [12.186, 13.358] (assumes normal distribution)


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
# Warmup Iteration   1: 7.091 ops/ms
# Warmup Iteration   2: 10.481 ops/ms
# Warmup Iteration   3: 10.513 ops/ms
Iteration   1: 10.425 ops/ms
Iteration   2: 10.608 ops/ms
Iteration   3: 10.620 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.551 ±(99.9%) 1.988 ops/ms [Average]
  (min, avg, max) = (10.425, 10.551, 10.620), stdev = 0.109
  CI (99.9%): [8.563, 12.539] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.779 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.566 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.004 ms/op
Iteration   1: 2.487 ±(99.9%) 0.004 ms/op
Iteration   2: 2.509 ±(99.9%) 0.004 ms/op
Iteration   3: 2.501 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.499 ±(99.9%) 0.202 ms/op [Average]
  (min, avg, max) = (2.487, 2.499, 2.509), stdev = 0.011
  CI (99.9%): [2.297, 2.701] (assumes normal distribution)


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
# Warmup Iteration   1: 3.645 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.478 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.004 ms/op
Iteration   1: 2.493 ±(99.9%) 0.005 ms/op
Iteration   2: 2.488 ±(99.9%) 0.004 ms/op
Iteration   3: 2.481 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.488 ±(99.9%) 0.111 ms/op [Average]
  (min, avg, max) = (2.481, 2.488, 2.493), stdev = 0.006
  CI (99.9%): [2.377, 2.598] (assumes normal distribution)


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
# Warmup Iteration   1: 3.938 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.521 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.004 ms/op
Iteration   1: 2.462 ±(99.9%) 0.003 ms/op
Iteration   2: 2.457 ±(99.9%) 0.003 ms/op
Iteration   3: 2.465 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.461 ±(99.9%) 0.071 ms/op [Average]
  (min, avg, max) = (2.457, 2.461, 2.465), stdev = 0.004
  CI (99.9%): [2.390, 2.533] (assumes normal distribution)


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
# Warmup Iteration   1: 4.875 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.005 ms/op
Iteration   1: 2.983 ±(99.9%) 0.005 ms/op
Iteration   2: 2.975 ±(99.9%) 0.007 ms/op
Iteration   3: 2.974 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.977 ±(99.9%) 0.096 ms/op [Average]
  (min, avg, max) = (2.974, 2.977, 2.983), stdev = 0.005
  CI (99.9%): [2.881, 3.074] (assumes normal distribution)


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
# Warmup Iteration   1: 4.247 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.650 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.548 ±(99.9%) 0.006 ms/op
Iteration   1: 2.520 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.899 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.678 ms/op
                 createUser·p0.999:  11.125 ms/op
                 createUser·p0.9999: 13.276 ms/op
                 createUser·p1.00:   13.910 ms/op

Iteration   2: 2.527 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.912 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.629 ms/op
                 createUser·p0.999:  9.412 ms/op
                 createUser·p0.9999: 12.326 ms/op
                 createUser·p1.00:   12.648 ms/op

Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.881 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.781 ms/op
                 createUser·p0.999:  8.405 ms/op
                 createUser·p0.9999: 10.110 ms/op
                 createUser·p1.00:   14.533 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379872
  mean =      2.524 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 183697 
    [ 2.500,  3.750) = 192636 
    [ 3.750,  5.000) = 2828 
    [ 5.000,  6.250) = 253 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.707 ms/op
     p(99.9000) =      8.438 ms/op
     p(99.9900) =     12.780 ms/op
     p(99.9990) =     13.700 ms/op
     p(99.9999) =     14.533 ms/op
    p(100.0000) =     14.533 ms/op


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
# Warmup Iteration   1: 3.724 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.502 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
Iteration   1: 2.468 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.893 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.482 ms/op
                 existUser·p0.999:  5.939 ms/op
                 existUser·p0.9999: 13.757 ms/op
                 existUser·p1.00:   14.287 ms/op

Iteration   2: 2.450 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.964 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.641 ms/op
                 existUser·p0.999:  6.834 ms/op
                 existUser·p0.9999: 12.861 ms/op
                 existUser·p1.00:   13.795 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.034 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.633 ms/op
                 existUser·p0.999:  8.369 ms/op
                 existUser·p0.9999: 11.913 ms/op
                 existUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388843
  mean =      2.466 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 191743 
    [ 2.500,  3.750) = 194021 
    [ 3.750,  5.000) = 2267 
    [ 5.000,  6.250) = 327 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 108 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 118 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.592 ms/op
     p(99.9000) =      8.126 ms/op
     p(99.9900) =     13.060 ms/op
     p(99.9990) =     14.256 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


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
# Warmup Iteration   1: 4.061 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.571 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.005 ms/op
Iteration   1: 2.513 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.059 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   4.039 ms/op
                 getUser·p0.999:  11.465 ms/op
                 getUser·p0.9999: 14.549 ms/op
                 getUser·p1.00:   15.286 ms/op

Iteration   2: 2.483 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.863 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.895 ms/op
                 getUser·p0.999:  7.028 ms/op
                 getUser·p0.9999: 13.670 ms/op
                 getUser·p1.00:   13.894 ms/op

Iteration   3: 2.508 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.967 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   4.760 ms/op
                 getUser·p0.999:  8.549 ms/op
                 getUser·p0.9999: 10.912 ms/op
                 getUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383440
  mean =      2.501 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 97 
    [ 1.250,  2.500) = 189479 
    [ 2.500,  3.750) = 187579 
    [ 3.750,  5.000) = 4655 
    [ 5.000,  6.250) = 1218 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      4.137 ms/op
     p(99.9000) =      8.551 ms/op
     p(99.9900) =     13.795 ms/op
     p(99.9990) =     15.142 ms/op
     p(99.9999) =     15.286 ms/op
    p(100.0000) =     15.286 ms/op


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
# Warmup Iteration   1: 4.718 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.008 ms/op
Iteration   1: 3.013 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.926 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.585 ms/op
                 listUser·p0.999:  9.486 ms/op
                 listUser·p0.9999: 13.441 ms/op
                 listUser·p1.00:   13.779 ms/op

Iteration   2: 3.009 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.984 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.568 ms/op
                 listUser·p0.9999: 11.000 ms/op
                 listUser·p1.00:   12.042 ms/op

Iteration   3: 3.032 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.943 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  9.437 ms/op
                 listUser·p0.9999: 12.132 ms/op
                 listUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317818
  mean =      3.018 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 113 
    [ 1.250,  2.500) = 91581 
    [ 2.500,  3.750) = 186568 
    [ 3.750,  5.000) = 32615 
    [ 5.000,  6.250) = 5696 
    [ 6.250,  7.500) = 584 
    [ 7.500,  8.750) = 164 
    [ 8.750, 10.000) = 289 
    [10.000, 11.250) = 164 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.926 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.503 ms/op
     p(99.9900) =     11.751 ms/op
     p(99.9990) =     13.727 ms/op
     p(99.9999) =     13.779 ms/op
    p(100.0000) =     13.779 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.434 ± 0.496  ops/ms
ClientPb.existUser                       thrpt       3  13.018 ± 1.400  ops/ms
ClientPb.getUser                         thrpt       3  12.772 ± 0.586  ops/ms
ClientPb.listUser                        thrpt       3  10.551 ± 1.988  ops/ms
ClientPb.createUser                       avgt       3   2.499 ± 0.202   ms/op
ClientPb.existUser                        avgt       3   2.488 ± 0.111   ms/op
ClientPb.getUser                          avgt       3   2.461 ± 0.071   ms/op
ClientPb.listUser                         avgt       3   2.977 ± 0.096   ms/op
ClientPb.createUser                     sample  379872   2.524 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.881           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.707           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.438           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.780           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.533           ms/op
ClientPb.existUser                      sample  388843   2.466 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.893           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.592           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.126           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.060           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.287           ms/op
ClientPb.getUser                        sample  383440   2.501 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.863           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.527           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.187           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.137           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.551           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.795           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.286           ms/op
ClientPb.listUser                       sample  317818   3.018 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.926           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.503           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.751           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.779           ms/op
