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
# Warmup Iteration   1: 4.825 ops/ms
# Warmup Iteration   2: 12.136 ops/ms
# Warmup Iteration   3: 12.262 ops/ms
Iteration   1: 12.360 ops/ms
Iteration   2: 12.611 ops/ms
Iteration   3: 12.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.534 ±(99.9%) 2.755 ops/ms [Average]
  (min, avg, max) = (12.360, 12.534, 12.631), stdev = 0.151
  CI (99.9%): [9.779, 15.289] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.095 ops/ms
# Warmup Iteration   2: 13.072 ops/ms
# Warmup Iteration   3: 13.341 ops/ms
Iteration   1: 13.248 ops/ms
Iteration   2: 13.358 ops/ms
Iteration   3: 13.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.344 ±(99.9%) 1.641 ops/ms [Average]
  (min, avg, max) = (13.248, 13.344, 13.426), stdev = 0.090
  CI (99.9%): [11.703, 14.984] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.733 ops/ms
# Warmup Iteration   2: 12.322 ops/ms
# Warmup Iteration   3: 12.387 ops/ms
Iteration   1: 12.551 ops/ms
Iteration   2: 12.508 ops/ms
Iteration   3: 12.539 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.533 ±(99.9%) 0.412 ops/ms [Average]
  (min, avg, max) = (12.508, 12.533, 12.551), stdev = 0.023
  CI (99.9%): [12.121, 12.945] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.439 ops/ms
# Warmup Iteration   2: 10.557 ops/ms
# Warmup Iteration   3: 10.591 ops/ms
Iteration   1: 10.844 ops/ms
Iteration   2: 10.845 ops/ms
Iteration   3: 10.693 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.794 ±(99.9%) 1.596 ops/ms [Average]
  (min, avg, max) = (10.693, 10.794, 10.845), stdev = 0.087
  CI (99.9%): [9.198, 12.390] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.212 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.581 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.003 ms/op
Iteration   1: 2.544 ±(99.9%) 0.004 ms/op
Iteration   2: 2.494 ±(99.9%) 0.004 ms/op
Iteration   3: 2.487 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.508 ±(99.9%) 0.570 ms/op [Average]
  (min, avg, max) = (2.487, 2.508, 2.544), stdev = 0.031
  CI (99.9%): [1.938, 3.079] (assumes normal distribution)


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
# Warmup Iteration   1: 3.618 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.461 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.003 ms/op
Iteration   1: 2.451 ±(99.9%) 0.003 ms/op
Iteration   2: 2.445 ±(99.9%) 0.003 ms/op
Iteration   3: 2.464 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.453 ±(99.9%) 0.180 ms/op [Average]
  (min, avg, max) = (2.445, 2.453, 2.464), stdev = 0.010
  CI (99.9%): [2.273, 2.634] (assumes normal distribution)


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
# Warmup Iteration   1: 3.755 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.527 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.004 ms/op
Iteration   1: 2.481 ±(99.9%) 0.003 ms/op
Iteration   2: 2.508 ±(99.9%) 0.004 ms/op
Iteration   3: 2.496 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.495 ±(99.9%) 0.245 ms/op [Average]
  (min, avg, max) = (2.481, 2.495, 2.508), stdev = 0.013
  CI (99.9%): [2.250, 2.740] (assumes normal distribution)


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
# Warmup Iteration   1: 4.637 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.067 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.006 ms/op
Iteration   1: 3.009 ±(99.9%) 0.006 ms/op
Iteration   2: 2.983 ±(99.9%) 0.005 ms/op
Iteration   3: 3.012 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.001 ±(99.9%) 0.292 ms/op [Average]
  (min, avg, max) = (2.983, 3.001, 3.012), stdev = 0.016
  CI (99.9%): [2.709, 3.294] (assumes normal distribution)


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
# Warmup Iteration   1: 4.103 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.716 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.006 ms/op
Iteration   1: 2.584 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.035 ms/op
                 createUser·p0.50:   2.666 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   3.891 ms/op
                 createUser·p0.999:  11.375 ms/op
                 createUser·p0.9999: 14.035 ms/op
                 createUser·p1.00:   14.369 ms/op

Iteration   2: 2.572 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.881 ms/op
                 createUser·p0.50:   2.683 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.789 ms/op
                 createUser·p0.999:  9.404 ms/op
                 createUser·p0.9999: 11.664 ms/op
                 createUser·p1.00:   12.173 ms/op

