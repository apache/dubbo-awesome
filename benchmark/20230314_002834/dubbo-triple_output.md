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
# Warmup Iteration   1: 1.184 ops/ms
# Warmup Iteration   2: 3.073 ops/ms
# Warmup Iteration   3: 6.008 ops/ms
Iteration   1: 5.911 ops/ms
Iteration   2: 6.229 ops/ms
Iteration   3: 6.146 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.096 ±(99.9%) 3.007 ops/ms [Average]
  (min, avg, max) = (5.911, 6.096, 6.229), stdev = 0.165
  CI (99.9%): [3.089, 9.102] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.885 ops/ms
# Warmup Iteration   2: 5.236 ops/ms
# Warmup Iteration   3: 6.119 ops/ms
Iteration   1: 6.146 ops/ms
Iteration   2: 6.445 ops/ms
Iteration   3: 6.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.345 ±(99.9%) 3.147 ops/ms [Average]
  (min, avg, max) = (6.146, 6.345, 6.445), stdev = 0.173
  CI (99.9%): [3.198, 9.492] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.602 ops/ms
# Warmup Iteration   2: 4.759 ops/ms
# Warmup Iteration   3: 6.054 ops/ms
Iteration   1: 5.646 ops/ms
Iteration   2: 5.644 ops/ms
Iteration   3: 5.527 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.606 ±(99.9%) 1.239 ops/ms [Average]
  (min, avg, max) = (5.527, 5.606, 5.646), stdev = 0.068
  CI (99.9%): [4.366, 6.845] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.431 ops/ms
# Warmup Iteration   2: 3.943 ops/ms
# Warmup Iteration   3: 4.719 ops/ms
Iteration   1: 4.781 ops/ms
Iteration   2: 5.049 ops/ms
Iteration   3: 4.969 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.933 ±(99.9%) 2.507 ops/ms [Average]
  (min, avg, max) = (4.781, 4.933, 5.049), stdev = 0.137
  CI (99.9%): [2.426, 7.440] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 20.005 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 6.690 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.797 ±(99.9%) 0.016 ms/op
Iteration   1: 5.533 ±(99.9%) 0.015 ms/op
Iteration   2: 5.664 ±(99.9%) 0.013 ms/op
Iteration   3: 5.617 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.605 ±(99.9%) 1.214 ms/op [Average]
  (min, avg, max) = (5.533, 5.605, 5.664), stdev = 0.067
  CI (99.9%): [4.391, 6.818] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 16.545 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 6.368 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.507 ±(99.9%) 0.013 ms/op
Iteration   1: 5.365 ±(99.9%) 0.009 ms/op
Iteration   2: 5.294 ±(99.9%) 0.016 ms/op
Iteration   3: 5.569 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.409 ±(99.9%) 2.598 ms/op [Average]
  (min, avg, max) = (5.294, 5.409, 5.569), stdev = 0.142
  CI (99.9%): [2.811, 8.008] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 19.149 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 6.577 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.744 ±(99.9%) 0.009 ms/op
Iteration   1: 5.483 ±(99.9%) 0.011 ms/op
Iteration   2: 5.520 ±(99.9%) 0.015 ms/op
Iteration   3: 5.484 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.496 ±(99.9%) 0.377 ms/op [Average]
  (min, avg, max) = (5.483, 5.496, 5.520), stdev = 0.021
  CI (99.9%): [5.118, 5.873] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 21.329 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 7.804 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.795 ±(99.9%) 0.013 ms/op
Iteration   1: 6.864 ±(99.9%) 0.008 ms/op
Iteration   2: 6.638 ±(99.9%) 0.016 ms/op
Iteration   3: 6.669 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.723 ±(99.9%) 2.236 ms/op [Average]
  (min, avg, max) = (6.638, 6.723, 6.864), stdev = 0.123
  CI (99.9%): [4.488, 8.959] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 18.927 ±(99.9%) 0.328 ms/op
# Warmup Iteration   2: 7.377 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 5.952 ±(99.9%) 0.025 ms/op
Iteration   1: 5.517 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.552 ms/op
                 createUser·p0.50:   5.259 ms/op
                 createUser·p0.90:   6.701 ms/op
                 createUser·p0.95:   7.578 ms/op
                 createUser·p0.99:   10.289 ms/op
                 createUser·p0.999:  24.347 ms/op
                 createUser·p0.9999: 27.892 ms/op
                 createUser·p1.00:   31.490 ms/op

