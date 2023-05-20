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
# Warmup Iteration   1: 2.472 ops/ms
# Warmup Iteration   2: 6.148 ops/ms
# Warmup Iteration   3: 8.927 ops/ms
Iteration   1: 10.072 ops/ms
Iteration   2: 9.714 ops/ms
Iteration   3: 9.633 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.806 ±(99.9%) 4.255 ops/ms [Average]
  (min, avg, max) = (9.633, 9.806, 10.072), stdev = 0.233
  CI (99.9%): [5.551, 14.062] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.594 ops/ms
# Warmup Iteration   2: 9.576 ops/ms
# Warmup Iteration   3: 10.278 ops/ms
Iteration   1: 10.564 ops/ms
Iteration   2: 10.100 ops/ms
Iteration   3: 10.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.465 ±(99.9%) 5.973 ops/ms [Average]
  (min, avg, max) = (10.100, 10.465, 10.732), stdev = 0.327
  CI (99.9%): [4.492, 16.438] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.421 ops/ms
# Warmup Iteration   2: 8.619 ops/ms
# Warmup Iteration   3: 10.066 ops/ms
Iteration   1: 9.977 ops/ms
Iteration   2: 9.982 ops/ms
Iteration   3: 9.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.852 ±(99.9%) 4.019 ops/ms [Average]
  (min, avg, max) = (9.598, 9.852, 9.982), stdev = 0.220
  CI (99.9%): [5.833, 13.872] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.982 ops/ms
# Warmup Iteration   2: 7.496 ops/ms
# Warmup Iteration   3: 8.246 ops/ms
Iteration   1: 8.218 ops/ms
Iteration   2: 8.204 ops/ms
Iteration   3: 8.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.336 ±(99.9%) 3.967 ops/ms [Average]
  (min, avg, max) = (8.204, 8.336, 8.587), stdev = 0.217
  CI (99.9%): [4.369, 12.303] (assumes normal distribution)


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
# Warmup Iteration   1: 8.859 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.653 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.351 ±(99.9%) 0.006 ms/op
Iteration   1: 3.301 ±(99.9%) 0.004 ms/op
Iteration   2: 3.216 ±(99.9%) 0.007 ms/op
Iteration   3: 3.065 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.194 ±(99.9%) 2.180 ms/op [Average]
  (min, avg, max) = (3.065, 3.194, 3.301), stdev = 0.120
  CI (99.9%): [1.014, 5.374] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.014 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.346 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.178 ±(99.9%) 0.005 ms/op
Iteration   1: 3.054 ±(99.9%) 0.004 ms/op
Iteration   2: 3.225 ±(99.9%) 0.003 ms/op
Iteration   3: 3.082 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.120 ±(99.9%) 1.674 ms/op [Average]
  (min, avg, max) = (3.054, 3.120, 3.225), stdev = 0.092
  CI (99.9%): [1.446, 4.794] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.585 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.460 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.350 ±(99.9%) 0.004 ms/op
Iteration   1: 3.244 ±(99.9%) 0.006 ms/op
Iteration   2: 3.298 ±(99.9%) 0.005 ms/op
Iteration   3: 3.202 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.248 ±(99.9%) 0.880 ms/op [Average]
  (min, avg, max) = (3.202, 3.248, 3.298), stdev = 0.048
  CI (99.9%): [2.367, 4.128] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.305 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.328 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.896 ±(99.9%) 0.005 ms/op
Iteration   1: 3.756 ±(99.9%) 0.008 ms/op
Iteration   2: 3.707 ±(99.9%) 0.010 ms/op
Iteration   3: 3.705 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.723 ±(99.9%) 0.529 ms/op [Average]
  (min, avg, max) = (3.705, 3.723, 3.756), stdev = 0.029
  CI (99.9%): [3.194, 4.251] (assumes normal distribution)


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
# Warmup Iteration   1: 8.173 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.673 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.139 ±(99.9%) 0.008 ms/op
Iteration   1: 3.205 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.682 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   6.341 ms/op
                 createUser·p0.999:  18.842 ms/op
                 createUser·p0.9999: 21.758 ms/op
                 createUser·p1.00:   22.544 ms/op

Iteration   2: 3.250 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.345 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   5.382 ms/op
                 createUser·p0.999:  10.733 ms/op
                 createUser·p0.9999: 24.962 ms/op
                 createUser·p1.00:   26.870 ms/op

Iteration   3: 3.258 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.468 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  16.595 ms/op
                 createUser·p0.9999: 21.764 ms/op
                 createUser·p1.00:   25.461 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296499
  mean =      3.238 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17847 
    [ 2.500,  5.000) = 273452 
    [ 5.000,  7.500) = 3876 
    [ 7.500, 10.000) = 781 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.345 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     17.809 ms/op
     p(99.9900) =     24.489 ms/op
     p(99.9990) =     26.740 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.638 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.615 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.354 ±(99.9%) 0.009 ms/op
