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
# Warmup Iteration   1: 1.080 ops/ms
# Warmup Iteration   2: 2.144 ops/ms
# Warmup Iteration   3: 4.450 ops/ms
Iteration   1: 5.338 ops/ms
Iteration   2: 5.466 ops/ms
Iteration   3: 5.564 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.456 ±(99.9%) 2.068 ops/ms [Average]
  (min, avg, max) = (5.338, 5.456, 5.564), stdev = 0.113
  CI (99.9%): [3.388, 7.525] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.772 ops/ms
# Warmup Iteration   2: 4.654 ops/ms
# Warmup Iteration   3: 5.688 ops/ms
Iteration   1: 5.834 ops/ms
Iteration   2: 6.069 ops/ms
Iteration   3: 6.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.005 ±(99.9%) 2.741 ops/ms [Average]
  (min, avg, max) = (5.834, 6.005, 6.114), stdev = 0.150
  CI (99.9%): [3.264, 8.747] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.514 ops/ms
# Warmup Iteration   2: 4.106 ops/ms
# Warmup Iteration   3: 5.505 ops/ms
Iteration   1: 5.384 ops/ms
Iteration   2: 5.677 ops/ms
Iteration   3: 5.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.538 ±(99.9%) 2.691 ops/ms [Average]
  (min, avg, max) = (5.384, 5.538, 5.677), stdev = 0.147
  CI (99.9%): [2.847, 8.229] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.445 ops/ms
# Warmup Iteration   2: 3.335 ops/ms
# Warmup Iteration   3: 4.682 ops/ms
Iteration   1: 4.624 ops/ms
Iteration   2: 4.962 ops/ms
Iteration   3: 4.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.773 ±(99.9%) 3.142 ops/ms [Average]
  (min, avg, max) = (4.624, 4.773, 4.962), stdev = 0.172
  CI (99.9%): [1.631, 7.915] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 18.549 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 7.844 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.931 ±(99.9%) 0.009 ms/op
Iteration   1: 5.751 ±(99.9%) 0.017 ms/op
Iteration   2: 5.658 ±(99.9%) 0.015 ms/op
Iteration   3: 5.495 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.635 ±(99.9%) 2.359 ms/op [Average]
  (min, avg, max) = (5.495, 5.635, 5.751), stdev = 0.129
  CI (99.9%): [3.275, 7.994] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 17.113 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 6.416 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.501 ±(99.9%) 0.017 ms/op
Iteration   1: 5.649 ±(99.9%) 0.008 ms/op
Iteration   2: 5.415 ±(99.9%) 0.012 ms/op
Iteration   3: 5.546 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.537 ±(99.9%) 2.131 ms/op [Average]
  (min, avg, max) = (5.415, 5.537, 5.649), stdev = 0.117
  CI (99.9%): [3.406, 7.668] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 17.601 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 6.891 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.724 ±(99.9%) 0.015 ms/op
Iteration   1: 5.966 ±(99.9%) 0.012 ms/op
Iteration   2: 5.822 ±(99.9%) 0.013 ms/op
Iteration   3: 5.688 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.826 ±(99.9%) 2.539 ms/op [Average]
  (min, avg, max) = (5.688, 5.826, 5.966), stdev = 0.139
  CI (99.9%): [3.287, 8.365] (assumes normal distribution)


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
# Warmup Iteration   1: 20.497 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 7.672 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 6.386 ±(99.9%) 0.023 ms/op
Iteration   1: 6.613 ±(99.9%) 0.011 ms/op
Iteration   2: 6.630 ±(99.9%) 0.017 ms/op
Iteration   3: 6.640 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.628 ±(99.9%) 0.243 ms/op [Average]
  (min, avg, max) = (6.613, 6.628, 6.640), stdev = 0.013
  CI (99.9%): [6.385, 6.871] (assumes normal distribution)


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
# Warmup Iteration   1: 18.735 ±(99.9%) 0.361 ms/op
# Warmup Iteration   2: 7.195 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 6.097 ±(99.9%) 0.026 ms/op
Iteration   1: 5.645 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.874 ms/op
                 createUser·p0.50:   5.358 ms/op
                 createUser·p0.90:   6.939 ms/op
                 createUser·p0.95:   7.930 ms/op
                 createUser·p0.99:   10.371 ms/op
                 createUser·p0.999:  26.850 ms/op
                 createUser·p0.9999: 31.371 ms/op
                 createUser·p1.00:   32.408 ms/op

