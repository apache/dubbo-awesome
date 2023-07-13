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
# Warmup Iteration   1: 0.990 ops/ms
# Warmup Iteration   2: 2.168 ops/ms
# Warmup Iteration   3: 5.002 ops/ms
Iteration   1: 5.442 ops/ms
Iteration   2: 5.674 ops/ms
Iteration   3: 5.712 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.610 ±(99.9%) 2.662 ops/ms [Average]
  (min, avg, max) = (5.442, 5.610, 5.712), stdev = 0.146
  CI (99.9%): [2.947, 8.272] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.793 ops/ms
# Warmup Iteration   2: 4.694 ops/ms
# Warmup Iteration   3: 5.942 ops/ms
Iteration   1: 5.747 ops/ms
Iteration   2: 5.993 ops/ms
Iteration   3: 6.109 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.949 ±(99.9%) 3.371 ops/ms [Average]
  (min, avg, max) = (5.747, 5.949, 6.109), stdev = 0.185
  CI (99.9%): [2.579, 9.320] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.452 ops/ms
# Warmup Iteration   2: 3.974 ops/ms
# Warmup Iteration   3: 5.531 ops/ms
Iteration   1: 5.520 ops/ms
Iteration   2: 5.601 ops/ms
Iteration   3: 5.674 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.598 ±(99.9%) 1.407 ops/ms [Average]
  (min, avg, max) = (5.520, 5.598, 5.674), stdev = 0.077
  CI (99.9%): [4.191, 7.005] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.526 ops/ms
# Warmup Iteration   2: 3.802 ops/ms
# Warmup Iteration   3: 4.682 ops/ms
Iteration   1: 4.689 ops/ms
Iteration   2: 4.737 ops/ms
Iteration   3: 4.795 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.740 ±(99.9%) 0.969 ops/ms [Average]
  (min, avg, max) = (4.689, 4.740, 4.795), stdev = 0.053
  CI (99.9%): [3.771, 5.710] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 20.677 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 7.251 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 6.032 ±(99.9%) 0.013 ms/op
Iteration   1: 5.941 ±(99.9%) 0.014 ms/op
Iteration   2: 5.660 ±(99.9%) 0.017 ms/op
Iteration   3: 5.716 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.773 ±(99.9%) 2.713 ms/op [Average]
  (min, avg, max) = (5.660, 5.773, 5.941), stdev = 0.149
  CI (99.9%): [3.060, 8.486] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 18.957 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 6.612 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.629 ±(99.9%) 0.011 ms/op
Iteration   1: 5.587 ±(99.9%) 0.009 ms/op
Iteration   2: 5.525 ±(99.9%) 0.015 ms/op
Iteration   3: 5.401 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.504 ±(99.9%) 1.728 ms/op [Average]
  (min, avg, max) = (5.401, 5.504, 5.587), stdev = 0.095
  CI (99.9%): [3.776, 7.233] (assumes normal distribution)


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
# Warmup Iteration   1: 21.014 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 7.225 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.711 ±(99.9%) 0.019 ms/op
Iteration   1: 5.842 ±(99.9%) 0.009 ms/op
Iteration   2: 5.610 ±(99.9%) 0.018 ms/op
Iteration   3: 5.832 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.761 ±(99.9%) 2.391 ms/op [Average]
  (min, avg, max) = (5.610, 5.761, 5.842), stdev = 0.131
  CI (99.9%): [3.371, 8.152] (assumes normal distribution)


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
# Warmup Iteration   1: 25.636 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 8.836 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 7.145 ±(99.9%) 0.020 ms/op
Iteration   1: 6.864 ±(99.9%) 0.013 ms/op
Iteration   2: 6.545 ±(99.9%) 0.016 ms/op
Iteration   3: 6.786 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.732 ±(99.9%) 3.028 ms/op [Average]
  (min, avg, max) = (6.545, 6.732, 6.864), stdev = 0.166
  CI (99.9%): [3.704, 9.759] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 19.283 ±(99.9%) 0.350 ms/op
# Warmup Iteration   2: 7.683 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 6.518 ±(99.9%) 0.034 ms/op
Iteration   1: 5.988 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   2.699 ms/op
                 createUser·p0.50:   5.464 ms/op
                 createUser·p0.90:   7.823 ms/op
                 createUser·p0.95:   9.208 ms/op
                 createUser·p0.99:   13.623 ms/op
                 createUser·p0.999:  26.051 ms/op
                 createUser·p0.9999: 32.953 ms/op
                 createUser·p1.00:   34.210 ms/op

