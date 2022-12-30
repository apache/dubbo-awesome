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
# Warmup Iteration   1: 2.338 ops/ms
# Warmup Iteration   2: 5.919 ops/ms
# Warmup Iteration   3: 9.144 ops/ms
Iteration   1: 10.057 ops/ms
Iteration   2: 10.027 ops/ms
Iteration   3: 10.151 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.078 ±(99.9%) 1.188 ops/ms [Average]
  (min, avg, max) = (10.027, 10.078, 10.151), stdev = 0.065
  CI (99.9%): [8.891, 11.266] (assumes normal distribution)


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
# Warmup Iteration   1: 4.007 ops/ms
# Warmup Iteration   2: 9.590 ops/ms
# Warmup Iteration   3: 10.533 ops/ms
Iteration   1: 10.161 ops/ms
Iteration   2: 10.525 ops/ms
Iteration   3: 10.268 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.318 ±(99.9%) 3.415 ops/ms [Average]
  (min, avg, max) = (10.161, 10.318, 10.525), stdev = 0.187
  CI (99.9%): [6.903, 13.733] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.635 ops/ms
# Warmup Iteration   2: 9.069 ops/ms
# Warmup Iteration   3: 9.444 ops/ms
Iteration   1: 10.434 ops/ms
Iteration   2: 9.823 ops/ms
Iteration   3: 10.268 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.175 ±(99.9%) 5.760 ops/ms [Average]
  (min, avg, max) = (9.823, 10.175, 10.434), stdev = 0.316
  CI (99.9%): [4.416, 15.935] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.513 ops/ms
# Warmup Iteration   2: 7.836 ops/ms
# Warmup Iteration   3: 8.035 ops/ms
Iteration   1: 8.674 ops/ms
Iteration   2: 8.220 ops/ms
Iteration   3: 8.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.548 ±(99.9%) 5.236 ops/ms [Average]
  (min, avg, max) = (8.220, 8.548, 8.751), stdev = 0.287
  CI (99.9%): [3.312, 13.784] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.125 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.603 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.252 ±(99.9%) 0.004 ms/op
Iteration   1: 3.103 ±(99.9%) 0.004 ms/op
Iteration   2: 3.195 ±(99.9%) 0.009 ms/op
Iteration   3: 3.129 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.142 ±(99.9%) 0.869 ms/op [Average]
  (min, avg, max) = (3.103, 3.142, 3.195), stdev = 0.048
  CI (99.9%): [2.274, 4.011] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 6.796 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.166 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.215 ±(99.9%) 0.002 ms/op
Iteration   1: 3.109 ±(99.9%) 0.005 ms/op
Iteration   2: 3.035 ±(99.9%) 0.006 ms/op
Iteration   3: 3.062 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.069 ±(99.9%) 0.680 ms/op [Average]
  (min, avg, max) = (3.035, 3.069, 3.109), stdev = 0.037
  CI (99.9%): [2.389, 3.748] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.312 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.703 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.430 ±(99.9%) 0.005 ms/op
Iteration   1: 3.102 ±(99.9%) 0.004 ms/op
Iteration   2: 3.122 ±(99.9%) 0.002 ms/op
Iteration   3: 3.104 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.109 ±(99.9%) 0.206 ms/op [Average]
  (min, avg, max) = (3.102, 3.109, 3.122), stdev = 0.011
  CI (99.9%): [2.903, 3.315] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.743 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.995 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.817 ±(99.9%) 0.004 ms/op
Iteration   1: 3.679 ±(99.9%) 0.004 ms/op
Iteration   2: 3.634 ±(99.9%) 0.007 ms/op
Iteration   3: 3.619 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.644 ±(99.9%) 0.563 ms/op [Average]
  (min, avg, max) = (3.619, 3.644, 3.679), stdev = 0.031
  CI (99.9%): [3.081, 4.207] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.168 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.572 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.247 ±(99.9%) 0.009 ms/op
Iteration   1: 3.207 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.458 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  14.433 ms/op
                 createUser·p0.9999: 20.908 ms/op
                 createUser·p1.00:   22.020 ms/op

Iteration   2: 3.194 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.868 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   5.472 ms/op
                 createUser·p0.999:  15.072 ms/op
                 createUser·p0.9999: 22.935 ms/op
                 createUser·p1.00:   24.183 ms/op

