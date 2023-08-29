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
# Warmup Iteration   1: 2.338 ops/ms
# Warmup Iteration   2: 6.089 ops/ms
# Warmup Iteration   3: 8.957 ops/ms
Iteration   1: 9.707 ops/ms
Iteration   2: 9.974 ops/ms
Iteration   3: 9.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.802 ±(99.9%) 2.714 ops/ms [Average]
  (min, avg, max) = (9.707, 9.802, 9.974), stdev = 0.149
  CI (99.9%): [7.088, 12.516] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.292 ops/ms
# Warmup Iteration   2: 8.741 ops/ms
# Warmup Iteration   3: 10.011 ops/ms
Iteration   1: 10.079 ops/ms
Iteration   2: 10.295 ops/ms
Iteration   3: 10.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.163 ±(99.9%) 2.118 ops/ms [Average]
  (min, avg, max) = (10.079, 10.163, 10.295), stdev = 0.116
  CI (99.9%): [8.045, 12.281] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.314 ops/ms
# Warmup Iteration   2: 8.840 ops/ms
# Warmup Iteration   3: 9.396 ops/ms
Iteration   1: 9.804 ops/ms
Iteration   2: 9.797 ops/ms
Iteration   3: 9.953 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.851 ±(99.9%) 1.605 ops/ms [Average]
  (min, avg, max) = (9.797, 9.851, 9.953), stdev = 0.088
  CI (99.9%): [8.247, 11.456] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.479 ops/ms
# Warmup Iteration   2: 7.775 ops/ms
# Warmup Iteration   3: 8.161 ops/ms
Iteration   1: 8.474 ops/ms
Iteration   2: 8.099 ops/ms
Iteration   3: 8.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.298 ±(99.9%) 3.442 ops/ms [Average]
  (min, avg, max) = (8.099, 8.298, 8.474), stdev = 0.189
  CI (99.9%): [4.857, 11.740] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.818 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.825 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.437 ±(99.9%) 0.004 ms/op
Iteration   1: 3.374 ±(99.9%) 0.004 ms/op
Iteration   2: 3.354 ±(99.9%) 0.005 ms/op
Iteration   3: 3.188 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.305 ±(99.9%) 1.859 ms/op [Average]
  (min, avg, max) = (3.188, 3.305, 3.374), stdev = 0.102
  CI (99.9%): [1.446, 5.165] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.232 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.381 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.115 ±(99.9%) 0.002 ms/op
Iteration   1: 3.170 ±(99.9%) 0.005 ms/op
Iteration   2: 3.214 ±(99.9%) 0.004 ms/op
Iteration   3: 3.272 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.219 ±(99.9%) 0.932 ms/op [Average]
  (min, avg, max) = (3.170, 3.219, 3.272), stdev = 0.051
  CI (99.9%): [2.287, 4.151] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.553 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.482 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.309 ±(99.9%) 0.002 ms/op
Iteration   1: 3.246 ±(99.9%) 0.006 ms/op
Iteration   2: 3.177 ±(99.9%) 0.004 ms/op
Iteration   3: 3.369 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.264 ±(99.9%) 1.777 ms/op [Average]
  (min, avg, max) = (3.177, 3.264, 3.369), stdev = 0.097
  CI (99.9%): [1.487, 5.042] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.232 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.123 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.043 ±(99.9%) 0.005 ms/op
Iteration   1: 3.910 ±(99.9%) 0.007 ms/op
Iteration   2: 3.798 ±(99.9%) 0.005 ms/op
Iteration   3: 3.816 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.841 ±(99.9%) 1.094 ms/op [Average]
  (min, avg, max) = (3.798, 3.841, 3.910), stdev = 0.060
  CI (99.9%): [2.747, 4.935] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.706 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.804 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.553 ±(99.9%) 0.013 ms/op
Iteration   1: 3.316 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.033 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   6.021 ms/op
                 createUser·p0.999:  14.117 ms/op
                 createUser·p0.9999: 22.392 ms/op
                 createUser·p1.00:   23.364 ms/op

Iteration   2: 3.433 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.690 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   5.988 ms/op
                 createUser·p0.999:  20.990 ms/op
                 createUser·p0.9999: 29.099 ms/op
                 createUser·p1.00:   29.327 ms/op

