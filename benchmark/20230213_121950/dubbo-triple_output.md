# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.362 ops/ms
# Warmup Iteration   2: 6.283 ops/ms
# Warmup Iteration   3: 8.682 ops/ms
Iteration   1: 9.379 ops/ms
Iteration   2: 9.340 ops/ms
Iteration   3: 9.407 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.375 ±(99.9%) 0.609 ops/ms [Average]
  (min, avg, max) = (9.340, 9.375, 9.407), stdev = 0.033
  CI (99.9%): [8.766, 9.984] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.356 ops/ms
# Warmup Iteration   2: 9.896 ops/ms
# Warmup Iteration   3: 10.623 ops/ms
Iteration   1: 10.402 ops/ms
Iteration   2: 10.261 ops/ms
Iteration   3: 10.619 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.428 ±(99.9%) 3.291 ops/ms [Average]
  (min, avg, max) = (10.261, 10.428, 10.619), stdev = 0.180
  CI (99.9%): [7.137, 13.718] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.676 ops/ms
# Warmup Iteration   2: 9.025 ops/ms
# Warmup Iteration   3: 9.323 ops/ms
Iteration   1: 9.430 ops/ms
Iteration   2: 9.720 ops/ms
Iteration   3: 9.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.504 ±(99.9%) 3.482 ops/ms [Average]
  (min, avg, max) = (9.360, 9.504, 9.720), stdev = 0.191
  CI (99.9%): [6.022, 12.985] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.894 ops/ms
# Warmup Iteration   2: 7.109 ops/ms
# Warmup Iteration   3: 7.897 ops/ms
Iteration   1: 7.748 ops/ms
Iteration   2: 8.623 ops/ms
Iteration   3: 8.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.178 ±(99.9%) 7.989 ops/ms [Average]
  (min, avg, max) = (7.748, 8.178, 8.623), stdev = 0.438
  CI (99.9%): [0.189, 16.167] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.151 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.516 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.703 ±(99.9%) 0.005 ms/op
Iteration   1: 3.339 ±(99.9%) 0.004 ms/op
Iteration   2: 3.097 ±(99.9%) 0.005 ms/op
Iteration   3: 3.171 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.202 ±(99.9%) 2.266 ms/op [Average]
  (min, avg, max) = (3.097, 3.202, 3.339), stdev = 0.124
  CI (99.9%): [0.937, 5.468] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 6.924 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.418 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.140 ±(99.9%) 0.004 ms/op
Iteration   1: 3.209 ±(99.9%) 0.010 ms/op
Iteration   2: 3.066 ±(99.9%) 0.005 ms/op
Iteration   3: 3.098 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.125 ±(99.9%) 1.370 ms/op [Average]
  (min, avg, max) = (3.066, 3.125, 3.209), stdev = 0.075
  CI (99.9%): [1.755, 4.494] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 7.379 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.469 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.177 ±(99.9%) 0.006 ms/op
Iteration   1: 3.464 ±(99.9%) 0.006 ms/op
Iteration   2: 3.599 ±(99.9%) 0.004 ms/op
Iteration   3: 3.619 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.561 ±(99.9%) 1.541 ms/op [Average]
  (min, avg, max) = (3.464, 3.561, 3.619), stdev = 0.084
  CI (99.9%): [2.020, 5.101] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 9.958 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.251 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.997 ±(99.9%) 0.008 ms/op
Iteration   1: 4.100 ±(99.9%) 0.010 ms/op
Iteration   2: 4.133 ±(99.9%) 0.011 ms/op
Iteration   3: 4.107 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.113 ±(99.9%) 0.317 ms/op [Average]
  (min, avg, max) = (4.100, 4.113, 4.133), stdev = 0.017
  CI (99.9%): [3.796, 4.431] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.729 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.509 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.123 ±(99.9%) 0.009 ms/op
Iteration   1: 3.299 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.039 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   5.358 ms/op
                 createUser·p0.999:  14.726 ms/op
                 createUser·p0.9999: 27.251 ms/op
                 createUser·p1.00:   29.557 ms/op

Iteration   2: 3.182 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.439 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   6.062 ms/op
                 createUser·p0.999:  13.337 ms/op
                 createUser·p0.9999: 25.199 ms/op
                 createUser·p1.00:   25.952 ms/op

