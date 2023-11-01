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
# Warmup Iteration   1: 1.893 ops/ms
# Warmup Iteration   2: 5.227 ops/ms
# Warmup Iteration   3: 8.295 ops/ms
Iteration   1: 8.696 ops/ms
Iteration   2: 9.032 ops/ms
Iteration   3: 8.768 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.832 ±(99.9%) 3.231 ops/ms [Average]
  (min, avg, max) = (8.696, 8.832, 9.032), stdev = 0.177
  CI (99.9%): [5.601, 12.063] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.024 ops/ms
# Warmup Iteration   2: 8.329 ops/ms
# Warmup Iteration   3: 9.226 ops/ms
Iteration   1: 9.436 ops/ms
Iteration   2: 9.396 ops/ms
Iteration   3: 9.241 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.358 ±(99.9%) 1.876 ops/ms [Average]
  (min, avg, max) = (9.241, 9.358, 9.436), stdev = 0.103
  CI (99.9%): [7.481, 11.234] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.835 ops/ms
# Warmup Iteration   2: 8.410 ops/ms
# Warmup Iteration   3: 8.879 ops/ms
Iteration   1: 9.050 ops/ms
Iteration   2: 9.081 ops/ms
Iteration   3: 9.169 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.100 ±(99.9%) 1.132 ops/ms [Average]
  (min, avg, max) = (9.050, 9.100, 9.169), stdev = 0.062
  CI (99.9%): [7.967, 10.232] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.537 ops/ms
# Warmup Iteration   2: 6.959 ops/ms
# Warmup Iteration   3: 7.442 ops/ms
Iteration   1: 7.378 ops/ms
Iteration   2: 7.700 ops/ms
Iteration   3: 7.634 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.570 ±(99.9%) 3.108 ops/ms [Average]
  (min, avg, max) = (7.378, 7.570, 7.700), stdev = 0.170
  CI (99.9%): [4.463, 10.678] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 9.422 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.919 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.638 ±(99.9%) 0.006 ms/op
Iteration   1: 3.547 ±(99.9%) 0.005 ms/op
Iteration   2: 3.455 ±(99.9%) 0.005 ms/op
Iteration   3: 3.464 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.489 ±(99.9%) 0.920 ms/op [Average]
  (min, avg, max) = (3.455, 3.489, 3.547), stdev = 0.050
  CI (99.9%): [2.569, 4.409] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.740 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.579 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.399 ±(99.9%) 0.002 ms/op
Iteration   1: 3.415 ±(99.9%) 0.004 ms/op
Iteration   2: 3.384 ±(99.9%) 0.004 ms/op
Iteration   3: 3.379 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.393 ±(99.9%) 0.359 ms/op [Average]
  (min, avg, max) = (3.379, 3.393, 3.415), stdev = 0.020
  CI (99.9%): [3.033, 3.752] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 9.965 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.690 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.585 ±(99.9%) 0.003 ms/op
Iteration   1: 3.522 ±(99.9%) 0.005 ms/op
Iteration   2: 3.467 ±(99.9%) 0.005 ms/op
Iteration   3: 3.557 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.515 ±(99.9%) 0.830 ms/op [Average]
  (min, avg, max) = (3.467, 3.515, 3.557), stdev = 0.046
  CI (99.9%): [2.685, 4.345] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 12.249 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.587 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.254 ±(99.9%) 0.005 ms/op
Iteration   1: 4.146 ±(99.9%) 0.009 ms/op
Iteration   2: 4.145 ±(99.9%) 0.009 ms/op
Iteration   3: 4.198 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.163 ±(99.9%) 0.557 ms/op [Average]
  (min, avg, max) = (4.145, 4.163, 4.198), stdev = 0.031
  CI (99.9%): [3.606, 4.720] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 10.791 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.870 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.901 ±(99.9%) 0.015 ms/op
Iteration   1: 3.515 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.575 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   6.365 ms/op
                 createUser·p0.999:  21.627 ms/op
                 createUser·p0.9999: 24.478 ms/op
                 createUser·p1.00:   25.985 ms/op

Iteration   2: 3.557 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.531 ms/op
                 createUser·p0.50:   3.432 ms/op
                 createUser·p0.90:   4.129 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   5.816 ms/op
                 createUser·p0.999:  23.789 ms/op
                 createUser·p0.9999: 26.968 ms/op
                 createUser·p1.00:   27.656 ms/op

Iteration   3: 3.595 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.511 ms/op
                 createUser·p0.50:   3.482 ms/op
                 createUser·p0.90:   4.129 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   6.250 ms/op
                 createUser·p0.999:  17.008 ms/op
                 createUser·p0.9999: 29.622 ms/op
                 createUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 269996
  mean =      3.555 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7230 
    [ 2.500,  5.000) = 256165 
    [ 5.000,  7.500) = 5302 
    [ 7.500, 10.000) = 658 
    [10.000, 12.500) = 218 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 116 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.531 ms/op
     p(50.0000) =      3.445 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.160 ms/op
     p(99.9000) =     17.892 ms/op
     p(99.9900) =     29.229 ms/op
     p(99.9990) =     30.009 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 9.301 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.625 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.499 ±(99.9%) 0.011 ms/op
