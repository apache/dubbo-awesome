# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.520 ops/ms
# Warmup Iteration   2: 6.787 ops/ms
# Warmup Iteration   3: 9.383 ops/ms
Iteration   1: 9.975 ops/ms
Iteration   2: 9.921 ops/ms
Iteration   3: 10.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.012 ±(99.9%) 2.098 ops/ms [Average]
  (min, avg, max) = (9.921, 10.012, 10.141), stdev = 0.115
  CI (99.9%): [7.914, 12.110] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.797 ops/ms
# Warmup Iteration   2: 9.480 ops/ms
# Warmup Iteration   3: 9.976 ops/ms
Iteration   1: 10.209 ops/ms
Iteration   2: 10.638 ops/ms
Iteration   3: 10.709 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.519 ±(99.9%) 4.941 ops/ms [Average]
  (min, avg, max) = (10.209, 10.519, 10.709), stdev = 0.271
  CI (99.9%): [5.578, 15.460] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.300 ops/ms
# Warmup Iteration   2: 8.961 ops/ms
# Warmup Iteration   3: 9.578 ops/ms
Iteration   1: 9.854 ops/ms
Iteration   2: 9.886 ops/ms
Iteration   3: 9.907 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.882 ±(99.9%) 0.485 ops/ms [Average]
  (min, avg, max) = (9.854, 9.882, 9.907), stdev = 0.027
  CI (99.9%): [9.398, 10.367] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.325 ops/ms
# Warmup Iteration   2: 7.559 ops/ms
# Warmup Iteration   3: 8.506 ops/ms
Iteration   1: 8.458 ops/ms
Iteration   2: 8.276 ops/ms
Iteration   3: 8.432 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.388 ±(99.9%) 1.798 ops/ms [Average]
  (min, avg, max) = (8.276, 8.388, 8.458), stdev = 0.099
  CI (99.9%): [6.590, 10.187] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.446 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.520 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.454 ±(99.9%) 0.005 ms/op
Iteration   1: 3.258 ±(99.9%) 0.005 ms/op
Iteration   2: 3.270 ±(99.9%) 0.007 ms/op
Iteration   3: 3.083 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.204 ±(99.9%) 1.910 ms/op [Average]
  (min, avg, max) = (3.083, 3.204, 3.270), stdev = 0.105
  CI (99.9%): [1.294, 5.114] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.114 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.232 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.002 ms/op
Iteration   1: 3.080 ±(99.9%) 0.003 ms/op
Iteration   2: 3.021 ±(99.9%) 0.005 ms/op
Iteration   3: 3.002 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.034 ±(99.9%) 0.737 ms/op [Average]
  (min, avg, max) = (3.002, 3.034, 3.080), stdev = 0.040
  CI (99.9%): [2.297, 3.771] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.931 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.425 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.163 ±(99.9%) 0.005 ms/op
Iteration   1: 3.171 ±(99.9%) 0.005 ms/op
Iteration   2: 3.312 ±(99.9%) 0.006 ms/op
Iteration   3: 3.215 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.233 ±(99.9%) 1.314 ms/op [Average]
  (min, avg, max) = (3.171, 3.233, 3.312), stdev = 0.072
  CI (99.9%): [1.919, 4.547] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.734 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.051 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.837 ±(99.9%) 0.007 ms/op
Iteration   1: 3.812 ±(99.9%) 0.004 ms/op
Iteration   2: 3.866 ±(99.9%) 0.003 ms/op
Iteration   3: 3.637 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.772 ±(99.9%) 2.180 ms/op [Average]
  (min, avg, max) = (3.637, 3.772, 3.866), stdev = 0.120
  CI (99.9%): [1.591, 5.952] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.180 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.685 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.383 ±(99.9%) 0.009 ms/op
Iteration   1: 3.413 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   4.407 ms/op
                 createUser·p0.95:   4.653 ms/op
                 createUser·p0.99:   5.972 ms/op
                 createUser·p0.999:  15.951 ms/op
                 createUser·p0.9999: 23.696 ms/op
                 createUser·p1.00:   25.690 ms/op

Iteration   2: 3.275 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  20.316 ms/op
                 createUser·p0.9999: 22.657 ms/op
                 createUser·p1.00:   23.265 ms/op

Iteration   3: 3.122 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.034 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.343 ms/op
                 createUser·p0.999:  7.881 ms/op
                 createUser·p0.9999: 18.957 ms/op
                 createUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293809
  mean =      3.266 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22132 
    [ 2.500,  5.000) = 265468 
    [ 5.000,  7.500) = 5614 
    [ 7.500, 10.000) = 268 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 125 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.959 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =     16.056 ms/op
     p(99.9900) =     22.401 ms/op
     p(99.9990) =     24.090 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.098 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 3.317 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.096 ±(99.9%) 0.007 ms/op
