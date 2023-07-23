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
# Warmup Iteration   1: 2.542 ops/ms
# Warmup Iteration   2: 6.062 ops/ms
# Warmup Iteration   3: 9.263 ops/ms
Iteration   1: 10.088 ops/ms
Iteration   2: 10.042 ops/ms
Iteration   3: 9.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.931 ±(99.9%) 4.274 ops/ms [Average]
  (min, avg, max) = (9.662, 9.931, 10.088), stdev = 0.234
  CI (99.9%): [5.657, 14.204] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.316 ops/ms
# Warmup Iteration   2: 8.547 ops/ms
# Warmup Iteration   3: 9.702 ops/ms
Iteration   1: 10.235 ops/ms
Iteration   2: 10.163 ops/ms
Iteration   3: 9.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.072 ±(99.9%) 4.056 ops/ms [Average]
  (min, avg, max) = (9.819, 10.072, 10.235), stdev = 0.222
  CI (99.9%): [6.016, 14.128] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.268 ops/ms
# Warmup Iteration   2: 8.638 ops/ms
# Warmup Iteration   3: 9.472 ops/ms
Iteration   1: 10.103 ops/ms
Iteration   2: 9.871 ops/ms
Iteration   3: 9.617 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.864 ±(99.9%) 4.433 ops/ms [Average]
  (min, avg, max) = (9.617, 9.864, 10.103), stdev = 0.243
  CI (99.9%): [5.431, 14.297] (assumes normal distribution)


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
# Warmup Iteration   1: 3.458 ops/ms
# Warmup Iteration   2: 7.875 ops/ms
# Warmup Iteration   3: 7.887 ops/ms
Iteration   1: 8.158 ops/ms
Iteration   2: 8.485 ops/ms
Iteration   3: 8.417 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.353 ±(99.9%) 3.148 ops/ms [Average]
  (min, avg, max) = (8.158, 8.353, 8.485), stdev = 0.173
  CI (99.9%): [5.205, 11.502] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.052 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.719 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.597 ±(99.9%) 0.003 ms/op
Iteration   1: 3.170 ±(99.9%) 0.005 ms/op
Iteration   2: 3.345 ±(99.9%) 0.004 ms/op
Iteration   3: 3.182 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.233 ±(99.9%) 1.779 ms/op [Average]
  (min, avg, max) = (3.170, 3.233, 3.345), stdev = 0.098
  CI (99.9%): [1.453, 5.012] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.425 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.601 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.218 ±(99.9%) 0.004 ms/op
Iteration   1: 3.086 ±(99.9%) 0.005 ms/op
Iteration   2: 3.209 ±(99.9%) 0.006 ms/op
Iteration   3: 3.042 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.112 ±(99.9%) 1.574 ms/op [Average]
  (min, avg, max) = (3.042, 3.112, 3.209), stdev = 0.086
  CI (99.9%): [1.538, 4.686] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.944 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.435 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.349 ±(99.9%) 0.007 ms/op
Iteration   1: 3.243 ±(99.9%) 0.006 ms/op
Iteration   2: 3.244 ±(99.9%) 0.007 ms/op
Iteration   3: 3.136 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.208 ±(99.9%) 1.138 ms/op [Average]
  (min, avg, max) = (3.136, 3.208, 3.244), stdev = 0.062
  CI (99.9%): [2.070, 4.346] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.351 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.069 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.759 ±(99.9%) 0.006 ms/op
Iteration   1: 3.715 ±(99.9%) 0.010 ms/op
Iteration   2: 3.796 ±(99.9%) 0.005 ms/op
Iteration   3: 3.878 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.796 ±(99.9%) 1.490 ms/op [Average]
  (min, avg, max) = (3.715, 3.796, 3.878), stdev = 0.082
  CI (99.9%): [2.306, 5.286] (assumes normal distribution)


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
# Warmup Iteration   1: 8.115 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.733 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.388 ±(99.9%) 0.010 ms/op
Iteration   1: 3.225 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.038 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.420 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  10.439 ms/op
                 createUser·p0.9999: 24.162 ms/op
                 createUser·p1.00:   25.199 ms/op

Iteration   2: 3.182 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.276 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.432 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  16.794 ms/op
                 createUser·p0.9999: 25.787 ms/op
                 createUser·p1.00:   26.051 ms/op

