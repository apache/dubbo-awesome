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
# Warmup Iteration   1: 2.731 ops/ms
# Warmup Iteration   2: 6.702 ops/ms
# Warmup Iteration   3: 9.040 ops/ms
Iteration   1: 9.949 ops/ms
Iteration   2: 9.906 ops/ms
Iteration   3: 9.914 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.923 ±(99.9%) 0.418 ops/ms [Average]
  (min, avg, max) = (9.906, 9.923, 9.949), stdev = 0.023
  CI (99.9%): [9.505, 10.341] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.880 ops/ms
# Warmup Iteration   2: 9.668 ops/ms
# Warmup Iteration   3: 10.176 ops/ms
Iteration   1: 10.127 ops/ms
Iteration   2: 10.646 ops/ms
Iteration   3: 9.938 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.237 ±(99.9%) 6.684 ops/ms [Average]
  (min, avg, max) = (9.938, 10.237, 10.646), stdev = 0.366
  CI (99.9%): [3.553, 16.921] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.232 ops/ms
# Warmup Iteration   2: 9.077 ops/ms
# Warmup Iteration   3: 9.771 ops/ms
Iteration   1: 9.939 ops/ms
Iteration   2: 10.331 ops/ms
Iteration   3: 10.048 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.106 ±(99.9%) 3.690 ops/ms [Average]
  (min, avg, max) = (9.939, 10.106, 10.331), stdev = 0.202
  CI (99.9%): [6.416, 13.795] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.166 ops/ms
# Warmup Iteration   2: 7.711 ops/ms
# Warmup Iteration   3: 8.433 ops/ms
Iteration   1: 8.420 ops/ms
Iteration   2: 8.695 ops/ms
Iteration   3: 8.794 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.636 ±(99.9%) 3.542 ops/ms [Average]
  (min, avg, max) = (8.420, 8.636, 8.794), stdev = 0.194
  CI (99.9%): [5.095, 12.178] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.829 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.553 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.397 ±(99.9%) 0.003 ms/op
Iteration   1: 3.293 ±(99.9%) 0.008 ms/op
Iteration   2: 3.060 ±(99.9%) 0.007 ms/op
Iteration   3: 3.128 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.161 ±(99.9%) 2.185 ms/op [Average]
  (min, avg, max) = (3.060, 3.161, 3.293), stdev = 0.120
  CI (99.9%): [0.976, 5.345] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.378 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.405 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.111 ±(99.9%) 0.005 ms/op
Iteration   1: 2.989 ±(99.9%) 0.006 ms/op
Iteration   2: 3.087 ±(99.9%) 0.005 ms/op
Iteration   3: 3.123 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.066 ±(99.9%) 1.258 ms/op [Average]
  (min, avg, max) = (2.989, 3.066, 3.123), stdev = 0.069
  CI (99.9%): [1.808, 4.324] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.350 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.466 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.246 ±(99.9%) 0.003 ms/op
Iteration   1: 3.164 ±(99.9%) 0.002 ms/op
Iteration   2: 3.180 ±(99.9%) 0.004 ms/op
Iteration   3: 3.119 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.154 ±(99.9%) 0.577 ms/op [Average]
  (min, avg, max) = (3.119, 3.154, 3.180), stdev = 0.032
  CI (99.9%): [2.577, 3.732] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.487 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.037 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.863 ±(99.9%) 0.008 ms/op
Iteration   1: 3.672 ±(99.9%) 0.012 ms/op
Iteration   2: 3.893 ±(99.9%) 0.004 ms/op
Iteration   3: 3.787 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.784 ±(99.9%) 2.021 ms/op [Average]
  (min, avg, max) = (3.672, 3.784, 3.893), stdev = 0.111
  CI (99.9%): [1.762, 5.805] (assumes normal distribution)


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
# Warmup Iteration   1: 7.916 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.732 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.396 ±(99.9%) 0.011 ms/op
Iteration   1: 3.193 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.286 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  14.156 ms/op
                 createUser·p0.9999: 19.660 ms/op
                 createUser·p1.00:   20.382 ms/op

Iteration   2: 3.076 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.249 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.240 ms/op
                 createUser·p0.95:   3.334 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  11.982 ms/op
                 createUser·p0.9999: 22.800 ms/op
                 createUser·p1.00:   23.167 ms/op

