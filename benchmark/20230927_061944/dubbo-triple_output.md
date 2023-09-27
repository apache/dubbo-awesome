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
# Warmup Iteration   1: 2.632 ops/ms
# Warmup Iteration   2: 5.888 ops/ms
# Warmup Iteration   3: 8.791 ops/ms
Iteration   1: 9.629 ops/ms
Iteration   2: 9.377 ops/ms
Iteration   3: 9.965 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.657 ±(99.9%) 5.380 ops/ms [Average]
  (min, avg, max) = (9.377, 9.657, 9.965), stdev = 0.295
  CI (99.9%): [4.277, 15.037] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.415 ops/ms
# Warmup Iteration   2: 8.740 ops/ms
# Warmup Iteration   3: 9.869 ops/ms
Iteration   1: 10.266 ops/ms
Iteration   2: 10.074 ops/ms
Iteration   3: 9.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.105 ±(99.9%) 2.705 ops/ms [Average]
  (min, avg, max) = (9.974, 10.105, 10.266), stdev = 0.148
  CI (99.9%): [7.400, 12.810] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.719 ops/ms
# Warmup Iteration   2: 9.003 ops/ms
# Warmup Iteration   3: 9.661 ops/ms
Iteration   1: 9.702 ops/ms
Iteration   2: 9.977 ops/ms
Iteration   3: 9.926 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.869 ±(99.9%) 2.665 ops/ms [Average]
  (min, avg, max) = (9.702, 9.869, 9.977), stdev = 0.146
  CI (99.9%): [7.203, 12.534] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.488 ops/ms
# Warmup Iteration   2: 7.703 ops/ms
# Warmup Iteration   3: 8.054 ops/ms
Iteration   1: 8.287 ops/ms
Iteration   2: 8.247 ops/ms
Iteration   3: 8.322 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.285 ±(99.9%) 0.687 ops/ms [Average]
  (min, avg, max) = (8.247, 8.285, 8.322), stdev = 0.038
  CI (99.9%): [7.598, 8.972] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.212 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.564 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.438 ±(99.9%) 0.003 ms/op
Iteration   1: 3.284 ±(99.9%) 0.002 ms/op
Iteration   2: 3.247 ±(99.9%) 0.002 ms/op
Iteration   3: 3.292 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.274 ±(99.9%) 0.435 ms/op [Average]
  (min, avg, max) = (3.247, 3.274, 3.292), stdev = 0.024
  CI (99.9%): [2.839, 3.710] (assumes normal distribution)


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
# Warmup Iteration   1: 7.209 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.366 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.127 ±(99.9%) 0.002 ms/op
Iteration   1: 3.133 ±(99.9%) 0.002 ms/op
Iteration   2: 3.204 ±(99.9%) 0.003 ms/op
Iteration   3: 3.092 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.143 ±(99.9%) 1.033 ms/op [Average]
  (min, avg, max) = (3.092, 3.143, 3.204), stdev = 0.057
  CI (99.9%): [2.109, 4.176] (assumes normal distribution)


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
# Warmup Iteration   1: 7.780 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.374 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.266 ±(99.9%) 0.003 ms/op
Iteration   1: 3.288 ±(99.9%) 0.002 ms/op
Iteration   2: 3.215 ±(99.9%) 0.003 ms/op
Iteration   3: 3.213 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.239 ±(99.9%) 0.778 ms/op [Average]
  (min, avg, max) = (3.213, 3.239, 3.288), stdev = 0.043
  CI (99.9%): [2.461, 4.017] (assumes normal distribution)


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
# Warmup Iteration   1: 8.666 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.067 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.927 ±(99.9%) 0.004 ms/op
Iteration   1: 3.820 ±(99.9%) 0.004 ms/op
Iteration   2: 3.754 ±(99.9%) 0.004 ms/op
Iteration   3: 3.814 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.796 ±(99.9%) 0.662 ms/op [Average]
  (min, avg, max) = (3.754, 3.796, 3.820), stdev = 0.036
  CI (99.9%): [3.133, 4.458] (assumes normal distribution)


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
# Warmup Iteration   1: 7.435 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.716 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.316 ±(99.9%) 0.009 ms/op
Iteration   1: 3.246 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.468 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  11.392 ms/op
                 createUser·p0.9999: 20.320 ms/op
                 createUser·p1.00:   20.709 ms/op

Iteration   2: 3.235 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.051 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   6.291 ms/op
                 createUser·p0.999:  17.339 ms/op
                 createUser·p0.9999: 22.614 ms/op
                 createUser·p1.00:   23.626 ms/op

