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
# Warmup Iteration   1: 2.477 ops/ms
# Warmup Iteration   2: 6.441 ops/ms
# Warmup Iteration   3: 9.007 ops/ms
Iteration   1: 9.957 ops/ms
Iteration   2: 9.955 ops/ms
Iteration   3: 9.872 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.928 ±(99.9%) 0.882 ops/ms [Average]
  (min, avg, max) = (9.872, 9.928, 9.957), stdev = 0.048
  CI (99.9%): [9.046, 10.810] (assumes normal distribution)


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
# Warmup Iteration   1: 3.751 ops/ms
# Warmup Iteration   2: 9.653 ops/ms
# Warmup Iteration   3: 10.246 ops/ms
Iteration   1: 10.324 ops/ms
Iteration   2: 10.380 ops/ms
Iteration   3: 10.201 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.301 ±(99.9%) 1.674 ops/ms [Average]
  (min, avg, max) = (10.201, 10.301, 10.380), stdev = 0.092
  CI (99.9%): [8.628, 11.975] (assumes normal distribution)


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
# Warmup Iteration   1: 3.390 ops/ms
# Warmup Iteration   2: 9.217 ops/ms
# Warmup Iteration   3: 9.781 ops/ms
Iteration   1: 9.682 ops/ms
Iteration   2: 10.021 ops/ms
Iteration   3: 9.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.826 ±(99.9%) 3.196 ops/ms [Average]
  (min, avg, max) = (9.682, 9.826, 10.021), stdev = 0.175
  CI (99.9%): [6.630, 13.021] (assumes normal distribution)


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
# Warmup Iteration   1: 3.564 ops/ms
# Warmup Iteration   2: 8.094 ops/ms
# Warmup Iteration   3: 8.478 ops/ms
Iteration   1: 8.385 ops/ms
Iteration   2: 8.504 ops/ms
Iteration   3: 8.592 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.494 ±(99.9%) 1.892 ops/ms [Average]
  (min, avg, max) = (8.385, 8.494, 8.592), stdev = 0.104
  CI (99.9%): [6.602, 10.385] (assumes normal distribution)


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
# Warmup Iteration   1: 8.598 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.530 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.375 ±(99.9%) 0.003 ms/op
Iteration   1: 3.278 ±(99.9%) 0.005 ms/op
Iteration   2: 3.214 ±(99.9%) 0.004 ms/op
Iteration   3: 3.175 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.222 ±(99.9%) 0.955 ms/op [Average]
  (min, avg, max) = (3.175, 3.222, 3.278), stdev = 0.052
  CI (99.9%): [2.267, 4.177] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 7.194 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.253 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.004 ms/op
Iteration   1: 3.043 ±(99.9%) 0.003 ms/op
Iteration   2: 3.062 ±(99.9%) 0.003 ms/op
Iteration   3: 3.146 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.083 ±(99.9%) 1.000 ms/op [Average]
  (min, avg, max) = (3.043, 3.083, 3.146), stdev = 0.055
  CI (99.9%): [2.083, 4.084] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.694 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.322 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.301 ±(99.9%) 0.003 ms/op
Iteration   1: 3.285 ±(99.9%) 0.003 ms/op
Iteration   2: 3.228 ±(99.9%) 0.001 ms/op
Iteration   3: 3.180 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.231 ±(99.9%) 0.954 ms/op [Average]
  (min, avg, max) = (3.180, 3.231, 3.285), stdev = 0.052
  CI (99.9%): [2.277, 4.185] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.317 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.030 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.840 ±(99.9%) 0.003 ms/op
Iteration   1: 3.723 ±(99.9%) 0.006 ms/op
Iteration   2: 3.760 ±(99.9%) 0.003 ms/op
Iteration   3: 3.739 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.741 ±(99.9%) 0.339 ms/op [Average]
  (min, avg, max) = (3.723, 3.741, 3.760), stdev = 0.019
  CI (99.9%): [3.402, 4.080] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.975 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.688 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.256 ±(99.9%) 0.008 ms/op
Iteration   1: 3.307 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.992 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   5.497 ms/op
                 createUser·p0.999:  12.435 ms/op
                 createUser·p0.9999: 20.535 ms/op
                 createUser·p1.00:   20.808 ms/op

Iteration   2: 3.269 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.848 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   4.801 ms/op
                 createUser·p0.999:  17.456 ms/op
                 createUser·p0.9999: 22.977 ms/op
                 createUser·p1.00:   23.888 ms/op

Iteration   3: 3.225 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.401 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   5.587 ms/op
                 createUser·p0.999:  15.254 ms/op
                 createUser·p0.9999: 21.168 ms/op
                 createUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293777
  mean =      3.267 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16916 
    [ 2.500,  5.000) = 272947 
    [ 5.000,  7.500) = 3094 
    [ 7.500, 10.000) = 314 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     15.254 ms/op
     p(99.9900) =     22.184 ms/op
     p(99.9990) =     23.241 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.903 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 3.351 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.132 ±(99.9%) 0.007 ms/op
