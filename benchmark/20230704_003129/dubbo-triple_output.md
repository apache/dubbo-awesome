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
# Warmup Iteration   1: 1.906 ops/ms
# Warmup Iteration   2: 5.115 ops/ms
# Warmup Iteration   3: 8.257 ops/ms
Iteration   1: 9.178 ops/ms
Iteration   2: 9.310 ops/ms
Iteration   3: 8.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.135 ±(99.9%) 3.660 ops/ms [Average]
  (min, avg, max) = (8.916, 9.135, 9.310), stdev = 0.201
  CI (99.9%): [5.474, 12.795] (assumes normal distribution)


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
# Warmup Iteration   1: 3.777 ops/ms
# Warmup Iteration   2: 8.594 ops/ms
# Warmup Iteration   3: 9.783 ops/ms
Iteration   1: 9.657 ops/ms
Iteration   2: 9.643 ops/ms
Iteration   3: 9.991 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.764 ±(99.9%) 3.588 ops/ms [Average]
  (min, avg, max) = (9.643, 9.764, 9.991), stdev = 0.197
  CI (99.9%): [6.176, 13.352] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.193 ops/ms
# Warmup Iteration   2: 8.803 ops/ms
# Warmup Iteration   3: 9.088 ops/ms
Iteration   1: 8.900 ops/ms
Iteration   2: 9.276 ops/ms
Iteration   3: 9.607 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.261 ±(99.9%) 6.457 ops/ms [Average]
  (min, avg, max) = (8.900, 9.261, 9.607), stdev = 0.354
  CI (99.9%): [2.804, 15.718] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.061 ops/ms
# Warmup Iteration   2: 7.354 ops/ms
# Warmup Iteration   3: 7.827 ops/ms
Iteration   1: 8.229 ops/ms
Iteration   2: 7.720 ops/ms
Iteration   3: 8.074 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.008 ±(99.9%) 4.765 ops/ms [Average]
  (min, avg, max) = (7.720, 8.008, 8.229), stdev = 0.261
  CI (99.9%): [3.243, 12.773] (assumes normal distribution)


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
# Warmup Iteration   1: 10.317 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.891 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.556 ±(99.9%) 0.009 ms/op
Iteration   1: 3.540 ±(99.9%) 0.009 ms/op
Iteration   2: 3.535 ±(99.9%) 0.007 ms/op
Iteration   3: 3.505 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.527 ±(99.9%) 0.344 ms/op [Average]
  (min, avg, max) = (3.505, 3.527, 3.540), stdev = 0.019
  CI (99.9%): [3.182, 3.871] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.985 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.767 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.335 ±(99.9%) 0.007 ms/op
Iteration   1: 3.282 ±(99.9%) 0.012 ms/op
Iteration   2: 3.372 ±(99.9%) 0.009 ms/op
Iteration   3: 3.293 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.316 ±(99.9%) 0.898 ms/op [Average]
  (min, avg, max) = (3.282, 3.316, 3.372), stdev = 0.049
  CI (99.9%): [2.418, 4.214] (assumes normal distribution)


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
# Warmup Iteration   1: 8.616 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.785 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.550 ±(99.9%) 0.005 ms/op
Iteration   1: 3.360 ±(99.9%) 0.005 ms/op
Iteration   2: 3.287 ±(99.9%) 0.009 ms/op
Iteration   3: 3.469 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.372 ±(99.9%) 1.670 ms/op [Average]
  (min, avg, max) = (3.287, 3.372, 3.469), stdev = 0.092
  CI (99.9%): [1.702, 5.042] (assumes normal distribution)


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
# Warmup Iteration   1: 11.100 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.370 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.067 ±(99.9%) 0.008 ms/op
Iteration   1: 3.960 ±(99.9%) 0.010 ms/op
Iteration   2: 3.985 ±(99.9%) 0.014 ms/op
Iteration   3: 3.924 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.956 ±(99.9%) 0.561 ms/op [Average]
  (min, avg, max) = (3.924, 3.956, 3.985), stdev = 0.031
  CI (99.9%): [3.396, 4.517] (assumes normal distribution)


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
# Warmup Iteration   1: 9.878 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.932 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.538 ±(99.9%) 0.012 ms/op
Iteration   1: 3.527 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.466 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   5.972 ms/op
                 createUser·p0.999:  20.619 ms/op
                 createUser·p0.9999: 24.180 ms/op
                 createUser·p1.00:   29.622 ms/op

Iteration   2: 3.562 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.776 ms/op
                 createUser·p0.50:   3.449 ms/op
                 createUser·p0.90:   4.133 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  23.245 ms/op
                 createUser·p0.9999: 25.919 ms/op
                 createUser·p1.00:   31.195 ms/op

