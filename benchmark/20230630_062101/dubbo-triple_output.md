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
# Warmup Iteration   1: 1.081 ops/ms
# Warmup Iteration   2: 2.228 ops/ms
# Warmup Iteration   3: 4.812 ops/ms
Iteration   1: 5.330 ops/ms
Iteration   2: 5.596 ops/ms
Iteration   3: 5.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.522 ±(99.9%) 3.058 ops/ms [Average]
  (min, avg, max) = (5.330, 5.522, 5.639), stdev = 0.168
  CI (99.9%): [2.463, 8.580] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.568 ops/ms
# Warmup Iteration   2: 4.719 ops/ms
# Warmup Iteration   3: 5.618 ops/ms
Iteration   1: 5.903 ops/ms
Iteration   2: 5.874 ops/ms
Iteration   3: 5.758 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.845 ±(99.9%) 1.407 ops/ms [Average]
  (min, avg, max) = (5.758, 5.845, 5.903), stdev = 0.077
  CI (99.9%): [4.438, 7.252] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.605 ops/ms
# Warmup Iteration   2: 4.563 ops/ms
# Warmup Iteration   3: 5.724 ops/ms
Iteration   1: 5.524 ops/ms
Iteration   2: 5.480 ops/ms
Iteration   3: 5.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.620 ±(99.9%) 3.754 ops/ms [Average]
  (min, avg, max) = (5.480, 5.620, 5.856), stdev = 0.206
  CI (99.9%): [1.867, 9.374] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.382 ops/ms
# Warmup Iteration   2: 3.526 ops/ms
# Warmup Iteration   3: 4.697 ops/ms
Iteration   1: 4.604 ops/ms
Iteration   2: 4.907 ops/ms
Iteration   3: 4.912 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.808 ±(99.9%) 3.216 ops/ms [Average]
  (min, avg, max) = (4.604, 4.808, 4.912), stdev = 0.176
  CI (99.9%): [1.592, 8.023] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 18.544 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 7.154 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.086 ±(99.9%) 0.009 ms/op
Iteration   1: 5.723 ±(99.9%) 0.011 ms/op
Iteration   2: 5.830 ±(99.9%) 0.013 ms/op
Iteration   3: 5.858 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.804 ±(99.9%) 1.309 ms/op [Average]
  (min, avg, max) = (5.723, 5.804, 5.858), stdev = 0.072
  CI (99.9%): [4.495, 7.113] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 16.896 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 6.505 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.407 ±(99.9%) 0.012 ms/op
Iteration   1: 5.340 ±(99.9%) 0.019 ms/op
Iteration   2: 5.316 ±(99.9%) 0.017 ms/op
Iteration   3: 5.416 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.357 ±(99.9%) 0.955 ms/op [Average]
  (min, avg, max) = (5.316, 5.357, 5.416), stdev = 0.052
  CI (99.9%): [4.403, 6.312] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 19.770 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 6.804 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.912 ±(99.9%) 0.016 ms/op
Iteration   1: 5.655 ±(99.9%) 0.016 ms/op
Iteration   2: 5.627 ±(99.9%) 0.013 ms/op
Iteration   3: 5.608 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.630 ±(99.9%) 0.426 ms/op [Average]
  (min, avg, max) = (5.608, 5.630, 5.655), stdev = 0.023
  CI (99.9%): [5.204, 6.056] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 22.004 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 8.869 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.819 ±(99.9%) 0.016 ms/op
Iteration   1: 6.770 ±(99.9%) 0.011 ms/op
Iteration   2: 6.563 ±(99.9%) 0.020 ms/op
Iteration   3: 6.518 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.617 ±(99.9%) 2.454 ms/op [Average]
  (min, avg, max) = (6.518, 6.617, 6.770), stdev = 0.135
  CI (99.9%): [4.163, 9.072] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 17.792 ±(99.9%) 0.322 ms/op
# Warmup Iteration   2: 7.202 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.743 ±(99.9%) 0.024 ms/op
Iteration   1: 5.475 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.531 ms/op
                 createUser·p0.50:   5.161 ms/op
                 createUser·p0.90:   6.734 ms/op
                 createUser·p0.95:   7.610 ms/op
                 createUser·p0.99:   9.920 ms/op
                 createUser·p0.999:  27.787 ms/op
                 createUser·p0.9999: 35.541 ms/op
                 createUser·p1.00:   35.979 ms/op

