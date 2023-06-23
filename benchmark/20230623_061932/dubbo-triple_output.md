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
# Warmup Iteration   1: 2.606 ops/ms
# Warmup Iteration   2: 6.568 ops/ms
# Warmup Iteration   3: 9.197 ops/ms
Iteration   1: 9.842 ops/ms
Iteration   2: 9.772 ops/ms
Iteration   3: 10.065 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.893 ±(99.9%) 2.791 ops/ms [Average]
  (min, avg, max) = (9.772, 9.893, 10.065), stdev = 0.153
  CI (99.9%): [7.102, 12.683] (assumes normal distribution)


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
# Warmup Iteration   1: 3.439 ops/ms
# Warmup Iteration   2: 9.521 ops/ms
# Warmup Iteration   3: 10.024 ops/ms
Iteration   1: 10.174 ops/ms
Iteration   2: 10.706 ops/ms
Iteration   3: 10.379 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.420 ±(99.9%) 4.898 ops/ms [Average]
  (min, avg, max) = (10.174, 10.420, 10.706), stdev = 0.268
  CI (99.9%): [5.522, 15.317] (assumes normal distribution)


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
# Warmup Iteration   1: 3.671 ops/ms
# Warmup Iteration   2: 9.152 ops/ms
# Warmup Iteration   3: 9.636 ops/ms
Iteration   1: 9.839 ops/ms
Iteration   2: 9.947 ops/ms
Iteration   3: 9.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.851 ±(99.9%) 1.648 ops/ms [Average]
  (min, avg, max) = (9.767, 9.851, 9.947), stdev = 0.090
  CI (99.9%): [8.204, 11.499] (assumes normal distribution)


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
# Warmup Iteration   1: 3.027 ops/ms
# Warmup Iteration   2: 7.211 ops/ms
# Warmup Iteration   3: 8.267 ops/ms
Iteration   1: 8.265 ops/ms
Iteration   2: 8.302 ops/ms
Iteration   3: 8.374 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.314 ±(99.9%) 1.011 ops/ms [Average]
  (min, avg, max) = (8.265, 8.314, 8.374), stdev = 0.055
  CI (99.9%): [7.302, 9.325] (assumes normal distribution)


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
# Warmup Iteration   1: 7.908 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.468 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.471 ±(99.9%) 0.005 ms/op
Iteration   1: 3.152 ±(99.9%) 0.004 ms/op
Iteration   2: 3.099 ±(99.9%) 0.007 ms/op
Iteration   3: 3.187 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.146 ±(99.9%) 0.816 ms/op [Average]
  (min, avg, max) = (3.099, 3.146, 3.187), stdev = 0.045
  CI (99.9%): [2.330, 3.962] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.213 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.410 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.192 ±(99.9%) 0.003 ms/op
Iteration   1: 3.103 ±(99.9%) 0.003 ms/op
Iteration   2: 3.012 ±(99.9%) 0.006 ms/op
Iteration   3: 3.055 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.057 ±(99.9%) 0.826 ms/op [Average]
  (min, avg, max) = (3.012, 3.057, 3.103), stdev = 0.045
  CI (99.9%): [2.230, 3.883] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.401 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.499 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.265 ±(99.9%) 0.003 ms/op
Iteration   1: 3.301 ±(99.9%) 0.003 ms/op
Iteration   2: 3.358 ±(99.9%) 0.007 ms/op
Iteration   3: 3.208 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.289 ±(99.9%) 1.382 ms/op [Average]
  (min, avg, max) = (3.208, 3.289, 3.358), stdev = 0.076
  CI (99.9%): [1.907, 4.671] (assumes normal distribution)


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
# Warmup Iteration   1: 9.942 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.306 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.845 ±(99.9%) 0.006 ms/op
Iteration   1: 3.876 ±(99.9%) 0.004 ms/op
Iteration   2: 3.764 ±(99.9%) 0.008 ms/op
Iteration   3: 3.780 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.807 ±(99.9%) 1.104 ms/op [Average]
  (min, avg, max) = (3.764, 3.807, 3.876), stdev = 0.060
  CI (99.9%): [2.703, 4.910] (assumes normal distribution)


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
# Warmup Iteration   1: 7.674 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.960 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.363 ±(99.9%) 0.010 ms/op
Iteration   1: 3.246 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.522 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.355 ms/op
                 createUser·p0.95:   3.457 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  17.531 ms/op
                 createUser·p0.9999: 19.628 ms/op
                 createUser·p1.00:   20.021 ms/op

Iteration   2: 3.243 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.380 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   5.169 ms/op
                 createUser·p0.999:  14.620 ms/op
                 createUser·p0.9999: 21.533 ms/op
                 createUser·p1.00:   22.118 ms/op

