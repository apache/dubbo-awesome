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
# Warmup Iteration   1: 1.441 ops/ms
# Warmup Iteration   2: 3.469 ops/ms
# Warmup Iteration   3: 6.387 ops/ms
Iteration   1: 6.472 ops/ms
Iteration   2: 7.175 ops/ms
Iteration   3: 7.764 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.137 ±(99.9%) 11.801 ops/ms [Average]
  (min, avg, max) = (6.472, 7.137, 7.764), stdev = 0.647
  CI (99.9%): [≈ 0, 18.939] (assumes normal distribution)


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
# Warmup Iteration   1: 2.052 ops/ms
# Warmup Iteration   2: 5.681 ops/ms
# Warmup Iteration   3: 7.198 ops/ms
Iteration   1: 7.566 ops/ms
Iteration   2: 7.686 ops/ms
Iteration   3: 7.462 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.571 ±(99.9%) 2.048 ops/ms [Average]
  (min, avg, max) = (7.462, 7.571, 7.686), stdev = 0.112
  CI (99.9%): [5.524, 9.619] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.891 ops/ms
# Warmup Iteration   2: 5.334 ops/ms
# Warmup Iteration   3: 7.050 ops/ms
Iteration   1: 7.078 ops/ms
Iteration   2: 7.617 ops/ms
Iteration   3: 7.074 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.256 ±(99.9%) 5.695 ops/ms [Average]
  (min, avg, max) = (7.074, 7.256, 7.617), stdev = 0.312
  CI (99.9%): [1.561, 12.952] (assumes normal distribution)


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
# Warmup Iteration   1: 1.677 ops/ms
# Warmup Iteration   2: 4.711 ops/ms
# Warmup Iteration   3: 5.827 ops/ms
Iteration   1: 6.437 ops/ms
Iteration   2: 6.084 ops/ms
Iteration   3: 5.907 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.143 ±(99.9%) 4.916 ops/ms [Average]
  (min, avg, max) = (5.907, 6.143, 6.437), stdev = 0.269
  CI (99.9%): [1.227, 11.059] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 15.373 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.083 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.682 ±(99.9%) 0.005 ms/op
Iteration   1: 4.290 ±(99.9%) 0.006 ms/op
Iteration   2: 4.652 ±(99.9%) 0.008 ms/op
Iteration   3: 4.517 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.486 ±(99.9%) 3.341 ms/op [Average]
  (min, avg, max) = (4.290, 4.486, 4.652), stdev = 0.183
  CI (99.9%): [1.145, 7.828] (assumes normal distribution)


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
# Warmup Iteration   1: 13.639 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.951 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.225 ±(99.9%) 0.004 ms/op
Iteration   1: 4.083 ±(99.9%) 0.006 ms/op
Iteration   2: 3.893 ±(99.9%) 0.005 ms/op
Iteration   3: 3.958 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.978 ±(99.9%) 1.762 ms/op [Average]
  (min, avg, max) = (3.893, 3.978, 4.083), stdev = 0.097
  CI (99.9%): [2.216, 5.740] (assumes normal distribution)


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
# Warmup Iteration   1: 16.084 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 5.611 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.433 ±(99.9%) 0.005 ms/op
Iteration   1: 4.216 ±(99.9%) 0.005 ms/op
Iteration   2: 4.395 ±(99.9%) 0.005 ms/op
Iteration   3: 4.396 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.336 ±(99.9%) 1.888 ms/op [Average]
  (min, avg, max) = (4.216, 4.336, 4.396), stdev = 0.103
  CI (99.9%): [2.448, 6.224] (assumes normal distribution)


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
# Warmup Iteration   1: 14.779 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 6.445 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.268 ±(99.9%) 0.010 ms/op
Iteration   1: 5.160 ±(99.9%) 0.009 ms/op
Iteration   2: 4.963 ±(99.9%) 0.012 ms/op
Iteration   3: 4.896 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.006 ±(99.9%) 2.503 ms/op [Average]
  (min, avg, max) = (4.896, 5.006, 5.160), stdev = 0.137
  CI (99.9%): [2.503, 7.510] (assumes normal distribution)


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
# Warmup Iteration   1: 14.456 ±(99.9%) 0.251 ms/op
# Warmup Iteration   2: 5.926 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 4.683 ±(99.9%) 0.021 ms/op
Iteration   1: 4.004 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.593 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   5.292 ms/op
                 createUser·p0.99:   7.548 ms/op
                 createUser·p0.999:  22.914 ms/op
                 createUser·p0.9999: 26.739 ms/op
                 createUser·p1.00:   27.394 ms/op

Iteration   2: 3.905 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   2.232 ms/op
                 createUser·p0.50:   3.867 ms/op
                 createUser·p0.90:   4.133 ms/op
                 createUser·p0.95:   4.612 ms/op
                 createUser·p0.99:   6.701 ms/op
                 createUser·p0.999:  27.066 ms/op
                 createUser·p0.9999: 30.605 ms/op
                 createUser·p1.00:   36.110 ms/op

