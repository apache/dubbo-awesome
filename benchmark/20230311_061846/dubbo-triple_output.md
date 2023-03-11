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
# Warmup Iteration   1: 1.028 ops/ms
# Warmup Iteration   2: 2.413 ops/ms
# Warmup Iteration   3: 5.433 ops/ms
Iteration   1: 5.579 ops/ms
Iteration   2: 5.632 ops/ms
Iteration   3: 5.845 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.685 ±(99.9%) 2.570 ops/ms [Average]
  (min, avg, max) = (5.579, 5.685, 5.845), stdev = 0.141
  CI (99.9%): [3.115, 8.256] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.525 ops/ms
# Warmup Iteration   2: 4.898 ops/ms
# Warmup Iteration   3: 6.357 ops/ms
Iteration   1: 6.337 ops/ms
Iteration   2: 6.287 ops/ms
Iteration   3: 6.272 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.299 ±(99.9%) 0.626 ops/ms [Average]
  (min, avg, max) = (6.272, 6.299, 6.337), stdev = 0.034
  CI (99.9%): [5.672, 6.925] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.509 ops/ms
# Warmup Iteration   2: 4.544 ops/ms
# Warmup Iteration   3: 5.730 ops/ms
Iteration   1: 5.823 ops/ms
Iteration   2: 5.621 ops/ms
Iteration   3: 5.591 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.678 ±(99.9%) 2.301 ops/ms [Average]
  (min, avg, max) = (5.591, 5.678, 5.823), stdev = 0.126
  CI (99.9%): [3.377, 7.980] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.244 ops/ms
# Warmup Iteration   2: 3.972 ops/ms
# Warmup Iteration   3: 4.838 ops/ms
Iteration   1: 4.737 ops/ms
Iteration   2: 4.859 ops/ms
Iteration   3: 5.005 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.867 ±(99.9%) 2.446 ops/ms [Average]
  (min, avg, max) = (4.737, 4.867, 5.005), stdev = 0.134
  CI (99.9%): [2.420, 7.313] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 19.255 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 6.860 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.130 ±(99.9%) 0.007 ms/op
Iteration   1: 5.794 ±(99.9%) 0.010 ms/op
Iteration   2: 5.415 ±(99.9%) 0.013 ms/op
Iteration   3: 5.502 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.571 ±(99.9%) 3.624 ms/op [Average]
  (min, avg, max) = (5.415, 5.571, 5.794), stdev = 0.199
  CI (99.9%): [1.947, 9.194] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 16.574 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 6.199 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.491 ±(99.9%) 0.010 ms/op
Iteration   1: 5.458 ±(99.9%) 0.012 ms/op
Iteration   2: 5.249 ±(99.9%) 0.015 ms/op
Iteration   3: 5.195 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.301 ±(99.9%) 2.528 ms/op [Average]
  (min, avg, max) = (5.195, 5.301, 5.458), stdev = 0.139
  CI (99.9%): [2.773, 7.829] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 17.557 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 6.518 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.689 ±(99.9%) 0.010 ms/op
Iteration   1: 5.623 ±(99.9%) 0.006 ms/op
Iteration   2: 5.586 ±(99.9%) 0.009 ms/op
Iteration   3: 5.353 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.521 ±(99.9%) 2.674 ms/op [Average]
  (min, avg, max) = (5.353, 5.521, 5.623), stdev = 0.147
  CI (99.9%): [2.847, 8.194] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 21.298 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 8.525 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.556 ±(99.9%) 0.014 ms/op
Iteration   1: 6.320 ±(99.9%) 0.017 ms/op
Iteration   2: 6.321 ±(99.9%) 0.018 ms/op
Iteration   3: 6.247 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.296 ±(99.9%) 0.771 ms/op [Average]
  (min, avg, max) = (6.247, 6.296, 6.321), stdev = 0.042
  CI (99.9%): [5.525, 7.068] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 18.049 ±(99.9%) 0.346 ms/op
# Warmup Iteration   2: 7.285 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 5.827 ±(99.9%) 0.025 ms/op
Iteration   1: 5.724 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.249 ms/op
                 createUser·p0.50:   5.243 ms/op
                 createUser·p0.90:   7.586 ms/op
                 createUser·p0.95:   8.847 ms/op
                 createUser·p0.99:   12.337 ms/op
                 createUser·p0.999:  16.564 ms/op
                 createUser·p0.9999: 32.219 ms/op
                 createUser·p1.00:   32.375 ms/op