Iteration   3: 3.530 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.616 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   4.026 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  19.245 ms/op
                 createUser·p0.9999: 26.472 ms/op
                 createUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271058
  mean =      3.540 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6990 
    [ 2.500,  5.000) = 254874 
    [ 5.000,  7.500) = 8203 
    [ 7.500, 10.000) = 506 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 151 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.466 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     19.923 ms/op
     p(99.9900) =     26.178 ms/op
     p(99.9990) =     27.946 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


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
# Warmup Iteration   1: 8.345 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.699 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.378 ±(99.9%) 0.008 ms/op
Iteration   1: 3.314 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.681 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   4.014 ms/op
                 existUser·p0.99:   5.865 ms/op
                 existUser·p0.999:  10.434 ms/op
                 existUser·p0.9999: 24.412 ms/op
                 existUser·p1.00:   25.100 ms/op

Iteration   2: 3.345 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.710 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   5.644 ms/op
                 existUser·p0.999:  19.411 ms/op
                 existUser·p0.9999: 31.712 ms/op
                 existUser·p1.00:   32.735 ms/op

Iteration   3: 3.278 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.935 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  12.370 ms/op
                 existUser·p0.9999: 26.631 ms/op
                 existUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289681
  mean =      3.312 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5296 
    [ 2.500,  5.000) = 279653 
    [ 5.000,  7.500) = 3901 
    [ 7.500, 10.000) = 479 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     10.945 ms/op
     p(99.9900) =     31.031 ms/op
     p(99.9990) =     32.578 ms/op
     p(99.9999) =     32.735 ms/op
    p(100.0000) =     32.735 ms/op


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
# Warmup Iteration   1: 9.095 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.731 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.605 ±(99.9%) 0.011 ms/op
Iteration   1: 3.493 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.456 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   6.226 ms/op
                 getUser·p0.999:  20.298 ms/op
                 getUser·p0.9999: 23.701 ms/op
                 getUser·p1.00:   24.969 ms/op

Iteration   2: 3.368 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.804 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   5.718 ms/op
                 getUser·p0.999:  21.269 ms/op
                 getUser·p0.9999: 28.082 ms/op
                 getUser·p1.00:   29.360 ms/op

Iteration   3: 3.559 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.434 ms/op
                 getUser·p0.50:   3.441 ms/op
                 getUser·p0.90:   4.129 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   6.259 ms/op
                 getUser·p0.999:  19.595 ms/op
                 getUser·p0.9999: 25.201 ms/op
                 getUser·p1.00:   26.444 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276308
  mean =      3.471 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9025 
    [ 2.500,  5.000) = 259047 
    [ 5.000,  7.500) = 7043 
    [ 7.500, 10.000) = 766 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 162 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.434 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.144 ms/op
     p(99.9000) =     20.263 ms/op
     p(99.9900) =     26.226 ms/op
     p(99.9990) =     28.595 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


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
# Warmup Iteration   1: 12.161 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.576 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.238 ±(99.9%) 0.015 ms/op
Iteration   1: 4.162 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.851 ms/op
                 listUser·p0.50:   4.080 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  19.766 ms/op
                 listUser·p0.9999: 23.571 ms/op
                 listUser·p1.00:   24.805 ms/op

Iteration   2: 4.052 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.355 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.810 ms/op
                 listUser·p0.99:   8.192 ms/op
                 listUser·p0.999:  16.007 ms/op
                 listUser·p0.9999: 22.643 ms/op
                 listUser·p1.00:   23.888 ms/op

Iteration   3: 3.978 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  12.861 ms/op
                 listUser·p0.9999: 16.024 ms/op
                 listUser·p1.00:   16.073 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235921
  mean =      4.062 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47 
    [ 2.500,  5.000) = 227884 
    [ 5.000,  7.500) = 5426 
    [ 7.500, 10.000) = 1780 
    [10.000, 12.500) = 257 
    [12.500, 15.000) = 243 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.851 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      7.709 ms/op
     p(99.9000) =     15.942 ms/op
     p(99.9900) =     22.643 ms/op
     p(99.9990) =     24.280 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.135 ± 3.660  ops/ms
ClientPb.existUser                       thrpt       3   9.764 ± 3.588  ops/ms
ClientPb.getUser                         thrpt       3   9.261 ± 6.457  ops/ms
ClientPb.listUser                        thrpt       3   8.008 ± 4.765  ops/ms
ClientPb.createUser                       avgt       3   3.527 ± 0.344   ms/op
ClientPb.existUser                        avgt       3   3.316 ± 0.898   ms/op
ClientPb.getUser                          avgt       3   3.372 ± 1.670   ms/op
ClientPb.listUser                         avgt       3   3.956 ± 0.561   ms/op
ClientPb.createUser                     sample  271058   3.540 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.466           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.424           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.088           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.538           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.906           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.923           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.178           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.195           ms/op
ClientPb.existUser                      sample  289681   3.312 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.935           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.191           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.949           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.628           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.945           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.031           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.735           ms/op
ClientPb.getUser                        sample  276308   3.471 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.434           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.371           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.932           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.293           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.144           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.263           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.226           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.360           ms/op
ClientPb.listUser                       sample  235921   4.062 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.851           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.661           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.709           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.942           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.643           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.805           ms/op
