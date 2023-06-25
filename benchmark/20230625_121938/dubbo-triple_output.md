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
# Warmup Iteration   1: 1.106 ops/ms
# Warmup Iteration   2: 2.441 ops/ms
# Warmup Iteration   3: 5.198 ops/ms
Iteration   1: 5.834 ops/ms
Iteration   2: 5.749 ops/ms
Iteration   3: 5.873 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.819 ±(99.9%) 1.157 ops/ms [Average]
  (min, avg, max) = (5.749, 5.819, 5.873), stdev = 0.063
  CI (99.9%): [4.661, 6.976] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.782 ops/ms
# Warmup Iteration   2: 5.146 ops/ms
# Warmup Iteration   3: 6.302 ops/ms
Iteration   1: 6.431 ops/ms
Iteration   2: 6.397 ops/ms
Iteration   3: 6.189 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.339 ±(99.9%) 2.396 ops/ms [Average]
  (min, avg, max) = (6.189, 6.339, 6.431), stdev = 0.131
  CI (99.9%): [3.943, 8.735] (assumes normal distribution)


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
# Warmup Iteration   1: 1.654 ops/ms
# Warmup Iteration   2: 4.929 ops/ms
# Warmup Iteration   3: 5.923 ops/ms
Iteration   1: 5.604 ops/ms
Iteration   2: 5.788 ops/ms
Iteration   3: 5.802 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.731 ±(99.9%) 2.017 ops/ms [Average]
  (min, avg, max) = (5.604, 5.731, 5.802), stdev = 0.111
  CI (99.9%): [3.714, 7.749] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.804 ops/ms
# Warmup Iteration   2: 4.320 ops/ms
# Warmup Iteration   3: 4.885 ops/ms
Iteration   1: 4.993 ops/ms
Iteration   2: 5.065 ops/ms
Iteration   3: 5.078 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.046 ±(99.9%) 0.839 ops/ms [Average]
  (min, avg, max) = (4.993, 5.046, 5.078), stdev = 0.046
  CI (99.9%): [4.206, 5.885] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 17.421 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 6.373 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.710 ±(99.9%) 0.011 ms/op
Iteration   1: 5.545 ±(99.9%) 0.012 ms/op
Iteration   2: 5.184 ±(99.9%) 0.024 ms/op
Iteration   3: 5.271 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.333 ±(99.9%) 3.433 ms/op [Average]
  (min, avg, max) = (5.184, 5.333, 5.545), stdev = 0.188
  CI (99.9%): [1.901, 8.766] (assumes normal distribution)


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
# Warmup Iteration   1: 17.374 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.964 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.171 ±(99.9%) 0.010 ms/op
Iteration   1: 5.032 ±(99.9%) 0.011 ms/op
Iteration   2: 4.894 ±(99.9%) 0.014 ms/op
Iteration   3: 4.977 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.968 ±(99.9%) 1.275 ms/op [Average]
  (min, avg, max) = (4.894, 4.968, 5.032), stdev = 0.070
  CI (99.9%): [3.692, 6.243] (assumes normal distribution)


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
# Warmup Iteration   1: 17.130 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 6.469 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.636 ±(99.9%) 0.014 ms/op
Iteration   1: 5.504 ±(99.9%) 0.009 ms/op
Iteration   2: 5.262 ±(99.9%) 0.012 ms/op
Iteration   3: 5.425 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.397 ±(99.9%) 2.245 ms/op [Average]
  (min, avg, max) = (5.262, 5.397, 5.504), stdev = 0.123
  CI (99.9%): [3.152, 7.642] (assumes normal distribution)


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
# Warmup Iteration   1: 17.758 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 7.353 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.520 ±(99.9%) 0.015 ms/op
Iteration   1: 6.288 ±(99.9%) 0.015 ms/op
Iteration   2: 6.360 ±(99.9%) 0.016 ms/op
Iteration   3: 6.445 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.364 ±(99.9%) 1.435 ms/op [Average]
  (min, avg, max) = (6.288, 6.364, 6.445), stdev = 0.079
  CI (99.9%): [4.929, 7.799] (assumes normal distribution)


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
# Warmup Iteration   1: 16.492 ±(99.9%) 0.252 ms/op
# Warmup Iteration   2: 6.046 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.581 ±(99.9%) 0.024 ms/op
Iteration   1: 5.033 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.122 ms/op
                 createUser·p0.50:   4.907 ms/op
                 createUser·p0.90:   5.964 ms/op
                 createUser·p0.95:   6.668 ms/op
                 createUser·p0.99:   8.634 ms/op
                 createUser·p0.999:  22.204 ms/op
                 createUser·p0.9999: 28.485 ms/op
                 createUser·p1.00:   29.426 ms/op