Iteration   2: 5.603 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.314 ms/op
                 createUser·p0.50:   5.325 ms/op
                 createUser·p0.90:   6.758 ms/op
                 createUser·p0.95:   7.553 ms/op
                 createUser·p0.99:   10.912 ms/op
                 createUser·p0.999:  17.561 ms/op
                 createUser·p0.9999: 34.144 ms/op
                 createUser·p1.00:   34.865 ms/op

Iteration   3: 5.887 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.376 ms/op
                 createUser·p0.50:   5.685 ms/op
                 createUser·p0.90:   7.012 ms/op
                 createUser·p0.95:   7.766 ms/op
                 createUser·p0.99:   11.534 ms/op
                 createUser·p0.999:  26.891 ms/op
                 createUser·p0.9999: 32.852 ms/op
                 createUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 168084
  mean =      5.709 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 48057 
    [ 5.000,  7.500) = 110104 
    [ 7.500, 10.000) = 7319 
    [10.000, 12.500) = 1639 
    [12.500, 15.000) = 524 
    [15.000, 17.500) = 192 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.874 ms/op
     p(50.0000) =      5.456 ms/op
     p(90.0000) =      6.906 ms/op
     p(95.0000) =      7.750 ms/op
     p(99.0000) =     10.977 ms/op
     p(99.9000) =     25.065 ms/op
     p(99.9900) =     32.774 ms/op
     p(99.9990) =     34.865 ms/op
     p(99.9999) =     34.865 ms/op
    p(100.0000) =     34.865 ms/op


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
# Warmup Iteration   1: 16.598 ±(99.9%) 0.264 ms/op
# Warmup Iteration   2: 6.537 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.589 ±(99.9%) 0.022 ms/op
Iteration   1: 5.644 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.425 ms/op
                 existUser·p0.50:   5.325 ms/op
                 existUser·p0.90:   7.094 ms/op
                 existUser·p0.95:   8.061 ms/op
                 existUser·p0.99:   10.043 ms/op
                 existUser·p0.999:  16.193 ms/op
                 existUser·p0.9999: 26.761 ms/op
                 existUser·p1.00:   33.489 ms/op

Iteration   2: 5.414 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.580 ms/op
                 existUser·p0.50:   5.153 ms/op
                 existUser·p0.90:   6.562 ms/op
                 existUser·p0.95:   7.201 ms/op
                 existUser·p0.99:   10.312 ms/op
                 existUser·p0.999:  25.420 ms/op
                 existUser·p0.9999: 29.855 ms/op
                 existUser·p1.00:   31.064 ms/op

Iteration   3: 5.352 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.265 ms/op
                 existUser·p0.50:   5.095 ms/op
                 existUser·p0.90:   6.562 ms/op
                 existUser·p0.95:   7.340 ms/op
                 existUser·p0.99:   9.273 ms/op
                 existUser·p0.999:  27.058 ms/op
                 existUser·p0.9999: 30.382 ms/op
                 existUser·p1.00:   32.080 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 175476
  mean =      5.467 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 68950 
    [ 5.000,  7.500) = 97537 
    [ 7.500, 10.000) = 7354 
    [10.000, 12.500) = 1076 
    [12.500, 15.000) = 289 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.265 ms/op
     p(50.0000) =      5.186 ms/op
     p(90.0000) =      6.742 ms/op
     p(95.0000) =      7.528 ms/op
     p(99.0000) =      9.830 ms/op
     p(99.9000) =     16.958 ms/op
     p(99.9900) =     29.884 ms/op
     p(99.9990) =     32.425 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


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
# Warmup Iteration   1: 17.815 ±(99.9%) 0.288 ms/op
# Warmup Iteration   2: 6.733 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.800 ±(99.9%) 0.022 ms/op
Iteration   1: 5.701 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.777 ms/op
                 getUser·p0.50:   5.358 ms/op
                 getUser·p0.90:   6.914 ms/op
                 getUser·p0.95:   8.323 ms/op
                 getUser·p0.99:   12.272 ms/op
                 getUser·p0.999:  22.409 ms/op
                 getUser·p0.9999: 25.855 ms/op
                 getUser·p1.00:   27.165 ms/op

Iteration   2: 5.704 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.602 ms/op
                 getUser·p0.50:   5.374 ms/op
                 getUser·p0.90:   7.029 ms/op
                 getUser·p0.95:   8.585 ms/op
                 getUser·p0.99:   11.452 ms/op
                 getUser·p0.999:  19.200 ms/op
                 getUser·p0.9999: 28.587 ms/op
                 getUser·p1.00:   29.196 ms/op