Iteration   2: 5.427 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.228 ms/op
                 createUser·p0.50:   5.005 ms/op
                 createUser·p0.90:   6.873 ms/op
                 createUser·p0.95:   8.020 ms/op
                 createUser·p0.99:   11.364 ms/op
                 createUser·p0.999:  26.745 ms/op
                 createUser·p0.9999: 30.580 ms/op
                 createUser·p1.00:   33.260 ms/op

Iteration   3: 5.653 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.003 ms/op
                 createUser·p0.50:   5.267 ms/op
                 createUser·p0.90:   7.135 ms/op
                 createUser·p0.95:   8.317 ms/op
                 createUser·p0.99:   11.731 ms/op
                 createUser·p0.999:  28.312 ms/op
                 createUser·p0.9999: 33.282 ms/op
                 createUser·p1.00:   33.456 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 171392
  mean =      5.598 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 74110 
    [ 5.000,  7.500) = 82843 
    [ 7.500, 10.000) = 10603 
    [10.000, 12.500) = 2406 
    [12.500, 15.000) = 926 
    [15.000, 17.500) = 226 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 79 
    [30.000, 32.500) = 62 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.003 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      7.217 ms/op
     p(95.0000) =      8.421 ms/op
     p(99.0000) =     12.043 ms/op
     p(99.9000) =     27.152 ms/op
     p(99.9900) =     32.375 ms/op
     p(99.9990) =     33.433 ms/op
     p(99.9999) =     33.456 ms/op
    p(100.0000) =     33.456 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 18.959 ±(99.9%) 0.316 ms/op
# Warmup Iteration   2: 6.392 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.376 ±(99.9%) 0.019 ms/op
Iteration   1: 5.207 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.761 ms/op
                 existUser·p0.50:   4.833 ms/op
                 existUser·p0.90:   6.529 ms/op
                 existUser·p0.95:   7.684 ms/op
                 existUser·p0.99:   10.535 ms/op
                 existUser·p0.999:  23.233 ms/op
                 existUser·p0.9999: 28.077 ms/op
                 existUser·p1.00:   31.162 ms/op

Iteration   2: 5.491 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   1.972 ms/op
                 existUser·p0.50:   5.005 ms/op
                 existUser·p0.90:   7.184 ms/op
                 existUser·p0.95:   8.405 ms/op
                 existUser·p0.99:   11.993 ms/op
                 existUser·p0.999:  25.015 ms/op
                 existUser·p0.9999: 29.115 ms/op
                 existUser·p1.00:   29.721 ms/op

Iteration   3: 5.176 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.918 ms/op
                 existUser·p0.50:   4.735 ms/op
                 existUser·p0.90:   6.660 ms/op
                 existUser·p0.95:   7.752 ms/op
                 existUser·p0.99:   11.113 ms/op
                 existUser·p0.999:  17.080 ms/op
                 existUser·p0.9999: 29.426 ms/op
                 existUser·p1.00:   29.917 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 181470
  mean =      5.287 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 104824 
    [ 5.000,  7.500) = 64614 
    [ 7.500, 10.000) = 8971 
    [10.000, 12.500) = 1873 
    [12.500, 15.000) = 639 
    [15.000, 17.500) = 215 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 66 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      4.841 ms/op
     p(90.0000) =      6.791 ms/op
     p(95.0000) =      7.995 ms/op
     p(99.0000) =     11.223 ms/op
     p(99.9000) =     23.414 ms/op
     p(99.9900) =     29.154 ms/op
     p(99.9990) =     30.148 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 21.030 ±(99.9%) 0.376 ms/op
# Warmup Iteration   2: 7.690 ±(99.9%) 0.063 ms/op
# Warmup Iteration   3: 5.774 ±(99.9%) 0.022 ms/op
Iteration   1: 5.522 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.134 ms/op
                 getUser·p0.50:   5.095 ms/op
                 getUser·p0.90:   6.832 ms/op
                 getUser·p0.95:   8.684 ms/op
                 getUser·p0.99:   12.075 ms/op
                 getUser·p0.999:  25.336 ms/op
                 getUser·p0.9999: 28.194 ms/op
                 getUser·p1.00:   28.967 ms/op

Iteration   2: 5.392 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.064 ms/op
                 getUser·p0.50:   5.046 ms/op
                 getUser·p0.90:   6.521 ms/op
                 getUser·p0.95:   7.938 ms/op
                 getUser·p0.99:   10.732 ms/op
                 getUser·p0.999:  24.288 ms/op
                 getUser·p0.9999: 27.860 ms/op
                 getUser·p1.00:   28.639 ms/op