Iteration   1: 3.398 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.362 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   4.047 ms/op
                 existUser·p0.99:   6.357 ms/op
                 existUser·p0.999:  21.429 ms/op
                 existUser·p0.9999: 24.824 ms/op
                 existUser·p1.00:   25.035 ms/op

Iteration   2: 3.368 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.949 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.084 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  22.568 ms/op
                 existUser·p0.9999: 27.737 ms/op
                 existUser·p1.00:   28.901 ms/op

Iteration   3: 3.389 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.714 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   4.112 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  11.370 ms/op
                 existUser·p0.9999: 29.945 ms/op
                 existUser·p1.00:   30.867 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283611
  mean =      3.385 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9707 
    [ 2.500,  5.000) = 268413 
    [ 5.000,  7.500) = 4619 
    [ 7.500, 10.000) = 376 
    [10.000, 12.500) = 201 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 122 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =     12.976 ms/op
     p(99.9900) =     28.306 ms/op
     p(99.9990) =     30.611 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 9.637 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 3.848 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.651 ±(99.9%) 0.010 ms/op
Iteration   1: 3.650 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.493 ms/op
                 getUser·p0.50:   3.510 ms/op
                 getUser·p0.90:   4.006 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   6.849 ms/op
                 getUser·p0.999:  23.016 ms/op
                 getUser·p0.9999: 28.958 ms/op
                 getUser·p1.00:   29.721 ms/op

Iteration   2: 3.516 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.653 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  12.812 ms/op
                 getUser·p0.9999: 27.355 ms/op
                 getUser·p1.00:   28.475 ms/op

Iteration   3: 3.563 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.493 ms/op
                 getUser·p0.50:   3.432 ms/op
                 getUser·p0.90:   4.010 ms/op
                 getUser·p0.95:   4.317 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  26.673 ms/op
                 getUser·p0.9999: 29.034 ms/op
                 getUser·p1.00:   30.015 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 268394
  mean =      3.575 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1613 
    [ 2.500,  5.000) = 259257 
    [ 5.000,  7.500) = 6464 
    [ 7.500, 10.000) = 570 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 106 
    [27.500, 30.000) = 87 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.493 ms/op
     p(50.0000) =      3.445 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     19.096 ms/op
     p(99.9900) =     28.869 ms/op
     p(99.9990) =     29.721 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.163 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.555 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.346 ±(99.9%) 0.014 ms/op
Iteration   1: 4.293 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.204 ms/op
                 listUser·p0.50:   4.170 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   8.233 ms/op
                 listUser·p0.999:  24.954 ms/op
                 listUser·p0.9999: 30.758 ms/op
                 listUser·p1.00:   32.178 ms/op

Iteration   2: 4.194 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.769 ms/op
                 listUser·p0.50:   4.088 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  16.548 ms/op
                 listUser·p0.9999: 19.625 ms/op
                 listUser·p1.00:   19.988 ms/op

Iteration   3: 4.201 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.408 ms/op
                 listUser·p0.50:   4.055 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   7.750 ms/op
                 listUser·p0.999:  16.054 ms/op
                 listUser·p0.9999: 16.728 ms/op
                 listUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 226808
  mean =      4.229 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47 
    [ 2.500,  5.000) = 217404 
    [ 5.000,  7.500) = 6998 
    [ 7.500, 10.000) = 1424 
    [10.000, 12.500) = 259 
    [12.500, 15.000) = 199 
    [15.000, 17.500) = 269 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      4.104 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      7.569 ms/op
     p(99.9000) =     17.072 ms/op
     p(99.9900) =     30.212 ms/op
     p(99.9990) =     32.064 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.832 ± 3.231  ops/ms
ClientPb.existUser                       thrpt       3   9.358 ± 1.876  ops/ms
ClientPb.getUser                         thrpt       3   9.100 ± 1.132  ops/ms
ClientPb.listUser                        thrpt       3   7.570 ± 3.108  ops/ms
ClientPb.createUser                       avgt       3   3.489 ± 0.920   ms/op
ClientPb.existUser                        avgt       3   3.393 ± 0.359   ms/op
ClientPb.getUser                          avgt       3   3.515 ± 0.830   ms/op
ClientPb.listUser                         avgt       3   4.163 ± 0.557   ms/op
ClientPb.createUser                     sample  269996   3.555 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.531           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.445           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.080           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.391           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.160           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.892           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.229           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.507           ms/op
ClientPb.existUser                      sample  283611   3.385 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.949           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.314           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.088           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.980           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.976           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.306           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.867           ms/op
ClientPb.getUser                        sample  268394   3.575 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.493           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.445           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.981           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.284           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.373           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.096           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.869           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.015           ms/op
ClientPb.listUser                       sample  226808   4.229 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.204           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.104           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.874           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.569           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.072           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.212           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.178           ms/op
