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
# Warmup Iteration   1: 2.102 ops/ms
# Warmup Iteration   2: 4.955 ops/ms
# Warmup Iteration   3: 8.300 ops/ms
Iteration   1: 9.101 ops/ms
Iteration   2: 9.534 ops/ms
Iteration   3: 9.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.325 ±(99.9%) 3.949 ops/ms [Average]
  (min, avg, max) = (9.101, 9.325, 9.534), stdev = 0.216
  CI (99.9%): [5.376, 13.274] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.867 ops/ms
# Warmup Iteration   2: 8.450 ops/ms
# Warmup Iteration   3: 9.447 ops/ms
Iteration   1: 9.757 ops/ms
Iteration   2: 9.771 ops/ms
Iteration   3: 9.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.731 ±(99.9%) 1.067 ops/ms [Average]
  (min, avg, max) = (9.664, 9.731, 9.771), stdev = 0.059
  CI (99.9%): [8.663, 10.798] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.651 ops/ms
# Warmup Iteration   2: 7.746 ops/ms
# Warmup Iteration   3: 9.303 ops/ms
Iteration   1: 9.197 ops/ms
Iteration   2: 9.219 ops/ms
Iteration   3: 8.784 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.066 ±(99.9%) 4.468 ops/ms [Average]
  (min, avg, max) = (8.784, 9.066, 9.219), stdev = 0.245
  CI (99.9%): [4.599, 13.534] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.719 ops/ms
# Warmup Iteration   2: 7.389 ops/ms
# Warmup Iteration   3: 7.896 ops/ms
Iteration   1: 7.876 ops/ms
Iteration   2: 8.137 ops/ms
Iteration   3: 7.910 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.974 ±(99.9%) 2.584 ops/ms [Average]
  (min, avg, max) = (7.876, 7.974, 8.137), stdev = 0.142
  CI (99.9%): [5.390, 10.559] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.698 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.810 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.734 ±(99.9%) 0.004 ms/op
Iteration   1: 3.511 ±(99.9%) 0.009 ms/op
Iteration   2: 3.519 ±(99.9%) 0.006 ms/op
Iteration   3: 3.602 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.544 ±(99.9%) 0.919 ms/op [Average]
  (min, avg, max) = (3.511, 3.544, 3.602), stdev = 0.050
  CI (99.9%): [2.625, 4.462] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 9.436 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.666 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.334 ±(99.9%) 0.005 ms/op
Iteration   1: 3.344 ±(99.9%) 0.009 ms/op
Iteration   2: 3.416 ±(99.9%) 0.003 ms/op
Iteration   3: 3.244 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.335 ±(99.9%) 1.579 ms/op [Average]
  (min, avg, max) = (3.244, 3.335, 3.416), stdev = 0.087
  CI (99.9%): [1.755, 4.914] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.874 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.667 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.539 ±(99.9%) 0.004 ms/op
Iteration   1: 3.516 ±(99.9%) 0.003 ms/op
Iteration   2: 3.517 ±(99.9%) 0.003 ms/op
Iteration   3: 3.518 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.517 ±(99.9%) 0.012 ms/op [Average]
  (min, avg, max) = (3.516, 3.517, 3.518), stdev = 0.001
  CI (99.9%): [3.505, 3.529] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.666 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.395 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.102 ±(99.9%) 0.005 ms/op
Iteration   1: 4.056 ±(99.9%) 0.009 ms/op
Iteration   2: 3.955 ±(99.9%) 0.007 ms/op
Iteration   3: 4.058 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.023 ±(99.9%) 1.074 ms/op [Average]
  (min, avg, max) = (3.955, 4.023, 4.058), stdev = 0.059
  CI (99.9%): [2.949, 5.097] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.543 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.083 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.424 ±(99.9%) 0.010 ms/op
Iteration   1: 3.406 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.343 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   6.699 ms/op
                 createUser·p0.999:  20.447 ms/op
                 createUser·p0.9999: 23.063 ms/op
                 createUser·p1.00:   23.560 ms/op

Iteration   2: 3.469 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.618 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   6.750 ms/op
                 createUser·p0.999:  21.345 ms/op
                 createUser·p0.9999: 24.117 ms/op
                 createUser·p1.00:   24.805 ms/op

Iteration   3: 3.534 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.139 ms/op
                 createUser·p0.50:   3.457 ms/op
                 createUser·p0.90:   4.071 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  16.887 ms/op
                 createUser·p0.9999: 25.264 ms/op
                 createUser·p1.00:   25.526 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276724
  mean =      3.469 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5721 
    [ 2.500,  5.000) = 262581 
    [ 5.000,  7.500) = 6895 
    [ 7.500, 10.000) = 856 
    [10.000, 12.500) = 306 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.139 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.488 ms/op
     p(99.9000) =     17.108 ms/op
     p(99.9900) =     24.160 ms/op
     p(99.9990) =     25.468 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


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
# Warmup Iteration   1: 8.626 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.617 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.509 ±(99.9%) 0.009 ms/op
Iteration   1: 3.471 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.294 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   4.002 ms/op
                 existUser·p0.95:   4.833 ms/op
                 existUser·p0.99:   6.898 ms/op
                 existUser·p0.999:  19.492 ms/op
                 existUser·p0.9999: 22.734 ms/op
                 existUser·p1.00:   23.658 ms/op