Iteration   3: 3.473 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.845 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   6.300 ms/op
                 createUser·p0.999:  19.562 ms/op
                 createUser·p0.9999: 29.018 ms/op
                 createUser·p1.00:   29.491 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281977
  mean =      3.406 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16374 
    [ 2.500,  5.000) = 257993 
    [ 5.000,  7.500) = 6117 
    [ 7.500, 10.000) = 1073 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 130 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.033 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =     19.236 ms/op
     p(99.9900) =     28.862 ms/op
     p(99.9990) =     29.333 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.770 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.682 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.270 ±(99.9%) 0.009 ms/op
Iteration   1: 3.151 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.346 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   5.677 ms/op
                 existUser·p0.999:  12.492 ms/op
                 existUser·p0.9999: 27.323 ms/op
                 existUser·p1.00:   28.508 ms/op

Iteration   2: 3.162 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.081 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   5.915 ms/op
                 existUser·p0.999:  9.863 ms/op
                 existUser·p0.9999: 22.475 ms/op
                 existUser·p1.00:   24.052 ms/op

Iteration   3: 3.152 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.002 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  9.612 ms/op
                 existUser·p0.9999: 22.507 ms/op
                 existUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304105
  mean =      3.155 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15314 
    [ 2.500,  5.000) = 282454 
    [ 5.000,  7.500) = 5309 
    [ 7.500, 10.000) = 693 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 189 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.002 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     11.189 ms/op
     p(99.9900) =     26.214 ms/op
     p(99.9990) =     28.409 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


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
# Warmup Iteration   1: 9.438 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.632 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.350 ±(99.9%) 0.010 ms/op
Iteration   1: 3.412 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.808 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  17.274 ms/op
                 getUser·p0.9999: 22.618 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   2: 3.323 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.579 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   7.037 ms/op
                 getUser·p0.999:  16.860 ms/op
                 getUser·p0.9999: 20.005 ms/op
                 getUser·p1.00:   21.004 ms/op

Iteration   3: 3.280 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.483 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   6.365 ms/op
                 getUser·p0.999:  11.904 ms/op
                 getUser·p0.9999: 23.437 ms/op
                 getUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 287426
  mean =      3.337 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7034 
    [ 2.500,  5.000) = 272006 
    [ 5.000,  7.500) = 6642 
    [ 7.500, 10.000) = 1280 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 140 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.483 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      6.496 ms/op
     p(99.9000) =     16.164 ms/op
     p(99.9900) =     22.446 ms/op
     p(99.9990) =     23.732 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


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
# Warmup Iteration   1: 9.055 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.216 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.888 ±(99.9%) 0.012 ms/op
Iteration   1: 3.805 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.175 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.145 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   7.422 ms/op
                 listUser·p0.999:  17.881 ms/op
                 listUser·p0.9999: 20.729 ms/op
                 listUser·p1.00:   21.070 ms/op

Iteration   2: 3.786 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.915 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   7.032 ms/op
                 listUser·p0.999:  13.980 ms/op
                 listUser·p0.9999: 20.709 ms/op
                 listUser·p1.00:   21.201 ms/op

Iteration   3: 3.767 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.548 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  13.797 ms/op
                 listUser·p0.9999: 15.551 ms/op
                 listUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253540
  mean =      3.786 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 246309 
    [ 5.000,  7.500) = 4962 
    [ 7.500, 10.000) = 1497 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 325 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.548 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     14.376 ms/op
     p(99.9900) =     20.632 ms/op
     p(99.9990) =     21.085 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.802 ± 2.714  ops/ms
ClientPb.existUser                       thrpt       3  10.163 ± 2.118  ops/ms
ClientPb.getUser                         thrpt       3   9.851 ± 1.605  ops/ms
ClientPb.listUser                        thrpt       3   8.298 ± 3.442  ops/ms
ClientPb.createUser                       avgt       3   3.305 ± 1.859   ms/op
ClientPb.existUser                        avgt       3   3.219 ± 0.932   ms/op
ClientPb.getUser                          avgt       3   3.264 ± 1.777   ms/op
ClientPb.listUser                         avgt       3   3.841 ± 1.094   ms/op
ClientPb.createUser                     sample  281977   3.406 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.033           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.351           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.121           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.070           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.236           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.862           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.491           ms/op
ClientPb.existUser                      sample  304105   3.155 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.002           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.420           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.726           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.189           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.214           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.508           ms/op
ClientPb.getUser                        sample  287426   3.337 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.483           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.736           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.076           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.496           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.164           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.446           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.888           ms/op
ClientPb.listUser                       sample  253540   3.786 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.548           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.670           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.096           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.201           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.376           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.632           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.201           ms/op
