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
# Warmup Iteration   1: 1.999 ops/ms
# Warmup Iteration   2: 5.257 ops/ms
# Warmup Iteration   3: 8.505 ops/ms
Iteration   1: 8.883 ops/ms
Iteration   2: 9.149 ops/ms
Iteration   3: 9.543 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.192 ±(99.9%) 6.061 ops/ms [Average]
  (min, avg, max) = (8.883, 9.192, 9.543), stdev = 0.332
  CI (99.9%): [3.131, 15.253] (assumes normal distribution)


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
# Warmup Iteration   1: 3.287 ops/ms
# Warmup Iteration   2: 8.897 ops/ms
# Warmup Iteration   3: 9.572 ops/ms
Iteration   1: 9.560 ops/ms
Iteration   2: 9.544 ops/ms
Iteration   3: 9.584 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.563 ±(99.9%) 0.371 ops/ms [Average]
  (min, avg, max) = (9.544, 9.563, 9.584), stdev = 0.020
  CI (99.9%): [9.192, 9.933] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.715 ops/ms
# Warmup Iteration   2: 8.049 ops/ms
# Warmup Iteration   3: 9.027 ops/ms
Iteration   1: 9.183 ops/ms
Iteration   2: 9.513 ops/ms
Iteration   3: 9.424 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.374 ±(99.9%) 3.116 ops/ms [Average]
  (min, avg, max) = (9.183, 9.374, 9.513), stdev = 0.171
  CI (99.9%): [6.258, 12.489] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.751 ops/ms
# Warmup Iteration   2: 7.161 ops/ms
# Warmup Iteration   3: 7.465 ops/ms
Iteration   1: 7.694 ops/ms
Iteration   2: 7.839 ops/ms
Iteration   3: 7.783 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.772 ±(99.9%) 1.337 ops/ms [Average]
  (min, avg, max) = (7.694, 7.772, 7.839), stdev = 0.073
  CI (99.9%): [6.435, 9.108] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.087 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.052 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.565 ±(99.9%) 0.008 ms/op
Iteration   1: 3.649 ±(99.9%) 0.007 ms/op
Iteration   2: 3.463 ±(99.9%) 0.008 ms/op
Iteration   3: 3.516 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.543 ±(99.9%) 1.752 ms/op [Average]
  (min, avg, max) = (3.463, 3.543, 3.649), stdev = 0.096
  CI (99.9%): [1.791, 5.295] (assumes normal distribution)


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
# Warmup Iteration   1: 8.160 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.675 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.325 ±(99.9%) 0.007 ms/op
Iteration   1: 3.359 ±(99.9%) 0.004 ms/op
Iteration   2: 3.278 ±(99.9%) 0.005 ms/op
Iteration   3: 3.364 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.333 ±(99.9%) 0.880 ms/op [Average]
  (min, avg, max) = (3.278, 3.333, 3.364), stdev = 0.048
  CI (99.9%): [2.453, 4.214] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.305 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.715 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.497 ±(99.9%) 0.007 ms/op
Iteration   1: 3.494 ±(99.9%) 0.005 ms/op
Iteration   2: 3.457 ±(99.9%) 0.005 ms/op
Iteration   3: 3.469 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.473 ±(99.9%) 0.353 ms/op [Average]
  (min, avg, max) = (3.457, 3.473, 3.494), stdev = 0.019
  CI (99.9%): [3.120, 3.826] (assumes normal distribution)


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
# Warmup Iteration   1: 10.874 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.494 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.112 ±(99.9%) 0.008 ms/op
Iteration   1: 4.175 ±(99.9%) 0.007 ms/op
Iteration   2: 4.050 ±(99.9%) 0.010 ms/op
Iteration   3: 4.069 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.098 ±(99.9%) 1.232 ms/op [Average]
  (min, avg, max) = (4.050, 4.098, 4.175), stdev = 0.068
  CI (99.9%): [2.866, 5.329] (assumes normal distribution)


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
# Warmup Iteration   1: 9.879 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 4.011 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.698 ±(99.9%) 0.012 ms/op
Iteration   1: 3.606 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.829 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   4.686 ms/op
                 createUser·p0.95:   5.022 ms/op
                 createUser·p0.99:   6.818 ms/op
                 createUser·p0.999:  20.913 ms/op
                 createUser·p0.9999: 27.701 ms/op
                 createUser·p1.00:   28.377 ms/op

Iteration   2: 3.471 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.227 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   6.414 ms/op
                 createUser·p0.999:  24.278 ms/op
                 createUser·p0.9999: 26.633 ms/op
                 createUser·p1.00:   28.082 ms/op