Iteration   2: 5.854 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.364 ms/op
                 createUser·p0.50:   5.505 ms/op
                 createUser·p0.90:   7.201 ms/op
                 createUser·p0.95:   8.389 ms/op
                 createUser·p0.99:   11.738 ms/op
                 createUser·p0.999:  28.246 ms/op
                 createUser·p0.9999: 34.097 ms/op
                 createUser·p1.00:   34.734 ms/op

Iteration   3: 5.721 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   0.481 ms/op
                 createUser·p0.50:   5.382 ms/op
                 createUser·p0.90:   7.004 ms/op
                 createUser·p0.95:   7.922 ms/op
                 createUser·p0.99:   11.059 ms/op
                 createUser·p0.999:  30.814 ms/op
                 createUser·p0.9999: 36.766 ms/op
                 createUser·p1.00:   38.076 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 163988
  mean =      5.852 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 40330 
    [ 5.000,  7.500) = 109022 
    [ 7.500, 10.000) = 10700 
    [10.000, 12.500) = 2410 
    [12.500, 15.000) = 859 
    [15.000, 17.500) = 306 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 53 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.481 ms/op
     p(50.0000) =      5.448 ms/op
     p(90.0000) =      7.315 ms/op
     p(95.0000) =      8.536 ms/op
     p(99.0000) =     12.206 ms/op
     p(99.9000) =     28.246 ms/op
     p(99.9900) =     36.412 ms/op
     p(99.9990) =     37.615 ms/op
     p(99.9999) =     38.076 ms/op
    p(100.0000) =     38.076 ms/op


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
# Warmup Iteration   1: 19.939 ±(99.9%) 0.300 ms/op
# Warmup Iteration   2: 6.731 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.883 ±(99.9%) 0.025 ms/op
Iteration   1: 5.817 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   1.839 ms/op
                 existUser·p0.50:   5.407 ms/op
                 existUser·p0.90:   7.520 ms/op
                 existUser·p0.95:   8.716 ms/op
                 existUser·p0.99:   11.174 ms/op
                 existUser·p0.999:  25.921 ms/op
                 existUser·p0.9999: 33.145 ms/op
                 existUser·p1.00:   34.013 ms/op

Iteration   2: 5.625 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.163 ms/op
                 existUser·p0.50:   5.259 ms/op
                 existUser·p0.90:   7.021 ms/op
                 existUser·p0.95:   8.217 ms/op
                 existUser·p0.99:   11.387 ms/op
                 existUser·p0.999:  18.153 ms/op
                 existUser·p0.9999: 30.888 ms/op
                 existUser·p1.00:   32.276 ms/op

Iteration   3: 5.650 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.429 ms/op
                 existUser·p0.50:   5.300 ms/op
                 existUser·p0.90:   6.947 ms/op
                 existUser·p0.95:   7.968 ms/op
                 existUser·p0.99:   10.945 ms/op
                 existUser·p0.999:  32.421 ms/op
                 existUser·p0.9999: 36.854 ms/op
                 existUser·p1.00:   37.814 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 168349
  mean =      5.696 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 51567 
    [ 5.000,  7.500) = 103404 
    [ 7.500, 10.000) = 10187 
    [10.000, 12.500) = 2171 
    [12.500, 15.000) = 624 
    [15.000, 17.500) = 157 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 52 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.839 ms/op
     p(50.0000) =      5.325 ms/op
     p(90.0000) =      7.143 ms/op
     p(95.0000) =      8.364 ms/op
     p(99.0000) =     11.190 ms/op
     p(99.9000) =     20.437 ms/op
     p(99.9900) =     34.996 ms/op
     p(99.9990) =     37.769 ms/op
     p(99.9999) =     37.814 ms/op
    p(100.0000) =     37.814 ms/op


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
# Warmup Iteration   1: 20.635 ±(99.9%) 0.416 ms/op
# Warmup Iteration   2: 7.953 ±(99.9%) 0.063 ms/op
# Warmup Iteration   3: 6.043 ±(99.9%) 0.026 ms/op
Iteration   1: 5.717 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.769 ms/op
                 getUser·p0.50:   5.317 ms/op
                 getUser·p0.90:   7.004 ms/op
                 getUser·p0.95:   8.618 ms/op
                 getUser·p0.99:   12.234 ms/op
                 getUser·p0.999:  17.465 ms/op
                 getUser·p0.9999: 25.992 ms/op
                 getUser·p1.00:   26.837 ms/op

Iteration   2: 5.665 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   3.256 ms/op
                 getUser·p0.50:   5.325 ms/op
                 getUser·p0.90:   6.832 ms/op
                 getUser·p0.95:   7.930 ms/op
                 getUser·p0.99:   11.158 ms/op
                 getUser·p0.999:  27.921 ms/op
                 getUser·p0.9999: 33.402 ms/op
                 getUser·p1.00:   34.210 ms/op

