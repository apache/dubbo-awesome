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
# Warmup Iteration   1: 1.082 ops/ms
# Warmup Iteration   2: 2.185 ops/ms
# Warmup Iteration   3: 5.141 ops/ms
Iteration   1: 5.393 ops/ms
Iteration   2: 5.781 ops/ms
Iteration   3: 5.690 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.621 ±(99.9%) 3.707 ops/ms [Average]
  (min, avg, max) = (5.393, 5.621, 5.781), stdev = 0.203
  CI (99.9%): [1.915, 9.328] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.366 ops/ms
# Warmup Iteration   2: 4.498 ops/ms
# Warmup Iteration   3: 5.826 ops/ms
Iteration   1: 6.136 ops/ms
Iteration   2: 6.226 ops/ms
Iteration   3: 6.145 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.169 ±(99.9%) 0.906 ops/ms [Average]
  (min, avg, max) = (6.136, 6.169, 6.226), stdev = 0.050
  CI (99.9%): [5.263, 7.074] (assumes normal distribution)


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
# Warmup Iteration   1: 1.437 ops/ms
# Warmup Iteration   2: 4.284 ops/ms
# Warmup Iteration   3: 5.893 ops/ms
Iteration   1: 5.749 ops/ms
Iteration   2: 5.862 ops/ms
Iteration   3: 6.130 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.914 ±(99.9%) 3.566 ops/ms [Average]
  (min, avg, max) = (5.749, 5.914, 6.130), stdev = 0.195
  CI (99.9%): [2.348, 9.479] (assumes normal distribution)


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
# Warmup Iteration   1: 1.350 ops/ms
# Warmup Iteration   2: 4.420 ops/ms
# Warmup Iteration   3: 4.936 ops/ms
Iteration   1: 5.181 ops/ms
Iteration   2: 5.319 ops/ms
Iteration   3: 5.264 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.255 ±(99.9%) 1.269 ops/ms [Average]
  (min, avg, max) = (5.181, 5.255, 5.319), stdev = 0.070
  CI (99.9%): [3.986, 6.523] (assumes normal distribution)


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
# Warmup Iteration   1: 19.180 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 6.690 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.407 ±(99.9%) 0.012 ms/op
Iteration   1: 5.544 ±(99.9%) 0.010 ms/op
Iteration   2: 5.304 ±(99.9%) 0.009 ms/op
Iteration   3: 5.325 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.391 ±(99.9%) 2.422 ms/op [Average]
  (min, avg, max) = (5.304, 5.391, 5.544), stdev = 0.133
  CI (99.9%): [2.969, 7.813] (assumes normal distribution)


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
# Warmup Iteration   1: 17.873 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 6.283 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.258 ±(99.9%) 0.019 ms/op
Iteration   1: 5.313 ±(99.9%) 0.011 ms/op
Iteration   2: 5.098 ±(99.9%) 0.011 ms/op
Iteration   3: 5.115 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.175 ±(99.9%) 2.183 ms/op [Average]
  (min, avg, max) = (5.098, 5.175, 5.313), stdev = 0.120
  CI (99.9%): [2.992, 7.358] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 16.356 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 6.210 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.370 ±(99.9%) 0.011 ms/op
Iteration   1: 5.718 ±(99.9%) 0.012 ms/op
Iteration   2: 5.312 ±(99.9%) 0.011 ms/op
Iteration   3: 5.360 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.463 ±(99.9%) 4.048 ms/op [Average]
  (min, avg, max) = (5.312, 5.463, 5.718), stdev = 0.222
  CI (99.9%): [1.415, 9.511] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 21.194 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 7.476 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 6.022 ±(99.9%) 0.014 ms/op
Iteration   1: 6.318 ±(99.9%) 0.010 ms/op
Iteration   2: 5.971 ±(99.9%) 0.022 ms/op
Iteration   3: 6.074 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.121 ±(99.9%) 3.251 ms/op [Average]
  (min, avg, max) = (5.971, 6.121, 6.318), stdev = 0.178
  CI (99.9%): [2.869, 9.372] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 18.094 ±(99.9%) 0.265 ms/op
# Warmup Iteration   2: 6.624 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 6.042 ±(99.9%) 0.028 ms/op
Iteration   1: 5.362 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.310 ms/op
                 createUser·p0.50:   5.095 ms/op
                 createUser·p0.90:   6.488 ms/op
                 createUser·p0.95:   7.193 ms/op
                 createUser·p0.99:   10.346 ms/op
                 createUser·p0.999:  23.757 ms/op
                 createUser·p0.9999: 31.524 ms/op
                 createUser·p1.00:   32.408 ms/op