Iteration   1: 3.053 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.563 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  8.735 ms/op
                 existUser·p0.9999: 19.973 ms/op
                 existUser·p1.00:   20.578 ms/op

Iteration   2: 3.094 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   5.186 ms/op
                 existUser·p0.999:  9.175 ms/op
                 existUser·p0.9999: 21.224 ms/op
                 existUser·p1.00:   21.856 ms/op

Iteration   3: 3.050 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.188 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  9.293 ms/op
                 existUser·p0.9999: 23.658 ms/op
                 existUser·p1.00:   24.773 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 312819
  mean =      3.065 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16945 
    [ 2.500,  5.000) = 291623 
    [ 5.000,  7.500) = 3610 
    [ 7.500, 10.000) = 351 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 132 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.305 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      5.243 ms/op
     p(99.9000) =      9.175 ms/op
     p(99.9900) =     22.437 ms/op
     p(99.9990) =     24.052 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.311 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 3.514 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.169 ±(99.9%) 0.008 ms/op
Iteration   1: 3.170 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.217 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   6.160 ms/op
                 getUser·p0.999:  16.941 ms/op
                 getUser·p0.9999: 40.954 ms/op
                 getUser·p1.00:   47.120 ms/op

Iteration   2: 3.242 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.011 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   5.800 ms/op
                 getUser·p0.999:  11.096 ms/op
                 getUser·p0.9999: 20.095 ms/op
                 getUser·p1.00:   23.495 ms/op

Iteration   3: 3.201 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.321 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   5.734 ms/op
                 getUser·p0.999:  9.918 ms/op
                 getUser·p0.9999: 19.466 ms/op
                 getUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299460
  mean =      3.204 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 292709 
    [ 5.000, 10.000) = 6422 
    [10.000, 15.000) = 14 
    [15.000, 20.000) = 243 
    [20.000, 25.000) = 41 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 10 
    [40.000, 45.000) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.011 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      5.860 ms/op
     p(99.9000) =     15.565 ms/op
     p(99.9900) =     37.621 ms/op
     p(99.9990) =     46.728 ms/op
     p(99.9999) =     47.120 ms/op
    p(100.0000) =     47.120 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.785 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.097 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.719 ±(99.9%) 0.010 ms/op
Iteration   1: 3.681 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.366 ms/op
                 listUser·p0.50:   3.564 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  15.918 ms/op
                 listUser·p0.9999: 23.614 ms/op
                 listUser·p1.00:   24.347 ms/op

Iteration   2: 3.755 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.802 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   4.116 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   6.562 ms/op
                 listUser·p0.999:  12.351 ms/op
                 listUser·p0.9999: 19.661 ms/op
                 listUser·p1.00:   19.726 ms/op

Iteration   3: 3.635 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.179 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   3.744 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   6.324 ms/op
                 listUser·p0.999:  14.550 ms/op
                 listUser·p0.9999: 16.600 ms/op
                 listUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 260000
  mean =      3.690 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 64 
    [ 2.500,  5.000) = 251567 
    [ 5.000,  7.500) = 6893 
    [ 7.500, 10.000) = 859 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 142 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.366 ms/op
     p(50.0000) =      3.592 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     14.696 ms/op
     p(99.9900) =     21.889 ms/op
     p(99.9990) =     24.327 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.012 ± 2.098  ops/ms
ClientPb.existUser                       thrpt       3  10.519 ± 4.941  ops/ms
ClientPb.getUser                         thrpt       3   9.882 ± 0.485  ops/ms
ClientPb.listUser                        thrpt       3   8.388 ± 1.798  ops/ms
ClientPb.createUser                       avgt       3   3.204 ± 1.910   ms/op
ClientPb.existUser                        avgt       3   3.034 ± 0.737   ms/op
ClientPb.getUser                          avgt       3   3.233 ± 1.314   ms/op
ClientPb.listUser                         avgt       3   3.772 ± 2.180   ms/op
ClientPb.createUser                     sample  293809   3.266 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.959           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.826           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.456           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.579           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.056           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.401           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.690           ms/op
ClientPb.existUser                      sample  312819   3.065 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.071           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.305           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.650           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.243           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.175           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.437           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.773           ms/op
ClientPb.getUser                        sample  299460   3.204 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.011           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.543           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.809           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.860           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.565           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.621           ms/op
ClientPb.getUser:getUser·p1.00          sample          47.120           ms/op
ClientPb.listUser                       sample  260000   3.690 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.366           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.592           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.043           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.652           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.696           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.889           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.347           ms/op