Iteration   1: 3.180 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.229 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   6.177 ms/op
                 existUser·p0.999:  10.065 ms/op
                 existUser·p0.9999: 20.241 ms/op
                 existUser·p1.00:   20.808 ms/op

Iteration   2: 3.203 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.014 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.858 ms/op
                 existUser·p0.99:   5.778 ms/op
                 existUser·p0.999:  10.387 ms/op
                 existUser·p0.9999: 21.595 ms/op
                 existUser·p1.00:   22.741 ms/op

Iteration   3: 3.192 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.278 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   5.571 ms/op
                 existUser·p0.999:  14.032 ms/op
                 existUser·p0.9999: 21.560 ms/op
                 existUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300743
  mean =      3.192 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19072 
    [ 2.500,  5.000) = 275648 
    [ 5.000,  7.500) = 5258 
    [ 7.500, 10.000) = 345 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.014 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =     10.965 ms/op
     p(99.9900) =     21.398 ms/op
     p(99.9990) =     22.708 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


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
# Warmup Iteration   1: 7.562 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.376 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.229 ±(99.9%) 0.008 ms/op
Iteration   1: 3.273 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.323 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   6.185 ms/op
                 getUser·p0.999:  17.302 ms/op
                 getUser·p0.9999: 21.660 ms/op
                 getUser·p1.00:   22.512 ms/op

Iteration   2: 3.141 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.128 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  19.857 ms/op
                 getUser·p0.9999: 22.369 ms/op
                 getUser·p1.00:   23.298 ms/op

Iteration   3: 3.213 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   6.431 ms/op
                 getUser·p0.999:  13.418 ms/op
                 getUser·p0.9999: 18.416 ms/op
                 getUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299076
  mean =      3.208 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11464 
    [ 2.500,  5.000) = 282399 
    [ 5.000,  7.500) = 4007 
    [ 7.500, 10.000) = 705 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     15.737 ms/op
     p(99.9900) =     21.892 ms/op
     p(99.9990) =     23.103 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


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
# Warmup Iteration   1: 8.298 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 4.124 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.823 ±(99.9%) 0.009 ms/op
Iteration   1: 3.778 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.620 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  14.778 ms/op
                 listUser·p0.9999: 17.990 ms/op
                 listUser·p1.00:   18.907 ms/op

Iteration   2: 3.803 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.064 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  13.434 ms/op
                 listUser·p0.9999: 16.882 ms/op
                 listUser·p1.00:   19.497 ms/op

Iteration   3: 3.715 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.174 ms/op
                 listUser·p0.99:   6.247 ms/op
                 listUser·p0.999:  12.616 ms/op
                 listUser·p0.9999: 15.948 ms/op
                 listUser·p1.00:   15.991 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254796
  mean =      3.765 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 80 
    [ 2.500,  3.750) = 167508 
    [ 3.750,  5.000) = 80815 
    [ 5.000,  6.250) = 2618 
    [ 6.250,  7.500) = 2425 
    [ 7.500,  8.750) = 394 
    [ 8.750, 10.000) = 148 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 256 
    [12.500, 13.750) = 204 
    [13.750, 15.000) = 134 
    [15.000, 16.250) = 74 
    [16.250, 17.500) = 34 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.620 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.627 ms/op
     p(99.9000) =     14.090 ms/op
     p(99.9900) =     17.632 ms/op
     p(99.9990) =     19.303 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.928 ± 0.882  ops/ms
ClientPb.existUser                       thrpt       3  10.301 ± 1.674  ops/ms
ClientPb.getUser                         thrpt       3   9.826 ± 3.196  ops/ms
ClientPb.listUser                        thrpt       3   8.494 ± 1.892  ops/ms
ClientPb.createUser                       avgt       3   3.222 ± 0.955   ms/op
ClientPb.existUser                        avgt       3   3.083 ± 1.000   ms/op
ClientPb.getUser                          avgt       3   3.231 ± 0.954   ms/op
ClientPb.listUser                         avgt       3   3.741 ± 0.339   ms/op
ClientPb.createUser                     sample  293777   3.267 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.848           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.723           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.961           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.448           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.254           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.184           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.888           ms/op
ClientPb.existUser                      sample  300743   3.192 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.014           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.473           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.867           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.070           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.965           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.398           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.839           ms/op
ClientPb.getUser                        sample  299076   3.208 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.860           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.555           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.825           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.737           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.892           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.298           ms/op
ClientPb.listUser                       sample  254796   3.765 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.620           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.654           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.088           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.627           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.090           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.632           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.497           ms/op