Iteration   2: 5.466 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.429 ms/op
                 createUser·p0.50:   5.194 ms/op
                 createUser·p0.90:   6.570 ms/op
                 createUser·p0.95:   7.487 ms/op
                 createUser·p0.99:   10.994 ms/op
                 createUser·p0.999:  28.604 ms/op
                 createUser·p0.9999: 32.347 ms/op
                 createUser·p1.00:   32.801 ms/op

Iteration   3: 5.440 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   5.194 ms/op
                 createUser·p0.90:   6.513 ms/op
                 createUser·p0.95:   7.512 ms/op
                 createUser·p0.99:   9.880 ms/op
                 createUser·p0.999:  27.600 ms/op
                 createUser·p0.9999: 32.543 ms/op
                 createUser·p1.00:   32.702 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 176938
  mean =      5.422 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 69370 
    [ 5.000,  7.500) = 99078 
    [ 7.500, 10.000) = 6428 
    [10.000, 12.500) = 1229 
    [12.500, 15.000) = 481 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 69 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      5.161 ms/op
     p(90.0000) =      6.521 ms/op
     p(95.0000) =      7.414 ms/op
     p(99.0000) =     10.322 ms/op
     p(99.9000) =     24.347 ms/op
     p(99.9900) =     32.034 ms/op
     p(99.9990) =     32.750 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.367 ±(99.9%) 0.292 ms/op
# Warmup Iteration   2: 6.155 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.238 ±(99.9%) 0.019 ms/op
Iteration   1: 5.056 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.195 ms/op
                 existUser·p0.50:   4.768 ms/op
                 existUser·p0.90:   6.226 ms/op
                 existUser·p0.95:   7.086 ms/op
                 existUser·p0.99:   9.863 ms/op
                 existUser·p0.999:  20.341 ms/op
                 existUser·p0.9999: 25.647 ms/op
                 existUser·p1.00:   27.591 ms/op

Iteration   2: 5.221 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.437 ms/op
                 existUser·p0.50:   4.989 ms/op
                 existUser·p0.90:   6.242 ms/op
                 existUser·p0.95:   6.873 ms/op
                 existUser·p0.99:   9.811 ms/op
                 existUser·p0.999:  25.028 ms/op
                 existUser·p0.9999: 28.877 ms/op
                 existUser·p1.00:   29.852 ms/op

Iteration   3: 5.075 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.929 ms/op
                 existUser·p0.50:   4.792 ms/op
                 existUser·p0.90:   6.152 ms/op
                 existUser·p0.95:   6.832 ms/op
                 existUser·p0.99:   9.372 ms/op
                 existUser·p0.999:  17.695 ms/op
                 existUser·p0.9999: 30.802 ms/op
                 existUser·p1.00:   32.080 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 187529
  mean =      5.116 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 107425 
    [ 5.000,  7.500) = 73703 
    [ 7.500, 10.000) = 4734 
    [10.000, 12.500) = 978 
    [12.500, 15.000) = 335 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.929 ms/op
     p(50.0000) =      4.850 ms/op
     p(90.0000) =      6.210 ms/op
     p(95.0000) =      6.914 ms/op
     p(99.0000) =      9.683 ms/op
     p(99.9000) =     18.693 ms/op
     p(99.9900) =     29.286 ms/op
     p(99.9990) =     31.936 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 19.268 ±(99.9%) 0.324 ms/op
# Warmup Iteration   2: 6.449 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.436 ±(99.9%) 0.020 ms/op
Iteration   1: 5.440 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.004 ms/op
                 getUser·p0.50:   5.177 ms/op
                 getUser·p0.90:   6.873 ms/op
                 getUser·p0.95:   7.537 ms/op
                 getUser·p0.99:   10.355 ms/op
                 getUser·p0.999:  23.107 ms/op
                 getUser·p0.9999: 26.085 ms/op
                 getUser·p1.00:   27.099 ms/op

Iteration   2: 5.303 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.942 ms/op
                 getUser·p0.50:   4.940 ms/op
                 getUser·p0.90:   6.529 ms/op
                 getUser·p0.95:   7.938 ms/op
                 getUser·p0.99:   11.452 ms/op
                 getUser·p0.999:  23.445 ms/op
                 getUser·p0.9999: 30.603 ms/op
                 getUser·p1.00:   30.704 ms/op

