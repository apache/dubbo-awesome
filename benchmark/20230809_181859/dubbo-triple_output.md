# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.027 ops/ms
# Warmup Iteration   2: 4.843 ops/ms
# Warmup Iteration   3: 8.387 ops/ms
Iteration   1: 8.687 ops/ms
Iteration   2: 9.170 ops/ms
Iteration   3: 9.206 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.021 ±(99.9%) 5.284 ops/ms [Average]
  (min, avg, max) = (8.687, 9.021, 9.206), stdev = 0.290
  CI (99.9%): [3.737, 14.305] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.285 ops/ms
# Warmup Iteration   2: 8.369 ops/ms
# Warmup Iteration   3: 9.014 ops/ms
Iteration   1: 9.584 ops/ms
Iteration   2: 9.515 ops/ms
Iteration   3: 9.406 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.501 ±(99.9%) 1.635 ops/ms [Average]
  (min, avg, max) = (9.406, 9.501, 9.584), stdev = 0.090
  CI (99.9%): [7.867, 11.136] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.683 ops/ms
# Warmup Iteration   2: 8.010 ops/ms
# Warmup Iteration   3: 8.938 ops/ms
Iteration   1: 9.005 ops/ms
Iteration   2: 8.922 ops/ms
Iteration   3: 9.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.003 ±(99.9%) 1.461 ops/ms [Average]
  (min, avg, max) = (8.922, 9.003, 9.082), stdev = 0.080
  CI (99.9%): [7.542, 10.463] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.921 ops/ms
# Warmup Iteration   2: 6.727 ops/ms
# Warmup Iteration   3: 7.473 ops/ms
Iteration   1: 7.546 ops/ms
Iteration   2: 7.901 ops/ms
Iteration   3: 7.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.730 ±(99.9%) 3.240 ops/ms [Average]
  (min, avg, max) = (7.546, 7.730, 7.901), stdev = 0.178
  CI (99.9%): [4.491, 10.970] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 9.938 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.790 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.779 ±(99.9%) 0.003 ms/op
Iteration   1: 3.476 ±(99.9%) 0.005 ms/op
Iteration   2: 3.473 ±(99.9%) 0.008 ms/op
Iteration   3: 3.539 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.496 ±(99.9%) 0.684 ms/op [Average]
  (min, avg, max) = (3.473, 3.496, 3.539), stdev = 0.037
  CI (99.9%): [2.812, 4.180] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.969 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.591 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.468 ±(99.9%) 0.004 ms/op
Iteration   1: 3.329 ±(99.9%) 0.004 ms/op
Iteration   2: 3.336 ±(99.9%) 0.006 ms/op
Iteration   3: 3.289 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.318 ±(99.9%) 0.460 ms/op [Average]
  (min, avg, max) = (3.289, 3.318, 3.336), stdev = 0.025
  CI (99.9%): [2.858, 3.779] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.221 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.881 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.596 ±(99.9%) 0.004 ms/op
Iteration   1: 3.456 ±(99.9%) 0.004 ms/op
Iteration   2: 3.410 ±(99.9%) 0.005 ms/op
Iteration   3: 3.415 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.427 ±(99.9%) 0.465 ms/op [Average]
  (min, avg, max) = (3.410, 3.427, 3.456), stdev = 0.025
  CI (99.9%): [2.963, 3.892] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.531 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.650 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.389 ±(99.9%) 0.004 ms/op
Iteration   1: 4.180 ±(99.9%) 0.009 ms/op
Iteration   2: 4.007 ±(99.9%) 0.012 ms/op
Iteration   3: 4.064 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.084 ±(99.9%) 1.610 ms/op [Average]
  (min, avg, max) = (4.007, 4.084, 4.180), stdev = 0.088
  CI (99.9%): [2.473, 5.694] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.470 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 3.989 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.432 ±(99.9%) 0.009 ms/op
Iteration   1: 3.556 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.311 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   4.055 ms/op
                 createUser·p0.95:   5.038 ms/op
                 createUser·p0.99:   6.988 ms/op
                 createUser·p0.999:  21.400 ms/op
                 createUser·p0.9999: 27.099 ms/op
                 createUser·p1.00:   27.689 ms/op

Iteration   2: 3.562 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.311 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   4.076 ms/op
                 createUser·p0.95:   4.620 ms/op
                 createUser·p0.99:   7.029 ms/op
                 createUser·p0.999:  23.377 ms/op
                 createUser·p0.9999: 30.769 ms/op
                 createUser·p1.00:   31.556 ms/op

Iteration   3: 3.449 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.628 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   6.414 ms/op
                 createUser·p0.999:  18.888 ms/op
                 createUser·p0.9999: 26.893 ms/op
                 createUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272521
  mean =      3.521 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6000 
    [ 2.500,  5.000) = 255632 
    [ 5.000,  7.500) = 8932 
    [ 7.500, 10.000) = 1241 
    [10.000, 12.500) = 303 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.311 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     19.431 ms/op
     p(99.9900) =     29.286 ms/op
     p(99.9990) =     31.189 ms/op
     p(99.9999) =     31.556 ms/op
    p(100.0000) =     31.556 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.034 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.719 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.349 ±(99.9%) 0.008 ms/op
