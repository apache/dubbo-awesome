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
# Warmup Iteration   1: 2.243 ops/ms
# Warmup Iteration   2: 5.820 ops/ms
# Warmup Iteration   3: 8.757 ops/ms
Iteration   1: 9.154 ops/ms
Iteration   2: 9.337 ops/ms
Iteration   3: 9.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.377 ±(99.9%) 4.488 ops/ms [Average]
  (min, avg, max) = (9.154, 9.377, 9.641), stdev = 0.246
  CI (99.9%): [4.889, 13.865] (assumes normal distribution)


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
# Warmup Iteration   1: 3.868 ops/ms
# Warmup Iteration   2: 9.398 ops/ms
# Warmup Iteration   3: 9.536 ops/ms
Iteration   1: 9.659 ops/ms
Iteration   2: 9.788 ops/ms
Iteration   3: 10.109 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.852 ±(99.9%) 4.224 ops/ms [Average]
  (min, avg, max) = (9.659, 9.852, 10.109), stdev = 0.232
  CI (99.9%): [5.628, 14.076] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.495 ops/ms
# Warmup Iteration   2: 8.739 ops/ms
# Warmup Iteration   3: 8.943 ops/ms
Iteration   1: 9.473 ops/ms
Iteration   2: 9.655 ops/ms
Iteration   3: 9.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.552 ±(99.9%) 1.700 ops/ms [Average]
  (min, avg, max) = (9.473, 9.552, 9.655), stdev = 0.093
  CI (99.9%): [7.853, 11.252] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.804 ops/ms
# Warmup Iteration   2: 7.223 ops/ms
# Warmup Iteration   3: 7.899 ops/ms
Iteration   1: 7.965 ops/ms
Iteration   2: 8.058 ops/ms
Iteration   3: 7.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.907 ±(99.9%) 3.405 ops/ms [Average]
  (min, avg, max) = (7.698, 7.907, 8.058), stdev = 0.187
  CI (99.9%): [4.502, 11.312] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 8.608 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.647 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.735 ±(99.9%) 0.007 ms/op
Iteration   1: 3.426 ±(99.9%) 0.009 ms/op
Iteration   2: 3.397 ±(99.9%) 0.010 ms/op
Iteration   3: 3.314 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.379 ±(99.9%) 1.063 ms/op [Average]
  (min, avg, max) = (3.314, 3.379, 3.426), stdev = 0.058
  CI (99.9%): [2.317, 4.442] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 9.022 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.632 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.335 ±(99.9%) 0.007 ms/op
Iteration   1: 3.190 ±(99.9%) 0.008 ms/op
Iteration   2: 3.251 ±(99.9%) 0.009 ms/op
Iteration   3: 3.224 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.222 ±(99.9%) 0.560 ms/op [Average]
  (min, avg, max) = (3.190, 3.222, 3.251), stdev = 0.031
  CI (99.9%): [2.662, 3.782] (assumes normal distribution)


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
# Warmup Iteration   1: 8.355 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.812 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.492 ±(99.9%) 0.005 ms/op
Iteration   1: 3.471 ±(99.9%) 0.007 ms/op
Iteration   2: 3.465 ±(99.9%) 0.008 ms/op
Iteration   3: 3.383 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.439 ±(99.9%) 0.898 ms/op [Average]
  (min, avg, max) = (3.383, 3.439, 3.471), stdev = 0.049
  CI (99.9%): [2.542, 4.337] (assumes normal distribution)


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
# Warmup Iteration   1: 8.820 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.285 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.219 ±(99.9%) 0.006 ms/op
Iteration   1: 4.138 ±(99.9%) 0.011 ms/op
Iteration   2: 3.960 ±(99.9%) 0.014 ms/op
Iteration   3: 3.912 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.003 ±(99.9%) 2.175 ms/op [Average]
  (min, avg, max) = (3.912, 4.003, 4.138), stdev = 0.119
  CI (99.9%): [1.829, 6.178] (assumes normal distribution)


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
# Warmup Iteration   1: 10.253 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 4.003 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.561 ±(99.9%) 0.010 ms/op
Iteration   1: 3.573 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.593 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   4.358 ms/op
                 createUser·p0.95:   5.587 ms/op
                 createUser·p0.99:   6.791 ms/op
                 createUser·p0.999:  21.332 ms/op
                 createUser·p0.9999: 30.017 ms/op
                 createUser·p1.00:   30.999 ms/op

Iteration   2: 3.327 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.778 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.680 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  21.932 ms/op
                 createUser·p0.9999: 25.244 ms/op
                 createUser·p1.00:   26.051 ms/op

Iteration   3: 3.452 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.186 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   6.128 ms/op
                 createUser·p0.999:  21.156 ms/op
                 createUser·p0.9999: 26.116 ms/op
                 createUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278515
  mean =      3.448 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13859 
    [ 2.500,  5.000) = 252518 
    [ 5.000,  7.500) = 10957 
    [ 7.500, 10.000) = 651 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 146 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      6.521 ms/op
     p(99.9000) =     21.282 ms/op
     p(99.9900) =     27.956 ms/op
     p(99.9990) =     30.783 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.911 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.506 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.325 ±(99.9%) 0.007 ms/op
