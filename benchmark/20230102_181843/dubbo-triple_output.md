# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.154 ops/ms
# Warmup Iteration   2: 5.562 ops/ms
# Warmup Iteration   3: 8.912 ops/ms
Iteration   1: 9.589 ops/ms
Iteration   2: 9.720 ops/ms
Iteration   3: 9.481 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.597 ±(99.9%) 2.183 ops/ms [Average]
  (min, avg, max) = (9.481, 9.597, 9.720), stdev = 0.120
  CI (99.9%): [7.413, 11.780] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.638 ops/ms
# Warmup Iteration   2: 9.322 ops/ms
# Warmup Iteration   3: 10.012 ops/ms
Iteration   1: 9.799 ops/ms
Iteration   2: 10.500 ops/ms
Iteration   3: 10.369 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.223 ±(99.9%) 6.802 ops/ms [Average]
  (min, avg, max) = (9.799, 10.223, 10.500), stdev = 0.373
  CI (99.9%): [3.421, 17.024] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.087 ops/ms
# Warmup Iteration   2: 8.934 ops/ms
# Warmup Iteration   3: 9.424 ops/ms
Iteration   1: 10.044 ops/ms
Iteration   2: 10.224 ops/ms
Iteration   3: 9.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.041 ±(99.9%) 3.375 ops/ms [Average]
  (min, avg, max) = (9.854, 10.041, 10.224), stdev = 0.185
  CI (99.9%): [6.665, 13.416] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.978 ops/ms
# Warmup Iteration   2: 7.126 ops/ms
# Warmup Iteration   3: 8.428 ops/ms
Iteration   1: 8.197 ops/ms
Iteration   2: 8.358 ops/ms
Iteration   3: 8.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.346 ±(99.9%) 2.613 ops/ms [Average]
  (min, avg, max) = (8.197, 8.346, 8.483), stdev = 0.143
  CI (99.9%): [5.733, 10.959] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.237 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.710 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.411 ±(99.9%) 0.005 ms/op
Iteration   1: 3.236 ±(99.9%) 0.007 ms/op
Iteration   2: 3.200 ±(99.9%) 0.004 ms/op
Iteration   3: 3.084 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.173 ±(99.9%) 1.451 ms/op [Average]
  (min, avg, max) = (3.084, 3.173, 3.236), stdev = 0.080
  CI (99.9%): [1.722, 4.624] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.545 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.476 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.004 ms/op
Iteration   1: 3.294 ±(99.9%) 0.006 ms/op
Iteration   2: 3.149 ±(99.9%) 0.004 ms/op
Iteration   3: 3.208 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.217 ±(99.9%) 1.333 ms/op [Average]
  (min, avg, max) = (3.149, 3.217, 3.294), stdev = 0.073
  CI (99.9%): [1.884, 4.550] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.781 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.504 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.326 ±(99.9%) 0.004 ms/op
Iteration   1: 3.200 ±(99.9%) 0.003 ms/op
Iteration   2: 3.075 ±(99.9%) 0.006 ms/op
Iteration   3: 3.075 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.117 ±(99.9%) 1.318 ms/op [Average]
  (min, avg, max) = (3.075, 3.117, 3.200), stdev = 0.072
  CI (99.9%): [1.799, 4.435] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.426 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.985 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.839 ±(99.9%) 0.003 ms/op
Iteration   1: 3.696 ±(99.9%) 0.012 ms/op
Iteration   2: 3.787 ±(99.9%) 0.012 ms/op
Iteration   3: 3.787 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.756 ±(99.9%) 0.956 ms/op [Average]
  (min, avg, max) = (3.696, 3.756, 3.787), stdev = 0.052
  CI (99.9%): [2.800, 4.713] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.304 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.747 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.236 ±(99.9%) 0.010 ms/op
Iteration   1: 3.139 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.565 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  16.941 ms/op
                 createUser·p0.9999: 18.704 ms/op
                 createUser·p1.00:   19.104 ms/op

Iteration   2: 3.205 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.214 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.391 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  9.945 ms/op
                 createUser·p0.9999: 21.040 ms/op
                 createUser·p1.00:   21.856 ms/op

