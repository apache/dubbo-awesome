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
# Warmup Iteration   1: 2.514 ops/ms
# Warmup Iteration   2: 6.065 ops/ms
# Warmup Iteration   3: 9.041 ops/ms
Iteration   1: 9.541 ops/ms
Iteration   2: 9.794 ops/ms
Iteration   3: 9.886 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.741 ±(99.9%) 3.263 ops/ms [Average]
  (min, avg, max) = (9.541, 9.741, 9.886), stdev = 0.179
  CI (99.9%): [6.478, 13.003] (assumes normal distribution)


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
# Warmup Iteration   1: 3.526 ops/ms
# Warmup Iteration   2: 9.500 ops/ms
# Warmup Iteration   3: 9.662 ops/ms
Iteration   1: 9.988 ops/ms
Iteration   2: 10.128 ops/ms
Iteration   3: 10.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.085 ±(99.9%) 1.536 ops/ms [Average]
  (min, avg, max) = (9.988, 10.085, 10.139), stdev = 0.084
  CI (99.9%): [8.549, 11.621] (assumes normal distribution)


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
# Warmup Iteration   1: 3.458 ops/ms
# Warmup Iteration   2: 8.521 ops/ms
# Warmup Iteration   3: 9.073 ops/ms
Iteration   1: 9.623 ops/ms
Iteration   2: 10.031 ops/ms
Iteration   3: 9.913 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.856 ±(99.9%) 3.831 ops/ms [Average]
  (min, avg, max) = (9.623, 9.856, 10.031), stdev = 0.210
  CI (99.9%): [6.024, 13.687] (assumes normal distribution)


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
# Warmup Iteration   1: 3.197 ops/ms
# Warmup Iteration   2: 7.689 ops/ms
# Warmup Iteration   3: 8.111 ops/ms
Iteration   1: 8.332 ops/ms
Iteration   2: 8.453 ops/ms
Iteration   3: 8.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.405 ±(99.9%) 1.172 ops/ms [Average]
  (min, avg, max) = (8.332, 8.405, 8.453), stdev = 0.064
  CI (99.9%): [7.233, 9.576] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.720 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.636 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.455 ±(99.9%) 0.006 ms/op
Iteration   1: 3.369 ±(99.9%) 0.003 ms/op
Iteration   2: 3.229 ±(99.9%) 0.006 ms/op
Iteration   3: 3.323 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.307 ±(99.9%) 1.305 ms/op [Average]
  (min, avg, max) = (3.229, 3.307, 3.369), stdev = 0.072
  CI (99.9%): [2.002, 4.612] (assumes normal distribution)


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
# Warmup Iteration   1: 6.958 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.331 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.001 ms/op
Iteration   1: 2.991 ±(99.9%) 0.002 ms/op
Iteration   2: 3.071 ±(99.9%) 0.007 ms/op
Iteration   3: 2.993 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.018 ±(99.9%) 0.841 ms/op [Average]
  (min, avg, max) = (2.991, 3.018, 3.071), stdev = 0.046
  CI (99.9%): [2.177, 3.859] (assumes normal distribution)


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
# Warmup Iteration   1: 7.876 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.418 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.287 ±(99.9%) 0.003 ms/op
Iteration   1: 3.177 ±(99.9%) 0.006 ms/op
Iteration   2: 3.175 ±(99.9%) 0.003 ms/op
Iteration   3: 3.176 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.176 ±(99.9%) 0.024 ms/op [Average]
  (min, avg, max) = (3.175, 3.176, 3.177), stdev = 0.001
  CI (99.9%): [3.152, 3.200] (assumes normal distribution)


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
# Warmup Iteration   1: 8.628 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.144 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.820 ±(99.9%) 0.007 ms/op
Iteration   1: 3.694 ±(99.9%) 0.009 ms/op
Iteration   2: 3.690 ±(99.9%) 0.009 ms/op
Iteration   3: 3.732 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.705 ±(99.9%) 0.418 ms/op [Average]
  (min, avg, max) = (3.690, 3.705, 3.732), stdev = 0.023
  CI (99.9%): [3.287, 4.123] (assumes normal distribution)


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
# Warmup Iteration   1: 8.180 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.659 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.331 ±(99.9%) 0.010 ms/op
Iteration   1: 3.147 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.169 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  17.321 ms/op
                 createUser·p0.9999: 19.333 ms/op
                 createUser·p1.00:   20.087 ms/op

Iteration   2: 3.156 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.561 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.945 ms/op
                 createUser·p0.999:  9.961 ms/op
                 createUser·p0.9999: 21.393 ms/op
                 createUser·p1.00:   21.791 ms/op

