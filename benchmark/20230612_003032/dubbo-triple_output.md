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
# Warmup Iteration   1: 2.187 ops/ms
# Warmup Iteration   2: 4.671 ops/ms
# Warmup Iteration   3: 8.743 ops/ms
Iteration   1: 9.050 ops/ms
Iteration   2: 9.291 ops/ms
Iteration   3: 9.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.314 ±(99.9%) 5.047 ops/ms [Average]
  (min, avg, max) = (9.050, 9.314, 9.602), stdev = 0.277
  CI (99.9%): [4.268, 14.361] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.961 ops/ms
# Warmup Iteration   2: 8.883 ops/ms
# Warmup Iteration   3: 9.879 ops/ms
Iteration   1: 9.847 ops/ms
Iteration   2: 9.840 ops/ms
Iteration   3: 9.867 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.852 ±(99.9%) 0.253 ops/ms [Average]
  (min, avg, max) = (9.840, 9.852, 9.867), stdev = 0.014
  CI (99.9%): [9.598, 10.105] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.573 ops/ms
# Warmup Iteration   2: 7.873 ops/ms
# Warmup Iteration   3: 8.947 ops/ms
Iteration   1: 8.870 ops/ms
Iteration   2: 9.261 ops/ms
Iteration   3: 9.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.201 ±(99.9%) 5.568 ops/ms [Average]
  (min, avg, max) = (8.870, 9.201, 9.472), stdev = 0.305
  CI (99.9%): [3.633, 14.769] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.591 ops/ms
# Warmup Iteration   2: 7.003 ops/ms
# Warmup Iteration   3: 7.851 ops/ms
Iteration   1: 7.983 ops/ms
Iteration   2: 8.063 ops/ms
Iteration   3: 8.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.030 ±(99.9%) 0.757 ops/ms [Average]
  (min, avg, max) = (7.983, 8.030, 8.063), stdev = 0.041
  CI (99.9%): [7.273, 8.787] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 9.543 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.682 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.532 ±(99.9%) 0.008 ms/op
Iteration   1: 3.445 ±(99.9%) 0.007 ms/op
Iteration   2: 3.401 ±(99.9%) 0.007 ms/op
Iteration   3: 3.443 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.430 ±(99.9%) 0.454 ms/op [Average]
  (min, avg, max) = (3.401, 3.430, 3.445), stdev = 0.025
  CI (99.9%): [2.975, 3.884] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 8.496 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.634 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.487 ±(99.9%) 0.005 ms/op
Iteration   1: 3.342 ±(99.9%) 0.006 ms/op
Iteration   2: 3.305 ±(99.9%) 0.011 ms/op
Iteration   3: 3.274 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.307 ±(99.9%) 0.623 ms/op [Average]
  (min, avg, max) = (3.274, 3.307, 3.342), stdev = 0.034
  CI (99.9%): [2.685, 3.930] (assumes normal distribution)


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
# Warmup Iteration   1: 8.740 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.542 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.531 ±(99.9%) 0.003 ms/op
Iteration   1: 3.458 ±(99.9%) 0.004 ms/op
Iteration   2: 3.512 ±(99.9%) 0.006 ms/op
Iteration   3: 3.326 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.432 ±(99.9%) 1.747 ms/op [Average]
  (min, avg, max) = (3.326, 3.432, 3.512), stdev = 0.096
  CI (99.9%): [1.685, 5.178] (assumes normal distribution)


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
# Warmup Iteration   1: 9.959 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.453 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.968 ±(99.9%) 0.009 ms/op
Iteration   1: 3.944 ±(99.9%) 0.007 ms/op
Iteration   2: 3.875 ±(99.9%) 0.013 ms/op
Iteration   3: 3.945 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.921 ±(99.9%) 0.725 ms/op [Average]
  (min, avg, max) = (3.875, 3.921, 3.945), stdev = 0.040
  CI (99.9%): [3.196, 4.647] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 9.979 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.080 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.464 ±(99.9%) 0.011 ms/op
Iteration   1: 3.434 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.358 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.999 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   5.980 ms/op
                 createUser·p0.999:  21.253 ms/op
                 createUser·p0.9999: 23.626 ms/op
                 createUser·p1.00:   24.969 ms/op

Iteration   2: 3.401 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.856 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  23.134 ms/op
                 createUser·p0.9999: 28.475 ms/op
                 createUser·p1.00:   29.000 ms/op

Iteration   3: 3.424 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.604 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   6.226 ms/op
                 createUser·p0.999:  20.005 ms/op
                 createUser·p0.9999: 26.755 ms/op
                 createUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280716
  mean =      3.420 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11941 
    [ 2.500,  5.000) = 261312 
    [ 5.000,  7.500) = 6359 
    [ 7.500, 10.000) = 647 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =     20.283 ms/op
     p(99.9900) =     27.949 ms/op
     p(99.9990) =     28.735 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


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
# Warmup Iteration   1: 8.366 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.591 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.462 ±(99.9%) 0.009 ms/op
Iteration   1: 3.411 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.606 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   4.125 ms/op
                 existUser·p0.99:   6.319 ms/op
                 existUser·p0.999:  21.627 ms/op
                 existUser·p0.9999: 24.662 ms/op
                 existUser·p1.00:   25.756 ms/op