Iteration   3: 3.189 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.262 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  9.620 ms/op
                 createUser·p0.9999: 17.856 ms/op
                 createUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297406
  mean =      3.226 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23723 
    [ 2.500,  5.000) = 267604 
    [ 5.000,  7.500) = 5370 
    [ 7.500, 10.000) = 323 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.262 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     14.565 ms/op
     p(99.9900) =     21.135 ms/op
     p(99.9990) =     22.054 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


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
# Warmup Iteration   1: 6.783 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.338 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.220 ±(99.9%) 0.008 ms/op
Iteration   1: 3.128 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.282 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  10.856 ms/op
                 existUser·p0.9999: 21.234 ms/op
                 existUser·p1.00:   21.692 ms/op

Iteration   2: 3.219 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.425 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   5.775 ms/op
                 existUser·p0.999:  17.689 ms/op
                 existUser·p0.9999: 23.364 ms/op
                 existUser·p1.00:   24.609 ms/op

Iteration   3: 3.240 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.102 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   6.341 ms/op
                 existUser·p0.999:  10.202 ms/op
                 existUser·p0.9999: 21.959 ms/op
                 existUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 299982
  mean =      3.195 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22859 
    [ 2.500,  5.000) = 269523 
    [ 5.000,  7.500) = 6696 
    [ 7.500, 10.000) = 532 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 177 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.102 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     14.044 ms/op
     p(99.9900) =     22.020 ms/op
     p(99.9990) =     23.790 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


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
# Warmup Iteration   1: 8.082 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.492 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.290 ±(99.9%) 0.010 ms/op
Iteration   1: 3.318 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.174 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   5.087 ms/op
                 getUser·p0.99:   6.767 ms/op
                 getUser·p0.999:  15.857 ms/op
                 getUser·p0.9999: 20.459 ms/op
                 getUser·p1.00:   21.889 ms/op

Iteration   2: 3.183 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.360 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.637 ms/op
                 getUser·p0.99:   5.505 ms/op
                 getUser·p0.999:  9.178 ms/op
                 getUser·p0.9999: 22.477 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   3: 3.248 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.751 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.982 ms/op
                 getUser·p0.99:   5.833 ms/op
                 getUser·p0.999:  9.926 ms/op
                 getUser·p0.9999: 20.158 ms/op
                 getUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295266
  mean =      3.249 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9769 
    [ 2.500,  5.000) = 276804 
    [ 5.000,  7.500) = 7693 
    [ 7.500, 10.000) = 606 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.174 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      4.022 ms/op
     p(99.0000) =      6.332 ms/op
     p(99.9000) =     13.840 ms/op
     p(99.9900) =     22.051 ms/op
     p(99.9990) =     22.980 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


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
# Warmup Iteration   1: 9.201 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.285 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.894 ±(99.9%) 0.011 ms/op
Iteration   1: 3.973 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.604 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   7.578 ms/op
                 listUser·p0.999:  18.137 ms/op
                 listUser·p0.9999: 23.624 ms/op
                 listUser·p1.00:   24.281 ms/op

Iteration   2: 3.707 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.999 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.076 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  13.976 ms/op
                 listUser·p0.9999: 19.464 ms/op
                 listUser·p1.00:   20.972 ms/op

Iteration   3: 3.786 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.134 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  12.698 ms/op
                 listUser·p0.9999: 16.040 ms/op
                 listUser·p1.00:   16.089 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251312
  mean =      3.819 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 71 
    [ 2.500,  5.000) = 243731 
    [ 5.000,  7.500) = 5470 
    [ 7.500, 10.000) = 1331 
    [10.000, 12.500) = 309 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.604 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      7.242 ms/op
     p(99.9000) =     13.911 ms/op
     p(99.9900) =     21.983 ms/op
     p(99.9990) =     24.149 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.893 ± 2.791  ops/ms
ClientPb.existUser                       thrpt       3  10.420 ± 4.898  ops/ms
ClientPb.getUser                         thrpt       3   9.851 ± 1.648  ops/ms
ClientPb.listUser                        thrpt       3   8.314 ± 1.011  ops/ms
ClientPb.createUser                       avgt       3   3.146 ± 0.816   ms/op
ClientPb.existUser                        avgt       3   3.057 ± 0.826   ms/op
ClientPb.getUser                          avgt       3   3.289 ± 1.382   ms/op
ClientPb.listUser                         avgt       3   3.807 ± 1.104   ms/op
ClientPb.createUser                     sample  297406   3.226 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.262           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.510           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.961           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.456           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.565           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.135           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.118           ms/op
ClientPb.existUser                      sample  299982   3.195 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.102           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.551           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.076           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.825           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.044           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.020           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.609           ms/op
ClientPb.getUser                        sample  295266   3.249 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.174           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.022           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.332           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.840           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.051           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.167           ms/op
ClientPb.listUser                       sample  251312   3.819 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.604           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.719           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.141           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.242           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.911           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.983           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.281           ms/op
