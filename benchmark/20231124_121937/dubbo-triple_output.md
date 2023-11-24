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
# Warmup Iteration   1: 4.828 ops/ms
# Warmup Iteration   2: 11.821 ops/ms
# Warmup Iteration   3: 11.991 ops/ms
Iteration   1: 12.253 ops/ms
Iteration   2: 12.485 ops/ms
Iteration   3: 12.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.431 ±(99.9%) 2.873 ops/ms [Average]
  (min, avg, max) = (12.253, 12.431, 12.554), stdev = 0.158
  CI (99.9%): [9.557, 15.304] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 7.951 ops/ms
# Warmup Iteration   2: 13.143 ops/ms
# Warmup Iteration   3: 13.132 ops/ms
Iteration   1: 13.337 ops/ms
Iteration   2: 13.025 ops/ms
Iteration   3: 13.006 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.123 ±(99.9%) 3.393 ops/ms [Average]
  (min, avg, max) = (13.006, 13.123, 13.337), stdev = 0.186
  CI (99.9%): [9.730, 16.516] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.492 ops/ms
# Warmup Iteration   2: 12.563 ops/ms
# Warmup Iteration   3: 12.846 ops/ms
Iteration   1: 12.612 ops/ms
Iteration   2: 12.848 ops/ms
Iteration   3: 12.917 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.792 ±(99.9%) 2.923 ops/ms [Average]
  (min, avg, max) = (12.612, 12.792, 12.917), stdev = 0.160
  CI (99.9%): [9.869, 15.716] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 6.424 ops/ms
# Warmup Iteration   2: 10.444 ops/ms
# Warmup Iteration   3: 10.645 ops/ms
Iteration   1: 10.628 ops/ms
Iteration   2: 10.619 ops/ms
Iteration   3: 10.735 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.661 ±(99.9%) 1.173 ops/ms [Average]
  (min, avg, max) = (10.619, 10.661, 10.735), stdev = 0.064
  CI (99.9%): [9.488, 11.834] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.957 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.591 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.004 ms/op
Iteration   1: 2.563 ±(99.9%) 0.004 ms/op
Iteration   2: 2.531 ±(99.9%) 0.003 ms/op
Iteration   3: 2.535 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.543 ±(99.9%) 0.321 ms/op [Average]
  (min, avg, max) = (2.531, 2.543, 2.563), stdev = 0.018
  CI (99.9%): [2.222, 2.864] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.917 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.440 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.438 ±(99.9%) 0.004 ms/op
Iteration   1: 2.438 ±(99.9%) 0.004 ms/op
Iteration   2: 2.428 ±(99.9%) 0.003 ms/op
Iteration   3: 2.433 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.433 ±(99.9%) 0.093 ms/op [Average]
  (min, avg, max) = (2.428, 2.433, 2.438), stdev = 0.005
  CI (99.9%): [2.340, 2.526] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.043 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.530 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.004 ms/op
Iteration   1: 2.464 ±(99.9%) 0.004 ms/op
Iteration   2: 2.459 ±(99.9%) 0.005 ms/op
Iteration   3: 2.444 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.456 ±(99.9%) 0.191 ms/op [Average]
  (min, avg, max) = (2.444, 2.456, 2.464), stdev = 0.010
  CI (99.9%): [2.264, 2.647] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.676 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.005 ms/op
Iteration   1: 2.983 ±(99.9%) 0.005 ms/op
Iteration   2: 3.004 ±(99.9%) 0.006 ms/op
Iteration   3: 3.058 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.015 ±(99.9%) 0.706 ms/op [Average]
  (min, avg, max) = (2.983, 3.015, 3.058), stdev = 0.039
  CI (99.9%): [2.309, 3.721] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.100 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.561 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
Iteration   1: 2.477 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.942 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.909 ms/op
                 createUser·p0.999:  6.658 ms/op
                 createUser·p0.9999: 13.631 ms/op
                 createUser·p1.00:   14.254 ms/op

Iteration   2: 2.479 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.982 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.658 ms/op
                 createUser·p0.999:  6.040 ms/op
                 createUser·p0.9999: 11.946 ms/op
                 createUser·p1.00:   12.419 ms/op

Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.943 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.990 ms/op
                 createUser·p0.999:  8.675 ms/op
                 createUser·p0.9999: 10.699 ms/op
                 createUser·p1.00:   10.994 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385773
  mean =      2.486 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 188741 
    [ 2.500,  3.750) = 192415 
    [ 3.750,  5.000) = 3695 
    [ 5.000,  6.250) = 427 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 97 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.942 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.850 ms/op
     p(99.9000) =      8.609 ms/op
     p(99.9900) =     13.140 ms/op
     p(99.9990) =     13.947 ms/op
     p(99.9999) =     14.254 ms/op
    p(100.0000) =     14.254 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.708 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.473 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
