# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.485 ops/ms
# Warmup Iteration   2: 6.788 ops/ms
# Warmup Iteration   3: 9.550 ops/ms
Iteration   1: 9.997 ops/ms
Iteration   2: 9.789 ops/ms
Iteration   3: 9.998 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.928 ±(99.9%) 2.198 ops/ms [Average]
  (min, avg, max) = (9.789, 9.928, 9.998), stdev = 0.120
  CI (99.9%): [7.730, 12.126] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.937 ops/ms
# Warmup Iteration   2: 9.828 ops/ms
# Warmup Iteration   3: 10.224 ops/ms
Iteration   1: 10.319 ops/ms
Iteration   2: 10.353 ops/ms
Iteration   3: 10.165 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.279 ±(99.9%) 1.829 ops/ms [Average]
  (min, avg, max) = (10.165, 10.279, 10.353), stdev = 0.100
  CI (99.9%): [8.450, 12.108] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.521 ops/ms
# Warmup Iteration   2: 9.632 ops/ms
# Warmup Iteration   3: 9.901 ops/ms
Iteration   1: 9.722 ops/ms
Iteration   2: 9.931 ops/ms
Iteration   3: 10.054 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.902 ±(99.9%) 3.063 ops/ms [Average]
  (min, avg, max) = (9.722, 9.902, 10.054), stdev = 0.168
  CI (99.9%): [6.839, 12.966] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.722 ops/ms
# Warmup Iteration   2: 7.444 ops/ms
# Warmup Iteration   3: 8.342 ops/ms
Iteration   1: 8.318 ops/ms
Iteration   2: 8.534 ops/ms
Iteration   3: 8.451 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.435 ±(99.9%) 1.987 ops/ms [Average]
  (min, avg, max) = (8.318, 8.435, 8.534), stdev = 0.109
  CI (99.9%): [6.448, 10.422] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.952 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.465 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.411 ±(99.9%) 0.003 ms/op
Iteration   1: 3.271 ±(99.9%) 0.004 ms/op
Iteration   2: 3.264 ±(99.9%) 0.002 ms/op
Iteration   3: 3.284 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.273 ±(99.9%) 0.188 ms/op [Average]
  (min, avg, max) = (3.264, 3.273, 3.284), stdev = 0.010
  CI (99.9%): [3.085, 3.462] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.060 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.442 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.142 ±(99.9%) 0.002 ms/op
Iteration   1: 3.059 ±(99.9%) 0.004 ms/op
Iteration   2: 3.100 ±(99.9%) 0.003 ms/op
Iteration   3: 3.077 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.079 ±(99.9%) 0.368 ms/op [Average]
  (min, avg, max) = (3.059, 3.079, 3.100), stdev = 0.020
  CI (99.9%): [2.710, 3.447] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.033 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.431 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.323 ±(99.9%) 0.002 ms/op
Iteration   1: 3.224 ±(99.9%) 0.003 ms/op
Iteration   2: 3.157 ±(99.9%) 0.002 ms/op
Iteration   3: 3.136 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.172 ±(99.9%) 0.843 ms/op [Average]
  (min, avg, max) = (3.136, 3.172, 3.224), stdev = 0.046
  CI (99.9%): [2.330, 4.015] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.068 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.023 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.868 ±(99.9%) 0.005 ms/op
Iteration   1: 3.768 ±(99.9%) 0.003 ms/op
Iteration   2: 3.722 ±(99.9%) 0.003 ms/op
Iteration   3: 3.727 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.739 ±(99.9%) 0.460 ms/op [Average]
  (min, avg, max) = (3.722, 3.739, 3.768), stdev = 0.025
  CI (99.9%): [3.279, 4.199] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.595 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.620 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.297 ±(99.9%) 0.009 ms/op
Iteration   1: 3.277 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.380 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  10.245 ms/op
                 createUser·p0.9999: 18.521 ms/op
                 createUser·p1.00:   19.300 ms/op

Iteration   2: 3.201 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.505 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  13.216 ms/op
                 createUser·p0.9999: 20.776 ms/op
                 createUser·p1.00:   22.151 ms/op