Iteration   2: 5.845 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.605 ms/op
                 createUser·p0.50:   5.521 ms/op
                 createUser·p0.90:   7.348 ms/op
                 createUser·p0.95:   8.438 ms/op
                 createUser·p0.99:   11.026 ms/op
                 createUser·p0.999:  26.814 ms/op
                 createUser·p0.9999: 30.310 ms/op
                 createUser·p1.00:   31.293 ms/op

Iteration   3: 5.588 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.269 ms/op
                 createUser·p0.50:   5.284 ms/op
                 createUser·p0.90:   6.816 ms/op
                 createUser·p0.95:   7.700 ms/op
                 createUser·p0.99:   10.994 ms/op
                 createUser·p0.999:  28.756 ms/op
                 createUser·p0.9999: 44.106 ms/op
                 createUser·p1.00:   44.237 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 169904
  mean =      5.647 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 51033 
    [ 5.000, 10.000) = 116458 
    [10.000, 15.000) = 1963 
    [15.000, 20.000) = 207 
    [20.000, 25.000) = 57 
    [25.000, 30.000) = 128 
    [30.000, 35.000) = 23 
    [35.000, 40.000) = 17 
    [40.000, 45.000) = 18 

  Percentiles, ms/op:
      p(0.0000) =      2.269 ms/op
     p(50.0000) =      5.333 ms/op
     p(90.0000) =      6.971 ms/op
     p(95.0000) =      7.913 ms/op
     p(99.0000) =     10.764 ms/op
     p(99.9000) =     26.542 ms/op
     p(99.9900) =     43.058 ms/op
     p(99.9990) =     44.191 ms/op
     p(99.9999) =     44.237 ms/op
    p(100.0000) =     44.237 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.612 ±(99.9%) 0.261 ms/op
# Warmup Iteration   2: 6.078 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.571 ±(99.9%) 0.021 ms/op
Iteration   1: 5.478 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.341 ms/op
                 existUser·p0.50:   5.169 ms/op
                 existUser·p0.90:   6.775 ms/op
                 existUser·p0.95:   7.897 ms/op
                 existUser·p0.99:   10.650 ms/op
                 existUser·p0.999:  25.062 ms/op
                 existUser·p0.9999: 30.243 ms/op
                 existUser·p1.00:   32.375 ms/op

Iteration   2: 5.383 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.030 ms/op
                 existUser·p0.50:   5.104 ms/op
                 existUser·p0.90:   6.586 ms/op
                 existUser·p0.95:   7.492 ms/op
                 existUser·p0.99:   10.600 ms/op
                 existUser·p0.999:  28.082 ms/op
                 existUser·p0.9999: 31.660 ms/op
                 existUser·p1.00:   32.604 ms/op

Iteration   3: 5.222 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.413 ms/op
                 existUser·p0.50:   5.014 ms/op
                 existUser·p0.90:   6.160 ms/op
                 existUser·p0.95:   7.037 ms/op
                 existUser·p0.99:   9.821 ms/op
                 existUser·p0.999:  30.202 ms/op
                 existUser·p0.9999: 34.390 ms/op
                 existUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 179060
  mean =      5.359 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 79633 
    [ 5.000,  7.500) = 90563 
    [ 7.500, 10.000) = 6616 
    [10.000, 12.500) = 1592 
    [12.500, 15.000) = 333 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 77 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.341 ms/op
     p(50.0000) =      5.087 ms/op
     p(90.0000) =      6.521 ms/op
     p(95.0000) =      7.479 ms/op
     p(99.0000) =     10.420 ms/op
     p(99.9000) =     26.139 ms/op
     p(99.9900) =     32.515 ms/op
     p(99.9990) =     34.858 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 17.606 ±(99.9%) 0.315 ms/op
# Warmup Iteration   2: 7.289 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 5.920 ±(99.9%) 0.023 ms/op
Iteration   1: 5.812 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.473 ms/op
                 getUser·p0.50:   5.456 ms/op
                 getUser·p0.90:   7.217 ms/op
                 getUser·p0.95:   8.602 ms/op
                 getUser·p0.99:   12.203 ms/op
                 getUser·p0.999:  23.460 ms/op
                 getUser·p0.9999: 26.247 ms/op
                 getUser·p1.00:   26.935 ms/op

Iteration   2: 5.556 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.331 ms/op
                 getUser·p0.50:   5.308 ms/op
                 getUser·p0.90:   6.611 ms/op
                 getUser·p0.95:   7.447 ms/op
                 getUser·p0.99:   10.109 ms/op
                 getUser·p0.999:  30.605 ms/op
                 getUser·p0.9999: 34.095 ms/op
                 getUser·p1.00:   35.324 ms/op