Iteration   1: 2.469 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.918 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.633 ms/op
                 existUser·p0.999:  5.775 ms/op
                 existUser·p0.9999: 19.235 ms/op
                 existUser·p1.00:   19.530 ms/op

Iteration   2: 2.486 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.986 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.940 ms/op
                 existUser·p0.999:  7.402 ms/op
                 existUser·p0.9999: 14.256 ms/op
                 existUser·p1.00:   14.582 ms/op

Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.921 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.572 ms/op
                 existUser·p0.999:  7.670 ms/op
                 existUser·p0.9999: 12.731 ms/op
                 existUser·p1.00:   13.058 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387696
  mean =      2.474 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 194537 
    [ 2.500,  3.750) = 189419 
    [ 3.750,  5.000) = 2806 
    [ 5.000,  6.250) = 452 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 42 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.918 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.711 ms/op
     p(99.9000) =      7.449 ms/op
     p(99.9900) =     14.360 ms/op
     p(99.9990) =     19.333 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.821 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.628 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.006 ms/op
Iteration   1: 2.511 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.004 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.842 ms/op
                 getUser·p0.999:  10.027 ms/op
                 getUser·p0.9999: 13.947 ms/op
                 getUser·p1.00:   14.500 ms/op

Iteration   2: 2.541 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.049 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.297 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.300 ms/op
                 getUser·p0.9999: 12.468 ms/op
                 getUser·p1.00:   13.287 ms/op

Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.987 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.686 ms/op
                 getUser·p0.999:  5.734 ms/op
                 getUser·p0.9999: 11.095 ms/op
                 getUser·p1.00:   11.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381309
  mean =      2.516 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 187631 
    [ 2.500,  3.750) = 188235 
    [ 3.750,  5.000) = 4403 
    [ 5.000,  6.250) = 604 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 123 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.987 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.969 ms/op
     p(99.9000) =      6.234 ms/op
     p(99.9900) =     13.138 ms/op
     p(99.9990) =     14.260 ms/op
     p(99.9999) =     14.500 ms/op
    p(100.0000) =     14.500 ms/op


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
# Warmup Iteration   1: 4.608 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.009 ms/op
Iteration   1: 3.032 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.955 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.290 ms/op
                 listUser·p0.9999: 11.517 ms/op
                 listUser·p1.00:   11.993 ms/op

Iteration   2: 3.006 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.894 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 12.300 ms/op
                 listUser·p1.00:   12.763 ms/op

Iteration   3: 2.989 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.916 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  9.012 ms/op
                 listUser·p0.9999: 13.964 ms/op
                 listUser·p1.00:   14.828 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318750
  mean =      3.009 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 97 
    [ 1.250,  2.500) = 95504 
    [ 2.500,  3.750) = 184134 
    [ 3.750,  5.000) = 31766 
    [ 5.000,  6.250) = 5795 
    [ 6.250,  7.500) = 783 
    [ 7.500,  8.750) = 273 
    [ 8.750, 10.000) = 172 
    [10.000, 11.250) = 142 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.894 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.191 ms/op
     p(99.9900) =     13.502 ms/op
     p(99.9990) =     14.708 ms/op
     p(99.9999) =     14.828 ms/op
    p(100.0000) =     14.828 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.431 ± 2.873  ops/ms
ClientPb.existUser                       thrpt       3  13.123 ± 3.393  ops/ms
ClientPb.getUser                         thrpt       3  12.792 ± 2.923  ops/ms
ClientPb.listUser                        thrpt       3  10.661 ± 1.173  ops/ms
ClientPb.createUser                       avgt       3   2.543 ± 0.321   ms/op
ClientPb.existUser                        avgt       3   2.433 ± 0.093   ms/op
ClientPb.getUser                          avgt       3   2.456 ± 0.191   ms/op
ClientPb.listUser                         avgt       3   3.015 ± 0.706   ms/op
ClientPb.createUser                     sample  385773   2.486 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.942           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.540           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.019           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.850           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.609           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.140           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.254           ms/op
ClientPb.existUser                      sample  387696   2.474 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.918           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.711           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.449           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.360           ms/op
ClientPb.existUser:existUser·p1.00      sample          19.530           ms/op
ClientPb.getUser                        sample  381309   2.516 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.987           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.969           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.234           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.138           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.500           ms/op
ClientPb.listUser                       sample  318750   3.009 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.894           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.191           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.502           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.828           ms/op
