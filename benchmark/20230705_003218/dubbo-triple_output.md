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
# Warmup Iteration   1: 2.229 ops/ms
# Warmup Iteration   2: 5.090 ops/ms
# Warmup Iteration   3: 8.255 ops/ms
Iteration   1: 9.133 ops/ms
Iteration   2: 9.531 ops/ms
Iteration   3: 9.616 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.427 ±(99.9%) 4.698 ops/ms [Average]
  (min, avg, max) = (9.133, 9.427, 9.616), stdev = 0.257
  CI (99.9%): [4.729, 14.124] (assumes normal distribution)


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
# Warmup Iteration   1: 2.930 ops/ms
# Warmup Iteration   2: 8.741 ops/ms
# Warmup Iteration   3: 9.765 ops/ms
Iteration   1: 9.935 ops/ms
Iteration   2: 9.587 ops/ms
Iteration   3: 9.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.813 ±(99.9%) 3.565 ops/ms [Average]
  (min, avg, max) = (9.587, 9.813, 9.935), stdev = 0.195
  CI (99.9%): [6.247, 13.378] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.271 ops/ms
# Warmup Iteration   2: 8.366 ops/ms
# Warmup Iteration   3: 8.946 ops/ms
Iteration   1: 9.351 ops/ms
Iteration   2: 8.991 ops/ms
Iteration   3: 9.338 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.226 ±(99.9%) 3.726 ops/ms [Average]
  (min, avg, max) = (8.991, 9.226, 9.351), stdev = 0.204
  CI (99.9%): [5.501, 12.952] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.671 ops/ms
# Warmup Iteration   2: 6.977 ops/ms
# Warmup Iteration   3: 7.929 ops/ms
Iteration   1: 7.882 ops/ms
Iteration   2: 7.932 ops/ms
Iteration   3: 8.152 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.989 ±(99.9%) 2.623 ops/ms [Average]
  (min, avg, max) = (7.882, 7.989, 8.152), stdev = 0.144
  CI (99.9%): [5.366, 10.612] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.566 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.931 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.575 ±(99.9%) 0.003 ms/op
Iteration   1: 3.390 ±(99.9%) 0.008 ms/op
Iteration   2: 3.301 ±(99.9%) 0.009 ms/op
Iteration   3: 3.352 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.348 ±(99.9%) 0.818 ms/op [Average]
  (min, avg, max) = (3.301, 3.348, 3.390), stdev = 0.045
  CI (99.9%): [2.529, 4.166] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.659 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.594 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.253 ±(99.9%) 0.008 ms/op
Iteration   1: 3.305 ±(99.9%) 0.004 ms/op
Iteration   2: 3.335 ±(99.9%) 0.008 ms/op
Iteration   3: 3.298 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.313 ±(99.9%) 0.352 ms/op [Average]
  (min, avg, max) = (3.298, 3.313, 3.335), stdev = 0.019
  CI (99.9%): [2.961, 3.665] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.664 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.632 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.617 ±(99.9%) 0.005 ms/op
Iteration   1: 3.352 ±(99.9%) 0.007 ms/op
Iteration   2: 3.555 ±(99.9%) 0.003 ms/op
Iteration   3: 3.490 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.466 ±(99.9%) 1.886 ms/op [Average]
  (min, avg, max) = (3.352, 3.466, 3.555), stdev = 0.103
  CI (99.9%): [1.580, 5.351] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.758 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.546 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.058 ±(99.9%) 0.011 ms/op
Iteration   1: 3.973 ±(99.9%) 0.010 ms/op
Iteration   2: 4.048 ±(99.9%) 0.005 ms/op
Iteration   3: 3.953 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.991 ±(99.9%) 0.915 ms/op [Average]
  (min, avg, max) = (3.953, 3.991, 4.048), stdev = 0.050
  CI (99.9%): [3.077, 4.906] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 11.744 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.131 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.779 ±(99.9%) 0.015 ms/op
Iteration   1: 3.461 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.130 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   6.799 ms/op
                 createUser·p0.999:  18.530 ms/op
                 createUser·p0.9999: 21.266 ms/op
                 createUser·p1.00:   21.856 ms/op

Iteration   2: 3.577 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.577 ms/op
                 createUser·p0.50:   3.428 ms/op
                 createUser·p0.90:   4.203 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   5.931 ms/op
                 createUser·p0.999:  20.371 ms/op
                 createUser·p0.9999: 23.206 ms/op
                 createUser·p1.00:   24.183 ms/op