Iteration   3: 3.081 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.286 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.219 ms/op
                 createUser·p0.95:   3.445 ms/op
                 createUser·p0.99:   5.339 ms/op
                 createUser·p0.999:  19.994 ms/op
                 createUser·p0.9999: 32.471 ms/op
                 createUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301260
  mean =      3.185 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22565 
    [ 2.500,  5.000) = 273521 
    [ 5.000,  7.500) = 4046 
    [ 7.500, 10.000) = 630 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.439 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     19.792 ms/op
     p(99.9900) =     30.892 ms/op
     p(99.9990) =     33.684 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.906 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.564 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.388 ±(99.9%) 0.010 ms/op
Iteration   1: 3.269 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.702 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  9.472 ms/op
                 existUser·p0.9999: 24.059 ms/op
                 existUser·p1.00:   25.788 ms/op

Iteration   2: 3.088 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.046 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  10.011 ms/op
                 existUser·p0.9999: 25.096 ms/op
                 existUser·p1.00:   26.051 ms/op

Iteration   3: 3.204 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.722 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   4.141 ms/op
                 existUser·p0.99:   6.069 ms/op
                 existUser·p0.999:  12.485 ms/op
                 existUser·p0.9999: 25.690 ms/op
                 existUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301565
  mean =      3.185 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13996 
    [ 2.500,  5.000) = 283095 
    [ 5.000,  7.500) = 3560 
    [ 7.500, 10.000) = 508 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 159 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.046 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     11.567 ms/op
     p(99.9900) =     25.203 ms/op
     p(99.9990) =     26.246 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.790 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.809 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.385 ±(99.9%) 0.012 ms/op
Iteration   1: 3.230 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.632 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   6.373 ms/op
                 getUser·p0.999:  10.469 ms/op
                 getUser·p0.9999: 23.003 ms/op
                 getUser·p1.00:   23.429 ms/op

Iteration   2: 3.220 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.647 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   5.931 ms/op
                 getUser·p0.999:  12.166 ms/op
                 getUser·p0.9999: 25.140 ms/op
                 getUser·p1.00:   25.985 ms/op

Iteration   3: 3.281 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.507 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  12.087 ms/op
                 getUser·p0.9999: 29.270 ms/op
                 getUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296069
  mean =      3.243 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22135 
    [ 2.500,  5.000) = 266091 
    [ 5.000,  7.500) = 6790 
    [ 7.500, 10.000) = 660 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 121 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.507 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.218 ms/op
     p(99.9000) =     12.055 ms/op
     p(99.9900) =     28.658 ms/op
     p(99.9990) =     29.492 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.080 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.354 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.194 ±(99.9%) 0.014 ms/op
Iteration   1: 4.237 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.146 ms/op
                 listUser·p0.50:   4.035 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   8.372 ms/op
                 listUser·p0.999:  18.484 ms/op
                 listUser·p0.9999: 25.574 ms/op
                 listUser·p1.00:   25.887 ms/op

Iteration   2: 4.013 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.803 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  16.712 ms/op
                 listUser·p0.9999: 19.205 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   3: 3.895 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.470 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  15.856 ms/op
                 listUser·p0.9999: 20.196 ms/op
                 listUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237229
  mean =      4.043 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 225220 
    [ 5.000,  7.500) = 9478 
    [ 7.500, 10.000) = 1452 
    [10.000, 12.500) = 549 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 240 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      2.146 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      7.627 ms/op
     p(99.9000) =     16.724 ms/op
     p(99.9900) =     24.356 ms/op
     p(99.9990) =     25.875 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.375 ± 0.609  ops/ms
ClientPb.existUser                       thrpt       3  10.428 ± 3.291  ops/ms
ClientPb.getUser                         thrpt       3   9.504 ± 3.482  ops/ms
ClientPb.listUser                        thrpt       3   8.178 ± 7.989  ops/ms
ClientPb.createUser                       avgt       3   3.202 ± 2.266   ms/op
ClientPb.existUser                        avgt       3   3.125 ± 1.370   ms/op
ClientPb.getUser                          avgt       3   3.561 ± 1.541   ms/op
ClientPb.listUser                         avgt       3   4.113 ± 0.317   ms/op
ClientPb.createUser                     sample  301260   3.185 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.439           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.510           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.636           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.792           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.892           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.406           ms/op
ClientPb.existUser                      sample  301565   3.185 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.046           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.539           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.858           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.521           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.567           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.203           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.509           ms/op
ClientPb.getUser                        sample  296069   3.243 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.507           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.772           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.218           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.055           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.658           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.655           ms/op
ClientPb.listUser                       sample  237229   4.043 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.146           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.014           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.627           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.724           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.356           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.887           ms/op
