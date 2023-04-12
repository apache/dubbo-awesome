# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.545 ops/ms
# Warmup Iteration   2: 6.443 ops/ms
# Warmup Iteration   3: 9.146 ops/ms
Iteration   1: 9.055 ops/ms
Iteration   2: 9.843 ops/ms
Iteration   3: 10.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.688 ±(99.9%) 10.426 ops/ms [Average]
  (min, avg, max) = (9.055, 9.688, 10.166), stdev = 0.571
  CI (99.9%): [≈ 0, 20.113] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.539 ops/ms
# Warmup Iteration   2: 9.264 ops/ms
# Warmup Iteration   3: 9.915 ops/ms
Iteration   1: 10.444 ops/ms
Iteration   2: 10.136 ops/ms
Iteration   3: 10.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.344 ±(99.9%) 3.301 ops/ms [Average]
  (min, avg, max) = (10.136, 10.344, 10.454), stdev = 0.181
  CI (99.9%): [7.043, 13.645] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.457 ops/ms
# Warmup Iteration   2: 9.091 ops/ms
# Warmup Iteration   3: 9.944 ops/ms
Iteration   1: 10.162 ops/ms
Iteration   2: 9.933 ops/ms
Iteration   3: 10.274 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.123 ±(99.9%) 3.168 ops/ms [Average]
  (min, avg, max) = (9.933, 10.123, 10.274), stdev = 0.174
  CI (99.9%): [6.955, 13.291] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.300 ops/ms
# Warmup Iteration   2: 7.483 ops/ms
# Warmup Iteration   3: 7.769 ops/ms
Iteration   1: 8.143 ops/ms
Iteration   2: 8.506 ops/ms
Iteration   3: 8.532 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.394 ±(99.9%) 3.965 ops/ms [Average]
  (min, avg, max) = (8.143, 8.394, 8.532), stdev = 0.217
  CI (99.9%): [4.428, 12.359] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.443 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.511 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.320 ±(99.9%) 0.005 ms/op
Iteration   1: 3.249 ±(99.9%) 0.006 ms/op
Iteration   2: 3.208 ±(99.9%) 0.004 ms/op
Iteration   3: 3.095 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.184 ±(99.9%) 1.456 ms/op [Average]
  (min, avg, max) = (3.095, 3.184, 3.249), stdev = 0.080
  CI (99.9%): [1.727, 4.640] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.000 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.429 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.007 ms/op
Iteration   1: 3.088 ±(99.9%) 0.007 ms/op
Iteration   2: 3.110 ±(99.9%) 0.004 ms/op
Iteration   3: 3.120 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.106 ±(99.9%) 0.300 ms/op [Average]
  (min, avg, max) = (3.088, 3.106, 3.120), stdev = 0.016
  CI (99.9%): [2.805, 3.406] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.447 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.397 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.330 ±(99.9%) 0.003 ms/op
Iteration   1: 3.350 ±(99.9%) 0.005 ms/op
Iteration   2: 3.144 ±(99.9%) 0.003 ms/op
Iteration   3: 3.140 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.212 ±(99.9%) 2.191 ms/op [Average]
  (min, avg, max) = (3.140, 3.212, 3.350), stdev = 0.120
  CI (99.9%): [1.021, 5.403] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.283 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.898 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.951 ±(99.9%) 0.003 ms/op
Iteration   1: 3.691 ±(99.9%) 0.008 ms/op
Iteration   2: 3.798 ±(99.9%) 0.005 ms/op
Iteration   3: 3.796 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.762 ±(99.9%) 1.113 ms/op [Average]
  (min, avg, max) = (3.691, 3.762, 3.798), stdev = 0.061
  CI (99.9%): [2.648, 4.875] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 6.993 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.702 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.232 ±(99.9%) 0.009 ms/op
Iteration   1: 3.248 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.687 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   5.947 ms/op
                 createUser·p0.999:  11.902 ms/op
                 createUser·p0.9999: 26.959 ms/op
                 createUser·p1.00:   27.558 ms/op

Iteration   2: 3.445 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.520 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   4.055 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  18.132 ms/op
                 createUser·p0.9999: 24.141 ms/op
                 createUser·p1.00:   24.642 ms/op

Iteration   3: 3.172 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.524 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   5.669 ms/op
                 createUser·p0.999:  12.091 ms/op
                 createUser·p0.9999: 19.262 ms/op
                 createUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 292172
  mean =      3.284 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13993 
    [ 2.500,  5.000) = 271570 
    [ 5.000,  7.500) = 5642 
    [ 7.500, 10.000) = 589 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.520 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     14.778 ms/op
     p(99.9900) =     25.388 ms/op
     p(99.9990) =     27.399 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.417 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.337 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.205 ±(99.9%) 0.009 ms/op
Iteration   1: 3.106 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.906 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.755 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  12.750 ms/op
                 existUser·p0.9999: 19.323 ms/op
                 existUser·p1.00:   19.988 ms/op

Iteration   2: 3.139 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.741 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   5.112 ms/op
                 existUser·p0.999:  14.533 ms/op
                 existUser·p0.9999: 21.587 ms/op
                 existUser·p1.00:   22.118 ms/op