Iteration   2: 5.099 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.985 ms/op
                 createUser·p0.50:   4.915 ms/op
                 createUser·p0.90:   6.087 ms/op
                 createUser·p0.95:   6.603 ms/op
                 createUser·p0.99:   8.946 ms/op
                 createUser·p0.999:  24.576 ms/op
                 createUser·p0.9999: 32.923 ms/op
                 createUser·p1.00:   33.620 ms/op

Iteration   3: 5.351 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.870 ms/op
                 createUser·p0.50:   5.161 ms/op
                 createUser·p0.90:   6.439 ms/op
                 createUser·p0.95:   7.152 ms/op
                 createUser·p0.99:   9.519 ms/op
                 createUser·p0.999:  27.271 ms/op
                 createUser·p0.9999: 31.005 ms/op
                 createUser·p1.00:   31.719 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 185989
  mean =      5.158 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 96203 
    [ 5.000,  7.500) = 84185 
    [ 7.500, 10.000) = 4429 
    [10.000, 12.500) = 653 
    [12.500, 15.000) = 217 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.870 ms/op
     p(50.0000) =      4.973 ms/op
     p(90.0000) =      6.185 ms/op
     p(95.0000) =      6.799 ms/op
     p(99.0000) =      8.929 ms/op
     p(99.9000) =     22.872 ms/op
     p(99.9900) =     32.264 ms/op
     p(99.9990) =     33.564 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


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
# Warmup Iteration   1: 16.551 ±(99.9%) 0.269 ms/op
# Warmup Iteration   2: 6.209 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.727 ±(99.9%) 0.024 ms/op
Iteration   1: 5.152 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.179 ms/op
                 existUser·p0.50:   4.940 ms/op
                 existUser·p0.90:   6.119 ms/op
                 existUser·p0.95:   6.881 ms/op
                 existUser·p0.99:   9.601 ms/op
                 existUser·p0.999:  25.470 ms/op
                 existUser·p0.9999: 27.636 ms/op
                 existUser·p1.00:   29.426 ms/op

Iteration   2: 5.063 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.478 ms/op
                 existUser·p0.50:   4.841 ms/op
                 existUser·p0.90:   5.997 ms/op
                 existUser·p0.95:   6.709 ms/op
                 existUser·p0.99:   9.896 ms/op
                 existUser·p0.999:  25.365 ms/op
                 existUser·p0.9999: 31.883 ms/op
                 existUser·p1.00:   33.292 ms/op

Iteration   3: 5.079 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.421 ms/op
                 existUser·p0.50:   4.907 ms/op
                 existUser·p0.90:   5.939 ms/op
                 existUser·p0.95:   6.464 ms/op
                 existUser·p0.99:   9.126 ms/op
                 existUser·p0.999:  28.248 ms/op
                 existUser·p0.9999: 31.425 ms/op
                 existUser·p1.00:   32.571 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 188145
  mean =      5.098 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 108022 
    [ 5.000,  7.500) = 74556 
    [ 7.500, 10.000) = 4105 
    [10.000, 12.500) = 839 
    [12.500, 15.000) = 227 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.179 ms/op
     p(50.0000) =      4.899 ms/op
     p(90.0000) =      6.021 ms/op
     p(95.0000) =      6.668 ms/op
     p(99.0000) =      9.552 ms/op
     p(99.9000) =     25.484 ms/op
     p(99.9900) =     31.725 ms/op
     p(99.9990) =     33.177 ms/op
     p(99.9999) =     33.292 ms/op
    p(100.0000) =     33.292 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.475 ±(99.9%) 0.252 ms/op
# Warmup Iteration   2: 6.532 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.648 ±(99.9%) 0.023 ms/op
Iteration   1: 5.333 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.220 ms/op
                 getUser·p0.50:   5.120 ms/op
                 getUser·p0.90:   6.398 ms/op
                 getUser·p0.95:   7.127 ms/op
                 getUser·p0.99:   9.667 ms/op
                 getUser·p0.999:  21.331 ms/op
                 getUser·p0.9999: 28.705 ms/op
                 getUser·p1.00:   29.327 ms/op

Iteration   2: 5.398 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.441 ms/op
                 getUser·p0.50:   5.145 ms/op
                 getUser·p0.90:   6.562 ms/op
                 getUser·p0.95:   7.995 ms/op
                 getUser·p0.99:   10.453 ms/op
                 getUser·p0.999:  26.166 ms/op
                 getUser·p0.9999: 31.752 ms/op
                 getUser·p1.00:   32.997 ms/op