Iteration   3: 3.262 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   5.915 ms/op
                 createUser·p0.999:  16.363 ms/op
                 createUser·p0.9999: 22.381 ms/op
                 createUser·p1.00:   23.790 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295703
  mean =      3.246 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13327 
    [ 2.500,  5.000) = 276626 
    [ 5.000,  7.500) = 4473 
    [ 7.500, 10.000) = 593 
    [10.000, 12.500) = 217 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 133 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     16.028 ms/op
     p(99.9900) =     21.927 ms/op
     p(99.9990) =     22.550 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.751 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 3.363 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.233 ±(99.9%) 0.007 ms/op
Iteration   1: 3.209 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.188 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  12.435 ms/op
                 existUser·p0.9999: 18.390 ms/op
                 existUser·p1.00:   18.940 ms/op

Iteration   2: 3.182 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.694 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   6.119 ms/op
                 existUser·p0.999:  15.061 ms/op
                 existUser·p0.9999: 21.035 ms/op
                 existUser·p1.00:   22.151 ms/op

Iteration   3: 3.107 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.296 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  14.287 ms/op
                 existUser·p0.9999: 19.305 ms/op
                 existUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303029
  mean =      3.165 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18510 
    [ 2.500,  5.000) = 278098 
    [ 5.000,  7.500) = 5315 
    [ 7.500, 10.000) = 445 
    [10.000, 12.500) = 258 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 148 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =     14.350 ms/op
     p(99.9900) =     20.175 ms/op
     p(99.9990) =     22.117 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.159 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.376 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.285 ±(99.9%) 0.009 ms/op
Iteration   1: 3.280 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.180 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   5.931 ms/op
                 getUser·p0.999:  17.482 ms/op
                 getUser·p0.9999: 19.767 ms/op
                 getUser·p1.00:   20.873 ms/op

Iteration   2: 3.287 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.307 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   6.341 ms/op
                 getUser·p0.999:  19.137 ms/op
                 getUser·p0.9999: 22.675 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   3: 3.210 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.098 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   5.546 ms/op
                 getUser·p0.999:  9.001 ms/op
                 getUser·p0.9999: 21.005 ms/op
                 getUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294501
  mean =      3.259 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10242 
    [ 2.500,  5.000) = 278169 
    [ 5.000,  7.500) = 5103 
    [ 7.500, 10.000) = 399 
    [10.000, 12.500) = 219 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.098 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.874 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     14.164 ms/op
     p(99.9900) =     21.809 ms/op
     p(99.9990) =     23.005 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.898 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.998 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.878 ±(99.9%) 0.010 ms/op
Iteration   1: 3.842 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.636 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.166 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  12.567 ms/op
                 listUser·p0.9999: 20.054 ms/op
                 listUser·p1.00:   21.168 ms/op

Iteration   2: 3.870 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.821 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  12.588 ms/op
                 listUser·p0.9999: 15.122 ms/op
                 listUser·p1.00:   16.450 ms/op

Iteration   3: 3.836 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.094 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  13.320 ms/op
                 listUser·p0.9999: 15.941 ms/op
                 listUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249309
  mean =      3.849 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 242319 
    [ 5.000,  7.500) = 5166 
    [ 7.500, 10.000) = 999 
    [10.000, 12.500) = 413 
    [12.500, 15.000) = 261 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.186 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     13.206 ms/op
     p(99.9900) =     18.726 ms/op
     p(99.9990) =     20.529 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.928 ± 2.198  ops/ms
ClientPb.existUser                       thrpt       3  10.279 ± 1.829  ops/ms
ClientPb.getUser                         thrpt       3   9.902 ± 3.063  ops/ms
ClientPb.listUser                        thrpt       3   8.435 ± 1.987  ops/ms
ClientPb.createUser                       avgt       3   3.273 ± 0.188   ms/op
ClientPb.existUser                        avgt       3   3.079 ± 0.368   ms/op
ClientPb.getUser                          avgt       3   3.172 ± 0.843   ms/op
ClientPb.listUser                         avgt       3   3.739 ± 0.460   ms/op
ClientPb.createUser                     sample  295703   3.246 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.053           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.637           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.936           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.702           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.028           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.927           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.790           ms/op
ClientPb.existUser                      sample  303029   3.165 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.694           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.461           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.980           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.350           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.175           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.151           ms/op
ClientPb.getUser                        sample  294501   3.259 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.098           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.604           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.874           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.874           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.164           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.809           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.167           ms/op
ClientPb.listUser                       sample  249309   3.849 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.094           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.764           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.186           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.881           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.206           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.726           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.168           ms/op
