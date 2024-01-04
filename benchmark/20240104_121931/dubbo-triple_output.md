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
# Warmup Iteration   1: 5.116 ops/ms
# Warmup Iteration   2: 12.184 ops/ms
# Warmup Iteration   3: 12.363 ops/ms
Iteration   1: 12.576 ops/ms
Iteration   2: 12.548 ops/ms
Iteration   3: 12.592 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.572 ±(99.9%) 0.406 ops/ms [Average]
  (min, avg, max) = (12.548, 12.572, 12.592), stdev = 0.022
  CI (99.9%): [12.166, 12.978] (assumes normal distribution)


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
# Warmup Iteration   1: 7.767 ops/ms
# Warmup Iteration   2: 13.087 ops/ms
# Warmup Iteration   3: 13.141 ops/ms
Iteration   1: 13.093 ops/ms
Iteration   2: 12.982 ops/ms
Iteration   3: 13.046 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.041 ±(99.9%) 1.014 ops/ms [Average]
  (min, avg, max) = (12.982, 13.041, 13.093), stdev = 0.056
  CI (99.9%): [12.027, 14.054] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.813 ops/ms
# Warmup Iteration   2: 12.304 ops/ms
# Warmup Iteration   3: 12.773 ops/ms
Iteration   1: 12.565 ops/ms
Iteration   2: 12.747 ops/ms
Iteration   3: 12.646 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.653 ±(99.9%) 1.659 ops/ms [Average]
  (min, avg, max) = (12.565, 12.653, 12.747), stdev = 0.091
  CI (99.9%): [10.993, 14.312] (assumes normal distribution)


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
# Warmup Iteration   1: 6.684 ops/ms
# Warmup Iteration   2: 10.609 ops/ms
# Warmup Iteration   3: 10.479 ops/ms
Iteration   1: 10.537 ops/ms
Iteration   2: 10.655 ops/ms
Iteration   3: 10.450 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.547 ±(99.9%) 1.871 ops/ms [Average]
  (min, avg, max) = (10.450, 10.547, 10.655), stdev = 0.103
  CI (99.9%): [8.676, 12.418] (assumes normal distribution)


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
# Warmup Iteration   1: 4.142 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.590 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.555 ±(99.9%) 0.004 ms/op
Iteration   1: 2.584 ±(99.9%) 0.004 ms/op
Iteration   2: 2.570 ±(99.9%) 0.003 ms/op
Iteration   3: 2.564 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.572 ±(99.9%) 0.185 ms/op [Average]
  (min, avg, max) = (2.564, 2.572, 2.584), stdev = 0.010
  CI (99.9%): [2.388, 2.757] (assumes normal distribution)


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
# Warmup Iteration   1: 3.622 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.468 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.004 ms/op
Iteration   1: 2.443 ±(99.9%) 0.005 ms/op
Iteration   2: 2.445 ±(99.9%) 0.004 ms/op
Iteration   3: 2.438 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.442 ±(99.9%) 0.070 ms/op [Average]
  (min, avg, max) = (2.438, 2.442, 2.445), stdev = 0.004
  CI (99.9%): [2.372, 2.512] (assumes normal distribution)


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
# Warmup Iteration   1: 3.824 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.554 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.004 ms/op
Iteration   1: 2.461 ±(99.9%) 0.004 ms/op
Iteration   2: 2.475 ±(99.9%) 0.004 ms/op
Iteration   3: 2.496 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.478 ±(99.9%) 0.323 ms/op [Average]
  (min, avg, max) = (2.461, 2.478, 2.496), stdev = 0.018
  CI (99.9%): [2.154, 2.801] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.637 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.978 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.006 ms/op
Iteration   1: 3.005 ±(99.9%) 0.006 ms/op
Iteration   2: 2.991 ±(99.9%) 0.004 ms/op
Iteration   3: 2.985 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.994 ±(99.9%) 0.191 ms/op [Average]
  (min, avg, max) = (2.985, 2.994, 3.005), stdev = 0.010
  CI (99.9%): [2.803, 3.184] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.093 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.718 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.527 ±(99.9%) 0.006 ms/op
Iteration   1: 2.545 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.926 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.871 ms/op
                 createUser·p0.999:  11.108 ms/op
                 createUser·p0.9999: 13.810 ms/op
                 createUser·p1.00:   14.123 ms/op

Iteration   2: 2.533 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.063 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.797 ms/op
                 createUser·p0.999:  9.974 ms/op
                 createUser·p0.9999: 15.680 ms/op
                 createUser·p1.00:   16.122 ms/op

