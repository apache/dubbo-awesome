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
# Warmup Iteration   1: 4.742 ops/ms
# Warmup Iteration   2: 11.810 ops/ms
# Warmup Iteration   3: 12.163 ops/ms
Iteration   1: 12.114 ops/ms
Iteration   2: 12.320 ops/ms
Iteration   3: 12.505 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.313 ±(99.9%) 3.562 ops/ms [Average]
  (min, avg, max) = (12.114, 12.313, 12.505), stdev = 0.195
  CI (99.9%): [8.751, 15.875] (assumes normal distribution)


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
# Warmup Iteration   1: 8.167 ops/ms
# Warmup Iteration   2: 12.748 ops/ms
# Warmup Iteration   3: 12.937 ops/ms
Iteration   1: 12.966 ops/ms
Iteration   2: 12.847 ops/ms
Iteration   3: 12.888 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.900 ±(99.9%) 1.099 ops/ms [Average]
  (min, avg, max) = (12.847, 12.900, 12.966), stdev = 0.060
  CI (99.9%): [11.802, 13.999] (assumes normal distribution)


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
# Warmup Iteration   1: 7.754 ops/ms
# Warmup Iteration   2: 12.818 ops/ms
# Warmup Iteration   3: 12.885 ops/ms
Iteration   1: 12.951 ops/ms
Iteration   2: 13.168 ops/ms
Iteration   3: 13.078 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.066 ±(99.9%) 1.986 ops/ms [Average]
  (min, avg, max) = (12.951, 13.066, 13.168), stdev = 0.109
  CI (99.9%): [11.080, 15.052] (assumes normal distribution)


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
# Warmup Iteration   1: 6.538 ops/ms
# Warmup Iteration   2: 10.508 ops/ms
# Warmup Iteration   3: 10.650 ops/ms
Iteration   1: 10.628 ops/ms
Iteration   2: 10.736 ops/ms
Iteration   3: 10.761 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.708 ±(99.9%) 1.289 ops/ms [Average]
  (min, avg, max) = (10.628, 10.708, 10.761), stdev = 0.071
  CI (99.9%): [9.419, 11.998] (assumes normal distribution)


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
# Warmup Iteration   1: 4.177 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.600 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.534 ±(99.9%) 0.004 ms/op
Iteration   1: 2.575 ±(99.9%) 0.004 ms/op
Iteration   2: 2.512 ±(99.9%) 0.005 ms/op
Iteration   3: 2.511 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.533 ±(99.9%) 0.671 ms/op [Average]
  (min, avg, max) = (2.511, 2.533, 2.575), stdev = 0.037
  CI (99.9%): [1.862, 3.203] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.654 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.005 ms/op
Iteration   1: 2.474 ±(99.9%) 0.004 ms/op
Iteration   2: 2.469 ±(99.9%) 0.003 ms/op
Iteration   3: 2.483 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.475 ±(99.9%) 0.130 ms/op [Average]
  (min, avg, max) = (2.469, 2.475, 2.483), stdev = 0.007
  CI (99.9%): [2.346, 2.605] (assumes normal distribution)


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
# Warmup Iteration   1: 4.010 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.532 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
Iteration   1: 2.457 ±(99.9%) 0.004 ms/op
Iteration   2: 2.492 ±(99.9%) 0.004 ms/op
Iteration   3: 2.468 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.473 ±(99.9%) 0.327 ms/op [Average]
  (min, avg, max) = (2.457, 2.473, 2.492), stdev = 0.018
  CI (99.9%): [2.146, 2.800] (assumes normal distribution)


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
# Warmup Iteration   1: 4.883 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.030 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.005 ms/op
Iteration   1: 2.958 ±(99.9%) 0.005 ms/op
Iteration   2: 2.985 ±(99.9%) 0.006 ms/op
Iteration   3: 2.976 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.973 ±(99.9%) 0.253 ms/op [Average]
  (min, avg, max) = (2.958, 2.973, 2.985), stdev = 0.014
  CI (99.9%): [2.720, 3.226] (assumes normal distribution)


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
# Warmup Iteration   1: 4.309 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.613 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.579 ±(99.9%) 0.006 ms/op
Iteration   1: 2.524 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.641 ms/op
                 createUser·p0.999:  11.245 ms/op
                 createUser·p0.9999: 13.255 ms/op
                 createUser·p1.00:   13.926 ms/op

Iteration   2: 2.568 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.969 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.243 ms/op
                 createUser·p0.99:   4.010 ms/op
                 createUser·p0.999:  10.011 ms/op
                 createUser·p0.9999: 13.337 ms/op
                 createUser·p1.00:   13.615 ms/op

