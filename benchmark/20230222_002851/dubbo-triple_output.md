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
# Warmup Iteration   1: 2.532 ops/ms
# Warmup Iteration   2: 5.889 ops/ms
# Warmup Iteration   3: 9.218 ops/ms
Iteration   1: 9.473 ops/ms
Iteration   2: 9.950 ops/ms
Iteration   3: 9.388 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.604 ±(99.9%) 5.521 ops/ms [Average]
  (min, avg, max) = (9.388, 9.604, 9.950), stdev = 0.303
  CI (99.9%): [4.083, 15.124] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.467 ops/ms
# Warmup Iteration   2: 8.040 ops/ms
# Warmup Iteration   3: 9.917 ops/ms
Iteration   1: 9.837 ops/ms
Iteration   2: 9.653 ops/ms
Iteration   3: 9.913 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.801 ±(99.9%) 2.440 ops/ms [Average]
  (min, avg, max) = (9.653, 9.801, 9.913), stdev = 0.134
  CI (99.9%): [7.361, 12.241] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.029 ops/ms
# Warmup Iteration   2: 8.632 ops/ms
# Warmup Iteration   3: 9.618 ops/ms
Iteration   1: 10.078 ops/ms
Iteration   2: 10.080 ops/ms
Iteration   3: 10.509 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.222 ±(99.9%) 4.529 ops/ms [Average]
  (min, avg, max) = (10.078, 10.222, 10.509), stdev = 0.248
  CI (99.9%): [5.693, 14.751] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.419 ops/ms
# Warmup Iteration   2: 7.605 ops/ms
# Warmup Iteration   3: 8.439 ops/ms
Iteration   1: 8.673 ops/ms
Iteration   2: 8.525 ops/ms
Iteration   3: 8.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.645 ±(99.9%) 1.983 ops/ms [Average]
  (min, avg, max) = (8.525, 8.645, 8.737), stdev = 0.109
  CI (99.9%): [6.662, 10.628] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.941 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.594 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.003 ms/op
Iteration   1: 3.272 ±(99.9%) 0.006 ms/op
Iteration   2: 3.156 ±(99.9%) 0.003 ms/op
Iteration   3: 3.094 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.174 ±(99.9%) 1.647 ms/op [Average]
  (min, avg, max) = (3.094, 3.174, 3.272), stdev = 0.090
  CI (99.9%): [1.527, 4.822] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.653 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.375 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.202 ±(99.9%) 0.007 ms/op
Iteration   1: 3.223 ±(99.9%) 0.004 ms/op
Iteration   2: 3.019 ±(99.9%) 0.007 ms/op
Iteration   3: 2.997 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.080 ±(99.9%) 2.269 ms/op [Average]
  (min, avg, max) = (2.997, 3.080, 3.223), stdev = 0.124
  CI (99.9%): [0.811, 5.348] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.339 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.505 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.345 ±(99.9%) 0.007 ms/op
Iteration   1: 3.230 ±(99.9%) 0.006 ms/op
Iteration   2: 3.314 ±(99.9%) 0.007 ms/op
Iteration   3: 3.175 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.240 ±(99.9%) 1.274 ms/op [Average]
  (min, avg, max) = (3.175, 3.240, 3.314), stdev = 0.070
  CI (99.9%): [1.966, 4.514] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.961 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.976 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.781 ±(99.9%) 0.005 ms/op
Iteration   1: 3.724 ±(99.9%) 0.004 ms/op
Iteration   2: 3.701 ±(99.9%) 0.008 ms/op
Iteration   3: 3.728 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.718 ±(99.9%) 0.262 ms/op [Average]
  (min, avg, max) = (3.701, 3.718, 3.728), stdev = 0.014
  CI (99.9%): [3.456, 3.979] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.487 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.669 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.301 ±(99.9%) 0.009 ms/op
Iteration   1: 3.273 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.186 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   6.062 ms/op
                 createUser·p0.999:  18.657 ms/op
                 createUser·p0.9999: 24.944 ms/op
                 createUser·p1.00:   26.378 ms/op

Iteration   2: 3.106 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.354 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.712 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  11.551 ms/op
                 createUser·p0.9999: 21.683 ms/op
                 createUser·p1.00:   22.282 ms/op