Iteration   3: 3.100 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.232 ms/op
                 existUser·p0.95:   3.330 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  14.497 ms/op
                 existUser·p0.9999: 21.520 ms/op
                 existUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308169
  mean =      3.115 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29502 
    [ 2.500,  5.000) = 274204 
    [ 5.000,  7.500) = 3654 
    [ 7.500, 10.000) = 308 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 134 
    [20.000, 22.500) = 128 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.322 ms/op
     p(95.0000) =      3.572 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =     14.516 ms/op
     p(99.9900) =     21.344 ms/op
     p(99.9990) =     22.083 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.613 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.551 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.380 ±(99.9%) 0.010 ms/op
Iteration   1: 3.205 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.341 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   6.267 ms/op
                 getUser·p0.999:  20.262 ms/op
                 getUser·p0.9999: 33.882 ms/op
                 getUser·p1.00:   34.079 ms/op

Iteration   2: 3.281 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.545 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   5.497 ms/op
                 getUser·p0.999:  13.746 ms/op
                 getUser·p0.9999: 26.640 ms/op
                 getUser·p1.00:   28.312 ms/op

Iteration   3: 3.214 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.243 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   6.065 ms/op
                 getUser·p0.999:  16.098 ms/op
                 getUser·p0.9999: 22.186 ms/op
                 getUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296759
  mean =      3.233 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12013 
    [ 2.500,  5.000) = 277702 
    [ 5.000,  7.500) = 5831 
    [ 7.500, 10.000) = 629 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.545 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =     18.350 ms/op
     p(99.9900) =     32.866 ms/op
     p(99.9990) =     34.079 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.142 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.164 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.979 ±(99.9%) 0.013 ms/op
Iteration   1: 3.741 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.109 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  17.662 ms/op
                 listUser·p0.9999: 20.775 ms/op
                 listUser·p1.00:   22.118 ms/op

Iteration   2: 3.714 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   3.785 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  13.402 ms/op
                 listUser·p0.9999: 16.217 ms/op
                 listUser·p1.00:   17.170 ms/op

Iteration   3: 3.727 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.939 ms/op
                 listUser·p0.50:   3.559 ms/op
                 listUser·p0.90:   4.145 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  14.044 ms/op
                 listUser·p0.9999: 16.105 ms/op
                 listUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257529
  mean =      3.727 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 63 
    [ 2.500,  5.000) = 249747 
    [ 5.000,  7.500) = 6053 
    [ 7.500, 10.000) = 926 
    [10.000, 12.500) = 220 
    [12.500, 15.000) = 329 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.939 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     13.983 ms/op
     p(99.9900) =     19.825 ms/op
     p(99.9990) =     21.442 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   9.688 ± 10.426  ops/ms
ClientPb.existUser                       thrpt       3  10.344 ±  3.301  ops/ms
ClientPb.getUser                         thrpt       3  10.123 ±  3.168  ops/ms
ClientPb.listUser                        thrpt       3   8.394 ±  3.965  ops/ms
ClientPb.createUser                       avgt       3   3.184 ±  1.456   ms/op
ClientPb.existUser                        avgt       3   3.106 ±  0.300   ms/op
ClientPb.getUser                          avgt       3   3.212 ±  2.191   ms/op
ClientPb.listUser                         avgt       3   3.762 ±  1.113   ms/op
ClientPb.createUser                     sample  292172   3.284 ±  0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.520            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.154            ms/op
ClientPb.createUser:createUser·p0.90    sample           3.895            ms/op
ClientPb.createUser:createUser·p0.95    sample           4.174            ms/op
ClientPb.createUser:createUser·p0.99    sample           5.685            ms/op
ClientPb.createUser:createUser·p0.999   sample          14.778            ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.388            ms/op
ClientPb.createUser:createUser·p1.00    sample          27.558            ms/op
ClientPb.existUser                      sample  308169   3.115 ±  0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.741            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.117            ms/op
ClientPb.existUser:existUser·p0.90      sample           3.322            ms/op
ClientPb.existUser:existUser·p0.95      sample           3.572            ms/op
ClientPb.existUser:existUser·p0.99      sample           5.284            ms/op
ClientPb.existUser:existUser·p0.999     sample          14.516            ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.344            ms/op
ClientPb.existUser:existUser·p1.00      sample          22.151            ms/op
ClientPb.getUser                        sample  296759   3.233 ±  0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.545            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.121            ms/op
ClientPb.getUser:getUser·p0.90          sample           3.592            ms/op
ClientPb.getUser:getUser·p0.95          sample           3.932            ms/op
ClientPb.getUser:getUser·p0.99          sample           5.980            ms/op
ClientPb.getUser:getUser·p0.999         sample          18.350            ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.866            ms/op
ClientPb.getUser:getUser·p1.00          sample          34.079            ms/op
ClientPb.listUser                       sample  257529   3.727 ±  0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.939            ms/op
ClientPb.listUser:listUser·p0.50        sample           3.650            ms/op
ClientPb.listUser:listUser·p0.90        sample           4.006            ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440            ms/op
ClientPb.listUser:listUser·p0.99        sample           6.742            ms/op
ClientPb.listUser:listUser·p0.999       sample          13.983            ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.825            ms/op
ClientPb.listUser:listUser·p1.00        sample          22.118            ms/op
