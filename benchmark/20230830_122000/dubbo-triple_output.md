# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.884 ops/ms
# Warmup Iteration   2: 5.655 ops/ms
# Warmup Iteration   3: 8.541 ops/ms
Iteration   1: 8.925 ops/ms
Iteration   2: 9.021 ops/ms
Iteration   3: 9.373 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.106 ±(99.9%) 4.301 ops/ms [Average]
  (min, avg, max) = (8.925, 9.106, 9.373), stdev = 0.236
  CI (99.9%): [4.805, 13.408] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.974 ops/ms
# Warmup Iteration   2: 8.425 ops/ms
# Warmup Iteration   3: 9.229 ops/ms
Iteration   1: 9.690 ops/ms
Iteration   2: 9.153 ops/ms
Iteration   3: 9.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.432 ±(99.9%) 4.910 ops/ms [Average]
  (min, avg, max) = (9.153, 9.432, 9.690), stdev = 0.269
  CI (99.9%): [4.523, 14.342] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.669 ops/ms
# Warmup Iteration   2: 7.730 ops/ms
# Warmup Iteration   3: 8.874 ops/ms
Iteration   1: 9.262 ops/ms
Iteration   2: 9.073 ops/ms
Iteration   3: 9.054 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.129 ±(99.9%) 2.100 ops/ms [Average]
  (min, avg, max) = (9.054, 9.129, 9.262), stdev = 0.115
  CI (99.9%): [7.029, 11.230] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.350 ops/ms
# Warmup Iteration   2: 6.454 ops/ms
# Warmup Iteration   3: 7.268 ops/ms
Iteration   1: 7.656 ops/ms
Iteration   2: 7.564 ops/ms
Iteration   3: 7.604 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.608 ±(99.9%) 0.843 ops/ms [Average]
  (min, avg, max) = (7.564, 7.608, 7.656), stdev = 0.046
  CI (99.9%): [6.765, 8.452] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.801 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.925 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.617 ±(99.9%) 0.007 ms/op
Iteration   1: 3.495 ±(99.9%) 0.003 ms/op
Iteration   2: 3.378 ±(99.9%) 0.007 ms/op
Iteration   3: 3.480 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.451 ±(99.9%) 1.163 ms/op [Average]
  (min, avg, max) = (3.378, 3.451, 3.495), stdev = 0.064
  CI (99.9%): [2.287, 4.614] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.742 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.673 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.509 ±(99.9%) 0.006 ms/op
Iteration   1: 3.342 ±(99.9%) 0.003 ms/op
Iteration   2: 3.381 ±(99.9%) 0.006 ms/op
Iteration   3: 3.392 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.372 ±(99.9%) 0.477 ms/op [Average]
  (min, avg, max) = (3.342, 3.372, 3.392), stdev = 0.026
  CI (99.9%): [2.895, 3.848] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.439 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 3.839 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.619 ±(99.9%) 0.004 ms/op
Iteration   1: 3.553 ±(99.9%) 0.008 ms/op
Iteration   2: 3.489 ±(99.9%) 0.003 ms/op
Iteration   3: 3.578 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.540 ±(99.9%) 0.832 ms/op [Average]
  (min, avg, max) = (3.489, 3.540, 3.578), stdev = 0.046
  CI (99.9%): [2.708, 4.372] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.641 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.949 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.352 ±(99.9%) 0.010 ms/op
Iteration   1: 4.094 ±(99.9%) 0.010 ms/op
Iteration   2: 4.207 ±(99.9%) 0.007 ms/op
Iteration   3: 4.091 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.131 ±(99.9%) 1.207 ms/op [Average]
  (min, avg, max) = (4.091, 4.131, 4.207), stdev = 0.066
  CI (99.9%): [2.923, 5.338] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 11.426 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.059 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.048 ±(99.9%) 0.017 ms/op
Iteration   1: 3.504 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.061 ms/op
                 createUser·p0.50:   3.432 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   6.439 ms/op
                 createUser·p0.999:  20.669 ms/op
                 createUser·p0.9999: 22.704 ms/op
                 createUser·p1.00:   23.265 ms/op

Iteration   2: 3.459 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.858 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   6.613 ms/op
                 createUser·p0.999:  21.104 ms/op
                 createUser·p0.9999: 24.011 ms/op
                 createUser·p1.00:   26.706 ms/op

Iteration   3: 3.481 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.241 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   6.234 ms/op
                 createUser·p0.999:  24.852 ms/op
                 createUser·p0.9999: 29.211 ms/op
                 createUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275564
  mean =      3.481 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8428 
    [ 2.500,  5.000) = 259746 
    [ 5.000,  7.500) = 5654 
    [ 7.500, 10.000) = 942 
    [10.000, 12.500) = 421 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 139 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 71 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.439 ms/op
     p(99.9000) =     20.808 ms/op
     p(99.9900) =     27.409 ms/op
     p(99.9990) =     29.679 ms/op
     p(99.9999) =     29.983 ms/op
    p(100.0000) =     29.983 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 11.046 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 3.709 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.449 ±(99.9%) 0.009 ms/op
