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
# Warmup Iteration   1: 2.162 ops/ms
# Warmup Iteration   2: 5.830 ops/ms
# Warmup Iteration   3: 8.449 ops/ms
Iteration   1: 8.779 ops/ms
Iteration   2: 9.193 ops/ms
Iteration   3: 9.370 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.114 ±(99.9%) 5.540 ops/ms [Average]
  (min, avg, max) = (8.779, 9.114, 9.370), stdev = 0.304
  CI (99.9%): [3.574, 14.654] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.143 ops/ms
# Warmup Iteration   2: 7.740 ops/ms
# Warmup Iteration   3: 8.914 ops/ms
Iteration   1: 9.339 ops/ms
Iteration   2: 9.395 ops/ms
Iteration   3: 9.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.439 ±(99.9%) 2.317 ops/ms [Average]
  (min, avg, max) = (9.339, 9.439, 9.582), stdev = 0.127
  CI (99.9%): [7.122, 11.755] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.131 ops/ms
# Warmup Iteration   2: 8.234 ops/ms
# Warmup Iteration   3: 8.938 ops/ms
Iteration   1: 8.975 ops/ms
Iteration   2: 8.917 ops/ms
Iteration   3: 9.195 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.029 ±(99.9%) 2.681 ops/ms [Average]
  (min, avg, max) = (8.917, 9.029, 9.195), stdev = 0.147
  CI (99.9%): [6.348, 11.710] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.642 ops/ms
# Warmup Iteration   2: 7.182 ops/ms
# Warmup Iteration   3: 7.491 ops/ms
Iteration   1: 7.858 ops/ms
Iteration   2: 7.815 ops/ms
Iteration   3: 7.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.865 ±(99.9%) 0.988 ops/ms [Average]
  (min, avg, max) = (7.815, 7.865, 7.922), stdev = 0.054
  CI (99.9%): [6.877, 8.853] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.698 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.993 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.751 ±(99.9%) 0.006 ms/op
Iteration   1: 3.508 ±(99.9%) 0.010 ms/op
Iteration   2: 3.471 ±(99.9%) 0.004 ms/op
Iteration   3: 3.450 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.476 ±(99.9%) 0.538 ms/op [Average]
  (min, avg, max) = (3.450, 3.476, 3.508), stdev = 0.029
  CI (99.9%): [2.938, 4.014] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.619 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.841 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.509 ±(99.9%) 0.004 ms/op
Iteration   1: 3.373 ±(99.9%) 0.004 ms/op
Iteration   2: 3.457 ±(99.9%) 0.004 ms/op
Iteration   3: 3.505 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.445 ±(99.9%) 1.222 ms/op [Average]
  (min, avg, max) = (3.373, 3.445, 3.505), stdev = 0.067
  CI (99.9%): [2.223, 4.667] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.088 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.984 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.659 ±(99.9%) 0.006 ms/op
Iteration   1: 3.449 ±(99.9%) 0.004 ms/op
Iteration   2: 3.510 ±(99.9%) 0.004 ms/op
Iteration   3: 3.589 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.516 ±(99.9%) 1.278 ms/op [Average]
  (min, avg, max) = (3.449, 3.516, 3.589), stdev = 0.070
  CI (99.9%): [2.238, 4.794] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 12.343 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.629 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.171 ±(99.9%) 0.008 ms/op
Iteration   1: 4.107 ±(99.9%) 0.007 ms/op
Iteration   2: 4.101 ±(99.9%) 0.006 ms/op
Iteration   3: 4.124 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.111 ±(99.9%) 0.213 ms/op [Average]
  (min, avg, max) = (4.101, 4.111, 4.124), stdev = 0.012
  CI (99.9%): [3.897, 4.324] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.540 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.021 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.645 ±(99.9%) 0.011 ms/op
Iteration   1: 3.553 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.186 ms/op
                 createUser·p0.50:   3.453 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.465 ms/op
                 createUser·p0.99:   7.143 ms/op
                 createUser·p0.999:  19.463 ms/op
                 createUser·p0.9999: 23.429 ms/op
                 createUser·p1.00:   24.052 ms/op

Iteration   2: 3.596 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.462 ms/op
                 createUser·p0.50:   3.490 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.735 ms/op
                 createUser·p0.99:   6.849 ms/op
                 createUser·p0.999:  21.400 ms/op
                 createUser·p0.9999: 23.560 ms/op
                 createUser·p1.00:   23.724 ms/op

Iteration   3: 3.644 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.180 ms/op
                 createUser·p0.50:   3.518 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   4.743 ms/op
                 createUser·p0.99:   6.721 ms/op
                 createUser·p0.999:  17.416 ms/op
                 createUser·p0.9999: 27.449 ms/op
                 createUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 266683
  mean =      3.597 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8066 
    [ 2.500,  5.000) = 248072 
    [ 5.000,  7.500) = 8518 
    [ 7.500, 10.000) = 1380 
    [10.000, 12.500) = 269 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      3.490 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     18.819 ms/op
     p(99.9900) =     26.629 ms/op
     p(99.9990) =     27.984 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


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
# Warmup Iteration   1: 9.899 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.798 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.494 ±(99.9%) 0.010 ms/op
Iteration   1: 3.518 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.567 ms/op
                 existUser·p0.50:   3.379 ms/op
                 existUser·p0.90:   3.949 ms/op
                 existUser·p0.95:   4.547 ms/op
                 existUser·p0.99:   7.832 ms/op
                 existUser·p0.999:  20.481 ms/op
                 existUser·p0.9999: 23.983 ms/op
                 existUser·p1.00:   24.642 ms/op