Iteration   3: 3.179 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.608 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  13.156 ms/op
                 createUser·p0.9999: 19.528 ms/op
                 createUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303700
  mean =      3.161 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7802 
    [ 2.500,  5.000) = 291919 
    [ 5.000,  7.500) = 3183 
    [ 7.500, 10.000) = 361 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 174 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      5.292 ms/op
     p(99.9000) =     15.881 ms/op
     p(99.9900) =     20.468 ms/op
     p(99.9990) =     21.788 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


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
# Warmup Iteration   1: 7.901 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.347 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.006 ms/op
Iteration   1: 3.191 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.278 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  9.106 ms/op
                 existUser·p0.9999: 21.329 ms/op
                 existUser·p1.00:   21.791 ms/op

Iteration   2: 3.095 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.532 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.191 ms/op
                 existUser·p0.95:   4.040 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  17.727 ms/op
                 existUser·p0.9999: 24.117 ms/op
                 existUser·p1.00:   25.297 ms/op

Iteration   3: 2.999 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.061 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.129 ms/op
                 existUser·p0.95:   3.219 ms/op
                 existUser·p0.99:   5.235 ms/op
                 existUser·p0.999:  7.905 ms/op
                 existUser·p0.9999: 22.392 ms/op
                 existUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310137
  mean =      3.093 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29741 
    [ 2.500,  5.000) = 275496 
    [ 5.000,  7.500) = 4245 
    [ 7.500, 10.000) = 272 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      5.267 ms/op
     p(99.9000) =     15.268 ms/op
     p(99.9900) =     22.708 ms/op
     p(99.9990) =     24.409 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


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
# Warmup Iteration   1: 8.313 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.527 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.264 ±(99.9%) 0.009 ms/op
Iteration   1: 3.264 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.270 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  12.278 ms/op
                 getUser·p0.9999: 20.984 ms/op
                 getUser·p1.00:   22.118 ms/op

Iteration   2: 3.358 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.649 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   6.242 ms/op
                 getUser·p0.999:  18.588 ms/op
                 getUser·p0.9999: 22.166 ms/op
                 getUser·p1.00:   23.101 ms/op

Iteration   3: 3.127 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.710 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   5.489 ms/op
                 getUser·p0.999:  12.270 ms/op
                 getUser·p0.9999: 23.396 ms/op
                 getUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295460
  mean =      3.247 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21761 
    [ 2.500,  5.000) = 266912 
    [ 5.000,  7.500) = 5659 
    [ 7.500, 10.000) = 648 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 127 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.270 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     12.531 ms/op
     p(99.9900) =     22.804 ms/op
     p(99.9990) =     23.974 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


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
# Warmup Iteration   1: 8.939 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.089 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.812 ±(99.9%) 0.012 ms/op
Iteration   1: 3.718 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.311 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.162 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  15.974 ms/op
                 listUser·p0.9999: 20.132 ms/op
                 listUser·p1.00:   22.643 ms/op

Iteration   2: 3.764 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.134 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.092 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  13.533 ms/op
                 listUser·p0.9999: 20.120 ms/op
                 listUser·p1.00:   20.185 ms/op

Iteration   3: 3.814 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.097 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.186 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  13.631 ms/op
                 listUser·p0.9999: 17.662 ms/op
                 listUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254792
  mean =      3.765 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 80 
    [ 2.500,  5.000) = 247400 
    [ 5.000,  7.500) = 5509 
    [ 7.500, 10.000) = 1035 
    [10.000, 12.500) = 280 
    [12.500, 15.000) = 292 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.311 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     14.336 ms/op
     p(99.9900) =     19.580 ms/op
     p(99.9990) =     21.016 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.741 ± 3.263  ops/ms
ClientPb.existUser                       thrpt       3  10.085 ± 1.536  ops/ms
ClientPb.getUser                         thrpt       3   9.856 ± 3.831  ops/ms
ClientPb.listUser                        thrpt       3   8.405 ± 1.172  ops/ms
ClientPb.createUser                       avgt       3   3.307 ± 1.305   ms/op
ClientPb.existUser                        avgt       3   3.018 ± 0.841   ms/op
ClientPb.getUser                          avgt       3   3.176 ± 0.024   ms/op
ClientPb.listUser                         avgt       3   3.705 ± 0.418   ms/op
ClientPb.createUser                     sample  303700   3.161 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.169           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.559           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.292           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.881           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.468           ms/op
ClientPb.createUser:createUser·p1.00    sample          21.791           ms/op
ClientPb.existUser                      sample  310137   3.093 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.061           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.351           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.736           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.267           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.268           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.708           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.297           ms/op
ClientPb.getUser                        sample  295460   3.247 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.270           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.711           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.088           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.792           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.531           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.804           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.478           ms/op
ClientPb.listUser                       sample  254792   3.765 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.311           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.686           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.067           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.873           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.336           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.580           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.643           ms/op
