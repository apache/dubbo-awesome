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
# Warmup Iteration   1: 1.903 ops/ms
# Warmup Iteration   2: 5.086 ops/ms
# Warmup Iteration   3: 8.304 ops/ms
Iteration   1: 8.731 ops/ms
Iteration   2: 8.898 ops/ms
Iteration   3: 9.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.884 ±(99.9%) 2.686 ops/ms [Average]
  (min, avg, max) = (8.731, 8.884, 9.024), stdev = 0.147
  CI (99.9%): [6.198, 11.570] (assumes normal distribution)


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
# Warmup Iteration   1: 2.677 ops/ms
# Warmup Iteration   2: 7.992 ops/ms
# Warmup Iteration   3: 9.245 ops/ms
Iteration   1: 9.164 ops/ms
Iteration   2: 9.267 ops/ms
Iteration   3: 9.196 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.209 ±(99.9%) 0.962 ops/ms [Average]
  (min, avg, max) = (9.164, 9.209, 9.267), stdev = 0.053
  CI (99.9%): [8.247, 10.172] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.555 ops/ms
# Warmup Iteration   2: 8.400 ops/ms
# Warmup Iteration   3: 8.951 ops/ms
Iteration   1: 9.247 ops/ms
Iteration   2: 9.001 ops/ms
Iteration   3: 9.223 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.157 ±(99.9%) 2.474 ops/ms [Average]
  (min, avg, max) = (9.001, 9.157, 9.247), stdev = 0.136
  CI (99.9%): [6.683, 11.631] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.752 ops/ms
# Warmup Iteration   2: 7.104 ops/ms
# Warmup Iteration   3: 7.424 ops/ms
Iteration   1: 7.272 ops/ms
Iteration   2: 7.619 ops/ms
Iteration   3: 7.514 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.469 ±(99.9%) 3.245 ops/ms [Average]
  (min, avg, max) = (7.272, 7.469, 7.619), stdev = 0.178
  CI (99.9%): [4.224, 10.714] (assumes normal distribution)


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
# Warmup Iteration   1: 11.401 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.887 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.737 ±(99.9%) 0.003 ms/op
Iteration   1: 3.628 ±(99.9%) 0.007 ms/op
Iteration   2: 3.457 ±(99.9%) 0.007 ms/op
Iteration   3: 3.558 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.547 ±(99.9%) 1.570 ms/op [Average]
  (min, avg, max) = (3.457, 3.547, 3.628), stdev = 0.086
  CI (99.9%): [1.977, 5.117] (assumes normal distribution)


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
# Warmup Iteration   1: 11.400 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.716 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.623 ±(99.9%) 0.005 ms/op
Iteration   1: 3.383 ±(99.9%) 0.005 ms/op
Iteration   2: 3.358 ±(99.9%) 0.004 ms/op
Iteration   3: 3.475 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.405 ±(99.9%) 1.120 ms/op [Average]
  (min, avg, max) = (3.358, 3.405, 3.475), stdev = 0.061
  CI (99.9%): [2.285, 4.525] (assumes normal distribution)


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
# Warmup Iteration   1: 10.847 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.826 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.515 ±(99.9%) 0.003 ms/op
Iteration   1: 3.560 ±(99.9%) 0.004 ms/op
Iteration   2: 3.526 ±(99.9%) 0.005 ms/op
Iteration   3: 3.482 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.523 ±(99.9%) 0.715 ms/op [Average]
  (min, avg, max) = (3.482, 3.523, 3.560), stdev = 0.039
  CI (99.9%): [2.808, 4.238] (assumes normal distribution)


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
# Warmup Iteration   1: 10.153 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.565 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.367 ±(99.9%) 0.008 ms/op
Iteration   1: 4.254 ±(99.9%) 0.006 ms/op
Iteration   2: 4.156 ±(99.9%) 0.006 ms/op
Iteration   3: 4.243 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.218 ±(99.9%) 0.982 ms/op [Average]
  (min, avg, max) = (4.156, 4.218, 4.254), stdev = 0.054
  CI (99.9%): [3.235, 5.200] (assumes normal distribution)


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
# Warmup Iteration   1: 11.120 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.338 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.226 ±(99.9%) 0.021 ms/op
Iteration   1: 3.570 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.047 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.637 ms/op
                 createUser·p0.99:   6.939 ms/op
                 createUser·p0.999:  21.114 ms/op
                 createUser·p0.9999: 25.199 ms/op
                 createUser·p1.00:   28.672 ms/op

Iteration   2: 3.638 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.501 ms/op
                 createUser·p0.50:   3.486 ms/op
                 createUser·p0.90:   4.174 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   7.520 ms/op
                 createUser·p0.999:  21.758 ms/op
                 createUser·p0.9999: 24.248 ms/op
                 createUser·p1.00:   24.969 ms/op

Iteration   3: 3.678 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.337 ms/op
                 createUser·p0.50:   3.490 ms/op
                 createUser·p0.90:   4.186 ms/op
                 createUser·p0.95:   4.579 ms/op
                 createUser·p0.99:   7.676 ms/op
                 createUser·p0.999:  23.855 ms/op
                 createUser·p0.9999: 31.326 ms/op
                 createUser·p1.00:   32.768 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 264663
  mean =      3.628 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1937 
    [ 2.500,  5.000) = 253117 
    [ 5.000,  7.500) = 7109 
    [ 7.500, 10.000) = 1845 
    [10.000, 12.500) = 246 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 134 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.047 ms/op
     p(50.0000) =      3.449 ms/op
     p(90.0000) =      4.153 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     21.463 ms/op
     p(99.9900) =     29.967 ms/op
     p(99.9990) =     31.828 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


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
# Warmup Iteration   1: 9.011 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.755 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.528 ±(99.9%) 0.010 ms/op
Iteration   1: 3.406 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.163 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   4.170 ms/op
                 existUser·p0.99:   6.475 ms/op
                 existUser·p0.999:  10.357 ms/op
                 existUser·p0.9999: 23.646 ms/op
                 existUser·p1.00:   24.052 ms/op

