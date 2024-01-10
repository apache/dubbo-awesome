# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.560 ops/ms
# Warmup Iteration   2: 12.290 ops/ms
# Warmup Iteration   3: 12.363 ops/ms
Iteration   1: 12.673 ops/ms
Iteration   2: 12.682 ops/ms
Iteration   3: 12.441 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.598 ±(99.9%) 2.494 ops/ms [Average]
  (min, avg, max) = (12.441, 12.598, 12.682), stdev = 0.137
  CI (99.9%): [10.104, 15.092] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.822 ops/ms
# Warmup Iteration   2: 13.223 ops/ms
# Warmup Iteration   3: 13.079 ops/ms
Iteration   1: 13.140 ops/ms
Iteration   2: 13.058 ops/ms
Iteration   3: 12.888 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.028 ±(99.9%) 2.346 ops/ms [Average]
  (min, avg, max) = (12.888, 13.028, 13.140), stdev = 0.129
  CI (99.9%): [10.682, 15.375] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.862 ops/ms
# Warmup Iteration   2: 12.715 ops/ms
# Warmup Iteration   3: 12.845 ops/ms
Iteration   1: 12.925 ops/ms
Iteration   2: 12.896 ops/ms
Iteration   3: 12.919 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.913 ±(99.9%) 0.276 ops/ms [Average]
  (min, avg, max) = (12.896, 12.913, 12.925), stdev = 0.015
  CI (99.9%): [12.638, 13.189] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.347 ops/ms
# Warmup Iteration   2: 10.470 ops/ms
# Warmup Iteration   3: 10.515 ops/ms
Iteration   1: 10.541 ops/ms
Iteration   2: 10.557 ops/ms
Iteration   3: 10.686 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.595 ±(99.9%) 1.448 ops/ms [Average]
  (min, avg, max) = (10.541, 10.595, 10.686), stdev = 0.079
  CI (99.9%): [9.146, 12.043] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.013 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.567 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
Iteration   1: 2.550 ±(99.9%) 0.004 ms/op
Iteration   2: 2.513 ±(99.9%) 0.005 ms/op
Iteration   3: 2.505 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.523 ±(99.9%) 0.431 ms/op [Average]
  (min, avg, max) = (2.505, 2.523, 2.550), stdev = 0.024
  CI (99.9%): [2.091, 2.954] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.545 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.404 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.411 ±(99.9%) 0.003 ms/op
Iteration   1: 2.435 ±(99.9%) 0.004 ms/op
Iteration   2: 2.446 ±(99.9%) 0.004 ms/op
Iteration   3: 2.432 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.438 ±(99.9%) 0.136 ms/op [Average]
  (min, avg, max) = (2.432, 2.438, 2.446), stdev = 0.007
  CI (99.9%): [2.302, 2.574] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.008 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.537 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.004 ms/op
Iteration   1: 2.498 ±(99.9%) 0.004 ms/op
Iteration   2: 2.479 ±(99.9%) 0.003 ms/op
Iteration   3: 2.540 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.506 ±(99.9%) 0.565 ms/op [Average]
  (min, avg, max) = (2.479, 2.506, 2.540), stdev = 0.031
  CI (99.9%): [1.940, 3.071] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.534 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.005 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.005 ms/op
Iteration   1: 2.978 ±(99.9%) 0.004 ms/op
Iteration   2: 2.991 ±(99.9%) 0.007 ms/op
Iteration   3: 2.975 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.981 ±(99.9%) 0.162 ms/op [Average]
  (min, avg, max) = (2.975, 2.981, 2.991), stdev = 0.009
  CI (99.9%): [2.820, 3.143] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.012 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.621 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.006 ms/op
Iteration   1: 2.477 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.962 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   3.682 ms/op
                 createUser·p0.999:  7.106 ms/op
                 createUser·p0.9999: 14.156 ms/op
                 createUser·p1.00:   14.844 ms/op

Iteration   2: 2.502 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.908 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.748 ms/op
                 createUser·p0.999:  9.096 ms/op
                 createUser·p0.9999: 13.180 ms/op
                 createUser·p1.00:   13.582 ms/op

Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.659 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   4.080 ms/op
                 createUser·p0.999:  8.165 ms/op
                 createUser·p0.9999: 10.142 ms/op
                 createUser·p1.00:   10.945 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383512
  mean =      2.501 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 186270 
    [ 2.500,  3.750) = 192843 
    [ 3.750,  5.000) = 3269 
    [ 5.000,  6.250) = 570 
    [ 6.250,  7.500) = 82 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 117 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.830 ms/op
     p(99.9000) =      8.134 ms/op
     p(99.9900) =     13.337 ms/op
     p(99.9990) =     14.718 ms/op
     p(99.9999) =     14.844 ms/op
    p(100.0000) =     14.844 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.728 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
