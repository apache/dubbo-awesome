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
# Warmup Iteration   1: 2.761 ops/ms
# Warmup Iteration   2: 6.705 ops/ms
# Warmup Iteration   3: 9.644 ops/ms
Iteration   1: 10.372 ops/ms
Iteration   2: 10.165 ops/ms
Iteration   3: 10.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.216 ±(99.9%) 2.503 ops/ms [Average]
  (min, avg, max) = (10.113, 10.216, 10.372), stdev = 0.137
  CI (99.9%): [7.713, 12.719] (assumes normal distribution)


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
# Warmup Iteration   1: 4.014 ops/ms
# Warmup Iteration   2: 9.164 ops/ms
# Warmup Iteration   3: 10.046 ops/ms
Iteration   1: 10.570 ops/ms
Iteration   2: 10.184 ops/ms
Iteration   3: 10.599 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.451 ±(99.9%) 4.220 ops/ms [Average]
  (min, avg, max) = (10.184, 10.451, 10.599), stdev = 0.231
  CI (99.9%): [6.231, 14.671] (assumes normal distribution)


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
# Warmup Iteration   1: 3.651 ops/ms
# Warmup Iteration   2: 9.005 ops/ms
# Warmup Iteration   3: 9.638 ops/ms
Iteration   1: 10.305 ops/ms
Iteration   2: 10.018 ops/ms
Iteration   3: 10.282 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.201 ±(99.9%) 2.913 ops/ms [Average]
  (min, avg, max) = (10.018, 10.201, 10.305), stdev = 0.160
  CI (99.9%): [7.288, 13.115] (assumes normal distribution)


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
# Warmup Iteration   1: 3.260 ops/ms
# Warmup Iteration   2: 7.869 ops/ms
# Warmup Iteration   3: 8.520 ops/ms
Iteration   1: 8.495 ops/ms
Iteration   2: 8.559 ops/ms
Iteration   3: 8.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.572 ±(99.9%) 1.540 ops/ms [Average]
  (min, avg, max) = (8.495, 8.572, 8.662), stdev = 0.084
  CI (99.9%): [7.032, 10.112] (assumes normal distribution)


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
# Warmup Iteration   1: 8.347 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.500 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.358 ±(99.9%) 0.003 ms/op
Iteration   1: 3.232 ±(99.9%) 0.003 ms/op
Iteration   2: 3.213 ±(99.9%) 0.005 ms/op
Iteration   3: 3.146 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.197 ±(99.9%) 0.825 ms/op [Average]
  (min, avg, max) = (3.146, 3.197, 3.232), stdev = 0.045
  CI (99.9%): [2.372, 4.022] (assumes normal distribution)


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
# Warmup Iteration   1: 6.406 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.282 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.281 ±(99.9%) 0.002 ms/op
Iteration   1: 3.118 ±(99.9%) 0.006 ms/op
Iteration   2: 3.209 ±(99.9%) 0.006 ms/op
Iteration   3: 3.209 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.179 ±(99.9%) 0.967 ms/op [Average]
  (min, avg, max) = (3.118, 3.179, 3.209), stdev = 0.053
  CI (99.9%): [2.212, 4.145] (assumes normal distribution)


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
# Warmup Iteration   1: 8.925 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.872 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.210 ±(99.9%) 0.004 ms/op
Iteration   1: 3.129 ±(99.9%) 0.006 ms/op
Iteration   2: 3.171 ±(99.9%) 0.002 ms/op
Iteration   3: 3.102 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.134 ±(99.9%) 0.634 ms/op [Average]
  (min, avg, max) = (3.102, 3.134, 3.171), stdev = 0.035
  CI (99.9%): [2.500, 3.768] (assumes normal distribution)


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
# Warmup Iteration   1: 8.374 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.062 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.765 ±(99.9%) 0.006 ms/op
Iteration   1: 3.776 ±(99.9%) 0.006 ms/op
Iteration   2: 3.768 ±(99.9%) 0.009 ms/op
Iteration   3: 3.705 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.749 ±(99.9%) 0.709 ms/op [Average]
  (min, avg, max) = (3.705, 3.749, 3.776), stdev = 0.039
  CI (99.9%): [3.041, 4.458] (assumes normal distribution)


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
# Warmup Iteration   1: 7.413 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.602 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.008 ms/op
Iteration   1: 3.291 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.085 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   4.026 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   5.841 ms/op
                 createUser·p0.999:  11.010 ms/op
                 createUser·p0.9999: 20.611 ms/op
                 createUser·p1.00:   22.151 ms/op

Iteration   2: 3.204 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.930 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   5.429 ms/op
                 createUser·p0.999:  15.602 ms/op
                 createUser·p0.9999: 22.775 ms/op
                 createUser·p1.00:   23.986 ms/op

