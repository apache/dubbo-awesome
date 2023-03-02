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
# Warmup Iteration   1: 2.450 ops/ms
# Warmup Iteration   2: 5.710 ops/ms
# Warmup Iteration   3: 8.505 ops/ms
Iteration   1: 9.574 ops/ms
Iteration   2: 9.431 ops/ms
Iteration   3: 9.710 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.571 ±(99.9%) 2.551 ops/ms [Average]
  (min, avg, max) = (9.431, 9.571, 9.710), stdev = 0.140
  CI (99.9%): [7.020, 12.123] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.164 ops/ms
# Warmup Iteration   2: 9.218 ops/ms
# Warmup Iteration   3: 9.767 ops/ms
Iteration   1: 10.149 ops/ms
Iteration   2: 10.094 ops/ms
Iteration   3: 10.208 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.150 ±(99.9%) 1.039 ops/ms [Average]
  (min, avg, max) = (10.094, 10.150, 10.208), stdev = 0.057
  CI (99.9%): [9.111, 11.189] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.148 ops/ms
# Warmup Iteration   2: 8.499 ops/ms
# Warmup Iteration   3: 8.938 ops/ms
Iteration   1: 9.457 ops/ms
Iteration   2: 9.319 ops/ms
Iteration   3: 9.520 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.432 ±(99.9%) 1.868 ops/ms [Average]
  (min, avg, max) = (9.319, 9.432, 9.520), stdev = 0.102
  CI (99.9%): [7.564, 11.300] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 2.913 ops/ms
# Warmup Iteration   2: 7.272 ops/ms
# Warmup Iteration   3: 7.927 ops/ms
Iteration   1: 8.058 ops/ms
Iteration   2: 8.287 ops/ms
Iteration   3: 8.439 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.261 ±(99.9%) 3.499 ops/ms [Average]
  (min, avg, max) = (8.058, 8.261, 8.439), stdev = 0.192
  CI (99.9%): [4.762, 11.761] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.475 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.716 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.527 ±(99.9%) 0.004 ms/op
Iteration   1: 3.311 ±(99.9%) 0.009 ms/op
Iteration   2: 3.341 ±(99.9%) 0.010 ms/op
Iteration   3: 3.444 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.365 ±(99.9%) 1.272 ms/op [Average]
  (min, avg, max) = (3.311, 3.365, 3.444), stdev = 0.070
  CI (99.9%): [2.093, 4.638] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.083 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.415 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.312 ±(99.9%) 0.002 ms/op
Iteration   1: 3.203 ±(99.9%) 0.005 ms/op
Iteration   2: 3.280 ±(99.9%) 0.003 ms/op
Iteration   3: 3.249 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.244 ±(99.9%) 0.707 ms/op [Average]
  (min, avg, max) = (3.203, 3.244, 3.280), stdev = 0.039
  CI (99.9%): [2.537, 3.951] (assumes normal distribution)


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
# Warmup Iteration   1: 7.765 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.600 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.471 ±(99.9%) 0.007 ms/op
Iteration   1: 3.260 ±(99.9%) 0.006 ms/op
Iteration   2: 3.255 ±(99.9%) 0.012 ms/op
Iteration   3: 3.381 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.299 ±(99.9%) 1.296 ms/op [Average]
  (min, avg, max) = (3.255, 3.299, 3.381), stdev = 0.071
  CI (99.9%): [2.003, 4.595] (assumes normal distribution)


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
# Warmup Iteration   1: 10.719 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.421 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.069 ±(99.9%) 0.016 ms/op
Iteration   1: 3.912 ±(99.9%) 0.010 ms/op
Iteration   2: 3.957 ±(99.9%) 0.011 ms/op
Iteration   3: 3.822 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.897 ±(99.9%) 1.253 ms/op [Average]
  (min, avg, max) = (3.822, 3.897, 3.957), stdev = 0.069
  CI (99.9%): [2.643, 5.150] (assumes normal distribution)


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
# Warmup Iteration   1: 8.357 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.109 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.403 ±(99.9%) 0.010 ms/op
Iteration   1: 3.268 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.980 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   5.857 ms/op
                 createUser·p0.999:  10.666 ms/op
                 createUser·p0.9999: 24.746 ms/op
                 createUser·p1.00:   25.559 ms/op

Iteration   2: 3.251 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.300 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.420 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   5.153 ms/op
                 createUser·p0.999:  9.830 ms/op
                 createUser·p0.9999: 35.475 ms/op
                 createUser·p1.00:   36.635 ms/op

