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
# Warmup Iteration   1: 1.765 ops/ms
# Warmup Iteration   2: 3.575 ops/ms
# Warmup Iteration   3: 7.260 ops/ms
Iteration   1: 8.083 ops/ms
Iteration   2: 6.906 ops/ms
Iteration   3: 7.990 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.660 ±(99.9%) 11.937 ops/ms [Average]
  (min, avg, max) = (6.906, 7.660, 8.083), stdev = 0.654
  CI (99.9%): [≈ 0, 19.597] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.176 ops/ms
# Warmup Iteration   2: 6.899 ops/ms
# Warmup Iteration   3: 7.367 ops/ms
Iteration   1: 8.019 ops/ms
Iteration   2: 7.744 ops/ms
Iteration   3: 7.670 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.811 ±(99.9%) 3.355 ops/ms [Average]
  (min, avg, max) = (7.670, 7.811, 8.019), stdev = 0.184
  CI (99.9%): [4.456, 11.166] (assumes normal distribution)


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
# Warmup Iteration   1: 2.205 ops/ms
# Warmup Iteration   2: 6.632 ops/ms
# Warmup Iteration   3: 7.105 ops/ms
Iteration   1: 6.660 ops/ms
Iteration   2: 8.248 ops/ms
Iteration   3: 8.532 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.813 ±(99.9%) 18.406 ops/ms [Average]
  (min, avg, max) = (6.660, 7.813, 8.532), stdev = 1.009
  CI (99.9%): [≈ 0, 26.219] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.890 ops/ms
# Warmup Iteration   2: 5.390 ops/ms
# Warmup Iteration   3: 5.368 ops/ms
Iteration   1: 4.931 ops/ms
Iteration   2: 5.409 ops/ms
Iteration   3: 6.714 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.685 ±(99.9%) 16.835 ops/ms [Average]
  (min, avg, max) = (4.931, 5.685, 6.714), stdev = 0.923
  CI (99.9%): [≈ 0, 22.519] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 14.884 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 5.059 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.253 ±(99.9%) 0.008 ms/op
Iteration   1: 3.952 ±(99.9%) 0.009 ms/op
Iteration   2: 3.869 ±(99.9%) 0.005 ms/op
Iteration   3: 4.102 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.974 ±(99.9%) 2.155 ms/op [Average]
  (min, avg, max) = (3.869, 3.974, 4.102), stdev = 0.118
  CI (99.9%): [1.820, 6.129] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 12.218 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.466 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.847 ±(99.9%) 0.003 ms/op
Iteration   1: 4.196 ±(99.9%) 0.002 ms/op
Iteration   2: 3.919 ±(99.9%) 0.003 ms/op
Iteration   3: 4.219 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.111 ±(99.9%) 3.043 ms/op [Average]
  (min, avg, max) = (3.919, 4.111, 4.219), stdev = 0.167
  CI (99.9%): [1.068, 7.155] (assumes normal distribution)


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
# Warmup Iteration   1: 14.719 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.838 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.324 ±(99.9%) 0.006 ms/op
Iteration   1: 3.847 ±(99.9%) 0.007 ms/op
Iteration   2: 4.681 ±(99.9%) 0.005 ms/op
Iteration   3: 4.622 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.383 ±(99.9%) 8.488 ms/op [Average]
  (min, avg, max) = (3.847, 4.383, 4.681), stdev = 0.465
  CI (99.9%): [≈ 0, 12.871] (assumes normal distribution)


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
# Warmup Iteration   1: 19.487 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 5.889 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.846 ±(99.9%) 0.011 ms/op
Iteration   1: 4.677 ±(99.9%) 0.006 ms/op
Iteration   2: 4.864 ±(99.9%) 0.007 ms/op
Iteration   3: 4.955 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.832 ±(99.9%) 2.592 ms/op [Average]
  (min, avg, max) = (4.677, 4.832, 4.955), stdev = 0.142
  CI (99.9%): [2.240, 7.424] (assumes normal distribution)


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
# Warmup Iteration   1: 13.924 ±(99.9%) 0.192 ms/op
# Warmup Iteration   2: 5.210 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.439 ±(99.9%) 0.019 ms/op
Iteration   1: 4.368 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.520 ms/op
                 createUser·p0.50:   3.949 ms/op
                 createUser·p0.90:   5.530 ms/op
                 createUser·p0.95:   6.660 ms/op
                 createUser·p0.99:   10.191 ms/op
                 createUser·p0.999:  25.756 ms/op
                 createUser·p0.9999: 40.548 ms/op
                 createUser·p1.00:   41.550 ms/op

Iteration   2: 3.944 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.595 ms/op
                 createUser·p0.50:   3.772 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   5.014 ms/op
                 createUser·p0.99:   7.407 ms/op
                 createUser·p0.999:  12.809 ms/op
                 createUser·p0.9999: 28.275 ms/op
                 createUser·p1.00:   29.458 ms/op

