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
# Warmup Iteration   1: 2.286 ops/ms
# Warmup Iteration   2: 5.735 ops/ms
# Warmup Iteration   3: 8.458 ops/ms
Iteration   1: 8.882 ops/ms
Iteration   2: 9.210 ops/ms
Iteration   3: 9.269 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.120 ±(99.9%) 3.803 ops/ms [Average]
  (min, avg, max) = (8.882, 9.120, 9.269), stdev = 0.208
  CI (99.9%): [5.317, 12.924] (assumes normal distribution)


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
# Warmup Iteration   1: 3.397 ops/ms
# Warmup Iteration   2: 8.807 ops/ms
# Warmup Iteration   3: 9.456 ops/ms
Iteration   1: 9.455 ops/ms
Iteration   2: 9.799 ops/ms
Iteration   3: 9.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.604 ±(99.9%) 3.216 ops/ms [Average]
  (min, avg, max) = (9.455, 9.604, 9.799), stdev = 0.176
  CI (99.9%): [6.388, 12.820] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.101 ops/ms
# Warmup Iteration   2: 8.168 ops/ms
# Warmup Iteration   3: 8.959 ops/ms
Iteration   1: 9.501 ops/ms
Iteration   2: 9.444 ops/ms
Iteration   3: 9.119 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.355 ±(99.9%) 3.766 ops/ms [Average]
  (min, avg, max) = (9.119, 9.355, 9.501), stdev = 0.206
  CI (99.9%): [5.589, 13.120] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.813 ops/ms
# Warmup Iteration   2: 7.002 ops/ms
# Warmup Iteration   3: 7.775 ops/ms
Iteration   1: 7.723 ops/ms
Iteration   2: 8.033 ops/ms
Iteration   3: 8.036 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.931 ±(99.9%) 3.276 ops/ms [Average]
  (min, avg, max) = (7.723, 7.931, 8.036), stdev = 0.180
  CI (99.9%): [4.654, 11.207] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.673 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.845 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.596 ±(99.9%) 0.004 ms/op
Iteration   1: 3.483 ±(99.9%) 0.007 ms/op
Iteration   2: 3.511 ±(99.9%) 0.006 ms/op
Iteration   3: 3.443 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.479 ±(99.9%) 0.628 ms/op [Average]
  (min, avg, max) = (3.443, 3.479, 3.511), stdev = 0.034
  CI (99.9%): [2.851, 4.107] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.311 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.647 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.267 ±(99.9%) 0.008 ms/op
Iteration   1: 3.282 ±(99.9%) 0.004 ms/op
Iteration   2: 3.359 ±(99.9%) 0.005 ms/op
Iteration   3: 3.444 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.362 ±(99.9%) 1.474 ms/op [Average]
  (min, avg, max) = (3.282, 3.362, 3.444), stdev = 0.081
  CI (99.9%): [1.887, 4.836] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.017 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.781 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.592 ±(99.9%) 0.005 ms/op
Iteration   1: 3.372 ±(99.9%) 0.003 ms/op
Iteration   2: 3.359 ±(99.9%) 0.007 ms/op
Iteration   3: 3.458 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.396 ±(99.9%) 0.987 ms/op [Average]
  (min, avg, max) = (3.359, 3.396, 3.458), stdev = 0.054
  CI (99.9%): [2.410, 4.383] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.575 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.312 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.121 ±(99.9%) 0.006 ms/op
Iteration   1: 4.048 ±(99.9%) 0.007 ms/op
Iteration   2: 4.097 ±(99.9%) 0.007 ms/op
Iteration   3: 4.030 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.058 ±(99.9%) 0.633 ms/op [Average]
  (min, avg, max) = (4.030, 4.058, 4.097), stdev = 0.035
  CI (99.9%): [3.426, 4.691] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.239 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.212 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.661 ±(99.9%) 0.012 ms/op
Iteration   1: 3.864 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.577 ms/op
                 createUser·p0.50:   3.535 ms/op
                 createUser·p0.90:   5.128 ms/op
                 createUser·p0.95:   6.078 ms/op
                 createUser·p0.99:   7.828 ms/op
                 createUser·p0.999:  12.698 ms/op
                 createUser·p0.9999: 29.104 ms/op
                 createUser·p1.00:   31.195 ms/op

Iteration   2: 3.467 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.524 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.170 ms/op
                 createUser·p0.99:   6.038 ms/op
                 createUser·p0.999:  21.062 ms/op
                 createUser·p0.9999: 27.161 ms/op
                 createUser·p1.00:   28.246 ms/op