Iteration   2: 3.488 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.108 ms/op
                 existUser·p0.50:   3.375 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   4.415 ms/op
                 existUser·p0.99:   7.897 ms/op
                 existUser·p0.999:  23.632 ms/op
                 existUser·p0.9999: 27.329 ms/op
                 existUser·p1.00:   27.853 ms/op

Iteration   3: 3.434 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.145 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   6.964 ms/op
                 existUser·p0.999:  24.183 ms/op
                 existUser·p0.9999: 27.034 ms/op
                 existUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 278845
  mean =      3.443 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7656 
    [ 2.500,  5.000) = 263112 
    [ 5.000,  7.500) = 5811 
    [ 7.500, 10.000) = 1667 
    [10.000, 12.500) = 244 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 117 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      7.250 ms/op
     p(99.9000) =     14.828 ms/op
     p(99.9900) =     27.041 ms/op
     p(99.9990) =     27.637 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


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
# Warmup Iteration   1: 11.573 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 3.962 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.856 ±(99.9%) 0.014 ms/op
Iteration   1: 3.700 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.395 ms/op
                 getUser·p0.50:   3.486 ms/op
                 getUser·p0.90:   4.104 ms/op
                 getUser·p0.95:   4.850 ms/op
                 getUser·p0.99:   7.815 ms/op
                 getUser·p0.999:  21.922 ms/op
                 getUser·p0.9999: 24.588 ms/op
                 getUser·p1.00:   25.985 ms/op

Iteration   2: 3.619 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.430 ms/op
                 getUser·p0.50:   3.465 ms/op
                 getUser·p0.90:   3.994 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   7.619 ms/op
                 getUser·p0.999:  23.003 ms/op
                 getUser·p0.9999: 31.031 ms/op
                 getUser·p1.00:   33.194 ms/op

Iteration   3: 3.588 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.200 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   7.242 ms/op
                 getUser·p0.999:  12.042 ms/op
                 getUser·p0.9999: 29.426 ms/op
                 getUser·p1.00:   30.015 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 263921
  mean =      3.635 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 930 
    [ 2.500,  5.000) = 253396 
    [ 5.000,  7.500) = 6577 
    [ 7.500, 10.000) = 2178 
    [10.000, 12.500) = 410 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 134 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.200 ms/op
     p(50.0000) =      3.461 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      7.643 ms/op
     p(99.9000) =     18.615 ms/op
     p(99.9900) =     30.003 ms/op
     p(99.9990) =     32.560 ms/op
     p(99.9999) =     33.194 ms/op
    p(100.0000) =     33.194 ms/op


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
# Warmup Iteration   1: 11.754 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 4.747 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.375 ±(99.9%) 0.014 ms/op
Iteration   1: 4.277 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.561 ms/op
                 listUser·p0.50:   4.071 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.136 ms/op
                 listUser·p0.99:   8.864 ms/op
                 listUser·p0.999:  21.365 ms/op
                 listUser·p0.9999: 24.971 ms/op
                 listUser·p1.00:   25.756 ms/op

Iteration   2: 4.269 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.662 ms/op
                 listUser·p0.50:   4.051 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   8.305 ms/op
                 listUser·p0.999:  15.843 ms/op
                 listUser·p0.9999: 18.072 ms/op
                 listUser·p1.00:   19.988 ms/op

Iteration   3: 4.254 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.384 ms/op
                 listUser·p0.50:   4.084 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.202 ms/op
                 listUser·p0.99:   8.585 ms/op
                 listUser·p0.999:  14.645 ms/op
                 listUser·p0.9999: 17.007 ms/op
                 listUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 224825
  mean =      4.267 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 211550 
    [ 5.000,  7.500) = 9430 
    [ 7.500, 10.000) = 2684 
    [10.000, 12.500) = 415 
    [12.500, 15.000) = 330 
    [15.000, 17.500) = 245 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.561 ms/op
     p(50.0000) =      4.071 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.128 ms/op
     p(99.0000) =      8.569 ms/op
     p(99.9000) =     16.155 ms/op
     p(99.9900) =     24.071 ms/op
     p(99.9990) =     25.354 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.884 ± 2.686  ops/ms
ClientPb.existUser                       thrpt       3   9.209 ± 0.962  ops/ms
ClientPb.getUser                         thrpt       3   9.157 ± 2.474  ops/ms
ClientPb.listUser                        thrpt       3   7.469 ± 3.245  ops/ms
ClientPb.createUser                       avgt       3   3.547 ± 1.570   ms/op
ClientPb.existUser                        avgt       3   3.405 ± 1.120   ms/op
ClientPb.getUser                          avgt       3   3.523 ± 0.715   ms/op
ClientPb.listUser                         avgt       3   4.218 ± 0.982   ms/op
ClientPb.createUser                     sample  264663   3.628 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.047           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.449           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.153           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.547           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.414           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.463           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.967           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.768           ms/op
ClientPb.existUser                      sample  278845   3.443 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.108           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.330           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.768           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.190           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.250           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.828           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.041           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.853           ms/op
ClientPb.getUser                        sample  263921   3.635 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.200           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.461           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.014           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.448           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.643           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.615           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.003           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.194           ms/op
ClientPb.listUser                       sample  224825   4.267 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.561           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.071           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.128           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.569           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.155           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.071           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.756           ms/op
