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
# Warmup Iteration   1: 4.984 ops/ms
# Warmup Iteration   2: 11.980 ops/ms
# Warmup Iteration   3: 12.370 ops/ms
Iteration   1: 12.514 ops/ms
Iteration   2: 12.421 ops/ms
Iteration   3: 12.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.528 ±(99.9%) 2.110 ops/ms [Average]
  (min, avg, max) = (12.421, 12.528, 12.650), stdev = 0.116
  CI (99.9%): [10.419, 14.638] (assumes normal distribution)


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
# Warmup Iteration   1: 8.157 ops/ms
# Warmup Iteration   2: 13.038 ops/ms
# Warmup Iteration   3: 12.904 ops/ms
Iteration   1: 13.058 ops/ms
Iteration   2: 13.049 ops/ms
Iteration   3: 12.967 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.025 ±(99.9%) 0.910 ops/ms [Average]
  (min, avg, max) = (12.967, 13.025, 13.058), stdev = 0.050
  CI (99.9%): [12.114, 13.935] (assumes normal distribution)


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
# Warmup Iteration   1: 8.024 ops/ms
# Warmup Iteration   2: 12.458 ops/ms
# Warmup Iteration   3: 12.731 ops/ms
Iteration   1: 12.934 ops/ms
Iteration   2: 12.943 ops/ms
Iteration   3: 12.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.853 ±(99.9%) 2.689 ops/ms [Average]
  (min, avg, max) = (12.683, 12.853, 12.943), stdev = 0.147
  CI (99.9%): [10.164, 15.542] (assumes normal distribution)


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
# Warmup Iteration   1: 6.293 ops/ms
# Warmup Iteration   2: 10.359 ops/ms
# Warmup Iteration   3: 10.456 ops/ms
Iteration   1: 10.396 ops/ms
Iteration   2: 10.598 ops/ms
Iteration   3: 10.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.518 ±(99.9%) 1.957 ops/ms [Average]
  (min, avg, max) = (10.396, 10.518, 10.598), stdev = 0.107
  CI (99.9%): [8.561, 12.474] (assumes normal distribution)


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
# Warmup Iteration   1: 4.217 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.621 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.534 ±(99.9%) 0.003 ms/op
Iteration   1: 2.533 ±(99.9%) 0.003 ms/op
Iteration   2: 2.596 ±(99.9%) 0.004 ms/op
Iteration   3: 2.519 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.549 ±(99.9%) 0.746 ms/op [Average]
  (min, avg, max) = (2.519, 2.549, 2.596), stdev = 0.041
  CI (99.9%): [1.803, 3.295] (assumes normal distribution)


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
# Warmup Iteration   1: 3.671 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.454 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.461 ±(99.9%) 0.004 ms/op
Iteration   1: 2.453 ±(99.9%) 0.004 ms/op
Iteration   2: 2.461 ±(99.9%) 0.004 ms/op
Iteration   3: 2.459 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.457 ±(99.9%) 0.079 ms/op [Average]
  (min, avg, max) = (2.453, 2.457, 2.461), stdev = 0.004
  CI (99.9%): [2.378, 2.536] (assumes normal distribution)


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
# Warmup Iteration   1: 4.025 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.558 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.004 ms/op
Iteration   1: 2.502 ±(99.9%) 0.004 ms/op
Iteration   2: 2.526 ±(99.9%) 0.004 ms/op
Iteration   3: 2.515 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.514 ±(99.9%) 0.221 ms/op [Average]
  (min, avg, max) = (2.502, 2.514, 2.526), stdev = 0.012
  CI (99.9%): [2.293, 2.735] (assumes normal distribution)


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
# Warmup Iteration   1: 4.591 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.033 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.005 ms/op
Iteration   1: 3.039 ±(99.9%) 0.005 ms/op
Iteration   2: 3.049 ±(99.9%) 0.005 ms/op
Iteration   3: 3.025 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.038 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (3.025, 3.038, 3.049), stdev = 0.012
  CI (99.9%): [2.815, 3.261] (assumes normal distribution)


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
# Warmup Iteration   1: 4.101 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.697 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.006 ms/op
Iteration   1: 2.533 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.888 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.768 ms/op
                 createUser·p0.999:  11.154 ms/op
                 createUser·p0.9999: 13.402 ms/op
                 createUser·p1.00:   13.894 ms/op

Iteration   2: 2.525 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.049 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.658 ms/op
                 createUser·p0.999:  9.454 ms/op
                 createUser·p0.9999: 12.472 ms/op
                 createUser·p1.00:   13.386 ms/op