Iteration   3: 4.910 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   1.442 ms/op
                 createUser·p0.50:   4.424 ms/op
                 createUser·p0.90:   6.685 ms/op
                 createUser·p0.95:   7.856 ms/op
                 createUser·p0.99:   10.974 ms/op
                 createUser·p0.999:  29.229 ms/op
                 createUser·p0.9999: 45.448 ms/op
                 createUser·p1.00:   46.662 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 219431
  mean =      4.372 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 181038 
    [ 5.000, 10.000) = 36353 
    [10.000, 15.000) = 1590 
    [15.000, 20.000) = 175 
    [20.000, 25.000) = 37 
    [25.000, 30.000) = 119 
    [30.000, 35.000) = 26 
    [35.000, 40.000) = 50 
    [40.000, 45.000) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.442 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      5.767 ms/op
     p(95.0000) =      6.742 ms/op
     p(99.0000) =      9.781 ms/op
     p(99.9000) =     26.167 ms/op
     p(99.9900) =     44.248 ms/op
     p(99.9990) =     46.338 ms/op
     p(99.9999) =     46.662 ms/op
    p(100.0000) =     46.662 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 14.149 ±(99.9%) 0.197 ms/op
# Warmup Iteration   2: 4.561 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.069 ±(99.9%) 0.014 ms/op
Iteration   1: 4.124 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.851 ms/op
                 existUser·p0.50:   3.813 ms/op
                 existUser·p0.90:   5.370 ms/op
                 existUser·p0.95:   6.308 ms/op
                 existUser·p0.99:   8.585 ms/op
                 existUser·p0.999:  14.156 ms/op
                 existUser·p0.9999: 35.389 ms/op
                 existUser·p1.00:   37.159 ms/op

Iteration   2: 4.659 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   1.716 ms/op
                 existUser·p0.50:   4.157 ms/op
                 existUser·p0.90:   6.103 ms/op
                 existUser·p0.95:   7.463 ms/op
                 existUser·p0.99:   12.583 ms/op
                 existUser·p0.999:  27.472 ms/op
                 existUser·p0.9999: 32.215 ms/op
                 existUser·p1.00:   33.063 ms/op

Iteration   3: 4.451 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.167 ms/op
                 existUser·p0.50:   4.092 ms/op
                 existUser·p0.90:   5.652 ms/op
                 existUser·p0.95:   6.676 ms/op
                 existUser·p0.99:   10.207 ms/op
                 existUser·p0.999:  19.300 ms/op
                 existUser·p0.9999: 31.844 ms/op
                 existUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 218011
  mean =      4.400 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 760 
    [ 2.500,  5.000) = 179285 
    [ 5.000,  7.500) = 30697 
    [ 7.500, 10.000) = 4640 
    [10.000, 12.500) = 1516 
    [12.500, 15.000) = 593 
    [15.000, 17.500) = 184 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 70 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.985 ms/op
     p(90.0000) =      5.734 ms/op
     p(95.0000) =      6.734 ms/op
     p(99.0000) =     10.617 ms/op
     p(99.9000) =     23.752 ms/op
     p(99.9900) =     34.669 ms/op
     p(99.9990) =     35.843 ms/op
     p(99.9999) =     37.159 ms/op
    p(100.0000) =     37.159 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.583 ±(99.9%) 0.182 ms/op
# Warmup Iteration   2: 4.709 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.212 ±(99.9%) 0.017 ms/op
Iteration   1: 4.363 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.810 ms/op
                 getUser·p0.50:   4.059 ms/op
                 getUser·p0.90:   5.464 ms/op
                 getUser·p0.95:   6.570 ms/op
                 getUser·p0.99:   9.208 ms/op
                 getUser·p0.999:  17.320 ms/op
                 getUser·p0.9999: 25.559 ms/op
                 getUser·p1.00:   25.919 ms/op

Iteration   2: 4.082 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.571 ms/op
                 getUser·p0.50:   3.838 ms/op
                 getUser·p0.90:   4.882 ms/op
                 getUser·p0.95:   5.718 ms/op
                 getUser·p0.99:   8.486 ms/op
                 getUser·p0.999:  26.434 ms/op
                 getUser·p0.9999: 30.781 ms/op
                 getUser·p1.00:   31.719 ms/op

Iteration   3: 4.259 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.356 ms/op
                 getUser·p0.50:   3.977 ms/op
                 getUser·p0.90:   5.177 ms/op
                 getUser·p0.95:   6.193 ms/op
                 getUser·p0.99:   8.929 ms/op
                 getUser·p0.999:  18.380 ms/op
                 getUser·p0.9999: 30.802 ms/op
                 getUser·p1.00:   33.161 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 226839
  mean =      4.232 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 166 
    [ 2.500,  5.000) = 200152 
    [ 5.000,  7.500) = 21529 
    [ 7.500, 10.000) = 3632 
    [10.000, 12.500) = 856 
    [12.500, 15.000) = 221 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 82 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.356 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      6.152 ms/op
     p(99.0000) =      8.946 ms/op
     p(99.9000) =     19.764 ms/op
     p(99.9900) =     30.671 ms/op
     p(99.9990) =     31.702 ms/op
     p(99.9999) =     33.161 ms/op
    p(100.0000) =     33.161 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.100 ±(99.9%) 0.240 ms/op
