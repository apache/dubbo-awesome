# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.573 ops/ms
# Warmup Iteration   2: 6.546 ops/ms
# Warmup Iteration   3: 9.329 ops/ms
Iteration   1: 9.805 ops/ms
Iteration   2: 9.597 ops/ms
Iteration   3: 9.991 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.798 ±(99.9%) 3.590 ops/ms [Average]
  (min, avg, max) = (9.597, 9.798, 9.991), stdev = 0.197
  CI (99.9%): [6.207, 13.388] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.662 ops/ms
# Warmup Iteration   2: 9.121 ops/ms
# Warmup Iteration   3: 10.050 ops/ms
Iteration   1: 10.019 ops/ms
Iteration   2: 10.241 ops/ms
Iteration   3: 10.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.238 ±(99.9%) 3.963 ops/ms [Average]
  (min, avg, max) = (10.019, 10.238, 10.453), stdev = 0.217
  CI (99.9%): [6.275, 14.200] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.891 ops/ms
# Warmup Iteration   2: 9.455 ops/ms
# Warmup Iteration   3: 9.775 ops/ms
Iteration   1: 9.609 ops/ms
Iteration   2: 10.046 ops/ms
Iteration   3: 9.949 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.868 ±(99.9%) 4.190 ops/ms [Average]
  (min, avg, max) = (9.609, 9.868, 10.046), stdev = 0.230
  CI (99.9%): [5.678, 14.058] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.966 ops/ms
# Warmup Iteration   2: 7.310 ops/ms
# Warmup Iteration   3: 8.348 ops/ms
Iteration   1: 8.530 ops/ms
Iteration   2: 8.577 ops/ms
Iteration   3: 8.459 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.522 ±(99.9%) 1.082 ops/ms [Average]
  (min, avg, max) = (8.459, 8.522, 8.577), stdev = 0.059
  CI (99.9%): [7.440, 9.603] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.671 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.639 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.342 ±(99.9%) 0.002 ms/op
Iteration   1: 3.228 ±(99.9%) 0.003 ms/op
Iteration   2: 3.113 ±(99.9%) 0.008 ms/op
Iteration   3: 3.120 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.154 ±(99.9%) 1.179 ms/op [Average]
  (min, avg, max) = (3.113, 3.154, 3.228), stdev = 0.065
  CI (99.9%): [1.975, 4.333] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.532 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.435 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.001 ms/op
Iteration   1: 3.140 ±(99.9%) 0.003 ms/op
Iteration   2: 2.995 ±(99.9%) 0.005 ms/op
Iteration   3: 3.223 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.120 ±(99.9%) 2.104 ms/op [Average]
  (min, avg, max) = (2.995, 3.120, 3.223), stdev = 0.115
  CI (99.9%): [1.015, 5.224] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.868 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.536 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.152 ±(99.9%) 0.005 ms/op
Iteration   1: 3.192 ±(99.9%) 0.002 ms/op
Iteration   2: 3.134 ±(99.9%) 0.003 ms/op
Iteration   3: 3.239 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.188 ±(99.9%) 0.953 ms/op [Average]
  (min, avg, max) = (3.134, 3.188, 3.239), stdev = 0.052
  CI (99.9%): [2.235, 4.141] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.185 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.134 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.856 ±(99.9%) 0.006 ms/op
Iteration   1: 3.665 ±(99.9%) 0.012 ms/op
Iteration   2: 3.721 ±(99.9%) 0.008 ms/op
Iteration   3: 3.721 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.702 ±(99.9%) 0.590 ms/op [Average]
  (min, avg, max) = (3.665, 3.702, 3.721), stdev = 0.032
  CI (99.9%): [3.112, 4.292] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.011 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.675 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.253 ±(99.9%) 0.009 ms/op
Iteration   1: 3.131 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.157 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   5.497 ms/op
                 createUser·p0.999:  18.842 ms/op
                 createUser·p0.9999: 21.004 ms/op
                 createUser·p1.00:   21.791 ms/op

Iteration   2: 3.139 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.405 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   5.235 ms/op
                 createUser·p0.999:  10.882 ms/op
                 createUser·p0.9999: 21.326 ms/op
                 createUser·p1.00:   22.807 ms/op

Iteration   3: 3.146 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.640 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.379 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  16.521 ms/op
                 createUser·p0.9999: 22.048 ms/op
                 createUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 305569
  mean =      3.139 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17008 
    [ 2.500,  5.000) = 283988 
    [ 5.000,  7.500) = 3651 
    [ 7.500, 10.000) = 388 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 201 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =     17.362 ms/op
     p(99.9900) =     21.234 ms/op
     p(99.9990) =     23.036 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.511 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.338 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.232 ±(99.9%) 0.008 ms/op
