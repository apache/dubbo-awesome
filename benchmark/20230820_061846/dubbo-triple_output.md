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
# Warmup Iteration   1: 1.074 ops/ms
# Warmup Iteration   2: 2.404 ops/ms
# Warmup Iteration   3: 5.092 ops/ms
Iteration   1: 5.500 ops/ms
Iteration   2: 5.470 ops/ms
Iteration   3: 5.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.499 ±(99.9%) 0.534 ops/ms [Average]
  (min, avg, max) = (5.470, 5.499, 5.529), stdev = 0.029
  CI (99.9%): [4.965, 6.033] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.505 ops/ms
# Warmup Iteration   2: 4.387 ops/ms
# Warmup Iteration   3: 5.897 ops/ms
Iteration   1: 5.912 ops/ms
Iteration   2: 6.079 ops/ms
Iteration   3: 6.037 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.010 ±(99.9%) 1.580 ops/ms [Average]
  (min, avg, max) = (5.912, 6.010, 6.079), stdev = 0.087
  CI (99.9%): [4.430, 7.589] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.665 ops/ms
# Warmup Iteration   2: 4.540 ops/ms
# Warmup Iteration   3: 5.698 ops/ms
Iteration   1: 5.734 ops/ms
Iteration   2: 5.638 ops/ms
Iteration   3: 5.921 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.764 ±(99.9%) 2.628 ops/ms [Average]
  (min, avg, max) = (5.638, 5.764, 5.921), stdev = 0.144
  CI (99.9%): [3.136, 8.392] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.518 ops/ms
# Warmup Iteration   2: 3.779 ops/ms
# Warmup Iteration   3: 5.047 ops/ms
Iteration   1: 5.035 ops/ms
Iteration   2: 4.576 ops/ms
Iteration   3: 4.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.692 ±(99.9%) 5.510 ops/ms [Average]
  (min, avg, max) = (4.465, 4.692, 5.035), stdev = 0.302
  CI (99.9%): [≈ 0, 10.202] (assumes normal distribution)


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
# Warmup Iteration   1: 19.913 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 7.632 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.609 ±(99.9%) 0.010 ms/op
Iteration   1: 5.615 ±(99.9%) 0.008 ms/op
Iteration   2: 5.587 ±(99.9%) 0.008 ms/op
Iteration   3: 5.500 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.568 ±(99.9%) 1.094 ms/op [Average]
  (min, avg, max) = (5.500, 5.568, 5.615), stdev = 0.060
  CI (99.9%): [4.474, 6.662] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 16.199 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 5.767 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.271 ±(99.9%) 0.009 ms/op
Iteration   1: 5.681 ±(99.9%) 0.008 ms/op
Iteration   2: 5.340 ±(99.9%) 0.012 ms/op
Iteration   3: 5.254 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.425 ±(99.9%) 4.114 ms/op [Average]
  (min, avg, max) = (5.254, 5.425, 5.681), stdev = 0.226
  CI (99.9%): [1.311, 9.539] (assumes normal distribution)


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
# Warmup Iteration   1: 19.427 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 6.794 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.737 ±(99.9%) 0.008 ms/op
Iteration   1: 5.840 ±(99.9%) 0.006 ms/op
Iteration   2: 5.807 ±(99.9%) 0.013 ms/op
Iteration   3: 5.356 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.668 ±(99.9%) 4.933 ms/op [Average]
  (min, avg, max) = (5.356, 5.668, 5.840), stdev = 0.270
  CI (99.9%): [0.734, 10.601] (assumes normal distribution)


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
# Warmup Iteration   1: 20.832 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 7.226 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.213 ±(99.9%) 0.016 ms/op
Iteration   1: 6.372 ±(99.9%) 0.013 ms/op
Iteration   2: 6.339 ±(99.9%) 0.021 ms/op
Iteration   3: 6.255 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.322 ±(99.9%) 1.100 ms/op [Average]
  (min, avg, max) = (6.255, 6.322, 6.372), stdev = 0.060
  CI (99.9%): [5.222, 7.421] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.181 ±(99.9%) 0.303 ms/op
# Warmup Iteration   2: 6.877 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.793 ±(99.9%) 0.026 ms/op
Iteration   1: 5.482 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.726 ms/op
                 createUser·p0.50:   5.235 ms/op
                 createUser·p0.90:   6.595 ms/op
                 createUser·p0.95:   7.356 ms/op
                 createUser·p0.99:   10.535 ms/op
                 createUser·p0.999:  27.137 ms/op
                 createUser·p0.9999: 37.497 ms/op
                 createUser·p1.00:   38.076 ms/op

