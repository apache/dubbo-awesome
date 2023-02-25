# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.406 ops/ms
# Warmup Iteration   2: 5.619 ops/ms
# Warmup Iteration   3: 8.867 ops/ms
Iteration   1: 9.387 ops/ms
Iteration   2: 9.905 ops/ms
Iteration   3: 9.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.694 ±(99.9%) 4.964 ops/ms [Average]
  (min, avg, max) = (9.387, 9.694, 9.905), stdev = 0.272
  CI (99.9%): [4.730, 14.658] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.236 ops/ms
# Warmup Iteration   2: 9.183 ops/ms
# Warmup Iteration   3: 10.272 ops/ms
Iteration   1: 10.178 ops/ms
Iteration   2: 10.621 ops/ms
Iteration   3: 10.366 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.388 ±(99.9%) 4.052 ops/ms [Average]
  (min, avg, max) = (10.178, 10.388, 10.621), stdev = 0.222
  CI (99.9%): [6.336, 14.440] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.515 ops/ms
# Warmup Iteration   2: 9.100 ops/ms
# Warmup Iteration   3: 10.012 ops/ms
Iteration   1: 10.069 ops/ms
Iteration   2: 9.712 ops/ms
Iteration   3: 9.609 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.796 ±(99.9%) 4.408 ops/ms [Average]
  (min, avg, max) = (9.609, 9.796, 10.069), stdev = 0.242
  CI (99.9%): [5.389, 14.204] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.876 ops/ms
# Warmup Iteration   2: 7.693 ops/ms
# Warmup Iteration   3: 8.344 ops/ms
Iteration   1: 8.597 ops/ms
Iteration   2: 8.559 ops/ms
Iteration   3: 8.455 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.537 ±(99.9%) 1.342 ops/ms [Average]
  (min, avg, max) = (8.455, 8.537, 8.597), stdev = 0.074
  CI (99.9%): [7.195, 9.878] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.118 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.407 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.340 ±(99.9%) 0.005 ms/op
Iteration   1: 3.155 ±(99.9%) 0.002 ms/op
Iteration   2: 3.125 ±(99.9%) 0.004 ms/op
Iteration   3: 3.150 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.143 ±(99.9%) 0.288 ms/op [Average]
  (min, avg, max) = (3.125, 3.143, 3.155), stdev = 0.016
  CI (99.9%): [2.856, 3.431] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.352 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.002 ms/op
Iteration   1: 3.007 ±(99.9%) 0.007 ms/op
Iteration   2: 3.301 ±(99.9%) 0.005 ms/op
Iteration   3: 3.111 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.140 ±(99.9%) 2.716 ms/op [Average]
  (min, avg, max) = (3.007, 3.140, 3.301), stdev = 0.149
  CI (99.9%): [0.424, 5.855] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.771 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.471 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.242 ±(99.9%) 0.003 ms/op
Iteration   1: 3.324 ±(99.9%) 0.005 ms/op
Iteration   2: 3.483 ±(99.9%) 0.006 ms/op
Iteration   3: 3.487 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.431 ±(99.9%) 1.701 ms/op [Average]
  (min, avg, max) = (3.324, 3.431, 3.487), stdev = 0.093
  CI (99.9%): [1.730, 5.133] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.577 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.051 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.894 ±(99.9%) 0.006 ms/op
Iteration   1: 3.796 ±(99.9%) 0.010 ms/op
Iteration   2: 3.762 ±(99.9%) 0.010 ms/op
Iteration   3: 3.838 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.799 ±(99.9%) 0.693 ms/op [Average]
  (min, avg, max) = (3.762, 3.799, 3.838), stdev = 0.038
  CI (99.9%): [3.106, 4.492] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.833 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.787 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.248 ±(99.9%) 0.008 ms/op
Iteration   1: 3.142 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.366 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  18.416 ms/op
                 createUser·p0.9999: 20.254 ms/op
                 createUser·p1.00:   21.365 ms/op

Iteration   2: 3.192 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.970 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  9.296 ms/op
                 createUser·p0.9999: 22.084 ms/op
                 createUser·p1.00:   23.298 ms/op

Iteration   3: 3.171 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.251 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.326 ms/op
                 createUser·p0.95:   3.588 ms/op
                 createUser·p0.99:   5.427 ms/op
                 createUser·p0.999:  15.668 ms/op
                 createUser·p0.9999: 18.514 ms/op
                 createUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302953
  mean =      3.168 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20896 
    [ 2.500,  5.000) = 276752 
    [ 5.000,  7.500) = 4405 
    [ 7.500, 10.000) = 380 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 168 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.970 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     15.974 ms/op
     p(99.9900) =     21.257 ms/op
     p(99.9990) =     23.002 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.731 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.353 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.006 ms/op
