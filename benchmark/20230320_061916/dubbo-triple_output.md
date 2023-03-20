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
# Warmup Iteration   1: 1.075 ops/ms
# Warmup Iteration   2: 2.582 ops/ms
# Warmup Iteration   3: 5.766 ops/ms
Iteration   1: 6.010 ops/ms
Iteration   2: 6.121 ops/ms
Iteration   3: 6.155 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.095 ±(99.9%) 1.382 ops/ms [Average]
  (min, avg, max) = (6.010, 6.095, 6.155), stdev = 0.076
  CI (99.9%): [4.714, 7.477] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.820 ops/ms
# Warmup Iteration   2: 5.456 ops/ms
# Warmup Iteration   3: 6.529 ops/ms
Iteration   1: 6.512 ops/ms
Iteration   2: 6.320 ops/ms
Iteration   3: 6.341 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.391 ±(99.9%) 1.919 ops/ms [Average]
  (min, avg, max) = (6.320, 6.391, 6.512), stdev = 0.105
  CI (99.9%): [4.472, 8.310] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.614 ops/ms
# Warmup Iteration   2: 4.457 ops/ms
# Warmup Iteration   3: 5.842 ops/ms
Iteration   1: 5.955 ops/ms
Iteration   2: 6.010 ops/ms
Iteration   3: 6.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.024 ±(99.9%) 1.402 ops/ms [Average]
  (min, avg, max) = (5.955, 6.024, 6.106), stdev = 0.077
  CI (99.9%): [4.621, 7.426] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.568 ops/ms
# Warmup Iteration   2: 3.998 ops/ms
# Warmup Iteration   3: 5.082 ops/ms
Iteration   1: 5.255 ops/ms
Iteration   2: 5.304 ops/ms
Iteration   3: 5.252 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.270 ±(99.9%) 0.528 ops/ms [Average]
  (min, avg, max) = (5.252, 5.270, 5.304), stdev = 0.029
  CI (99.9%): [4.743, 5.798] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 17.799 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 6.820 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.887 ±(99.9%) 0.012 ms/op
Iteration   1: 5.409 ±(99.9%) 0.019 ms/op
Iteration   2: 5.078 ±(99.9%) 0.017 ms/op
Iteration   3: 5.241 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.243 ±(99.9%) 3.024 ms/op [Average]
  (min, avg, max) = (5.078, 5.243, 5.409), stdev = 0.166
  CI (99.9%): [2.219, 8.266] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 14.929 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 6.025 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.253 ±(99.9%) 0.009 ms/op
Iteration   1: 4.919 ±(99.9%) 0.016 ms/op
Iteration   2: 4.885 ±(99.9%) 0.022 ms/op
Iteration   3: 5.021 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.942 ±(99.9%) 1.289 ms/op [Average]
  (min, avg, max) = (4.885, 4.942, 5.021), stdev = 0.071
  CI (99.9%): [3.652, 6.231] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 16.438 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 6.253 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.476 ±(99.9%) 0.008 ms/op
Iteration   1: 5.363 ±(99.9%) 0.009 ms/op
Iteration   2: 5.261 ±(99.9%) 0.009 ms/op
Iteration   3: 5.062 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.229 ±(99.9%) 2.794 ms/op [Average]
  (min, avg, max) = (5.062, 5.229, 5.363), stdev = 0.153
  CI (99.9%): [2.435, 8.023] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 18.172 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 7.110 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.377 ±(99.9%) 0.011 ms/op
Iteration   1: 6.308 ±(99.9%) 0.012 ms/op
Iteration   2: 6.430 ±(99.9%) 0.014 ms/op
Iteration   3: 6.153 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.297 ±(99.9%) 2.527 ms/op [Average]
  (min, avg, max) = (6.153, 6.297, 6.430), stdev = 0.138
  CI (99.9%): [3.770, 8.823] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 16.259 ±(99.9%) 0.281 ms/op
# Warmup Iteration   2: 6.751 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.592 ±(99.9%) 0.024 ms/op
Iteration   1: 5.486 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.208 ms/op
                 createUser·p0.50:   5.177 ms/op
                 createUser·p0.90:   6.840 ms/op
                 createUser·p0.95:   7.807 ms/op
                 createUser·p0.99:   10.416 ms/op
                 createUser·p0.999:  27.700 ms/op
                 createUser·p0.9999: 39.780 ms/op
                 createUser·p1.00:   40.763 ms/op

