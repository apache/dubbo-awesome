# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.183 ops/ms
# Warmup Iteration   2: 5.656 ops/ms
# Warmup Iteration   3: 7.382 ops/ms
Iteration   1: 7.714 ops/ms
Iteration   2: 7.840 ops/ms
Iteration   3: 7.716 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.756 ±(99.9%) 1.314 ops/ms [Average]
  (min, avg, max) = (7.714, 7.756, 7.840), stdev = 0.072
  CI (99.9%): [6.442, 9.071] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.378 ops/ms
# Warmup Iteration   2: 7.371 ops/ms
# Warmup Iteration   3: 7.837 ops/ms
Iteration   1: 8.165 ops/ms
Iteration   2: 8.132 ops/ms
Iteration   3: 7.914 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.070 ±(99.9%) 2.487 ops/ms [Average]
  (min, avg, max) = (7.914, 8.070, 8.165), stdev = 0.136
  CI (99.9%): [5.583, 10.557] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.117 ops/ms
# Warmup Iteration   2: 6.648 ops/ms
# Warmup Iteration   3: 7.279 ops/ms
Iteration   1: 7.433 ops/ms
Iteration   2: 7.546 ops/ms
Iteration   3: 7.551 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.510 ±(99.9%) 1.215 ops/ms [Average]
  (min, avg, max) = (7.433, 7.510, 7.551), stdev = 0.067
  CI (99.9%): [6.295, 8.725] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.755 ops/ms
# Warmup Iteration   2: 5.679 ops/ms
# Warmup Iteration   3: 6.015 ops/ms
Iteration   1: 5.899 ops/ms
Iteration   2: 6.124 ops/ms
Iteration   3: 5.978 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.000 ±(99.9%) 2.079 ops/ms [Average]
  (min, avg, max) = (5.899, 6.000, 6.124), stdev = 0.114
  CI (99.9%): [3.921, 8.079] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.615 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.372 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.245 ±(99.9%) 0.018 ms/op
Iteration   1: 4.366 ±(99.9%) 0.004 ms/op
Iteration   2: 4.172 ±(99.9%) 0.004 ms/op
Iteration   3: 4.290 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.276 ±(99.9%) 1.775 ms/op [Average]
  (min, avg, max) = (4.172, 4.276, 4.366), stdev = 0.097
  CI (99.9%): [2.501, 6.051] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.150 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.518 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.173 ±(99.9%) 0.003 ms/op
Iteration   1: 4.121 ±(99.9%) 0.004 ms/op
Iteration   2: 4.140 ±(99.9%) 0.003 ms/op
Iteration   3: 4.000 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.087 ±(99.9%) 1.382 ms/op [Average]
  (min, avg, max) = (4.000, 4.087, 4.140), stdev = 0.076
  CI (99.9%): [2.705, 5.469] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.197 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.548 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.434 ±(99.9%) 0.004 ms/op
Iteration   1: 4.387 ±(99.9%) 0.002 ms/op
Iteration   2: 4.339 ±(99.9%) 0.007 ms/op
Iteration   3: 4.321 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.349 ±(99.9%) 0.626 ms/op [Average]
  (min, avg, max) = (4.321, 4.349, 4.387), stdev = 0.034
  CI (99.9%): [3.723, 4.975] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.493 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 5.730 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.364 ±(99.9%) 0.006 ms/op
Iteration   1: 5.278 ±(99.9%) 0.019 ms/op
Iteration   2: 4.986 ±(99.9%) 0.012 ms/op
Iteration   3: 5.086 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.117 ±(99.9%) 2.710 ms/op [Average]
  (min, avg, max) = (4.986, 5.117, 5.278), stdev = 0.149
  CI (99.9%): [2.407, 7.827] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.611 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.525 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.397 ±(99.9%) 0.014 ms/op
Iteration   1: 4.358 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.992 ms/op
                 createUser·p0.50:   4.211 ms/op
                 createUser·p0.90:   5.579 ms/op
                 createUser·p0.95:   6.128 ms/op
                 createUser·p0.99:   8.012 ms/op
                 createUser·p0.999:  12.320 ms/op
                 createUser·p0.9999: 17.836 ms/op
                 createUser·p1.00:   18.383 ms/op

