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
# Warmup Iteration   1: 2.100 ops/ms
# Warmup Iteration   2: 5.225 ops/ms
# Warmup Iteration   3: 8.351 ops/ms
Iteration   1: 8.984 ops/ms
Iteration   2: 9.188 ops/ms
Iteration   3: 9.243 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.138 ±(99.9%) 2.495 ops/ms [Average]
  (min, avg, max) = (8.984, 9.138, 9.243), stdev = 0.137
  CI (99.9%): [6.644, 11.633] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.216 ops/ms
# Warmup Iteration   2: 8.291 ops/ms
# Warmup Iteration   3: 9.181 ops/ms
Iteration   1: 9.284 ops/ms
Iteration   2: 9.559 ops/ms
Iteration   3: 9.583 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.475 ±(99.9%) 3.040 ops/ms [Average]
  (min, avg, max) = (9.284, 9.475, 9.583), stdev = 0.167
  CI (99.9%): [6.435, 12.516] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.643 ops/ms
# Warmup Iteration   2: 8.005 ops/ms
# Warmup Iteration   3: 9.013 ops/ms
Iteration   1: 9.081 ops/ms
Iteration   2: 9.182 ops/ms
Iteration   3: 9.240 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.168 ±(99.9%) 1.473 ops/ms [Average]
  (min, avg, max) = (9.081, 9.168, 9.240), stdev = 0.081
  CI (99.9%): [7.694, 10.641] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.595 ops/ms
# Warmup Iteration   2: 7.021 ops/ms
# Warmup Iteration   3: 7.396 ops/ms
Iteration   1: 7.586 ops/ms
Iteration   2: 7.456 ops/ms
Iteration   3: 7.958 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.666 ±(99.9%) 4.753 ops/ms [Average]
  (min, avg, max) = (7.456, 7.666, 7.958), stdev = 0.261
  CI (99.9%): [2.913, 12.419] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 10.774 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.972 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.642 ±(99.9%) 0.004 ms/op
Iteration   1: 3.433 ±(99.9%) 0.008 ms/op
Iteration   2: 3.577 ±(99.9%) 0.003 ms/op
Iteration   3: 3.572 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.527 ±(99.9%) 1.489 ms/op [Average]
  (min, avg, max) = (3.433, 3.527, 3.577), stdev = 0.082
  CI (99.9%): [2.038, 5.016] (assumes normal distribution)


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
# Warmup Iteration   1: 9.997 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.651 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.343 ±(99.9%) 0.004 ms/op
Iteration   1: 3.412 ±(99.9%) 0.002 ms/op
Iteration   2: 3.307 ±(99.9%) 0.003 ms/op
Iteration   3: 3.314 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.344 ±(99.9%) 1.069 ms/op [Average]
  (min, avg, max) = (3.307, 3.344, 3.412), stdev = 0.059
  CI (99.9%): [2.276, 4.413] (assumes normal distribution)


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
# Warmup Iteration   1: 9.552 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.724 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.506 ±(99.9%) 0.003 ms/op
Iteration   1: 3.405 ±(99.9%) 0.004 ms/op
Iteration   2: 3.452 ±(99.9%) 0.004 ms/op
Iteration   3: 3.435 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.431 ±(99.9%) 0.440 ms/op [Average]
  (min, avg, max) = (3.405, 3.431, 3.452), stdev = 0.024
  CI (99.9%): [2.991, 3.871] (assumes normal distribution)


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
# Warmup Iteration   1: 10.662 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.384 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.226 ±(99.9%) 0.008 ms/op
Iteration   1: 4.098 ±(99.9%) 0.006 ms/op
Iteration   2: 4.073 ±(99.9%) 0.006 ms/op
Iteration   3: 4.071 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.081 ±(99.9%) 0.282 ms/op [Average]
  (min, avg, max) = (4.071, 4.081, 4.098), stdev = 0.015
  CI (99.9%): [3.798, 4.363] (assumes normal distribution)


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
# Warmup Iteration   1: 9.876 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 4.215 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.633 ±(99.9%) 0.011 ms/op
Iteration   1: 3.570 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.731 ms/op
                 createUser·p0.50:   3.469 ms/op
                 createUser·p0.90:   4.047 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  20.655 ms/op
                 createUser·p0.9999: 31.524 ms/op
                 createUser·p1.00:   31.949 ms/op

Iteration   2: 3.561 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.016 ms/op
                 createUser·p0.50:   3.531 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  20.942 ms/op
                 createUser·p0.9999: 24.806 ms/op
                 createUser·p1.00:   26.280 ms/op