Iteration   2: 5.315 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.720 ms/op
                 createUser·p0.50:   4.964 ms/op
                 createUser·p0.90:   6.676 ms/op
                 createUser·p0.95:   7.537 ms/op
                 createUser·p0.99:   10.256 ms/op
                 createUser·p0.999:  23.739 ms/op
                 createUser·p0.9999: 28.606 ms/op
                 createUser·p1.00:   29.852 ms/op

Iteration   3: 5.220 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.066 ms/op
                 createUser·p0.50:   4.981 ms/op
                 createUser·p0.90:   6.365 ms/op
                 createUser·p0.95:   7.086 ms/op
                 createUser·p0.99:   9.622 ms/op
                 createUser·p0.999:  22.053 ms/op
                 createUser·p0.9999: 27.312 ms/op
                 createUser·p1.00:   31.621 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 179783
  mean =      5.338 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 86871 
    [ 5.000, 10.000) = 90968 
    [10.000, 15.000) = 1701 
    [15.000, 20.000) = 51 
    [20.000, 25.000) = 50 
    [25.000, 30.000) = 103 
    [30.000, 35.000) = 7 
    [35.000, 40.000) = 28 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.720 ms/op
     p(50.0000) =      5.038 ms/op
     p(90.0000) =      6.627 ms/op
     p(95.0000) =      7.504 ms/op
     p(99.0000) =     10.158 ms/op
     p(99.9000) =     23.436 ms/op
     p(99.9900) =     37.686 ms/op
     p(99.9990) =     40.763 ms/op
     p(99.9999) =     40.763 ms/op
    p(100.0000) =     40.763 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 16.794 ±(99.9%) 0.283 ms/op
# Warmup Iteration   2: 5.678 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.206 ±(99.9%) 0.020 ms/op
Iteration   1: 5.172 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.886 ms/op
                 existUser·p0.50:   4.825 ms/op
                 existUser·p0.90:   6.619 ms/op
                 existUser·p0.95:   7.660 ms/op
                 existUser·p0.99:   9.765 ms/op
                 existUser·p0.999:  22.282 ms/op
                 existUser·p0.9999: 29.060 ms/op
                 existUser·p1.00:   29.786 ms/op

Iteration   2: 4.838 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.437 ms/op
                 existUser·p0.50:   4.620 ms/op
                 existUser·p0.90:   5.857 ms/op
                 existUser·p0.95:   6.652 ms/op
                 existUser·p0.99:   8.897 ms/op
                 existUser·p0.999:  16.866 ms/op
                 existUser·p0.9999: 24.431 ms/op
                 existUser·p1.00:   25.592 ms/op

Iteration   3: 5.126 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.048 ms/op
                 existUser·p0.50:   4.792 ms/op
                 existUser·p0.90:   6.414 ms/op
                 existUser·p0.95:   7.537 ms/op
                 existUser·p0.99:   9.699 ms/op
                 existUser·p0.999:  22.848 ms/op
                 existUser·p0.9999: 26.632 ms/op
                 existUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 190412
  mean =      5.041 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 76 
    [ 2.500,  5.000) = 123853 
    [ 5.000,  7.500) = 57997 
    [ 7.500, 10.000) = 7086 
    [10.000, 12.500) = 925 
    [12.500, 15.000) = 210 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.886 ms/op
     p(50.0000) =      4.727 ms/op
     p(90.0000) =      6.308 ms/op
     p(95.0000) =      7.291 ms/op
     p(99.0000) =      9.519 ms/op
     p(99.9000) =     21.710 ms/op
     p(99.9900) =     26.736 ms/op
     p(99.9990) =     29.431 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 18.067 ±(99.9%) 0.325 ms/op
# Warmup Iteration   2: 6.131 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.400 ±(99.9%) 0.021 ms/op
Iteration   1: 5.216 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.116 ms/op
                 getUser·p0.50:   4.940 ms/op
                 getUser·p0.90:   6.316 ms/op
                 getUser·p0.95:   7.389 ms/op
                 getUser·p0.99:   10.158 ms/op
                 getUser·p0.999:  24.056 ms/op
                 getUser·p0.9999: 30.962 ms/op
                 getUser·p1.00:   31.621 ms/op

Iteration   2: 5.192 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.384 ms/op
                 getUser·p0.50:   4.817 ms/op
                 getUser·p0.90:   6.525 ms/op
                 getUser·p0.95:   7.856 ms/op
                 getUser·p0.99:   10.797 ms/op
                 getUser·p0.999:  27.853 ms/op
                 getUser·p0.9999: 36.014 ms/op
                 getUser·p1.00:   36.176 ms/op