Iteration   2: 5.242 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.839 ms/op
                 createUser·p0.50:   5.128 ms/op
                 createUser·p0.90:   5.808 ms/op
                 createUser·p0.95:   6.472 ms/op
                 createUser·p0.99:   9.175 ms/op
                 createUser·p0.999:  26.968 ms/op
                 createUser·p0.9999: 30.766 ms/op
                 createUser·p1.00:   34.013 ms/op

Iteration   3: 5.556 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.363 ms/op
                 createUser·p0.50:   5.267 ms/op
                 createUser·p0.90:   6.832 ms/op
                 createUser·p0.95:   7.594 ms/op
                 createUser·p0.99:   9.880 ms/op
                 createUser·p0.999:  28.820 ms/op
                 createUser·p0.9999: 31.392 ms/op
                 createUser·p1.00:   33.194 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 176918
  mean =      5.421 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 59712 
    [ 5.000,  7.500) = 109218 
    [ 7.500, 10.000) = 6546 
    [10.000, 12.500) = 865 
    [12.500, 15.000) = 255 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 71 
    [30.000, 32.500) = 71 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      2.363 ms/op
     p(50.0000) =      5.177 ms/op
     p(90.0000) =      6.537 ms/op
     p(95.0000) =      7.348 ms/op
     p(99.0000) =      9.699 ms/op
     p(99.9000) =     27.498 ms/op
     p(99.9900) =     34.669 ms/op
     p(99.9990) =     35.979 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.971 ±(99.9%) 0.281 ms/op
# Warmup Iteration   2: 6.552 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.587 ±(99.9%) 0.018 ms/op
Iteration   1: 5.398 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.023 ms/op
                 existUser·p0.50:   5.120 ms/op
                 existUser·p0.90:   6.406 ms/op
                 existUser·p0.95:   7.881 ms/op
                 existUser·p0.99:   9.994 ms/op
                 existUser·p0.999:  25.068 ms/op
                 existUser·p0.9999: 32.150 ms/op
                 existUser·p1.00:   33.227 ms/op

Iteration   2: 5.315 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.699 ms/op
                 existUser·p0.50:   5.079 ms/op
                 existUser·p0.90:   6.226 ms/op
                 existUser·p0.95:   7.029 ms/op
                 existUser·p0.99:   9.552 ms/op
                 existUser·p0.999:  26.560 ms/op
                 existUser·p0.9999: 30.964 ms/op
                 existUser·p1.00:   32.047 ms/op

Iteration   3: 5.489 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.216 ms/op
                 existUser·p0.50:   5.267 ms/op
                 existUser·p0.90:   6.513 ms/op
                 existUser·p0.95:   7.277 ms/op
                 existUser·p0.99:   10.011 ms/op
                 existUser·p0.999:  16.666 ms/op
                 existUser·p0.9999: 29.557 ms/op
                 existUser·p1.00:   30.114 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 177654
  mean =      5.400 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 69381 
    [ 5.000,  7.500) = 100109 
    [ 7.500, 10.000) = 6579 
    [10.000, 12.500) = 948 
    [12.500, 15.000) = 339 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 78 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.023 ms/op
     p(50.0000) =      5.153 ms/op
     p(90.0000) =      6.382 ms/op
     p(95.0000) =      7.348 ms/op
     p(99.0000) =      9.863 ms/op
     p(99.9000) =     18.121 ms/op
     p(99.9900) =     31.012 ms/op
     p(99.9990) =     32.514 ms/op
     p(99.9999) =     33.227 ms/op
    p(100.0000) =     33.227 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 19.216 ±(99.9%) 0.285 ms/op
# Warmup Iteration   2: 6.522 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.691 ±(99.9%) 0.021 ms/op
Iteration   1: 5.672 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.507 ms/op
                 getUser·p0.50:   5.235 ms/op
                 getUser·p0.90:   6.865 ms/op
                 getUser·p0.95:   8.389 ms/op
                 getUser·p0.99:   13.828 ms/op
                 getUser·p0.999:  24.988 ms/op
                 getUser·p0.9999: 28.551 ms/op
                 getUser·p1.00:   29.360 ms/op

Iteration   2: 5.635 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.384 ms/op
                 getUser·p0.50:   5.317 ms/op
                 getUser·p0.90:   6.767 ms/op
                 getUser·p0.95:   7.823 ms/op
                 getUser·p0.99:   11.125 ms/op
                 getUser·p0.999:  18.153 ms/op
                 getUser·p0.9999: 35.235 ms/op
                 getUser·p1.00:   36.569 ms/op

