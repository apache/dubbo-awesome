# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.581 ops/ms
# Warmup Iteration   2: 5.572 ops/ms
# Warmup Iteration   3: 8.889 ops/ms
Iteration   1: 9.794 ops/ms
Iteration   2: 9.819 ops/ms
Iteration   3: 9.911 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.841 ±(99.9%) 1.116 ops/ms [Average]
  (min, avg, max) = (9.794, 9.841, 9.911), stdev = 0.061
  CI (99.9%): [8.725, 10.958] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.755 ops/ms
# Warmup Iteration   2: 9.402 ops/ms
# Warmup Iteration   3: 10.338 ops/ms
Iteration   1: 10.488 ops/ms
Iteration   2: 10.075 ops/ms
Iteration   3: 10.307 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.290 ±(99.9%) 3.770 ops/ms [Average]
  (min, avg, max) = (10.075, 10.290, 10.488), stdev = 0.207
  CI (99.9%): [6.520, 14.060] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.464 ops/ms
# Warmup Iteration   2: 8.785 ops/ms
# Warmup Iteration   3: 10.125 ops/ms
Iteration   1: 9.785 ops/ms
Iteration   2: 10.081 ops/ms
Iteration   3: 9.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.839 ±(99.9%) 4.014 ops/ms [Average]
  (min, avg, max) = (9.651, 9.839, 10.081), stdev = 0.220
  CI (99.9%): [5.825, 13.852] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.107 ops/ms
# Warmup Iteration   2: 7.523 ops/ms
# Warmup Iteration   3: 8.364 ops/ms
Iteration   1: 8.733 ops/ms
Iteration   2: 8.646 ops/ms
Iteration   3: 8.802 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.727 ±(99.9%) 1.425 ops/ms [Average]
  (min, avg, max) = (8.646, 8.727, 8.802), stdev = 0.078
  CI (99.9%): [7.302, 10.152] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.826 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.468 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.305 ±(99.9%) 0.006 ms/op
Iteration   1: 3.160 ±(99.9%) 0.006 ms/op
Iteration   2: 3.117 ±(99.9%) 0.004 ms/op
Iteration   3: 3.342 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.206 ±(99.9%) 2.180 ms/op [Average]
  (min, avg, max) = (3.117, 3.206, 3.342), stdev = 0.120
  CI (99.9%): [1.026, 5.387] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.574 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.249 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.206 ±(99.9%) 0.007 ms/op
Iteration   1: 3.131 ±(99.9%) 0.006 ms/op
Iteration   2: 3.137 ±(99.9%) 0.005 ms/op
Iteration   3: 3.018 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.095 ±(99.9%) 1.229 ms/op [Average]
  (min, avg, max) = (3.018, 3.095, 3.137), stdev = 0.067
  CI (99.9%): [1.867, 4.324] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.177 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.521 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.353 ±(99.9%) 0.005 ms/op
Iteration   1: 3.243 ±(99.9%) 0.005 ms/op
Iteration   2: 3.109 ±(99.9%) 0.002 ms/op
Iteration   3: 3.139 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.164 ±(99.9%) 1.284 ms/op [Average]
  (min, avg, max) = (3.109, 3.164, 3.243), stdev = 0.070
  CI (99.9%): [1.880, 4.448] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.464 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.082 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.862 ±(99.9%) 0.006 ms/op
Iteration   1: 3.718 ±(99.9%) 0.008 ms/op
Iteration   2: 3.703 ±(99.9%) 0.008 ms/op
Iteration   3: 3.717 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.712 ±(99.9%) 0.155 ms/op [Average]
  (min, avg, max) = (3.703, 3.712, 3.718), stdev = 0.008
  CI (99.9%): [3.558, 3.867] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.225 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.730 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.198 ±(99.9%) 0.009 ms/op
Iteration   1: 3.144 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.366 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.297 ms/op
                 createUser·p0.95:   3.786 ms/op
                 createUser·p0.99:   5.453 ms/op
                 createUser·p0.999:  12.304 ms/op
                 createUser·p0.9999: 22.604 ms/op
                 createUser·p1.00:   23.593 ms/op

Iteration   2: 3.158 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.331 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  20.110 ms/op
                 createUser·p0.9999: 21.922 ms/op
                 createUser·p1.00:   22.446 ms/op

Iteration   3: 3.087 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.087 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.371 ms/op
                 createUser·p0.95:   3.613 ms/op
                 createUser·p0.99:   4.940 ms/op
                 createUser·p0.999:  10.927 ms/op
                 createUser·p0.9999: 23.603 ms/op
                 createUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 306662
  mean =      3.129 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18264 
    [ 2.500,  5.000) = 283185 
    [ 5.000,  7.500) = 4254 
    [ 7.500, 10.000) = 455 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 146 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     17.739 ms/op
     p(99.9900) =     22.610 ms/op
     p(99.9990) =     23.921 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.300 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.386 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.325 ±(99.9%) 0.009 ms/op