Iteration   3: 3.422 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   5.841 ms/op
                 createUser·p0.999:  20.163 ms/op
                 createUser·p0.9999: 28.431 ms/op
                 createUser·p1.00:   29.131 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 268391
  mean =      3.574 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3996 
    [ 2.500,  5.000) = 252052 
    [ 5.000,  7.500) = 9936 
    [ 7.500, 10.000) = 1813 
    [10.000, 12.500) = 281 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 84 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      7.381 ms/op
     p(99.9000) =     15.896 ms/op
     p(99.9900) =     28.251 ms/op
     p(99.9990) =     29.446 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


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
# Warmup Iteration   1: 9.548 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.631 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.357 ±(99.9%) 0.009 ms/op
Iteration   1: 3.288 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.055 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   6.144 ms/op
                 existUser·p0.999:  10.600 ms/op
                 existUser·p0.9999: 22.151 ms/op
                 existUser·p1.00:   22.544 ms/op

Iteration   2: 3.286 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.010 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   6.406 ms/op
                 existUser·p0.999:  12.342 ms/op
                 existUser·p0.9999: 36.897 ms/op
                 existUser·p1.00:   37.814 ms/op

Iteration   3: 3.366 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.354 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   6.177 ms/op
                 existUser·p0.999:  12.763 ms/op
                 existUser·p0.9999: 23.642 ms/op
                 existUser·p1.00:   24.412 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289449
  mean =      3.313 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4279 
    [ 2.500,  5.000) = 279029 
    [ 5.000,  7.500) = 4767 
    [ 7.500, 10.000) = 966 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.010 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      6.189 ms/op
     p(99.9000) =     12.763 ms/op
     p(99.9900) =     35.065 ms/op
     p(99.9990) =     37.259 ms/op
     p(99.9999) =     37.814 ms/op
    p(100.0000) =     37.814 ms/op


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
# Warmup Iteration   1: 10.409 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.801 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.612 ±(99.9%) 0.012 ms/op
Iteration   1: 3.517 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.573 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.932 ms/op
                 getUser·p0.95:   4.899 ms/op
                 getUser·p0.99:   7.176 ms/op
                 getUser·p0.999:  20.630 ms/op
                 getUser·p0.9999: 23.027 ms/op
                 getUser·p1.00:   24.510 ms/op

Iteration   2: 3.508 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.454 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   6.005 ms/op
                 getUser·p0.999:  21.332 ms/op
                 getUser·p0.9999: 25.846 ms/op
                 getUser·p1.00:   26.280 ms/op

Iteration   3: 3.561 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.210 ms/op
                 getUser·p0.50:   3.441 ms/op
                 getUser·p0.90:   4.006 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   6.062 ms/op
                 getUser·p0.999:  19.552 ms/op
                 getUser·p0.9999: 26.247 ms/op
                 getUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271993
  mean =      3.529 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8277 
    [ 2.500,  5.000) = 253535 
    [ 5.000,  7.500) = 8513 
    [ 7.500, 10.000) = 1078 
    [10.000, 12.500) = 227 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 126 
    [25.000, 27.500) = 48 

  Percentiles, ms/op:
      p(0.0000) =      1.210 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     19.988 ms/op
     p(99.9900) =     25.749 ms/op
     p(99.9990) =     26.522 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 10.142 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.382 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.149 ±(99.9%) 0.014 ms/op
Iteration   1: 4.107 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.104 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   7.913 ms/op
                 listUser·p0.999:  20.154 ms/op
                 listUser·p0.9999: 25.094 ms/op
                 listUser·p1.00:   25.985 ms/op

Iteration   2: 4.019 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.499 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  15.730 ms/op
                 listUser·p0.9999: 21.168 ms/op
                 listUser·p1.00:   21.266 ms/op

Iteration   3: 4.068 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.626 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   8.503 ms/op
                 listUser·p0.999:  15.227 ms/op
                 listUser·p0.9999: 16.558 ms/op
                 listUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236077
  mean =      4.064 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 226705 
    [ 5.000,  7.500) = 6293 
    [ 7.500, 10.000) = 2054 
    [10.000, 12.500) = 487 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 174 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      8.110 ms/op
     p(99.9000) =     15.925 ms/op
     p(99.9900) =     24.163 ms/op
     p(99.9990) =     25.658 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.120 ± 3.803  ops/ms
ClientPb.existUser                       thrpt       3   9.604 ± 3.216  ops/ms
ClientPb.getUser                         thrpt       3   9.355 ± 3.766  ops/ms
ClientPb.listUser                        thrpt       3   7.931 ± 3.276  ops/ms
ClientPb.createUser                       avgt       3   3.479 ± 0.628   ms/op
ClientPb.existUser                        avgt       3   3.362 ± 1.474   ms/op
ClientPb.getUser                          avgt       3   3.396 ± 0.987   ms/op
ClientPb.listUser                         avgt       3   4.058 ± 0.633   ms/op
ClientPb.createUser                     sample  268391   3.574 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.143           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.400           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.735           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.381           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.896           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.251           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.195           ms/op
ClientPb.existUser                      sample  289449   3.313 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.010           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.191           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.903           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.189           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.763           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.065           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.814           ms/op
ClientPb.getUser                        sample  271993   3.529 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.210           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.383           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.465           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.595           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.988           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.749           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.673           ms/op
ClientPb.listUser                       sample  236077   4.064 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.104           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.751           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.110           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.925           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.163           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.985           ms/op