Iteration   3: 3.181 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.532 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  13.992 ms/op
                 createUser·p0.9999: 18.315 ms/op
                 createUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302356
  mean =      3.175 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25542 
    [ 2.500,  5.000) = 272346 
    [ 5.000,  7.500) = 3771 
    [ 7.500, 10.000) = 259 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 153 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.214 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      5.333 ms/op
     p(99.9000) =     15.297 ms/op
     p(99.9900) =     18.957 ms/op
     p(99.9990) =     21.625 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.625 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.333 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.008 ms/op
Iteration   1: 3.246 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.516 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   6.027 ms/op
                 existUser·p0.999:  10.510 ms/op
                 existUser·p0.9999: 20.391 ms/op
                 existUser·p1.00:   21.037 ms/op

Iteration   2: 3.209 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.225 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.829 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  9.546 ms/op
                 existUser·p0.9999: 23.563 ms/op
                 existUser·p1.00:   23.921 ms/op

Iteration   3: 3.074 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.174 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.371 ms/op
                 existUser·p0.99:   5.030 ms/op
                 existUser·p0.999:  11.698 ms/op
                 existUser·p0.9999: 21.489 ms/op
                 existUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302094
  mean =      3.175 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24834 
    [ 2.500,  5.000) = 271213 
    [ 5.000,  7.500) = 5425 
    [ 7.500, 10.000) = 290 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.174 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     11.665 ms/op
     p(99.9900) =     22.079 ms/op
     p(99.9990) =     23.822 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.413 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.549 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.465 ±(99.9%) 0.011 ms/op
Iteration   1: 3.201 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.280 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   6.119 ms/op
                 getUser·p0.999:  16.433 ms/op
                 getUser·p0.9999: 21.201 ms/op
                 getUser·p1.00:   21.791 ms/op

Iteration   2: 3.257 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.810 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   5.784 ms/op
                 getUser·p0.999:  10.055 ms/op
                 getUser·p0.9999: 27.689 ms/op
                 getUser·p1.00:   28.475 ms/op

Iteration   3: 3.239 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.326 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   5.751 ms/op
                 getUser·p0.999:  14.930 ms/op
                 getUser·p0.9999: 22.741 ms/op
                 getUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296931
  mean =      3.232 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18566 
    [ 2.500,  5.000) = 272100 
    [ 5.000,  7.500) = 5112 
    [ 7.500, 10.000) = 683 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 181 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.326 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     15.925 ms/op
     p(99.9900) =     26.061 ms/op
     p(99.9990) =     28.313 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.307 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 4.303 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.800 ±(99.9%) 0.012 ms/op
Iteration   1: 3.885 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  16.182 ms/op
                 listUser·p0.9999: 21.284 ms/op
                 listUser·p1.00:   21.660 ms/op

Iteration   2: 3.920 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.504 ms/op
                 listUser·p0.999:  13.861 ms/op
                 listUser·p0.9999: 19.497 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   3: 3.744 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  13.779 ms/op
                 listUser·p0.9999: 20.024 ms/op
                 listUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249390
  mean =      3.848 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 240248 
    [ 5.000,  7.500) = 7059 
    [ 7.500, 10.000) = 1374 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 275 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.236 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     14.333 ms/op
     p(99.9900) =     20.449 ms/op
     p(99.9990) =     21.643 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.597 ± 2.183  ops/ms
ClientPb.existUser                       thrpt       3  10.223 ± 6.802  ops/ms
ClientPb.getUser                         thrpt       3  10.041 ± 3.375  ops/ms
ClientPb.listUser                        thrpt       3   8.346 ± 2.613  ops/ms
ClientPb.createUser                       avgt       3   3.173 ± 1.451   ms/op
ClientPb.existUser                        avgt       3   3.217 ± 1.333   ms/op
ClientPb.getUser                          avgt       3   3.117 ± 1.318   ms/op
ClientPb.listUser                         avgt       3   3.756 ± 0.956   ms/op
ClientPb.createUser                     sample  302356   3.175 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.214           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.482           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.333           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.297           ms/op
ClientPb.createUser:createUser·p0.9999  sample          18.957           ms/op
ClientPb.createUser:createUser·p1.00    sample          21.856           ms/op
ClientPb.existUser                      sample  302094   3.175 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.174           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.166           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.469           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.846           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.489           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.665           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.079           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.921           ms/op
ClientPb.getUser                        sample  296931   3.232 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.326           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.961           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.833           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.925           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.061           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.475           ms/op
ClientPb.listUser                       sample  249390   3.848 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.236           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.727           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.637           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.234           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.333           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.449           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.938           ms/op