Iteration   1: 3.209 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.577 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   5.614 ms/op
                 existUser·p0.999:  12.146 ms/op
                 existUser·p0.9999: 20.087 ms/op
                 existUser·p1.00:   20.578 ms/op

Iteration   2: 3.169 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.556 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   5.161 ms/op
                 existUser·p0.999:  12.337 ms/op
                 existUser·p0.9999: 22.312 ms/op
                 existUser·p1.00:   23.462 ms/op

Iteration   3: 3.074 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.984 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   5.403 ms/op
                 existUser·p0.999:  10.926 ms/op
                 existUser·p0.9999: 23.724 ms/op
                 existUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304714
  mean =      3.149 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21997 
    [ 2.500,  5.000) = 277671 
    [ 5.000,  7.500) = 4464 
    [ 7.500, 10.000) = 162 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 127 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.984 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =     11.977 ms/op
     p(99.9900) =     22.841 ms/op
     p(99.9990) =     23.985 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.169 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.529 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.270 ±(99.9%) 0.009 ms/op
Iteration   1: 3.317 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.973 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   4.317 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  17.269 ms/op
                 getUser·p0.9999: 19.968 ms/op
                 getUser·p1.00:   20.939 ms/op

Iteration   2: 3.426 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.877 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   5.906 ms/op
                 getUser·p0.99:   7.193 ms/op
                 getUser·p0.999:  19.454 ms/op
                 getUser·p0.9999: 25.341 ms/op
                 getUser·p1.00:   27.853 ms/op

Iteration   3: 3.419 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.096 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   5.407 ms/op
                 getUser·p0.99:   7.045 ms/op
                 getUser·p0.999:  16.122 ms/op
                 getUser·p0.9999: 23.067 ms/op
                 getUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 283108
  mean =      3.387 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18222 
    [ 2.500,  5.000) = 248535 
    [ 5.000,  7.500) = 14492 
    [ 7.500, 10.000) = 1336 
    [10.000, 12.500) = 187 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.877 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      5.251 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     17.101 ms/op
     p(99.9900) =     24.631 ms/op
     p(99.9990) =     26.353 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.220 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.296 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.853 ±(99.9%) 0.011 ms/op
Iteration   1: 3.681 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.276 ms/op
                 listUser·p0.50:   3.543 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.194 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  15.385 ms/op
                 listUser·p0.9999: 19.923 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   2: 3.841 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.159 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  13.206 ms/op
                 listUser·p0.9999: 14.582 ms/op
                 listUser·p1.00:   15.974 ms/op

Iteration   3: 3.758 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.195 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  12.582 ms/op
                 listUser·p0.9999: 17.513 ms/op
                 listUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255337
  mean =      3.759 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 67 
    [ 2.500,  5.000) = 247515 
    [ 5.000,  7.500) = 6149 
    [ 7.500, 10.000) = 858 
    [10.000, 12.500) = 287 
    [12.500, 15.000) = 325 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.276 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     13.648 ms/op
     p(99.9900) =     18.726 ms/op
     p(99.9990) =     20.232 ms/op
     p(99.9999) =     20.283 ms/op
    p(100.0000) =     20.283 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.798 ± 3.590  ops/ms
ClientPb.existUser                       thrpt       3  10.238 ± 3.963  ops/ms
ClientPb.getUser                         thrpt       3   9.868 ± 4.190  ops/ms
ClientPb.listUser                        thrpt       3   8.522 ± 1.082  ops/ms
ClientPb.createUser                       avgt       3   3.154 ± 1.179   ms/op
ClientPb.existUser                        avgt       3   3.120 ± 2.104   ms/op
ClientPb.getUser                          avgt       3   3.188 ± 0.953   ms/op
ClientPb.listUser                         avgt       3   3.702 ± 0.590   ms/op
ClientPb.createUser                     sample  305569   3.139 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.157           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.420           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.727           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.423           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.362           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.234           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.069           ms/op
ClientPb.existUser                      sample  304714   3.149 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.984           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.391           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.407           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.977           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.841           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.478           ms/op
ClientPb.getUser                        sample  283108   3.387 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.877           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.026           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.251           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.971           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.101           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.631           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.853           ms/op
ClientPb.listUser                       sample  255337   3.759 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.276           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.629           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.149           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.791           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.648           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.726           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.283           ms/op
