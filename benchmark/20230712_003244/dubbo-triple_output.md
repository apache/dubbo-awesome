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
# Warmup Iteration   1: 2.023 ops/ms
# Warmup Iteration   2: 5.033 ops/ms
# Warmup Iteration   3: 8.715 ops/ms
Iteration   1: 9.204 ops/ms
Iteration   2: 9.130 ops/ms
Iteration   3: 9.218 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.184 ±(99.9%) 0.867 ops/ms [Average]
  (min, avg, max) = (9.130, 9.184, 9.218), stdev = 0.048
  CI (99.9%): [8.317, 10.051] (assumes normal distribution)


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
# Warmup Iteration   1: 2.696 ops/ms
# Warmup Iteration   2: 8.249 ops/ms
# Warmup Iteration   3: 9.304 ops/ms
Iteration   1: 9.706 ops/ms
Iteration   2: 9.738 ops/ms
Iteration   3: 9.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.599 ±(99.9%) 3.880 ops/ms [Average]
  (min, avg, max) = (9.354, 9.599, 9.738), stdev = 0.213
  CI (99.9%): [5.719, 13.479] (assumes normal distribution)


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
# Warmup Iteration   1: 2.860 ops/ms
# Warmup Iteration   2: 7.728 ops/ms
# Warmup Iteration   3: 8.994 ops/ms
Iteration   1: 9.068 ops/ms
Iteration   2: 9.042 ops/ms
Iteration   3: 8.938 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.016 ±(99.9%) 1.255 ops/ms [Average]
  (min, avg, max) = (8.938, 9.016, 9.068), stdev = 0.069
  CI (99.9%): [7.761, 10.271] (assumes normal distribution)


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
# Warmup Iteration   1: 2.613 ops/ms
# Warmup Iteration   2: 6.843 ops/ms
# Warmup Iteration   3: 7.410 ops/ms
Iteration   1: 7.825 ops/ms
Iteration   2: 7.935 ops/ms
Iteration   3: 7.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.872 ±(99.9%) 1.032 ops/ms [Average]
  (min, avg, max) = (7.825, 7.872, 7.935), stdev = 0.057
  CI (99.9%): [6.839, 8.904] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 12.773 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.250 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.648 ±(99.9%) 0.005 ms/op
Iteration   1: 3.473 ±(99.9%) 0.008 ms/op
Iteration   2: 3.531 ±(99.9%) 0.007 ms/op
Iteration   3: 3.448 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.484 ±(99.9%) 0.776 ms/op [Average]
  (min, avg, max) = (3.448, 3.484, 3.531), stdev = 0.043
  CI (99.9%): [2.708, 4.259] (assumes normal distribution)


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
# Warmup Iteration   1: 8.064 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.817 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.432 ±(99.9%) 0.006 ms/op
Iteration   1: 3.239 ±(99.9%) 0.009 ms/op
Iteration   2: 3.371 ±(99.9%) 0.007 ms/op
Iteration   3: 3.325 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.311 ±(99.9%) 1.218 ms/op [Average]
  (min, avg, max) = (3.239, 3.311, 3.371), stdev = 0.067
  CI (99.9%): [2.094, 4.529] (assumes normal distribution)


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
# Warmup Iteration   1: 11.852 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.002 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.619 ±(99.9%) 0.007 ms/op
Iteration   1: 3.608 ±(99.9%) 0.004 ms/op
Iteration   2: 3.572 ±(99.9%) 0.006 ms/op
Iteration   3: 3.381 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.520 ±(99.9%) 2.223 ms/op [Average]
  (min, avg, max) = (3.381, 3.520, 3.608), stdev = 0.122
  CI (99.9%): [1.297, 5.744] (assumes normal distribution)


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
# Warmup Iteration   1: 9.954 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.937 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.141 ±(99.9%) 0.010 ms/op
Iteration   1: 4.067 ±(99.9%) 0.008 ms/op
Iteration   2: 4.170 ±(99.9%) 0.005 ms/op
Iteration   3: 3.996 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.077 ±(99.9%) 1.598 ms/op [Average]
  (min, avg, max) = (3.996, 4.077, 4.170), stdev = 0.088
  CI (99.9%): [2.479, 5.675] (assumes normal distribution)


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
# Warmup Iteration   1: 10.236 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.459 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.477 ±(99.9%) 0.009 ms/op
Iteration   1: 3.680 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.726 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   6.095 ms/op
                 createUser·p0.99:   7.610 ms/op
                 createUser·p0.999:  22.053 ms/op
                 createUser·p0.9999: 27.065 ms/op
                 createUser·p1.00:   28.639 ms/op

Iteration   2: 3.482 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.016 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   6.263 ms/op
                 createUser·p0.999:  22.741 ms/op
                 createUser·p0.9999: 28.660 ms/op
                 createUser·p1.00:   29.065 ms/op

