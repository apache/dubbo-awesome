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
# Warmup Iteration   1: 4.867 ops/ms
# Warmup Iteration   2: 12.101 ops/ms
# Warmup Iteration   3: 12.255 ops/ms
Iteration   1: 12.523 ops/ms
Iteration   2: 12.503 ops/ms
Iteration   3: 12.585 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.537 ±(99.9%) 0.782 ops/ms [Average]
  (min, avg, max) = (12.503, 12.537, 12.585), stdev = 0.043
  CI (99.9%): [11.755, 13.319] (assumes normal distribution)


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
# Warmup Iteration   1: 8.587 ops/ms
# Warmup Iteration   2: 12.950 ops/ms
# Warmup Iteration   3: 12.910 ops/ms
Iteration   1: 12.983 ops/ms
Iteration   2: 12.871 ops/ms
Iteration   3: 13.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.961 ±(99.9%) 1.491 ops/ms [Average]
  (min, avg, max) = (12.871, 12.961, 13.030), stdev = 0.082
  CI (99.9%): [11.470, 14.452] (assumes normal distribution)


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
# Warmup Iteration   1: 8.241 ops/ms
# Warmup Iteration   2: 12.414 ops/ms
# Warmup Iteration   3: 12.603 ops/ms
Iteration   1: 12.622 ops/ms
Iteration   2: 12.686 ops/ms
Iteration   3: 12.504 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.604 ±(99.9%) 1.684 ops/ms [Average]
  (min, avg, max) = (12.504, 12.604, 12.686), stdev = 0.092
  CI (99.9%): [10.920, 14.288] (assumes normal distribution)


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
# Warmup Iteration   1: 6.468 ops/ms
# Warmup Iteration   2: 10.359 ops/ms
# Warmup Iteration   3: 10.638 ops/ms
Iteration   1: 10.568 ops/ms
Iteration   2: 10.702 ops/ms
Iteration   3: 10.556 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.609 ±(99.9%) 1.473 ops/ms [Average]
  (min, avg, max) = (10.556, 10.609, 10.702), stdev = 0.081
  CI (99.9%): [9.136, 12.082] (assumes normal distribution)


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
# Warmup Iteration   1: 4.181 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.603 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.003 ms/op
Iteration   1: 2.546 ±(99.9%) 0.004 ms/op
Iteration   2: 2.556 ±(99.9%) 0.004 ms/op
Iteration   3: 2.564 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.555 ±(99.9%) 0.169 ms/op [Average]
  (min, avg, max) = (2.546, 2.555, 2.564), stdev = 0.009
  CI (99.9%): [2.386, 2.724] (assumes normal distribution)


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
# Warmup Iteration   1: 3.629 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.509 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.003 ms/op
Iteration   1: 2.470 ±(99.9%) 0.003 ms/op
Iteration   2: 2.479 ±(99.9%) 0.004 ms/op
Iteration   3: 2.510 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.486 ±(99.9%) 0.379 ms/op [Average]
  (min, avg, max) = (2.470, 2.486, 2.510), stdev = 0.021
  CI (99.9%): [2.107, 2.865] (assumes normal distribution)


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
# Warmup Iteration   1: 3.887 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.005 ms/op
Iteration   1: 2.504 ±(99.9%) 0.004 ms/op
Iteration   2: 2.528 ±(99.9%) 0.003 ms/op
Iteration   3: 2.523 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.519 ±(99.9%) 0.228 ms/op [Average]
  (min, avg, max) = (2.504, 2.519, 2.528), stdev = 0.012
  CI (99.9%): [2.291, 2.746] (assumes normal distribution)


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
# Warmup Iteration   1: 4.620 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.008 ms/op
Iteration   1: 2.998 ±(99.9%) 0.005 ms/op
Iteration   2: 2.999 ±(99.9%) 0.005 ms/op
Iteration   3: 3.025 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.008 ±(99.9%) 0.283 ms/op [Average]
  (min, avg, max) = (2.998, 3.008, 3.025), stdev = 0.016
  CI (99.9%): [2.724, 3.291] (assumes normal distribution)


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
# Warmup Iteration   1: 4.079 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.688 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.006 ms/op
Iteration   1: 2.522 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.937 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.789 ms/op
                 createUser·p0.999:  11.587 ms/op
                 createUser·p0.9999: 13.915 ms/op
                 createUser·p1.00:   14.844 ms/op

Iteration   2: 2.538 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.041 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.772 ms/op
                 createUser·p0.999:  9.553 ms/op
                 createUser·p0.9999: 11.928 ms/op
                 createUser·p1.00:   12.845 ms/op

Iteration   3: 2.565 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.942 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   4.002 ms/op
                 createUser·p0.999:  8.913 ms/op
                 createUser·p0.9999: 10.898 ms/op
                 createUser·p1.00:   15.041 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377308
  mean =      2.541 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 179294 
    [ 2.500,  3.750) = 193421 
    [ 3.750,  5.000) = 3656 
    [ 5.000,  6.250) = 421 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 109 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.937 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.850 ms/op
     p(99.9000) =      9.001 ms/op
     p(99.9900) =     13.395 ms/op
     p(99.9990) =     14.749 ms/op
     p(99.9999) =     15.041 ms/op
    p(100.0000) =     15.041 ms/op


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
# Warmup Iteration   1: 3.771 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.544 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
Iteration   1: 2.494 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.876 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.609 ms/op
                 existUser·p0.999:  5.659 ms/op
                 existUser·p0.9999: 15.683 ms/op
                 existUser·p1.00:   16.122 ms/op

