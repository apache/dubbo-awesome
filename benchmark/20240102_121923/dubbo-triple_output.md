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
# Warmup Iteration   1: 5.056 ops/ms
# Warmup Iteration   2: 11.944 ops/ms
# Warmup Iteration   3: 12.332 ops/ms
Iteration   1: 12.569 ops/ms
Iteration   2: 12.535 ops/ms
Iteration   3: 12.703 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.602 ±(99.9%) 1.619 ops/ms [Average]
  (min, avg, max) = (12.535, 12.602, 12.703), stdev = 0.089
  CI (99.9%): [10.983, 14.221] (assumes normal distribution)


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
# Warmup Iteration   1: 7.940 ops/ms
# Warmup Iteration   2: 12.965 ops/ms
# Warmup Iteration   3: 12.962 ops/ms
Iteration   1: 12.954 ops/ms
Iteration   2: 13.086 ops/ms
Iteration   3: 12.959 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.999 ±(99.9%) 1.364 ops/ms [Average]
  (min, avg, max) = (12.954, 12.999, 13.086), stdev = 0.075
  CI (99.9%): [11.635, 14.363] (assumes normal distribution)


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
# Warmup Iteration   1: 7.759 ops/ms
# Warmup Iteration   2: 12.350 ops/ms
# Warmup Iteration   3: 12.809 ops/ms
Iteration   1: 12.887 ops/ms
Iteration   2: 12.775 ops/ms
Iteration   3: 12.665 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.776 ±(99.9%) 2.027 ops/ms [Average]
  (min, avg, max) = (12.665, 12.776, 12.887), stdev = 0.111
  CI (99.9%): [10.749, 14.803] (assumes normal distribution)


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
# Warmup Iteration   1: 6.725 ops/ms
# Warmup Iteration   2: 10.391 ops/ms
# Warmup Iteration   3: 10.476 ops/ms
Iteration   1: 10.530 ops/ms
Iteration   2: 10.525 ops/ms
Iteration   3: 10.487 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.514 ±(99.9%) 0.432 ops/ms [Average]
  (min, avg, max) = (10.487, 10.514, 10.530), stdev = 0.024
  CI (99.9%): [10.082, 10.946] (assumes normal distribution)


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
# Warmup Iteration   1: 4.081 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.661 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.570 ±(99.9%) 0.004 ms/op
Iteration   1: 2.568 ±(99.9%) 0.005 ms/op
Iteration   2: 2.536 ±(99.9%) 0.004 ms/op
Iteration   3: 2.510 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.538 ±(99.9%) 0.528 ms/op [Average]
  (min, avg, max) = (2.510, 2.538, 2.568), stdev = 0.029
  CI (99.9%): [2.010, 3.067] (assumes normal distribution)


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
# Warmup Iteration   1: 3.852 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.489 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.004 ms/op
Iteration   1: 2.479 ±(99.9%) 0.004 ms/op
Iteration   2: 2.486 ±(99.9%) 0.004 ms/op
Iteration   3: 2.451 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.472 ±(99.9%) 0.339 ms/op [Average]
  (min, avg, max) = (2.451, 2.472, 2.486), stdev = 0.019
  CI (99.9%): [2.133, 2.811] (assumes normal distribution)


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
# Warmup Iteration   1: 3.720 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.525 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.004 ms/op
Iteration   1: 2.517 ±(99.9%) 0.004 ms/op
Iteration   2: 2.467 ±(99.9%) 0.004 ms/op
Iteration   3: 2.470 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.484 ±(99.9%) 0.511 ms/op [Average]
  (min, avg, max) = (2.467, 2.484, 2.517), stdev = 0.028
  CI (99.9%): [1.973, 2.996] (assumes normal distribution)


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
# Warmup Iteration   1: 4.575 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.014 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.005 ms/op
Iteration   1: 3.002 ±(99.9%) 0.006 ms/op
Iteration   2: 2.987 ±(99.9%) 0.005 ms/op
Iteration   3: 2.983 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.991 ±(99.9%) 0.186 ms/op [Average]
  (min, avg, max) = (2.983, 2.991, 3.002), stdev = 0.010
  CI (99.9%): [2.804, 3.177] (assumes normal distribution)


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
# Warmup Iteration   1: 4.206 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.686 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.573 ±(99.9%) 0.006 ms/op
Iteration   1: 2.534 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.790 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.695 ms/op
                 createUser·p0.999:  11.649 ms/op
                 createUser·p0.9999: 13.474 ms/op
                 createUser·p1.00:   14.041 ms/op