Iteration   3: 5.750 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.695 ms/op
                 getUser·p0.50:   5.358 ms/op
                 getUser·p0.90:   7.201 ms/op
                 getUser·p0.95:   8.258 ms/op
                 getUser·p0.99:   12.288 ms/op
                 getUser·p0.999:  27.918 ms/op
                 getUser·p0.9999: 34.530 ms/op
                 getUser·p1.00:   35.389 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 167987
  mean =      5.710 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 44801 
    [ 5.000,  7.500) = 110940 
    [ 7.500, 10.000) = 8371 
    [10.000, 12.500) = 2537 
    [12.500, 15.000) = 789 
    [15.000, 17.500) = 310 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.695 ms/op
     p(50.0000) =      5.333 ms/op
     p(90.0000) =      7.012 ms/op
     p(95.0000) =      8.274 ms/op
     p(99.0000) =     11.829 ms/op
     p(99.9000) =     22.184 ms/op
     p(99.9900) =     33.096 ms/op
     p(99.9990) =     35.122 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


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
# Warmup Iteration   1: 20.873 ±(99.9%) 0.370 ms/op
# Warmup Iteration   2: 7.957 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 7.219 ±(99.9%) 0.035 ms/op
Iteration   1: 6.849 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.486 ms/op
                 listUser·p0.50:   6.398 ms/op
                 listUser·p0.90:   8.471 ms/op
                 listUser·p0.95:   10.011 ms/op
                 listUser·p0.99:   13.287 ms/op
                 listUser·p0.999:  25.690 ms/op
                 listUser·p0.9999: 32.244 ms/op
                 listUser·p1.00:   33.030 ms/op

Iteration   2: 6.717 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.474 ms/op
                 listUser·p0.50:   6.160 ms/op
                 listUser·p0.90:   8.471 ms/op
                 listUser·p0.95:   10.142 ms/op
                 listUser·p0.99:   14.732 ms/op
                 listUser·p0.999:  24.423 ms/op
                 listUser·p0.9999: 29.592 ms/op
                 listUser·p1.00:   30.736 ms/op

Iteration   3: 6.856 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   3.105 ms/op
                 listUser·p0.50:   6.259 ms/op
                 listUser·p0.90:   8.978 ms/op
                 listUser·p0.95:   10.453 ms/op
                 listUser·p0.99:   13.419 ms/op
                 listUser·p0.999:  25.766 ms/op
                 listUser·p0.9999: 31.479 ms/op
                 listUser·p1.00:   32.080 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 141130
  mean =      6.807 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 2918 
    [ 5.000,  7.500) = 111044 
    [ 7.500, 10.000) = 19301 
    [10.000, 12.500) = 5478 
    [12.500, 15.000) = 1509 
    [15.000, 17.500) = 496 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.474 ms/op
     p(50.0000) =      6.275 ms/op
     p(90.0000) =      8.651 ms/op
     p(95.0000) =     10.256 ms/op
     p(99.0000) =     13.713 ms/op
     p(99.9000) =     25.362 ms/op
     p(99.9900) =     31.523 ms/op
     p(99.9990) =     32.841 ms/op
     p(99.9999) =     33.030 ms/op
    p(100.0000) =     33.030 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.610 ± 2.662  ops/ms
ClientPb.existUser                       thrpt       3   5.949 ± 3.371  ops/ms
ClientPb.getUser                         thrpt       3   5.598 ± 1.407  ops/ms
ClientPb.listUser                        thrpt       3   4.740 ± 0.969  ops/ms
ClientPb.createUser                       avgt       3   5.773 ± 2.713   ms/op
ClientPb.existUser                        avgt       3   5.504 ± 1.728   ms/op
ClientPb.getUser                          avgt       3   5.761 ± 2.391   ms/op
ClientPb.listUser                         avgt       3   6.732 ± 3.028   ms/op
ClientPb.createUser                     sample  163988   5.852 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.481           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.448           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.315           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.536           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.206           ms/op
ClientPb.createUser:createUser·p0.999   sample          28.246           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.412           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.076           ms/op
ClientPb.existUser                      sample  168349   5.696 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.839           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.325           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.143           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.364           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.190           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.437           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.996           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.814           ms/op
ClientPb.getUser                        sample  167987   5.710 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.695           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.333           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.012           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.274           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.829           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.184           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.096           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.389           ms/op
ClientPb.listUser                       sample  141130   6.807 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.474           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.275           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.651           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.256           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.713           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.362           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.523           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.030           ms/op