Iteration   2: 2.500 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.039 ms/op
                 existUser·p0.50:   2.585 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.760 ms/op
                 existUser·p0.999:  8.045 ms/op
                 existUser·p0.9999: 13.668 ms/op
                 existUser·p1.00:   14.287 ms/op

Iteration   3: 2.527 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.858 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.084 ms/op
                 existUser·p0.95:   3.203 ms/op
                 existUser·p0.99:   3.793 ms/op
                 existUser·p0.999:  8.970 ms/op
                 existUser·p0.9999: 12.534 ms/op
                 existUser·p1.00:   12.763 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 382597
  mean =      2.507 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 185618 
    [ 2.500,  3.750) = 193303 
    [ 3.750,  5.000) = 2802 
    [ 5.000,  6.250) = 406 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 116 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.858 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.719 ms/op
     p(99.9000) =      7.578 ms/op
     p(99.9900) =     14.426 ms/op
     p(99.9990) =     16.016 ms/op
     p(99.9999) =     16.122 ms/op
    p(100.0000) =     16.122 ms/op


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
# Warmup Iteration   1: 4.018 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.629 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.599 ±(99.9%) 0.007 ms/op
Iteration   1: 2.539 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.883 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   4.005 ms/op
                 getUser·p0.999:  11.815 ms/op
                 getUser·p0.9999: 13.818 ms/op
                 getUser·p1.00:   14.844 ms/op

Iteration   2: 2.552 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.974 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   3.727 ms/op
                 getUser·p0.999:  9.052 ms/op
                 getUser·p0.9999: 15.655 ms/op
                 getUser·p1.00:   16.810 ms/op

Iteration   3: 2.576 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.966 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.146 ms/op
                 getUser·p0.95:   3.310 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  9.485 ms/op
                 getUser·p0.9999: 12.698 ms/op
                 getUser·p1.00:   13.877 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 375266
  mean =      2.556 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 182441 
    [ 2.500,  3.750) = 186952 
    [ 3.750,  5.000) = 4815 
    [ 5.000,  6.250) = 599 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 109 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.265 ms/op
     p(99.0000) =      4.065 ms/op
     p(99.9000) =      9.457 ms/op
     p(99.9900) =     14.244 ms/op
     p(99.9990) =     16.302 ms/op
     p(99.9999) =     16.810 ms/op
    p(100.0000) =     16.810 ms/op


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
# Warmup Iteration   1: 4.807 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.009 ms/op
Iteration   1: 3.033 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.898 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  9.054 ms/op
                 listUser·p0.9999: 11.599 ms/op
                 listUser·p1.00:   12.173 ms/op

Iteration   2: 3.027 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.774 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.388 ms/op
                 listUser·p0.9999: 11.083 ms/op
                 listUser·p1.00:   12.124 ms/op

Iteration   3: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.038 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.415 ms/op
                 listUser·p0.999:  8.897 ms/op
                 listUser·p0.9999: 11.251 ms/op
                 listUser·p1.00:   12.468 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317610
  mean =      3.020 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 137 
    [ 1.250,  2.500) = 89248 
    [ 2.500,  3.750) = 189134 
    [ 3.750,  5.000) = 31901 
    [ 5.000,  6.250) = 5953 
    [ 6.250,  7.500) = 540 
    [ 7.500,  8.750) = 282 
    [ 8.750, 10.000) = 257 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.165 ms/op
     p(99.9900) =     11.424 ms/op
     p(99.9990) =     12.170 ms/op
     p(99.9999) =     12.468 ms/op
    p(100.0000) =     12.468 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.537 ± 0.782  ops/ms
ClientPb.existUser                       thrpt       3  12.961 ± 1.491  ops/ms
ClientPb.getUser                         thrpt       3  12.604 ± 1.684  ops/ms
ClientPb.listUser                        thrpt       3  10.609 ± 1.473  ops/ms
ClientPb.createUser                       avgt       3   2.555 ± 0.169   ms/op
ClientPb.existUser                        avgt       3   2.486 ± 0.379   ms/op
ClientPb.getUser                          avgt       3   2.519 ± 0.228   ms/op
ClientPb.listUser                         avgt       3   3.008 ± 0.283   ms/op
ClientPb.createUser                     sample  377308   2.541 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.937           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.850           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.001           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.395           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.041           ms/op
ClientPb.existUser                      sample  382597   2.507 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.858           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.572           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.170           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.578           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.426           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.122           ms/op
ClientPb.getUser                        sample  375266   2.556 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.883           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.568           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.265           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.065           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.457           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.244           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.810           ms/op
ClientPb.listUser                       sample  317610   3.020 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.774           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.165           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.424           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.468           ms/op
