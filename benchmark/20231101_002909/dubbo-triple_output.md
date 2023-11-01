# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.816 ops/ms
# Warmup Iteration   2: 3.677 ops/ms
# Warmup Iteration   3: 7.475 ops/ms
Iteration   1: 7.551 ops/ms
Iteration   2: 8.228 ops/ms
Iteration   3: 8.109 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.963 ±(99.9%) 6.597 ops/ms [Average]
  (min, avg, max) = (7.551, 7.963, 8.228), stdev = 0.362
  CI (99.9%): [1.366, 14.560] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.097 ops/ms
# Warmup Iteration   2: 7.315 ops/ms
# Warmup Iteration   3: 7.944 ops/ms
Iteration   1: 8.484 ops/ms
Iteration   2: 8.509 ops/ms
Iteration   3: 8.618 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.537 ±(99.9%) 1.301 ops/ms [Average]
  (min, avg, max) = (8.484, 8.537, 8.618), stdev = 0.071
  CI (99.9%): [7.236, 9.838] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.279 ops/ms
# Warmup Iteration   2: 7.129 ops/ms
# Warmup Iteration   3: 7.622 ops/ms
Iteration   1: 7.972 ops/ms
Iteration   2: 7.918 ops/ms
Iteration   3: 7.967 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.953 ±(99.9%) 0.542 ops/ms [Average]
  (min, avg, max) = (7.918, 7.953, 7.972), stdev = 0.030
  CI (99.9%): [7.411, 8.494] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.961 ops/ms
# Warmup Iteration   2: 5.796 ops/ms
# Warmup Iteration   3: 6.566 ops/ms
Iteration   1: 6.788 ops/ms
Iteration   2: 6.764 ops/ms
Iteration   3: 6.685 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.746 ±(99.9%) 0.990 ops/ms [Average]
  (min, avg, max) = (6.685, 6.746, 6.788), stdev = 0.054
  CI (99.9%): [5.756, 7.736] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 13.351 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.383 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.347 ±(99.9%) 0.004 ms/op
Iteration   1: 4.117 ±(99.9%) 0.006 ms/op
Iteration   2: 3.934 ±(99.9%) 0.005 ms/op
Iteration   3: 3.962 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.004 ±(99.9%) 1.795 ms/op [Average]
  (min, avg, max) = (3.934, 4.004, 4.117), stdev = 0.098
  CI (99.9%): [2.209, 5.799] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 11.567 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.189 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.890 ±(99.9%) 0.005 ms/op
Iteration   1: 3.803 ±(99.9%) 0.004 ms/op
Iteration   2: 3.829 ±(99.9%) 0.004 ms/op
Iteration   3: 3.865 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.832 ±(99.9%) 0.576 ms/op [Average]
  (min, avg, max) = (3.803, 3.832, 3.865), stdev = 0.032
  CI (99.9%): [3.257, 4.408] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 12.261 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.586 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.096 ±(99.9%) 0.004 ms/op
Iteration   1: 3.974 ±(99.9%) 0.005 ms/op
Iteration   2: 4.000 ±(99.9%) 0.004 ms/op
Iteration   3: 3.965 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.980 ±(99.9%) 0.334 ms/op [Average]
  (min, avg, max) = (3.965, 3.980, 4.000), stdev = 0.018
  CI (99.9%): [3.646, 4.314] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 14.539 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.365 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.779 ±(99.9%) 0.004 ms/op
Iteration   1: 4.660 ±(99.9%) 0.007 ms/op
Iteration   2: 4.886 ±(99.9%) 0.005 ms/op
Iteration   3: 4.717 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.754 ±(99.9%) 2.144 ms/op [Average]
  (min, avg, max) = (4.660, 4.754, 4.886), stdev = 0.118
  CI (99.9%): [2.611, 6.898] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 12.094 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 5.196 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.238 ±(99.9%) 0.018 ms/op