Iteration   3: 3.185 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.274 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  17.596 ms/op
                 createUser·p0.9999: 20.217 ms/op
                 createUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297294
  mean =      3.226 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13404 
    [ 2.500,  5.000) = 277018 
    [ 5.000,  7.500) = 5742 
    [ 7.500, 10.000) = 538 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 186 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.930 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      5.686 ms/op
     p(99.9000) =     17.498 ms/op
     p(99.9900) =     22.357 ms/op
     p(99.9990) =     28.214 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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
# Warmup Iteration   1: 6.645 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 3.315 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.201 ±(99.9%) 0.007 ms/op
Iteration   1: 3.055 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   5.770 ms/op
                 existUser·p0.999:  9.355 ms/op
                 existUser·p0.9999: 18.466 ms/op
                 existUser·p1.00:   19.169 ms/op

Iteration   2: 3.269 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.868 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.133 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  13.379 ms/op
                 existUser·p0.9999: 24.066 ms/op
                 existUser·p1.00:   24.740 ms/op

Iteration   3: 3.053 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.300 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  9.325 ms/op
                 existUser·p0.9999: 19.023 ms/op
                 existUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307053
  mean =      3.122 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19369 
    [ 2.500,  5.000) = 281714 
    [ 5.000,  7.500) = 5353 
    [ 7.500, 10.000) = 252 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     12.434 ms/op
     p(99.9900) =     22.454 ms/op
     p(99.9990) =     24.375 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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
# Warmup Iteration   1: 8.599 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.442 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.009 ms/op
Iteration   1: 3.178 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.464 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  17.793 ms/op
                 getUser·p0.9999: 19.825 ms/op
                 getUser·p1.00:   20.742 ms/op

Iteration   2: 3.266 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.606 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   6.021 ms/op
                 getUser·p0.999:  13.501 ms/op
                 getUser·p0.9999: 22.033 ms/op
                 getUser·p1.00:   22.413 ms/op

Iteration   3: 3.315 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.378 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.350 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  13.218 ms/op
                 getUser·p0.9999: 21.552 ms/op
                 getUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294965
  mean =      3.252 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16637 
    [ 2.500,  5.000) = 268718 
    [ 5.000,  7.500) = 8320 
    [ 7.500, 10.000) = 807 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 161 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.245 ms/op
     p(99.9000) =     15.975 ms/op
     p(99.9900) =     21.463 ms/op
     p(99.9990) =     22.351 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


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
# Warmup Iteration   1: 8.834 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.125 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.820 ±(99.9%) 0.012 ms/op
Iteration   1: 3.738 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.294 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  15.701 ms/op
                 listUser·p0.9999: 21.398 ms/op
                 listUser·p1.00:   21.856 ms/op

Iteration   2: 3.729 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   7.414 ms/op
                 listUser·p0.999:  12.796 ms/op
                 listUser·p0.9999: 14.081 ms/op
                 listUser·p1.00:   14.828 ms/op

Iteration   3: 3.684 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   6.423 ms/op
                 listUser·p0.999:  12.714 ms/op
                 listUser·p0.9999: 16.810 ms/op
                 listUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258312
  mean =      3.717 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 63 
    [ 2.500,  5.000) = 250562 
    [ 5.000,  7.500) = 5953 
    [ 7.500, 10.000) = 1089 
    [10.000, 12.500) = 267 
    [12.500, 15.000) = 248 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.294 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     13.156 ms/op
     p(99.9900) =     19.628 ms/op
     p(99.9990) =     21.804 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.216 ± 2.503  ops/ms
ClientPb.existUser                       thrpt       3  10.451 ± 4.220  ops/ms
ClientPb.getUser                         thrpt       3  10.201 ± 2.913  ops/ms
ClientPb.listUser                        thrpt       3   8.572 ± 1.540  ops/ms
ClientPb.createUser                       avgt       3   3.197 ± 0.825   ms/op
ClientPb.existUser                        avgt       3   3.179 ± 0.967   ms/op
ClientPb.getUser                          avgt       3   3.134 ± 0.634   ms/op
ClientPb.listUser                         avgt       3   3.749 ± 0.709   ms/op
ClientPb.createUser                     sample  297294   3.226 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.930           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.190           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.686           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.498           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.357           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.246           ms/op
ClientPb.existUser                      sample  307053   3.122 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.868           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.535           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.879           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.464           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.434           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.454           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.740           ms/op
ClientPb.getUser                        sample  294965   3.252 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.606           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.670           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.245           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.975           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.463           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.413           ms/op
ClientPb.listUser                       sample  258312   3.717 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.294           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.629           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.969           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.252           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.799           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.156           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.628           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.856           ms/op