Iteration   3: 3.387 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.573 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.047 ms/op
                 createUser·p0.99:   5.333 ms/op
                 createUser·p0.999:  23.331 ms/op
                 createUser·p0.9999: 28.133 ms/op
                 createUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276231
  mean =      3.473 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4937 
    [ 2.500,  5.000) = 265847 
    [ 5.000,  7.500) = 4315 
    [ 7.500, 10.000) = 661 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 145 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =     20.538 ms/op
     p(99.9900) =     27.099 ms/op
     p(99.9990) =     28.694 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.193 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.665 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.335 ±(99.9%) 0.009 ms/op
Iteration   1: 3.305 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.573 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  12.935 ms/op
                 existUser·p0.9999: 21.113 ms/op
                 existUser·p1.00:   22.446 ms/op

Iteration   2: 3.289 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.227 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   6.277 ms/op
                 existUser·p0.999:  9.748 ms/op
                 existUser·p0.9999: 22.970 ms/op
                 existUser·p1.00:   23.691 ms/op

Iteration   3: 3.295 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.192 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   6.242 ms/op
                 existUser·p0.999:  12.433 ms/op
                 existUser·p0.9999: 24.291 ms/op
                 existUser·p1.00:   25.264 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291096
  mean =      3.296 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8094 
    [ 2.500,  5.000) = 275817 
    [ 5.000,  7.500) = 6116 
    [ 7.500, 10.000) = 679 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 138 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.192 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     12.385 ms/op
     p(99.9900) =     23.131 ms/op
     p(99.9990) =     24.513 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.525 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.890 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.406 ±(99.9%) 0.009 ms/op
Iteration   1: 3.436 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.866 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   4.170 ms/op
                 getUser·p0.99:   6.234 ms/op
                 getUser·p0.999:  15.973 ms/op
                 getUser·p0.9999: 25.319 ms/op
                 getUser·p1.00:   26.280 ms/op

Iteration   2: 3.419 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.190 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.137 ms/op
                 getUser·p0.99:   5.768 ms/op
                 getUser·p0.999:  21.883 ms/op
                 getUser·p0.9999: 24.826 ms/op
                 getUser·p1.00:   25.428 ms/op

Iteration   3: 3.508 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.219 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   4.022 ms/op
                 getUser·p0.95:   4.841 ms/op
                 getUser·p0.99:   6.750 ms/op
                 getUser·p0.999:  19.787 ms/op
                 getUser·p0.9999: 24.212 ms/op
                 getUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277845
  mean =      3.454 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9003 
    [ 2.500,  5.000) = 259977 
    [ 5.000,  7.500) = 7646 
    [ 7.500, 10.000) = 747 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 133 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      6.431 ms/op
     p(99.9000) =     15.974 ms/op
     p(99.9900) =     24.780 ms/op
     p(99.9990) =     26.138 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.805 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.521 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.182 ±(99.9%) 0.014 ms/op
Iteration   1: 4.001 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.167 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  19.691 ms/op
                 listUser·p0.9999: 24.411 ms/op
                 listUser·p1.00:   25.199 ms/op

Iteration   2: 3.925 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.372 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.125 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   5.814 ms/op
                 listUser·p0.999:  14.270 ms/op
                 listUser·p0.9999: 17.231 ms/op
                 listUser·p1.00:   17.957 ms/op

Iteration   3: 3.930 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.137 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  14.572 ms/op
                 listUser·p0.9999: 17.203 ms/op
                 listUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 243024
  mean =      3.952 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41 
    [ 2.500,  5.000) = 236628 
    [ 5.000,  7.500) = 4713 
    [ 7.500, 10.000) = 973 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 212 
    [15.000, 17.500) = 156 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     15.466 ms/op
     p(99.9900) =     23.976 ms/op
     p(99.9990) =     24.936 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.427 ± 4.698  ops/ms
ClientPb.existUser                       thrpt       3   9.813 ± 3.565  ops/ms
ClientPb.getUser                         thrpt       3   9.226 ± 3.726  ops/ms
ClientPb.listUser                        thrpt       3   7.989 ± 2.623  ops/ms
ClientPb.createUser                       avgt       3   3.348 ± 0.818   ms/op
ClientPb.existUser                        avgt       3   3.313 ± 0.352   ms/op
ClientPb.getUser                          avgt       3   3.466 ± 1.886   ms/op
ClientPb.listUser                         avgt       3   3.991 ± 0.915   ms/op
ClientPb.createUser                     sample  276231   3.473 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.130           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.338           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.022           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.276           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.013           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.538           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.099           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.901           ms/op
ClientPb.existUser                      sample  291096   3.296 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.192           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.191           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.895           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.972           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.385           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.131           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.264           ms/op
ClientPb.getUser                        sample  277845   3.454 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.190           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.342           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.431           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.974           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.780           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.280           ms/op
ClientPb.listUser                       sample  243024   3.952 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.167           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.219           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.906           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.466           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.976           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.199           ms/op
