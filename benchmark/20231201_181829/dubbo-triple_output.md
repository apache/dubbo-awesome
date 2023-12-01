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
# Warmup Iteration   1: 4.219 ops/ms
# Warmup Iteration   2: 11.628 ops/ms
# Warmup Iteration   3: 12.220 ops/ms
Iteration   1: 12.400 ops/ms
Iteration   2: 12.520 ops/ms
Iteration   3: 12.761 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.560 ±(99.9%) 3.347 ops/ms [Average]
  (min, avg, max) = (12.400, 12.560, 12.761), stdev = 0.183
  CI (99.9%): [9.213, 15.907] (assumes normal distribution)


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
# Warmup Iteration   1: 7.788 ops/ms
# Warmup Iteration   2: 12.906 ops/ms
# Warmup Iteration   3: 12.974 ops/ms
Iteration   1: 13.032 ops/ms
Iteration   2: 13.048 ops/ms
Iteration   3: 12.982 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.021 ±(99.9%) 0.635 ops/ms [Average]
  (min, avg, max) = (12.982, 13.021, 13.048), stdev = 0.035
  CI (99.9%): [12.386, 13.656] (assumes normal distribution)


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
# Warmup Iteration   1: 7.545 ops/ms
# Warmup Iteration   2: 12.444 ops/ms
# Warmup Iteration   3: 12.487 ops/ms
Iteration   1: 12.823 ops/ms
Iteration   2: 12.823 ops/ms
Iteration   3: 12.678 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.775 ±(99.9%) 1.524 ops/ms [Average]
  (min, avg, max) = (12.678, 12.775, 12.823), stdev = 0.084
  CI (99.9%): [11.250, 14.299] (assumes normal distribution)


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
# Warmup Iteration   1: 6.347 ops/ms
# Warmup Iteration   2: 10.340 ops/ms
# Warmup Iteration   3: 10.505 ops/ms
Iteration   1: 10.591 ops/ms
Iteration   2: 10.636 ops/ms
Iteration   3: 10.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.580 ±(99.9%) 1.141 ops/ms [Average]
  (min, avg, max) = (10.512, 10.580, 10.636), stdev = 0.063
  CI (99.9%): [9.438, 11.721] (assumes normal distribution)


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
# Warmup Iteration   1: 3.955 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.603 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.543 ±(99.9%) 0.004 ms/op
Iteration   1: 2.493 ±(99.9%) 0.004 ms/op
Iteration   2: 2.539 ±(99.9%) 0.004 ms/op
Iteration   3: 2.530 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.521 ±(99.9%) 0.446 ms/op [Average]
  (min, avg, max) = (2.493, 2.521, 2.539), stdev = 0.024
  CI (99.9%): [2.074, 2.967] (assumes normal distribution)


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
# Warmup Iteration   1: 3.651 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.460 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.432 ±(99.9%) 0.003 ms/op
Iteration   1: 2.466 ±(99.9%) 0.004 ms/op
Iteration   2: 2.436 ±(99.9%) 0.004 ms/op
Iteration   3: 2.462 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.454 ±(99.9%) 0.291 ms/op [Average]
  (min, avg, max) = (2.436, 2.454, 2.466), stdev = 0.016
  CI (99.9%): [2.164, 2.745] (assumes normal distribution)


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
# Warmup Iteration   1: 3.859 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.581 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.004 ms/op
Iteration   1: 2.512 ±(99.9%) 0.004 ms/op
Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
Iteration   3: 2.486 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.500 ±(99.9%) 0.237 ms/op [Average]
  (min, avg, max) = (2.486, 2.500, 2.512), stdev = 0.013
  CI (99.9%): [2.263, 2.737] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.616 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.005 ms/op
Iteration   1: 3.020 ±(99.9%) 0.007 ms/op
Iteration   2: 3.050 ±(99.9%) 0.007 ms/op
Iteration   3: 2.998 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.023 ±(99.9%) 0.475 ms/op [Average]
  (min, avg, max) = (2.998, 3.023, 3.050), stdev = 0.026
  CI (99.9%): [2.548, 3.498] (assumes normal distribution)


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
# Warmup Iteration   1: 4.082 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.631 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.006 ms/op
Iteration   1: 2.558 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.018 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.924 ms/op
                 createUser·p0.999:  11.010 ms/op
                 createUser·p0.9999: 16.376 ms/op
                 createUser·p1.00:   17.662 ms/op

Iteration   2: 2.553 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.866 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.826 ms/op
                 createUser·p0.999:  9.178 ms/op
                 createUser·p0.9999: 12.435 ms/op
                 createUser·p1.00:   13.566 ms/op

Iteration   3: 2.583 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.146 ms/op
                 createUser·p0.95:   3.301 ms/op
                 createUser·p0.99:   4.100 ms/op
                 createUser·p0.999:  9.729 ms/op
                 createUser·p0.9999: 11.583 ms/op
                 createUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374017
  mean =      2.565 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 178371 
    [ 2.500,  3.750) = 190420 
    [ 3.750,  5.000) = 3987 
    [ 5.000,  6.250) = 715 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 128 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      2.634 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      3.961 ms/op
     p(99.9000) =      9.683 ms/op
     p(99.9900) =     15.397 ms/op
     p(99.9990) =     17.531 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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
