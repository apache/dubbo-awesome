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
# Warmup Iteration   1: 2.540 ops/ms
# Warmup Iteration   2: 6.494 ops/ms
# Warmup Iteration   3: 9.407 ops/ms
Iteration   1: 10.017 ops/ms
Iteration   2: 9.887 ops/ms
Iteration   3: 9.876 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.927 ±(99.9%) 1.432 ops/ms [Average]
  (min, avg, max) = (9.876, 9.927, 10.017), stdev = 0.078
  CI (99.9%): [8.495, 11.359] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.734 ops/ms
# Warmup Iteration   2: 9.435 ops/ms
# Warmup Iteration   3: 10.109 ops/ms
Iteration   1: 10.580 ops/ms
Iteration   2: 10.133 ops/ms
Iteration   3: 10.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.395 ±(99.9%) 4.251 ops/ms [Average]
  (min, avg, max) = (10.133, 10.395, 10.580), stdev = 0.233
  CI (99.9%): [6.144, 14.646] (assumes normal distribution)


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
# Warmup Iteration   1: 3.534 ops/ms
# Warmup Iteration   2: 9.132 ops/ms
# Warmup Iteration   3: 9.707 ops/ms
Iteration   1: 9.804 ops/ms
Iteration   2: 9.975 ops/ms
Iteration   3: 10.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.960 ±(99.9%) 2.724 ops/ms [Average]
  (min, avg, max) = (9.804, 9.960, 10.102), stdev = 0.149
  CI (99.9%): [7.236, 12.684] (assumes normal distribution)


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
# Warmup Iteration   1: 3.481 ops/ms
# Warmup Iteration   2: 7.862 ops/ms
# Warmup Iteration   3: 8.391 ops/ms
Iteration   1: 8.676 ops/ms
Iteration   2: 8.656 ops/ms
Iteration   3: 8.547 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.626 ±(99.9%) 1.276 ops/ms [Average]
  (min, avg, max) = (8.547, 8.626, 8.676), stdev = 0.070
  CI (99.9%): [7.350, 9.903] (assumes normal distribution)


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
# Warmup Iteration   1: 7.968 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.482 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.192 ±(99.9%) 0.005 ms/op
Iteration   1: 3.135 ±(99.9%) 0.006 ms/op
Iteration   2: 3.181 ±(99.9%) 0.009 ms/op
Iteration   3: 3.249 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.188 ±(99.9%) 1.052 ms/op [Average]
  (min, avg, max) = (3.135, 3.188, 3.249), stdev = 0.058
  CI (99.9%): [2.137, 4.240] (assumes normal distribution)


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
# Warmup Iteration   1: 7.033 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.285 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.002 ms/op
Iteration   1: 3.059 ±(99.9%) 0.004 ms/op
Iteration   2: 3.109 ±(99.9%) 0.007 ms/op
Iteration   3: 2.994 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.054 ±(99.9%) 1.058 ms/op [Average]
  (min, avg, max) = (2.994, 3.054, 3.109), stdev = 0.058
  CI (99.9%): [1.996, 4.112] (assumes normal distribution)


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
# Warmup Iteration   1: 7.018 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.374 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.004 ms/op
Iteration   1: 3.142 ±(99.9%) 0.004 ms/op
Iteration   2: 3.048 ±(99.9%) 0.004 ms/op
Iteration   3: 3.042 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.077 ±(99.9%) 1.030 ms/op [Average]
  (min, avg, max) = (3.042, 3.077, 3.142), stdev = 0.056
  CI (99.9%): [2.047, 4.107] (assumes normal distribution)


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
# Warmup Iteration   1: 9.453 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.141 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.810 ±(99.9%) 0.004 ms/op
Iteration   1: 3.819 ±(99.9%) 0.004 ms/op
Iteration   2: 3.717 ±(99.9%) 0.009 ms/op
Iteration   3: 3.747 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.761 ±(99.9%) 0.959 ms/op [Average]
  (min, avg, max) = (3.717, 3.761, 3.819), stdev = 0.053
  CI (99.9%): [2.802, 4.720] (assumes normal distribution)


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
# Warmup Iteration   1: 7.802 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 3.932 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.177 ±(99.9%) 0.009 ms/op
Iteration   1: 3.348 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.247 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  18.148 ms/op
                 createUser·p0.9999: 20.822 ms/op
                 createUser·p1.00:   21.398 ms/op

Iteration   2: 3.280 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.707 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  13.785 ms/op
                 createUser·p0.9999: 21.266 ms/op
                 createUser·p1.00:   22.118 ms/op

