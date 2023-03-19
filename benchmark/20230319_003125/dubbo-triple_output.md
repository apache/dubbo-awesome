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
# Warmup Iteration   1: 2.143 ops/ms
# Warmup Iteration   2: 5.942 ops/ms
# Warmup Iteration   3: 8.609 ops/ms
Iteration   1: 9.365 ops/ms
Iteration   2: 9.461 ops/ms
Iteration   3: 9.490 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.439 ±(99.9%) 1.198 ops/ms [Average]
  (min, avg, max) = (9.365, 9.439, 9.490), stdev = 0.066
  CI (99.9%): [8.241, 10.637] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.204 ops/ms
# Warmup Iteration   2: 8.872 ops/ms
# Warmup Iteration   3: 9.620 ops/ms
Iteration   1: 9.779 ops/ms
Iteration   2: 9.710 ops/ms
Iteration   3: 10.049 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.846 ±(99.9%) 3.262 ops/ms [Average]
  (min, avg, max) = (9.710, 9.846, 10.049), stdev = 0.179
  CI (99.9%): [6.584, 13.108] (assumes normal distribution)


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
# Warmup Iteration   1: 2.856 ops/ms
# Warmup Iteration   2: 8.650 ops/ms
# Warmup Iteration   3: 9.173 ops/ms
Iteration   1: 9.129 ops/ms
Iteration   2: 9.064 ops/ms
Iteration   3: 9.390 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.194 ±(99.9%) 3.149 ops/ms [Average]
  (min, avg, max) = (9.064, 9.194, 9.390), stdev = 0.173
  CI (99.9%): [6.045, 12.343] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.790 ops/ms
# Warmup Iteration   2: 6.966 ops/ms
# Warmup Iteration   3: 7.821 ops/ms
Iteration   1: 7.847 ops/ms
Iteration   2: 7.964 ops/ms
Iteration   3: 8.041 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.951 ±(99.9%) 1.784 ops/ms [Average]
  (min, avg, max) = (7.847, 7.951, 8.041), stdev = 0.098
  CI (99.9%): [6.166, 9.735] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.286 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.631 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.554 ±(99.9%) 0.004 ms/op
Iteration   1: 3.444 ±(99.9%) 0.008 ms/op
Iteration   2: 3.385 ±(99.9%) 0.010 ms/op
Iteration   3: 3.296 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.375 ±(99.9%) 1.360 ms/op [Average]
  (min, avg, max) = (3.296, 3.375, 3.444), stdev = 0.075
  CI (99.9%): [2.015, 4.735] (assumes normal distribution)


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
# Warmup Iteration   1: 8.060 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.624 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.292 ±(99.9%) 0.005 ms/op
Iteration   1: 3.213 ±(99.9%) 0.008 ms/op
Iteration   2: 3.197 ±(99.9%) 0.004 ms/op
Iteration   3: 3.303 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.238 ±(99.9%) 1.045 ms/op [Average]
  (min, avg, max) = (3.197, 3.238, 3.303), stdev = 0.057
  CI (99.9%): [2.193, 4.283] (assumes normal distribution)


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
# Warmup Iteration   1: 9.326 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.560 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.409 ±(99.9%) 0.003 ms/op
Iteration   1: 3.281 ±(99.9%) 0.007 ms/op
Iteration   2: 3.341 ±(99.9%) 0.004 ms/op
Iteration   3: 3.260 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.294 ±(99.9%) 0.768 ms/op [Average]
  (min, avg, max) = (3.260, 3.294, 3.341), stdev = 0.042
  CI (99.9%): [2.526, 4.062] (assumes normal distribution)


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
# Warmup Iteration   1: 9.851 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.307 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.005 ±(99.9%) 0.007 ms/op
Iteration   1: 3.798 ±(99.9%) 0.015 ms/op
Iteration   2: 3.942 ±(99.9%) 0.010 ms/op
Iteration   3: 3.883 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.874 ±(99.9%) 1.316 ms/op [Average]
  (min, avg, max) = (3.798, 3.874, 3.942), stdev = 0.072
  CI (99.9%): [2.559, 5.190] (assumes normal distribution)


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
# Warmup Iteration   1: 9.820 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.920 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.426 ±(99.9%) 0.010 ms/op
Iteration   1: 3.361 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.804 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   5.841 ms/op
                 createUser·p0.999:  19.450 ms/op
                 createUser·p0.9999: 22.855 ms/op
                 createUser·p1.00:   24.642 ms/op

Iteration   2: 3.480 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.542 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.059 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   5.587 ms/op
                 createUser·p0.999:  21.791 ms/op
                 createUser·p0.9999: 24.719 ms/op
                 createUser·p1.00:   25.428 ms/op