Iteration   1: 4.110 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.849 ms/op
                 createUser·p0.50:   3.924 ms/op
                 createUser·p0.90:   4.825 ms/op
                 createUser·p0.95:   5.136 ms/op
                 createUser·p0.99:   6.824 ms/op
                 createUser·p0.999:  23.827 ms/op
                 createUser·p0.9999: 26.491 ms/op
                 createUser·p1.00:   27.394 ms/op

Iteration   2: 3.965 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.102 ms/op
                 createUser·p0.50:   3.838 ms/op
                 createUser·p0.90:   4.637 ms/op
                 createUser·p0.95:   5.030 ms/op
                 createUser·p0.99:   6.971 ms/op
                 createUser·p0.999:  25.136 ms/op
                 createUser·p0.9999: 28.762 ms/op
                 createUser·p1.00:   29.983 ms/op

Iteration   3: 3.961 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.375 ms/op
                 createUser·p0.50:   3.760 ms/op
                 createUser·p0.90:   4.563 ms/op
                 createUser·p0.95:   4.882 ms/op
                 createUser·p0.99:   7.239 ms/op
                 createUser·p0.999:  14.361 ms/op
                 createUser·p0.9999: 30.310 ms/op
                 createUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 239498
  mean =      4.011 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 260 
    [ 2.500,  5.000) = 226561 
    [ 5.000,  7.500) = 10816 
    [ 7.500, 10.000) = 1082 
    [10.000, 12.500) = 395 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 90 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.375 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     23.806 ms/op
     p(99.9900) =     29.917 ms/op
     p(99.9990) =     32.074 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 12.244 ±(99.9%) 0.161 ms/op
# Warmup Iteration   2: 4.378 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.962 ±(99.9%) 0.010 ms/op
Iteration   1: 3.892 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.419 ms/op
                 existUser·p0.50:   3.752 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   7.627 ms/op
                 existUser·p0.999:  23.511 ms/op
                 existUser·p0.9999: 25.716 ms/op
                 existUser·p1.00:   26.051 ms/op

Iteration   2: 3.798 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.954 ms/op
                 existUser·p0.50:   3.674 ms/op
                 existUser·p0.90:   4.149 ms/op
                 existUser·p0.95:   4.481 ms/op
                 existUser·p0.99:   7.145 ms/op
                 existUser·p0.999:  14.584 ms/op
                 existUser·p0.9999: 30.605 ms/op
                 existUser·p1.00:   31.031 ms/op

Iteration   3: 3.876 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.975 ms/op
                 existUser·p0.50:   3.777 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.588 ms/op
                 existUser·p0.99:   6.784 ms/op
                 existUser·p0.999:  14.058 ms/op
                 existUser·p0.9999: 30.368 ms/op
                 existUser·p1.00:   31.818 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 248918
  mean =      3.855 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 326 
    [ 2.500,  5.000) = 240902 
    [ 5.000,  7.500) = 5581 
    [ 7.500, 10.000) = 1330 
    [10.000, 12.500) = 416 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.975 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      7.242 ms/op
     p(99.9000) =     14.944 ms/op
     p(99.9900) =     30.347 ms/op
     p(99.9990) =     31.294 ms/op
     p(99.9999) =     31.818 ms/op
    p(100.0000) =     31.818 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 13.108 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 4.782 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.194 ±(99.9%) 0.013 ms/op
Iteration   1: 4.139 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.714 ms/op
                 getUser·p0.50:   3.932 ms/op
                 getUser·p0.90:   4.702 ms/op
                 getUser·p0.95:   5.292 ms/op
                 getUser·p0.99:   8.421 ms/op
                 getUser·p0.999:  24.478 ms/op
                 getUser·p0.9999: 38.797 ms/op
                 getUser·p1.00:   40.698 ms/op

