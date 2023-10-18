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
# Warmup Iteration   1: 0.943 ops/ms
# Warmup Iteration   2: 2.115 ops/ms
# Warmup Iteration   3: 4.207 ops/ms
Iteration   1: 5.276 ops/ms
Iteration   2: 5.472 ops/ms
Iteration   3: 5.235 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.328 ±(99.9%) 2.310 ops/ms [Average]
  (min, avg, max) = (5.235, 5.328, 5.472), stdev = 0.127
  CI (99.9%): [3.018, 7.638] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 1.510 ops/ms
# Warmup Iteration   2: 5.023 ops/ms
# Warmup Iteration   3: 5.641 ops/ms
Iteration   1: 5.592 ops/ms
Iteration   2: 5.679 ops/ms
Iteration   3: 5.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.660 ±(99.9%) 1.097 ops/ms [Average]
  (min, avg, max) = (5.592, 5.660, 5.708), stdev = 0.060
  CI (99.9%): [4.562, 6.757] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.461 ops/ms
# Warmup Iteration   2: 4.180 ops/ms
# Warmup Iteration   3: 5.329 ops/ms
Iteration   1: 5.431 ops/ms
Iteration   2: 5.224 ops/ms
Iteration   3: 5.278 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.311 ±(99.9%) 1.956 ops/ms [Average]
  (min, avg, max) = (5.224, 5.311, 5.431), stdev = 0.107
  CI (99.9%): [3.355, 7.267] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.349 ops/ms
# Warmup Iteration   2: 3.232 ops/ms
# Warmup Iteration   3: 4.407 ops/ms
Iteration   1: 4.583 ops/ms
Iteration   2: 4.752 ops/ms
Iteration   3: 4.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.709 ±(99.9%) 2.020 ops/ms [Average]
  (min, avg, max) = (4.583, 4.709, 4.792), stdev = 0.111
  CI (99.9%): [2.689, 6.729] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 19.699 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 7.023 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.360 ±(99.9%) 0.009 ms/op
Iteration   1: 6.023 ±(99.9%) 0.009 ms/op
Iteration   2: 5.740 ±(99.9%) 0.013 ms/op
Iteration   3: 5.841 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.868 ±(99.9%) 2.621 ms/op [Average]
  (min, avg, max) = (5.740, 5.868, 6.023), stdev = 0.144
  CI (99.9%): [3.247, 8.489] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 18.687 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 6.896 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.809 ±(99.9%) 0.013 ms/op
Iteration   1: 5.472 ±(99.9%) 0.008 ms/op
Iteration   2: 5.913 ±(99.9%) 0.011 ms/op
Iteration   3: 5.768 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.717 ±(99.9%) 4.101 ms/op [Average]
  (min, avg, max) = (5.472, 5.717, 5.913), stdev = 0.225
  CI (99.9%): [1.616, 9.819] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 20.361 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 7.627 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 6.076 ±(99.9%) 0.007 ms/op
Iteration   1: 5.889 ±(99.9%) 0.008 ms/op
Iteration   2: 5.681 ±(99.9%) 0.014 ms/op
Iteration   3: 5.910 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.827 ±(99.9%) 2.316 ms/op [Average]
  (min, avg, max) = (5.681, 5.827, 5.910), stdev = 0.127
  CI (99.9%): [3.511, 8.142] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 21.938 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 9.468 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 7.110 ±(99.9%) 0.015 ms/op
Iteration   1: 6.853 ±(99.9%) 0.009 ms/op
Iteration   2: 6.815 ±(99.9%) 0.013 ms/op
Iteration   3: 6.663 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.777 ±(99.9%) 1.841 ms/op [Average]
  (min, avg, max) = (6.663, 6.777, 6.853), stdev = 0.101
  CI (99.9%): [4.936, 8.618] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 20.692 ±(99.9%) 0.391 ms/op
# Warmup Iteration   2: 7.835 ±(99.9%) 0.062 ms/op
# Warmup Iteration   3: 6.216 ±(99.9%) 0.030 ms/op
Iteration   1: 5.976 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   1.061 ms/op
                 createUser·p0.50:   5.530 ms/op
                 createUser·p0.90:   7.905 ms/op
                 createUser·p0.95:   9.208 ms/op
                 createUser·p0.99:   12.927 ms/op
                 createUser·p0.999:  25.966 ms/op
                 createUser·p0.9999: 29.938 ms/op
                 createUser·p1.00:   30.540 ms/op

Iteration   2: 5.902 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   2.544 ms/op
                 createUser·p0.50:   5.439 ms/op
                 createUser·p0.90:   7.569 ms/op
                 createUser·p0.95:   9.175 ms/op
                 createUser·p0.99:   12.534 ms/op
                 createUser·p0.999:  29.813 ms/op
                 createUser·p0.9999: 32.544 ms/op
                 createUser·p1.00:   34.537 ms/op

