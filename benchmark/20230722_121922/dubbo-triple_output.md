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
# Warmup Iteration   1: 0.993 ops/ms
# Warmup Iteration   2: 2.194 ops/ms
# Warmup Iteration   3: 4.695 ops/ms
Iteration   1: 5.534 ops/ms
Iteration   2: 5.670 ops/ms
Iteration   3: 5.456 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.553 ±(99.9%) 1.978 ops/ms [Average]
  (min, avg, max) = (5.456, 5.553, 5.670), stdev = 0.108
  CI (99.9%): [3.575, 7.532] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.569 ops/ms
# Warmup Iteration   2: 4.870 ops/ms
# Warmup Iteration   3: 5.762 ops/ms
Iteration   1: 5.911 ops/ms
Iteration   2: 5.873 ops/ms
Iteration   3: 5.910 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.898 ±(99.9%) 0.395 ops/ms [Average]
  (min, avg, max) = (5.873, 5.898, 5.911), stdev = 0.022
  CI (99.9%): [5.503, 6.293] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.394 ops/ms
# Warmup Iteration   2: 4.166 ops/ms
# Warmup Iteration   3: 5.638 ops/ms
Iteration   1: 5.569 ops/ms
Iteration   2: 5.798 ops/ms
Iteration   3: 5.624 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.664 ±(99.9%) 2.182 ops/ms [Average]
  (min, avg, max) = (5.569, 5.664, 5.798), stdev = 0.120
  CI (99.9%): [3.481, 7.846] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.660 ops/ms
# Warmup Iteration   2: 3.512 ops/ms
# Warmup Iteration   3: 4.829 ops/ms
Iteration   1: 4.732 ops/ms
Iteration   2: 5.013 ops/ms
Iteration   3: 5.128 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.958 ±(99.9%) 3.712 ops/ms [Average]
  (min, avg, max) = (4.732, 4.958, 5.128), stdev = 0.203
  CI (99.9%): [1.245, 8.670] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 18.389 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 6.468 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.964 ±(99.9%) 0.012 ms/op
Iteration   1: 5.437 ±(99.9%) 0.013 ms/op
Iteration   2: 5.315 ±(99.9%) 0.020 ms/op
Iteration   3: 5.467 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.406 ±(99.9%) 1.467 ms/op [Average]
  (min, avg, max) = (5.315, 5.406, 5.467), stdev = 0.080
  CI (99.9%): [3.940, 6.873] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 16.311 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 5.831 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.551 ±(99.9%) 0.008 ms/op
Iteration   1: 5.364 ±(99.9%) 0.009 ms/op
Iteration   2: 5.486 ±(99.9%) 0.011 ms/op
Iteration   3: 5.335 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.395 ±(99.9%) 1.457 ms/op [Average]
  (min, avg, max) = (5.335, 5.395, 5.486), stdev = 0.080
  CI (99.9%): [3.938, 6.853] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 19.040 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 6.921 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.717 ±(99.9%) 0.012 ms/op
Iteration   1: 5.743 ±(99.9%) 0.015 ms/op
Iteration   2: 5.578 ±(99.9%) 0.011 ms/op
Iteration   3: 5.582 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.635 ±(99.9%) 1.720 ms/op [Average]
  (min, avg, max) = (5.578, 5.635, 5.743), stdev = 0.094
  CI (99.9%): [3.915, 7.354] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 21.337 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 8.015 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.410 ±(99.9%) 0.013 ms/op
Iteration   1: 6.518 ±(99.9%) 0.014 ms/op
Iteration   2: 6.573 ±(99.9%) 0.017 ms/op
Iteration   3: 6.637 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.576 ±(99.9%) 1.083 ms/op [Average]
  (min, avg, max) = (6.518, 6.576, 6.637), stdev = 0.059
  CI (99.9%): [5.493, 7.659] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 19.971 ±(99.9%) 0.369 ms/op
# Warmup Iteration   2: 7.084 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 6.287 ±(99.9%) 0.032 ms/op
Iteration   1: 5.882 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.200 ms/op
                 createUser·p0.50:   5.489 ms/op
                 createUser·p0.90:   7.561 ms/op
                 createUser·p0.95:   8.765 ms/op
                 createUser·p0.99:   11.682 ms/op
                 createUser·p0.999:  25.096 ms/op
                 createUser·p0.9999: 28.461 ms/op
                 createUser·p1.00:   30.114 ms/op