Iteration   1: 3.222 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.176 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   4.182 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   6.062 ms/op
                 existUser·p0.999:  12.969 ms/op
                 existUser·p0.9999: 26.673 ms/op
                 existUser·p1.00:   27.066 ms/op

Iteration   2: 3.239 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.325 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   3.994 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  8.651 ms/op
                 existUser·p0.9999: 23.761 ms/op
                 existUser·p1.00:   24.248 ms/op

Iteration   3: 3.007 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.270 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.183 ms/op
                 existUser·p0.95:   3.416 ms/op
                 existUser·p0.99:   5.046 ms/op
                 existUser·p0.999:  9.873 ms/op
                 existUser·p0.9999: 21.692 ms/op
                 existUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304302
  mean =      3.152 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20801 
    [ 2.500,  5.000) = 276783 
    [ 5.000,  7.500) = 6012 
    [ 7.500, 10.000) = 336 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.176 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     12.911 ms/op
     p(99.9900) =     23.827 ms/op
     p(99.9990) =     27.025 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.694 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.329 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.311 ±(99.9%) 0.009 ms/op
Iteration   1: 3.310 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.124 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   6.062 ms/op
                 getUser·p0.999:  17.556 ms/op
                 getUser·p0.9999: 20.667 ms/op
                 getUser·p1.00:   21.168 ms/op

Iteration   2: 3.093 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.864 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.359 ms/op
                 getUser·p0.95:   3.473 ms/op
                 getUser·p0.99:   5.177 ms/op
                 getUser·p0.999:  9.496 ms/op
                 getUser·p0.9999: 22.512 ms/op
                 getUser·p1.00:   23.462 ms/op

Iteration   3: 3.083 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.587 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.330 ms/op
                 getUser·p0.95:   3.461 ms/op
                 getUser·p0.99:   4.825 ms/op
                 getUser·p0.999:  8.672 ms/op
                 getUser·p0.9999: 21.504 ms/op
                 getUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 303721
  mean =      3.159 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12179 
    [ 2.500,  5.000) = 286378 
    [ 5.000,  7.500) = 4441 
    [ 7.500, 10.000) = 369 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 141 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     15.466 ms/op
     p(99.9900) =     21.779 ms/op
     p(99.9990) =     22.970 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.362 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.365 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.761 ±(99.9%) 0.011 ms/op
Iteration   1: 3.794 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.616 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.125 ms/op
                 listUser·p0.95:   5.218 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  15.516 ms/op
                 listUser·p0.9999: 22.273 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   2: 3.915 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.288 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   5.095 ms/op
                 listUser·p0.99:   7.447 ms/op
                 listUser·p0.999:  13.407 ms/op
                 listUser·p0.9999: 17.465 ms/op
                 listUser·p1.00:   17.498 ms/op

Iteration   3: 3.811 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  13.648 ms/op
                 listUser·p0.9999: 14.778 ms/op
                 listUser·p1.00:   14.778 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249942
  mean =      3.839 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 81 
    [ 2.500,  5.000) = 238078 
    [ 5.000,  7.500) = 10063 
    [ 7.500, 10.000) = 1124 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 300 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.288 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     13.894 ms/op
     p(99.9900) =     21.201 ms/op
     p(99.9990) =     22.659 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.841 ± 1.116  ops/ms
ClientPb.existUser                       thrpt       3  10.290 ± 3.770  ops/ms
ClientPb.getUser                         thrpt       3   9.839 ± 4.014  ops/ms
ClientPb.listUser                        thrpt       3   8.727 ± 1.425  ops/ms
ClientPb.createUser                       avgt       3   3.206 ± 2.180   ms/op
ClientPb.existUser                        avgt       3   3.095 ± 1.229   ms/op
ClientPb.getUser                          avgt       3   3.164 ± 1.284   ms/op
ClientPb.listUser                         avgt       3   3.712 ± 0.155   ms/op
ClientPb.createUser                     sample  306662   3.129 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.087           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.420           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.727           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.439           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.739           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.610           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.609           ms/op
ClientPb.existUser                      sample  304302   3.152 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.176           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.178           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.546           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.911           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.827           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.066           ms/op
ClientPb.getUser                        sample  303721   3.159 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.864           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.506           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.850           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.530           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.466           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.779           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.462           ms/op
ClientPb.listUser                       sample  249942   3.839 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.288           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.703           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.833           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.029           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.894           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.201           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.331           ms/op