Iteration   3: 5.887 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   3.138 ms/op
                 getUser·p0.50:   5.595 ms/op
                 getUser·p0.90:   7.127 ms/op
                 getUser·p0.95:   8.298 ms/op
                 getUser·p0.99:   11.616 ms/op
                 getUser·p0.999:  28.213 ms/op
                 getUser·p0.9999: 38.928 ms/op
                 getUser·p1.00:   39.125 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 166889
  mean =      5.748 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 42365 
    [ 5.000,  7.500) = 112773 
    [ 7.500, 10.000) = 8665 
    [10.000, 12.500) = 2051 
    [12.500, 15.000) = 638 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.473 ms/op
     p(50.0000) =      5.439 ms/op
     p(90.0000) =      6.971 ms/op
     p(95.0000) =      8.102 ms/op
     p(99.0000) =     11.223 ms/op
     p(99.9000) =     24.445 ms/op
     p(99.9900) =     37.552 ms/op
     p(99.9990) =     39.125 ms/op
     p(99.9999) =     39.125 ms/op
    p(100.0000) =     39.125 ms/op


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
# Warmup Iteration   1: 19.833 ±(99.9%) 0.317 ms/op
# Warmup Iteration   2: 7.585 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 6.726 ±(99.9%) 0.029 ms/op
Iteration   1: 6.309 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.499 ms/op
                 listUser·p0.50:   5.923 ms/op
                 listUser·p0.90:   7.766 ms/op
                 listUser·p0.95:   9.273 ms/op
                 listUser·p0.99:   11.829 ms/op
                 listUser·p0.999:  27.366 ms/op
                 listUser·p0.9999: 35.482 ms/op
                 listUser·p1.00:   37.028 ms/op

Iteration   2: 6.003 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.404 ms/op
                 listUser·p0.50:   5.718 ms/op
                 listUser·p0.90:   7.022 ms/op
                 listUser·p0.95:   7.938 ms/op
                 listUser·p0.99:   10.830 ms/op
                 listUser·p0.999:  29.689 ms/op
                 listUser·p0.9999: 33.206 ms/op
                 listUser·p1.00:   35.127 ms/op

Iteration   3: 6.249 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   0.981 ms/op
                 listUser·p0.50:   5.988 ms/op
                 listUser·p0.90:   7.479 ms/op
                 listUser·p0.95:   8.421 ms/op
                 listUser·p0.99:   11.649 ms/op
                 listUser·p0.999:  22.561 ms/op
                 listUser·p0.9999: 25.481 ms/op
                 listUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 155213
  mean =      6.184 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 12296 
    [ 5.000,  7.500) = 128073 
    [ 7.500, 10.000) = 11350 
    [10.000, 12.500) = 2467 
    [12.500, 15.000) = 471 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 84 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 50 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.981 ms/op
     p(50.0000) =      5.865 ms/op
     p(90.0000) =      7.447 ms/op
     p(95.0000) =      8.536 ms/op
     p(99.0000) =     11.485 ms/op
     p(99.9000) =     27.001 ms/op
     p(99.9900) =     33.663 ms/op
     p(99.9990) =     36.738 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.096 ± 3.007  ops/ms
ClientPb.existUser                       thrpt       3   6.345 ± 3.147  ops/ms
ClientPb.getUser                         thrpt       3   5.606 ± 1.239  ops/ms
ClientPb.listUser                        thrpt       3   4.933 ± 2.507  ops/ms
ClientPb.createUser                       avgt       3   5.605 ± 1.214   ms/op
ClientPb.existUser                        avgt       3   5.409 ± 2.598   ms/op
ClientPb.getUser                          avgt       3   5.496 ± 0.377   ms/op
ClientPb.listUser                         avgt       3   6.723 ± 2.236   ms/op
ClientPb.createUser                     sample  169904   5.647 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.269           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.333           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.971           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.913           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.764           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.542           ms/op
ClientPb.createUser:createUser·p0.9999  sample          43.058           ms/op
ClientPb.createUser:createUser·p1.00    sample          44.237           ms/op
ClientPb.existUser                      sample  179060   5.359 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.341           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.087           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.521           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.479           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.420           ms/op
ClientPb.existUser:existUser·p0.999     sample          26.139           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.515           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.324           ms/op
ClientPb.getUser                        sample  166889   5.748 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.473           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.439           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.971           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.102           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.223           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.445           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.552           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.125           ms/op
ClientPb.listUser                       sample  155213   6.184 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.981           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.865           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.447           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.536           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.485           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.001           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.663           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.028           ms/op
