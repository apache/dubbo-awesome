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
# Warmup Iteration   1: 4.561 ops/ms
# Warmup Iteration   2: 11.995 ops/ms
# Warmup Iteration   3: 12.400 ops/ms
Iteration   1: 12.734 ops/ms
Iteration   2: 12.465 ops/ms
Iteration   3: 12.668 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.622 ±(99.9%) 2.563 ops/ms [Average]
  (min, avg, max) = (12.465, 12.622, 12.734), stdev = 0.140
  CI (99.9%): [10.060, 15.185] (assumes normal distribution)


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
# Warmup Iteration   1: 7.777 ops/ms
# Warmup Iteration   2: 13.033 ops/ms
# Warmup Iteration   3: 13.144 ops/ms
Iteration   1: 13.095 ops/ms
Iteration   2: 13.051 ops/ms
Iteration   3: 12.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.044 ±(99.9%) 0.991 ops/ms [Average]
  (min, avg, max) = (12.987, 13.044, 13.095), stdev = 0.054
  CI (99.9%): [12.054, 14.035] (assumes normal distribution)


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
# Warmup Iteration   1: 7.450 ops/ms
# Warmup Iteration   2: 12.322 ops/ms
# Warmup Iteration   3: 12.560 ops/ms
Iteration   1: 12.515 ops/ms
Iteration   2: 12.451 ops/ms
Iteration   3: 12.591 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.519 ±(99.9%) 1.282 ops/ms [Average]
  (min, avg, max) = (12.451, 12.519, 12.591), stdev = 0.070
  CI (99.9%): [11.237, 13.801] (assumes normal distribution)


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
# Warmup Iteration   1: 6.209 ops/ms
# Warmup Iteration   2: 10.443 ops/ms
# Warmup Iteration   3: 10.436 ops/ms
Iteration   1: 10.612 ops/ms
Iteration   2: 10.583 ops/ms
Iteration   3: 10.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.584 ±(99.9%) 0.491 ops/ms [Average]
  (min, avg, max) = (10.558, 10.584, 10.612), stdev = 0.027
  CI (99.9%): [10.094, 11.075] (assumes normal distribution)


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
# Warmup Iteration   1: 4.088 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.650 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.561 ±(99.9%) 0.004 ms/op
Iteration   1: 2.539 ±(99.9%) 0.004 ms/op
Iteration   2: 2.556 ±(99.9%) 0.004 ms/op
Iteration   3: 2.609 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.568 ±(99.9%) 0.672 ms/op [Average]
  (min, avg, max) = (2.539, 2.568, 2.609), stdev = 0.037
  CI (99.9%): [1.896, 3.240] (assumes normal distribution)


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
# Warmup Iteration   1: 3.904 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.505 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.456 ±(99.9%) 0.004 ms/op
Iteration   1: 2.465 ±(99.9%) 0.004 ms/op
Iteration   2: 2.491 ±(99.9%) 0.004 ms/op
Iteration   3: 2.510 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.489 ±(99.9%) 0.417 ms/op [Average]
  (min, avg, max) = (2.465, 2.489, 2.510), stdev = 0.023
  CI (99.9%): [2.072, 2.905] (assumes normal distribution)


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
# Warmup Iteration   1: 3.862 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.621 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.570 ±(99.9%) 0.004 ms/op
Iteration   1: 2.534 ±(99.9%) 0.004 ms/op
Iteration   2: 2.553 ±(99.9%) 0.004 ms/op
Iteration   3: 2.564 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.550 ±(99.9%) 0.280 ms/op [Average]
  (min, avg, max) = (2.534, 2.550, 2.564), stdev = 0.015
  CI (99.9%): [2.270, 2.831] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.980 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.005 ms/op
Iteration   1: 3.014 ±(99.9%) 0.005 ms/op
Iteration   2: 3.019 ±(99.9%) 0.006 ms/op
Iteration   3: 3.023 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.019 ±(99.9%) 0.084 ms/op [Average]
  (min, avg, max) = (3.014, 3.019, 3.023), stdev = 0.005
  CI (99.9%): [2.935, 3.103] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.163 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.663 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.545 ±(99.9%) 0.006 ms/op
Iteration   1: 2.561 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.971 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   4.125 ms/op
                 createUser·p0.999:  11.979 ms/op
                 createUser·p0.9999: 15.795 ms/op
                 createUser·p1.00:   17.269 ms/op

Iteration   2: 2.551 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.740 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.758 ms/op
                 createUser·p0.999:  9.835 ms/op
                 createUser·p0.9999: 11.750 ms/op
                 createUser·p1.00:   12.288 ms/op

Iteration   3: 2.585 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.834 ms/op
                 createUser·p0.50:   2.683 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.269 ms/op
                 createUser·p0.99:   4.141 ms/op
                 createUser·p0.999:  8.804 ms/op
                 createUser·p0.9999: 11.828 ms/op
                 createUser·p1.00:   12.780 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 373871
  mean =      2.565 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 175652 
    [ 2.500,  3.750) = 192712 
    [ 3.750,  5.000) = 4212 
    [ 5.000,  6.250) = 738 
    [ 6.250,  7.500) = 105 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      2.642 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      3.244 ms/op
     p(99.0000) =      4.018 ms/op
     p(99.9000) =      8.866 ms/op
     p(99.9900) =     14.018 ms/op
     p(99.9990) =     16.877 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


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
# Warmup Iteration   1: 3.804 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
Iteration   1: 2.500 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.908 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.682 ms/op
                 existUser·p0.999:  11.277 ms/op
                 existUser·p0.9999: 13.812 ms/op
                 existUser·p1.00:   14.074 ms/op