Iteration   1: 3.345 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.276 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.998 ms/op
                 existUser·p0.99:   6.860 ms/op
                 existUser·p0.999:  19.815 ms/op
                 existUser·p0.9999: 23.930 ms/op
                 existUser·p1.00:   28.017 ms/op

Iteration   2: 3.304 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.169 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   5.931 ms/op
                 existUser·p0.999:  11.759 ms/op
                 existUser·p0.9999: 28.213 ms/op
                 existUser·p1.00:   28.901 ms/op

Iteration   3: 3.351 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.391 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   4.125 ms/op
                 existUser·p0.99:   6.383 ms/op
                 existUser·p0.999:  19.334 ms/op
                 existUser·p0.9999: 26.459 ms/op
                 existUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288065
  mean =      3.333 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18430 
    [ 2.500,  5.000) = 261973 
    [ 5.000,  7.500) = 6005 
    [ 7.500, 10.000) = 1055 
    [10.000, 12.500) = 279 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 65 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =     19.242 ms/op
     p(99.9900) =     27.702 ms/op
     p(99.9990) =     28.778 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 9.579 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.055 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.607 ±(99.9%) 0.010 ms/op
Iteration   1: 3.649 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.692 ms/op
                 getUser·p0.50:   3.527 ms/op
                 getUser·p0.90:   4.104 ms/op
                 getUser·p0.95:   4.604 ms/op
                 getUser·p0.99:   7.381 ms/op
                 getUser·p0.999:  21.889 ms/op
                 getUser·p0.9999: 25.432 ms/op
                 getUser·p1.00:   27.066 ms/op

Iteration   2: 3.651 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.722 ms/op
                 getUser·p0.50:   3.498 ms/op
                 getUser·p0.90:   4.116 ms/op
                 getUser·p0.95:   5.030 ms/op
                 getUser·p0.99:   7.135 ms/op
                 getUser·p0.999:  24.010 ms/op
                 getUser·p0.9999: 26.550 ms/op
                 getUser·p1.00:   27.329 ms/op

Iteration   3: 3.681 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.128 ms/op
                 getUser·p0.50:   3.518 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   4.907 ms/op
                 getUser·p0.99:   7.070 ms/op
                 getUser·p0.999:  22.289 ms/op
                 getUser·p0.9999: 29.993 ms/op
                 getUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 262448
  mean =      3.660 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3451 
    [ 2.500,  5.000) = 247027 
    [ 5.000,  7.500) = 9795 
    [ 7.500, 10.000) = 1382 
    [10.000, 12.500) = 395 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 130 
    [25.000, 27.500) = 102 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.128 ms/op
     p(50.0000) =      3.514 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      7.168 ms/op
     p(99.9000) =     22.577 ms/op
     p(99.9900) =     28.082 ms/op
     p(99.9990) =     30.126 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.484 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.668 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.228 ±(99.9%) 0.016 ms/op
Iteration   1: 4.252 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.056 ms/op
                 listUser·p0.50:   4.022 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   5.349 ms/op
                 listUser·p0.99:   8.602 ms/op
                 listUser·p0.999:  22.668 ms/op
                 listUser·p0.9999: 26.787 ms/op
                 listUser·p1.00:   28.213 ms/op

Iteration   2: 4.186 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.195 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.154 ms/op
                 listUser·p0.99:   8.415 ms/op
                 listUser·p0.999:  15.979 ms/op
                 listUser·p0.9999: 19.913 ms/op
                 listUser·p1.00:   23.560 ms/op

Iteration   3: 4.117 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.083 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   5.095 ms/op
                 listUser·p0.99:   7.870 ms/op
                 listUser·p0.999:  16.024 ms/op
                 listUser·p0.9999: 18.645 ms/op
                 listUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229378
  mean =      4.184 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 215230 
    [ 5.000,  7.500) = 10443 
    [ 7.500, 10.000) = 2475 
    [10.000, 12.500) = 600 
    [12.500, 15.000) = 223 
    [15.000, 17.500) = 175 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      2.056 ms/op
     p(50.0000) =      3.985 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.177 ms/op
     p(99.0000) =      8.356 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     25.594 ms/op
     p(99.9990) =     28.075 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.106 ± 4.301  ops/ms
ClientPb.existUser                       thrpt       3   9.432 ± 4.910  ops/ms
ClientPb.getUser                         thrpt       3   9.129 ± 2.100  ops/ms
ClientPb.listUser                        thrpt       3   7.608 ± 0.843  ops/ms
ClientPb.createUser                       avgt       3   3.451 ± 1.163   ms/op
ClientPb.existUser                        avgt       3   3.372 ± 0.477   ms/op
ClientPb.getUser                          avgt       3   3.540 ± 0.832   ms/op
ClientPb.listUser                         avgt       3   4.131 ± 1.207   ms/op
ClientPb.createUser                     sample  275564   3.481 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.061           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.379           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.284           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.439           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.808           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.409           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.983           ms/op
ClientPb.existUser                      sample  288065   3.333 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.169           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.559           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.994           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.365           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.242           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.702           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.901           ms/op
ClientPb.getUser                        sample  262448   3.660 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.128           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.514           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.202           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.841           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.168           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.577           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.082           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.310           ms/op
ClientPb.listUser                       sample  229378   4.184 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.056           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.985           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.177           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.356           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.876           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.594           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.213           ms/op