Iteration   3: 5.626 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.847 ms/op
                 getUser·p0.50:   5.423 ms/op
                 getUser·p0.90:   6.619 ms/op
                 getUser·p0.95:   7.250 ms/op
                 getUser·p0.99:   9.681 ms/op
                 getUser·p0.999:  27.104 ms/op
                 getUser·p0.9999: 30.710 ms/op
                 getUser·p1.00:   31.228 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 169966
  mean =      5.644 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 46609 
    [ 5.000,  7.500) = 113844 
    [ 7.500, 10.000) = 6583 
    [10.000, 12.500) = 1730 
    [12.500, 15.000) = 468 
    [15.000, 17.500) = 385 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.384 ms/op
     p(50.0000) =      5.325 ms/op
     p(90.0000) =      6.734 ms/op
     p(95.0000) =      7.717 ms/op
     p(99.0000) =     11.387 ms/op
     p(99.9000) =     24.184 ms/op
     p(99.9900) =     34.472 ms/op
     p(99.9990) =     36.523 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.156 ±(99.9%) 0.329 ms/op
# Warmup Iteration   2: 8.613 ±(99.9%) 0.063 ms/op
# Warmup Iteration   3: 6.865 ±(99.9%) 0.027 ms/op
Iteration   1: 6.846 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.765 ms/op
                 listUser·p0.50:   6.423 ms/op
                 listUser·p0.90:   8.241 ms/op
                 listUser·p0.95:   10.158 ms/op
                 listUser·p0.99:   13.628 ms/op
                 listUser·p0.999:  27.257 ms/op
                 listUser·p0.9999: 34.537 ms/op
                 listUser·p1.00:   35.258 ms/op

Iteration   2: 6.423 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.429 ms/op
                 listUser·p0.50:   6.177 ms/op
                 listUser·p0.90:   7.299 ms/op
                 listUser·p0.95:   8.061 ms/op
                 listUser·p0.99:   11.583 ms/op
                 listUser·p0.999:  28.842 ms/op
                 listUser·p0.9999: 31.491 ms/op
                 listUser·p1.00:   36.897 ms/op

Iteration   3: 6.447 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.075 ms/op
                 listUser·p0.50:   6.160 ms/op
                 listUser·p0.90:   7.553 ms/op
                 listUser·p0.95:   8.438 ms/op
                 listUser·p0.99:   11.256 ms/op
                 listUser·p0.999:  23.744 ms/op
                 listUser·p0.9999: 32.028 ms/op
                 listUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 146218
  mean =      6.566 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 2923 
    [ 5.000,  7.500) = 125899 
    [ 7.500, 10.000) = 12965 
    [10.000, 12.500) = 3023 
    [12.500, 15.000) = 821 
    [15.000, 17.500) = 211 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 52 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.075 ms/op
     p(50.0000) =      6.234 ms/op
     p(90.0000) =      7.684 ms/op
     p(95.0000) =      8.782 ms/op
     p(99.0000) =     12.386 ms/op
     p(99.9000) =     27.689 ms/op
     p(99.9900) =     33.948 ms/op
     p(99.9990) =     36.140 ms/op
     p(99.9999) =     36.897 ms/op
    p(100.0000) =     36.897 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.522 ± 3.058  ops/ms
ClientPb.existUser                       thrpt       3   5.845 ± 1.407  ops/ms
ClientPb.getUser                         thrpt       3   5.620 ± 3.754  ops/ms
ClientPb.listUser                        thrpt       3   4.808 ± 3.216  ops/ms
ClientPb.createUser                       avgt       3   5.804 ± 1.309   ms/op
ClientPb.existUser                        avgt       3   5.357 ± 0.955   ms/op
ClientPb.getUser                          avgt       3   5.630 ± 0.426   ms/op
ClientPb.listUser                         avgt       3   6.617 ± 2.454   ms/op
ClientPb.createUser                     sample  176918   5.421 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.363           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.177           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.537           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.348           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.699           ms/op
ClientPb.createUser:createUser·p0.999   sample          27.498           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.669           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.979           ms/op
ClientPb.existUser                      sample  177654   5.400 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.023           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.153           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.382           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.348           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.863           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.121           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.012           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.227           ms/op
ClientPb.getUser                        sample  169966   5.644 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.384           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.325           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.734           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.717           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.387           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.184           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.472           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.569           ms/op
ClientPb.listUser                       sample  146218   6.566 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.075           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.234           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.684           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.782           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.386           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.689           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.948           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.897           ms/op