Iteration   2: 5.249 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.458 ms/op
                 createUser·p0.50:   5.005 ms/op
                 createUser·p0.90:   6.275 ms/op
                 createUser·p0.95:   6.874 ms/op
                 createUser·p0.99:   9.552 ms/op
                 createUser·p0.999:  27.200 ms/op
                 createUser·p0.9999: 30.629 ms/op
                 createUser·p1.00:   31.064 ms/op

Iteration   3: 5.471 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.056 ms/op
                 createUser·p0.50:   5.210 ms/op
                 createUser·p0.90:   6.603 ms/op
                 createUser·p0.95:   7.438 ms/op
                 createUser·p0.99:   10.372 ms/op
                 createUser·p0.999:  30.180 ms/op
                 createUser·p0.9999: 35.564 ms/op
                 createUser·p1.00:   37.093 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 177836
  mean =      5.398 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 75632 
    [ 5.000,  7.500) = 94729 
    [ 7.500, 10.000) = 5500 
    [10.000, 12.500) = 1282 
    [12.500, 15.000) = 347 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 35 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.726 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      6.496 ms/op
     p(95.0000) =      7.225 ms/op
     p(99.0000) =     10.207 ms/op
     p(99.9000) =     27.367 ms/op
     p(99.9900) =     36.176 ms/op
     p(99.9990) =     38.076 ms/op
     p(99.9999) =     38.076 ms/op
    p(100.0000) =     38.076 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 15.984 ±(99.9%) 0.277 ms/op
# Warmup Iteration   2: 6.598 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.542 ±(99.9%) 0.023 ms/op
Iteration   1: 5.379 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.221 ms/op
                 existUser·p0.50:   5.022 ms/op
                 existUser·p0.90:   6.849 ms/op
                 existUser·p0.95:   7.971 ms/op
                 existUser·p0.99:   10.682 ms/op
                 existUser·p0.999:  20.120 ms/op
                 existUser·p0.9999: 28.215 ms/op
                 existUser·p1.00:   29.393 ms/op

Iteration   2: 5.194 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.413 ms/op
                 existUser·p0.50:   4.899 ms/op
                 existUser·p0.90:   6.341 ms/op
                 existUser·p0.95:   7.045 ms/op
                 existUser·p0.99:   10.109 ms/op
                 existUser·p0.999:  25.235 ms/op
                 existUser·p0.9999: 29.957 ms/op
                 existUser·p1.00:   31.359 ms/op

Iteration   3: 5.197 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.261 ms/op
                 existUser·p0.50:   4.833 ms/op
                 existUser·p0.90:   6.283 ms/op
                 existUser·p0.95:   7.725 ms/op
                 existUser·p0.99:   11.567 ms/op
                 existUser·p0.999:  27.967 ms/op
                 existUser·p0.9999: 31.834 ms/op
                 existUser·p1.00:   33.128 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 182608
  mean =      5.255 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 100356 
    [ 5.000,  7.500) = 72709 
    [ 7.500, 10.000) = 6979 
    [10.000, 12.500) = 1598 
    [12.500, 15.000) = 507 
    [15.000, 17.500) = 209 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 83 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.221 ms/op
     p(50.0000) =      4.915 ms/op
     p(90.0000) =      6.488 ms/op
     p(95.0000) =      7.586 ms/op
     p(99.0000) =     10.764 ms/op
     p(99.9000) =     23.147 ms/op
     p(99.9900) =     30.768 ms/op
     p(99.9990) =     33.047 ms/op
     p(99.9999) =     33.128 ms/op
    p(100.0000) =     33.128 ms/op


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
# Warmup Iteration   1: 17.496 ±(99.9%) 0.286 ms/op
# Warmup Iteration   2: 6.294 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.423 ±(99.9%) 0.020 ms/op
Iteration   1: 5.325 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.208 ms/op
                 getUser·p0.50:   4.932 ms/op
                 getUser·p0.90:   6.472 ms/op
                 getUser·p0.95:   8.069 ms/op
                 getUser·p0.99:   12.534 ms/op
                 getUser·p0.999:  24.375 ms/op
                 getUser·p0.9999: 28.475 ms/op
                 getUser·p1.00:   29.983 ms/op

Iteration   2: 5.638 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.905 ms/op
                 getUser·p0.50:   5.267 ms/op
                 getUser·p0.90:   7.004 ms/op
                 getUser·p0.95:   8.176 ms/op
                 getUser·p0.99:   11.911 ms/op
                 getUser·p0.999:  27.706 ms/op
                 getUser·p0.9999: 34.100 ms/op
                 getUser·p1.00:   35.521 ms/op