Iteration   3: 3.529 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.090 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.170 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   6.398 ms/op
                 createUser·p0.999:  28.484 ms/op
                 createUser·p0.9999: 31.553 ms/op
                 createUser·p1.00:   31.850 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 269338
  mean =      3.562 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7793 
    [ 2.500,  5.000) = 250203 
    [ 5.000,  7.500) = 9493 
    [ 7.500, 10.000) = 1254 
    [10.000, 12.500) = 239 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 79 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.016 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      7.283 ms/op
     p(99.9000) =     22.719 ms/op
     p(99.9900) =     30.671 ms/op
     p(99.9990) =     31.818 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


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
# Warmup Iteration   1: 10.112 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 3.864 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.560 ±(99.9%) 0.011 ms/op
Iteration   1: 3.347 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.548 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   6.300 ms/op
                 existUser·p0.999:  21.281 ms/op
                 existUser·p0.9999: 25.377 ms/op
                 existUser·p1.00:   26.968 ms/op

Iteration   2: 3.406 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.421 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.317 ms/op
                 existUser·p0.99:   6.750 ms/op
                 existUser·p0.999:  23.593 ms/op
                 existUser·p0.9999: 39.230 ms/op
                 existUser·p1.00:   39.584 ms/op

Iteration   3: 3.287 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.632 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.826 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  9.334 ms/op
                 existUser·p0.9999: 29.899 ms/op
                 existUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286842
  mean =      3.346 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8117 
    [ 2.500,  5.000) = 271379 
    [ 5.000,  7.500) = 6282 
    [ 7.500, 10.000) = 584 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.421 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =     13.475 ms/op
     p(99.9900) =     38.097 ms/op
     p(99.9990) =     39.461 ms/op
     p(99.9999) =     39.584 ms/op
    p(100.0000) =     39.584 ms/op


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
# Warmup Iteration   1: 9.477 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.902 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.521 ±(99.9%) 0.012 ms/op
Iteration   1: 3.494 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.464 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.969 ms/op
                 getUser·p0.95:   5.218 ms/op
                 getUser·p0.99:   6.832 ms/op
                 getUser·p0.999:  22.176 ms/op
                 getUser·p0.9999: 24.299 ms/op
                 getUser·p1.00:   26.345 ms/op

Iteration   2: 3.472 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.571 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   6.087 ms/op
                 getUser·p0.999:  25.586 ms/op
                 getUser·p0.9999: 33.395 ms/op
                 getUser·p1.00:   34.079 ms/op

Iteration   3: 3.480 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.776 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  20.125 ms/op
                 getUser·p0.9999: 27.165 ms/op
                 getUser·p1.00:   27.918 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275671
  mean =      3.482 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4044 
    [ 2.500,  5.000) = 261430 
    [ 5.000,  7.500) = 8919 
    [ 7.500, 10.000) = 808 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.464 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      6.406 ms/op
     p(99.9000) =     21.331 ms/op
     p(99.9900) =     31.766 ms/op
     p(99.9990) =     34.029 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


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
# Warmup Iteration   1: 11.050 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 5.413 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.200 ±(99.9%) 0.015 ms/op
Iteration   1: 4.076 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.430 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.954 ms/op
                 listUser·p0.999:  23.460 ms/op
                 listUser·p0.9999: 27.301 ms/op
                 listUser·p1.00:   28.475 ms/op

Iteration   2: 4.136 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.554 ms/op
                 listUser·p0.50:   4.018 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.512 ms/op
                 listUser·p0.999:  15.869 ms/op
                 listUser·p0.9999: 19.431 ms/op
                 listUser·p1.00:   19.759 ms/op

Iteration   3: 4.070 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.698 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   7.051 ms/op
                 listUser·p0.999:  15.204 ms/op
                 listUser·p0.9999: 22.516 ms/op
                 listUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234577
  mean =      4.094 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 226208 
    [ 5.000,  7.500) = 5878 
    [ 7.500, 10.000) = 1625 
    [10.000, 12.500) = 296 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.430 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      7.578 ms/op
     p(99.9000) =     17.498 ms/op
     p(99.9900) =     26.363 ms/op
     p(99.9990) =     28.399 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.184 ± 0.867  ops/ms
ClientPb.existUser                       thrpt       3   9.599 ± 3.880  ops/ms
ClientPb.getUser                         thrpt       3   9.016 ± 1.255  ops/ms
ClientPb.listUser                        thrpt       3   7.872 ± 1.032  ops/ms
ClientPb.createUser                       avgt       3   3.484 ± 0.776   ms/op
ClientPb.existUser                        avgt       3   3.311 ± 1.218   ms/op
ClientPb.getUser                          avgt       3   3.520 ± 2.223   ms/op
ClientPb.listUser                         avgt       3   4.077 ± 1.598   ms/op
ClientPb.createUser                     sample  269338   3.562 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.016           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.379           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.104           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.604           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.283           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.719           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.671           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.850           ms/op
ClientPb.existUser                      sample  286842   3.346 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.421           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.998           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.365           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.475           ms/op
ClientPb.existUser:existUser·p0.9999    sample          38.097           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.584           ms/op
ClientPb.getUser                        sample  275671   3.482 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.464           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.314           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.456           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.406           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.331           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.766           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.079           ms/op
ClientPb.listUser                       sample  234577   4.094 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.430           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.686           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.578           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.498           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.363           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.475           ms/op
