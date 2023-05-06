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
# Warmup Iteration   1: 2.683 ops/ms
# Warmup Iteration   2: 5.807 ops/ms
# Warmup Iteration   3: 8.759 ops/ms
Iteration   1: 9.677 ops/ms
Iteration   2: 9.864 ops/ms
Iteration   3: 10.234 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.925 ±(99.9%) 5.171 ops/ms [Average]
  (min, avg, max) = (9.677, 9.925, 10.234), stdev = 0.283
  CI (99.9%): [4.754, 15.095] (assumes normal distribution)


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
# Warmup Iteration   1: 3.246 ops/ms
# Warmup Iteration   2: 8.914 ops/ms
# Warmup Iteration   3: 9.990 ops/ms
Iteration   1: 10.457 ops/ms
Iteration   2: 10.251 ops/ms
Iteration   3: 10.402 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.370 ±(99.9%) 1.949 ops/ms [Average]
  (min, avg, max) = (10.251, 10.370, 10.457), stdev = 0.107
  CI (99.9%): [8.421, 12.319] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.109 ops/ms
# Warmup Iteration   2: 9.000 ops/ms
# Warmup Iteration   3: 9.802 ops/ms
Iteration   1: 9.932 ops/ms
Iteration   2: 10.163 ops/ms
Iteration   3: 9.933 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.009 ±(99.9%) 2.428 ops/ms [Average]
  (min, avg, max) = (9.932, 10.009, 10.163), stdev = 0.133
  CI (99.9%): [7.582, 12.437] (assumes normal distribution)


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
# Warmup Iteration   1: 2.899 ops/ms
# Warmup Iteration   2: 7.142 ops/ms
# Warmup Iteration   3: 8.137 ops/ms
Iteration   1: 8.616 ops/ms
Iteration   2: 8.406 ops/ms
Iteration   3: 8.518 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.513 ±(99.9%) 1.912 ops/ms [Average]
  (min, avg, max) = (8.406, 8.513, 8.616), stdev = 0.105
  CI (99.9%): [6.601, 10.426] (assumes normal distribution)


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
# Warmup Iteration   1: 7.903 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.484 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.324 ±(99.9%) 0.003 ms/op
Iteration   1: 3.137 ±(99.9%) 0.003 ms/op
Iteration   2: 3.205 ±(99.9%) 0.005 ms/op
Iteration   3: 3.097 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.146 ±(99.9%) 1.002 ms/op [Average]
  (min, avg, max) = (3.097, 3.146, 3.205), stdev = 0.055
  CI (99.9%): [2.144, 4.148] (assumes normal distribution)


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
# Warmup Iteration   1: 6.882 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.368 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.005 ms/op
Iteration   1: 3.178 ±(99.9%) 0.005 ms/op
Iteration   2: 3.232 ±(99.9%) 0.008 ms/op
Iteration   3: 3.063 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.158 ±(99.9%) 1.576 ms/op [Average]
  (min, avg, max) = (3.063, 3.158, 3.232), stdev = 0.086
  CI (99.9%): [1.582, 4.733] (assumes normal distribution)


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
# Warmup Iteration   1: 7.650 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.739 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.300 ±(99.9%) 0.004 ms/op
Iteration   1: 3.180 ±(99.9%) 0.001 ms/op
Iteration   2: 3.256 ±(99.9%) 0.004 ms/op
Iteration   3: 3.327 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.255 ±(99.9%) 1.343 ms/op [Average]
  (min, avg, max) = (3.180, 3.255, 3.327), stdev = 0.074
  CI (99.9%): [1.912, 4.598] (assumes normal distribution)


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
# Warmup Iteration   1: 8.645 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.040 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.866 ±(99.9%) 0.007 ms/op
Iteration   1: 3.707 ±(99.9%) 0.008 ms/op
Iteration   2: 3.791 ±(99.9%) 0.005 ms/op
Iteration   3: 3.822 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.773 ±(99.9%) 1.082 ms/op [Average]
  (min, avg, max) = (3.707, 3.773, 3.822), stdev = 0.059
  CI (99.9%): [2.691, 4.856] (assumes normal distribution)


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
# Warmup Iteration   1: 7.815 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.816 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.169 ±(99.9%) 0.008 ms/op
Iteration   1: 3.147 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.511 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.391 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   5.339 ms/op
                 createUser·p0.999:  16.099 ms/op
                 createUser·p0.9999: 20.802 ms/op
                 createUser·p1.00:   23.986 ms/op

Iteration   2: 3.210 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.649 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   5.972 ms/op
                 createUser·p0.999:  19.180 ms/op
                 createUser·p0.9999: 23.495 ms/op
                 createUser·p1.00:   25.428 ms/op