Iteration   2: 4.284 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.424 ms/op
                 createUser·p0.50:   4.149 ms/op
                 createUser·p0.90:   5.431 ms/op
                 createUser·p0.95:   5.923 ms/op
                 createUser·p0.99:   7.651 ms/op
                 createUser·p0.999:  11.851 ms/op
                 createUser·p0.9999: 22.252 ms/op
                 createUser·p1.00:   22.872 ms/op

Iteration   3: 4.335 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.110 ms/op
                 createUser·p0.50:   4.227 ms/op
                 createUser·p0.90:   5.521 ms/op
                 createUser·p0.95:   5.972 ms/op
                 createUser·p0.99:   8.074 ms/op
                 createUser·p0.999:  12.487 ms/op
                 createUser·p0.9999: 23.711 ms/op
                 createUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 222006
  mean =      4.325 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5147 
    [ 2.500,  5.000) = 170602 
    [ 5.000,  7.500) = 43295 
    [ 7.500, 10.000) = 2333 
    [10.000, 12.500) = 429 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.424 ms/op
     p(50.0000) =      4.194 ms/op
     p(90.0000) =      5.513 ms/op
     p(95.0000) =      6.013 ms/op
     p(99.0000) =      7.922 ms/op
     p(99.9000) =     12.288 ms/op
     p(99.9900) =     23.200 ms/op
     p(99.9990) =     23.997 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.280 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.298 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.116 ±(99.9%) 0.012 ms/op
Iteration   1: 4.145 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.854 ms/op
                 existUser·p0.50:   4.051 ms/op
                 existUser·p0.90:   5.194 ms/op
                 existUser·p0.95:   5.587 ms/op
                 existUser·p0.99:   7.504 ms/op
                 existUser·p0.999:  17.589 ms/op
                 existUser·p0.9999: 31.255 ms/op
                 existUser·p1.00:   31.818 ms/op

Iteration   2: 3.983 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   3.867 ms/op
                 existUser·p0.90:   5.005 ms/op
                 existUser·p0.95:   5.464 ms/op
                 existUser·p0.99:   7.217 ms/op
                 existUser·p0.999:  13.550 ms/op
                 existUser·p0.9999: 20.608 ms/op
                 existUser·p1.00:   21.332 ms/op

Iteration   3: 4.000 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.382 ms/op
                 existUser·p0.50:   3.916 ms/op
                 existUser·p0.90:   5.038 ms/op
                 existUser·p0.95:   5.448 ms/op
                 existUser·p0.99:   7.266 ms/op
                 existUser·p0.999:  15.896 ms/op
                 existUser·p0.9999: 27.689 ms/op
                 existUser·p1.00:   28.475 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 237536
  mean =      4.041 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7688 
    [ 2.500,  5.000) = 202335 
    [ 5.000,  7.500) = 25314 
    [ 7.500, 10.000) = 1454 
    [10.000, 12.500) = 257 
    [12.500, 15.000) = 248 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.382 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     15.048 ms/op
     p(99.9900) =     29.810 ms/op
     p(99.9990) =     31.748 ms/op
     p(99.9999) =     31.818 ms/op
    p(100.0000) =     31.818 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.987 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 4.694 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.437 ±(99.9%) 0.013 ms/op
Iteration   1: 4.382 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.057 ms/op
                 getUser·p0.50:   4.268 ms/op
                 getUser·p0.90:   5.595 ms/op
                 getUser·p0.95:   6.005 ms/op
                 getUser·p0.99:   7.980 ms/op
                 getUser·p0.999:  15.483 ms/op
                 getUser·p0.9999: 21.859 ms/op
                 getUser·p1.00:   22.479 ms/op

Iteration   2: 4.326 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.180 ms/op
                 getUser·p0.50:   4.202 ms/op
                 getUser·p0.90:   5.407 ms/op
                 getUser·p0.95:   5.915 ms/op
                 getUser·p0.99:   8.438 ms/op
                 getUser·p0.999:  12.879 ms/op
                 getUser·p0.9999: 17.984 ms/op
                 getUser·p1.00:   18.481 ms/op

