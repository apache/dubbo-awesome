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
# Warmup Iteration   1: 2.116 ops/ms
# Warmup Iteration   2: 5.495 ops/ms
# Warmup Iteration   3: 8.468 ops/ms
Iteration   1: 9.390 ops/ms
Iteration   2: 9.427 ops/ms
Iteration   3: 9.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.536 ±(99.9%) 4.052 ops/ms [Average]
  (min, avg, max) = (9.390, 9.536, 9.792), stdev = 0.222
  CI (99.9%): [5.485, 13.588] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.903 ops/ms
# Warmup Iteration   2: 8.067 ops/ms
# Warmup Iteration   3: 9.075 ops/ms
Iteration   1: 9.870 ops/ms
Iteration   2: 10.122 ops/ms
Iteration   3: 9.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.943 ±(99.9%) 2.838 ops/ms [Average]
  (min, avg, max) = (9.838, 9.943, 10.122), stdev = 0.156
  CI (99.9%): [7.105, 12.781] (assumes normal distribution)


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
# Warmup Iteration   1: 3.143 ops/ms
# Warmup Iteration   2: 8.521 ops/ms
# Warmup Iteration   3: 9.194 ops/ms
Iteration   1: 9.593 ops/ms
Iteration   2: 9.221 ops/ms
Iteration   3: 9.208 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.340 ±(99.9%) 3.991 ops/ms [Average]
  (min, avg, max) = (9.208, 9.340, 9.593), stdev = 0.219
  CI (99.9%): [5.349, 13.332] (assumes normal distribution)


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
# Warmup Iteration   1: 3.069 ops/ms
# Warmup Iteration   2: 7.385 ops/ms
# Warmup Iteration   3: 8.177 ops/ms
Iteration   1: 8.304 ops/ms
Iteration   2: 8.189 ops/ms
Iteration   3: 8.446 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.313 ±(99.9%) 2.348 ops/ms [Average]
  (min, avg, max) = (8.189, 8.313, 8.446), stdev = 0.129
  CI (99.9%): [5.965, 10.660] (assumes normal distribution)


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
# Warmup Iteration   1: 10.224 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 3.697 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.576 ±(99.9%) 0.007 ms/op
Iteration   1: 3.398 ±(99.9%) 0.005 ms/op
Iteration   2: 3.356 ±(99.9%) 0.006 ms/op
Iteration   3: 3.429 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.394 ±(99.9%) 0.662 ms/op [Average]
  (min, avg, max) = (3.356, 3.394, 3.429), stdev = 0.036
  CI (99.9%): [2.733, 4.056] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.843 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.451 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.327 ±(99.9%) 0.009 ms/op
Iteration   1: 3.200 ±(99.9%) 0.004 ms/op
Iteration   2: 3.203 ±(99.9%) 0.002 ms/op
Iteration   3: 3.180 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.194 ±(99.9%) 0.227 ms/op [Average]
  (min, avg, max) = (3.180, 3.194, 3.203), stdev = 0.012
  CI (99.9%): [2.967, 3.422] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.326 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.708 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.478 ±(99.9%) 0.005 ms/op
Iteration   1: 3.474 ±(99.9%) 0.009 ms/op
Iteration   2: 3.353 ±(99.9%) 0.005 ms/op
Iteration   3: 3.507 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.445 ±(99.9%) 1.471 ms/op [Average]
  (min, avg, max) = (3.353, 3.445, 3.507), stdev = 0.081
  CI (99.9%): [1.973, 4.916] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.588 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.191 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.957 ±(99.9%) 0.008 ms/op
Iteration   1: 3.885 ±(99.9%) 0.014 ms/op
Iteration   2: 3.896 ±(99.9%) 0.013 ms/op
Iteration   3: 3.873 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.885 ±(99.9%) 0.210 ms/op [Average]
  (min, avg, max) = (3.873, 3.885, 3.896), stdev = 0.012
  CI (99.9%): [3.674, 4.095] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.435 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.914 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.321 ±(99.9%) 0.009 ms/op
Iteration   1: 3.366 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.223 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   4.149 ms/op
                 createUser·p0.99:   6.300 ms/op
                 createUser·p0.999:  17.882 ms/op
                 createUser·p0.9999: 21.070 ms/op
                 createUser·p1.00:   21.627 ms/op

Iteration   2: 3.357 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.276 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  18.588 ms/op
                 createUser·p0.9999: 23.379 ms/op
                 createUser·p1.00:   25.657 ms/op