Iteration   3: 3.227 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.029 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   6.128 ms/op
                 createUser·p0.999:  15.679 ms/op
                 createUser·p0.9999: 32.181 ms/op
                 createUser·p1.00:   35.455 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300369
  mean =      3.194 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22865 
    [ 2.500,  5.000) = 271401 
    [ 5.000,  7.500) = 4951 
    [ 7.500, 10.000) = 582 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.649 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     16.607 ms/op
     p(99.9900) =     27.327 ms/op
     p(99.9990) =     32.865 ms/op
     p(99.9999) =     35.455 ms/op
    p(100.0000) =     35.455 ms/op


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
# Warmup Iteration   1: 8.218 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.323 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.007 ms/op
Iteration   1: 3.182 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.051 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   5.442 ms/op
                 existUser·p0.999:  12.616 ms/op
                 existUser·p0.9999: 19.004 ms/op
                 existUser·p1.00:   19.268 ms/op

Iteration   2: 3.042 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.890 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.183 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  11.172 ms/op
                 existUser·p0.9999: 20.578 ms/op
                 existUser·p1.00:   20.972 ms/op

Iteration   3: 3.104 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.630 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   6.128 ms/op
                 existUser·p0.999:  13.042 ms/op
                 existUser·p0.9999: 20.601 ms/op
                 existUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308629
  mean =      3.109 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16978 
    [ 2.500,  5.000) = 285820 
    [ 5.000,  7.500) = 4916 
    [ 7.500, 10.000) = 419 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 165 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     12.616 ms/op
     p(99.9900) =     20.513 ms/op
     p(99.9990) =     21.470 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


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
# Warmup Iteration   1: 9.000 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.696 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.516 ±(99.9%) 0.013 ms/op
Iteration   1: 3.232 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.169 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   5.964 ms/op
                 getUser·p0.999:  16.750 ms/op
                 getUser·p0.9999: 20.870 ms/op
                 getUser·p1.00:   23.462 ms/op

Iteration   2: 3.121 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.305 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.383 ms/op
                 getUser·p0.95:   3.564 ms/op
                 getUser·p0.99:   5.267 ms/op
                 getUser·p0.999:  9.667 ms/op
                 getUser·p0.9999: 21.889 ms/op
                 getUser·p1.00:   22.479 ms/op

Iteration   3: 3.257 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.477 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   6.283 ms/op
                 getUser·p0.999:  12.513 ms/op
                 getUser·p0.9999: 24.123 ms/op
                 getUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299739
  mean =      3.202 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17276 
    [ 2.500,  5.000) = 276314 
    [ 5.000,  7.500) = 5116 
    [ 7.500, 10.000) = 629 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 155 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     16.105 ms/op
     p(99.9900) =     22.843 ms/op
     p(99.9990) =     24.871 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


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
# Warmup Iteration   1: 8.400 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 4.013 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.873 ±(99.9%) 0.013 ms/op
Iteration   1: 3.755 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.991 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  15.729 ms/op
                 listUser·p0.9999: 24.031 ms/op
                 listUser·p1.00:   24.773 ms/op

Iteration   2: 3.748 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.790 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.190 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  13.844 ms/op
                 listUser·p0.9999: 21.449 ms/op
                 listUser·p1.00:   21.758 ms/op

Iteration   3: 3.844 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.714 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  13.271 ms/op
                 listUser·p0.9999: 16.564 ms/op
                 listUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253762
  mean =      3.782 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 67 
    [ 2.500,  5.000) = 245635 
    [ 5.000,  7.500) = 6119 
    [ 7.500, 10.000) = 1253 
    [10.000, 12.500) = 307 
    [12.500, 15.000) = 160 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.714 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     14.356 ms/op
     p(99.9900) =     21.713 ms/op
     p(99.9990) =     24.556 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.925 ± 5.171  ops/ms
ClientPb.existUser                       thrpt       3  10.370 ± 1.949  ops/ms
ClientPb.getUser                         thrpt       3  10.009 ± 2.428  ops/ms
ClientPb.listUser                        thrpt       3   8.513 ± 1.912  ops/ms
ClientPb.createUser                       avgt       3   3.146 ± 1.002   ms/op
ClientPb.existUser                        avgt       3   3.158 ± 1.576   ms/op
ClientPb.getUser                          avgt       3   3.255 ± 1.343   ms/op
ClientPb.listUser                         avgt       3   3.773 ± 1.082   ms/op
ClientPb.createUser                     sample  300369   3.194 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.649           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.523           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.879           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.718           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.607           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.327           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.455           ms/op
ClientPb.existUser                      sample  308629   3.109 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.890           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.379           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.489           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.616           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.513           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.922           ms/op
ClientPb.getUser                        sample  299739   3.202 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.169           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.555           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.792           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.105           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.843           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.936           ms/op
ClientPb.listUser                       sample  253762   3.782 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.714           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.658           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.096           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.037           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.356           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.713           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.773           ms/op
