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
# Warmup Iteration   1: 2.233 ops/ms
# Warmup Iteration   2: 5.550 ops/ms
# Warmup Iteration   3: 8.498 ops/ms
Iteration   1: 8.925 ops/ms
Iteration   2: 8.690 ops/ms
Iteration   3: 9.693 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.103 ±(99.9%) 9.572 ops/ms [Average]
  (min, avg, max) = (8.690, 9.103, 9.693), stdev = 0.525
  CI (99.9%): [≈ 0, 18.675] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.166 ops/ms
# Warmup Iteration   2: 8.727 ops/ms
# Warmup Iteration   3: 9.498 ops/ms
Iteration   1: 9.710 ops/ms
Iteration   2: 9.568 ops/ms
Iteration   3: 9.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.662 ±(99.9%) 1.486 ops/ms [Average]
  (min, avg, max) = (9.568, 9.662, 9.710), stdev = 0.081
  CI (99.9%): [8.176, 11.148] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.296 ops/ms
# Warmup Iteration   2: 8.577 ops/ms
# Warmup Iteration   3: 8.952 ops/ms
Iteration   1: 9.215 ops/ms
Iteration   2: 9.364 ops/ms
Iteration   3: 9.532 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.370 ±(99.9%) 2.893 ops/ms [Average]
  (min, avg, max) = (9.215, 9.370, 9.532), stdev = 0.159
  CI (99.9%): [6.477, 12.264] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.749 ops/ms
# Warmup Iteration   2: 7.431 ops/ms
# Warmup Iteration   3: 7.511 ops/ms
Iteration   1: 8.029 ops/ms
Iteration   2: 7.955 ops/ms
Iteration   3: 8.110 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.031 ±(99.9%) 1.416 ops/ms [Average]
  (min, avg, max) = (7.955, 8.031, 8.110), stdev = 0.078
  CI (99.9%): [6.615, 9.447] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.905 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.849 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.504 ±(99.9%) 0.006 ms/op
Iteration   1: 3.463 ±(99.9%) 0.005 ms/op
Iteration   2: 3.537 ±(99.9%) 0.004 ms/op
Iteration   3: 3.357 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.452 ±(99.9%) 1.657 ms/op [Average]
  (min, avg, max) = (3.357, 3.452, 3.537), stdev = 0.091
  CI (99.9%): [1.795, 5.109] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.931 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.551 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.466 ±(99.9%) 0.006 ms/op
Iteration   1: 3.259 ±(99.9%) 0.009 ms/op
Iteration   2: 3.310 ±(99.9%) 0.010 ms/op
Iteration   3: 3.348 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.306 ±(99.9%) 0.820 ms/op [Average]
  (min, avg, max) = (3.259, 3.306, 3.348), stdev = 0.045
  CI (99.9%): [2.486, 4.126] (assumes normal distribution)


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
# Warmup Iteration   1: 9.757 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.661 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.548 ±(99.9%) 0.005 ms/op
Iteration   1: 3.384 ±(99.9%) 0.007 ms/op
Iteration   2: 3.465 ±(99.9%) 0.010 ms/op
Iteration   3: 3.468 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.439 ±(99.9%) 0.869 ms/op [Average]
  (min, avg, max) = (3.384, 3.439, 3.468), stdev = 0.048
  CI (99.9%): [2.571, 4.308] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.067 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.379 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.125 ±(99.9%) 0.005 ms/op
Iteration   1: 4.022 ±(99.9%) 0.008 ms/op
Iteration   2: 3.957 ±(99.9%) 0.012 ms/op
Iteration   3: 3.941 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.973 ±(99.9%) 0.781 ms/op [Average]
  (min, avg, max) = (3.941, 3.973, 4.022), stdev = 0.043
  CI (99.9%): [3.192, 4.754] (assumes normal distribution)


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
# Warmup Iteration   1: 9.260 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.825 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.597 ±(99.9%) 0.011 ms/op
Iteration   1: 3.503 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.370 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.985 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  19.916 ms/op
                 createUser·p0.9999: 23.622 ms/op
                 createUser·p1.00:   24.019 ms/op

Iteration   2: 3.340 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.489 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.559 ms/op
                 createUser·p0.99:   4.467 ms/op
                 createUser·p0.999:  22.832 ms/op
                 createUser·p0.9999: 29.023 ms/op
                 createUser·p1.00:   31.195 ms/op

Iteration   3: 3.476 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.862 ms/op
                 createUser·p0.50:   3.478 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.497 ms/op
                 createUser·p0.999:  17.924 ms/op
                 createUser·p0.9999: 24.216 ms/op
                 createUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278940
  mean =      3.438 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11152 
    [ 2.500,  5.000) = 262728 
    [ 5.000,  7.500) = 4108 
    [ 7.500, 10.000) = 503 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 126 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.370 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     18.254 ms/op
     p(99.9900) =     28.158 ms/op
     p(99.9990) =     29.629 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


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
# Warmup Iteration   1: 8.653 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.632 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.514 ±(99.9%) 0.011 ms/op
Iteration   1: 3.315 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.589 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   4.002 ms/op
                 existUser·p0.99:   5.857 ms/op
                 existUser·p0.999:  15.350 ms/op
                 existUser·p0.9999: 31.174 ms/op
                 existUser·p1.00:   31.916 ms/op