Iteration   2: 3.346 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.354 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   6.701 ms/op
                 existUser·p0.999:  21.543 ms/op
                 existUser·p0.9999: 25.536 ms/op
                 existUser·p1.00:   26.116 ms/op

Iteration   3: 3.445 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.567 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   3.949 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   6.234 ms/op
                 existUser·p0.999:  9.781 ms/op
                 existUser·p0.9999: 27.431 ms/op
                 existUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 280731
  mean =      3.420 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13377 
    [ 2.500,  5.000) = 257654 
    [ 5.000,  7.500) = 8255 
    [ 7.500, 10.000) = 1077 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 67 

  Percentiles, ms/op:
      p(0.0000) =      1.294 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     12.763 ms/op
     p(99.9900) =     26.572 ms/op
     p(99.9990) =     28.055 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


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
# Warmup Iteration   1: 10.161 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.805 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.610 ±(99.9%) 0.013 ms/op
Iteration   1: 3.633 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.305 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   4.309 ms/op
                 getUser·p0.95:   4.948 ms/op
                 getUser·p0.99:   6.799 ms/op
                 getUser·p0.999:  20.444 ms/op
                 getUser·p0.9999: 33.632 ms/op
                 getUser·p1.00:   34.341 ms/op

Iteration   2: 3.351 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.622 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.905 ms/op
                 getUser·p0.99:   6.026 ms/op
                 getUser·p0.999:  18.434 ms/op
                 getUser·p0.9999: 23.230 ms/op
                 getUser·p1.00:   23.953 ms/op

Iteration   3: 3.534 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.786 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   4.121 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   7.094 ms/op
                 getUser·p0.999:  11.575 ms/op
                 getUser·p0.9999: 26.540 ms/op
                 getUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274045
  mean =      3.502 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9528 
    [ 2.500,  5.000) = 253832 
    [ 5.000,  7.500) = 8987 
    [ 7.500, 10.000) = 1282 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     12.517 ms/op
     p(99.9900) =     31.654 ms/op
     p(99.9990) =     34.341 ms/op
     p(99.9999) =     34.341 ms/op
    p(100.0000) =     34.341 ms/op


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
# Warmup Iteration   1: 10.960 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.451 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.343 ±(99.9%) 0.017 ms/op
Iteration   1: 4.062 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.128 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   7.947 ms/op
                 listUser·p0.999:  21.090 ms/op
                 listUser·p0.9999: 24.871 ms/op
                 listUser·p1.00:   25.788 ms/op

Iteration   2: 4.093 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.210 ms/op
                 listUser·p0.99:   8.069 ms/op
                 listUser·p0.999:  14.451 ms/op
                 listUser·p0.9999: 19.005 ms/op
                 listUser·p1.00:   19.071 ms/op

Iteration   3: 4.058 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.935 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.907 ms/op
                 listUser·p0.99:   8.028 ms/op
                 listUser·p0.999:  14.533 ms/op
                 listUser·p0.9999: 16.048 ms/op
                 listUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235610
  mean =      4.071 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 223340 
    [ 5.000,  7.500) = 9279 
    [ 7.500, 10.000) = 1997 
    [10.000, 12.500) = 429 
    [12.500, 15.000) = 262 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.128 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      8.028 ms/op
     p(99.9000) =     15.761 ms/op
     p(99.9900) =     23.341 ms/op
     p(99.9990) =     25.002 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.325 ± 3.949  ops/ms
ClientPb.existUser                       thrpt       3   9.731 ± 1.067  ops/ms
ClientPb.getUser                         thrpt       3   9.066 ± 4.468  ops/ms
ClientPb.listUser                        thrpt       3   7.974 ± 2.584  ops/ms
ClientPb.createUser                       avgt       3   3.544 ± 0.919   ms/op
ClientPb.existUser                        avgt       3   3.335 ± 1.579   ms/op
ClientPb.getUser                          avgt       3   3.517 ± 0.012   ms/op
ClientPb.listUser                         avgt       3   4.023 ± 1.074   ms/op
ClientPb.createUser                     sample  276724   3.469 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.139           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.342           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.293           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.488           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.108           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.160           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.526           ms/op
ClientPb.existUser                      sample  280731   3.420 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.294           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.297           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.867           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.350           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.693           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.763           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.572           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.606           ms/op
ClientPb.getUser                        sample  274045   3.502 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.786           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.334           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.579           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.816           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.517           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.654           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.341           ms/op
ClientPb.listUser                       sample  235610   4.071 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.128           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.932           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.038           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.028           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.761           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.341           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.788           ms/op