Iteration   3: 2.543 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.682 ms/op
                 createUser·p0.999:  8.503 ms/op
                 createUser·p0.9999: 14.791 ms/op
                 createUser·p1.00:   15.565 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377520
  mean =      2.540 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 181041 
    [ 2.500,  3.750) = 192407 
    [ 3.750,  5.000) = 3343 
    [ 5.000,  6.250) = 277 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 116 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.926 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.785 ms/op
     p(99.9000) =      8.552 ms/op
     p(99.9900) =     14.786 ms/op
     p(99.9990) =     16.044 ms/op
     p(99.9999) =     16.122 ms/op
    p(100.0000) =     16.122 ms/op


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
# Warmup Iteration   1: 3.737 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.446 ±(99.9%) 0.005 ms/op
Iteration   1: 2.452 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.124 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.478 ms/op
                 existUser·p0.999:  7.714 ms/op
                 existUser·p0.9999: 13.729 ms/op
                 existUser·p1.00:   14.139 ms/op

Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.993 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.604 ms/op
                 existUser·p0.999:  7.936 ms/op
                 existUser·p0.9999: 14.075 ms/op
                 existUser·p1.00:   14.811 ms/op

Iteration   3: 2.450 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.787 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.596 ms/op
                 existUser·p0.999:  6.328 ms/op
                 existUser·p0.9999: 12.075 ms/op
                 existUser·p1.00:   13.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389893
  mean =      2.460 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 191876 
    [ 2.500,  3.750) = 195236 
    [ 3.750,  5.000) = 2021 
    [ 5.000,  6.250) = 284 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.559 ms/op
     p(99.9000) =      7.289 ms/op
     p(99.9900) =     13.664 ms/op
     p(99.9990) =     14.746 ms/op
     p(99.9999) =     14.811 ms/op
    p(100.0000) =     14.811 ms/op


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
# Warmup Iteration   1: 4.027 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.569 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.527 ±(99.9%) 0.006 ms/op
Iteration   1: 2.514 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.013 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.752 ms/op
                 getUser·p0.999:  10.791 ms/op
                 getUser·p0.9999: 13.416 ms/op
                 getUser·p1.00:   14.008 ms/op

Iteration   2: 2.514 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.843 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.903 ms/op
                 getUser·p0.999:  9.422 ms/op
                 getUser·p0.9999: 13.264 ms/op
                 getUser·p1.00:   14.107 ms/op

Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.135 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.916 ms/op
                 getUser·p0.999:  8.700 ms/op
                 getUser·p0.9999: 11.051 ms/op
                 getUser·p1.00:   12.780 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381815
  mean =      2.512 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 186835 
    [ 2.500,  3.750) = 190156 
    [ 3.750,  5.000) = 4019 
    [ 5.000,  6.250) = 305 
    [ 6.250,  7.500) = 72 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 116 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      8.752 ms/op
     p(99.9900) =     13.235 ms/op
     p(99.9990) =     13.938 ms/op
     p(99.9999) =     14.107 ms/op
    p(100.0000) =     14.107 ms/op


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
# Warmup Iteration   1: 4.699 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.009 ms/op
Iteration   1: 3.054 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.993 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.865 ms/op
                 listUser·p0.999:  9.241 ms/op
                 listUser·p0.9999: 18.121 ms/op
                 listUser·p1.00:   18.219 ms/op

Iteration   2: 3.032 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.061 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  8.941 ms/op
                 listUser·p0.9999: 11.959 ms/op
                 listUser·p1.00:   12.337 ms/op

Iteration   3: 3.055 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.908 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.574 ms/op
                 listUser·p0.9999: 11.847 ms/op
                 listUser·p1.00:   12.976 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314790
  mean =      3.047 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 76 
    [ 1.250,  2.500) = 87015 
    [ 2.500,  3.750) = 187449 
    [ 3.750,  5.000) = 32223 
    [ 5.000,  6.250) = 6539 
    [ 6.250,  7.500) = 828 
    [ 7.500,  8.750) = 210 
    [ 8.750, 10.000) = 243 
    [10.000, 11.250) = 114 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =      9.355 ms/op
     p(99.9900) =     16.744 ms/op
     p(99.9990) =     18.153 ms/op
     p(99.9999) =     18.219 ms/op
    p(100.0000) =     18.219 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.572 ± 0.406  ops/ms
ClientPb.existUser                       thrpt       3  13.041 ± 1.014  ops/ms
ClientPb.getUser                         thrpt       3  12.653 ± 1.659  ops/ms
ClientPb.listUser                        thrpt       3  10.547 ± 1.871  ops/ms
ClientPb.createUser                       avgt       3   2.572 ± 0.185   ms/op
ClientPb.existUser                        avgt       3   2.442 ± 0.070   ms/op
ClientPb.getUser                          avgt       3   2.478 ± 0.323   ms/op
ClientPb.listUser                         avgt       3   2.994 ± 0.191   ms/op
ClientPb.createUser                     sample  377520   2.540 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.926           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.785           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.552           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.786           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.122           ms/op
ClientPb.existUser                      sample  389893   2.460 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.787           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.559           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.289           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.664           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.811           ms/op
ClientPb.getUser                        sample  381815   2.512 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.843           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.556           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.752           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.235           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.107           ms/op
ClientPb.listUser                       sample  314790   3.047 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.908           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.710           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.355           ms/op
ClientPb.listUser:listUser·p0.9999      sample          16.744           ms/op
ClientPb.listUser:listUser·p1.00        sample          18.219           ms/op