Iteration   3: 5.461 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.437 ms/op
                 getUser·p0.50:   5.235 ms/op
                 getUser·p0.90:   6.644 ms/op
                 getUser·p0.95:   7.382 ms/op
                 getUser·p0.99:   9.929 ms/op
                 getUser·p0.999:  28.321 ms/op
                 getUser·p0.9999: 31.400 ms/op
                 getUser·p1.00:   32.473 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 177891
  mean =      5.400 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 80391 
    [ 5.000,  7.500) = 88015 
    [ 7.500, 10.000) = 6965 
    [10.000, 12.500) = 1770 
    [12.500, 15.000) = 410 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.004 ms/op
     p(50.0000) =      5.112 ms/op
     p(90.0000) =      6.717 ms/op
     p(95.0000) =      7.594 ms/op
     p(99.0000) =     10.650 ms/op
     p(99.9000) =     23.495 ms/op
     p(99.9900) =     30.743 ms/op
     p(99.9990) =     31.937 ms/op
     p(99.9999) =     32.473 ms/op
    p(100.0000) =     32.473 ms/op


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
# Warmup Iteration   1: 17.943 ±(99.9%) 0.304 ms/op
# Warmup Iteration   2: 6.855 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 6.679 ±(99.9%) 0.028 ms/op
Iteration   1: 6.102 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.433 ms/op
                 listUser·p0.50:   5.652 ms/op
                 listUser·p0.90:   7.512 ms/op
                 listUser·p0.95:   8.700 ms/op
                 listUser·p0.99:   11.943 ms/op
                 listUser·p0.999:  24.530 ms/op
                 listUser·p0.9999: 28.042 ms/op
                 listUser·p1.00:   28.443 ms/op

Iteration   2: 6.081 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.490 ms/op
                 listUser·p0.50:   5.841 ms/op
                 listUser·p0.90:   7.111 ms/op
                 listUser·p0.95:   8.167 ms/op
                 listUser·p0.99:   11.452 ms/op
                 listUser·p0.999:  23.429 ms/op
                 listUser·p0.9999: 28.573 ms/op
                 listUser·p1.00:   30.015 ms/op

Iteration   3: 6.111 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.372 ms/op
                 listUser·p0.50:   5.841 ms/op
                 listUser·p0.90:   7.406 ms/op
                 listUser·p0.95:   8.290 ms/op
                 listUser·p0.99:   10.879 ms/op
                 listUser·p0.999:  21.097 ms/op
                 listUser·p0.9999: 24.969 ms/op
                 listUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 157310
  mean =      6.098 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 17936 
    [ 5.000,  7.500) = 125481 
    [ 7.500, 10.000) = 11139 
    [10.000, 12.500) = 1774 
    [12.500, 15.000) = 487 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 134 
    [22.500, 25.000) = 121 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.372 ms/op
     p(50.0000) =      5.800 ms/op
     p(90.0000) =      7.348 ms/op
     p(95.0000) =      8.389 ms/op
     p(99.0000) =     11.370 ms/op
     p(99.9000) =     23.429 ms/op
     p(99.9900) =     27.886 ms/op
     p(99.9990) =     29.602 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.621 ± 3.707  ops/ms
ClientPb.existUser                       thrpt       3   6.169 ± 0.906  ops/ms
ClientPb.getUser                         thrpt       3   5.914 ± 3.566  ops/ms
ClientPb.listUser                        thrpt       3   5.255 ± 1.269  ops/ms
ClientPb.createUser                       avgt       3   5.391 ± 2.422   ms/op
ClientPb.existUser                        avgt       3   5.175 ± 2.183   ms/op
ClientPb.getUser                          avgt       3   5.463 ± 4.048   ms/op
ClientPb.listUser                         avgt       3   6.121 ± 3.251   ms/op
ClientPb.createUser                     sample  176938   5.422 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.053           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.161           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.521           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.414           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.322           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.347           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.034           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.801           ms/op
ClientPb.existUser                      sample  187529   5.116 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.929           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.850           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.210           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.914           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.683           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.693           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.286           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.080           ms/op
ClientPb.getUser                        sample  177891   5.400 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.004           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.112           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.717           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.594           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.650           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.495           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.743           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.473           ms/op
ClientPb.listUser                       sample  157310   6.098 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.372           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.800           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.348           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.389           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.370           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.429           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.886           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.015           ms/op
