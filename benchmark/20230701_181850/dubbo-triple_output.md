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
# Warmup Iteration   1: 1.003 ops/ms
# Warmup Iteration   2: 2.184 ops/ms
# Warmup Iteration   3: 4.878 ops/ms
Iteration   1: 5.088 ops/ms
Iteration   2: 5.595 ops/ms
Iteration   3: 5.663 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.449 ±(99.9%) 5.729 ops/ms [Average]
  (min, avg, max) = (5.088, 5.449, 5.663), stdev = 0.314
  CI (99.9%): [≈ 0, 11.177] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:17
# Fork: 1 of 1
# Warmup Iteration   1: 1.515 ops/ms
# Warmup Iteration   2: 4.009 ops/ms
# Warmup Iteration   3: 5.769 ops/ms
Iteration   1: 5.757 ops/ms
Iteration   2: 5.703 ops/ms
Iteration   3: 5.511 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.657 ±(99.9%) 2.358 ops/ms [Average]
  (min, avg, max) = (5.511, 5.657, 5.757), stdev = 0.129
  CI (99.9%): [3.299, 8.015] (assumes normal distribution)


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
# Warmup Iteration   1: 1.546 ops/ms
# Warmup Iteration   2: 4.380 ops/ms
# Warmup Iteration   3: 5.382 ops/ms
Iteration   1: 5.396 ops/ms
Iteration   2: 5.669 ops/ms
Iteration   3: 5.593 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.553 ±(99.9%) 2.564 ops/ms [Average]
  (min, avg, max) = (5.396, 5.553, 5.669), stdev = 0.141
  CI (99.9%): [2.989, 8.116] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.450 ops/ms
# Warmup Iteration   2: 3.608 ops/ms
# Warmup Iteration   3: 4.618 ops/ms
Iteration   1: 4.644 ops/ms
Iteration   2: 4.825 ops/ms
Iteration   3: 4.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.722 ±(99.9%) 1.696 ops/ms [Average]
  (min, avg, max) = (4.644, 4.722, 4.825), stdev = 0.093
  CI (99.9%): [3.027, 6.418] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 22.828 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 6.946 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.963 ±(99.9%) 0.014 ms/op
Iteration   1: 5.909 ±(99.9%) 0.016 ms/op
Iteration   2: 5.833 ±(99.9%) 0.008 ms/op
Iteration   3: 5.807 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.850 ±(99.9%) 0.962 ms/op [Average]
  (min, avg, max) = (5.807, 5.850, 5.909), stdev = 0.053
  CI (99.9%): [4.888, 6.811] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 17.636 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 6.394 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.664 ±(99.9%) 0.007 ms/op
Iteration   1: 5.512 ±(99.9%) 0.014 ms/op
Iteration   2: 5.544 ±(99.9%) 0.016 ms/op
Iteration   3: 5.379 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.478 ±(99.9%) 1.598 ms/op [Average]
  (min, avg, max) = (5.379, 5.478, 5.544), stdev = 0.088
  CI (99.9%): [3.880, 7.076] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:40
# Fork: 1 of 1
# Warmup Iteration   1: 17.739 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 7.579 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.937 ±(99.9%) 0.010 ms/op
Iteration   1: 5.728 ±(99.9%) 0.017 ms/op
Iteration   2: 6.020 ±(99.9%) 0.012 ms/op
Iteration   3: 6.029 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.926 ±(99.9%) 3.128 ms/op [Average]
  (min, avg, max) = (5.728, 5.926, 6.029), stdev = 0.171
  CI (99.9%): [2.797, 9.054] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 20.120 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 8.704 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 7.221 ±(99.9%) 0.014 ms/op
Iteration   1: 6.877 ±(99.9%) 0.014 ms/op
Iteration   2: 6.941 ±(99.9%) 0.015 ms/op
Iteration   3: 6.736 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.851 ±(99.9%) 1.906 ms/op [Average]
  (min, avg, max) = (6.736, 6.851, 6.941), stdev = 0.104
  CI (99.9%): [4.945, 8.758] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 20.454 ±(99.9%) 0.328 ms/op
# Warmup Iteration   2: 7.757 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 6.372 ±(99.9%) 0.031 ms/op
Iteration   1: 6.090 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.855 ms/op
                 createUser·p0.50:   5.734 ms/op
                 createUser·p0.90:   7.528 ms/op
                 createUser·p0.95:   8.716 ms/op
                 createUser·p0.99:   11.551 ms/op
                 createUser·p0.999:  25.625 ms/op
                 createUser·p0.9999: 30.294 ms/op
                 createUser·p1.00:   31.359 ms/op