Iteration   2: 4.157 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.987 ms/op
                 getUser·p0.50:   3.916 ms/op
                 getUser·p0.90:   4.760 ms/op
                 getUser·p0.95:   5.472 ms/op
                 getUser·p0.99:   8.465 ms/op
                 getUser·p0.999:  12.583 ms/op
                 getUser·p0.9999: 27.460 ms/op
                 getUser·p1.00:   28.279 ms/op

Iteration   3: 3.991 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.798 ms/op
                 getUser·p0.50:   3.871 ms/op
                 getUser·p0.90:   4.456 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   6.717 ms/op
                 getUser·p0.999:  26.555 ms/op
                 getUser·p0.9999: 29.295 ms/op
                 getUser·p1.00:   30.704 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 234463
  mean =      4.094 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 221168 
    [ 5.000, 10.000) = 12524 
    [10.000, 15.000) = 471 
    [15.000, 20.000) = 12 
    [20.000, 25.000) = 85 
    [25.000, 30.000) = 168 
    [30.000, 35.000) = 7 
    [35.000, 40.000) = 26 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.120 ms/op
     p(99.0000) =      8.217 ms/op
     p(99.9000) =     24.495 ms/op
     p(99.9900) =     37.916 ms/op
     p(99.9990) =     39.995 ms/op
     p(99.9999) =     40.698 ms/op
    p(100.0000) =     40.698 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.878 ±(99.9%) 0.195 ms/op
# Warmup Iteration   2: 5.519 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.856 ±(99.9%) 0.016 ms/op
Iteration   1: 4.778 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.595 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   7.771 ms/op
                 listUser·p0.999:  25.727 ms/op
                 listUser·p0.9999: 28.672 ms/op
                 listUser·p1.00:   29.327 ms/op

Iteration   2: 4.815 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.913 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   6.128 ms/op
                 listUser·p0.99:   9.961 ms/op
                 listUser·p0.999:  17.203 ms/op
                 listUser·p0.9999: 24.129 ms/op
                 listUser·p1.00:   26.673 ms/op

Iteration   3: 4.724 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.909 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   8.503 ms/op
                 listUser·p0.999:  15.647 ms/op
                 listUser·p0.9999: 18.259 ms/op
                 listUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 201045
  mean =      4.772 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 164783 
    [ 5.000,  7.500) = 32308 
    [ 7.500, 10.000) = 2729 
    [10.000, 12.500) = 681 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 198 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 59 

  Percentiles, ms/op:
      p(0.0000) =      1.595 ms/op
     p(50.0000) =      4.628 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      8.831 ms/op
     p(99.9000) =     17.727 ms/op
     p(99.9900) =     27.489 ms/op
     p(99.9990) =     28.836 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.963 ± 6.597  ops/ms
ClientPb.existUser                       thrpt       3   8.537 ± 1.301  ops/ms
ClientPb.getUser                         thrpt       3   7.953 ± 0.542  ops/ms
ClientPb.listUser                        thrpt       3   6.746 ± 0.990  ops/ms
ClientPb.createUser                       avgt       3   4.004 ± 1.795   ms/op
ClientPb.existUser                        avgt       3   3.832 ± 0.576   ms/op
ClientPb.getUser                          avgt       3   3.980 ± 0.334   ms/op
ClientPb.listUser                         avgt       3   4.754 ± 2.144   ms/op
ClientPb.createUser                     sample  239498   4.011 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.375           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.850           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.694           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.030           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.939           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.806           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.917           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.178           ms/op
ClientPb.existUser                      sample  248918   3.855 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.975           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.727           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.235           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.579           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.242           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.944           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.347           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.818           ms/op
ClientPb.getUser                        sample  234463   4.094 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.798           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.637           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.120           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.217           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.495           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.916           ms/op
ClientPb.getUser:getUser·p1.00          sample          40.698           ms/op
ClientPb.listUser                       sample  201045   4.772 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.595           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.202           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.831           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.727           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.489           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.327           ms/op