Iteration   3: 3.602 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.722 ms/op
                 createUser·p0.50:   3.531 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   6.308 ms/op
                 createUser·p0.999:  20.190 ms/op
                 createUser·p0.9999: 28.846 ms/op
                 createUser·p1.00:   29.360 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 268512
  mean =      3.578 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2584 
    [ 2.500,  5.000) = 260806 
    [ 5.000,  7.500) = 3960 
    [ 7.500, 10.000) = 439 
    [10.000, 12.500) = 283 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.016 ms/op
     p(50.0000) =      3.514 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     20.709 ms/op
     p(99.9900) =     30.812 ms/op
     p(99.9990) =     31.785 ms/op
     p(99.9999) =     31.949 ms/op
    p(100.0000) =     31.949 ms/op


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
# Warmup Iteration   1: 9.198 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.623 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.330 ±(99.9%) 0.007 ms/op
Iteration   1: 3.392 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.630 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   3.994 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  19.753 ms/op
                 existUser·p0.9999: 22.217 ms/op
                 existUser·p1.00:   23.101 ms/op

Iteration   2: 3.375 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.126 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   3.977 ms/op
                 existUser·p0.99:   6.136 ms/op
                 existUser·p0.999:  21.627 ms/op
                 existUser·p0.9999: 26.035 ms/op
                 existUser·p1.00:   26.673 ms/op

Iteration   3: 3.350 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.554 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  20.395 ms/op
                 existUser·p0.9999: 26.572 ms/op
                 existUser·p1.00:   28.049 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284476
  mean =      3.372 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3539 
    [ 2.500,  5.000) = 276214 
    [ 5.000,  7.500) = 3754 
    [ 7.500, 10.000) = 366 
    [10.000, 12.500) = 237 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 139 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 68 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     20.155 ms/op
     p(99.9900) =     25.872 ms/op
     p(99.9990) =     27.730 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


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
# Warmup Iteration   1: 8.576 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.733 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.539 ±(99.9%) 0.010 ms/op
Iteration   1: 3.559 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.722 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.964 ms/op
                 getUser·p0.99:   7.340 ms/op
                 getUser·p0.999:  19.169 ms/op
                 getUser·p0.9999: 21.693 ms/op
                 getUser·p1.00:   22.348 ms/op

Iteration   2: 3.442 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.043 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   5.431 ms/op
                 getUser·p0.999:  20.459 ms/op
                 getUser·p0.9999: 23.518 ms/op
                 getUser·p1.00:   25.166 ms/op

Iteration   3: 3.511 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.804 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   3.932 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   6.516 ms/op
                 getUser·p0.999:  10.958 ms/op
                 getUser·p0.9999: 25.457 ms/op
                 getUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273939
  mean =      3.503 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3253 
    [ 2.500,  5.000) = 262702 
    [ 5.000,  7.500) = 6455 
    [ 7.500, 10.000) = 943 
    [10.000, 12.500) = 265 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.043 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     18.649 ms/op
     p(99.9900) =     24.334 ms/op
     p(99.9990) =     25.576 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


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
# Warmup Iteration   1: 10.956 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.399 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.188 ±(99.9%) 0.012 ms/op
Iteration   1: 4.190 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.273 ms/op
                 listUser·p0.50:   4.039 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   7.471 ms/op
                 listUser·p0.999:  20.600 ms/op
                 listUser·p0.9999: 24.553 ms/op
                 listUser·p1.00:   25.166 ms/op

Iteration   2: 4.243 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.720 ms/op
                 listUser·p0.50:   4.129 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   4.990 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  16.099 ms/op
                 listUser·p0.9999: 17.990 ms/op
                 listUser·p1.00:   18.678 ms/op

Iteration   3: 4.024 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.939 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   6.119 ms/op
                 listUser·p0.999:  13.713 ms/op
                 listUser·p0.9999: 16.204 ms/op
                 listUser·p1.00:   16.253 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 231213
  mean =      4.150 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 222310 
    [ 5.000,  7.500) = 7199 
    [ 7.500, 10.000) = 850 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 323 
    [15.000, 17.500) = 217 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.720 ms/op
     p(50.0000) =      4.035 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     16.204 ms/op
     p(99.9900) =     23.065 ms/op
     p(99.9990) =     25.006 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.138 ± 2.495  ops/ms
ClientPb.existUser                       thrpt       3   9.475 ± 3.040  ops/ms
ClientPb.getUser                         thrpt       3   9.168 ± 1.473  ops/ms
ClientPb.listUser                        thrpt       3   7.666 ± 4.753  ops/ms
ClientPb.createUser                       avgt       3   3.527 ± 1.489   ms/op
ClientPb.existUser                        avgt       3   3.344 ± 1.069   ms/op
ClientPb.getUser                          avgt       3   3.431 ± 0.440   ms/op
ClientPb.listUser                         avgt       3   4.081 ± 0.282   ms/op
ClientPb.createUser                     sample  268512   3.578 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.016           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.514           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.973           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.268           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.956           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.709           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.812           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.949           ms/op
ClientPb.existUser                      sample  284476   3.372 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.126           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.973           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.571           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.155           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.872           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.049           ms/op
ClientPb.getUser                        sample  273939   3.503 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.043           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.359           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.840           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.649           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.334           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.756           ms/op
ClientPb.listUser                       sample  231213   4.150 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.720           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.035           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.841           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.102           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.204           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.065           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.166           ms/op