# Warmup Iteration   2: 5.577 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.751 ±(99.9%) 0.017 ms/op
Iteration   1: 6.136 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   2.130 ms/op
                 listUser·p0.50:   5.382 ms/op
                 listUser·p0.90:   8.995 ms/op
                 listUser·p0.95:   10.535 ms/op
                 listUser·p0.99:   14.741 ms/op
                 listUser·p0.999:  27.066 ms/op
                 listUser·p0.9999: 39.570 ms/op
                 listUser·p1.00:   40.239 ms/op

Iteration   2: 5.466 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.335 ms/op
                 listUser·p0.50:   4.809 ms/op
                 listUser·p0.90:   7.381 ms/op
                 listUser·p0.95:   8.700 ms/op
                 listUser·p0.99:   13.400 ms/op
                 listUser·p0.999:  24.264 ms/op
                 listUser·p0.9999: 32.705 ms/op
                 listUser·p1.00:   33.751 ms/op

Iteration   3: 6.073 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.620 ms/op
                 listUser·p0.50:   5.677 ms/op
                 listUser·p0.90:   8.053 ms/op
                 listUser·p0.95:   9.306 ms/op
                 listUser·p0.99:   12.426 ms/op
                 listUser·p0.999:  22.632 ms/op
                 listUser·p0.9999: 43.416 ms/op
                 listUser·p1.00:   47.120 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 163297
  mean =      5.875 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 72273 
    [ 5.000, 10.000) = 84265 
    [10.000, 15.000) = 5704 
    [15.000, 20.000) = 672 
    [20.000, 25.000) = 209 
    [25.000, 30.000) = 88 
    [30.000, 35.000) = 36 
    [35.000, 40.000) = 38 
    [40.000, 45.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.620 ms/op
     p(50.0000) =      5.226 ms/op
     p(90.0000) =      8.151 ms/op
     p(95.0000) =      9.585 ms/op
     p(99.0000) =     13.517 ms/op
     p(99.9000) =     25.788 ms/op
     p(99.9900) =     39.562 ms/op
     p(99.9990) =     46.830 ms/op
     p(99.9999) =     47.120 ms/op
    p(100.0000) =     47.120 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   7.660 ± 11.937  ops/ms
ClientPb.existUser                       thrpt       3   7.811 ±  3.355  ops/ms
ClientPb.getUser                         thrpt       3   7.813 ± 18.406  ops/ms
ClientPb.listUser                        thrpt       3   5.685 ± 16.835  ops/ms
ClientPb.createUser                       avgt       3   3.974 ±  2.155   ms/op
ClientPb.existUser                        avgt       3   4.111 ±  3.043   ms/op
ClientPb.getUser                          avgt       3   4.383 ±  8.488   ms/op
ClientPb.listUser                         avgt       3   4.832 ±  2.592   ms/op
ClientPb.createUser                     sample  219431   4.372 ±  0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.442            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.924            ms/op
ClientPb.createUser:createUser·p0.90    sample           5.767            ms/op
ClientPb.createUser:createUser·p0.95    sample           6.742            ms/op
ClientPb.createUser:createUser·p0.99    sample           9.781            ms/op
ClientPb.createUser:createUser·p0.999   sample          26.167            ms/op
ClientPb.createUser:createUser·p0.9999  sample          44.248            ms/op
ClientPb.createUser:createUser·p1.00    sample          46.662            ms/op
ClientPb.existUser                      sample  218011   4.400 ±  0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.167            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.985            ms/op
ClientPb.existUser:existUser·p0.90      sample           5.734            ms/op
ClientPb.existUser:existUser·p0.95      sample           6.734            ms/op
ClientPb.existUser:existUser·p0.99      sample          10.617            ms/op
ClientPb.existUser:existUser·p0.999     sample          23.752            ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.669            ms/op
ClientPb.existUser:existUser·p1.00      sample          37.159            ms/op
ClientPb.getUser                        sample  226839   4.232 ±  0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.356            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.953            ms/op
ClientPb.getUser:getUser·p0.90          sample           5.177            ms/op
ClientPb.getUser:getUser·p0.95          sample           6.152            ms/op
ClientPb.getUser:getUser·p0.99          sample           8.946            ms/op
ClientPb.getUser:getUser·p0.999         sample          19.764            ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.671            ms/op
ClientPb.getUser:getUser·p1.00          sample          33.161            ms/op
ClientPb.listUser                       sample  163297   5.875 ±  0.018   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.620            ms/op
ClientPb.listUser:listUser·p0.50        sample           5.226            ms/op
ClientPb.listUser:listUser·p0.90        sample           8.151            ms/op
ClientPb.listUser:listUser·p0.95        sample           9.585            ms/op
ClientPb.listUser:listUser·p0.99        sample          13.517            ms/op
ClientPb.listUser:listUser·p0.999       sample          25.788            ms/op
ClientPb.listUser:listUser·p0.9999      sample          39.562            ms/op
ClientPb.listUser:listUser·p1.00        sample          47.120            ms/op