Iteration   3: 5.933 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   2.654 ms/op
                 createUser·p0.50:   5.456 ms/op
                 createUser·p0.90:   7.586 ms/op
                 createUser·p0.95:   9.273 ms/op
                 createUser·p0.99:   13.173 ms/op
                 createUser·p0.999:  32.369 ms/op
                 createUser·p0.9999: 39.951 ms/op
                 createUser·p1.00:   40.174 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 161606
  mean =      5.937 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 42330 
    [ 5.000, 10.000) = 113819 
    [10.000, 15.000) = 4760 
    [15.000, 20.000) = 461 
    [20.000, 25.000) = 46 
    [25.000, 30.000) = 71 
    [30.000, 35.000) = 98 
    [35.000, 40.000) = 17 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      5.472 ms/op
     p(90.0000) =      7.700 ms/op
     p(95.0000) =      9.224 ms/op
     p(99.0000) =     12.894 ms/op
     p(99.9000) =     27.472 ms/op
     p(99.9900) =     35.609 ms/op
     p(99.9990) =     40.133 ms/op
     p(99.9999) =     40.174 ms/op
    p(100.0000) =     40.174 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 19.057 ±(99.9%) 0.327 ms/op
# Warmup Iteration   2: 6.897 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 6.176 ±(99.9%) 0.034 ms/op
Iteration   1: 5.819 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   2.241 ms/op
                 existUser·p0.50:   5.374 ms/op
                 existUser·p0.90:   7.496 ms/op
                 existUser·p0.95:   9.191 ms/op
                 existUser·p0.99:   13.418 ms/op
                 existUser·p0.999:  18.678 ms/op
                 existUser·p0.9999: 30.557 ms/op
                 existUser·p1.00:   31.261 ms/op

Iteration   2: 5.920 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   2.372 ms/op
                 existUser·p0.50:   5.341 ms/op
                 existUser·p0.90:   8.135 ms/op
                 existUser·p0.95:   9.699 ms/op
                 existUser·p0.99:   13.582 ms/op
                 existUser·p0.999:  31.340 ms/op
                 existUser·p0.9999: 34.669 ms/op
                 existUser·p1.00:   34.931 ms/op

Iteration   3: 5.835 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   2.376 ms/op
                 existUser·p0.50:   5.292 ms/op
                 existUser·p0.90:   7.627 ms/op
                 existUser·p0.95:   9.388 ms/op
                 existUser·p0.99:   13.435 ms/op
                 existUser·p0.999:  33.128 ms/op
                 existUser·p0.9999: 37.849 ms/op
                 existUser·p1.00:   38.863 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 163798
  mean =      5.857 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 51729 
    [ 5.000,  7.500) = 93788 
    [ 7.500, 10.000) = 11951 
    [10.000, 12.500) = 4005 
    [12.500, 15.000) = 1432 
    [15.000, 17.500) = 431 
    [17.500, 20.000) = 195 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 53 
    [32.500, 35.000) = 49 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      2.241 ms/op
     p(50.0000) =      5.333 ms/op
     p(90.0000) =      7.758 ms/op
     p(95.0000) =      9.454 ms/op
     p(99.0000) =     13.435 ms/op
     p(99.9000) =     24.098 ms/op
     p(99.9900) =     37.593 ms/op
     p(99.9990) =     38.779 ms/op
     p(99.9999) =     38.863 ms/op
    p(100.0000) =     38.863 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 19.924 ±(99.9%) 0.367 ms/op
# Warmup Iteration   2: 7.733 ±(99.9%) 0.057 ms/op
# Warmup Iteration   3: 5.946 ±(99.9%) 0.025 ms/op
Iteration   1: 5.947 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.540 ms/op
                 getUser·p0.50:   5.439 ms/op
                 getUser·p0.90:   8.028 ms/op
                 getUser·p0.95:   9.454 ms/op
                 getUser·p0.99:   12.927 ms/op
                 getUser·p0.999:  18.526 ms/op
                 getUser·p0.9999: 30.838 ms/op
                 getUser·p1.00:   32.637 ms/op

Iteration   2: 6.159 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   2.806 ms/op
                 getUser·p0.50:   5.554 ms/op
                 getUser·p0.90:   8.290 ms/op
                 getUser·p0.95:   9.994 ms/op
                 getUser·p0.99:   14.778 ms/op
                 getUser·p0.999:  31.362 ms/op
                 getUser·p0.9999: 35.586 ms/op
                 getUser·p1.00:   35.586 ms/op

