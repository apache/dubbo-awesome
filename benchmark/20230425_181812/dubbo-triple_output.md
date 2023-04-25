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
# Warmup Iteration   1: 2.272 ops/ms
# Warmup Iteration   2: 5.791 ops/ms
# Warmup Iteration   3: 8.742 ops/ms
Iteration   1: 9.184 ops/ms
Iteration   2: 9.586 ops/ms
Iteration   3: 9.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.530 ±(99.9%) 5.866 ops/ms [Average]
  (min, avg, max) = (9.184, 9.530, 9.819), stdev = 0.322
  CI (99.9%): [3.663, 15.396] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.893 ops/ms
# Warmup Iteration   2: 8.787 ops/ms
# Warmup Iteration   3: 9.829 ops/ms
Iteration   1: 9.850 ops/ms
Iteration   2: 9.835 ops/ms
Iteration   3: 10.249 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.978 ±(99.9%) 4.281 ops/ms [Average]
  (min, avg, max) = (9.835, 9.978, 10.249), stdev = 0.235
  CI (99.9%): [5.697, 14.259] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.851 ops/ms
# Warmup Iteration   2: 8.086 ops/ms
# Warmup Iteration   3: 9.085 ops/ms
Iteration   1: 9.342 ops/ms
Iteration   2: 9.556 ops/ms
Iteration   3: 9.794 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.564 ±(99.9%) 4.129 ops/ms [Average]
  (min, avg, max) = (9.342, 9.564, 9.794), stdev = 0.226
  CI (99.9%): [5.435, 13.694] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.315 ops/ms
# Warmup Iteration   2: 7.394 ops/ms
# Warmup Iteration   3: 8.098 ops/ms
Iteration   1: 8.183 ops/ms
Iteration   2: 7.993 ops/ms
Iteration   3: 8.035 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.071 ±(99.9%) 1.817 ops/ms [Average]
  (min, avg, max) = (7.993, 8.071, 8.183), stdev = 0.100
  CI (99.9%): [6.253, 9.888] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.982 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.806 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.622 ±(99.9%) 0.010 ms/op
Iteration   1: 3.428 ±(99.9%) 0.003 ms/op
Iteration   2: 3.311 ±(99.9%) 0.014 ms/op
Iteration   3: 3.294 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.344 ±(99.9%) 1.329 ms/op [Average]
  (min, avg, max) = (3.294, 3.344, 3.428), stdev = 0.073
  CI (99.9%): [2.015, 4.674] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.155 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.374 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.177 ±(99.9%) 0.005 ms/op
Iteration   1: 3.237 ±(99.9%) 0.005 ms/op
Iteration   2: 3.270 ±(99.9%) 0.009 ms/op
Iteration   3: 3.184 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.230 ±(99.9%) 0.788 ms/op [Average]
  (min, avg, max) = (3.184, 3.230, 3.270), stdev = 0.043
  CI (99.9%): [2.443, 4.018] (assumes normal distribution)


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
# Warmup Iteration   1: 8.379 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.586 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.554 ±(99.9%) 0.007 ms/op
Iteration   1: 3.307 ±(99.9%) 0.004 ms/op
Iteration   2: 3.322 ±(99.9%) 0.003 ms/op
Iteration   3: 3.291 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.306 ±(99.9%) 0.285 ms/op [Average]
  (min, avg, max) = (3.291, 3.306, 3.322), stdev = 0.016
  CI (99.9%): [3.021, 3.591] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.771 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.258 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.971 ±(99.9%) 0.007 ms/op
Iteration   1: 3.939 ±(99.9%) 0.005 ms/op
Iteration   2: 3.889 ±(99.9%) 0.009 ms/op
Iteration   3: 3.876 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.901 ±(99.9%) 0.606 ms/op [Average]
  (min, avg, max) = (3.876, 3.901, 3.939), stdev = 0.033
  CI (99.9%): [3.296, 4.507] (assumes normal distribution)


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
# Warmup Iteration   1: 9.218 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.875 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.365 ±(99.9%) 0.009 ms/op
Iteration   1: 3.410 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.296 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  19.104 ms/op
                 createUser·p0.9999: 22.568 ms/op
                 createUser·p1.00:   23.396 ms/op

Iteration   2: 3.384 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.992 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   5.939 ms/op
                 createUser·p0.999:  21.679 ms/op
                 createUser·p0.9999: 26.331 ms/op
                 createUser·p1.00:   26.608 ms/op

Iteration   3: 3.500 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.546 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.555 ms/op
                 createUser·p0.99:   6.726 ms/op
                 createUser·p0.999:  19.857 ms/op
                 createUser·p0.9999: 24.407 ms/op
                 createUser·p1.00:   25.002 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279743
  mean =      3.430 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10676 
    [ 2.500,  5.000) = 260032 
    [ 5.000,  7.500) = 7879 
    [ 7.500, 10.000) = 700 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.931 ms/op
     p(99.9000) =     19.473 ms/op
     p(99.9900) =     24.937 ms/op
     p(99.9990) =     26.509 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.510 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.500 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.227 ±(99.9%) 0.007 ms/op
