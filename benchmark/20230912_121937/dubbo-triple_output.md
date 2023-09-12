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
# Warmup Iteration   1: 1.928 ops/ms
# Warmup Iteration   2: 4.421 ops/ms
# Warmup Iteration   3: 7.231 ops/ms
Iteration   1: 7.879 ops/ms
Iteration   2: 8.810 ops/ms
Iteration   3: 8.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.414 ±(99.9%) 8.777 ops/ms [Average]
  (min, avg, max) = (7.879, 8.414, 8.810), stdev = 0.481
  CI (99.9%): [≈ 0, 17.192] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.493 ops/ms
# Warmup Iteration   2: 7.626 ops/ms
# Warmup Iteration   3: 8.126 ops/ms
Iteration   1: 8.775 ops/ms
Iteration   2: 8.467 ops/ms
Iteration   3: 8.689 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.644 ±(99.9%) 2.898 ops/ms [Average]
  (min, avg, max) = (8.467, 8.644, 8.775), stdev = 0.159
  CI (99.9%): [5.746, 11.542] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.887 ops/ms
# Warmup Iteration   2: 7.246 ops/ms
# Warmup Iteration   3: 7.809 ops/ms
Iteration   1: 8.372 ops/ms
Iteration   2: 8.281 ops/ms
Iteration   3: 8.292 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.315 ±(99.9%) 0.906 ops/ms [Average]
  (min, avg, max) = (8.281, 8.315, 8.372), stdev = 0.050
  CI (99.9%): [7.409, 9.222] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.234 ops/ms
# Warmup Iteration   2: 5.996 ops/ms
# Warmup Iteration   3: 6.905 ops/ms
Iteration   1: 6.873 ops/ms
Iteration   2: 6.892 ops/ms
Iteration   3: 6.939 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.901 ±(99.9%) 0.618 ops/ms [Average]
  (min, avg, max) = (6.873, 6.901, 6.939), stdev = 0.034
  CI (99.9%): [6.283, 7.519] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 11.737 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.390 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.999 ±(99.9%) 0.003 ms/op
Iteration   1: 3.825 ±(99.9%) 0.010 ms/op
Iteration   2: 4.009 ±(99.9%) 0.007 ms/op
Iteration   3: 3.685 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.840 ±(99.9%) 2.968 ms/op [Average]
  (min, avg, max) = (3.685, 3.840, 4.009), stdev = 0.163
  CI (99.9%): [0.872, 6.807] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 11.540 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.175 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.773 ±(99.9%) 0.009 ms/op
Iteration   1: 3.826 ±(99.9%) 0.003 ms/op
Iteration   2: 3.764 ±(99.9%) 0.003 ms/op
Iteration   3: 3.675 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.755 ±(99.9%) 1.384 ms/op [Average]
  (min, avg, max) = (3.675, 3.755, 3.826), stdev = 0.076
  CI (99.9%): [2.371, 5.139] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.859 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.407 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.033 ±(99.9%) 0.005 ms/op
Iteration   1: 3.854 ±(99.9%) 0.009 ms/op
Iteration   2: 3.710 ±(99.9%) 0.006 ms/op
Iteration   3: 3.619 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.728 ±(99.9%) 2.162 ms/op [Average]
  (min, avg, max) = (3.619, 3.728, 3.854), stdev = 0.118
  CI (99.9%): [1.566, 5.889] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 13.672 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.857 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.674 ±(99.9%) 0.007 ms/op
Iteration   1: 4.509 ±(99.9%) 0.010 ms/op
Iteration   2: 4.475 ±(99.9%) 0.009 ms/op
Iteration   3: 4.410 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.465 ±(99.9%) 0.924 ms/op [Average]
  (min, avg, max) = (4.410, 4.465, 4.509), stdev = 0.051
  CI (99.9%): [3.540, 5.389] (assumes normal distribution)


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
# Warmup Iteration   1: 10.926 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 4.415 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.311 ±(99.9%) 0.017 ms/op
Iteration   1: 4.012 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.716 ms/op
                 createUser·p0.50:   3.777 ms/op
                 createUser·p0.90:   4.768 ms/op
                 createUser·p0.95:   5.366 ms/op
                 createUser·p0.99:   7.963 ms/op
                 createUser·p0.999:  24.117 ms/op
                 createUser·p0.9999: 27.329 ms/op
                 createUser·p1.00:   29.360 ms/op

Iteration   2: 3.944 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.878 ms/op
                 createUser·p0.50:   3.752 ms/op
                 createUser·p0.90:   4.637 ms/op
                 createUser·p0.95:   5.349 ms/op
                 createUser·p0.99:   7.660 ms/op
                 createUser·p0.999:  13.776 ms/op
                 createUser·p0.9999: 27.456 ms/op
                 createUser·p1.00:   27.951 ms/op

Iteration   3: 4.006 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.161 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   4.620 ms/op
                 createUser·p0.95:   5.022 ms/op
                 createUser·p0.99:   7.283 ms/op
                 createUser·p0.999:  29.632 ms/op
                 createUser·p0.9999: 33.686 ms/op
                 createUser·p1.00:   35.258 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 240699
  mean =      3.987 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 853 
    [ 2.500,  5.000) = 224764 
    [ 5.000,  7.500) = 12563 
    [ 7.500, 10.000) = 1519 
    [10.000, 12.500) = 616 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 117 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 54 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.235 ms/op
     p(99.0000) =      7.619 ms/op
     p(99.9000) =     23.865 ms/op
     p(99.9900) =     32.342 ms/op
     p(99.9990) =     35.166 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


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
# Warmup Iteration   1: 12.139 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.218 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.802 ±(99.9%) 0.010 ms/op
Iteration   1: 3.719 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.860 ms/op
                 existUser·p0.50:   3.596 ms/op
                 existUser·p0.90:   4.121 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   6.504 ms/op
                 existUser·p0.999:  22.608 ms/op
                 existUser·p0.9999: 24.707 ms/op
                 existUser·p1.00:   25.952 ms/op

