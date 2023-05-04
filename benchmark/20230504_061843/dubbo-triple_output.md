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
# Warmup Iteration   1: 1.573 ops/ms
# Warmup Iteration   2: 3.094 ops/ms
# Warmup Iteration   3: 6.546 ops/ms
Iteration   1: 6.644 ops/ms
Iteration   2: 7.999 ops/ms
Iteration   3: 8.210 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.618 ±(99.9%) 15.505 ops/ms [Average]
  (min, avg, max) = (6.644, 7.618, 8.210), stdev = 0.850
  CI (99.9%): [≈ 0, 23.123] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 1.905 ops/ms
# Warmup Iteration   2: 6.732 ops/ms
# Warmup Iteration   3: 8.029 ops/ms
Iteration   1: 8.372 ops/ms
Iteration   2: 8.372 ops/ms
Iteration   3: 8.403 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.382 ±(99.9%) 0.318 ops/ms [Average]
  (min, avg, max) = (8.372, 8.382, 8.403), stdev = 0.017
  CI (99.9%): [8.064, 8.700] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.183 ops/ms
# Warmup Iteration   2: 6.253 ops/ms
# Warmup Iteration   3: 7.018 ops/ms
Iteration   1: 7.767 ops/ms
Iteration   2: 8.176 ops/ms
Iteration   3: 8.136 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.026 ±(99.9%) 4.115 ops/ms [Average]
  (min, avg, max) = (7.767, 8.026, 8.176), stdev = 0.226
  CI (99.9%): [3.911, 12.141] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.946 ops/ms
# Warmup Iteration   2: 5.038 ops/ms
# Warmup Iteration   3: 5.972 ops/ms
Iteration   1: 6.776 ops/ms
Iteration   2: 6.258 ops/ms
Iteration   3: 7.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.688 ±(99.9%) 7.171 ops/ms [Average]
  (min, avg, max) = (6.258, 6.688, 7.030), stdev = 0.393
  CI (99.9%): [≈ 0, 13.859] (assumes normal distribution)


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
# Warmup Iteration   1: 12.783 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 5.445 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.103 ±(99.9%) 0.007 ms/op
Iteration   1: 4.390 ±(99.9%) 0.010 ms/op
Iteration   2: 4.250 ±(99.9%) 0.014 ms/op
Iteration   3: 3.917 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.186 ±(99.9%) 4.429 ms/op [Average]
  (min, avg, max) = (3.917, 4.186, 4.390), stdev = 0.243
  CI (99.9%): [≈ 0, 8.615] (assumes normal distribution)


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
# Warmup Iteration   1: 16.836 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 5.201 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.000 ±(99.9%) 0.006 ms/op
Iteration   1: 4.217 ±(99.9%) 0.005 ms/op
Iteration   2: 3.745 ±(99.9%) 0.007 ms/op
Iteration   3: 3.799 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.920 ±(99.9%) 4.714 ms/op [Average]
  (min, avg, max) = (3.745, 3.920, 4.217), stdev = 0.258
  CI (99.9%): [≈ 0, 8.634] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 14.566 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.877 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.077 ±(99.9%) 0.009 ms/op
Iteration   1: 4.411 ±(99.9%) 0.009 ms/op
Iteration   2: 4.387 ±(99.9%) 0.009 ms/op
Iteration   3: 4.436 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.411 ±(99.9%) 0.441 ms/op [Average]
  (min, avg, max) = (4.387, 4.411, 4.436), stdev = 0.024
  CI (99.9%): [3.970, 4.853] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 13.208 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.278 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.882 ±(99.9%) 0.008 ms/op
Iteration   1: 4.679 ±(99.9%) 0.008 ms/op
Iteration   2: 5.114 ±(99.9%) 0.007 ms/op
Iteration   3: 5.706 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.166 ±(99.9%) 9.405 ms/op [Average]
  (min, avg, max) = (4.679, 5.166, 5.706), stdev = 0.515
  CI (99.9%): [≈ 0, 14.571] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 13.833 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 5.877 ±(99.9%) 0.074 ms/op
# Warmup Iteration   3: 4.766 ±(99.9%) 0.034 ms/op
Iteration   1: 4.323 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   1.970 ms/op
                 createUser·p0.50:   3.752 ms/op
                 createUser·p0.90:   4.817 ms/op
                 createUser·p0.95:   6.652 ms/op
                 createUser·p0.99:   16.712 ms/op
                 createUser·p0.999:  26.082 ms/op
                 createUser·p0.9999: 32.755 ms/op
                 createUser·p1.00:   33.489 ms/op

Iteration   2: 4.648 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   1.997 ms/op
                 createUser·p0.50:   3.752 ms/op
                 createUser·p0.90:   4.841 ms/op
                 createUser·p0.95:   14.238 ms/op
                 createUser·p0.99:   18.907 ms/op
                 createUser·p0.999:  25.843 ms/op
                 createUser·p0.9999: 29.164 ms/op
                 createUser·p1.00:   30.638 ms/op

