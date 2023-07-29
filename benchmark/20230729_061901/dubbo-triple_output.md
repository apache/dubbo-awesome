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
# Warmup Iteration   1: 2.267 ops/ms
# Warmup Iteration   2: 6.125 ops/ms
# Warmup Iteration   3: 9.043 ops/ms
Iteration   1: 9.454 ops/ms
Iteration   2: 9.712 ops/ms
Iteration   3: 9.907 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.691 ±(99.9%) 4.152 ops/ms [Average]
  (min, avg, max) = (9.454, 9.691, 9.907), stdev = 0.228
  CI (99.9%): [5.539, 13.843] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.655 ops/ms
# Warmup Iteration   2: 9.401 ops/ms
# Warmup Iteration   3: 9.862 ops/ms
Iteration   1: 10.437 ops/ms
Iteration   2: 10.355 ops/ms
Iteration   3: 10.676 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.489 ±(99.9%) 3.047 ops/ms [Average]
  (min, avg, max) = (10.355, 10.489, 10.676), stdev = 0.167
  CI (99.9%): [7.443, 13.536] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.036 ops/ms
# Warmup Iteration   2: 8.335 ops/ms
# Warmup Iteration   3: 9.652 ops/ms
Iteration   1: 9.808 ops/ms
Iteration   2: 9.789 ops/ms
Iteration   3: 10.283 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.960 ±(99.9%) 5.106 ops/ms [Average]
  (min, avg, max) = (9.789, 9.960, 10.283), stdev = 0.280
  CI (99.9%): [4.854, 15.066] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 2.982 ops/ms
# Warmup Iteration   2: 7.343 ops/ms
# Warmup Iteration   3: 8.263 ops/ms
Iteration   1: 8.342 ops/ms
Iteration   2: 8.626 ops/ms
Iteration   3: 8.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.471 ±(99.9%) 2.623 ops/ms [Average]
  (min, avg, max) = (8.342, 8.471, 8.626), stdev = 0.144
  CI (99.9%): [5.848, 11.093] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 7.751 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.475 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.387 ±(99.9%) 0.004 ms/op
Iteration   1: 3.196 ±(99.9%) 0.008 ms/op
Iteration   2: 3.202 ±(99.9%) 0.010 ms/op
Iteration   3: 3.220 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.206 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (3.196, 3.206, 3.220), stdev = 0.012
  CI (99.9%): [2.984, 3.429] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.193 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.401 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.159 ±(99.9%) 0.005 ms/op
Iteration   1: 3.120 ±(99.9%) 0.009 ms/op
Iteration   2: 3.137 ±(99.9%) 0.008 ms/op
Iteration   3: 3.001 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.086 ±(99.9%) 1.346 ms/op [Average]
  (min, avg, max) = (3.001, 3.086, 3.137), stdev = 0.074
  CI (99.9%): [1.740, 4.432] (assumes normal distribution)


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
# Warmup Iteration   1: 8.635 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.433 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.274 ±(99.9%) 0.004 ms/op
Iteration   1: 3.287 ±(99.9%) 0.005 ms/op
Iteration   2: 3.151 ±(99.9%) 0.008 ms/op
Iteration   3: 3.221 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.220 ±(99.9%) 1.237 ms/op [Average]
  (min, avg, max) = (3.151, 3.220, 3.287), stdev = 0.068
  CI (99.9%): [1.983, 4.457] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 9.762 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.206 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.782 ±(99.9%) 0.007 ms/op
Iteration   1: 3.711 ±(99.9%) 0.011 ms/op
Iteration   2: 3.733 ±(99.9%) 0.004 ms/op
Iteration   3: 3.843 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.763 ±(99.9%) 1.294 ms/op [Average]
  (min, avg, max) = (3.711, 3.763, 3.843), stdev = 0.071
  CI (99.9%): [2.469, 5.056] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.616 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.930 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.215 ±(99.9%) 0.009 ms/op
Iteration   1: 3.200 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.458 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  11.829 ms/op
                 createUser·p0.9999: 22.151 ms/op
                 createUser·p1.00:   23.593 ms/op

Iteration   2: 3.212 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.313 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.363 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  20.257 ms/op
                 createUser·p0.9999: 24.184 ms/op
                 createUser·p1.00:   24.478 ms/op

Iteration   3: 3.207 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.243 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  16.712 ms/op
                 createUser·p0.9999: 25.133 ms/op
                 createUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299414
  mean =      3.206 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21280 
    [ 2.500,  5.000) = 272836 
    [ 5.000,  7.500) = 4459 
    [ 7.500, 10.000) = 379 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.243 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =     18.730 ms/op
     p(99.9900) =     24.478 ms/op
     p(99.9990) =     26.182 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.960 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.610 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.145 ±(99.9%) 0.007 ms/op