Iteration   3: 5.335 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.421 ms/op
                 getUser·p0.50:   5.087 ms/op
                 getUser·p0.90:   6.611 ms/op
                 getUser·p0.95:   7.627 ms/op
                 getUser·p0.99:   9.355 ms/op
                 getUser·p0.999:  12.141 ms/op
                 getUser·p0.9999: 28.803 ms/op
                 getUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 182808
  mean =      5.247 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 96990 
    [ 5.000,  7.500) = 75692 
    [ 7.500, 10.000) = 8331 
    [10.000, 12.500) = 1263 
    [12.500, 15.000) = 295 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.116 ms/op
     p(50.0000) =      4.948 ms/op
     p(90.0000) =      6.488 ms/op
     p(95.0000) =      7.660 ms/op
     p(99.0000) =      9.978 ms/op
     p(99.9000) =     19.575 ms/op
     p(99.9900) =     34.257 ms/op
     p(99.9990) =     36.176 ms/op
     p(99.9999) =     36.176 ms/op
    p(100.0000) =     36.176 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 18.659 ±(99.9%) 0.328 ms/op
# Warmup Iteration   2: 7.473 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 6.690 ±(99.9%) 0.026 ms/op
Iteration   1: 6.423 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.998 ms/op
                 listUser·p0.50:   5.931 ms/op
                 listUser·p0.90:   8.249 ms/op
                 listUser·p0.95:   9.634 ms/op
                 listUser·p0.99:   13.091 ms/op
                 listUser·p0.999:  29.413 ms/op
                 listUser·p0.9999: 32.969 ms/op
                 listUser·p1.00:   35.783 ms/op

Iteration   2: 6.109 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   3.101 ms/op
                 listUser·p0.50:   5.751 ms/op
                 listUser·p0.90:   7.381 ms/op
                 listUser·p0.95:   8.634 ms/op
                 listUser·p0.99:   11.118 ms/op
                 listUser·p0.999:  29.000 ms/op
                 listUser·p0.9999: 32.629 ms/op
                 listUser·p1.00:   33.751 ms/op

Iteration   3: 6.175 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   5.898 ms/op
                 listUser·p0.90:   7.373 ms/op
                 listUser·p0.95:   8.167 ms/op
                 listUser·p0.99:   11.370 ms/op
                 listUser·p0.999:  26.138 ms/op
                 listUser·p0.9999: 33.428 ms/op
                 listUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 153965
  mean =      6.233 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 10533 
    [ 5.000,  7.500) = 127011 
    [ 7.500, 10.000) = 12348 
    [10.000, 12.500) = 2931 
    [12.500, 15.000) = 568 
    [15.000, 17.500) = 196 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 95 
    [30.000, 32.500) = 68 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.331 ms/op
     p(50.0000) =      5.857 ms/op
     p(90.0000) =      7.594 ms/op
     p(95.0000) =      8.929 ms/op
     p(99.0000) =     11.862 ms/op
     p(99.9000) =     28.608 ms/op
     p(99.9900) =     32.952 ms/op
     p(99.9990) =     34.898 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.095 ± 1.382  ops/ms
ClientPb.existUser                       thrpt       3   6.391 ± 1.919  ops/ms
ClientPb.getUser                         thrpt       3   6.024 ± 1.402  ops/ms
ClientPb.listUser                        thrpt       3   5.270 ± 0.528  ops/ms
ClientPb.createUser                       avgt       3   5.243 ± 3.024   ms/op
ClientPb.existUser                        avgt       3   4.942 ± 1.289   ms/op
ClientPb.getUser                          avgt       3   5.229 ± 2.794   ms/op
ClientPb.listUser                         avgt       3   6.297 ± 2.527   ms/op
ClientPb.createUser                     sample  179783   5.338 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.720           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.038           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.627           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.504           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.158           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.436           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.686           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.763           ms/op
ClientPb.existUser                      sample  190412   5.041 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.886           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.727           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.308           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.291           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.519           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.710           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.736           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.786           ms/op
ClientPb.getUser                        sample  182808   5.247 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.116           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.948           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.488           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.660           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.978           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.575           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.257           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.176           ms/op
ClientPb.listUser                       sample  153965   6.233 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.331           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.857           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.594           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.929           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.862           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.608           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.952           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.783           ms/op
