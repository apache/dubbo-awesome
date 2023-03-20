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
# Warmup Iteration   1: 2.376 ops/ms
# Warmup Iteration   2: 5.889 ops/ms
# Warmup Iteration   3: 8.848 ops/ms
Iteration   1: 9.194 ops/ms
Iteration   2: 9.498 ops/ms
Iteration   3: 9.357 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.350 ±(99.9%) 2.775 ops/ms [Average]
  (min, avg, max) = (9.194, 9.350, 9.498), stdev = 0.152
  CI (99.9%): [6.575, 12.125] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.467 ops/ms
# Warmup Iteration   2: 9.015 ops/ms
# Warmup Iteration   3: 9.562 ops/ms
Iteration   1: 9.490 ops/ms
Iteration   2: 10.019 ops/ms
Iteration   3: 9.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.775 ±(99.9%) 4.869 ops/ms [Average]
  (min, avg, max) = (9.490, 9.775, 10.019), stdev = 0.267
  CI (99.9%): [4.906, 14.644] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.695 ops/ms
# Warmup Iteration   2: 8.584 ops/ms
# Warmup Iteration   3: 9.124 ops/ms
Iteration   1: 9.239 ops/ms
Iteration   2: 9.585 ops/ms
Iteration   3: 8.938 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.254 ±(99.9%) 5.908 ops/ms [Average]
  (min, avg, max) = (8.938, 9.254, 9.585), stdev = 0.324
  CI (99.9%): [3.346, 15.162] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.746 ops/ms
# Warmup Iteration   2: 7.509 ops/ms
# Warmup Iteration   3: 7.911 ops/ms
Iteration   1: 7.755 ops/ms
Iteration   2: 8.103 ops/ms
Iteration   3: 8.243 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.033 ±(99.9%) 4.581 ops/ms [Average]
  (min, avg, max) = (7.755, 8.033, 8.243), stdev = 0.251
  CI (99.9%): [3.453, 12.614] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.550 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.851 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.449 ±(99.9%) 0.010 ms/op
Iteration   1: 3.324 ±(99.9%) 0.010 ms/op
Iteration   2: 3.376 ±(99.9%) 0.005 ms/op
Iteration   3: 3.625 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.442 ±(99.9%) 2.929 ms/op [Average]
  (min, avg, max) = (3.324, 3.442, 3.625), stdev = 0.161
  CI (99.9%): [0.512, 6.371] (assumes normal distribution)


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
# Warmup Iteration   1: 9.115 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.621 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.503 ±(99.9%) 0.002 ms/op
Iteration   1: 3.220 ±(99.9%) 0.005 ms/op
Iteration   2: 3.610 ±(99.9%) 0.007 ms/op
Iteration   3: 3.342 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.390 ±(99.9%) 3.638 ms/op [Average]
  (min, avg, max) = (3.220, 3.390, 3.610), stdev = 0.199
  CI (99.9%): [≈ 0, 7.028] (assumes normal distribution)


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
# Warmup Iteration   1: 10.968 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.884 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.451 ±(99.9%) 0.005 ms/op
Iteration   1: 3.488 ±(99.9%) 0.007 ms/op
Iteration   2: 3.447 ±(99.9%) 0.007 ms/op
Iteration   3: 3.371 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.435 ±(99.9%) 1.080 ms/op [Average]
  (min, avg, max) = (3.371, 3.435, 3.488), stdev = 0.059
  CI (99.9%): [2.355, 4.515] (assumes normal distribution)


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
# Warmup Iteration   1: 9.847 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.453 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.142 ±(99.9%) 0.007 ms/op
Iteration   1: 3.917 ±(99.9%) 0.015 ms/op
Iteration   2: 3.997 ±(99.9%) 0.008 ms/op
Iteration   3: 3.890 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.935 ±(99.9%) 1.015 ms/op [Average]
  (min, avg, max) = (3.890, 3.935, 3.997), stdev = 0.056
  CI (99.9%): [2.919, 4.950] (assumes normal distribution)


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
# Warmup Iteration   1: 9.440 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 4.027 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.473 ±(99.9%) 0.010 ms/op
Iteration   1: 3.409 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.010 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  21.692 ms/op
                 createUser·p0.9999: 24.347 ms/op
                 createUser·p1.00:   25.461 ms/op

Iteration   2: 3.352 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.280 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  25.645 ms/op
                 createUser·p0.9999: 32.781 ms/op
                 createUser·p1.00:   34.406 ms/op

Iteration   3: 3.451 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.017 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.973 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   6.193 ms/op
                 createUser·p0.999:  21.955 ms/op
                 createUser·p0.9999: 24.960 ms/op
                 createUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282000
  mean =      3.404 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4898 
    [ 2.500,  5.000) = 271790 
    [ 5.000,  7.500) = 4195 
    [ 7.500, 10.000) = 597 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 160 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.010 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     22.381 ms/op
     p(99.9900) =     31.772 ms/op
     p(99.9990) =     33.763 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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