Iteration   3: 3.270 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.499 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   5.587 ms/op
                 createUser·p0.999:  16.220 ms/op
                 createUser·p0.9999: 22.872 ms/op
                 createUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297490
  mean =      3.225 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16443 
    [ 2.500,  5.000) = 276556 
    [ 5.000,  7.500) = 3696 
    [ 7.500, 10.000) = 296 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.038 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =     16.253 ms/op
     p(99.9900) =     25.068 ms/op
     p(99.9990) =     25.986 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 9.296 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.539 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.147 ±(99.9%) 0.008 ms/op
Iteration   1: 3.248 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.450 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.957 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   5.816 ms/op
                 existUser·p0.999:  9.772 ms/op
                 existUser·p0.9999: 24.510 ms/op
                 existUser·p1.00:   25.919 ms/op

Iteration   2: 3.144 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.223 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  17.203 ms/op
                 existUser·p0.9999: 23.527 ms/op
                 existUser·p1.00:   24.248 ms/op

Iteration   3: 3.067 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.233 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.457 ms/op
                 existUser·p0.99:   4.874 ms/op
                 existUser·p0.999:  10.268 ms/op
                 existUser·p0.9999: 20.644 ms/op
                 existUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304499
  mean =      3.151 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9823 
    [ 2.500,  5.000) = 289020 
    [ 5.000,  7.500) = 4804 
    [ 7.500, 10.000) = 493 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =     13.468 ms/op
     p(99.9900) =     23.909 ms/op
     p(99.9990) =     25.033 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.886 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 3.535 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.326 ±(99.9%) 0.011 ms/op
Iteration   1: 3.281 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.241 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   6.660 ms/op
                 getUser·p0.999:  14.659 ms/op
                 getUser·p0.9999: 21.660 ms/op
                 getUser·p1.00:   22.643 ms/op

Iteration   2: 3.354 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.208 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   6.783 ms/op
                 getUser·p0.999:  20.132 ms/op
                 getUser·p0.9999: 22.938 ms/op
                 getUser·p1.00:   23.724 ms/op

Iteration   3: 3.177 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.331 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.866 ms/op
                 getUser·p0.999:  9.110 ms/op
                 getUser·p0.9999: 23.260 ms/op
                 getUser·p1.00:   23.822 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293349
  mean =      3.269 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18184 
    [ 2.500,  5.000) = 269364 
    [ 5.000,  7.500) = 4457 
    [ 7.500, 10.000) = 877 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 140 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.208 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     14.216 ms/op
     p(99.9900) =     22.894 ms/op
     p(99.9990) =     23.792 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


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
# Warmup Iteration   1: 8.486 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.076 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.912 ±(99.9%) 0.012 ms/op
Iteration   1: 3.859 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.513 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   7.073 ms/op
                 listUser·p0.999:  14.959 ms/op
                 listUser·p0.9999: 24.645 ms/op
                 listUser·p1.00:   25.821 ms/op

Iteration   2: 3.809 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  13.779 ms/op
                 listUser·p0.9999: 15.811 ms/op
                 listUser·p1.00:   18.678 ms/op

Iteration   3: 3.907 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   5.104 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  12.468 ms/op
                 listUser·p0.9999: 15.974 ms/op
                 listUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248748
  mean =      3.858 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 239457 
    [ 5.000,  7.500) = 7125 
    [ 7.500, 10.000) = 1319 
    [10.000, 12.500) = 406 
    [12.500, 15.000) = 276 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.513 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     13.607 ms/op
     p(99.9900) =     23.527 ms/op
     p(99.9990) =     24.855 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.931 ± 4.274  ops/ms
ClientPb.existUser                       thrpt       3  10.072 ± 4.056  ops/ms
ClientPb.getUser                         thrpt       3   9.864 ± 4.433  ops/ms
ClientPb.listUser                        thrpt       3   8.353 ± 3.148  ops/ms
ClientPb.createUser                       avgt       3   3.233 ± 1.779   ms/op
ClientPb.existUser                        avgt       3   3.112 ± 1.574   ms/op
ClientPb.getUser                          avgt       3   3.208 ± 1.138   ms/op
ClientPb.listUser                         avgt       3   3.796 ± 1.490   ms/op
ClientPb.createUser                     sample  297490   3.225 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.038           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.523           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.538           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.253           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.068           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.051           ms/op
ClientPb.existUser                      sample  304499   3.151 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.223           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.437           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.969           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.652           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.468           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.909           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.919           ms/op
ClientPb.getUser                        sample  293349   3.269 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.208           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.645           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.998           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.111           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.216           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.894           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.822           ms/op
ClientPb.listUser                       sample  248748   3.858 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.513           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.719           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.157           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.193           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.607           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.527           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.821           ms/op