Iteration   2: 3.336 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.751 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   4.014 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  23.337 ms/op
                 existUser·p0.9999: 28.397 ms/op
                 existUser·p1.00:   28.934 ms/op

Iteration   3: 3.377 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.708 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   4.432 ms/op
                 existUser·p0.99:   6.480 ms/op
                 existUser·p0.999:  19.641 ms/op
                 existUser·p0.9999: 27.805 ms/op
                 existUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284325
  mean =      3.375 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5960 
    [ 2.500,  5.000) = 270562 
    [ 5.000,  7.500) = 6550 
    [ 7.500, 10.000) = 695 
    [10.000, 12.500) = 218 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 100 

  Percentiles, ms/op:
      p(0.0000) =      1.606 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      6.218 ms/op
     p(99.9000) =     19.793 ms/op
     p(99.9900) =     27.698 ms/op
     p(99.9990) =     28.682 ms/op
     p(99.9999) =     28.934 ms/op
    p(100.0000) =     28.934 ms/op


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
# Warmup Iteration   1: 9.071 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.003 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.499 ±(99.9%) 0.011 ms/op
Iteration   1: 3.368 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.843 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   5.816 ms/op
                 getUser·p0.999:  11.076 ms/op
                 getUser·p0.9999: 24.068 ms/op
                 getUser·p1.00:   24.740 ms/op

Iteration   2: 3.562 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.194 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   7.274 ms/op
                 getUser·p0.999:  10.945 ms/op
                 getUser·p0.9999: 25.661 ms/op
                 getUser·p1.00:   26.903 ms/op

Iteration   3: 3.450 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.452 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   6.070 ms/op
                 getUser·p0.999:  21.070 ms/op
                 getUser·p0.9999: 27.532 ms/op
                 getUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277346
  mean =      3.458 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13158 
    [ 2.500,  5.000) = 256532 
    [ 5.000,  7.500) = 6296 
    [ 7.500, 10.000) = 967 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      1.194 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     11.070 ms/op
     p(99.9900) =     26.437 ms/op
     p(99.9990) =     28.057 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


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
# Warmup Iteration   1: 11.264 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.464 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.120 ±(99.9%) 0.015 ms/op
Iteration   1: 4.001 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.507 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   8.372 ms/op
                 listUser·p0.999:  17.858 ms/op
                 listUser·p0.9999: 24.019 ms/op
                 listUser·p1.00:   24.510 ms/op

Iteration   2: 4.110 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.163 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   7.610 ms/op
                 listUser·p0.999:  19.628 ms/op
                 listUser·p0.9999: 23.757 ms/op
                 listUser·p1.00:   24.281 ms/op

Iteration   3: 3.979 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.042 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.090 ms/op
                 listUser·p0.999:  15.219 ms/op
                 listUser·p0.9999: 20.216 ms/op
                 listUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238230
  mean =      4.029 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 68 
    [ 2.500,  5.000) = 228449 
    [ 5.000,  7.500) = 7140 
    [ 7.500, 10.000) = 1696 
    [10.000, 12.500) = 290 
    [12.500, 15.000) = 171 
    [15.000, 17.500) = 172 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.507 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      7.717 ms/op
     p(99.9000) =     17.720 ms/op
     p(99.9900) =     23.730 ms/op
     p(99.9990) =     24.478 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.314 ± 5.047  ops/ms
ClientPb.existUser                       thrpt       3   9.852 ± 0.253  ops/ms
ClientPb.getUser                         thrpt       3   9.201 ± 5.568  ops/ms
ClientPb.listUser                        thrpt       3   8.030 ± 0.757  ops/ms
ClientPb.createUser                       avgt       3   3.430 ± 0.454   ms/op
ClientPb.existUser                        avgt       3   3.307 ± 0.623   ms/op
ClientPb.getUser                          avgt       3   3.432 ± 1.747   ms/op
ClientPb.listUser                         avgt       3   3.921 ± 0.725   ms/op
ClientPb.createUser                     sample  280716   3.420 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.856           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.301           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.366           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.013           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.283           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.949           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.000           ms/op
ClientPb.existUser                      sample  284325   3.375 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.606           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.252           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.748           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.137           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.218           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.793           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.698           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.934           ms/op
ClientPb.getUser                        sample  277346   3.458 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.194           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.355           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.317           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.603           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.070           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.437           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.410           ms/op
ClientPb.listUser                       sample  238230   4.029 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.507           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.833           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.717           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.720           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.730           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.510           ms/op