Iteration   2: 6.063 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.188 ms/op
                 createUser·p0.50:   5.677 ms/op
                 createUser·p0.90:   7.553 ms/op
                 createUser·p0.95:   8.569 ms/op
                 createUser·p0.99:   11.567 ms/op
                 createUser·p0.999:  29.983 ms/op
                 createUser·p0.9999: 33.108 ms/op
                 createUser·p1.00:   34.079 ms/op

Iteration   3: 6.141 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   2.261 ms/op
                 createUser·p0.50:   5.734 ms/op
                 createUser·p0.90:   7.799 ms/op
                 createUser·p0.95:   8.978 ms/op
                 createUser·p0.99:   11.780 ms/op
                 createUser·p0.999:  30.638 ms/op
                 createUser·p0.9999: 34.996 ms/op
                 createUser·p1.00:   35.586 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 157269
  mean =      6.098 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 19999 
    [ 5.000,  7.500) = 120211 
    [ 7.500, 10.000) = 13179 
    [10.000, 12.500) = 2840 
    [12.500, 15.000) = 593 
    [15.000, 17.500) = 196 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 94 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.188 ms/op
     p(50.0000) =      5.718 ms/op
     p(90.0000) =      7.610 ms/op
     p(95.0000) =      8.782 ms/op
     p(99.0000) =     11.649 ms/op
     p(99.9000) =     26.664 ms/op
     p(99.9900) =     32.917 ms/op
     p(99.9990) =     35.511 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 19.920 ±(99.9%) 0.333 ms/op
# Warmup Iteration   2: 7.971 ±(99.9%) 0.066 ms/op
# Warmup Iteration   3: 5.947 ±(99.9%) 0.025 ms/op
Iteration   1: 5.880 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   1.763 ms/op
                 existUser·p0.50:   5.546 ms/op
                 existUser·p0.90:   7.315 ms/op
                 existUser·p0.95:   8.782 ms/op
                 existUser·p0.99:   10.945 ms/op
                 existUser·p0.999:  26.018 ms/op
                 existUser·p0.9999: 29.120 ms/op
                 existUser·p1.00:   30.114 ms/op

Iteration   2: 5.828 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.843 ms/op
                 existUser·p0.50:   5.497 ms/op
                 existUser·p0.90:   7.152 ms/op
                 existUser·p0.95:   8.266 ms/op
                 existUser·p0.99:   11.377 ms/op
                 existUser·p0.999:  16.735 ms/op
                 existUser·p0.9999: 30.229 ms/op
                 existUser·p1.00:   30.441 ms/op

Iteration   3: 5.958 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.726 ms/op
                 existUser·p0.50:   5.480 ms/op
                 existUser·p0.90:   7.586 ms/op
                 existUser·p0.95:   9.224 ms/op
                 existUser·p0.99:   12.845 ms/op
                 existUser·p0.999:  32.123 ms/op
                 existUser·p0.9999: 35.324 ms/op
                 existUser·p1.00:   37.224 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 162918
  mean =      5.888 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 30284 
    [ 5.000,  7.500) = 117960 
    [ 7.500, 10.000) = 10602 
    [10.000, 12.500) = 2833 
    [12.500, 15.000) = 727 
    [15.000, 17.500) = 265 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 44 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      5.513 ms/op
     p(90.0000) =      7.340 ms/op
     p(95.0000) =      8.765 ms/op
     p(99.0000) =     11.731 ms/op
     p(99.9000) =     25.627 ms/op
     p(99.9900) =     34.669 ms/op
     p(99.9990) =     36.235 ms/op
     p(99.9999) =     37.224 ms/op
    p(100.0000) =     37.224 ms/op


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
# Warmup Iteration   1: 20.563 ±(99.9%) 0.390 ms/op
# Warmup Iteration   2: 8.017 ±(99.9%) 0.062 ms/op
# Warmup Iteration   3: 6.234 ±(99.9%) 0.030 ms/op
Iteration   1: 6.022 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.817 ms/op
                 getUser·p0.50:   5.718 ms/op
                 getUser·p0.90:   7.340 ms/op
                 getUser·p0.95:   8.618 ms/op
                 getUser·p0.99:   11.485 ms/op
                 getUser·p0.999:  15.791 ms/op
                 getUser·p0.9999: 25.199 ms/op
                 getUser·p1.00:   26.706 ms/op

Iteration   2: 6.034 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.491 ms/op
                 getUser·p0.50:   5.685 ms/op
                 getUser·p0.90:   7.258 ms/op
                 getUser·p0.95:   8.897 ms/op
                 getUser·p0.99:   12.747 ms/op
                 getUser·p0.999:  25.355 ms/op
                 getUser·p0.9999: 29.285 ms/op
                 getUser·p1.00:   29.950 ms/op