Iteration   3: 2.551 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.845 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   3.895 ms/op
                 createUser·p0.999:  8.658 ms/op
                 createUser·p0.9999: 10.944 ms/op
                 createUser·p1.00:   13.468 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378057
  mean =      2.537 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 178980 
    [ 2.500,  3.750) = 195078 
    [ 3.750,  5.000) = 3254 
    [ 5.000,  6.250) = 239 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      2.617 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.772 ms/op
     p(99.9000) =      8.667 ms/op
     p(99.9900) =     13.238 ms/op
     p(99.9990) =     13.757 ms/op
     p(99.9999) =     13.894 ms/op
    p(100.0000) =     13.894 ms/op


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
# Warmup Iteration   1: 3.779 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.491 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
Iteration   1: 2.464 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.947 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.465 ms/op
                 existUser·p0.999:  6.473 ms/op
                 existUser·p0.9999: 13.943 ms/op
                 existUser·p1.00:   14.860 ms/op

Iteration   2: 2.452 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.879 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.490 ms/op
                 existUser·p0.999:  7.604 ms/op
                 existUser·p0.9999: 12.631 ms/op
                 existUser·p1.00:   14.303 ms/op

Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.891 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.674 ms/op
                 existUser·p0.999:  6.411 ms/op
                 existUser·p0.9999: 11.388 ms/op
                 existUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389924
  mean =      2.460 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 190417 
    [ 2.500,  3.750) = 196640 
    [ 3.750,  5.000) = 2147 
    [ 5.000,  6.250) = 257 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.551 ms/op
     p(99.9000) =      6.677 ms/op
     p(99.9900) =     13.239 ms/op
     p(99.9990) =     14.782 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


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
# Warmup Iteration   1: 4.019 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.575 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.006 ms/op
Iteration   1: 2.481 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.954 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.686 ms/op
                 getUser·p0.999:  9.272 ms/op
                 getUser·p0.9999: 16.695 ms/op
                 getUser·p1.00:   17.039 ms/op

Iteration   2: 2.490 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.952 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.875 ms/op
                 getUser·p0.999:  6.698 ms/op
                 getUser·p0.9999: 22.555 ms/op
                 getUser·p1.00:   23.462 ms/op

Iteration   3: 2.485 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.924 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.645 ms/op
                 getUser·p0.999:  7.713 ms/op
                 getUser·p0.9999: 15.761 ms/op
                 getUser·p1.00:   15.876 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385989
  mean =      2.486 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 192983 
    [ 2.500,  5.000) = 191918 
    [ 5.000,  7.500) = 698 
    [ 7.500, 10.000) = 109 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.924 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.727 ms/op
     p(99.9000) =      7.512 ms/op
     p(99.9900) =     16.823 ms/op
     p(99.9990) =     23.204 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


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
# Warmup Iteration   1: 4.787 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.009 ms/op
Iteration   1: 3.054 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.974 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.257 ms/op
                 listUser·p0.9999: 11.627 ms/op
                 listUser·p1.00:   13.844 ms/op

Iteration   2: 3.051 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.866 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.775 ms/op
                 listUser·p0.999:  9.617 ms/op
                 listUser·p0.9999: 11.059 ms/op
                 listUser·p1.00:   12.108 ms/op

Iteration   3: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.965 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.617 ms/op
                 listUser·p0.9999: 11.198 ms/op
                 listUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315072
  mean =      3.044 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 94 
    [ 1.250,  2.500) = 87436 
    [ 2.500,  3.750) = 186642 
    [ 3.750,  5.000) = 33061 
    [ 5.000,  6.250) = 6442 
    [ 6.250,  7.500) = 730 
    [ 7.500,  8.750) = 192 
    [ 8.750, 10.000) = 285 
    [10.000, 11.250) = 171 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =      9.519 ms/op
     p(99.9900) =     11.108 ms/op
     p(99.9990) =     13.311 ms/op
     p(99.9999) =     13.844 ms/op
    p(100.0000) =     13.844 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.528 ± 2.110  ops/ms
ClientPb.existUser                       thrpt       3  13.025 ± 0.910  ops/ms
ClientPb.getUser                         thrpt       3  12.853 ± 2.689  ops/ms
ClientPb.listUser                        thrpt       3  10.518 ± 1.957  ops/ms
ClientPb.createUser                       avgt       3   2.549 ± 0.746   ms/op
ClientPb.existUser                        avgt       3   2.457 ± 0.079   ms/op
ClientPb.getUser                          avgt       3   2.514 ± 0.221   ms/op
ClientPb.listUser                         avgt       3   3.038 ± 0.223   ms/op
ClientPb.createUser                     sample  378057   2.537 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.845           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.617           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.772           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.667           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.238           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.894           ms/op
ClientPb.existUser                      sample  389924   2.460 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.879           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.564           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.551           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.677           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.239           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.860           ms/op
ClientPb.getUser                        sample  385989   2.486 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.924           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.727           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.512           ms/op
ClientPb.getUser:getUser·p0.9999        sample          16.823           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.462           ms/op
ClientPb.listUser                       sample  315072   3.044 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.866           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.982           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.677           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.519           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.108           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.844           ms/op