Iteration   3: 5.912 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   2.032 ms/op
                 getUser·p0.50:   5.423 ms/op
                 getUser·p0.90:   7.561 ms/op
                 getUser·p0.95:   9.601 ms/op
                 getUser·p0.99:   13.532 ms/op
                 getUser·p0.999:  30.785 ms/op
                 getUser·p0.9999: 33.233 ms/op
                 getUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 159828
  mean =      6.004 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 39783 
    [ 5.000,  7.500) = 100494 
    [ 7.500, 10.000) = 12472 
    [10.000, 12.500) = 4536 
    [12.500, 15.000) = 1479 
    [15.000, 17.500) = 577 
    [17.500, 20.000) = 194 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 99 
    [32.500, 35.000) = 40 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      2.032 ms/op
     p(50.0000) =      5.472 ms/op
     p(90.0000) =      8.004 ms/op
     p(95.0000) =      9.683 ms/op
     p(99.0000) =     13.795 ms/op
     p(99.9000) =     29.557 ms/op
     p(99.9900) =     33.458 ms/op
     p(99.9990) =     35.586 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


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
# Warmup Iteration   1: 22.059 ±(99.9%) 0.433 ms/op
# Warmup Iteration   2: 11.626 ±(99.9%) 0.115 ms/op
# Warmup Iteration   3: 7.693 ±(99.9%) 0.050 ms/op
Iteration   1: 7.007 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   2.802 ms/op
                 listUser·p0.50:   6.398 ms/op
                 listUser·p0.90:   9.078 ms/op
                 listUser·p0.95:   10.830 ms/op
                 listUser·p0.99:   15.811 ms/op
                 listUser·p0.999:  27.045 ms/op
                 listUser·p0.9999: 30.796 ms/op
                 listUser·p1.00:   32.408 ms/op

Iteration   2: 6.929 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   2.568 ms/op
                 listUser·p0.50:   6.447 ms/op
                 listUser·p0.90:   8.667 ms/op
                 listUser·p0.95:   10.224 ms/op
                 listUser·p0.99:   14.434 ms/op
                 listUser·p0.999:  33.686 ms/op
                 listUser·p0.9999: 35.873 ms/op
                 listUser·p1.00:   38.011 ms/op

Iteration   3: 6.947 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   2.949 ms/op
                 listUser·p0.50:   6.390 ms/op
                 listUser·p0.90:   8.503 ms/op
                 listUser·p0.95:   10.831 ms/op
                 listUser·p0.99:   15.073 ms/op
                 listUser·p0.999:  34.342 ms/op
                 listUser·p0.9999: 36.373 ms/op
                 listUser·p1.00:   37.814 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 137776
  mean =      6.961 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 3093 
    [ 5.000,  7.500) = 106820 
    [ 7.500, 10.000) = 19241 
    [10.000, 12.500) = 4960 
    [12.500, 15.000) = 2158 
    [15.000, 17.500) = 724 
    [17.500, 20.000) = 400 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 97 
    [35.000, 37.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      2.568 ms/op
     p(50.0000) =      6.414 ms/op
     p(90.0000) =      8.798 ms/op
     p(95.0000) =     10.617 ms/op
     p(99.0000) =     15.286 ms/op
     p(99.9000) =     32.553 ms/op
     p(99.9900) =     35.994 ms/op
     p(99.9990) =     37.937 ms/op
     p(99.9999) =     38.011 ms/op
    p(100.0000) =     38.011 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.328 ± 2.310  ops/ms
ClientPb.existUser                       thrpt       3   5.660 ± 1.097  ops/ms
ClientPb.getUser                         thrpt       3   5.311 ± 1.956  ops/ms
ClientPb.listUser                        thrpt       3   4.709 ± 2.020  ops/ms
ClientPb.createUser                       avgt       3   5.868 ± 2.621   ms/op
ClientPb.existUser                        avgt       3   5.717 ± 4.101   ms/op
ClientPb.getUser                          avgt       3   5.827 ± 2.316   ms/op
ClientPb.listUser                         avgt       3   6.777 ± 1.841   ms/op
ClientPb.createUser                     sample  161606   5.937 ± 0.015   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.061           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.472           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.700           ms/op
ClientPb.createUser:createUser·p0.95    sample           9.224           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.894           ms/op
ClientPb.createUser:createUser·p0.999   sample          27.472           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.609           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.174           ms/op
ClientPb.existUser                      sample  163798   5.857 ± 0.016   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.241           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.333           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.758           ms/op
ClientPb.existUser:existUser·p0.95      sample           9.454           ms/op
ClientPb.existUser:existUser·p0.99      sample          13.435           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.098           ms/op
ClientPb.existUser:existUser·p0.9999    sample          37.593           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.863           ms/op
ClientPb.getUser                        sample  159828   6.004 ± 0.017   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.032           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.472           ms/op
ClientPb.getUser:getUser·p0.90          sample           8.004           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.683           ms/op
ClientPb.getUser:getUser·p0.99          sample          13.795           ms/op
ClientPb.getUser:getUser·p0.999         sample          29.557           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.458           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.586           ms/op
ClientPb.listUser                       sample  137776   6.961 ± 0.019   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.568           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.414           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.798           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.617           ms/op
ClientPb.listUser:listUser·p0.99        sample          15.286           ms/op
ClientPb.listUser:listUser·p0.999       sample          32.553           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.994           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.011           ms/op
