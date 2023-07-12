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
# Warmup Iteration   1: 2.233 ops/ms
# Warmup Iteration   2: 5.373 ops/ms
# Warmup Iteration   3: 8.371 ops/ms
Iteration   1: 9.147 ops/ms
Iteration   2: 9.111 ops/ms
Iteration   3: 9.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.140 ±(99.9%) 0.470 ops/ms [Average]
  (min, avg, max) = (9.111, 9.140, 9.161), stdev = 0.026
  CI (99.9%): [8.670, 9.611] (assumes normal distribution)


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
# Warmup Iteration   1: 3.337 ops/ms
# Warmup Iteration   2: 8.878 ops/ms
# Warmup Iteration   3: 9.669 ops/ms
Iteration   1: 9.951 ops/ms
Iteration   2: 9.627 ops/ms
Iteration   3: 9.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.783 ±(99.9%) 2.960 ops/ms [Average]
  (min, avg, max) = (9.627, 9.783, 9.951), stdev = 0.162
  CI (99.9%): [6.823, 12.744] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.840 ops/ms
# Warmup Iteration   2: 8.513 ops/ms
# Warmup Iteration   3: 8.630 ops/ms
Iteration   1: 9.337 ops/ms
Iteration   2: 9.534 ops/ms
Iteration   3: 9.403 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.424 ±(99.9%) 1.833 ops/ms [Average]
  (min, avg, max) = (9.337, 9.424, 9.534), stdev = 0.100
  CI (99.9%): [7.591, 11.257] (assumes normal distribution)


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
# Warmup Iteration   1: 2.880 ops/ms
# Warmup Iteration   2: 7.323 ops/ms
# Warmup Iteration   3: 7.677 ops/ms
Iteration   1: 7.925 ops/ms
Iteration   2: 7.790 ops/ms
Iteration   3: 7.516 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.744 ±(99.9%) 3.797 ops/ms [Average]
  (min, avg, max) = (7.516, 7.744, 7.925), stdev = 0.208
  CI (99.9%): [3.947, 11.540] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.540 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.875 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.635 ±(99.9%) 0.002 ms/op
Iteration   1: 3.385 ±(99.9%) 0.008 ms/op
Iteration   2: 3.456 ±(99.9%) 0.008 ms/op
Iteration   3: 3.534 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.458 ±(99.9%) 1.362 ms/op [Average]
  (min, avg, max) = (3.385, 3.458, 3.534), stdev = 0.075
  CI (99.9%): [2.097, 4.820] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.066 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.747 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.574 ±(99.9%) 0.007 ms/op
Iteration   1: 3.338 ±(99.9%) 0.007 ms/op
Iteration   2: 3.359 ±(99.9%) 0.003 ms/op
Iteration   3: 3.208 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.302 ±(99.9%) 1.499 ms/op [Average]
  (min, avg, max) = (3.208, 3.302, 3.359), stdev = 0.082
  CI (99.9%): [1.803, 4.801] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.457 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.849 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.593 ±(99.9%) 0.006 ms/op
Iteration   1: 3.532 ±(99.9%) 0.004 ms/op
Iteration   2: 3.432 ±(99.9%) 0.003 ms/op
Iteration   3: 3.376 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.446 ±(99.9%) 1.438 ms/op [Average]
  (min, avg, max) = (3.376, 3.446, 3.532), stdev = 0.079
  CI (99.9%): [2.008, 4.885] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.912 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.624 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.248 ±(99.9%) 0.005 ms/op
Iteration   1: 4.090 ±(99.9%) 0.008 ms/op
Iteration   2: 3.862 ±(99.9%) 0.014 ms/op
Iteration   3: 3.945 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.966 ±(99.9%) 2.104 ms/op [Average]
  (min, avg, max) = (3.862, 3.966, 4.090), stdev = 0.115
  CI (99.9%): [1.862, 6.069] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.909 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.273 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.584 ±(99.9%) 0.010 ms/op
Iteration   1: 3.456 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.223 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   6.005 ms/op
                 createUser·p0.999:  19.251 ms/op
                 createUser·p0.9999: 27.054 ms/op
                 createUser·p1.00:   27.951 ms/op

Iteration   2: 3.468 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.917 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  22.080 ms/op
                 createUser·p0.9999: 26.273 ms/op
                 createUser·p1.00:   27.591 ms/op

Iteration   3: 3.692 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.365 ms/op
                 createUser·p0.50:   3.592 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.751 ms/op
                 createUser·p0.99:   6.038 ms/op
                 createUser·p0.999:  21.692 ms/op
                 createUser·p0.9999: 28.543 ms/op
                 createUser·p1.00:   30.638 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271314
  mean =      3.535 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2660 
    [ 2.500,  5.000) = 261442 
    [ 5.000,  7.500) = 6180 
    [ 7.500, 10.000) = 566 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.365 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     20.961 ms/op
     p(99.9900) =     27.390 ms/op
     p(99.9990) =     29.381 ms/op
     p(99.9999) =     30.638 ms/op
    p(100.0000) =     30.638 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.632 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.699 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.350 ±(99.9%) 0.008 ms/op