Iteration   3: 3.343 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.288 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   6.242 ms/op
                 createUser·p0.999:  20.972 ms/op
                 createUser·p0.9999: 31.799 ms/op
                 createUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 292124
  mean =      3.287 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14939 
    [ 2.500,  5.000) = 271966 
    [ 5.000,  7.500) = 4429 
    [ 7.500, 10.000) = 399 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.288 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      5.749 ms/op
     p(99.9000) =     19.526 ms/op
     p(99.9900) =     35.067 ms/op
     p(99.9990) =     36.635 ms/op
     p(99.9999) =     36.635 ms/op
    p(100.0000) =     36.635 ms/op


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
# Warmup Iteration   1: 7.505 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.506 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.278 ±(99.9%) 0.008 ms/op
Iteration   1: 3.192 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.624 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  20.143 ms/op
                 existUser·p0.9999: 22.740 ms/op
                 existUser·p1.00:   24.707 ms/op

Iteration   2: 3.269 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.141 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   5.644 ms/op
                 existUser·p0.999:  15.882 ms/op
                 existUser·p0.9999: 23.240 ms/op
                 existUser·p1.00:   23.560 ms/op

Iteration   3: 3.186 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.075 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.591 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  13.319 ms/op
                 existUser·p0.9999: 24.868 ms/op
                 existUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 298270
  mean =      3.215 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13446 
    [ 2.500,  5.000) = 280325 
    [ 5.000,  7.500) = 3591 
    [ 7.500, 10.000) = 463 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 170 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     15.955 ms/op
     p(99.9900) =     23.926 ms/op
     p(99.9990) =     25.432 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


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
# Warmup Iteration   1: 8.673 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.588 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.459 ±(99.9%) 0.010 ms/op
Iteration   1: 3.385 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.861 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   6.586 ms/op
                 getUser·p0.999:  21.480 ms/op
                 getUser·p0.9999: 53.776 ms/op
                 getUser·p1.00:   54.133 ms/op

Iteration   2: 3.277 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.225 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   5.947 ms/op
                 getUser·p0.999:  14.429 ms/op
                 getUser·p0.9999: 27.074 ms/op
                 getUser·p1.00:   28.246 ms/op

Iteration   3: 3.431 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.204 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.957 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   6.668 ms/op
                 getUser·p0.999:  18.121 ms/op
                 getUser·p0.9999: 29.612 ms/op
                 getUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 285178
  mean =      3.363 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 276585 
    [ 5.000, 10.000) = 8175 
    [10.000, 15.000) = 130 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 110 
    [25.000, 30.000) = 112 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 1 
    [50.000, 55.000) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      6.480 ms/op
     p(99.9000) =     18.121 ms/op
     p(99.9900) =     52.198 ms/op
     p(99.9990) =     54.067 ms/op
     p(99.9999) =     54.133 ms/op
    p(100.0000) =     54.133 ms/op


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
# Warmup Iteration   1: 10.250 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 4.396 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.246 ±(99.9%) 0.014 ms/op
Iteration   1: 4.153 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.360 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   7.873 ms/op
                 listUser·p0.999:  16.122 ms/op
                 listUser·p0.9999: 27.109 ms/op
                 listUser·p1.00:   28.115 ms/op

Iteration   2: 3.955 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.714 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  15.093 ms/op
                 listUser·p0.9999: 20.215 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   3: 3.921 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.761 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  14.877 ms/op
                 listUser·p0.9999: 18.967 ms/op
                 listUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239492
  mean =      4.007 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 229516 
    [ 5.000,  7.500) = 7678 
    [ 7.500, 10.000) = 1550 
    [10.000, 12.500) = 226 
    [12.500, 15.000) = 247 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.360 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     14.983 ms/op
     p(99.9900) =     25.952 ms/op
     p(99.9990) =     27.598 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.571 ± 2.551  ops/ms
ClientPb.existUser                       thrpt       3  10.150 ± 1.039  ops/ms
ClientPb.getUser                         thrpt       3   9.432 ± 1.868  ops/ms
ClientPb.listUser                        thrpt       3   8.261 ± 3.499  ops/ms
ClientPb.createUser                       avgt       3   3.365 ± 1.272   ms/op
ClientPb.existUser                        avgt       3   3.244 ± 0.707   ms/op
ClientPb.getUser                          avgt       3   3.299 ± 1.296   ms/op
ClientPb.listUser                         avgt       3   3.897 ± 1.253   ms/op
ClientPb.createUser                     sample  292124   3.287 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.288           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.609           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.932           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.749           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.526           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.067           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.635           ms/op
ClientPb.existUser                      sample  298270   3.215 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.075           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.457           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.472           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.955           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.926           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.690           ms/op
ClientPb.getUser                        sample  285178   3.363 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.861           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.777           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.137           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.480           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.121           ms/op
ClientPb.getUser:getUser·p0.9999        sample          52.198           ms/op
ClientPb.getUser:getUser·p1.00          sample          54.133           ms/op
ClientPb.listUser                       sample  239492   4.007 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.360           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.809           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.414           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.983           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.952           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.115           ms/op