Iteration   3: 4.216 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   2.146 ms/op
                 createUser·p0.50:   3.830 ms/op
                 createUser·p0.90:   4.157 ms/op
                 createUser·p0.95:   5.620 ms/op
                 createUser·p0.99:   16.482 ms/op
                 createUser·p0.999:  26.583 ms/op
                 createUser·p0.9999: 32.892 ms/op
                 createUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 218562
  mean =      4.388 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 147 
    [ 2.500,  5.000) = 200870 
    [ 5.000,  7.500) = 7313 
    [ 7.500, 10.000) = 1381 
    [10.000, 12.500) = 1054 
    [12.500, 15.000) = 2283 
    [15.000, 17.500) = 3350 
    [17.500, 20.000) = 1152 
    [20.000, 22.500) = 487 
    [22.500, 25.000) = 213 
    [25.000, 27.500) = 176 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.970 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      7.004 ms/op
     p(99.0000) =     17.465 ms/op
     p(99.9000) =     26.327 ms/op
     p(99.9900) =     32.571 ms/op
     p(99.9990) =     33.817 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.584 ±(99.9%) 0.260 ms/op
# Warmup Iteration   2: 5.440 ±(99.9%) 0.064 ms/op
# Warmup Iteration   3: 4.333 ±(99.9%) 0.040 ms/op
Iteration   1: 3.863 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.946 ms/op
                 existUser·p0.50:   3.695 ms/op
                 existUser·p0.90:   4.481 ms/op
                 existUser·p0.95:   5.104 ms/op
                 existUser·p0.99:   7.004 ms/op
                 existUser·p0.999:  12.064 ms/op
                 existUser·p0.9999: 26.369 ms/op
                 existUser·p1.00:   28.213 ms/op

Iteration   2: 3.966 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   1.286 ms/op
                 existUser·p0.50:   3.572 ms/op
                 existUser·p0.90:   3.969 ms/op
                 existUser·p0.95:   5.382 ms/op
                 existUser·p0.99:   14.959 ms/op
                 existUser·p0.999:  21.705 ms/op
                 existUser·p0.9999: 27.521 ms/op
                 existUser·p1.00:   28.049 ms/op

Iteration   3: 3.829 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.399 ms/op
                 existUser·p0.50:   3.633 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.768 ms/op
                 existUser·p0.99:   7.456 ms/op
                 existUser·p0.999:  14.598 ms/op
                 existUser·p0.9999: 29.053 ms/op
                 existUser·p1.00:   30.015 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 247092
  mean =      3.885 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 320 
    [ 2.500,  5.000) = 234157 
    [ 5.000,  7.500) = 8442 
    [ 7.500, 10.000) = 1274 
    [10.000, 12.500) = 716 
    [12.500, 15.000) = 1243 
    [15.000, 17.500) = 574 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.286 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =     11.551 ms/op
     p(99.9000) =     20.152 ms/op
     p(99.9900) =     28.593 ms/op
     p(99.9990) =     29.464 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.533 ±(99.9%) 0.208 ms/op
# Warmup Iteration   2: 5.069 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.224 ±(99.9%) 0.015 ms/op
Iteration   1: 4.071 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.066 ms/op
                 getUser·p0.50:   3.817 ms/op
                 getUser·p0.90:   4.678 ms/op
                 getUser·p0.95:   5.865 ms/op
                 getUser·p0.99:   8.634 ms/op
                 getUser·p0.999:  24.478 ms/op
                 getUser·p0.9999: 33.948 ms/op
                 getUser·p1.00:   33.948 ms/op

Iteration   2: 4.413 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   2.327 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   5.005 ms/op
                 getUser·p0.95:   6.537 ms/op
                 getUser·p0.99:   18.612 ms/op
                 getUser·p0.999:  30.048 ms/op
                 getUser·p0.9999: 38.388 ms/op
                 getUser·p1.00:   50.332 ms/op

Iteration   3: 4.029 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.134 ms/op
                 getUser·p0.50:   3.805 ms/op
                 getUser·p0.90:   4.661 ms/op
                 getUser·p0.95:   5.439 ms/op
                 getUser·p0.99:   8.077 ms/op
                 getUser·p0.999:  29.182 ms/op
                 getUser·p0.9999: 33.820 ms/op
                 getUser·p1.00:   35.652 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 230608
  mean =      4.164 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 212215 
    [ 5.000, 10.000) = 15682 
    [10.000, 15.000) = 1077 
    [15.000, 20.000) = 842 
    [20.000, 25.000) = 382 
    [25.000, 30.000) = 241 
    [30.000, 35.000) = 128 
    [35.000, 40.000) = 36 
    [40.000, 45.000) = 1 
    [45.000, 50.000) = 3 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.066 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.898 ms/op
     p(99.0000) =     11.928 ms/op
     p(99.9000) =     28.508 ms/op
     p(99.9900) =     37.548 ms/op
     p(99.9990) =     45.629 ms/op
     p(99.9999) =     50.332 ms/op
    p(100.0000) =     50.332 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.053 ±(99.9%) 0.227 ms/op