Iteration   1: 3.108 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.536 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.256 ms/op
                 existUser·p0.95:   3.424 ms/op
                 existUser·p0.99:   5.145 ms/op
                 existUser·p0.999:  7.973 ms/op
                 existUser·p0.9999: 23.247 ms/op
                 existUser·p1.00:   23.691 ms/op

Iteration   2: 3.097 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.235 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.461 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  13.810 ms/op
                 existUser·p0.9999: 23.265 ms/op
                 existUser·p1.00:   25.100 ms/op

Iteration   3: 3.138 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.985 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   5.448 ms/op
                 existUser·p0.999:  12.698 ms/op
                 existUser·p0.9999: 24.891 ms/op
                 existUser·p1.00:   25.526 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307902
  mean =      3.114 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28807 
    [ 2.500,  5.000) = 274773 
    [ 5.000,  7.500) = 3590 
    [ 7.500, 10.000) = 261 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 161 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.985 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.252 ms/op
     p(95.0000) =      3.490 ms/op
     p(99.0000) =      5.317 ms/op
     p(99.9000) =     13.158 ms/op
     p(99.9900) =     23.639 ms/op
     p(99.9990) =     25.196 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


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
# Warmup Iteration   1: 7.742 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.373 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.382 ±(99.9%) 0.011 ms/op
Iteration   1: 3.413 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.591 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   6.423 ms/op
                 getUser·p0.999:  17.559 ms/op
                 getUser·p0.9999: 23.826 ms/op
                 getUser·p1.00:   24.248 ms/op

Iteration   2: 3.203 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.538 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   5.610 ms/op
                 getUser·p0.999:  12.307 ms/op
                 getUser·p0.9999: 24.577 ms/op
                 getUser·p1.00:   25.100 ms/op

Iteration   3: 3.298 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.856 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  16.647 ms/op
                 getUser·p0.9999: 23.767 ms/op
                 getUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 290558
  mean =      3.303 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15038 
    [ 2.500,  5.000) = 266130 
    [ 5.000,  7.500) = 8203 
    [ 7.500, 10.000) = 697 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 116 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.087 ms/op
     p(99.9000) =     15.234 ms/op
     p(99.9900) =     24.019 ms/op
     p(99.9990) =     25.002 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


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
# Warmup Iteration   1: 8.413 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 4.162 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.853 ±(99.9%) 0.012 ms/op
Iteration   1: 3.784 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.667 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   7.384 ms/op
                 listUser·p0.999:  14.680 ms/op
                 listUser·p0.9999: 20.435 ms/op
                 listUser·p1.00:   20.972 ms/op

Iteration   2: 3.704 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.677 ms/op
                 listUser·p0.50:   3.564 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  13.206 ms/op
                 listUser·p0.9999: 14.790 ms/op
                 listUser·p1.00:   15.024 ms/op

Iteration   3: 3.777 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   6.874 ms/op
                 listUser·p0.999:  12.878 ms/op
                 listUser·p0.9999: 15.221 ms/op
                 listUser·p1.00:   15.254 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255491
  mean =      3.755 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 76 
    [ 2.500,  5.000) = 248063 
    [ 5.000,  7.500) = 5372 
    [ 7.500, 10.000) = 1266 
    [10.000, 12.500) = 237 
    [12.500, 15.000) = 399 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.667 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     13.738 ms/op
     p(99.9900) =     18.776 ms/op
     p(99.9990) =     20.873 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.691 ± 4.152  ops/ms
ClientPb.existUser                       thrpt       3  10.489 ± 3.047  ops/ms
ClientPb.getUser                         thrpt       3   9.960 ± 5.106  ops/ms
ClientPb.listUser                        thrpt       3   8.471 ± 2.623  ops/ms
ClientPb.createUser                       avgt       3   3.206 ± 0.223   ms/op
ClientPb.existUser                        avgt       3   3.086 ± 1.346   ms/op
ClientPb.getUser                          avgt       3   3.220 ± 1.237   ms/op
ClientPb.listUser                         avgt       3   3.763 ± 1.294   ms/op
ClientPb.createUser                     sample  299414   3.206 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.243           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.469           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.772           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.497           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.730           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.478           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.182           ms/op
ClientPb.existUser                      sample  307902   3.114 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.985           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.252           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.490           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.317           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.158           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.639           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.526           ms/op
ClientPb.getUser                        sample  290558   3.303 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.856           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.727           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.366           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.087           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.234           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.019           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.100           ms/op
ClientPb.listUser                       sample  255491   3.755 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.667           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.637           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.051           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.980           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.738           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.776           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.972           ms/op