# Warmup Iteration   1: 3.736 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.506 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.454 ±(99.9%) 0.006 ms/op
Iteration   1: 2.456 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.868 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.707 ms/op
                 existUser·p0.999:  6.602 ms/op
                 existUser·p0.9999: 16.449 ms/op
                 existUser·p1.00:   17.236 ms/op

Iteration   2: 2.472 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.914 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.985 ms/op
                 existUser·p0.999:  7.346 ms/op
                 existUser·p0.9999: 13.272 ms/op
                 existUser·p1.00:   15.892 ms/op

Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.122 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.661 ms/op
                 existUser·p0.999:  7.253 ms/op
                 existUser·p0.9999: 13.238 ms/op
                 existUser·p1.00:   13.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389603
  mean =      2.462 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 191112 
    [ 2.500,  3.750) = 194509 
    [ 3.750,  5.000) = 3083 
    [ 5.000,  6.250) = 453 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 104 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.756 ms/op
     p(99.9000) =      7.032 ms/op
     p(99.9900) =     15.766 ms/op
     p(99.9990) =     17.236 ms/op
     p(99.9999) =     17.236 ms/op
    p(100.0000) =     17.236 ms/op


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
# Warmup Iteration   1: 3.688 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.569 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.006 ms/op
Iteration   1: 2.494 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.957 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.990 ms/op
                 getUser·p0.999:  11.070 ms/op
                 getUser·p0.9999: 16.223 ms/op
                 getUser·p1.00:   17.859 ms/op

Iteration   2: 2.498 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.969 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.117 ms/op
                 getUser·p0.999:  9.880 ms/op
                 getUser·p0.9999: 14.660 ms/op
                 getUser·p1.00:   15.073 ms/op

Iteration   3: 2.510 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.951 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.891 ms/op
                 getUser·p0.999:  8.274 ms/op
                 getUser·p0.9999: 11.007 ms/op
                 getUser·p1.00:   11.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383559
  mean =      2.501 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 89 
    [ 1.250,  2.500) = 190253 
    [ 2.500,  3.750) = 186431 
    [ 3.750,  5.000) = 5066 
    [ 5.000,  6.250) = 1032 
    [ 6.250,  7.500) = 232 
    [ 7.500,  8.750) = 80 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      8.274 ms/op
     p(99.9900) =     14.936 ms/op
     p(99.9990) =     17.476 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


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
# Warmup Iteration   1: 4.836 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.009 ms/op
Iteration   1: 3.070 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.852 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   5.833 ms/op
                 listUser·p0.999:  9.206 ms/op
                 listUser·p0.9999: 11.186 ms/op
                 listUser·p1.00:   13.058 ms/op

Iteration   2: 3.053 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.930 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.287 ms/op
                 listUser·p0.9999: 11.806 ms/op
                 listUser·p1.00:   12.091 ms/op

Iteration   3: 3.023 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.957 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.118 ms/op
                 listUser·p0.9999: 10.493 ms/op
                 listUser·p1.00:   11.174 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314575
  mean =      3.049 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 119 
    [ 1.250,  2.500) = 84907 
    [ 2.500,  3.750) = 188036 
    [ 3.750,  5.000) = 33917 
    [ 5.000,  6.250) = 6160 
    [ 6.250,  7.500) = 803 
    [ 7.500,  8.750) = 204 
    [ 8.750, 10.000) = 233 
    [10.000, 11.250) = 156 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.852 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =      9.175 ms/op
     p(99.9900) =     11.363 ms/op
     p(99.9990) =     12.091 ms/op
     p(99.9999) =     13.058 ms/op
    p(100.0000) =     13.058 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.560 ± 3.347  ops/ms
ClientPb.existUser                       thrpt       3  13.021 ± 0.635  ops/ms
ClientPb.getUser                         thrpt       3  12.775 ± 1.524  ops/ms
ClientPb.listUser                        thrpt       3  10.580 ± 1.141  ops/ms
ClientPb.createUser                       avgt       3   2.521 ± 0.446   ms/op
ClientPb.existUser                        avgt       3   2.454 ± 0.291   ms/op
ClientPb.getUser                          avgt       3   2.500 ± 0.237   ms/op
ClientPb.listUser                         avgt       3   3.023 ± 0.475   ms/op
ClientPb.createUser                     sample  374017   2.565 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.866           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.634           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.236           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.961           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.683           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.397           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.662           ms/op
ClientPb.existUser                      sample  389603   2.462 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.868           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.032           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.766           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.236           ms/op
ClientPb.getUser                        sample  383559   2.501 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.951           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.215           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.243           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.274           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.936           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.859           ms/op
ClientPb.listUser                       sample  314575   3.049 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.852           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.982           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.932           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.685           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.175           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.363           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.058           ms/op