Iteration   3: 3.223 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.241 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   6.029 ms/op
                 createUser·p0.999:  15.171 ms/op
                 createUser·p0.9999: 23.209 ms/op
                 createUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296475
  mean =      3.235 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12349 
    [ 2.500,  5.000) = 278579 
    [ 5.000,  7.500) = 4478 
    [ 7.500, 10.000) = 528 
    [10.000, 12.500) = 173 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     15.688 ms/op
     p(99.9900) =     22.523 ms/op
     p(99.9990) =     23.764 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


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
# Warmup Iteration   1: 7.343 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.295 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.136 ±(99.9%) 0.008 ms/op
Iteration   1: 3.188 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.130 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   6.128 ms/op
                 existUser·p0.999:  11.971 ms/op
                 existUser·p0.9999: 20.709 ms/op
                 existUser·p1.00:   21.856 ms/op

Iteration   2: 3.093 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.837 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   4.833 ms/op
                 existUser·p0.999:  8.131 ms/op
                 existUser·p0.9999: 22.315 ms/op
                 existUser·p1.00:   23.101 ms/op

Iteration   3: 3.254 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.104 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   6.423 ms/op
                 existUser·p0.999:  15.244 ms/op
                 existUser·p0.9999: 21.299 ms/op
                 existUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302101
  mean =      3.177 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16650 
    [ 2.500,  5.000) = 279067 
    [ 5.000,  7.500) = 5382 
    [ 7.500, 10.000) = 356 
    [10.000, 12.500) = 276 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     15.088 ms/op
     p(99.9900) =     21.573 ms/op
     p(99.9990) =     22.936 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


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
# Warmup Iteration   1: 8.251 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.464 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.288 ±(99.9%) 0.008 ms/op
Iteration   1: 3.296 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.346 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   6.644 ms/op
                 getUser·p0.999:  18.045 ms/op
                 getUser·p0.9999: 20.129 ms/op
                 getUser·p1.00:   20.611 ms/op

Iteration   2: 3.283 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.114 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   5.538 ms/op
                 getUser·p0.999:  17.009 ms/op
                 getUser·p0.9999: 23.527 ms/op
                 getUser·p1.00:   24.084 ms/op

Iteration   3: 3.292 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   6.169 ms/op
                 getUser·p0.999:  14.447 ms/op
                 getUser·p0.9999: 22.081 ms/op
                 getUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 291723
  mean =      3.290 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12181 
    [ 2.500,  5.000) = 273096 
    [ 5.000,  7.500) = 5266 
    [ 7.500, 10.000) = 478 
    [10.000, 12.500) = 248 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      6.210 ms/op
     p(99.9000) =     14.533 ms/op
     p(99.9900) =     22.479 ms/op
     p(99.9990) =     23.803 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


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
# Warmup Iteration   1: 9.935 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.096 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.892 ±(99.9%) 0.012 ms/op
Iteration   1: 3.830 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.891 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.149 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  15.235 ms/op
                 listUser·p0.9999: 19.113 ms/op
                 listUser·p1.00:   19.628 ms/op

Iteration   2: 3.889 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.614 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   7.158 ms/op
                 listUser·p0.999:  14.658 ms/op
                 listUser·p0.9999: 16.448 ms/op
                 listUser·p1.00:   20.447 ms/op

Iteration   3: 3.839 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.872 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   6.529 ms/op
                 listUser·p0.999:  13.070 ms/op
                 listUser·p0.9999: 17.881 ms/op
                 listUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249146
  mean =      3.853 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 242686 
    [ 5.000,  7.500) = 5039 
    [ 7.500, 10.000) = 595 
    [10.000, 12.500) = 260 
    [12.500, 15.000) = 346 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     14.184 ms/op
     p(99.9900) =     17.957 ms/op
     p(99.9990) =     19.612 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.657 ± 5.380  ops/ms
ClientPb.existUser                       thrpt       3  10.105 ± 2.705  ops/ms
ClientPb.getUser                         thrpt       3   9.869 ± 2.665  ops/ms
ClientPb.listUser                        thrpt       3   8.285 ± 0.687  ops/ms
ClientPb.createUser                       avgt       3   3.274 ± 0.435   ms/op
ClientPb.existUser                        avgt       3   3.143 ± 1.033   ms/op
ClientPb.getUser                          avgt       3   3.239 ± 0.778   ms/op
ClientPb.listUser                         avgt       3   3.796 ± 0.662   ms/op
ClientPb.createUser                     sample  296475   3.235 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.051           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.609           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.923           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.688           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.523           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.117           ms/op
ClientPb.existUser                      sample  302101   3.177 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.837           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.424           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.808           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.088           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.573           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.101           ms/op
ClientPb.getUser                        sample  291723   3.290 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.073           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.641           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.210           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.533           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.479           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.084           ms/op
ClientPb.listUser                       sample  249146   3.853 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.891           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.740           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.182           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.726           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.184           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.957           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.447           ms/op