Iteration   1: 3.429 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.651 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   3.863 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  14.434 ms/op
                 existUser·p0.9999: 23.658 ms/op
                 existUser·p1.00:   26.411 ms/op

Iteration   2: 3.519 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.473 ms/op
                 existUser·p0.50:   3.359 ms/op
                 existUser·p0.90:   4.014 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   7.172 ms/op
                 existUser·p0.999:  20.775 ms/op
                 existUser·p0.9999: 28.798 ms/op
                 existUser·p1.00:   29.917 ms/op

Iteration   3: 3.490 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.196 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.719 ms/op
                 existUser·p0.99:   6.824 ms/op
                 existUser·p0.999:  21.239 ms/op
                 existUser·p0.9999: 26.673 ms/op
                 existUser·p1.00:   27.427 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 275597
  mean =      3.479 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10094 
    [ 2.500,  5.000) = 255507 
    [ 5.000,  7.500) = 8376 
    [ 7.500, 10.000) = 1039 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.196 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     15.791 ms/op
     p(99.9900) =     26.673 ms/op
     p(99.9990) =     29.712 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.145 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.032 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.589 ±(99.9%) 0.011 ms/op
Iteration   1: 3.622 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.864 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   4.076 ms/op
                 getUser·p0.95:   5.464 ms/op
                 getUser·p0.99:   7.291 ms/op
                 getUser·p0.999:  21.291 ms/op
                 getUser·p0.9999: 24.445 ms/op
                 getUser·p1.00:   27.427 ms/op

Iteration   2: 3.490 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.647 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  23.265 ms/op
                 getUser·p0.9999: 26.690 ms/op
                 getUser·p1.00:   27.230 ms/op

Iteration   3: 3.558 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.559 ms/op
                 getUser·p0.50:   3.449 ms/op
                 getUser·p0.90:   3.932 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   7.037 ms/op
                 getUser·p0.999:  23.069 ms/op
                 getUser·p0.9999: 30.409 ms/op
                 getUser·p1.00:   31.130 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 269783
  mean =      3.556 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4306 
    [ 2.500,  5.000) = 254891 
    [ 5.000,  7.500) = 8721 
    [ 7.500, 10.000) = 1211 
    [10.000, 12.500) = 270 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 153 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.559 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     21.896 ms/op
     p(99.9900) =     28.705 ms/op
     p(99.9990) =     30.881 ms/op
     p(99.9999) =     31.130 ms/op
    p(100.0000) =     31.130 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.512 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.888 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.448 ±(99.9%) 0.015 ms/op
Iteration   1: 4.299 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.841 ms/op
                 listUser·p0.50:   4.039 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.947 ms/op
                 listUser·p0.99:   8.284 ms/op
                 listUser·p0.999:  23.938 ms/op
                 listUser·p0.9999: 26.986 ms/op
                 listUser·p1.00:   28.639 ms/op

Iteration   2: 4.083 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.376 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   8.364 ms/op
                 listUser·p0.999:  16.040 ms/op
                 listUser·p0.9999: 17.995 ms/op
                 listUser·p1.00:   19.628 ms/op

Iteration   3: 4.253 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.212 ms/op
                 listUser·p0.50:   4.067 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.202 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  18.492 ms/op
                 listUser·p0.9999: 21.446 ms/op
                 listUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 227903
  mean =      4.210 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 81 
    [ 2.500,  5.000) = 213715 
    [ 5.000,  7.500) = 10687 
    [ 7.500, 10.000) = 2042 
    [10.000, 12.500) = 728 
    [12.500, 15.000) = 170 
    [15.000, 17.500) = 210 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      1.841 ms/op
     p(50.0000) =      4.006 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.300 ms/op
     p(99.0000) =      8.389 ms/op
     p(99.9000) =     18.845 ms/op
     p(99.9900) =     25.599 ms/op
     p(99.9990) =     27.245 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.021 ± 5.284  ops/ms
ClientPb.existUser                       thrpt       3   9.501 ± 1.635  ops/ms
ClientPb.getUser                         thrpt       3   9.003 ± 1.461  ops/ms
ClientPb.listUser                        thrpt       3   7.730 ± 3.240  ops/ms
ClientPb.createUser                       avgt       3   3.496 ± 0.684   ms/op
ClientPb.existUser                        avgt       3   3.318 ± 0.460   ms/op
ClientPb.getUser                          avgt       3   3.427 ± 0.465   ms/op
ClientPb.listUser                         avgt       3   4.084 ± 1.610   ms/op
ClientPb.createUser                     sample  272521   3.521 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.311           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.334           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.014           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.760           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.922           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.431           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.286           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.556           ms/op
ClientPb.existUser                      sample  275597   3.479 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.196           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.338           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.010           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.538           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.832           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.791           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.673           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.917           ms/op
ClientPb.getUser                        sample  269783   3.556 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.559           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.416           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.932           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.424           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.094           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.896           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.705           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.130           ms/op
ClientPb.listUser                       sample  227903   4.210 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.841           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.006           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.678           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.300           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.389           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.845           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.599           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.639           ms/op