Iteration   2: 5.540 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.171 ms/op
                 createUser·p0.50:   5.259 ms/op
                 createUser·p0.90:   6.717 ms/op
                 createUser·p0.95:   7.422 ms/op
                 createUser·p0.99:   10.535 ms/op
                 createUser·p0.999:  24.619 ms/op
                 createUser·p0.9999: 28.458 ms/op
                 createUser·p1.00:   29.229 ms/op

Iteration   3: 5.674 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   0.505 ms/op
                 createUser·p0.50:   5.358 ms/op
                 createUser·p0.90:   7.070 ms/op
                 createUser·p0.95:   8.077 ms/op
                 createUser·p0.99:   10.519 ms/op
                 createUser·p0.999:  18.186 ms/op
                 createUser·p0.9999: 30.787 ms/op
                 createUser·p1.00:   31.261 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 168415
  mean =      5.695 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 47514 
    [ 5.000,  7.500) = 108473 
    [ 7.500, 10.000) = 9757 
    [10.000, 12.500) = 1871 
    [12.500, 15.000) = 470 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.505 ms/op
     p(50.0000) =      5.358 ms/op
     p(90.0000) =      7.094 ms/op
     p(95.0000) =      8.167 ms/op
     p(99.0000) =     10.895 ms/op
     p(99.9000) =     20.021 ms/op
     p(99.9900) =     29.567 ms/op
     p(99.9990) =     31.261 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 16.276 ±(99.9%) 0.260 ms/op
# Warmup Iteration   2: 6.100 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.621 ±(99.9%) 0.021 ms/op
Iteration   1: 5.287 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.792 ms/op
                 existUser·p0.50:   5.014 ms/op
                 existUser·p0.90:   6.488 ms/op
                 existUser·p0.95:   7.643 ms/op
                 existUser·p0.99:   9.814 ms/op
                 existUser·p0.999:  13.297 ms/op
                 existUser·p0.9999: 28.310 ms/op
                 existUser·p1.00:   29.524 ms/op

Iteration   2: 5.571 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.593 ms/op
                 existUser·p0.50:   5.284 ms/op
                 existUser·p0.90:   6.808 ms/op
                 existUser·p0.95:   7.725 ms/op
                 existUser·p0.99:   10.830 ms/op
                 existUser·p0.999:  27.132 ms/op
                 existUser·p0.9999: 32.053 ms/op
                 existUser·p1.00:   35.848 ms/op

Iteration   3: 5.512 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.441 ms/op
                 existUser·p0.50:   5.169 ms/op
                 existUser·p0.90:   6.804 ms/op
                 existUser·p0.95:   7.971 ms/op
                 existUser·p0.99:   10.650 ms/op
                 existUser·p0.999:  30.766 ms/op
                 existUser·p0.9999: 33.764 ms/op
                 existUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 175877
  mean =      5.454 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 72464 
    [ 5.000,  7.500) = 92955 
    [ 7.500, 10.000) = 8209 
    [10.000, 12.500) = 1574 
    [12.500, 15.000) = 359 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 62 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.792 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      6.701 ms/op
     p(95.0000) =      7.799 ms/op
     p(99.0000) =     10.469 ms/op
     p(99.9000) =     21.729 ms/op
     p(99.9900) =     33.319 ms/op
     p(99.9990) =     35.600 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 17.310 ±(99.9%) 0.259 ms/op
# Warmup Iteration   2: 6.871 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.761 ±(99.9%) 0.022 ms/op
Iteration   1: 5.830 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.429 ms/op
                 getUser·p0.50:   5.399 ms/op
                 getUser·p0.90:   7.160 ms/op
                 getUser·p0.95:   8.700 ms/op
                 getUser·p0.99:   14.641 ms/op
                 getUser·p0.999:  25.741 ms/op
                 getUser·p0.9999: 29.181 ms/op
                 getUser·p1.00:   31.490 ms/op

Iteration   2: 5.643 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.327 ms/op
                 getUser·p0.50:   5.382 ms/op
                 getUser·p0.90:   6.857 ms/op
                 getUser·p0.95:   7.774 ms/op
                 getUser·p0.99:   10.109 ms/op
                 getUser·p0.999:  14.948 ms/op
                 getUser·p0.9999: 31.305 ms/op
                 getUser·p1.00:   33.128 ms/op

