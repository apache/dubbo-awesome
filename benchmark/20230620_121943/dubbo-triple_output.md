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
# Warmup Iteration   1: 1.793 ops/ms
# Warmup Iteration   2: 4.426 ops/ms
# Warmup Iteration   3: 8.468 ops/ms
Iteration   1: 8.898 ops/ms
Iteration   2: 8.804 ops/ms
Iteration   3: 9.319 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.007 ±(99.9%) 4.999 ops/ms [Average]
  (min, avg, max) = (8.804, 9.007, 9.319), stdev = 0.274
  CI (99.9%): [4.008, 14.006] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.642 ops/ms
# Warmup Iteration   2: 8.004 ops/ms
# Warmup Iteration   3: 9.179 ops/ms
Iteration   1: 9.501 ops/ms
Iteration   2: 9.470 ops/ms
Iteration   3: 9.436 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.469 ±(99.9%) 0.587 ops/ms [Average]
  (min, avg, max) = (9.436, 9.469, 9.501), stdev = 0.032
  CI (99.9%): [8.882, 10.056] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.417 ops/ms
# Warmup Iteration   2: 7.596 ops/ms
# Warmup Iteration   3: 8.921 ops/ms
Iteration   1: 9.273 ops/ms
Iteration   2: 9.224 ops/ms
Iteration   3: 9.122 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.206 ±(99.9%) 1.400 ops/ms [Average]
  (min, avg, max) = (9.122, 9.206, 9.273), stdev = 0.077
  CI (99.9%): [7.806, 10.607] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.442 ops/ms
# Warmup Iteration   2: 6.811 ops/ms
# Warmup Iteration   3: 7.683 ops/ms
Iteration   1: 7.573 ops/ms
Iteration   2: 7.722 ops/ms
Iteration   3: 7.765 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.687 ±(99.9%) 1.841 ops/ms [Average]
  (min, avg, max) = (7.573, 7.687, 7.765), stdev = 0.101
  CI (99.9%): [5.846, 9.528] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.449 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.004 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.756 ±(99.9%) 0.003 ms/op
Iteration   1: 3.565 ±(99.9%) 0.008 ms/op
Iteration   2: 3.462 ±(99.9%) 0.005 ms/op
Iteration   3: 3.496 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.508 ±(99.9%) 0.954 ms/op [Average]
  (min, avg, max) = (3.462, 3.508, 3.565), stdev = 0.052
  CI (99.9%): [2.553, 4.462] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.275 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.743 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.477 ±(99.9%) 0.006 ms/op
Iteration   1: 3.437 ±(99.9%) 0.011 ms/op
Iteration   2: 3.473 ±(99.9%) 0.006 ms/op
Iteration   3: 3.455 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.455 ±(99.9%) 0.327 ms/op [Average]
  (min, avg, max) = (3.437, 3.455, 3.473), stdev = 0.018
  CI (99.9%): [3.128, 3.782] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.841 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.774 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.643 ±(99.9%) 0.005 ms/op
Iteration   1: 3.604 ±(99.9%) 0.003 ms/op
Iteration   2: 3.567 ±(99.9%) 0.006 ms/op
Iteration   3: 3.484 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.552 ±(99.9%) 1.129 ms/op [Average]
  (min, avg, max) = (3.484, 3.552, 3.604), stdev = 0.062
  CI (99.9%): [2.423, 4.680] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 12.197 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.567 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.187 ±(99.9%) 0.006 ms/op
Iteration   1: 4.046 ±(99.9%) 0.010 ms/op
Iteration   2: 4.003 ±(99.9%) 0.016 ms/op
Iteration   3: 4.147 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.066 ±(99.9%) 1.345 ms/op [Average]
  (min, avg, max) = (4.003, 4.066, 4.147), stdev = 0.074
  CI (99.9%): [2.721, 5.410] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 11.088 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.300 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.884 ±(99.9%) 0.015 ms/op
Iteration   1: 3.563 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.528 ms/op
                 createUser·p0.50:   3.441 ms/op
                 createUser·p0.90:   4.104 ms/op
                 createUser·p0.95:   4.579 ms/op
                 createUser·p0.99:   6.242 ms/op
                 createUser·p0.999:  22.970 ms/op
                 createUser·p0.9999: 36.844 ms/op
                 createUser·p1.00:   37.618 ms/op

Iteration   2: 3.618 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.221 ms/op
                 createUser·p0.50:   3.457 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   6.029 ms/op
                 createUser·p0.999:  24.131 ms/op
                 createUser·p0.9999: 30.480 ms/op
                 createUser·p1.00:   31.556 ms/op

