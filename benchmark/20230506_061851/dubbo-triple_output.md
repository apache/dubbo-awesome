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
# Warmup Iteration   1: 2.450 ops/ms
# Warmup Iteration   2: 5.765 ops/ms
# Warmup Iteration   3: 9.446 ops/ms
Iteration   1: 9.801 ops/ms
Iteration   2: 10.007 ops/ms
Iteration   3: 9.722 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.843 ±(99.9%) 2.688 ops/ms [Average]
  (min, avg, max) = (9.722, 9.843, 10.007), stdev = 0.147
  CI (99.9%): [7.155, 12.531] (assumes normal distribution)


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
# Warmup Iteration   1: 4.011 ops/ms
# Warmup Iteration   2: 9.267 ops/ms
# Warmup Iteration   3: 9.920 ops/ms
Iteration   1: 10.657 ops/ms
Iteration   2: 10.540 ops/ms
Iteration   3: 10.327 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.508 ±(99.9%) 3.046 ops/ms [Average]
  (min, avg, max) = (10.327, 10.508, 10.657), stdev = 0.167
  CI (99.9%): [7.462, 13.554] (assumes normal distribution)


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
# Warmup Iteration   1: 3.731 ops/ms
# Warmup Iteration   2: 9.381 ops/ms
# Warmup Iteration   3: 10.326 ops/ms
Iteration   1: 9.720 ops/ms
Iteration   2: 9.981 ops/ms
Iteration   3: 10.343 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.015 ±(99.9%) 5.708 ops/ms [Average]
  (min, avg, max) = (9.720, 10.015, 10.343), stdev = 0.313
  CI (99.9%): [4.306, 15.723] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.506 ops/ms
# Warmup Iteration   2: 7.962 ops/ms
# Warmup Iteration   3: 8.607 ops/ms
Iteration   1: 8.633 ops/ms
Iteration   2: 8.524 ops/ms
Iteration   3: 8.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.644 ±(99.9%) 2.284 ops/ms [Average]
  (min, avg, max) = (8.524, 8.644, 8.774), stdev = 0.125
  CI (99.9%): [6.359, 10.928] (assumes normal distribution)


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
# Warmup Iteration   1: 8.163 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.472 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.282 ±(99.9%) 0.003 ms/op
Iteration   1: 3.190 ±(99.9%) 0.007 ms/op
Iteration   2: 3.214 ±(99.9%) 0.004 ms/op
Iteration   3: 3.093 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.165 ±(99.9%) 1.168 ms/op [Average]
  (min, avg, max) = (3.093, 3.165, 3.214), stdev = 0.064
  CI (99.9%): [1.997, 4.334] (assumes normal distribution)


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
# Warmup Iteration   1: 8.349 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.411 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.004 ms/op
Iteration   1: 2.995 ±(99.9%) 0.003 ms/op
Iteration   2: 3.156 ±(99.9%) 0.004 ms/op
Iteration   3: 3.113 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.088 ±(99.9%) 1.521 ms/op [Average]
  (min, avg, max) = (2.995, 3.088, 3.156), stdev = 0.083
  CI (99.9%): [1.567, 4.610] (assumes normal distribution)


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
# Warmup Iteration   1: 8.418 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.554 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.381 ±(99.9%) 0.002 ms/op
Iteration   1: 3.193 ±(99.9%) 0.006 ms/op
Iteration   2: 3.218 ±(99.9%) 0.007 ms/op
Iteration   3: 3.303 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.238 ±(99.9%) 1.052 ms/op [Average]
  (min, avg, max) = (3.193, 3.238, 3.303), stdev = 0.058
  CI (99.9%): [2.186, 4.290] (assumes normal distribution)


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
# Warmup Iteration   1: 9.203 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.036 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.863 ±(99.9%) 0.008 ms/op
Iteration   1: 3.772 ±(99.9%) 0.011 ms/op
Iteration   2: 3.800 ±(99.9%) 0.005 ms/op
Iteration   3: 3.698 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.757 ±(99.9%) 0.957 ms/op [Average]
  (min, avg, max) = (3.698, 3.757, 3.800), stdev = 0.052
  CI (99.9%): [2.799, 4.714] (assumes normal distribution)


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
# Warmup Iteration   1: 7.580 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.703 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.253 ±(99.9%) 0.009 ms/op
Iteration   1: 3.206 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.190 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  9.613 ms/op
                 createUser·p0.9999: 20.548 ms/op
                 createUser·p1.00:   20.873 ms/op

Iteration   2: 3.245 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.037 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  19.071 ms/op
                 createUser·p0.9999: 22.366 ms/op
                 createUser·p1.00:   22.708 ms/op