Iteration   1: 3.345 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.223 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   4.084 ms/op
                 existUser·p0.99:   6.349 ms/op
                 existUser·p0.999:  18.940 ms/op
                 existUser·p0.9999: 22.413 ms/op
                 existUser·p1.00:   23.298 ms/op

Iteration   2: 3.306 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.268 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   6.398 ms/op
                 existUser·p0.999:  15.812 ms/op
                 existUser·p0.9999: 23.735 ms/op
                 existUser·p1.00:   24.936 ms/op

Iteration   3: 3.301 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.047 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  18.842 ms/op
                 existUser·p0.9999: 28.202 ms/op
                 existUser·p1.00:   29.524 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289109
  mean =      3.317 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8565 
    [ 2.500,  5.000) = 273769 
    [ 5.000,  7.500) = 5435 
    [ 7.500, 10.000) = 776 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 139 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.047 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      6.119 ms/op
     p(99.9000) =     18.834 ms/op
     p(99.9900) =     27.176 ms/op
     p(99.9990) =     29.276 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.073 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.756 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.499 ±(99.9%) 0.010 ms/op
Iteration   1: 3.444 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.462 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   6.513 ms/op
                 getUser·p0.999:  21.332 ms/op
                 getUser·p0.9999: 24.108 ms/op
                 getUser·p1.00:   24.969 ms/op

Iteration   2: 3.374 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.645 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  21.512 ms/op
                 getUser·p0.9999: 24.251 ms/op
                 getUser·p1.00:   24.871 ms/op

Iteration   3: 3.395 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.796 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   4.129 ms/op
                 getUser·p0.99:   6.349 ms/op
                 getUser·p0.999:  17.536 ms/op
                 getUser·p0.9999: 23.055 ms/op
                 getUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 281969
  mean =      3.404 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4609 
    [ 2.500,  5.000) = 271012 
    [ 5.000,  7.500) = 4973 
    [ 7.500, 10.000) = 938 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 155 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.462 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      6.267 ms/op
     p(99.9000) =     18.777 ms/op
     p(99.9900) =     24.084 ms/op
     p(99.9990) =     24.942 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.157 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.580 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.060 ±(99.9%) 0.014 ms/op
Iteration   1: 4.044 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.786 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   7.676 ms/op
                 listUser·p0.999:  20.513 ms/op
                 listUser·p0.9999: 24.716 ms/op
                 listUser·p1.00:   27.853 ms/op

Iteration   2: 3.990 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   7.447 ms/op
                 listUser·p0.999:  15.020 ms/op
                 listUser·p0.9999: 16.105 ms/op
                 listUser·p1.00:   16.908 ms/op

Iteration   3: 3.929 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  15.301 ms/op
                 listUser·p0.9999: 16.989 ms/op
                 listUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240652
  mean =      3.987 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 233802 
    [ 5.000,  7.500) = 4588 
    [ 7.500, 10.000) = 1363 
    [10.000, 12.500) = 314 
    [12.500, 15.000) = 238 
    [15.000, 17.500) = 195 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.786 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      7.324 ms/op
     p(99.9000) =     15.734 ms/op
     p(99.9900) =     23.820 ms/op
     p(99.9990) =     27.793 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.140 ± 0.470  ops/ms
ClientPb.existUser                       thrpt       3   9.783 ± 2.960  ops/ms
ClientPb.getUser                         thrpt       3   9.424 ± 1.833  ops/ms
ClientPb.listUser                        thrpt       3   7.744 ± 3.797  ops/ms
ClientPb.createUser                       avgt       3   3.458 ± 1.362   ms/op
ClientPb.existUser                        avgt       3   3.302 ± 1.499   ms/op
ClientPb.getUser                          avgt       3   3.446 ± 1.438   ms/op
ClientPb.listUser                         avgt       3   3.966 ± 2.104   ms/op
ClientPb.createUser                     sample  271314   3.535 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.365           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.428           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.961           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.432           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.890           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.961           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.390           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.638           ms/op
ClientPb.existUser                      sample  289109   3.317 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.047           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.211           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.604           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.903           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.119           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.834           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.176           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.524           ms/op
ClientPb.getUser                        sample  281969   3.404 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.462           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.301           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.703           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.267           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.777           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.084           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.035           ms/op
ClientPb.listUser                       sample  240652   3.987 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.786           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.324           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.734           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.820           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.853           ms/op
