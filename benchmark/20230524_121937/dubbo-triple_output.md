# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.498 ops/ms
# Warmup Iteration   2: 6.098 ops/ms
# Warmup Iteration   3: 9.378 ops/ms
Iteration   1: 9.367 ops/ms
Iteration   2: 9.372 ops/ms
Iteration   3: 9.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.467 ±(99.9%) 3.080 ops/ms [Average]
  (min, avg, max) = (9.367, 9.467, 9.662), stdev = 0.169
  CI (99.9%): [6.387, 12.546] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.570 ops/ms
# Warmup Iteration   2: 8.971 ops/ms
# Warmup Iteration   3: 9.856 ops/ms
Iteration   1: 10.012 ops/ms
Iteration   2: 9.928 ops/ms
Iteration   3: 10.527 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.156 ±(99.9%) 5.914 ops/ms [Average]
  (min, avg, max) = (9.928, 10.156, 10.527), stdev = 0.324
  CI (99.9%): [4.242, 16.070] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.570 ops/ms
# Warmup Iteration   2: 8.874 ops/ms
# Warmup Iteration   3: 9.227 ops/ms
Iteration   1: 10.095 ops/ms
Iteration   2: 9.565 ops/ms
Iteration   3: 9.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.822 ±(99.9%) 4.841 ops/ms [Average]
  (min, avg, max) = (9.565, 9.822, 10.095), stdev = 0.265
  CI (99.9%): [4.981, 14.664] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.293 ops/ms
# Warmup Iteration   2: 7.675 ops/ms
# Warmup Iteration   3: 8.071 ops/ms
Iteration   1: 8.553 ops/ms
Iteration   2: 8.431 ops/ms
Iteration   3: 8.499 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.494 ±(99.9%) 1.112 ops/ms [Average]
  (min, avg, max) = (8.431, 8.494, 8.553), stdev = 0.061
  CI (99.9%): [7.382, 9.607] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.015 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.617 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.394 ±(99.9%) 0.007 ms/op
Iteration   1: 3.176 ±(99.9%) 0.004 ms/op
Iteration   2: 3.162 ±(99.9%) 0.008 ms/op
Iteration   3: 3.140 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.159 ±(99.9%) 0.333 ms/op [Average]
  (min, avg, max) = (3.140, 3.159, 3.176), stdev = 0.018
  CI (99.9%): [2.826, 3.492] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.712 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.295 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.004 ms/op
Iteration   1: 3.163 ±(99.9%) 0.003 ms/op
Iteration   2: 3.251 ±(99.9%) 0.002 ms/op
Iteration   3: 3.142 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.185 ±(99.9%) 1.054 ms/op [Average]
  (min, avg, max) = (3.142, 3.185, 3.251), stdev = 0.058
  CI (99.9%): [2.131, 4.240] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.965 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.672 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.270 ±(99.9%) 0.003 ms/op
Iteration   1: 3.200 ±(99.9%) 0.004 ms/op
Iteration   2: 3.110 ±(99.9%) 0.006 ms/op
Iteration   3: 3.101 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.137 ±(99.9%) 0.996 ms/op [Average]
  (min, avg, max) = (3.101, 3.137, 3.200), stdev = 0.055
  CI (99.9%): [2.141, 4.133] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.546 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.176 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.836 ±(99.9%) 0.004 ms/op
Iteration   1: 3.663 ±(99.9%) 0.012 ms/op
Iteration   2: 3.702 ±(99.9%) 0.009 ms/op
Iteration   3: 3.763 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.709 ±(99.9%) 0.919 ms/op [Average]
  (min, avg, max) = (3.663, 3.709, 3.763), stdev = 0.050
  CI (99.9%): [2.790, 4.629] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.926 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.767 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.370 ±(99.9%) 0.010 ms/op
Iteration   1: 3.143 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.622 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.371 ms/op
                 createUser·p0.95:   3.580 ms/op
                 createUser·p0.99:   5.300 ms/op
                 createUser·p0.999:  17.511 ms/op
                 createUser·p0.9999: 23.843 ms/op
                 createUser·p1.00:   28.639 ms/op

Iteration   2: 3.141 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.744 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.314 ms/op
                 createUser·p0.95:   3.576 ms/op
                 createUser·p0.99:   5.325 ms/op
                 createUser·p0.999:  12.435 ms/op
                 createUser·p0.9999: 21.189 ms/op
                 createUser·p1.00:   21.594 ms/op

