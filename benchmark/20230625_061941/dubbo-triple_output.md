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
# Warmup Iteration   1: 2.518 ops/ms
# Warmup Iteration   2: 5.907 ops/ms
# Warmup Iteration   3: 8.922 ops/ms
Iteration   1: 9.324 ops/ms
Iteration   2: 9.717 ops/ms
Iteration   3: 9.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.580 ±(99.9%) 4.050 ops/ms [Average]
  (min, avg, max) = (9.324, 9.580, 9.717), stdev = 0.222
  CI (99.9%): [5.530, 13.631] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.509 ops/ms
# Warmup Iteration   2: 9.039 ops/ms
# Warmup Iteration   3: 10.479 ops/ms
Iteration   1: 10.498 ops/ms
Iteration   2: 10.640 ops/ms
Iteration   3: 10.808 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.648 ±(99.9%) 2.831 ops/ms [Average]
  (min, avg, max) = (10.498, 10.648, 10.808), stdev = 0.155
  CI (99.9%): [7.817, 13.480] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.568 ops/ms
# Warmup Iteration   2: 9.188 ops/ms
# Warmup Iteration   3: 9.449 ops/ms
Iteration   1: 9.827 ops/ms
Iteration   2: 10.159 ops/ms
Iteration   3: 10.046 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.011 ±(99.9%) 3.076 ops/ms [Average]
  (min, avg, max) = (9.827, 10.011, 10.159), stdev = 0.169
  CI (99.9%): [6.935, 13.087] (assumes normal distribution)


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
# Warmup Iteration   1: 3.406 ops/ms
# Warmup Iteration   2: 7.767 ops/ms
# Warmup Iteration   3: 8.368 ops/ms
Iteration   1: 8.213 ops/ms
Iteration   2: 8.421 ops/ms
Iteration   3: 8.347 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.327 ±(99.9%) 1.915 ops/ms [Average]
  (min, avg, max) = (8.213, 8.327, 8.421), stdev = 0.105
  CI (99.9%): [6.412, 10.242] (assumes normal distribution)


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
# Warmup Iteration   1: 7.365 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.591 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.383 ±(99.9%) 0.005 ms/op
Iteration   1: 3.238 ±(99.9%) 0.007 ms/op
Iteration   2: 3.173 ±(99.9%) 0.004 ms/op
Iteration   3: 3.136 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.182 ±(99.9%) 0.949 ms/op [Average]
  (min, avg, max) = (3.136, 3.182, 3.238), stdev = 0.052
  CI (99.9%): [2.233, 4.131] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.774 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.304 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.155 ±(99.9%) 0.003 ms/op
Iteration   1: 3.029 ±(99.9%) 0.008 ms/op
Iteration   2: 3.262 ±(99.9%) 0.003 ms/op
Iteration   3: 3.001 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.097 ±(99.9%) 2.616 ms/op [Average]
  (min, avg, max) = (3.001, 3.097, 3.262), stdev = 0.143
  CI (99.9%): [0.481, 5.713] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.347 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.449 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.379 ±(99.9%) 0.002 ms/op
Iteration   1: 3.170 ±(99.9%) 0.006 ms/op
Iteration   2: 3.175 ±(99.9%) 0.004 ms/op
Iteration   3: 3.080 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.142 ±(99.9%) 0.971 ms/op [Average]
  (min, avg, max) = (3.080, 3.142, 3.175), stdev = 0.053
  CI (99.9%): [2.171, 4.113] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.652 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.245 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.905 ±(99.9%) 0.006 ms/op
Iteration   1: 3.638 ±(99.9%) 0.011 ms/op
Iteration   2: 3.791 ±(99.9%) 0.005 ms/op
Iteration   3: 3.731 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.720 ±(99.9%) 1.407 ms/op [Average]
  (min, avg, max) = (3.638, 3.720, 3.791), stdev = 0.077
  CI (99.9%): [2.313, 5.127] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.809 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.657 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.244 ±(99.9%) 0.009 ms/op
Iteration   1: 3.135 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.912 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.334 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  11.878 ms/op
                 createUser·p0.9999: 19.458 ms/op
                 createUser·p1.00:   19.857 ms/op

Iteration   2: 3.152 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.485 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   5.063 ms/op
                 createUser·p0.999:  19.608 ms/op
                 createUser·p0.9999: 22.151 ms/op
                 createUser·p1.00:   23.134 ms/op

