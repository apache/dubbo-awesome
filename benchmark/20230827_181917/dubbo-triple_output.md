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
# Warmup Iteration   1: 2.608 ops/ms
# Warmup Iteration   2: 5.995 ops/ms
# Warmup Iteration   3: 8.831 ops/ms
Iteration   1: 9.813 ops/ms
Iteration   2: 9.460 ops/ms
Iteration   3: 9.723 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.665 ±(99.9%) 3.347 ops/ms [Average]
  (min, avg, max) = (9.460, 9.665, 9.813), stdev = 0.183
  CI (99.9%): [6.318, 13.013] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.720 ops/ms
# Warmup Iteration   2: 9.042 ops/ms
# Warmup Iteration   3: 9.937 ops/ms
Iteration   1: 10.074 ops/ms
Iteration   2: 10.255 ops/ms
Iteration   3: 10.191 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.173 ±(99.9%) 1.670 ops/ms [Average]
  (min, avg, max) = (10.074, 10.173, 10.255), stdev = 0.092
  CI (99.9%): [8.503, 11.844] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.557 ops/ms
# Warmup Iteration   2: 8.932 ops/ms
# Warmup Iteration   3: 9.515 ops/ms
Iteration   1: 9.380 ops/ms
Iteration   2: 9.554 ops/ms
Iteration   3: 9.419 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.451 ±(99.9%) 1.665 ops/ms [Average]
  (min, avg, max) = (9.380, 9.451, 9.554), stdev = 0.091
  CI (99.9%): [7.786, 11.116] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.352 ops/ms
# Warmup Iteration   2: 7.542 ops/ms
# Warmup Iteration   3: 8.191 ops/ms
Iteration   1: 8.549 ops/ms
Iteration   2: 8.491 ops/ms
Iteration   3: 8.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.534 ±(99.9%) 0.694 ops/ms [Average]
  (min, avg, max) = (8.491, 8.534, 8.563), stdev = 0.038
  CI (99.9%): [7.840, 9.228] (assumes normal distribution)


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
# Warmup Iteration   1: 8.150 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.552 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.304 ±(99.9%) 0.010 ms/op
Iteration   1: 3.334 ±(99.9%) 0.006 ms/op
Iteration   2: 3.330 ±(99.9%) 0.005 ms/op
Iteration   3: 3.204 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.289 ±(99.9%) 1.354 ms/op [Average]
  (min, avg, max) = (3.204, 3.289, 3.334), stdev = 0.074
  CI (99.9%): [1.935, 4.643] (assumes normal distribution)


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
# Warmup Iteration   1: 7.821 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.413 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.004 ms/op
Iteration   1: 3.171 ±(99.9%) 0.006 ms/op
Iteration   2: 3.191 ±(99.9%) 0.006 ms/op
Iteration   3: 3.211 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.191 ±(99.9%) 0.365 ms/op [Average]
  (min, avg, max) = (3.171, 3.191, 3.211), stdev = 0.020
  CI (99.9%): [2.826, 3.556] (assumes normal distribution)


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
# Warmup Iteration   1: 8.116 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.504 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.456 ±(99.9%) 0.003 ms/op
Iteration   1: 3.355 ±(99.9%) 0.006 ms/op
Iteration   2: 3.205 ±(99.9%) 0.005 ms/op
Iteration   3: 3.201 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.253 ±(99.9%) 1.600 ms/op [Average]
  (min, avg, max) = (3.201, 3.253, 3.355), stdev = 0.088
  CI (99.9%): [1.653, 4.853] (assumes normal distribution)


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
# Warmup Iteration   1: 10.000 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.296 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.896 ±(99.9%) 0.005 ms/op
Iteration   1: 3.762 ±(99.9%) 0.006 ms/op
Iteration   2: 3.697 ±(99.9%) 0.011 ms/op
Iteration   3: 3.758 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.739 ±(99.9%) 0.670 ms/op [Average]
  (min, avg, max) = (3.697, 3.739, 3.762), stdev = 0.037
  CI (99.9%): [3.069, 4.409] (assumes normal distribution)


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
# Warmup Iteration   1: 7.598 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.752 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.291 ±(99.9%) 0.009 ms/op
Iteration   1: 3.205 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.231 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   6.201 ms/op
                 createUser·p0.999:  19.792 ms/op
                 createUser·p0.9999: 22.678 ms/op
                 createUser·p1.00:   23.396 ms/op

Iteration   2: 3.267 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.098 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   6.185 ms/op
                 createUser·p0.999:  13.582 ms/op
                 createUser·p0.9999: 26.444 ms/op
                 createUser·p1.00:   26.903 ms/op