Iteration   2: 3.233 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.237 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  12.977 ms/op
                 existUser·p0.9999: 26.644 ms/op
                 existUser·p1.00:   27.460 ms/op

Iteration   3: 3.236 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.577 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  14.451 ms/op
                 existUser·p0.9999: 28.036 ms/op
                 existUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294323
  mean =      3.261 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15852 
    [ 2.500,  5.000) = 273465 
    [ 5.000,  7.500) = 3924 
    [ 7.500, 10.000) = 619 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     14.369 ms/op
     p(99.9900) =     30.184 ms/op
     p(99.9990) =     31.598 ms/op
     p(99.9999) =     31.916 ms/op
    p(100.0000) =     31.916 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.607 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.823 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.545 ±(99.9%) 0.011 ms/op
Iteration   1: 3.455 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.083 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   4.071 ms/op
                 getUser·p0.99:   6.884 ms/op
                 getUser·p0.999:  19.806 ms/op
                 getUser·p0.9999: 22.593 ms/op
                 getUser·p1.00:   23.691 ms/op

Iteration   2: 3.569 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.766 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.792 ms/op
                 getUser·p0.99:   7.209 ms/op
                 getUser·p0.999:  22.130 ms/op
                 getUser·p0.9999: 25.137 ms/op
                 getUser·p1.00:   25.788 ms/op

Iteration   3: 3.574 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.745 ms/op
                 getUser·p0.50:   3.432 ms/op
                 getUser·p0.90:   4.125 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   6.349 ms/op
                 getUser·p0.999:  15.443 ms/op
                 getUser·p0.9999: 33.886 ms/op
                 getUser·p1.00:   36.307 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271600
  mean =      3.532 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7639 
    [ 2.500,  5.000) = 253814 
    [ 5.000,  7.500) = 8542 
    [ 7.500, 10.000) = 995 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     17.577 ms/op
     p(99.9900) =     30.314 ms/op
     p(99.9990) =     35.998 ms/op
     p(99.9999) =     36.307 ms/op
    p(100.0000) =     36.307 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.581 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.648 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.180 ±(99.9%) 0.012 ms/op
Iteration   1: 4.190 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.251 ms/op
                 listUser·p0.50:   4.022 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   8.454 ms/op
                 listUser·p0.999:  18.011 ms/op
                 listUser·p0.9999: 22.327 ms/op
                 listUser·p1.00:   22.708 ms/op

Iteration   2: 4.096 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.561 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   7.520 ms/op
                 listUser·p0.999:  15.712 ms/op
                 listUser·p0.9999: 17.714 ms/op
                 listUser·p1.00:   18.448 ms/op

Iteration   3: 4.039 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   6.504 ms/op
                 listUser·p0.999:  15.090 ms/op
                 listUser·p0.9999: 20.155 ms/op
                 listUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233483
  mean =      4.108 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 225246 
    [ 5.000,  7.500) = 5698 
    [ 7.500, 10.000) = 1674 
    [10.000, 12.500) = 336 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 215 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.251 ms/op
     p(50.0000) =      3.981 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      7.684 ms/op
     p(99.9000) =     16.122 ms/op
     p(99.9900) =     21.014 ms/op
     p(99.9990) =     22.522 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.103 ± 9.572  ops/ms
ClientPb.existUser                       thrpt       3   9.662 ± 1.486  ops/ms
ClientPb.getUser                         thrpt       3   9.370 ± 2.893  ops/ms
ClientPb.listUser                        thrpt       3   8.031 ± 1.416  ops/ms
ClientPb.createUser                       avgt       3   3.452 ± 1.657   ms/op
ClientPb.existUser                        avgt       3   3.306 ± 0.820   ms/op
ClientPb.getUser                          avgt       3   3.439 ± 0.869   ms/op
ClientPb.listUser                         avgt       3   3.973 ± 0.781   ms/op
ClientPb.createUser                     sample  278940   3.438 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.370           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.400           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.096           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.530           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.254           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.158           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.195           ms/op
ClientPb.existUser                      sample  294323   3.261 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.237           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.195           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.486           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.772           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.726           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.369           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.184           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.916           ms/op
ClientPb.getUser                        sample  271600   3.532 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.766           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.383           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.051           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.497           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.037           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.577           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.314           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.307           ms/op
ClientPb.listUser                       sample  233483   4.108 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.251           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.981           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.751           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.684           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.122           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.014           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.708           ms/op