Iteration   1: 3.332 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.483 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   4.047 ms/op
                 existUser·p0.99:   6.414 ms/op
                 existUser·p0.999:  18.675 ms/op
                 existUser·p0.9999: 24.642 ms/op
                 existUser·p1.00:   25.821 ms/op

Iteration   2: 3.293 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.274 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  10.106 ms/op
                 existUser·p0.9999: 24.314 ms/op
                 existUser·p1.00:   25.002 ms/op

Iteration   3: 3.309 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.120 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  14.759 ms/op
                 existUser·p0.9999: 26.160 ms/op
                 existUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289862
  mean =      3.311 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7811 
    [ 2.500,  5.000) = 276614 
    [ 5.000,  7.500) = 4530 
    [ 7.500, 10.000) = 512 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.120 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     16.712 ms/op
     p(99.9900) =     24.872 ms/op
     p(99.9990) =     26.742 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


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
# Warmup Iteration   1: 8.236 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.993 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.595 ±(99.9%) 0.011 ms/op
Iteration   1: 3.484 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.450 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.977 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   6.767 ms/op
                 getUser·p0.999:  20.873 ms/op
                 getUser·p0.9999: 58.774 ms/op
                 getUser·p1.00:   59.965 ms/op

Iteration   2: 3.592 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.270 ms/op
                 getUser·p0.50:   3.473 ms/op
                 getUser·p0.90:   4.059 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   6.078 ms/op
                 getUser·p0.999:  21.496 ms/op
                 getUser·p0.9999: 27.443 ms/op
                 getUser·p1.00:   28.017 ms/op

Iteration   3: 3.540 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.894 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   4.076 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  22.483 ms/op
                 getUser·p0.9999: 35.388 ms/op
                 getUser·p1.00:   36.438 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271143
  mean =      3.538 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 262095 
    [ 5.000, 10.000) = 8601 
    [10.000, 15.000) = 140 
    [15.000, 20.000) = 19 
    [20.000, 25.000) = 156 
    [25.000, 30.000) = 67 
    [30.000, 35.000) = 23 
    [35.000, 40.000) = 10 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.270 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.324 ms/op
     p(99.9000) =     21.229 ms/op
     p(99.9900) =     56.878 ms/op
     p(99.9990) =     59.113 ms/op
     p(99.9999) =     59.965 ms/op
    p(100.0000) =     59.965 ms/op


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
# Warmup Iteration   1: 11.237 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.511 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.039 ±(99.9%) 0.012 ms/op
Iteration   1: 4.055 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.341 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.471 ms/op
                 listUser·p0.999:  23.232 ms/op
                 listUser·p0.9999: 29.265 ms/op
                 listUser·p1.00:   30.573 ms/op

Iteration   2: 4.070 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.837 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   8.094 ms/op
                 listUser·p0.999:  15.463 ms/op
                 listUser·p0.9999: 20.597 ms/op
                 listUser·p1.00:   21.529 ms/op

Iteration   3: 3.916 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.083 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.186 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   7.765 ms/op
                 listUser·p0.999:  15.865 ms/op
                 listUser·p0.9999: 19.071 ms/op
                 listUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239207
  mean =      4.013 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 230003 
    [ 5.000,  7.500) = 6406 
    [ 7.500, 10.000) = 1873 
    [10.000, 12.500) = 251 
    [12.500, 15.000) = 253 
    [15.000, 17.500) = 155 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.341 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      7.750 ms/op
     p(99.9000) =     17.091 ms/op
     p(99.9900) =     27.336 ms/op
     p(99.9990) =     30.154 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.377 ± 4.488  ops/ms
ClientPb.existUser                       thrpt       3   9.852 ± 4.224  ops/ms
ClientPb.getUser                         thrpt       3   9.552 ± 1.700  ops/ms
ClientPb.listUser                        thrpt       3   7.907 ± 3.405  ops/ms
ClientPb.createUser                       avgt       3   3.379 ± 1.063   ms/op
ClientPb.existUser                        avgt       3   3.222 ± 0.560   ms/op
ClientPb.getUser                          avgt       3   3.439 ± 0.898   ms/op
ClientPb.listUser                         avgt       3   4.003 ± 2.175   ms/op
ClientPb.createUser                     sample  278515   3.448 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.593           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.355           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.571           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.521           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.282           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.956           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.999           ms/op
ClientPb.existUser                      sample  289862   3.311 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.120           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.211           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.953           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.685           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.712           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.872           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.804           ms/op
ClientPb.getUser                        sample  271143   3.538 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.270           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.379           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.415           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.324           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.229           ms/op
ClientPb.getUser:getUser·p0.9999        sample          56.878           ms/op
ClientPb.getUser:getUser·p1.00          sample          59.965           ms/op
ClientPb.listUser                       sample  239207   4.013 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.341           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.838           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.678           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.750           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.091           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.336           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.573           ms/op