Iteration   2: 3.438 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.661 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   6.291 ms/op
                 existUser·p0.999:  21.120 ms/op
                 existUser·p0.9999: 30.331 ms/op
                 existUser·p1.00:   30.999 ms/op

Iteration   3: 3.481 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.141 ms/op
                 existUser·p0.50:   3.391 ms/op
                 existUser·p0.90:   3.895 ms/op
                 existUser·p0.95:   4.579 ms/op
                 existUser·p0.99:   6.267 ms/op
                 existUser·p0.999:  9.798 ms/op
                 existUser·p0.9999: 27.558 ms/op
                 existUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 275768
  mean =      3.479 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13508 
    [ 2.500,  5.000) = 252907 
    [ 5.000,  7.500) = 7472 
    [ 7.500, 10.000) = 1315 
    [10.000, 12.500) = 291 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.567 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      6.671 ms/op
     p(99.9000) =     12.462 ms/op
     p(99.9900) =     28.334 ms/op
     p(99.9990) =     30.966 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


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
# Warmup Iteration   1: 8.888 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.863 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.607 ±(99.9%) 0.012 ms/op
Iteration   1: 3.564 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.624 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.716 ms/op
                 getUser·p0.99:   7.471 ms/op
                 getUser·p0.999:  20.925 ms/op
                 getUser·p0.9999: 23.136 ms/op
                 getUser·p1.00:   24.216 ms/op

Iteration   2: 3.509 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.602 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   6.390 ms/op
                 getUser·p0.999:  22.734 ms/op
                 getUser·p0.9999: 30.245 ms/op
                 getUser·p1.00:   30.900 ms/op

Iteration   3: 3.571 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.481 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   4.137 ms/op
                 getUser·p0.95:   4.801 ms/op
                 getUser·p0.99:   6.852 ms/op
                 getUser·p0.999:  23.345 ms/op
                 getUser·p0.9999: 26.362 ms/op
                 getUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270480
  mean =      3.548 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9300 
    [ 2.500,  5.000) = 250900 
    [ 5.000,  7.500) = 8211 
    [ 7.500, 10.000) = 1618 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 151 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.481 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     21.349 ms/op
     p(99.9900) =     28.636 ms/op
     p(99.9990) =     30.450 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


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
# Warmup Iteration   1: 10.611 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.730 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.252 ±(99.9%) 0.015 ms/op
Iteration   1: 4.255 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.884 ms/op
                 listUser·p0.50:   4.067 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.226 ms/op
                 listUser·p0.99:   8.633 ms/op
                 listUser·p0.999:  24.536 ms/op
                 listUser·p0.9999: 26.965 ms/op
                 listUser·p1.00:   28.180 ms/op

Iteration   2: 4.131 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.339 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   5.104 ms/op
                 listUser·p0.99:   8.552 ms/op
                 listUser·p0.999:  15.909 ms/op
                 listUser·p0.9999: 20.775 ms/op
                 listUser·p1.00:   21.758 ms/op

Iteration   3: 4.212 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.251 ms/op
                 listUser·p0.99:   8.345 ms/op
                 listUser·p0.999:  16.696 ms/op
                 listUser·p0.9999: 21.332 ms/op
                 listUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 228554
  mean =      4.198 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 215467 
    [ 5.000,  7.500) = 9016 
    [ 7.500, 10.000) = 2978 
    [10.000, 12.500) = 482 
    [12.500, 15.000) = 187 
    [15.000, 17.500) = 195 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 62 

  Percentiles, ms/op:
      p(0.0000) =      1.884 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.210 ms/op
     p(99.0000) =      8.487 ms/op
     p(99.9000) =     17.039 ms/op
     p(99.9900) =     26.182 ms/op
     p(99.9990) =     27.656 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.114 ± 5.540  ops/ms
ClientPb.existUser                       thrpt       3   9.439 ± 2.317  ops/ms
ClientPb.getUser                         thrpt       3   9.029 ± 2.681  ops/ms
ClientPb.listUser                        thrpt       3   7.865 ± 0.988  ops/ms
ClientPb.createUser                       avgt       3   3.476 ± 0.538   ms/op
ClientPb.existUser                        avgt       3   3.445 ± 1.222   ms/op
ClientPb.getUser                          avgt       3   3.516 ± 1.278   ms/op
ClientPb.listUser                         avgt       3   4.111 ± 0.213   ms/op
ClientPb.createUser                     sample  266683   3.597 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.180           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.490           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.088           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.669           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.881           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.819           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.629           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.082           ms/op
ClientPb.existUser                      sample  275768   3.479 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.567           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.375           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.863           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.506           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.671           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.462           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.334           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.999           ms/op
ClientPb.getUser                        sample  270480   3.548 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.481           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.387           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.096           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.588           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.922           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.349           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.636           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.900           ms/op
ClientPb.listUser                       sample  228554   4.198 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.884           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.969           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.210           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.487           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.039           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.182           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.180           ms/op