Iteration   1: 3.134 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.477 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   4.125 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  9.287 ms/op
                 existUser·p0.9999: 32.000 ms/op
                 existUser·p1.00:   32.604 ms/op

Iteration   2: 3.180 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.137 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   4.141 ms/op
                 existUser·p0.99:   5.382 ms/op
                 existUser·p0.999:  11.401 ms/op
                 existUser·p0.9999: 27.853 ms/op
                 existUser·p1.00:   29.557 ms/op

Iteration   3: 3.172 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   4.174 ms/op
                 existUser·p0.99:   5.344 ms/op
                 existUser·p0.999:  11.108 ms/op
                 existUser·p0.9999: 39.765 ms/op
                 existUser·p1.00:   40.436 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303512
  mean =      3.162 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 298425 
    [ 5.000, 10.000) = 4769 
    [10.000, 15.000) = 62 
    [15.000, 20.000) = 66 
    [20.000, 25.000) = 58 
    [25.000, 30.000) = 68 
    [30.000, 35.000) = 32 
    [35.000, 40.000) = 26 
    [40.000, 45.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.477 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      5.349 ms/op
     p(99.9000) =     11.092 ms/op
     p(99.9900) =     37.984 ms/op
     p(99.9990) =     40.237 ms/op
     p(99.9999) =     40.436 ms/op
    p(100.0000) =     40.436 ms/op


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
# Warmup Iteration   1: 7.893 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.679 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.390 ±(99.9%) 0.011 ms/op
Iteration   1: 3.172 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.473 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   5.906 ms/op
                 getUser·p0.999:  8.536 ms/op
                 getUser·p0.9999: 21.744 ms/op
                 getUser·p1.00:   23.134 ms/op

Iteration   2: 3.219 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.946 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   5.464 ms/op
                 getUser·p0.999:  10.859 ms/op
                 getUser·p0.9999: 23.038 ms/op
                 getUser·p1.00:   23.527 ms/op

Iteration   3: 3.369 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.479 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   6.349 ms/op
                 getUser·p0.999:  15.569 ms/op
                 getUser·p0.9999: 23.053 ms/op
                 getUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294973
  mean =      3.251 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14468 
    [ 2.500,  5.000) = 272700 
    [ 5.000,  7.500) = 7000 
    [ 7.500, 10.000) = 475 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 151 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.946 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     11.256 ms/op
     p(99.9900) =     22.184 ms/op
     p(99.9990) =     23.464 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


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
# Warmup Iteration   1: 9.715 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.117 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.814 ±(99.9%) 0.010 ms/op
Iteration   1: 3.821 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.698 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  17.367 ms/op
                 listUser·p0.9999: 19.808 ms/op
                 listUser·p1.00:   20.513 ms/op

Iteration   2: 3.733 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.355 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.149 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  13.484 ms/op
                 listUser·p0.9999: 15.013 ms/op
                 listUser·p1.00:   16.581 ms/op

Iteration   3: 3.858 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.829 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   7.340 ms/op
                 listUser·p0.999:  15.186 ms/op
                 listUser·p0.9999: 21.520 ms/op
                 listUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252170
  mean =      3.803 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 244826 
    [ 5.000,  7.500) = 5379 
    [ 7.500, 10.000) = 1253 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 234 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.698 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     14.975 ms/op
     p(99.9900) =     19.661 ms/op
     p(99.9990) =     21.920 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.806 ± 4.255  ops/ms
ClientPb.existUser                       thrpt       3  10.465 ± 5.973  ops/ms
ClientPb.getUser                         thrpt       3   9.852 ± 4.019  ops/ms
ClientPb.listUser                        thrpt       3   8.336 ± 3.967  ops/ms
ClientPb.createUser                       avgt       3   3.194 ± 2.180   ms/op
ClientPb.existUser                        avgt       3   3.120 ± 1.674   ms/op
ClientPb.getUser                          avgt       3   3.248 ± 0.880   ms/op
ClientPb.listUser                         avgt       3   3.723 ± 0.529   ms/op
ClientPb.createUser                     sample  296499   3.238 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.345           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.613           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.977           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.636           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.809           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.489           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.870           ms/op
ClientPb.existUser                      sample  303512   3.162 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.477           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.621           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.145           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.349           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.092           ms/op
ClientPb.existUser:existUser·p0.9999    sample          37.984           ms/op
ClientPb.existUser:existUser·p1.00      sample          40.436           ms/op
ClientPb.getUser                        sample  294973   3.251 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.946           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.695           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.141           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.784           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.256           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.184           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.527           ms/op
ClientPb.listUser                       sample  252170   3.803 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.698           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.719           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.080           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.947           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.975           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.661           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.821           ms/op