Iteration   1: 3.009 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.805 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.146 ms/op
                 existUser·p0.95:   3.367 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  9.005 ms/op
                 existUser·p0.9999: 19.300 ms/op
                 existUser·p1.00:   19.759 ms/op

Iteration   2: 3.024 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.675 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.416 ms/op
                 existUser·p0.99:   6.005 ms/op
                 existUser·p0.999:  11.554 ms/op
                 existUser·p0.9999: 20.428 ms/op
                 existUser·p1.00:   21.430 ms/op

Iteration   3: 3.015 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.544 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.461 ms/op
                 existUser·p0.99:   5.182 ms/op
                 existUser·p0.999:  11.764 ms/op
                 existUser·p0.9999: 20.470 ms/op
                 existUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 318315
  mean =      3.016 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13738 
    [ 2.500,  5.000) = 299856 
    [ 5.000,  7.500) = 4145 
    [ 7.500, 10.000) = 213 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 189 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.232 ms/op
     p(95.0000) =      3.428 ms/op
     p(99.0000) =      5.267 ms/op
     p(99.9000) =     11.540 ms/op
     p(99.9900) =     20.038 ms/op
     p(99.9990) =     21.144 ms/op
     p(99.9999) =     21.430 ms/op
    p(100.0000) =     21.430 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.698 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.356 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.342 ±(99.9%) 0.010 ms/op
Iteration   1: 3.189 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.257 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   6.496 ms/op
                 getUser·p0.999:  18.121 ms/op
                 getUser·p0.9999: 23.790 ms/op
                 getUser·p1.00:   24.609 ms/op

Iteration   2: 3.104 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.083 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.784 ms/op
                 getUser·p0.999:  13.119 ms/op
                 getUser·p0.9999: 28.901 ms/op
                 getUser·p1.00:   30.999 ms/op

Iteration   3: 3.321 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.432 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.985 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   6.382 ms/op
                 getUser·p0.999:  14.991 ms/op
                 getUser·p0.9999: 21.769 ms/op
                 getUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299750
  mean =      3.202 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16229 
    [ 2.500,  5.000) = 275004 
    [ 5.000,  7.500) = 7457 
    [ 7.500, 10.000) = 548 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =      6.144 ms/op
     p(99.9000) =     15.589 ms/op
     p(99.9900) =     27.004 ms/op
     p(99.9990) =     30.279 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.407 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.091 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.818 ±(99.9%) 0.011 ms/op
Iteration   1: 3.835 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.563 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   6.695 ms/op
                 listUser·p0.999:  15.565 ms/op
                 listUser·p0.9999: 23.680 ms/op
                 listUser·p1.00:   24.248 ms/op

Iteration   2: 3.702 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.351 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  12.681 ms/op
                 listUser·p0.9999: 17.400 ms/op
                 listUser·p1.00:   17.433 ms/op

Iteration   3: 3.848 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.085 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   7.897 ms/op
                 listUser·p0.999:  13.337 ms/op
                 listUser·p0.9999: 14.817 ms/op
                 listUser·p1.00:   15.237 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253061
  mean =      3.794 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 81 
    [ 2.500,  5.000) = 244081 
    [ 5.000,  7.500) = 6743 
    [ 7.500, 10.000) = 1463 
    [10.000, 12.500) = 320 
    [12.500, 15.000) = 218 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.174 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     13.926 ms/op
     p(99.9900) =     20.657 ms/op
     p(99.9990) =     23.982 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.694 ± 4.964  ops/ms
ClientPb.existUser                       thrpt       3  10.388 ± 4.052  ops/ms
ClientPb.getUser                         thrpt       3   9.796 ± 4.408  ops/ms
ClientPb.listUser                        thrpt       3   8.537 ± 1.342  ops/ms
ClientPb.createUser                       avgt       3   3.143 ± 0.288   ms/op
ClientPb.existUser                        avgt       3   3.140 ± 2.716   ms/op
ClientPb.getUser                          avgt       3   3.431 ± 1.701   ms/op
ClientPb.listUser                         avgt       3   3.799 ± 0.693   ms/op
ClientPb.createUser                     sample  302953   3.168 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.970           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.486           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.431           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.974           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.257           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.298           ms/op
ClientPb.existUser                      sample  318315   3.016 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.675           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.941           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.232           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.428           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.267           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.540           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.038           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.430           ms/op
ClientPb.getUser                        sample  299750   3.202 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.083           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.613           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.182           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.144           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.589           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.004           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.999           ms/op
ClientPb.listUser                       sample  253061   3.794 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.563           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.711           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.174           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.547           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.201           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.926           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.657           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.248           ms/op