Iteration   3: 5.719 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.654 ms/op
                 getUser·p0.50:   5.308 ms/op
                 getUser·p0.90:   7.176 ms/op
                 getUser·p0.95:   8.520 ms/op
                 getUser·p0.99:   12.435 ms/op
                 getUser·p0.999:  26.654 ms/op
                 getUser·p0.9999: 32.887 ms/op
                 getUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 173112
  mean =      5.541 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 72345 
    [ 5.000,  7.500) = 88309 
    [ 7.500, 10.000) = 8763 
    [10.000, 12.500) = 2339 
    [12.500, 15.000) = 664 
    [15.000, 17.500) = 296 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 109 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.064 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      6.857 ms/op
     p(95.0000) =      8.339 ms/op
     p(99.0000) =     11.698 ms/op
     p(99.9000) =     25.257 ms/op
     p(99.9900) =     32.234 ms/op
     p(99.9990) =     33.882 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 21.837 ±(99.9%) 0.399 ms/op
# Warmup Iteration   2: 8.088 ±(99.9%) 0.062 ms/op
# Warmup Iteration   3: 6.742 ±(99.9%) 0.032 ms/op
Iteration   1: 6.639 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   6.185 ms/op
                 listUser·p0.90:   8.487 ms/op
                 listUser·p0.95:   9.912 ms/op
                 listUser·p0.99:   13.091 ms/op
                 listUser·p0.999:  28.672 ms/op
                 listUser·p0.9999: 30.775 ms/op
                 listUser·p1.00:   30.999 ms/op

Iteration   2: 6.705 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   2.126 ms/op
                 listUser·p0.50:   6.111 ms/op
                 listUser·p0.90:   8.798 ms/op
                 listUser·p0.95:   10.420 ms/op
                 listUser·p0.99:   14.860 ms/op
                 listUser·p0.999:  34.777 ms/op
                 listUser·p0.9999: 39.463 ms/op
                 listUser·p1.00:   40.829 ms/op

Iteration   3: 6.587 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   3.301 ms/op
                 listUser·p0.50:   6.046 ms/op
                 listUser·p0.90:   8.389 ms/op
                 listUser·p0.95:   10.029 ms/op
                 listUser·p0.99:   14.133 ms/op
                 listUser·p0.999:  29.748 ms/op
                 listUser·p0.9999: 37.814 ms/op
                 listUser·p1.00:   37.945 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 144372
  mean =      6.643 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 5722 
    [ 5.000, 10.000) = 131012 
    [10.000, 15.000) = 6632 
    [15.000, 20.000) = 655 
    [20.000, 25.000) = 83 
    [25.000, 30.000) = 138 
    [30.000, 35.000) = 56 
    [35.000, 40.000) = 73 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.126 ms/op
     p(50.0000) =      6.111 ms/op
     p(90.0000) =      8.569 ms/op
     p(95.0000) =     10.109 ms/op
     p(99.0000) =     13.910 ms/op
     p(99.9000) =     29.676 ms/op
     p(99.9900) =     38.076 ms/op
     p(99.9990) =     40.451 ms/op
     p(99.9999) =     40.829 ms/op
    p(100.0000) =     40.829 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.685 ± 2.570  ops/ms
ClientPb.existUser                       thrpt       3   6.299 ± 0.626  ops/ms
ClientPb.getUser                         thrpt       3   5.678 ± 2.301  ops/ms
ClientPb.listUser                        thrpt       3   4.867 ± 2.446  ops/ms
ClientPb.createUser                       avgt       3   5.571 ± 3.624   ms/op
ClientPb.existUser                        avgt       3   5.301 ± 2.528   ms/op
ClientPb.getUser                          avgt       3   5.521 ± 2.674   ms/op
ClientPb.listUser                         avgt       3   6.296 ± 0.771   ms/op
ClientPb.createUser                     sample  171392   5.598 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.003           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.145           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.217           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.421           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.043           ms/op
ClientPb.createUser:createUser·p0.999   sample          27.152           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.375           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.456           ms/op
ClientPb.existUser                      sample  181470   5.287 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.761           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.841           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.791           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.995           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.223           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.414           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.154           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.162           ms/op
ClientPb.getUser                        sample  173112   5.541 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.064           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.145           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.857           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.339           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.698           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.257           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.234           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.882           ms/op
ClientPb.listUser                       sample  144372   6.643 ± 0.018   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.126           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.111           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.569           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.109           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.910           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.676           ms/op
ClientPb.listUser:listUser·p0.9999      sample          38.076           ms/op
ClientPb.listUser:listUser·p1.00        sample          40.829           ms/op