Iteration   3: 5.174 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.429 ms/op
                 getUser·p0.50:   4.981 ms/op
                 getUser·p0.90:   6.160 ms/op
                 getUser·p0.95:   6.926 ms/op
                 getUser·p0.99:   9.832 ms/op
                 getUser·p0.999:  25.704 ms/op
                 getUser·p0.9999: 30.162 ms/op
                 getUser·p1.00:   30.802 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 181026
  mean =      5.300 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 82070 
    [ 5.000,  7.500) = 90547 
    [ 7.500, 10.000) = 6520 
    [10.000, 12.500) = 1202 
    [12.500, 15.000) = 352 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.220 ms/op
     p(50.0000) =      5.079 ms/op
     p(90.0000) =      6.357 ms/op
     p(95.0000) =      7.340 ms/op
     p(99.0000) =     10.109 ms/op
     p(99.9000) =     23.985 ms/op
     p(99.9900) =     30.399 ms/op
     p(99.9990) =     32.546 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


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
# Warmup Iteration   1: 18.344 ±(99.9%) 0.290 ms/op
# Warmup Iteration   2: 7.082 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 6.426 ±(99.9%) 0.026 ms/op
Iteration   1: 6.251 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.499 ms/op
                 listUser·p0.50:   5.931 ms/op
                 listUser·p0.90:   7.561 ms/op
                 listUser·p0.95:   8.454 ms/op
                 listUser·p0.99:   11.190 ms/op
                 listUser·p0.999:  28.344 ms/op
                 listUser·p0.9999: 32.610 ms/op
                 listUser·p1.00:   33.260 ms/op

Iteration   2: 6.297 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.150 ms/op
                 listUser·p0.50:   5.947 ms/op
                 listUser·p0.90:   7.594 ms/op
                 listUser·p0.95:   8.487 ms/op
                 listUser·p0.99:   11.780 ms/op
                 listUser·p0.999:  31.925 ms/op
                 listUser·p0.9999: 38.333 ms/op
                 listUser·p1.00:   39.125 ms/op

Iteration   3: 6.403 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   3.019 ms/op
                 listUser·p0.50:   6.185 ms/op
                 listUser·p0.90:   7.299 ms/op
                 listUser·p0.95:   8.151 ms/op
                 listUser·p0.99:   11.059 ms/op
                 listUser·p0.999:  23.331 ms/op
                 listUser·p0.9999: 29.623 ms/op
                 listUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 151937
  mean =      6.317 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 8041 
    [ 5.000,  7.500) = 128808 
    [ 7.500, 10.000) = 12044 
    [10.000, 12.500) = 2027 
    [12.500, 15.000) = 518 
    [15.000, 17.500) = 163 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 78 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.499 ms/op
     p(50.0000) =      6.029 ms/op
     p(90.0000) =      7.496 ms/op
     p(95.0000) =      8.389 ms/op
     p(99.0000) =     11.370 ms/op
     p(99.9000) =     27.789 ms/op
     p(99.9900) =     36.556 ms/op
     p(99.9990) =     39.057 ms/op
     p(99.9999) =     39.125 ms/op
    p(100.0000) =     39.125 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.819 ± 1.157  ops/ms
ClientPb.existUser                       thrpt       3   6.339 ± 2.396  ops/ms
ClientPb.getUser                         thrpt       3   5.731 ± 2.017  ops/ms
ClientPb.listUser                        thrpt       3   5.046 ± 0.839  ops/ms
ClientPb.createUser                       avgt       3   5.333 ± 3.433   ms/op
ClientPb.existUser                        avgt       3   4.968 ± 1.275   ms/op
ClientPb.getUser                          avgt       3   5.397 ± 2.245   ms/op
ClientPb.listUser                         avgt       3   6.364 ± 1.435   ms/op
ClientPb.createUser                     sample  185989   5.158 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.870           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.973           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.185           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.799           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.929           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.872           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.264           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.620           ms/op
ClientPb.existUser                      sample  188145   5.098 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.179           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.899           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.021           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.668           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.552           ms/op
ClientPb.existUser:existUser·p0.999     sample          25.484           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.725           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.292           ms/op
ClientPb.getUser                        sample  181026   5.300 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.220           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.079           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.357           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.340           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.109           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.985           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.399           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.997           ms/op
ClientPb.listUser                       sample  151937   6.317 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.499           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.029           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.496           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.389           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.370           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.789           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.556           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.125           ms/op