Iteration   3: 2.548 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.956 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.707 ms/op
                 createUser·p0.999:  8.239 ms/op
                 createUser·p0.9999: 10.927 ms/op
                 createUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376533
  mean =      2.547 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 179885 
    [ 2.500,  3.750) = 192564 
    [ 3.750,  5.000) = 3299 
    [ 5.000,  6.250) = 292 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 71 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 104 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.956 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.793 ms/op
     p(99.9000) =      8.335 ms/op
     p(99.9900) =     13.107 ms/op
     p(99.9990) =     13.680 ms/op
     p(99.9999) =     13.926 ms/op
    p(100.0000) =     13.926 ms/op


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
# Warmup Iteration   1: 3.761 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.496 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
Iteration   1: 2.480 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.053 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.486 ms/op
                 existUser·p0.999:  5.918 ms/op
                 existUser·p0.9999: 13.731 ms/op
                 existUser·p1.00:   14.287 ms/op

Iteration   2: 2.485 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.932 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.767 ms/op
                 existUser·p0.999:  5.743 ms/op
                 existUser·p0.9999: 12.665 ms/op
                 existUser·p1.00:   13.484 ms/op

Iteration   3: 2.519 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.889 ms/op
                 existUser·p0.50:   2.585 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.174 ms/op
                 existUser·p0.99:   3.772 ms/op
                 existUser·p0.999:  9.981 ms/op
                 existUser·p0.9999: 12.124 ms/op
                 existUser·p1.00:   12.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384494
  mean =      2.494 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 188193 
    [ 2.500,  3.750) = 192877 
    [ 3.750,  5.000) = 2660 
    [ 5.000,  6.250) = 305 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 141 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.889 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.670 ms/op
     p(99.9000) =      7.115 ms/op
     p(99.9900) =     13.271 ms/op
     p(99.9990) =     14.177 ms/op
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
# Warmup Iteration   1: 4.067 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.649 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.564 ±(99.9%) 0.006 ms/op
Iteration   1: 2.529 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.989 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.760 ms/op
                 getUser·p0.999:  10.971 ms/op
                 getUser·p0.9999: 17.440 ms/op
                 getUser·p1.00:   18.317 ms/op

Iteration   2: 2.536 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.067 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.998 ms/op
                 getUser·p0.999:  8.962 ms/op
                 getUser·p0.9999: 13.245 ms/op
                 getUser·p1.00:   14.090 ms/op

Iteration   3: 2.547 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.893 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  8.602 ms/op
                 getUser·p0.9999: 11.376 ms/op
                 getUser·p1.00:   12.288 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377992
  mean =      2.537 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 73 
    [ 1.250,  2.500) = 185156 
    [ 2.500,  3.750) = 187483 
    [ 3.750,  5.000) = 3898 
    [ 5.000,  6.250) = 892 
    [ 6.250,  7.500) = 79 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.977 ms/op
     p(99.9000) =      8.684 ms/op
     p(99.9900) =     13.759 ms/op
     p(99.9990) =     17.957 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


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
# Warmup Iteration   1: 4.820 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.008 ms/op
Iteration   1: 2.997 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.766 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.683 ms/op
                 listUser·p0.9999: 11.360 ms/op
                 listUser·p1.00:   12.042 ms/op

Iteration   2: 3.016 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.883 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.191 ms/op
                 listUser·p0.9999: 10.957 ms/op
                 listUser·p1.00:   12.780 ms/op

Iteration   3: 3.025 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.889 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.546 ms/op
                 listUser·p0.9999: 11.378 ms/op
                 listUser·p1.00:   12.419 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318396
  mean =      3.012 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 118 
    [ 1.250,  2.500) = 91370 
    [ 2.500,  3.750) = 187556 
    [ 3.750,  5.000) = 32352 
    [ 5.000,  6.250) = 5577 
    [ 6.250,  7.500) = 749 
    [ 7.500,  8.750) = 220 
    [ 8.750, 10.000) = 253 
    [10.000, 11.250) = 165 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.372 ms/op
     p(99.9900) =     11.340 ms/op
     p(99.9990) =     12.148 ms/op
     p(99.9999) =     12.780 ms/op
    p(100.0000) =     12.780 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.313 ± 3.562  ops/ms
ClientPb.existUser                       thrpt       3  12.900 ± 1.099  ops/ms
ClientPb.getUser                         thrpt       3  13.066 ± 1.986  ops/ms
ClientPb.listUser                        thrpt       3  10.708 ± 1.289  ops/ms
ClientPb.createUser                       avgt       3   2.533 ± 0.671   ms/op
ClientPb.existUser                        avgt       3   2.475 ± 0.130   ms/op
ClientPb.getUser                          avgt       3   2.473 ± 0.327   ms/op
ClientPb.listUser                         avgt       3   2.973 ± 0.253   ms/op
ClientPb.createUser                     sample  376533   2.547 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.956           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.621           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.335           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.107           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.926           ms/op
ClientPb.existUser                      sample  384494   2.494 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.889           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.556           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.115           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.271           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.287           ms/op
ClientPb.getUser                        sample  377992   2.537 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.893           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.215           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.684           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.759           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.317           ms/op
ClientPb.listUser                       sample  318396   3.012 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.766           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.372           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.340           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.780           ms/op