Iteration   3: 3.424 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.282 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   5.038 ms/op
                 createUser·p0.999:  24.432 ms/op
                 createUser·p0.9999: 33.663 ms/op
                 createUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271417
  mean =      3.533 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10051 
    [ 2.500,  5.000) = 255257 
    [ 5.000,  7.500) = 5110 
    [ 7.500, 10.000) = 527 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 99 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 33 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.221 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     23.153 ms/op
     p(99.9900) =     34.266 ms/op
     p(99.9990) =     37.552 ms/op
     p(99.9999) =     37.618 ms/op
    p(100.0000) =     37.618 ms/op


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
# Warmup Iteration   1: 11.308 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 3.972 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.613 ±(99.9%) 0.011 ms/op
Iteration   1: 3.324 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.561 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   5.767 ms/op
                 existUser·p0.999:  19.008 ms/op
                 existUser·p0.9999: 27.263 ms/op
                 existUser·p1.00:   28.803 ms/op

Iteration   2: 3.410 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.898 ms/op
                 existUser·p0.50:   3.391 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  22.923 ms/op
                 existUser·p0.9999: 38.838 ms/op
                 existUser·p1.00:   40.501 ms/op

Iteration   3: 3.354 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.210 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  9.503 ms/op
                 existUser·p0.9999: 27.114 ms/op
                 existUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285511
  mean =      3.362 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 280690 
    [ 5.000, 10.000) = 4476 
    [10.000, 15.000) = 89 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 136 
    [25.000, 30.000) = 88 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 30 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.210 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     10.928 ms/op
     p(99.9900) =     37.844 ms/op
     p(99.9990) =     39.698 ms/op
     p(99.9999) =     40.501 ms/op
    p(100.0000) =     40.501 ms/op


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
# Warmup Iteration   1: 10.646 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 3.812 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.735 ±(99.9%) 0.013 ms/op
Iteration   1: 3.496 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.823 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   7.160 ms/op
                 getUser·p0.999:  14.172 ms/op
                 getUser·p0.9999: 22.567 ms/op
                 getUser·p1.00:   23.265 ms/op

Iteration   2: 3.465 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.587 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  23.478 ms/op
                 getUser·p0.9999: 29.280 ms/op
                 getUser·p1.00:   30.933 ms/op

Iteration   3: 3.415 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.806 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  22.792 ms/op
                 getUser·p0.9999: 26.745 ms/op
                 getUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277342
  mean =      3.458 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 831 
    [ 2.500,  5.000) = 270638 
    [ 5.000,  7.500) = 4697 
    [ 7.500, 10.000) = 822 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.587 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =     14.232 ms/op
     p(99.9900) =     28.134 ms/op
     p(99.9990) =     30.552 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


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
# Warmup Iteration   1: 10.985 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.729 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.316 ±(99.9%) 0.015 ms/op
Iteration   1: 4.105 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.761 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   7.889 ms/op
                 listUser·p0.999:  20.388 ms/op
                 listUser·p0.9999: 23.757 ms/op
                 listUser·p1.00:   25.756 ms/op

Iteration   2: 4.038 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  16.521 ms/op
                 listUser·p0.9999: 20.283 ms/op
                 listUser·p1.00:   21.070 ms/op

Iteration   3: 4.066 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.273 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.479 ms/op
                 listUser·p0.999:  15.401 ms/op
                 listUser·p0.9999: 18.022 ms/op
                 listUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235876
  mean =      4.070 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 227099 
    [ 5.000,  7.500) = 6444 
    [ 7.500, 10.000) = 1483 
    [10.000, 12.500) = 301 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 220 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.761 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      7.479 ms/op
     p(99.9000) =     16.908 ms/op
     p(99.9900) =     22.768 ms/op
     p(99.9990) =     25.503 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.007 ± 4.999  ops/ms
ClientPb.existUser                       thrpt       3   9.469 ± 0.587  ops/ms
ClientPb.getUser                         thrpt       3   9.206 ± 1.400  ops/ms
ClientPb.listUser                        thrpt       3   7.687 ± 1.841  ops/ms
ClientPb.createUser                       avgt       3   3.508 ± 0.954   ms/op
ClientPb.existUser                        avgt       3   3.455 ± 0.327   ms/op
ClientPb.getUser                          avgt       3   3.552 ± 1.129   ms/op
ClientPb.listUser                         avgt       3   4.066 ± 1.345   ms/op
ClientPb.createUser                     sample  271417   3.533 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.221           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.428           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.071           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.383           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.947           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.153           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.266           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.618           ms/op
ClientPb.existUser                      sample  285511   3.362 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.210           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.342           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.871           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.685           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.928           ms/op
ClientPb.existUser:existUser·p0.9999    sample          37.844           ms/op
ClientPb.existUser:existUser·p1.00      sample          40.501           ms/op
ClientPb.getUser                        sample  277342   3.458 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.587           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.342           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.764           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.953           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.185           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.232           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.134           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.933           ms/op
ClientPb.listUser                       sample  235876   4.070 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.761           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.784           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.479           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.908           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.768           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.756           ms/op