Iteration   2: 2.543 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   3.101 ms/op
                 existUser·p0.95:   3.289 ms/op
                 existUser·p0.99:   4.088 ms/op
                 existUser·p0.999:  8.927 ms/op
                 existUser·p0.9999: 13.030 ms/op
                 existUser·p1.00:   14.008 ms/op

Iteration   3: 2.514 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.087 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.047 ms/op
                 existUser·p0.95:   3.174 ms/op
                 existUser·p0.99:   4.312 ms/op
                 existUser·p0.999:  8.503 ms/op
                 existUser·p0.9999: 12.124 ms/op
                 existUser·p1.00:   12.632 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 380750
  mean =      2.519 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 25 
    [ 1.250,  2.500) = 183602 
    [ 2.500,  3.750) = 191345 
    [ 3.750,  5.000) = 4544 
    [ 5.000,  6.250) = 702 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 99 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      4.035 ms/op
     p(99.9000) =      8.638 ms/op
     p(99.9900) =     13.400 ms/op
     p(99.9990) =     14.008 ms/op
     p(99.9999) =     14.074 ms/op
    p(100.0000) =     14.074 ms/op


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
# Warmup Iteration   1: 3.903 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.617 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.558 ±(99.9%) 0.006 ms/op
Iteration   1: 2.498 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.954 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.863 ms/op
                 getUser·p0.999:  11.551 ms/op
                 getUser·p0.9999: 14.012 ms/op
                 getUser·p1.00:   14.664 ms/op

Iteration   2: 2.503 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.876 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.899 ms/op
                 getUser·p0.999:  9.799 ms/op
                 getUser·p0.9999: 14.185 ms/op
                 getUser·p1.00:   15.811 ms/op

Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.700 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.908 ms/op
                 getUser·p0.999:  8.651 ms/op
                 getUser·p0.9999: 11.873 ms/op
                 getUser·p1.00:   12.288 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383438
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 188579 
    [ 2.500,  3.750) = 189912 
    [ 3.750,  5.000) = 3961 
    [ 5.000,  6.250) = 498 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 115 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.891 ms/op
     p(99.9000) =      8.651 ms/op
     p(99.9900) =     13.795 ms/op
     p(99.9990) =     15.461 ms/op
     p(99.9999) =     15.811 ms/op
    p(100.0000) =     15.811 ms/op


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
# Warmup Iteration   1: 4.796 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.009 ms/op
Iteration   1: 3.042 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.962 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.093 ms/op
                 listUser·p0.9999: 15.907 ms/op
                 listUser·p1.00:   16.613 ms/op

Iteration   2: 3.002 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.859 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.495 ms/op
                 listUser·p0.9999: 10.852 ms/op
                 listUser·p1.00:   12.059 ms/op

Iteration   3: 2.994 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.836 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.121 ms/op
                 listUser·p0.9999: 11.758 ms/op
                 listUser·p1.00:   12.894 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318330
  mean =      3.013 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 125 
    [ 1.250,  2.500) = 88743 
    [ 2.500,  3.750) = 189967 
    [ 3.750,  5.000) = 32477 
    [ 5.000,  6.250) = 5797 
    [ 6.250,  7.500) = 566 
    [ 7.500,  8.750) = 206 
    [ 8.750, 10.000) = 292 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.836 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.535 ms/op
     p(99.9000) =      9.290 ms/op
     p(99.9900) =     13.571 ms/op
     p(99.9990) =     16.604 ms/op
     p(99.9999) =     16.613 ms/op
    p(100.0000) =     16.613 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.622 ± 2.563  ops/ms
ClientPb.existUser                       thrpt       3  13.044 ± 0.991  ops/ms
ClientPb.getUser                         thrpt       3  12.519 ± 1.282  ops/ms
ClientPb.listUser                        thrpt       3  10.584 ± 0.491  ops/ms
ClientPb.createUser                       avgt       3   2.568 ± 0.672   ms/op
ClientPb.existUser                        avgt       3   2.489 ± 0.417   ms/op
ClientPb.getUser                          avgt       3   2.550 ± 0.280   ms/op
ClientPb.listUser                         avgt       3   3.019 ± 0.084   ms/op
ClientPb.createUser                     sample  373871   2.565 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.740           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.642           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.244           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.018           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.866           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.018           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.269           ms/op
ClientPb.existUser                      sample  380750   2.519 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.813           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.580           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.195           ms/op
ClientPb.existUser:existUser·p0.99      sample           4.035           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.638           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.400           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.074           ms/op
ClientPb.getUser                        sample  383438   2.502 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.700           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.651           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.795           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.811           ms/op
ClientPb.listUser                       sample  318330   3.013 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.836           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.535           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.290           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.571           ms/op
ClientPb.listUser:listUser·p1.00        sample          16.613           ms/op