Iteration   3: 3.408 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.274 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.153 ms/op
                 createUser·p0.99:   5.923 ms/op
                 createUser·p0.999:  19.825 ms/op
                 createUser·p0.9999: 32.579 ms/op
                 createUser·p1.00:   37.880 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 284215
  mean =      3.377 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16866 
    [ 2.500,  5.000) = 260497 
    [ 5.000,  7.500) = 5599 
    [ 7.500, 10.000) = 608 
    [10.000, 12.500) = 240 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     18.654 ms/op
     p(99.9900) =     31.149 ms/op
     p(99.9990) =     37.549 ms/op
     p(99.9999) =     37.880 ms/op
    p(100.0000) =     37.880 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 10.165 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 3.904 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.268 ±(99.9%) 0.009 ms/op
Iteration   1: 3.292 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.411 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.936 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  10.091 ms/op
                 existUser·p0.9999: 22.348 ms/op
                 existUser·p1.00:   22.938 ms/op

Iteration   2: 3.243 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.953 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  12.532 ms/op
                 existUser·p0.9999: 23.495 ms/op
                 existUser·p1.00:   24.281 ms/op

Iteration   3: 3.362 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.698 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   4.026 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   5.980 ms/op
                 existUser·p0.999:  16.295 ms/op
                 existUser·p0.9999: 24.229 ms/op
                 existUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290916
  mean =      3.298 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18709 
    [ 2.500,  5.000) = 265567 
    [ 5.000,  7.500) = 5491 
    [ 7.500, 10.000) = 639 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 167 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     15.894 ms/op
     p(99.9900) =     23.462 ms/op
     p(99.9990) =     24.546 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


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
# Warmup Iteration   1: 10.769 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 3.809 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.551 ±(99.9%) 0.010 ms/op
Iteration   1: 3.360 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.769 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   4.258 ms/op
                 getUser·p0.99:   6.512 ms/op
                 getUser·p0.999:  18.638 ms/op
                 getUser·p0.9999: 21.938 ms/op
                 getUser·p1.00:   22.512 ms/op

Iteration   2: 3.424 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.565 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   4.035 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   5.718 ms/op
                 getUser·p0.999:  8.897 ms/op
                 getUser·p0.9999: 21.234 ms/op
                 getUser·p1.00:   22.118 ms/op

Iteration   3: 3.386 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.171 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   6.119 ms/op
                 getUser·p0.999:  19.189 ms/op
                 getUser·p0.9999: 35.777 ms/op
                 getUser·p1.00:   36.766 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 283005
  mean =      3.390 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10455 
    [ 2.500,  5.000) = 264935 
    [ 5.000,  7.500) = 6679 
    [ 7.500, 10.000) = 515 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 144 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      6.218 ms/op
     p(99.9000) =     18.117 ms/op
     p(99.9900) =     33.440 ms/op
     p(99.9990) =     36.646 ms/op
     p(99.9999) =     36.766 ms/op
    p(100.0000) =     36.766 ms/op


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
# Warmup Iteration   1: 12.524 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.293 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.035 ±(99.9%) 0.013 ms/op
Iteration   1: 3.878 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.157 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   6.868 ms/op
                 listUser·p0.999:  20.006 ms/op
                 listUser·p0.9999: 25.461 ms/op
                 listUser·p1.00:   26.640 ms/op

Iteration   2: 3.953 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.093 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  15.172 ms/op
                 listUser·p0.9999: 17.695 ms/op
                 listUser·p1.00:   19.104 ms/op

Iteration   3: 3.840 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.150 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  16.510 ms/op
                 listUser·p0.9999: 20.043 ms/op
                 listUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 246654
  mean =      3.889 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 239181 
    [ 5.000,  7.500) = 5693 
    [ 7.500, 10.000) = 1011 
    [10.000, 12.500) = 218 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 176 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     16.499 ms/op
     p(99.9900) =     23.932 ms/op
     p(99.9990) =     26.121 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.536 ± 4.052  ops/ms
ClientPb.existUser                       thrpt       3   9.943 ± 2.838  ops/ms
ClientPb.getUser                         thrpt       3   9.340 ± 3.991  ops/ms
ClientPb.listUser                        thrpt       3   8.313 ± 2.348  ops/ms
ClientPb.createUser                       avgt       3   3.394 ± 0.662   ms/op
ClientPb.existUser                        avgt       3   3.194 ± 0.227   ms/op
ClientPb.getUser                          avgt       3   3.445 ± 1.471   ms/op
ClientPb.listUser                         avgt       3   3.885 ± 0.210   ms/op
ClientPb.createUser                     sample  284215   3.377 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.223           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.285           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.785           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.137           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.890           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.654           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.149           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.880           ms/op
ClientPb.existUser                      sample  290916   3.298 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.071           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.157           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.685           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.894           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.462           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.642           ms/op
ClientPb.getUser                        sample  283005   3.390 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.171           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.269           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.850           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.218           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.117           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.440           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.766           ms/op
ClientPb.listUser                       sample  246654   3.889 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.157           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.748           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.260           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.988           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.499           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.932           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.640           ms/op