Iteration   3: 3.188 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.855 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  12.807 ms/op
                 createUser·p0.9999: 20.578 ms/op
                 createUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303912
  mean =      3.158 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30262 
    [ 2.500,  5.000) = 268592 
    [ 5.000,  7.500) = 4217 
    [ 7.500, 10.000) = 375 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     16.024 ms/op
     p(99.9900) =     21.758 ms/op
     p(99.9990) =     22.695 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


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
# Warmup Iteration   1: 8.813 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.482 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.007 ms/op
Iteration   1: 3.026 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.542 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.154 ms/op
                 existUser·p0.95:   3.334 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  13.124 ms/op
                 existUser·p0.9999: 21.150 ms/op
                 existUser·p1.00:   22.053 ms/op

Iteration   2: 3.186 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.573 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  13.413 ms/op
                 existUser·p0.9999: 21.365 ms/op
                 existUser·p1.00:   21.692 ms/op

Iteration   3: 3.175 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.608 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   5.478 ms/op
                 existUser·p0.999:  14.385 ms/op
                 existUser·p0.9999: 20.370 ms/op
                 existUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307113
  mean =      3.127 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32143 
    [ 2.500,  5.000) = 269568 
    [ 5.000,  7.500) = 4616 
    [ 7.500, 10.000) = 294 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 122 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.542 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.355 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      5.300 ms/op
     p(99.9000) =     13.189 ms/op
     p(99.9900) =     21.168 ms/op
     p(99.9990) =     21.884 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


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
# Warmup Iteration   1: 7.180 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.338 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.434 ±(99.9%) 0.011 ms/op
Iteration   1: 3.197 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.493 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   5.833 ms/op
                 getUser·p0.999:  13.205 ms/op
                 getUser·p0.9999: 21.430 ms/op
                 getUser·p1.00:   23.200 ms/op

Iteration   2: 3.154 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.116 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   5.505 ms/op
                 getUser·p0.999:  11.218 ms/op
                 getUser·p0.9999: 26.603 ms/op
                 getUser·p1.00:   28.049 ms/op

Iteration   3: 3.173 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.781 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   5.622 ms/op
                 getUser·p0.999:  11.305 ms/op
                 getUser·p0.9999: 24.999 ms/op
                 getUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 302111
  mean =      3.175 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15544 
    [ 2.500,  5.000) = 280680 
    [ 5.000,  7.500) = 4977 
    [ 7.500, 10.000) = 435 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =     12.550 ms/op
     p(99.9900) =     25.938 ms/op
     p(99.9990) =     27.787 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


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
# Warmup Iteration   1: 9.094 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.044 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.789 ±(99.9%) 0.011 ms/op
Iteration   1: 3.905 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.303 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.867 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  16.597 ms/op
                 listUser·p0.9999: 24.190 ms/op
                 listUser·p1.00:   24.609 ms/op

Iteration   2: 3.864 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.310 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  13.435 ms/op
                 listUser·p0.9999: 15.134 ms/op
                 listUser·p1.00:   15.254 ms/op

Iteration   3: 3.703 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.862 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.170 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  13.511 ms/op
                 listUser·p0.9999: 14.533 ms/op
                 listUser·p1.00:   14.533 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251177
  mean =      3.822 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 75 
    [ 2.500,  5.000) = 242116 
    [ 5.000,  7.500) = 7195 
    [ 7.500, 10.000) = 1064 
    [10.000, 12.500) = 230 
    [12.500, 15.000) = 367 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.303 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     14.123 ms/op
     p(99.9900) =     19.759 ms/op
     p(99.9990) =     24.526 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.580 ± 4.050  ops/ms
ClientPb.existUser                       thrpt       3  10.648 ± 2.831  ops/ms
ClientPb.getUser                         thrpt       3  10.011 ± 3.076  ops/ms
ClientPb.listUser                        thrpt       3   8.327 ± 1.915  ops/ms
ClientPb.createUser                       avgt       3   3.182 ± 0.949   ms/op
ClientPb.existUser                        avgt       3   3.097 ± 2.616   ms/op
ClientPb.getUser                          avgt       3   3.142 ± 0.971   ms/op
ClientPb.listUser                         avgt       3   3.720 ± 1.407   ms/op
ClientPb.createUser                     sample  303912   3.158 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.855           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.441           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.817           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.448           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.024           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.758           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.134           ms/op
ClientPb.existUser                      sample  307113   3.127 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.542           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.355           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.809           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.300           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.189           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.168           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.053           ms/op
ClientPb.getUser                        sample  302111   3.175 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.781           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.486           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.652           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.550           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.938           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.049           ms/op
ClientPb.listUser                       sample  251177   3.822 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.303           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.707           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.141           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.881           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.123           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.759           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.609           ms/op