# Warmup Iteration   2: 6.515 ±(99.9%) 0.069 ms/op
# Warmup Iteration   3: 4.597 ±(99.9%) 0.013 ms/op
Iteration   1: 5.321 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   1.939 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   6.300 ms/op
                 listUser·p0.95:   8.520 ms/op
                 listUser·p0.99:   22.807 ms/op
                 listUser·p0.999:  31.850 ms/op
                 listUser·p0.9999: 46.005 ms/op
                 listUser·p1.00:   46.203 ms/op

Iteration   2: 4.999 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   2.404 ms/op
                 listUser·p0.50:   4.366 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   7.029 ms/op
                 listUser·p0.99:   19.366 ms/op
                 listUser·p0.999:  27.168 ms/op
                 listUser·p0.9999: 39.991 ms/op
                 listUser·p1.00:   41.812 ms/op

Iteration   3: 4.675 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.834 ms/op
                 listUser·p0.50:   4.391 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   6.373 ms/op
                 listUser·p0.99:   9.224 ms/op
                 listUser·p0.999:  17.662 ms/op
                 listUser·p0.9999: 23.364 ms/op
                 listUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 192357
  mean =      4.985 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 157326 
    [ 5.000, 10.000) = 30288 
    [10.000, 15.000) = 1292 
    [15.000, 20.000) = 2020 
    [20.000, 25.000) = 980 
    [25.000, 30.000) = 327 
    [30.000, 35.000) = 69 
    [35.000, 40.000) = 16 
    [40.000, 45.000) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.939 ms/op
     p(50.0000) =      4.424 ms/op
     p(90.0000) =      5.431 ms/op
     p(95.0000) =      7.463 ms/op
     p(99.0000) =     18.678 ms/op
     p(99.9000) =     27.984 ms/op
     p(99.9900) =     43.091 ms/op
     p(99.9990) =     46.142 ms/op
     p(99.9999) =     46.203 ms/op
    p(100.0000) =     46.203 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   7.618 ± 15.505  ops/ms
ClientPb.existUser                       thrpt       3   8.382 ±  0.318  ops/ms
ClientPb.getUser                         thrpt       3   8.026 ±  4.115  ops/ms
ClientPb.listUser                        thrpt       3   6.688 ±  7.171  ops/ms
ClientPb.createUser                       avgt       3   4.186 ±  4.429   ms/op
ClientPb.existUser                        avgt       3   3.920 ±  4.714   ms/op
ClientPb.getUser                          avgt       3   4.411 ±  0.441   ms/op
ClientPb.listUser                         avgt       3   5.166 ±  9.405   ms/op
ClientPb.createUser                     sample  218562   4.388 ±  0.018   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.970            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.789            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.620            ms/op
ClientPb.createUser:createUser·p0.95    sample           7.004            ms/op
ClientPb.createUser:createUser·p0.99    sample          17.465            ms/op
ClientPb.createUser:createUser·p0.999   sample          26.327            ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.571            ms/op
ClientPb.createUser:createUser·p1.00    sample          33.948            ms/op
ClientPb.existUser                      sample  247092   3.885 ±  0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.286            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.633            ms/op
ClientPb.existUser:existUser·p0.90      sample           4.293            ms/op
ClientPb.existUser:existUser·p0.95      sample           5.030            ms/op
ClientPb.existUser:existUser·p0.99      sample          11.551            ms/op
ClientPb.existUser:existUser·p0.999     sample          20.152            ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.593            ms/op
ClientPb.existUser:existUser·p1.00      sample          30.015            ms/op
ClientPb.getUser                        sample  230608   4.164 ±  0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.066            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.858            ms/op
ClientPb.getUser:getUser·p0.90          sample           4.760            ms/op
ClientPb.getUser:getUser·p0.95          sample           5.898            ms/op
ClientPb.getUser:getUser·p0.99          sample          11.928            ms/op
ClientPb.getUser:getUser·p0.999         sample          28.508            ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.548            ms/op
ClientPb.getUser:getUser·p1.00          sample          50.332            ms/op
ClientPb.listUser                       sample  192357   4.985 ±  0.018   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.939            ms/op
ClientPb.listUser:listUser·p0.50        sample           4.424            ms/op
ClientPb.listUser:listUser·p0.90        sample           5.431            ms/op
ClientPb.listUser:listUser·p0.95        sample           7.463            ms/op
ClientPb.listUser:listUser·p0.99        sample          18.678            ms/op
ClientPb.listUser:listUser·p0.999       sample          27.984            ms/op
ClientPb.listUser:listUser·p0.9999      sample          43.091            ms/op
ClientPb.listUser:listUser·p1.00        sample          46.203            ms/op