Iteration   3: 4.144 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.866 ms/op
                 createUser·p0.50:   3.940 ms/op
                 createUser·p0.90:   4.915 ms/op
                 createUser·p0.95:   5.585 ms/op
                 createUser·p0.99:   7.669 ms/op
                 createUser·p0.999:  12.960 ms/op
                 createUser·p0.9999: 31.607 ms/op
                 createUser·p1.00:   32.244 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 238882
  mean =      4.015 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 192 
    [ 2.500,  5.000) = 224364 
    [ 5.000,  7.500) = 12042 
    [ 7.500, 10.000) = 1469 
    [10.000, 12.500) = 484 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 62 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.593 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      5.169 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     22.970 ms/op
     p(99.9900) =     30.969 ms/op
     p(99.9990) =     35.888 ms/op
     p(99.9999) =     36.110 ms/op
    p(100.0000) =     36.110 ms/op


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
# Warmup Iteration   1: 15.266 ±(99.9%) 0.226 ms/op
# Warmup Iteration   2: 5.888 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 4.401 ±(99.9%) 0.017 ms/op
Iteration   1: 4.010 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.577 ms/op
                 existUser·p0.50:   3.830 ms/op
                 existUser·p0.90:   4.588 ms/op
                 existUser·p0.95:   5.300 ms/op
                 existUser·p0.99:   7.668 ms/op
                 existUser·p0.999:  25.406 ms/op
                 existUser·p0.9999: 29.329 ms/op
                 existUser·p1.00:   30.048 ms/op

Iteration   2: 4.311 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.397 ms/op
                 existUser·p0.50:   3.985 ms/op
                 existUser·p0.90:   5.358 ms/op
                 existUser·p0.95:   6.414 ms/op
                 existUser·p0.99:   10.027 ms/op
                 existUser·p0.999:  16.025 ms/op
                 existUser·p0.9999: 32.244 ms/op
                 existUser·p1.00:   32.866 ms/op

Iteration   3: 4.287 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.814 ms/op
                 existUser·p0.50:   3.940 ms/op
                 existUser·p0.90:   5.407 ms/op
                 existUser·p0.95:   6.463 ms/op
                 existUser·p0.99:   9.945 ms/op
                 existUser·p0.999:  20.067 ms/op
                 existUser·p0.9999: 31.326 ms/op
                 existUser·p1.00:   33.194 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 228515
  mean =      4.198 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 398 
    [ 2.500,  5.000) = 203108 
    [ 5.000,  7.500) = 20230 
    [ 7.500, 10.000) = 3097 
    [10.000, 12.500) = 1115 
    [12.500, 15.000) = 234 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 94 
    [30.000, 32.500) = 61 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.397 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      5.120 ms/op
     p(95.0000) =      6.152 ms/op
     p(99.0000) =      9.224 ms/op
     p(99.9000) =     20.263 ms/op
     p(99.9900) =     31.626 ms/op
     p(99.9990) =     32.810 ms/op
     p(99.9999) =     33.194 ms/op
    p(100.0000) =     33.194 ms/op


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
# Warmup Iteration   1: 13.686 ±(99.9%) 0.222 ms/op
# Warmup Iteration   2: 5.095 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.345 ±(99.9%) 0.015 ms/op
Iteration   1: 4.347 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.645 ms/op
                 getUser·p0.50:   4.047 ms/op
                 getUser·p0.90:   5.382 ms/op
                 getUser·p0.95:   6.373 ms/op
                 getUser·p0.99:   9.535 ms/op
                 getUser·p0.999:  18.612 ms/op
                 getUser·p0.9999: 26.911 ms/op
                 getUser·p1.00:   27.427 ms/op

Iteration   2: 4.479 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.063 ms/op
                 getUser·p0.50:   4.112 ms/op
                 getUser·p0.90:   5.751 ms/op
                 getUser·p0.95:   6.865 ms/op
                 getUser·p0.99:   9.945 ms/op
                 getUser·p0.999:  20.546 ms/op
                 getUser·p0.9999: 29.786 ms/op
                 getUser·p1.00:   30.474 ms/op

Iteration   3: 4.376 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.722 ms/op
                 getUser·p0.50:   4.026 ms/op
                 getUser·p0.90:   5.464 ms/op
                 getUser·p0.95:   6.636 ms/op
                 getUser·p0.99:   9.814 ms/op
                 getUser·p0.999:  32.571 ms/op
                 getUser·p0.9999: 39.433 ms/op
                 getUser·p1.00:   39.780 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 218099
  mean =      4.400 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 160 
    [ 2.500,  5.000) = 185360 
    [ 5.000,  7.500) = 26207 
    [ 7.500, 10.000) = 4336 
    [10.000, 12.500) = 1211 
    [12.500, 15.000) = 361 
    [15.000, 17.500) = 177 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      4.059 ms/op
     p(90.0000) =      5.538 ms/op
     p(95.0000) =      6.676 ms/op
     p(99.0000) =      9.699 ms/op
     p(99.9000) =     24.599 ms/op
     p(99.9900) =     37.892 ms/op
     p(99.9990) =     39.715 ms/op
     p(99.9999) =     39.780 ms/op
    p(100.0000) =     39.780 ms/op


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
# Warmup Iteration   1: 16.231 ±(99.9%) 0.237 ms/op
# Warmup Iteration   2: 6.739 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.271 ±(99.9%) 0.023 ms/op
Iteration   1: 5.126 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.013 ms/op
                 listUser·p0.50:   4.735 ms/op
                 listUser·p0.90:   6.291 ms/op
                 listUser·p0.95:   7.733 ms/op
                 listUser·p0.99:   10.273 ms/op
                 listUser·p0.999:  26.247 ms/op
                 listUser·p0.9999: 30.179 ms/op
                 listUser·p1.00:   31.162 ms/op