Iteration   2: 2.506 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.924 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.617 ms/op
                 createUser·p0.999:  9.902 ms/op
                 createUser·p0.9999: 13.459 ms/op
                 createUser·p1.00:   14.533 ms/op

Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.011 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.858 ms/op
                 createUser·p0.999:  8.068 ms/op
                 createUser·p0.9999: 11.878 ms/op
                 createUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381242
  mean =      2.516 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 184004 
    [ 2.500,  3.750) = 193541 
    [ 3.750,  5.000) = 2843 
    [ 5.000,  6.250) = 397 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 109 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 108 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.790 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.727 ms/op
     p(99.9000) =      8.305 ms/op
     p(99.9900) =     13.353 ms/op
     p(99.9990) =     14.377 ms/op
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
# Warmup Iteration   1: 3.875 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.467 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
Iteration   1: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.894 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  5.602 ms/op
                 existUser·p0.9999: 15.138 ms/op
                 existUser·p1.00:   15.761 ms/op

Iteration   2: 2.440 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.971 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.707 ms/op
                 existUser·p0.999:  6.439 ms/op
                 existUser·p0.9999: 13.366 ms/op
                 existUser·p1.00:   14.123 ms/op

Iteration   3: 2.439 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.905 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.875 ms/op
                 existUser·p0.999:  8.945 ms/op
                 existUser·p0.9999: 11.598 ms/op
                 existUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392528
  mean =      2.443 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 197250 
    [ 2.500,  3.750) = 191525 
    [ 3.750,  5.000) = 2995 
    [ 5.000,  6.250) = 251 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 109 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.894 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.715 ms/op
     p(99.9000) =      8.929 ms/op
     p(99.9900) =     14.434 ms/op
     p(99.9990) =     15.713 ms/op
     p(99.9999) =     15.761 ms/op
    p(100.0000) =     15.761 ms/op


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
# Warmup Iteration   1: 3.908 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.624 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.566 ±(99.9%) 0.007 ms/op
Iteration   1: 2.522 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.716 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.641 ms/op
                 getUser·p0.999:  11.872 ms/op
                 getUser·p0.9999: 17.749 ms/op
                 getUser·p1.00:   19.497 ms/op

Iteration   2: 2.531 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.623 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  9.863 ms/op
                 getUser·p0.9999: 13.709 ms/op
                 getUser·p1.00:   14.877 ms/op

Iteration   3: 2.526 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.968 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   4.071 ms/op
                 getUser·p0.999:  9.346 ms/op
                 getUser·p0.9999: 12.949 ms/op
                 getUser·p1.00:   13.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379713
  mean =      2.526 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 185428 
    [ 2.500,  3.750) = 189017 
    [ 3.750,  5.000) = 3879 
    [ 5.000,  6.250) = 819 
    [ 6.250,  7.500) = 104 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.977 ms/op
     p(99.9000) =      9.503 ms/op
     p(99.9900) =     16.302 ms/op
     p(99.9990) =     19.288 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


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
# Warmup Iteration   1: 4.728 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.009 ms/op
Iteration   1: 2.997 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.814 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  9.830 ms/op
                 listUser·p0.9999: 11.289 ms/op
                 listUser·p1.00:   11.715 ms/op

Iteration   2: 2.999 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.854 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.423 ms/op
                 listUser·p0.999:  8.788 ms/op
                 listUser·p0.9999: 11.436 ms/op
                 listUser·p1.00:   12.124 ms/op

Iteration   3: 2.982 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.728 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.614 ms/op
                 listUser·p0.9999: 12.852 ms/op
                 listUser·p1.00:   14.139 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320484
  mean =      2.993 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 139 
    [ 1.250,  2.500) = 95877 
    [ 2.500,  3.750) = 186192 
    [ 3.750,  5.000) = 31202 
    [ 5.000,  6.250) = 5789 
    [ 6.250,  7.500) = 567 
    [ 7.500,  8.750) = 225 
    [ 8.750, 10.000) = 266 
    [10.000, 11.250) = 149 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.503 ms/op
     p(99.9900) =     12.075 ms/op
     p(99.9990) =     13.080 ms/op
     p(99.9999) =     14.139 ms/op
    p(100.0000) =     14.139 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.602 ± 1.619  ops/ms
ClientPb.existUser                       thrpt       3  12.999 ± 1.364  ops/ms
ClientPb.getUser                         thrpt       3  12.776 ± 2.027  ops/ms
ClientPb.listUser                        thrpt       3  10.514 ± 0.432  ops/ms
ClientPb.createUser                       avgt       3   2.538 ± 0.528   ms/op
ClientPb.existUser                        avgt       3   2.472 ± 0.339   ms/op
ClientPb.getUser                          avgt       3   2.484 ± 0.511   ms/op
ClientPb.listUser                         avgt       3   2.991 ± 0.186   ms/op
ClientPb.createUser                     sample  381242   2.516 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.790           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.572           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.727           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.305           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.353           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.533           ms/op
ClientPb.existUser                      sample  392528   2.443 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.894           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.715           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.929           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.434           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.761           ms/op
ClientPb.getUser                        sample  379713   2.526 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.623           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.564           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.503           ms/op
ClientPb.getUser:getUser·p0.9999        sample          16.302           ms/op
ClientPb.getUser:getUser·p1.00          sample          19.497           ms/op
ClientPb.listUser                       sample  320484   2.993 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.728           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.929           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.867           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.503           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.075           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.139           ms/op