Iteration   3: 5.783 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.739 ms/op
                 getUser·p0.50:   5.431 ms/op
                 getUser·p0.90:   7.037 ms/op
                 getUser·p0.95:   8.298 ms/op
                 getUser·p0.99:   12.435 ms/op
                 getUser·p0.999:  29.018 ms/op
                 getUser·p0.9999: 38.108 ms/op
                 getUser·p1.00:   38.470 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 166800
  mean =      5.751 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 39924 
    [ 5.000,  7.500) = 114445 
    [ 7.500, 10.000) = 9167 
    [10.000, 12.500) = 1754 
    [12.500, 15.000) = 724 
    [15.000, 17.500) = 402 
    [17.500, 20.000) = 149 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.739 ms/op
     p(50.0000) =      5.399 ms/op
     p(90.0000) =      6.988 ms/op
     p(95.0000) =      8.290 ms/op
     p(99.0000) =     12.075 ms/op
     p(99.9000) =     24.091 ms/op
     p(99.9900) =     35.998 ms/op
     p(99.9990) =     38.382 ms/op
     p(99.9999) =     38.470 ms/op
    p(100.0000) =     38.470 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.384 ±(99.9%) 0.361 ms/op
# Warmup Iteration   2: 7.443 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 6.984 ±(99.9%) 0.032 ms/op
Iteration   1: 6.573 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.970 ms/op
                 listUser·p0.50:   6.152 ms/op
                 listUser·p0.90:   7.889 ms/op
                 listUser·p0.95:   9.355 ms/op
                 listUser·p0.99:   13.124 ms/op
                 listUser·p0.999:  28.280 ms/op
                 listUser·p0.9999: 32.163 ms/op
                 listUser·p1.00:   32.702 ms/op

Iteration   2: 6.737 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.892 ms/op
                 listUser·p0.50:   6.332 ms/op
                 listUser·p0.90:   8.118 ms/op
                 listUser·p0.95:   9.519 ms/op
                 listUser·p0.99:   12.951 ms/op
                 listUser·p0.999:  31.966 ms/op
                 listUser·p0.9999: 34.800 ms/op
                 listUser·p1.00:   35.193 ms/op

Iteration   3: 6.422 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.966 ms/op
                 listUser·p0.50:   6.128 ms/op
                 listUser·p0.90:   7.610 ms/op
                 listUser·p0.95:   8.473 ms/op
                 listUser·p0.99:   11.026 ms/op
                 listUser·p0.999:  22.696 ms/op
                 listUser·p0.9999: 32.311 ms/op
                 listUser·p1.00:   33.456 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 145932
  mean =      6.575 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 3462 
    [ 5.000,  7.500) = 123049 
    [ 7.500, 10.000) = 14697 
    [10.000, 12.500) = 3269 
    [12.500, 15.000) = 755 
    [15.000, 17.500) = 281 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 69 
    [32.500, 35.000) = 40 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.892 ms/op
     p(50.0000) =      6.201 ms/op
     p(90.0000) =      7.864 ms/op
     p(95.0000) =      9.077 ms/op
     p(99.0000) =     12.485 ms/op
     p(99.9000) =     28.644 ms/op
     p(99.9900) =     34.079 ms/op
     p(99.9990) =     35.042 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.553 ± 1.978  ops/ms
ClientPb.existUser                       thrpt       3   5.898 ± 0.395  ops/ms
ClientPb.getUser                         thrpt       3   5.664 ± 2.182  ops/ms
ClientPb.listUser                        thrpt       3   4.958 ± 3.712  ops/ms
ClientPb.createUser                       avgt       3   5.406 ± 1.467   ms/op
ClientPb.existUser                        avgt       3   5.395 ± 1.457   ms/op
ClientPb.getUser                          avgt       3   5.635 ± 1.720   ms/op
ClientPb.listUser                         avgt       3   6.576 ± 1.083   ms/op
ClientPb.createUser                     sample  168415   5.695 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.505           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.358           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.094           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.167           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.895           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.021           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.567           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.261           ms/op
ClientPb.existUser                      sample  175877   5.454 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.792           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.145           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.701           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.799           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.469           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.729           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.319           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.848           ms/op
ClientPb.getUser                        sample  166800   5.751 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.739           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.399           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.988           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.290           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.075           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.091           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.998           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.470           ms/op
ClientPb.listUser                       sample  145932   6.575 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.892           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.201           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.864           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.077           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.485           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.644           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.079           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.193           ms/op