Iteration   3: 3.431 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.616 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.915 ms/op
                 createUser·p0.999:  20.494 ms/op
                 createUser·p0.9999: 27.799 ms/op
                 createUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274067
  mean =      3.501 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7544 
    [ 2.500,  5.000) = 256093 
    [ 5.000,  7.500) = 8854 
    [ 7.500, 10.000) = 1064 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 134 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      6.390 ms/op
     p(99.9000) =     20.770 ms/op
     p(99.9900) =     27.479 ms/op
     p(99.9990) =     28.648 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


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
# Warmup Iteration   1: 9.980 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 3.703 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.410 ±(99.9%) 0.010 ms/op
Iteration   1: 3.324 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.346 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   6.291 ms/op
                 existUser·p0.999:  19.817 ms/op
                 existUser·p0.9999: 35.742 ms/op
                 existUser·p1.00:   37.290 ms/op

Iteration   2: 3.367 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.325 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   4.096 ms/op
                 existUser·p0.99:   6.439 ms/op
                 existUser·p0.999:  22.116 ms/op
                 existUser·p0.9999: 27.148 ms/op
                 existUser·p1.00:   27.754 ms/op

Iteration   3: 3.346 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.642 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   4.092 ms/op
                 existUser·p0.99:   6.455 ms/op
                 existUser·p0.999:  12.877 ms/op
                 existUser·p0.9999: 32.440 ms/op
                 existUser·p1.00:   32.932 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286805
  mean =      3.346 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7557 
    [ 2.500,  5.000) = 271027 
    [ 5.000,  7.500) = 6646 
    [ 7.500, 10.000) = 993 
    [10.000, 12.500) = 276 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.325 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      6.414 ms/op
     p(99.9000) =     13.435 ms/op
     p(99.9900) =     34.537 ms/op
     p(99.9990) =     37.168 ms/op
     p(99.9999) =     37.290 ms/op
    p(100.0000) =     37.290 ms/op


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
# Warmup Iteration   1: 9.192 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.862 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.693 ±(99.9%) 0.014 ms/op
Iteration   1: 3.496 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.272 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   6.936 ms/op
                 getUser·p0.999:  22.101 ms/op
                 getUser·p0.9999: 30.268 ms/op
                 getUser·p1.00:   31.687 ms/op

Iteration   2: 3.434 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.427 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   6.513 ms/op
                 getUser·p0.999:  23.524 ms/op
                 getUser·p0.9999: 29.458 ms/op
                 getUser·p1.00:   30.605 ms/op

Iteration   3: 3.475 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.518 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   6.595 ms/op
                 getUser·p0.999:  22.178 ms/op
                 getUser·p0.9999: 30.257 ms/op
                 getUser·p1.00:   31.130 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276734
  mean =      3.468 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5160 
    [ 2.500,  5.000) = 262553 
    [ 5.000,  7.500) = 7240 
    [ 7.500, 10.000) = 1293 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.272 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     22.127 ms/op
     p(99.9900) =     30.135 ms/op
     p(99.9990) =     31.332 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


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
# Warmup Iteration   1: 11.502 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.612 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.197 ±(99.9%) 0.015 ms/op
Iteration   1: 4.088 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.638 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   7.954 ms/op
                 listUser·p0.999:  20.570 ms/op
                 listUser·p0.9999: 24.909 ms/op
                 listUser·p1.00:   25.362 ms/op

Iteration   2: 4.121 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.105 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.104 ms/op
                 listUser·p0.99:   8.118 ms/op
                 listUser·p0.999:  17.400 ms/op
                 listUser·p0.9999: 21.594 ms/op
                 listUser·p1.00:   22.479 ms/op

Iteration   3: 4.021 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.458 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   7.537 ms/op
                 listUser·p0.999:  15.925 ms/op
                 listUser·p0.9999: 20.546 ms/op
                 listUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235547
  mean =      4.077 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 62 
    [ 2.500,  5.000) = 224015 
    [ 5.000,  7.500) = 8672 
    [ 7.500, 10.000) = 1810 
    [10.000, 12.500) = 441 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 207 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.638 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.973 ms/op
     p(99.0000) =      7.873 ms/op
     p(99.9000) =     16.941 ms/op
     p(99.9900) =     23.112 ms/op
     p(99.9990) =     25.252 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.192 ± 6.061  ops/ms
ClientPb.existUser                       thrpt       3   9.563 ± 0.371  ops/ms
ClientPb.getUser                         thrpt       3   9.374 ± 3.116  ops/ms
ClientPb.listUser                        thrpt       3   7.772 ± 1.337  ops/ms
ClientPb.createUser                       avgt       3   3.543 ± 1.752   ms/op
ClientPb.existUser                        avgt       3   3.333 ± 0.880   ms/op
ClientPb.getUser                          avgt       3   3.473 ± 0.353   ms/op
ClientPb.listUser                         avgt       3   4.098 ± 1.232   ms/op
ClientPb.createUser                     sample  274067   3.501 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.227           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.351           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.030           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.809           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.390           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.770           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.479           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.672           ms/op
ClientPb.existUser                      sample  286805   3.346 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.325           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.063           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.414           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.435           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.537           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.290           ms/op
ClientPb.getUser                        sample  276734   3.468 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.272           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.318           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.846           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.243           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.783           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.127           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.135           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.687           ms/op
ClientPb.listUser                       sample  235547   4.077 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.638           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.973           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.873           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.941           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.112           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.362           ms/op