# Warmup Iteration   1: 8.954 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.539 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.363 ±(99.9%) 0.009 ms/op
Iteration   1: 3.311 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.253 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   3.998 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  11.321 ms/op
                 existUser·p0.9999: 23.670 ms/op
                 existUser·p1.00:   24.150 ms/op

Iteration   2: 3.371 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.180 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   4.067 ms/op
                 existUser·p0.99:   6.078 ms/op
                 existUser·p0.999:  22.545 ms/op
                 existUser·p0.9999: 29.491 ms/op
                 existUser·p1.00:   30.081 ms/op

Iteration   3: 3.424 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.589 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.863 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   5.763 ms/op
                 existUser·p0.999:  18.616 ms/op
                 existUser·p0.9999: 26.279 ms/op
                 existUser·p1.00:   27.066 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285023
  mean =      3.368 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8229 
    [ 2.500,  5.000) = 271634 
    [ 5.000,  7.500) = 4223 
    [ 7.500, 10.000) = 432 
    [10.000, 12.500) = 178 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 123 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     15.482 ms/op
     p(99.9900) =     28.213 ms/op
     p(99.9990) =     29.725 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


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
# Warmup Iteration   1: 8.868 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.602 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.461 ±(99.9%) 0.010 ms/op
Iteration   1: 3.514 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.726 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   4.018 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   6.860 ms/op
                 getUser·p0.999:  23.812 ms/op
                 getUser·p0.9999: 30.273 ms/op
                 getUser·p1.00:   31.261 ms/op

Iteration   2: 3.366 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.833 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   5.087 ms/op
                 getUser·p0.999:  9.044 ms/op
                 getUser·p0.9999: 24.871 ms/op
                 getUser·p1.00:   25.428 ms/op

Iteration   3: 3.437 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.425 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   6.709 ms/op
                 getUser·p0.999:  19.620 ms/op
                 getUser·p0.9999: 27.253 ms/op
                 getUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279336
  mean =      3.438 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7299 
    [ 2.500,  5.000) = 263776 
    [ 5.000,  7.500) = 7032 
    [ 7.500, 10.000) = 662 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.324 ms/op
     p(99.9000) =     17.039 ms/op
     p(99.9900) =     29.067 ms/op
     p(99.9990) =     31.053 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


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
# Warmup Iteration   1: 10.131 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.383 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.036 ±(99.9%) 0.013 ms/op
Iteration   1: 4.065 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   4.907 ms/op
                 listUser·p0.99:   7.733 ms/op
                 listUser·p0.999:  21.849 ms/op
                 listUser·p0.9999: 25.157 ms/op
                 listUser·p1.00:   26.411 ms/op

Iteration   2: 4.074 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.700 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   8.241 ms/op
                 listUser·p0.999:  15.073 ms/op
                 listUser·p0.9999: 16.763 ms/op
                 listUser·p1.00:   17.367 ms/op

Iteration   3: 3.992 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.486 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   7.619 ms/op
                 listUser·p0.999:  18.119 ms/op
                 listUser·p0.9999: 26.116 ms/op
                 listUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237087
  mean =      4.044 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 227199 
    [ 5.000,  7.500) = 7076 
    [ 7.500, 10.000) = 1755 
    [10.000, 12.500) = 520 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 180 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.700 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      7.823 ms/op
     p(99.9000) =     16.905 ms/op
     p(99.9900) =     24.651 ms/op
     p(99.9990) =     26.182 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.350 ± 2.775  ops/ms
ClientPb.existUser                       thrpt       3   9.775 ± 4.869  ops/ms
ClientPb.getUser                         thrpt       3   9.254 ± 5.908  ops/ms
ClientPb.listUser                        thrpt       3   8.033 ± 4.581  ops/ms
ClientPb.createUser                       avgt       3   3.442 ± 2.929   ms/op
ClientPb.existUser                        avgt       3   3.390 ± 3.638   ms/op
ClientPb.getUser                          avgt       3   3.435 ± 1.080   ms/op
ClientPb.listUser                         avgt       3   3.935 ± 1.015   ms/op
ClientPb.createUser                     sample  282000   3.404 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.010           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.265           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.137           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.792           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.381           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.772           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.406           ms/op
ClientPb.existUser                      sample  285023   3.368 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.180           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.772           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.100           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.669           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.482           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.213           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.081           ms/op
ClientPb.getUser                        sample  279336   3.438 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.833           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.310           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.324           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.039           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.067           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.261           ms/op
ClientPb.listUser                       sample  237087   4.044 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.700           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.841           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.823           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.905           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.651           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.411           ms/op