Iteration   3: 3.163 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.325 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   5.587 ms/op
                 createUser·p0.999:  9.867 ms/op
                 createUser·p0.9999: 21.398 ms/op
                 createUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298756
  mean =      3.211 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11402 
    [ 2.500,  5.000) = 279826 
    [ 5.000,  7.500) = 6213 
    [ 7.500, 10.000) = 851 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 133 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.098 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     17.219 ms/op
     p(99.9900) =     25.043 ms/op
     p(99.9990) =     26.805 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


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
# Warmup Iteration   1: 7.600 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.410 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.137 ±(99.9%) 0.007 ms/op
Iteration   1: 3.195 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.796 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.939 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  10.568 ms/op
                 existUser·p0.9999: 21.561 ms/op
                 existUser·p1.00:   21.889 ms/op

Iteration   2: 3.135 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.323 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   4.010 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  16.089 ms/op
                 existUser·p0.9999: 20.605 ms/op
                 existUser·p1.00:   21.266 ms/op

Iteration   3: 3.145 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.755 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   6.103 ms/op
                 existUser·p0.999:  14.111 ms/op
                 existUser·p0.9999: 21.332 ms/op
                 existUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303898
  mean =      3.158 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20332 
    [ 2.500,  5.000) = 276406 
    [ 5.000,  7.500) = 5966 
    [ 7.500, 10.000) = 742 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 133 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.755 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     14.293 ms/op
     p(99.9900) =     21.299 ms/op
     p(99.9990) =     21.789 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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
# Warmup Iteration   1: 8.579 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.537 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.411 ±(99.9%) 0.010 ms/op
Iteration   1: 3.339 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.120 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   6.939 ms/op
                 getUser·p0.999:  19.767 ms/op
                 getUser·p0.9999: 27.098 ms/op
                 getUser·p1.00:   28.672 ms/op

Iteration   2: 3.191 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.413 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   5.784 ms/op
                 getUser·p0.999:  10.895 ms/op
                 getUser·p0.9999: 24.904 ms/op
                 getUser·p1.00:   25.362 ms/op

Iteration   3: 3.293 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.356 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   6.504 ms/op
                 getUser·p0.999:  15.594 ms/op
                 getUser·p0.9999: 25.293 ms/op
                 getUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293136
  mean =      3.273 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12166 
    [ 2.500,  5.000) = 271629 
    [ 5.000,  7.500) = 7607 
    [ 7.500, 10.000) = 1157 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      1.120 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.496 ms/op
     p(99.9000) =     18.935 ms/op
     p(99.9900) =     25.745 ms/op
     p(99.9990) =     28.052 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


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
# Warmup Iteration   1: 9.611 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.067 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.980 ±(99.9%) 0.012 ms/op
Iteration   1: 3.793 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.616 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  16.138 ms/op
                 listUser·p0.9999: 22.741 ms/op
                 listUser·p1.00:   25.461 ms/op

Iteration   2: 3.893 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.413 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.907 ms/op
                 listUser·p0.999:  15.218 ms/op
                 listUser·p0.9999: 18.350 ms/op
                 listUser·p1.00:   18.416 ms/op

Iteration   3: 3.899 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.626 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.381 ms/op
                 listUser·p0.999:  13.140 ms/op
                 listUser·p0.9999: 19.835 ms/op
                 listUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248516
  mean =      3.861 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 74 
    [ 2.500,  5.000) = 239542 
    [ 5.000,  7.500) = 6371 
    [ 7.500, 10.000) = 1729 
    [10.000, 12.500) = 382 
    [12.500, 15.000) = 154 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.616 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      7.553 ms/op
     p(99.9000) =     15.196 ms/op
     p(99.9900) =     21.970 ms/op
     p(99.9990) =     22.987 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.665 ± 3.347  ops/ms
ClientPb.existUser                       thrpt       3  10.173 ± 1.670  ops/ms
ClientPb.getUser                         thrpt       3   9.451 ± 1.665  ops/ms
ClientPb.listUser                        thrpt       3   8.534 ± 0.694  ops/ms
ClientPb.createUser                       avgt       3   3.289 ± 1.354   ms/op
ClientPb.existUser                        avgt       3   3.191 ± 0.365   ms/op
ClientPb.getUser                          avgt       3   3.253 ± 1.600   ms/op
ClientPb.listUser                         avgt       3   3.739 ± 0.670   ms/op
ClientPb.createUser                     sample  298756   3.211 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.098           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.650           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.084           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.947           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.219           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.043           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.903           ms/op
ClientPb.existUser                      sample  303898   3.158 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.755           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.428           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.887           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.833           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.293           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.299           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.889           ms/op
ClientPb.getUser                        sample  293136   3.273 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.120           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.645           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.496           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.935           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.745           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.672           ms/op
ClientPb.listUser                       sample  248516   3.861 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.616           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.744           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.227           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.553           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.196           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.970           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.461           ms/op