Iteration   3: 3.239 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.565 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  14.926 ms/op
                 createUser·p0.9999: 22.286 ms/op
                 createUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298585
  mean =      3.213 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27115 
    [ 2.500,  5.000) = 265654 
    [ 5.000,  7.500) = 4754 
    [ 7.500, 10.000) = 590 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 156 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     14.926 ms/op
     p(99.9900) =     22.193 ms/op
     p(99.9990) =     23.529 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


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
# Warmup Iteration   1: 7.827 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.372 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.167 ±(99.9%) 0.007 ms/op
Iteration   1: 3.124 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.738 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   4.002 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  13.844 ms/op
                 existUser·p0.9999: 19.464 ms/op
                 existUser·p1.00:   20.087 ms/op

Iteration   2: 3.000 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.982 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.416 ms/op
                 existUser·p0.99:   5.112 ms/op
                 existUser·p0.999:  11.484 ms/op
                 existUser·p0.9999: 21.070 ms/op
                 existUser·p1.00:   22.086 ms/op

Iteration   3: 3.250 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.223 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.834 ms/op
                 existUser·p0.95:   4.415 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  10.097 ms/op
                 existUser·p0.9999: 22.157 ms/op
                 existUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307368
  mean =      3.121 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24223 
    [ 2.500,  5.000) = 277380 
    [ 5.000,  7.500) = 5013 
    [ 7.500, 10.000) = 392 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 133 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      5.374 ms/op
     p(99.9000) =     13.053 ms/op
     p(99.9900) =     21.275 ms/op
     p(99.9990) =     22.671 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.903 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.387 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.376 ±(99.9%) 0.011 ms/op
Iteration   1: 3.250 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.251 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   5.702 ms/op
                 getUser·p0.999:  10.900 ms/op
                 getUser·p0.9999: 23.271 ms/op
                 getUser·p1.00:   23.953 ms/op

Iteration   2: 3.114 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.262 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.387 ms/op
                 getUser·p0.95:   3.654 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  11.112 ms/op
                 getUser·p0.9999: 22.049 ms/op
                 getUser·p1.00:   22.610 ms/op

Iteration   3: 3.278 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.243 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   5.800 ms/op
                 getUser·p0.999:  14.533 ms/op
                 getUser·p0.9999: 23.700 ms/op
                 getUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298560
  mean =      3.212 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21296 
    [ 2.500,  5.000) = 270460 
    [ 5.000,  7.500) = 5989 
    [ 7.500, 10.000) = 478 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 125 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.243 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     11.072 ms/op
     p(99.9900) =     23.172 ms/op
     p(99.9990) =     24.675 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


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
# Warmup Iteration   1: 9.093 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.074 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.806 ±(99.9%) 0.012 ms/op
Iteration   1: 3.746 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.858 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  14.828 ms/op
                 listUser·p0.9999: 21.668 ms/op
                 listUser·p1.00:   22.315 ms/op

Iteration   2: 3.709 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.200 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  14.817 ms/op
                 listUser·p0.9999: 20.493 ms/op
                 listUser·p1.00:   21.660 ms/op

Iteration   3: 3.680 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.183 ms/op
                 listUser·p0.50:   3.547 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   6.736 ms/op
                 listUser·p0.999:  14.256 ms/op
                 listUser·p0.9999: 16.728 ms/op
                 listUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258540
  mean =      3.712 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49 
    [ 2.500,  5.000) = 251473 
    [ 5.000,  7.500) = 5171 
    [ 7.500, 10.000) = 1081 
    [10.000, 12.500) = 308 
    [12.500, 15.000) = 262 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.858 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     14.376 ms/op
     p(99.9900) =     19.741 ms/op
     p(99.9990) =     22.074 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.078 ± 1.188  ops/ms
ClientPb.existUser                       thrpt       3  10.318 ± 3.415  ops/ms
ClientPb.getUser                         thrpt       3  10.175 ± 5.760  ops/ms
ClientPb.listUser                        thrpt       3   8.548 ± 5.236  ops/ms
ClientPb.createUser                       avgt       3   3.142 ± 0.869   ms/op
ClientPb.existUser                        avgt       3   3.069 ± 0.680   ms/op
ClientPb.getUser                          avgt       3   3.109 ± 0.206   ms/op
ClientPb.listUser                         avgt       3   3.644 ± 0.563   ms/op
ClientPb.createUser                     sample  298585   3.213 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.868           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.670           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.981           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.571           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.926           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.193           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.183           ms/op
ClientPb.existUser                      sample  307368   3.121 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.738           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.437           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.010           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.374           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.053           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.275           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.872           ms/op
ClientPb.getUser                        sample  298560   3.212 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.243           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.654           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.571           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.072           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.172           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.231           ms/op
ClientPb.listUser                       sample  258540   3.712 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.858           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.600           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.014           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.865           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.376           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.741           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.315           ms/op