Iteration   3: 3.125 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.364 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.260 ms/op
                 createUser·p0.95:   3.387 ms/op
                 createUser·p0.99:   5.358 ms/op
                 createUser·p0.999:  15.034 ms/op
                 createUser·p0.9999: 19.038 ms/op
                 createUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300675
  mean =      3.191 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27619 
    [ 2.500,  5.000) = 267688 
    [ 5.000,  7.500) = 4448 
    [ 7.500, 10.000) = 434 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 140 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.037 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     15.641 ms/op
     p(99.9900) =     21.133 ms/op
     p(99.9990) =     22.642 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


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
# Warmup Iteration   1: 7.521 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.464 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.171 ±(99.9%) 0.009 ms/op
Iteration   1: 3.115 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.985 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   5.923 ms/op
                 existUser·p0.999:  12.064 ms/op
                 existUser·p0.9999: 19.628 ms/op
                 existUser·p1.00:   20.414 ms/op

Iteration   2: 3.064 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.896 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  12.780 ms/op
                 existUser·p0.9999: 21.266 ms/op
                 existUser·p1.00:   22.184 ms/op

Iteration   3: 3.080 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.542 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.964 ms/op
                 existUser·p0.999:  14.912 ms/op
                 existUser·p0.9999: 18.784 ms/op
                 existUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310815
  mean =      3.086 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15126 
    [ 2.500,  5.000) = 290158 
    [ 5.000,  7.500) = 4548 
    [ 7.500, 10.000) = 465 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 175 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.301 ms/op
     p(95.0000) =      3.559 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     13.375 ms/op
     p(99.9900) =     20.477 ms/op
     p(99.9990) =     21.918 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


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
# Warmup Iteration   1: 7.400 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.554 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.220 ±(99.9%) 0.009 ms/op
Iteration   1: 3.227 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.182 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.474 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   6.373 ms/op
                 getUser·p0.999:  18.842 ms/op
                 getUser·p0.9999: 20.909 ms/op
                 getUser·p1.00:   22.020 ms/op

Iteration   2: 3.186 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.198 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.633 ms/op
                 getUser·p0.99:   5.521 ms/op
                 getUser·p0.999:  20.585 ms/op
                 getUser·p0.9999: 22.738 ms/op
                 getUser·p1.00:   23.986 ms/op

Iteration   3: 3.193 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.802 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  9.732 ms/op
                 getUser·p0.9999: 18.907 ms/op
                 getUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299467
  mean =      3.202 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7999 
    [ 2.500,  5.000) = 284432 
    [ 5.000,  7.500) = 5782 
    [ 7.500, 10.000) = 731 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 147 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.182 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     16.049 ms/op
     p(99.9900) =     22.217 ms/op
     p(99.9990) =     23.201 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


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
# Warmup Iteration   1: 9.387 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.039 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.791 ±(99.9%) 0.012 ms/op
Iteration   1: 3.693 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.319 ms/op
                 listUser·p0.50:   3.584 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.121 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  14.178 ms/op
                 listUser·p0.9999: 20.917 ms/op
                 listUser·p1.00:   21.398 ms/op

Iteration   2: 3.784 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.347 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   7.717 ms/op
                 listUser·p0.999:  13.100 ms/op
                 listUser·p0.9999: 16.876 ms/op
                 listUser·p1.00:   17.269 ms/op

Iteration   3: 3.741 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.056 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   4.186 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  12.419 ms/op
                 listUser·p0.9999: 16.400 ms/op
                 listUser·p1.00:   16.466 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256554
  mean =      3.739 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 249994 
    [ 5.000,  7.500) = 4504 
    [ 7.500, 10.000) = 1259 
    [10.000, 12.500) = 405 
    [12.500, 15.000) = 189 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.319 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     13.440 ms/op
     p(99.9900) =     19.105 ms/op
     p(99.9990) =     21.244 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.843 ± 2.688  ops/ms
ClientPb.existUser                       thrpt       3  10.508 ± 3.046  ops/ms
ClientPb.getUser                         thrpt       3  10.015 ± 5.708  ops/ms
ClientPb.listUser                        thrpt       3   8.644 ± 2.284  ops/ms
ClientPb.createUser                       avgt       3   3.165 ± 1.168   ms/op
ClientPb.existUser                        avgt       3   3.088 ± 1.521   ms/op
ClientPb.getUser                          avgt       3   3.238 ± 1.052   ms/op
ClientPb.listUser                         avgt       3   3.757 ± 0.957   ms/op
ClientPb.createUser                     sample  300675   3.191 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.037           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.387           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.740           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.489           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.641           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.133           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.708           ms/op
ClientPb.existUser                      sample  310815   3.086 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.896           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.301           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.559           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.669           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.375           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.477           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.184           ms/op
ClientPb.getUser                        sample  299467   3.202 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.182           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.469           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.740           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.964           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.049           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.217           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.986           ms/op
ClientPb.listUser                       sample  256554   3.739 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.319           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.609           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.063           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.037           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.440           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.105           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.398           ms/op