Iteration   3: 5.365 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.421 ms/op
                 getUser·p0.50:   5.145 ms/op
                 getUser·p0.90:   6.210 ms/op
                 getUser·p0.95:   7.078 ms/op
                 getUser·p0.99:   9.852 ms/op
                 getUser·p0.999:  26.127 ms/op
                 getUser·p0.9999: 30.511 ms/op
                 getUser·p1.00:   33.128 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 171858
  mean =      5.585 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 56257 
    [ 5.000,  7.500) = 104487 
    [ 7.500, 10.000) = 8317 
    [10.000, 12.500) = 1647 
    [12.500, 15.000) = 731 
    [15.000, 17.500) = 178 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.602 ms/op
     p(50.0000) =      5.284 ms/op
     p(90.0000) =      6.685 ms/op
     p(95.0000) =      8.102 ms/op
     p(99.0000) =     11.289 ms/op
     p(99.9000) =     20.386 ms/op
     p(99.9900) =     29.196 ms/op
     p(99.9990) =     32.775 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.084 ±(99.9%) 0.397 ms/op
# Warmup Iteration   2: 8.166 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 6.765 ±(99.9%) 0.029 ms/op
Iteration   1: 6.986 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.912 ms/op
                 listUser·p0.50:   6.668 ms/op
                 listUser·p0.90:   8.135 ms/op
                 listUser·p0.95:   9.781 ms/op
                 listUser·p0.99:   13.048 ms/op
                 listUser·p0.999:  29.466 ms/op
                 listUser·p0.9999: 32.140 ms/op
                 listUser·p1.00:   32.702 ms/op

Iteration   2: 6.802 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.224 ms/op
                 listUser·p0.50:   6.439 ms/op
                 listUser·p0.90:   8.208 ms/op
                 listUser·p0.95:   9.306 ms/op
                 listUser·p0.99:   12.615 ms/op
                 listUser·p0.999:  29.229 ms/op
                 listUser·p0.9999: 31.628 ms/op
                 listUser·p1.00:   32.375 ms/op

Iteration   3: 6.535 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.112 ms/op
                 listUser·p0.50:   6.234 ms/op
                 listUser·p0.90:   7.627 ms/op
                 listUser·p0.95:   8.700 ms/op
                 listUser·p0.99:   11.829 ms/op
                 listUser·p0.999:  23.495 ms/op
                 listUser·p0.9999: 32.808 ms/op
                 listUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 141753
  mean =      6.769 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 2339 
    [ 5.000,  7.500) = 117310 
    [ 7.500, 10.000) = 17194 
    [10.000, 12.500) = 3425 
    [12.500, 15.000) = 884 
    [15.000, 17.500) = 245 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 87 
    [30.000, 32.500) = 83 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      6.414 ms/op
     p(90.0000) =      8.004 ms/op
     p(95.0000) =      9.208 ms/op
     p(99.0000) =     12.599 ms/op
     p(99.9000) =     28.483 ms/op
     p(99.9900) =     32.211 ms/op
     p(99.9990) =     34.384 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.456 ± 2.068  ops/ms
ClientPb.existUser                       thrpt       3   6.005 ± 2.741  ops/ms
ClientPb.getUser                         thrpt       3   5.538 ± 2.691  ops/ms
ClientPb.listUser                        thrpt       3   4.773 ± 3.142  ops/ms
ClientPb.createUser                       avgt       3   5.635 ± 2.359   ms/op
ClientPb.existUser                        avgt       3   5.537 ± 2.131   ms/op
ClientPb.getUser                          avgt       3   5.826 ± 2.539   ms/op
ClientPb.listUser                         avgt       3   6.628 ± 0.243   ms/op
ClientPb.createUser                     sample  168084   5.709 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.874           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.456           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.906           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.750           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.977           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.065           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.774           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.865           ms/op
ClientPb.existUser                      sample  175476   5.467 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.265           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.186           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.742           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.528           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.830           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.958           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.884           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.489           ms/op
ClientPb.getUser                        sample  171858   5.585 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.602           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.284           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.685           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.102           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.289           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.386           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.196           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.128           ms/op
ClientPb.listUser                       sample  141753   6.769 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.112           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.414           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.004           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.208           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.599           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.483           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.211           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.603           ms/op