Iteration   1: 2.457 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.013 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.502 ms/op
                 existUser·p0.999:  5.611 ms/op
                 existUser·p0.9999: 14.368 ms/op
                 existUser·p1.00:   14.893 ms/op

Iteration   2: 2.432 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.987 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.514 ms/op
                 existUser·p0.999:  5.448 ms/op
                 existUser·p0.9999: 12.616 ms/op
                 existUser·p1.00:   13.550 ms/op

Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.004 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.187 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  8.964 ms/op
                 existUser·p0.9999: 11.852 ms/op
                 existUser·p1.00:   12.288 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389453
  mean =      2.462 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 193242 
    [ 2.500,  3.750) = 192330 
    [ 3.750,  5.000) = 2966 
    [ 5.000,  6.250) = 494 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 105 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.987 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.740 ms/op
     p(99.9000) =      5.970 ms/op
     p(99.9900) =     13.518 ms/op
     p(99.9990) =     14.550 ms/op
     p(99.9999) =     14.893 ms/op
    p(100.0000) =     14.893 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.882 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.525 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.005 ms/op
Iteration   1: 2.450 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.006 ms/op
                 getUser·p0.50:   2.437 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.658 ms/op
                 getUser·p0.999:  5.527 ms/op
                 getUser·p0.9999: 13.417 ms/op
                 getUser·p1.00:   13.828 ms/op

Iteration   2: 2.533 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.301 ms/op
                 getUser·p0.99:   4.710 ms/op
                 getUser·p0.999:  10.056 ms/op
                 getUser·p0.9999: 12.343 ms/op
                 getUser·p1.00:   12.829 ms/op

Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.033 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.711 ms/op
                 getUser·p0.999:  6.343 ms/op
                 getUser·p0.9999: 12.141 ms/op
                 getUser·p1.00:   12.861 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386655
  mean =      2.481 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 195338 
    [ 2.500,  3.750) = 185685 
    [ 3.750,  5.000) = 4375 
    [ 5.000,  6.250) = 758 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 133 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      3.029 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      4.043 ms/op
     p(99.9000) =      8.167 ms/op
     p(99.9900) =     12.976 ms/op
     p(99.9990) =     13.699 ms/op
     p(99.9999) =     13.828 ms/op
    p(100.0000) =     13.828 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.903 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.008 ms/op
Iteration   1: 3.012 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.525 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.140 ms/op
                 listUser·p0.9999: 10.662 ms/op
                 listUser·p1.00:   11.469 ms/op

Iteration   2: 2.965 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.867 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.486 ms/op
                 listUser·p0.9999: 11.955 ms/op
                 listUser·p1.00:   13.353 ms/op

Iteration   3: 2.989 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.957 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.489 ms/op
                 listUser·p0.999:  9.044 ms/op
                 listUser·p0.9999: 10.545 ms/op
                 listUser·p1.00:   11.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320925
  mean =      2.989 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 115 
    [ 1.250,  2.500) = 97763 
    [ 2.500,  3.750) = 185797 
    [ 3.750,  5.000) = 30208 
    [ 5.000,  6.250) = 5730 
    [ 6.250,  7.500) = 607 
    [ 7.500,  8.750) = 273 
    [ 8.750, 10.000) = 291 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.525 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.209 ms/op
     p(99.9900) =     10.910 ms/op
     p(99.9990) =     13.166 ms/op
     p(99.9999) =     13.353 ms/op
    p(100.0000) =     13.353 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.598 ± 2.494  ops/ms
ClientPb.existUser                       thrpt       3  13.028 ± 2.346  ops/ms
ClientPb.getUser                         thrpt       3  12.913 ± 0.276  ops/ms
ClientPb.listUser                        thrpt       3  10.595 ± 1.448  ops/ms
ClientPb.createUser                       avgt       3   2.523 ± 0.431   ms/op
ClientPb.existUser                        avgt       3   2.438 ± 0.136   ms/op
ClientPb.getUser                          avgt       3   2.506 ± 0.565   ms/op
ClientPb.listUser                         avgt       3   2.981 ± 0.162   ms/op
ClientPb.createUser                     sample  383512   2.501 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.659           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.134           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.337           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.844           ms/op
ClientPb.existUser                      sample  389453   2.462 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.987           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.970           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.518           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.893           ms/op
ClientPb.getUser                        sample  386655   2.481 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.896           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.482           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.029           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.043           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.167           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.976           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.828           ms/op
ClientPb.listUser                       sample  320925   2.989 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.525           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.929           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.209           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.910           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.353           ms/op