Iteration   3: 5.939 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.851 ms/op
                 getUser·p0.50:   5.431 ms/op
                 getUser·p0.90:   8.184 ms/op
                 getUser·p0.95:   9.535 ms/op
                 getUser·p0.99:   12.730 ms/op
                 getUser·p0.999:  17.334 ms/op
                 getUser·p0.9999: 32.087 ms/op
                 getUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 170623
  mean =      5.623 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 67666 
    [ 5.000,  7.500) = 87739 
    [ 7.500, 10.000) = 10636 
    [10.000, 12.500) = 2882 
    [12.500, 15.000) = 1079 
    [15.000, 17.500) = 332 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      5.194 ms/op
     p(90.0000) =      7.234 ms/op
     p(95.0000) =      8.634 ms/op
     p(99.0000) =     12.452 ms/op
     p(99.9000) =     25.027 ms/op
     p(99.9900) =     32.174 ms/op
     p(99.9990) =     35.382 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


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
# Warmup Iteration   1: 20.495 ±(99.9%) 0.374 ms/op
# Warmup Iteration   2: 8.298 ±(99.9%) 0.062 ms/op
# Warmup Iteration   3: 6.740 ±(99.9%) 0.030 ms/op
Iteration   1: 6.179 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   5.906 ms/op
                 listUser·p0.90:   7.201 ms/op
                 listUser·p0.95:   8.086 ms/op
                 listUser·p0.99:   11.108 ms/op
                 listUser·p0.999:  26.149 ms/op
                 listUser·p0.9999: 28.633 ms/op
                 listUser·p1.00:   29.819 ms/op

Iteration   2: 6.193 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.802 ms/op
                 listUser·p0.50:   5.849 ms/op
                 listUser·p0.90:   7.226 ms/op
                 listUser·p0.95:   8.290 ms/op
                 listUser·p0.99:   11.900 ms/op
                 listUser·p0.999:  29.141 ms/op
                 listUser·p0.9999: 34.865 ms/op
                 listUser·p1.00:   37.618 ms/op

Iteration   3: 6.453 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.560 ms/op
                 listUser·p0.50:   6.062 ms/op
                 listUser·p0.90:   7.692 ms/op
                 listUser·p0.95:   9.273 ms/op
                 listUser·p0.99:   13.369 ms/op
                 listUser·p0.999:  23.407 ms/op
                 listUser·p0.9999: 27.625 ms/op
                 listUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 153100
  mean =      6.273 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 6283 
    [ 5.000,  7.500) = 133274 
    [ 7.500, 10.000) = 9539 
    [10.000, 12.500) = 2598 
    [12.500, 15.000) = 770 
    [15.000, 17.500) = 239 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.265 ms/op
     p(50.0000) =      5.939 ms/op
     p(90.0000) =      7.340 ms/op
     p(95.0000) =      8.602 ms/op
     p(99.0000) =     12.239 ms/op
     p(99.9000) =     26.378 ms/op
     p(99.9900) =     34.124 ms/op
     p(99.9990) =     36.330 ms/op
     p(99.9999) =     37.618 ms/op
    p(100.0000) =     37.618 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.499 ± 0.534  ops/ms
ClientPb.existUser                       thrpt       3   6.010 ± 1.580  ops/ms
ClientPb.getUser                         thrpt       3   5.764 ± 2.628  ops/ms
ClientPb.listUser                        thrpt       3   4.692 ± 5.510  ops/ms
ClientPb.createUser                       avgt       3   5.568 ± 1.094   ms/op
ClientPb.existUser                        avgt       3   5.425 ± 4.114   ms/op
ClientPb.getUser                          avgt       3   5.668 ± 4.933   ms/op
ClientPb.listUser                         avgt       3   6.322 ± 1.100   ms/op
ClientPb.createUser                     sample  177836   5.398 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.726           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.145           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.496           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.225           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.207           ms/op
ClientPb.createUser:createUser·p0.999   sample          27.367           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.176           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.076           ms/op
ClientPb.existUser                      sample  182608   5.255 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.221           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.915           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.488           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.586           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.764           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.147           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.768           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.128           ms/op
ClientPb.getUser                        sample  170623   5.623 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.851           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.194           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.234           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.634           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.452           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.027           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.174           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.521           ms/op
ClientPb.listUser                       sample  153100   6.273 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.265           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.939           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.340           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.602           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.239           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.378           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.124           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.618           ms/op