Iteration   3: 6.055 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.931 ms/op
                 getUser·p0.50:   5.734 ms/op
                 getUser·p0.90:   7.324 ms/op
                 getUser·p0.95:   8.667 ms/op
                 getUser·p0.99:   12.141 ms/op
                 getUser·p0.999:  19.307 ms/op
                 getUser·p0.9999: 27.984 ms/op
                 getUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 158925
  mean =      6.037 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 20510 
    [ 5.000,  7.500) = 124442 
    [ 7.500, 10.000) = 9557 
    [10.000, 12.500) = 3027 
    [12.500, 15.000) = 910 
    [15.000, 17.500) = 201 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.491 ms/op
     p(50.0000) =      5.710 ms/op
     p(90.0000) =      7.315 ms/op
     p(95.0000) =      8.716 ms/op
     p(99.0000) =     12.141 ms/op
     p(99.9000) =     22.254 ms/op
     p(99.9900) =     28.519 ms/op
     p(99.9990) =     31.807 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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
# Warmup Iteration   1: 21.386 ±(99.9%) 0.379 ms/op
# Warmup Iteration   2: 8.551 ±(99.9%) 0.055 ms/op
# Warmup Iteration   3: 7.040 ±(99.9%) 0.028 ms/op
Iteration   1: 7.009 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.662 ms/op
                 listUser·p0.50:   6.595 ms/op
                 listUser·p0.90:   8.634 ms/op
                 listUser·p0.95:   10.125 ms/op
                 listUser·p0.99:   13.320 ms/op
                 listUser·p0.999:  30.553 ms/op
                 listUser·p0.9999: 34.042 ms/op
                 listUser·p1.00:   36.110 ms/op

Iteration   2: 6.967 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.097 ms/op
                 listUser·p0.50:   6.562 ms/op
                 listUser·p0.90:   8.634 ms/op
                 listUser·p0.95:   10.191 ms/op
                 listUser·p0.99:   13.533 ms/op
                 listUser·p0.999:  31.527 ms/op
                 listUser·p0.9999: 35.613 ms/op
                 listUser·p1.00:   36.176 ms/op

Iteration   3: 6.993 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   2.413 ms/op
                 listUser·p0.50:   6.414 ms/op
                 listUser·p0.90:   8.962 ms/op
                 listUser·p0.95:   10.617 ms/op
                 listUser·p0.99:   14.598 ms/op
                 listUser·p0.999:  30.730 ms/op
                 listUser·p0.9999: 35.320 ms/op
                 listUser·p1.00:   36.241 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 137282
  mean =      6.990 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 2009 
    [ 5.000,  7.500) = 106184 
    [ 7.500, 10.000) = 21153 
    [10.000, 12.500) = 5482 
    [12.500, 15.000) = 1597 
    [15.000, 17.500) = 440 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 96 
    [30.000, 32.500) = 86 
    [32.500, 35.000) = 63 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      2.097 ms/op
     p(50.0000) =      6.529 ms/op
     p(90.0000) =      8.749 ms/op
     p(95.0000) =     10.322 ms/op
     p(99.0000) =     13.798 ms/op
     p(99.9000) =     30.704 ms/op
     p(99.9900) =     35.163 ms/op
     p(99.9990) =     36.217 ms/op
     p(99.9999) =     36.241 ms/op
    p(100.0000) =     36.241 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.449 ± 5.729  ops/ms
ClientPb.existUser                       thrpt       3   5.657 ± 2.358  ops/ms
ClientPb.getUser                         thrpt       3   5.553 ± 2.564  ops/ms
ClientPb.listUser                        thrpt       3   4.722 ± 1.696  ops/ms
ClientPb.createUser                       avgt       3   5.850 ± 0.962   ms/op
ClientPb.existUser                        avgt       3   5.478 ± 1.598   ms/op
ClientPb.getUser                          avgt       3   5.926 ± 3.128   ms/op
ClientPb.listUser                         avgt       3   6.851 ± 1.906   ms/op
ClientPb.createUser                     sample  157269   6.098 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.188           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.718           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.610           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.782           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.649           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.664           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.917           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.586           ms/op
ClientPb.existUser                      sample  162918   5.888 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.726           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.513           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.340           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.765           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.731           ms/op
ClientPb.existUser:existUser·p0.999     sample          25.627           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.669           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.224           ms/op
ClientPb.getUser                        sample  158925   6.037 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.491           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.710           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.315           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.716           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.141           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.254           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.519           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.472           ms/op
ClientPb.listUser                       sample  137282   6.990 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.097           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.529           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.749           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.322           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.798           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.704           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.163           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.241           ms/op