Iteration   3: 2.602 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.871 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.170 ms/op
                 createUser·p0.95:   3.310 ms/op
                 createUser·p0.99:   4.026 ms/op
                 createUser·p0.999:  8.536 ms/op
                 createUser·p0.9999: 11.263 ms/op
                 createUser·p1.00:   11.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 370886
  mean =      2.586 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 174612 
    [ 2.500,  3.750) = 191428 
    [ 3.750,  5.000) = 3689 
    [ 5.000,  6.250) = 679 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 158 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      2.671 ms/op
     p(90.0000) =      3.138 ms/op
     p(95.0000) =      3.260 ms/op
     p(99.0000) =      3.903 ms/op
     p(99.9000) =      9.324 ms/op
     p(99.9900) =     13.401 ms/op
     p(99.9990) =     14.259 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


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
# Warmup Iteration   1: 3.901 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.522 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.005 ms/op
Iteration   1: 2.472 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.009 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.604 ms/op
                 existUser·p0.999:  5.208 ms/op
                 existUser·p0.9999: 13.943 ms/op
                 existUser·p1.00:   14.385 ms/op

Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.026 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.613 ms/op
                 existUser·p0.999:  8.962 ms/op
                 existUser·p0.9999: 13.815 ms/op
                 existUser·p1.00:   14.483 ms/op

Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.940 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.047 ms/op
                 existUser·p0.95:   3.203 ms/op
                 existUser·p0.99:   4.063 ms/op
                 existUser·p0.999:  7.930 ms/op
                 existUser·p0.9999: 11.846 ms/op
                 existUser·p1.00:   12.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384616
  mean =      2.494 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 186323 
    [ 2.500,  3.750) = 194287 
    [ 3.750,  5.000) = 3036 
    [ 5.000,  6.250) = 541 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.768 ms/op
     p(99.9000) =      6.259 ms/op
     p(99.9900) =     13.576 ms/op
     p(99.9990) =     14.272 ms/op
     p(99.9999) =     14.483 ms/op
    p(100.0000) =     14.483 ms/op


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
# Warmup Iteration   1: 3.785 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.537 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.006 ms/op
Iteration   1: 2.466 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.046 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.707 ms/op
                 getUser·p0.999:  6.279 ms/op
                 getUser·p0.9999: 13.468 ms/op
                 getUser·p1.00:   13.664 ms/op

Iteration   2: 2.488 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.946 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.953 ms/op
                 getUser·p0.999:  9.651 ms/op
                 getUser·p0.9999: 12.192 ms/op
                 getUser·p1.00:   12.583 ms/op

Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.834 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   2.986 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   4.141 ms/op
                 getUser·p0.999:  7.389 ms/op
                 getUser·p0.9999: 13.108 ms/op
                 getUser·p1.00:   13.943 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387898
  mean =      2.472 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 94 
    [ 1.250,  2.500) = 193191 
    [ 2.500,  3.750) = 189586 
    [ 3.750,  5.000) = 3957 
    [ 5.000,  6.250) = 585 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 118 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.912 ms/op
     p(99.9000) =      9.065 ms/op
     p(99.9900) =     13.160 ms/op
     p(99.9990) =     13.603 ms/op
     p(99.9999) =     13.943 ms/op
    p(100.0000) =     13.943 ms/op


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
# Warmup Iteration   1: 4.779 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.009 ms/op
Iteration   1: 3.039 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.886 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.175 ms/op
                 listUser·p0.9999: 11.223 ms/op
                 listUser·p1.00:   11.764 ms/op

Iteration   2: 3.049 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.867 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.884 ms/op
                 listUser·p0.9999: 11.944 ms/op
                 listUser·p1.00:   12.780 ms/op

Iteration   3: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.970 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  9.077 ms/op
                 listUser·p0.9999: 10.933 ms/op
                 listUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315656
  mean =      3.039 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 101 
    [ 1.250,  2.500) = 86859 
    [ 2.500,  3.750) = 187584 
    [ 3.750,  5.000) = 33515 
    [ 5.000,  6.250) = 6171 
    [ 6.250,  7.500) = 772 
    [ 7.500,  8.750) = 184 
    [ 8.750, 10.000) = 255 
    [10.000, 11.250) = 174 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =      9.426 ms/op
     p(99.9900) =     11.321 ms/op
     p(99.9990) =     12.648 ms/op
     p(99.9999) =     12.780 ms/op
    p(100.0000) =     12.780 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.534 ± 2.755  ops/ms
ClientPb.existUser                       thrpt       3  13.344 ± 1.641  ops/ms
ClientPb.getUser                         thrpt       3  12.533 ± 0.412  ops/ms
ClientPb.listUser                        thrpt       3  10.794 ± 1.596  ops/ms
ClientPb.createUser                       avgt       3   2.508 ± 0.570   ms/op
ClientPb.existUser                        avgt       3   2.453 ± 0.180   ms/op
ClientPb.getUser                          avgt       3   2.495 ± 0.245   ms/op
ClientPb.listUser                         avgt       3   3.001 ± 0.292   ms/op
ClientPb.createUser                     sample  370886   2.586 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.871           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.671           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.260           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.324           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.401           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.369           ms/op
ClientPb.existUser                      sample  384616   2.494 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.940           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.568           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.154           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.768           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.259           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.576           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.483           ms/op
ClientPb.getUser                        sample  387898   2.472 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.834           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.011           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.912           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.065           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.160           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.943           ms/op
ClientPb.listUser                       sample  315656   3.039 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.867           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.978           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.426           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.321           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.780           ms/op