Iteration   1: 3.286 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.110 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   4.129 ms/op
                 existUser·p0.99:   6.324 ms/op
                 existUser·p0.999:  12.585 ms/op
                 existUser·p0.9999: 28.198 ms/op
                 existUser·p1.00:   30.376 ms/op

Iteration   2: 3.274 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.927 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  13.650 ms/op
                 existUser·p0.9999: 25.173 ms/op
                 existUser·p1.00:   26.083 ms/op

Iteration   3: 3.220 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.679 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   6.226 ms/op
                 existUser·p0.999:  13.255 ms/op
                 existUser·p0.9999: 30.386 ms/op
                 existUser·p1.00:   33.096 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294396
  mean =      3.260 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8062 
    [ 2.500,  5.000) = 279174 
    [ 5.000,  7.500) = 6228 
    [ 7.500, 10.000) = 464 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 130 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.927 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      6.119 ms/op
     p(99.9000) =     13.287 ms/op
     p(99.9900) =     29.411 ms/op
     p(99.9990) =     31.121 ms/op
     p(99.9999) =     33.096 ms/op
    p(100.0000) =     33.096 ms/op


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
# Warmup Iteration   1: 9.625 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.774 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.377 ±(99.9%) 0.010 ms/op
Iteration   1: 3.322 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.241 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   6.340 ms/op
                 getUser·p0.999:  20.467 ms/op
                 getUser·p0.9999: 28.967 ms/op
                 getUser·p1.00:   29.000 ms/op

Iteration   2: 3.327 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.874 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   6.242 ms/op
                 getUser·p0.999:  19.985 ms/op
                 getUser·p0.9999: 27.210 ms/op
                 getUser·p1.00:   28.672 ms/op

Iteration   3: 3.289 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.446 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   5.677 ms/op
                 getUser·p0.999:  15.368 ms/op
                 getUser·p0.9999: 24.299 ms/op
                 getUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 289803
  mean =      3.313 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14583 
    [ 2.500,  5.000) = 267498 
    [ 5.000,  7.500) = 6452 
    [ 7.500, 10.000) = 823 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 128 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.241 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =     17.746 ms/op
     p(99.9900) =     28.214 ms/op
     p(99.9990) =     29.000 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


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
# Warmup Iteration   1: 10.658 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.358 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.076 ±(99.9%) 0.013 ms/op
Iteration   1: 4.054 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.083 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   7.397 ms/op
                 listUser·p0.999:  18.514 ms/op
                 listUser·p0.9999: 23.040 ms/op
                 listUser·p1.00:   24.052 ms/op

Iteration   2: 3.855 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.982 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   6.928 ms/op
                 listUser·p0.999:  15.319 ms/op
                 listUser·p0.9999: 23.429 ms/op
                 listUser·p1.00:   27.918 ms/op

Iteration   3: 3.984 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  15.974 ms/op
                 listUser·p0.9999: 19.661 ms/op
                 listUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242033
  mean =      3.963 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 64 
    [ 2.500,  5.000) = 234157 
    [ 5.000,  7.500) = 5768 
    [ 7.500, 10.000) = 1222 
    [10.000, 12.500) = 241 
    [12.500, 15.000) = 227 
    [15.000, 17.500) = 182 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     15.925 ms/op
     p(99.9900) =     22.892 ms/op
     p(99.9990) =     24.508 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.530 ± 5.866  ops/ms
ClientPb.existUser                       thrpt       3   9.978 ± 4.281  ops/ms
ClientPb.getUser                         thrpt       3   9.564 ± 4.129  ops/ms
ClientPb.listUser                        thrpt       3   8.071 ± 1.817  ops/ms
ClientPb.createUser                       avgt       3   3.344 ± 1.329   ms/op
ClientPb.existUser                        avgt       3   3.230 ± 0.788   ms/op
ClientPb.getUser                          avgt       3   3.306 ± 0.285   ms/op
ClientPb.listUser                         avgt       3   3.901 ± 0.606   ms/op
ClientPb.createUser                     sample  279743   3.430 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.546           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.305           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.961           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.424           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.931           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.473           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.937           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.608           ms/op
ClientPb.existUser                      sample  294396   3.260 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.927           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.104           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.119           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.287           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.411           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.096           ms/op
ClientPb.getUser                        sample  289803   3.313 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.241           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.699           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.051           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.070           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.746           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.214           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.000           ms/op
ClientPb.listUser                       sample  242033   3.963 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.083           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.217           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.925           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.892           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.918           ms/op