Iteration   2: 3.948 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.542 ms/op
                 existUser·p0.50:   3.756 ms/op
                 existUser·p0.90:   4.530 ms/op
                 existUser·p0.95:   5.112 ms/op
                 existUser·p0.99:   7.807 ms/op
                 existUser·p0.999:  13.369 ms/op
                 existUser·p0.9999: 26.834 ms/op
                 existUser·p1.00:   27.460 ms/op

Iteration   3: 3.678 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.155 ms/op
                 existUser·p0.50:   3.559 ms/op
                 existUser·p0.90:   4.202 ms/op
                 existUser·p0.95:   4.645 ms/op
                 existUser·p0.99:   6.889 ms/op
                 existUser·p0.999:  25.429 ms/op
                 existUser·p0.9999: 33.063 ms/op
                 existUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 254059
  mean =      3.778 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1993 
    [ 2.500,  5.000) = 242278 
    [ 5.000,  7.500) = 7528 
    [ 7.500, 10.000) = 1436 
    [10.000, 12.500) = 484 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 112 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      7.307 ms/op
     p(99.9000) =     22.313 ms/op
     p(99.9900) =     31.843 ms/op
     p(99.9990) =     33.675 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


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
# Warmup Iteration   1: 12.650 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.672 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.147 ±(99.9%) 0.013 ms/op
Iteration   1: 4.004 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.753 ms/op
                 getUser·p0.50:   3.736 ms/op
                 getUser·p0.90:   4.719 ms/op
                 getUser·p0.95:   6.750 ms/op
                 getUser·p0.99:   9.293 ms/op
                 getUser·p0.999:  18.836 ms/op
                 getUser·p0.9999: 22.873 ms/op
                 getUser·p1.00:   24.347 ms/op

Iteration   2: 3.895 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.788 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   8.004 ms/op
                 getUser·p0.999:  11.845 ms/op
                 getUser·p0.9999: 27.733 ms/op
                 getUser·p1.00:   28.803 ms/op

Iteration   3: 3.681 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.604 ms/op
                 getUser·p0.50:   3.559 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   6.652 ms/op
                 getUser·p0.999:  22.680 ms/op
                 getUser·p0.9999: 27.918 ms/op
                 getUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 248887
  mean =      3.855 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2023 
    [ 2.500,  5.000) = 232911 
    [ 5.000,  7.500) = 9348 
    [ 7.500, 10.000) = 3627 
    [10.000, 12.500) = 656 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 60 

  Percentiles, ms/op:
      p(0.0000) =      1.604 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      5.341 ms/op
     p(99.0000) =      8.200 ms/op
     p(99.9000) =     18.266 ms/op
     p(99.9900) =     27.689 ms/op
     p(99.9990) =     28.904 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


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
# Warmup Iteration   1: 13.701 ±(99.9%) 0.200 ms/op
# Warmup Iteration   2: 5.275 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.578 ±(99.9%) 0.017 ms/op
Iteration   1: 4.592 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   4.391 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   6.332 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  23.712 ms/op
                 listUser·p0.9999: 26.935 ms/op
                 listUser·p1.00:   27.197 ms/op

Iteration   2: 4.794 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.774 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   6.390 ms/op
                 listUser·p0.99:   9.732 ms/op
                 listUser·p0.999:  19.833 ms/op
                 listUser·p0.9999: 24.865 ms/op
                 listUser·p1.00:   26.018 ms/op

Iteration   3: 4.669 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   6.070 ms/op
                 listUser·p0.99:   9.142 ms/op
                 listUser·p0.999:  17.203 ms/op
                 listUser·p0.9999: 22.039 ms/op
                 listUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 204962
  mean =      4.684 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 174011 
    [ 5.000,  7.500) = 24620 
    [ 7.500, 10.000) = 4984 
    [10.000, 12.500) = 612 
    [12.500, 15.000) = 176 
    [15.000, 17.500) = 166 
    [17.500, 20.000) = 155 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      1.774 ms/op
     p(50.0000) =      4.481 ms/op
     p(90.0000) =      5.218 ms/op
     p(95.0000) =      6.283 ms/op
     p(99.0000) =      9.175 ms/op
     p(99.9000) =     19.924 ms/op
     p(99.9900) =     26.428 ms/op
     p(99.9990) =     27.130 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.414 ± 8.777  ops/ms
ClientPb.existUser                       thrpt       3   8.644 ± 2.898  ops/ms
ClientPb.getUser                         thrpt       3   8.315 ± 0.906  ops/ms
ClientPb.listUser                        thrpt       3   6.901 ± 0.618  ops/ms
ClientPb.createUser                       avgt       3   3.840 ± 2.968   ms/op
ClientPb.existUser                        avgt       3   3.755 ± 1.384   ms/op
ClientPb.getUser                          avgt       3   3.728 ± 2.162   ms/op
ClientPb.listUser                         avgt       3   4.465 ± 0.924   ms/op
ClientPb.createUser                     sample  240699   3.987 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.161           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.678           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.235           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.619           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.865           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.342           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.258           ms/op
ClientPb.existUser                      sample  254059   3.778 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.155           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.613           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.293           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.735           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.307           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.313           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.843           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.275           ms/op
ClientPb.getUser                        sample  248887   3.855 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.604           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.686           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.366           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.341           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.200           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.266           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.689           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.000           ms/op
ClientPb.listUser                       sample  204962   4.684 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.774           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.218           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.283           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.175           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.924           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.428           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.197           ms/op