Iteration   3: 3.257 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.280 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   6.709 ms/op
                 createUser·p0.999:  17.560 ms/op
                 createUser·p0.9999: 28.875 ms/op
                 createUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302243
  mean =      3.174 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27708 
    [ 2.500,  5.000) = 269484 
    [ 5.000,  7.500) = 3698 
    [ 7.500, 10.000) = 695 
    [10.000, 12.500) = 173 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 151 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.249 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     17.195 ms/op
     p(99.9900) =     27.689 ms/op
     p(99.9990) =     29.196 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


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
# Warmup Iteration   1: 7.282 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.268 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.007 ms/op
Iteration   1: 3.129 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.986 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  9.060 ms/op
                 existUser·p0.9999: 19.817 ms/op
                 existUser·p1.00:   21.627 ms/op

Iteration   2: 3.171 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.204 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   4.116 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  13.058 ms/op
                 existUser·p0.9999: 25.589 ms/op
                 existUser·p1.00:   27.951 ms/op

Iteration   3: 3.047 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.750 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.154 ms/op
                 existUser·p0.95:   3.334 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  12.191 ms/op
                 existUser·p0.9999: 19.940 ms/op
                 existUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308046
  mean =      3.115 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29834 
    [ 2.500,  5.000) = 272798 
    [ 5.000,  7.500) = 4578 
    [ 7.500, 10.000) = 441 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.416 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      5.366 ms/op
     p(99.9000) =     12.205 ms/op
     p(99.9900) =     22.774 ms/op
     p(99.9990) =     26.010 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


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
# Warmup Iteration   1: 7.015 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.283 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.409 ±(99.9%) 0.010 ms/op
Iteration   1: 3.176 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   6.078 ms/op
                 getUser·p0.999:  16.685 ms/op
                 getUser·p0.9999: 25.753 ms/op
                 getUser·p1.00:   25.952 ms/op

Iteration   2: 3.183 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.247 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   4.186 ms/op
                 getUser·p0.99:   5.415 ms/op
                 getUser·p0.999:  11.315 ms/op
                 getUser·p0.9999: 23.786 ms/op
                 getUser·p1.00:   24.773 ms/op

Iteration   3: 3.175 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.436 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   5.795 ms/op
                 getUser·p0.999:  12.780 ms/op
                 getUser·p0.9999: 18.151 ms/op
                 getUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 301944
  mean =      3.178 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17342 
    [ 2.500,  5.000) = 277597 
    [ 5.000,  7.500) = 5990 
    [ 7.500, 10.000) = 564 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     15.581 ms/op
     p(99.9900) =     23.770 ms/op
     p(99.9990) =     25.887 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


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
# Warmup Iteration   1: 9.338 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 4.120 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.799 ±(99.9%) 0.012 ms/op
Iteration   1: 3.727 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.475 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  14.928 ms/op
                 listUser·p0.9999: 20.100 ms/op
                 listUser·p1.00:   20.447 ms/op

Iteration   2: 3.762 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.046 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.343 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  15.516 ms/op
                 listUser·p0.9999: 19.606 ms/op
                 listUser·p1.00:   20.480 ms/op

Iteration   3: 3.700 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.075 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   6.537 ms/op
                 listUser·p0.999:  13.550 ms/op
                 listUser·p0.9999: 15.172 ms/op
                 listUser·p1.00:   15.909 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257348
  mean =      3.729 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 75 
    [ 2.500,  5.000) = 251353 
    [ 5.000,  7.500) = 4192 
    [ 7.500, 10.000) = 1001 
    [10.000, 12.500) = 242 
    [12.500, 15.000) = 276 
    [15.000, 17.500) = 148 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.475 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     14.576 ms/op
     p(99.9900) =     19.235 ms/op
     p(99.9990) =     20.391 ms/op
     p(99.9999) =     20.480 ms/op
    p(100.0000) =     20.480 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.923 ± 0.418  ops/ms
ClientPb.existUser                       thrpt       3  10.237 ± 6.684  ops/ms
ClientPb.getUser                         thrpt       3  10.106 ± 3.690  ops/ms
ClientPb.listUser                        thrpt       3   8.636 ± 3.542  ops/ms
ClientPb.createUser                       avgt       3   3.161 ± 2.185   ms/op
ClientPb.existUser                        avgt       3   3.066 ± 1.258   ms/op
ClientPb.getUser                          avgt       3   3.154 ± 0.577   ms/op
ClientPb.listUser                         avgt       3   3.784 ± 2.021   ms/op
ClientPb.createUser                     sample  302243   3.174 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.249           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.453           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.785           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.587           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.195           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.689           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.295           ms/op
ClientPb.existUser                      sample  308046   3.115 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.750           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.416           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.805           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.366           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.205           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.774           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.951           ms/op
ClientPb.getUser                        sample  301944   3.178 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.055           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.539           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.129           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.792           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.581           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.770           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.952           ms/op
ClientPb.listUser                       sample  257348   3.729 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.475           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.666           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.018           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.276           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.652           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.576           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.235           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.480           ms/op