Iteration   3: 3.119 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.511 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.700 ms/op
                 createUser·p0.999:  15.261 ms/op
                 createUser·p0.9999: 22.045 ms/op
                 createUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303335
  mean =      3.164 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15661 
    [ 2.500,  5.000) = 283011 
    [ 5.000,  7.500) = 3721 
    [ 7.500, 10.000) = 439 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.186 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =     15.871 ms/op
     p(99.9900) =     22.861 ms/op
     p(99.9990) =     25.558 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.615 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.297 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.198 ±(99.9%) 0.008 ms/op
Iteration   1: 3.139 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.133 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  9.147 ms/op
                 existUser·p0.9999: 18.573 ms/op
                 existUser·p1.00:   20.840 ms/op

Iteration   2: 3.010 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.031 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.383 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  10.149 ms/op
                 existUser·p0.9999: 20.840 ms/op
                 existUser·p1.00:   21.561 ms/op

Iteration   3: 3.164 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.458 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  12.269 ms/op
                 existUser·p0.9999: 19.046 ms/op
                 existUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309252
  mean =      3.103 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21126 
    [ 2.500,  5.000) = 283325 
    [ 5.000,  7.500) = 4183 
    [ 7.500, 10.000) = 254 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.031 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.371 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      5.333 ms/op
     p(99.9000) =     12.239 ms/op
     p(99.9900) =     20.021 ms/op
     p(99.9990) =     21.100 ms/op
     p(99.9999) =     21.561 ms/op
    p(100.0000) =     21.561 ms/op


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
# Warmup Iteration   1: 8.292 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.450 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.239 ±(99.9%) 0.009 ms/op
Iteration   1: 3.188 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.350 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   6.406 ms/op
                 getUser·p0.999:  15.815 ms/op
                 getUser·p0.9999: 20.445 ms/op
                 getUser·p1.00:   21.430 ms/op

Iteration   2: 3.130 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.346 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.661 ms/op
                 getUser·p0.999:  14.238 ms/op
                 getUser·p0.9999: 21.594 ms/op
                 getUser·p1.00:   22.446 ms/op

Iteration   3: 3.239 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.323 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   5.571 ms/op
                 getUser·p0.999:  9.774 ms/op
                 getUser·p0.9999: 24.052 ms/op
                 getUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300981
  mean =      3.185 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19011 
    [ 2.500,  5.000) = 276305 
    [ 5.000,  7.500) = 4765 
    [ 7.500, 10.000) = 501 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.323 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     14.258 ms/op
     p(99.9900) =     23.033 ms/op
     p(99.9990) =     24.345 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


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
# Warmup Iteration   1: 9.261 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 4.383 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.929 ±(99.9%) 0.012 ms/op
Iteration   1: 3.772 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.696 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   7.005 ms/op
                 listUser·p0.999:  16.653 ms/op
                 listUser·p0.9999: 26.116 ms/op
                 listUser·p1.00:   26.706 ms/op

Iteration   2: 3.812 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  14.549 ms/op
                 listUser·p0.9999: 17.947 ms/op
                 listUser·p1.00:   18.612 ms/op

Iteration   3: 3.836 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.186 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  13.812 ms/op
                 listUser·p0.9999: 15.958 ms/op
                 listUser·p1.00:   16.187 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252093
  mean =      3.807 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 99 
    [ 2.500,  5.000) = 244337 
    [ 5.000,  7.500) = 5773 
    [ 7.500, 10.000) = 1204 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 297 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.696 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     14.500 ms/op
     p(99.9900) =     24.280 ms/op
     p(99.9990) =     26.518 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.604 ± 5.521  ops/ms
ClientPb.existUser                       thrpt       3   9.801 ± 2.440  ops/ms
ClientPb.getUser                         thrpt       3  10.222 ± 4.529  ops/ms
ClientPb.listUser                        thrpt       3   8.645 ± 1.983  ops/ms
ClientPb.createUser                       avgt       3   3.174 ± 1.647   ms/op
ClientPb.existUser                        avgt       3   3.080 ± 2.269   ms/op
ClientPb.getUser                          avgt       3   3.240 ± 1.274   ms/op
ClientPb.listUser                         avgt       3   3.718 ± 0.262   ms/op
ClientPb.createUser                     sample  303335   3.164 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.186           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.641           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.006           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.423           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.871           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.861           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.378           ms/op
ClientPb.existUser                      sample  309252   3.103 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.031           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.371           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.333           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.239           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.021           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.561           ms/op
ClientPb.getUser                        sample  300981   3.185 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.323           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.580           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.693           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.258           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.033           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.445           ms/op
ClientPb.listUser                       sample  252093   3.807 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.696           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.723           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.121           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.004           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.500           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.280           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.706           ms/op