Iteration   3: 3.451 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.356 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   4.030 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  8.725 ms/op
                 createUser·p0.9999: 25.579 ms/op
                 createUser·p1.00:   26.247 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279947
  mean =      3.430 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15925 
    [ 2.500,  5.000) = 255459 
    [ 5.000,  7.500) = 7839 
    [ 7.500, 10.000) = 409 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 130 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.542 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     11.272 ms/op
     p(99.9900) =     24.904 ms/op
     p(99.9990) =     26.221 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


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
# Warmup Iteration   1: 8.092 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.502 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.464 ±(99.9%) 0.009 ms/op
Iteration   1: 3.373 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.688 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.940 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  20.392 ms/op
                 existUser·p0.9999: 22.692 ms/op
                 existUser·p1.00:   23.626 ms/op

Iteration   2: 3.219 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.417 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  9.273 ms/op
                 existUser·p0.9999: 25.592 ms/op
                 existUser·p1.00:   26.313 ms/op

Iteration   3: 3.286 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.075 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   6.185 ms/op
                 existUser·p0.999:  17.672 ms/op
                 existUser·p0.9999: 26.509 ms/op
                 existUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291464
  mean =      3.291 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17483 
    [ 2.500,  5.000) = 268097 
    [ 5.000,  7.500) = 5097 
    [ 7.500, 10.000) = 484 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 111 
    [25.000, 27.500) = 48 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     11.331 ms/op
     p(99.9900) =     25.816 ms/op
     p(99.9990) =     28.413 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


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
# Warmup Iteration   1: 9.650 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.798 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.373 ±(99.9%) 0.010 ms/op
Iteration   1: 3.273 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.724 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  12.141 ms/op
                 getUser·p0.9999: 22.224 ms/op
                 getUser·p1.00:   23.200 ms/op

Iteration   2: 3.357 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.804 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   5.153 ms/op
                 getUser·p0.999:  20.751 ms/op
                 getUser·p0.9999: 24.067 ms/op
                 getUser·p1.00:   25.264 ms/op

Iteration   3: 3.486 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.327 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   4.030 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   6.504 ms/op
                 getUser·p0.999:  21.637 ms/op
                 getUser·p0.9999: 23.899 ms/op
                 getUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 284804
  mean =      3.370 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6022 
    [ 2.500,  5.000) = 272516 
    [ 5.000,  7.500) = 5215 
    [ 7.500, 10.000) = 576 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 214 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.327 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     20.814 ms/op
     p(99.9900) =     23.660 ms/op
     p(99.9990) =     24.745 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


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
# Warmup Iteration   1: 10.553 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.420 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.026 ±(99.9%) 0.013 ms/op
Iteration   1: 4.027 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.743 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   8.307 ms/op
                 listUser·p0.999:  21.483 ms/op
                 listUser·p0.9999: 28.489 ms/op
                 listUser·p1.00:   29.557 ms/op

Iteration   2: 3.993 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.356 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   7.479 ms/op
                 listUser·p0.999:  16.430 ms/op
                 listUser·p0.9999: 23.054 ms/op
                 listUser·p1.00:   23.134 ms/op

Iteration   3: 3.986 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.425 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   7.946 ms/op
                 listUser·p0.999:  15.085 ms/op
                 listUser·p0.9999: 18.546 ms/op
                 listUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239813
  mean =      4.002 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 229884 
    [ 5.000,  7.500) = 6911 
    [ 7.500, 10.000) = 1936 
    [10.000, 12.500) = 437 
    [12.500, 15.000) = 232 
    [15.000, 17.500) = 171 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.356 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      8.004 ms/op
     p(99.9000) =     16.466 ms/op
     p(99.9900) =     26.380 ms/op
     p(99.9990) =     29.124 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.439 ± 1.198  ops/ms
ClientPb.existUser                       thrpt       3   9.846 ± 3.262  ops/ms
ClientPb.getUser                         thrpt       3   9.194 ± 3.149  ops/ms
ClientPb.listUser                        thrpt       3   7.951 ± 1.784  ops/ms
ClientPb.createUser                       avgt       3   3.375 ± 1.360   ms/op
ClientPb.existUser                        avgt       3   3.238 ± 1.045   ms/op
ClientPb.getUser                          avgt       3   3.294 ± 0.768   ms/op
ClientPb.listUser                         avgt       3   3.874 ± 1.316   ms/op
ClientPb.createUser                     sample  279947   3.430 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.542           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.334           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.010           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.375           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.743           ms/op
ClientPb.createUser:createUser·p0.999   sample          11.272           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.904           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.247           ms/op
ClientPb.existUser                      sample  291464   3.291 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.075           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.228           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.699           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.055           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.505           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.331           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.816           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.508           ms/op
ClientPb.getUser                        sample  284804   3.370 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.327           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.252           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.756           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.035           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.833           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.814           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.660           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.264           ms/op
ClientPb.listUser                       sample  239813   4.002 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.356           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.826           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.751           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.004           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.466           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.380           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.557           ms/op