Iteration   3: 3.254 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.550 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   5.804 ms/op
                 createUser·p0.999:  14.083 ms/op
                 createUser·p0.9999: 18.365 ms/op
                 createUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301981
  mean =      3.179 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18215 
    [ 2.500,  5.000) = 278371 
    [ 5.000,  7.500) = 4433 
    [ 7.500, 10.000) = 424 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 141 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     14.910 ms/op
     p(99.9900) =     22.309 ms/op
     p(99.9990) =     28.508 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.164 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.527 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.239 ±(99.9%) 0.008 ms/op
Iteration   1: 3.181 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.200 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.981 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  7.982 ms/op
                 existUser·p0.9999: 25.395 ms/op
                 existUser·p1.00:   25.985 ms/op

Iteration   2: 3.288 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.530 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   6.070 ms/op
                 existUser·p0.999:  7.895 ms/op
                 existUser·p0.9999: 21.481 ms/op
                 existUser·p1.00:   22.086 ms/op

Iteration   3: 3.221 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.466 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  13.875 ms/op
                 existUser·p0.9999: 22.643 ms/op
                 existUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 297111
  mean =      3.229 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28158 
    [ 2.500,  5.000) = 262198 
    [ 5.000,  7.500) = 5928 
    [ 7.500, 10.000) = 471 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.200 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     11.724 ms/op
     p(99.9900) =     24.717 ms/op
     p(99.9990) =     25.793 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.075 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.509 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.276 ±(99.9%) 0.009 ms/op
Iteration   1: 3.379 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.470 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   4.039 ms/op
                 getUser·p0.95:   4.604 ms/op
                 getUser·p0.99:   6.145 ms/op
                 getUser·p0.999:  18.994 ms/op
                 getUser·p0.9999: 25.052 ms/op
                 getUser·p1.00:   25.428 ms/op

Iteration   2: 3.176 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.348 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.568 ms/op
                 getUser·p0.99:   5.267 ms/op
                 getUser·p0.999:  11.354 ms/op
                 getUser·p0.9999: 23.394 ms/op
                 getUser·p1.00:   23.921 ms/op

Iteration   3: 3.192 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.446 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   5.546 ms/op
                 getUser·p0.999:  12.976 ms/op
                 getUser·p0.9999: 23.394 ms/op
                 getUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295698
  mean =      3.246 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9168 
    [ 2.500,  5.000) = 280010 
    [ 5.000,  7.500) = 5671 
    [ 7.500, 10.000) = 461 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.470 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     15.696 ms/op
     p(99.9900) =     24.539 ms/op
     p(99.9990) =     25.206 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.529 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.040 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.792 ±(99.9%) 0.012 ms/op
Iteration   1: 3.833 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  14.696 ms/op
                 listUser·p0.9999: 21.059 ms/op
                 listUser·p1.00:   22.282 ms/op

Iteration   2: 3.890 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.525 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  13.091 ms/op
                 listUser·p0.9999: 14.778 ms/op
                 listUser·p1.00:   14.909 ms/op

Iteration   3: 3.706 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.077 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   6.474 ms/op
                 listUser·p0.999:  13.795 ms/op
                 listUser·p0.9999: 15.483 ms/op
                 listUser·p1.00:   15.483 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251921
  mean =      3.808 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 75 
    [ 2.500,  5.000) = 243589 
    [ 5.000,  7.500) = 6456 
    [ 7.500, 10.000) = 1179 
    [10.000, 12.500) = 220 
    [12.500, 15.000) = 296 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.525 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     13.615 ms/op
     p(99.9900) =     20.408 ms/op
     p(99.9990) =     21.660 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.467 ± 3.080  ops/ms
ClientPb.existUser                       thrpt       3  10.156 ± 5.914  ops/ms
ClientPb.getUser                         thrpt       3   9.822 ± 4.841  ops/ms
ClientPb.listUser                        thrpt       3   8.494 ± 1.112  ops/ms
ClientPb.createUser                       avgt       3   3.159 ± 0.333   ms/op
ClientPb.existUser                        avgt       3   3.185 ± 1.054   ms/op
ClientPb.getUser                          avgt       3   3.137 ± 0.996   ms/op
ClientPb.listUser                         avgt       3   3.709 ± 0.919   ms/op
ClientPb.createUser                     sample  301981   3.179 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.744           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.453           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.472           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.910           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.309           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.639           ms/op
ClientPb.existUser                      sample  297111   3.229 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.200           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.183           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.580           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.043           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.661           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.724           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.717           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.985           ms/op
ClientPb.getUser                        sample  295698   3.246 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.470           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.658           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.030           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.718           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.696           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.539           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.428           ms/op
ClientPb.listUser                       sample  251921   3.808 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.525           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.723           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.149           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.939           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.615           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.408           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.282           ms/op