Iteration   2: 5.352 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.494 ms/op
                 listUser·p0.50:   4.981 ms/op
                 listUser·p0.90:   6.630 ms/op
                 listUser·p0.95:   7.848 ms/op
                 listUser·p0.99:   10.420 ms/op
                 listUser·p0.999:  28.601 ms/op
                 listUser·p0.9999: 32.509 ms/op
                 listUser·p1.00:   33.030 ms/op

Iteration   3: 5.356 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.011 ms/op
                 listUser·p0.50:   4.932 ms/op
                 listUser·p0.90:   6.775 ms/op
                 listUser·p0.95:   8.225 ms/op
                 listUser·p0.99:   11.354 ms/op
                 listUser·p0.999:  20.756 ms/op
                 listUser·p0.9999: 23.531 ms/op
                 listUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 181912
  mean =      5.276 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 103684 
    [ 5.000,  7.500) = 66831 
    [ 7.500, 10.000) = 8746 
    [10.000, 12.500) = 1674 
    [12.500, 15.000) = 452 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.011 ms/op
     p(50.0000) =      4.882 ms/op
     p(90.0000) =      6.578 ms/op
     p(95.0000) =      7.938 ms/op
     p(99.0000) =     10.666 ms/op
     p(99.9000) =     24.808 ms/op
     p(99.9900) =     31.118 ms/op
     p(99.9990) =     32.735 ms/op
     p(99.9999) =     33.030 ms/op
    p(100.0000) =     33.030 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   7.137 ± 11.801  ops/ms
ClientPb.existUser                       thrpt       3   7.571 ±  2.048  ops/ms
ClientPb.getUser                         thrpt       3   7.256 ±  5.695  ops/ms
ClientPb.listUser                        thrpt       3   6.143 ±  4.916  ops/ms
ClientPb.createUser                       avgt       3   4.486 ±  3.341   ms/op
ClientPb.existUser                        avgt       3   3.978 ±  1.762   ms/op
ClientPb.getUser                          avgt       3   4.336 ±  1.888   ms/op
ClientPb.listUser                         avgt       3   5.006 ±  2.503   ms/op
ClientPb.createUser                     sample  238882   4.015 ±  0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.593            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.883            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.604            ms/op
ClientPb.createUser:createUser·p0.95    sample           5.169            ms/op
ClientPb.createUser:createUser·p0.99    sample           7.414            ms/op
ClientPb.createUser:createUser·p0.999   sample          22.970            ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.969            ms/op
ClientPb.createUser:createUser·p1.00    sample          36.110            ms/op
ClientPb.existUser                      sample  228515   4.198 ±  0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.397            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.908            ms/op
ClientPb.existUser:existUser·p0.90      sample           5.120            ms/op
ClientPb.existUser:existUser·p0.95      sample           6.152            ms/op
ClientPb.existUser:existUser·p0.99      sample           9.224            ms/op
ClientPb.existUser:existUser·p0.999     sample          20.263            ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.626            ms/op
ClientPb.existUser:existUser·p1.00      sample          33.194            ms/op
ClientPb.getUser                        sample  218099   4.400 ±  0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.645            ms/op
ClientPb.getUser:getUser·p0.50          sample           4.059            ms/op
ClientPb.getUser:getUser·p0.90          sample           5.538            ms/op
ClientPb.getUser:getUser·p0.95          sample           6.676            ms/op
ClientPb.getUser:getUser·p0.99          sample           9.699            ms/op
ClientPb.getUser:getUser·p0.999         sample          24.599            ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.892            ms/op
ClientPb.getUser:getUser·p1.00          sample          39.780            ms/op
ClientPb.listUser                       sample  181912   5.276 ±  0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.011            ms/op
ClientPb.listUser:listUser·p0.50        sample           4.882            ms/op
ClientPb.listUser:listUser·p0.90        sample           6.578            ms/op
ClientPb.listUser:listUser·p0.95        sample           7.938            ms/op
ClientPb.listUser:listUser·p0.99        sample          10.666            ms/op
ClientPb.listUser:listUser·p0.999       sample          24.808            ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.118            ms/op
ClientPb.listUser:listUser·p1.00        sample          33.030            ms/op