Iteration   3: 3.273 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.253 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   5.259 ms/op
                 createUser·p0.999:  15.542 ms/op
                 createUser·p0.9999: 20.462 ms/op
                 createUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 290836
  mean =      3.300 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24170 
    [ 2.500,  5.000) = 260142 
    [ 5.000,  7.500) = 5760 
    [ 7.500, 10.000) = 354 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 137 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.707 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     15.422 ms/op
     p(99.9900) =     21.037 ms/op
     p(99.9990) =     21.698 ms/op
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
# Warmup Iteration   1: 7.346 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.363 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.253 ±(99.9%) 0.008 ms/op
Iteration   1: 3.219 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.174 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  16.735 ms/op
                 existUser·p0.9999: 26.055 ms/op
                 existUser·p1.00:   27.001 ms/op

Iteration   2: 3.019 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.139 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.203 ms/op
                 existUser·p0.95:   3.424 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  9.422 ms/op
                 existUser·p0.9999: 22.348 ms/op
                 existUser·p1.00:   23.396 ms/op

Iteration   3: 3.173 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.051 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   4.157 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  8.977 ms/op
                 existUser·p0.9999: 24.309 ms/op
                 existUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305999
  mean =      3.134 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23119 
    [ 2.500,  5.000) = 277156 
    [ 5.000,  7.500) = 4920 
    [ 7.500, 10.000) = 440 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     13.386 ms/op
     p(99.9900) =     24.556 ms/op
     p(99.9990) =     26.852 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


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
# Warmup Iteration   1: 7.711 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.503 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.345 ±(99.9%) 0.011 ms/op
Iteration   1: 3.205 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.559 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   6.250 ms/op
                 getUser·p0.999:  12.259 ms/op
                 getUser·p0.9999: 25.593 ms/op
                 getUser·p1.00:   26.345 ms/op

Iteration   2: 3.263 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.219 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   5.554 ms/op
                 getUser·p0.999:  11.365 ms/op
                 getUser·p0.9999: 23.581 ms/op
                 getUser·p1.00:   24.543 ms/op

Iteration   3: 3.207 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.124 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  16.335 ms/op
                 getUser·p0.9999: 29.102 ms/op
                 getUser·p1.00:   29.852 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297262
  mean =      3.225 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17688 
    [ 2.500,  5.000) = 271796 
    [ 5.000,  7.500) = 6871 
    [ 7.500, 10.000) = 519 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     16.302 ms/op
     p(99.9900) =     27.144 ms/op
     p(99.9990) =     29.691 ms/op
     p(99.9999) =     29.852 ms/op
    p(100.0000) =     29.852 ms/op


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
# Warmup Iteration   1: 7.659 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 4.016 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.889 ±(99.9%) 0.012 ms/op
Iteration   1: 3.721 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.800 ms/op
                 listUser·p0.50:   3.555 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  14.828 ms/op
                 listUser·p0.9999: 20.094 ms/op
                 listUser·p1.00:   21.430 ms/op

Iteration   2: 3.786 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.133 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  13.575 ms/op
                 listUser·p0.9999: 20.939 ms/op
                 listUser·p1.00:   20.972 ms/op

Iteration   3: 3.716 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.126 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  13.287 ms/op
                 listUser·p0.9999: 20.034 ms/op
                 listUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256405
  mean =      3.741 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 248993 
    [ 5.000,  7.500) = 5751 
    [ 7.500, 10.000) = 1021 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 267 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.800 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     14.149 ms/op
     p(99.9900) =     20.110 ms/op
     p(99.9990) =     21.061 ms/op
     p(99.9999) =     21.430 ms/op
    p(100.0000) =     21.430 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.927 ± 1.432  ops/ms
ClientPb.existUser                       thrpt       3  10.395 ± 4.251  ops/ms
ClientPb.getUser                         thrpt       3   9.960 ± 2.724  ops/ms
ClientPb.listUser                        thrpt       3   8.626 ± 1.276  ops/ms
ClientPb.createUser                       avgt       3   3.188 ± 1.052   ms/op
ClientPb.existUser                        avgt       3   3.054 ± 1.058   ms/op
ClientPb.getUser                          avgt       3   3.077 ± 1.030   ms/op
ClientPb.listUser                         avgt       3   3.761 ± 0.959   ms/op
ClientPb.createUser                     sample  290836   3.300 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.707           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.240           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.740           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.002           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.448           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.422           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.037           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.118           ms/op
ClientPb.existUser                      sample  305999   3.134 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.051           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.531           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.867           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.505           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.386           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.556           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.001           ms/op
ClientPb.getUser                        sample  297262   3.225 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.124           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.604           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.018           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.808           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.302           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.144           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.852           ms/op
ClientPb.listUser                       sample  256405   3.741 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.800           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.662           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.076           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.750           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.149           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.110           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.430           ms/op