Iteration   3: 4.239 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.971 ms/op
                 getUser·p0.50:   4.121 ms/op
                 getUser·p0.90:   5.399 ms/op
                 getUser·p0.95:   5.833 ms/op
                 getUser·p0.99:   7.332 ms/op
                 getUser·p0.999:  10.968 ms/op
                 getUser·p0.9999: 24.492 ms/op
                 getUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 222562
  mean =      4.315 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5371 
    [ 2.500,  5.000) = 171883 
    [ 5.000,  7.500) = 42528 
    [ 7.500, 10.000) = 2069 
    [10.000, 12.500) = 386 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.971 ms/op
     p(50.0000) =      4.194 ms/op
     p(90.0000) =      5.480 ms/op
     p(95.0000) =      5.915 ms/op
     p(99.0000) =      7.881 ms/op
     p(99.9000) =     14.063 ms/op
     p(99.9900) =     22.445 ms/op
     p(99.9990) =     24.677 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.240 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 5.947 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.490 ±(99.9%) 0.020 ms/op
Iteration   1: 5.430 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.092 ms/op
                 listUser·p0.50:   5.104 ms/op
                 listUser·p0.90:   7.291 ms/op
                 listUser·p0.95:   8.176 ms/op
                 listUser·p0.99:   10.584 ms/op
                 listUser·p0.999:  18.484 ms/op
                 listUser·p0.9999: 22.616 ms/op
                 listUser·p1.00:   23.364 ms/op

Iteration   2: 5.537 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.200 ms/op
                 listUser·p0.50:   5.194 ms/op
                 listUser·p0.90:   7.406 ms/op
                 listUser·p0.95:   8.249 ms/op
                 listUser·p0.99:   10.961 ms/op
                 listUser·p0.999:  17.531 ms/op
                 listUser·p0.9999: 23.735 ms/op
                 listUser·p1.00:   24.183 ms/op

Iteration   3: 5.245 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.464 ms/op
                 listUser·p0.50:   4.981 ms/op
                 listUser·p0.90:   6.742 ms/op
                 listUser·p0.95:   7.832 ms/op
                 listUser·p0.99:   10.224 ms/op
                 listUser·p0.999:  29.528 ms/op
                 listUser·p0.9999: 38.713 ms/op
                 listUser·p1.00:   39.125 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 177603
  mean =      5.401 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 212 
    [ 2.500,  5.000) = 81942 
    [ 5.000,  7.500) = 81181 
    [ 7.500, 10.000) = 11737 
    [10.000, 12.500) = 1817 
    [12.500, 15.000) = 311 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      5.087 ms/op
     p(90.0000) =      7.201 ms/op
     p(95.0000) =      8.086 ms/op
     p(99.0000) =     10.600 ms/op
     p(99.9000) =     20.100 ms/op
     p(99.9900) =     31.751 ms/op
     p(99.9990) =     39.125 ms/op
     p(99.9999) =     39.125 ms/op
    p(100.0000) =     39.125 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.756 ± 1.314  ops/ms
ClientGrpc.existUser                       thrpt       3   8.070 ± 2.487  ops/ms
ClientGrpc.getUser                         thrpt       3   7.510 ± 1.215  ops/ms
ClientGrpc.listUser                        thrpt       3   6.000 ± 2.079  ops/ms
ClientGrpc.createUser                       avgt       3   4.276 ± 1.775   ms/op
ClientGrpc.existUser                        avgt       3   4.087 ± 1.382   ms/op
ClientGrpc.getUser                          avgt       3   4.349 ± 0.626   ms/op
ClientGrpc.listUser                         avgt       3   5.117 ± 2.710   ms/op
ClientGrpc.createUser                     sample  222006   4.325 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.424           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.194           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.513           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.013           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.922           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.288           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.200           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.019           ms/op
ClientGrpc.existUser                      sample  237536   4.041 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.382           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.940           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.087           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.505           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.348           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          15.048           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          29.810           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          31.818           ms/op
ClientGrpc.getUser                        sample  222562   4.315 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.971           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.194           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.480           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.915           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.881           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.063           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.445           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.838           ms/op
ClientGrpc.listUser                       sample  177603   5.401 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.092           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.201           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.086           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.600           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.100           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.751           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          39.125           ms/op
