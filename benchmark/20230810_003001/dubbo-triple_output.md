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
# Warmup Iteration   1: 2.124 ops/ms
# Warmup Iteration   2: 5.681 ops/ms
# Warmup Iteration   3: 9.081 ops/ms
Iteration   1: 9.668 ops/ms
Iteration   2: 10.048 ops/ms
Iteration   3: 9.773 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.830 ±(99.9%) 3.575 ops/ms [Average]
  (min, avg, max) = (9.668, 9.830, 10.048), stdev = 0.196
  CI (99.9%): [6.254, 13.405] (assumes normal distribution)


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
# Warmup Iteration   1: 3.064 ops/ms
# Warmup Iteration   2: 9.102 ops/ms
# Warmup Iteration   3: 9.464 ops/ms
Iteration   1: 9.752 ops/ms
Iteration   2: 9.810 ops/ms
Iteration   3: 10.103 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.888 ±(99.9%) 3.437 ops/ms [Average]
  (min, avg, max) = (9.752, 9.888, 10.103), stdev = 0.188
  CI (99.9%): [6.452, 13.325] (assumes normal distribution)


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
# Warmup Iteration   1: 3.372 ops/ms
# Warmup Iteration   2: 8.810 ops/ms
# Warmup Iteration   3: 9.430 ops/ms
Iteration   1: 9.707 ops/ms
Iteration   2: 9.600 ops/ms
Iteration   3: 9.908 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.738 ±(99.9%) 2.851 ops/ms [Average]
  (min, avg, max) = (9.600, 9.738, 9.908), stdev = 0.156
  CI (99.9%): [6.887, 12.590] (assumes normal distribution)


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
# Warmup Iteration   1: 3.137 ops/ms
# Warmup Iteration   2: 7.560 ops/ms
# Warmup Iteration   3: 8.172 ops/ms
Iteration   1: 8.361 ops/ms
Iteration   2: 8.329 ops/ms
Iteration   3: 8.361 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.350 ±(99.9%) 0.340 ops/ms [Average]
  (min, avg, max) = (8.329, 8.350, 8.361), stdev = 0.019
  CI (99.9%): [8.010, 8.691] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.819 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.854 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.458 ±(99.9%) 0.002 ms/op
Iteration   1: 3.249 ±(99.9%) 0.002 ms/op
Iteration   2: 3.358 ±(99.9%) 0.003 ms/op
Iteration   3: 3.374 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.327 ±(99.9%) 1.242 ms/op [Average]
  (min, avg, max) = (3.249, 3.327, 3.374), stdev = 0.068
  CI (99.9%): [2.085, 4.569] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.016 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.455 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.374 ±(99.9%) 0.004 ms/op
Iteration   1: 3.128 ±(99.9%) 0.004 ms/op
Iteration   2: 3.183 ±(99.9%) 0.007 ms/op
Iteration   3: 3.179 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.164 ±(99.9%) 0.557 ms/op [Average]
  (min, avg, max) = (3.128, 3.164, 3.183), stdev = 0.031
  CI (99.9%): [2.607, 3.721] (assumes normal distribution)


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
# Warmup Iteration   1: 8.903 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.518 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.291 ±(99.9%) 0.002 ms/op
Iteration   1: 3.283 ±(99.9%) 0.002 ms/op
Iteration   2: 3.236 ±(99.9%) 0.004 ms/op
Iteration   3: 3.245 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.255 ±(99.9%) 0.458 ms/op [Average]
  (min, avg, max) = (3.236, 3.255, 3.283), stdev = 0.025
  CI (99.9%): [2.797, 3.712] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.768 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.404 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.953 ±(99.9%) 0.006 ms/op
Iteration   1: 3.835 ±(99.9%) 0.008 ms/op
Iteration   2: 3.812 ±(99.9%) 0.007 ms/op
Iteration   3: 3.804 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.817 ±(99.9%) 0.291 ms/op [Average]
  (min, avg, max) = (3.804, 3.817, 3.835), stdev = 0.016
  CI (99.9%): [3.526, 4.108] (assumes normal distribution)


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
# Warmup Iteration   1: 7.930 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.913 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.223 ±(99.9%) 0.008 ms/op
Iteration   1: 3.314 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.989 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   6.545 ms/op
                 createUser·p0.999:  14.991 ms/op
                 createUser·p0.9999: 27.167 ms/op
                 createUser·p1.00:   27.918 ms/op

Iteration   2: 3.274 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.945 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   6.578 ms/op
                 createUser·p0.999:  11.543 ms/op
                 createUser·p0.9999: 28.515 ms/op
                 createUser·p1.00:   28.901 ms/op

Iteration   3: 3.280 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.182 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  16.074 ms/op
                 createUser·p0.9999: 21.930 ms/op
                 createUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 291708
  mean =      3.289 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13678 
    [ 2.500,  5.000) = 269118 
    [ 5.000,  7.500) = 7310 
    [ 7.500, 10.000) = 1187 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      0.945 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =     15.914 ms/op
     p(99.9900) =     27.159 ms/op
     p(99.9990) =     28.809 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


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
# Warmup Iteration   1: 7.194 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.365 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.292 ±(99.9%) 0.008 ms/op
Iteration   1: 3.116 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.364 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  10.720 ms/op
                 existUser·p0.9999: 23.042 ms/op
                 existUser·p1.00:   24.052 ms/op

Iteration   2: 3.210 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   4.112 ms/op
                 existUser·p0.99:   7.004 ms/op
                 existUser·p0.999:  19.956 ms/op
                 existUser·p0.9999: 24.478 ms/op
                 existUser·p1.00:   25.854 ms/op

Iteration   3: 3.228 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.973 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   4.186 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  12.255 ms/op
                 existUser·p0.9999: 26.611 ms/op
                 existUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301385
  mean =      3.184 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14313 
    [ 2.500,  5.000) = 278183 
    [ 5.000,  7.500) = 7279 
    [ 7.500, 10.000) = 1057 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 58 

  Percentiles, ms/op:
      p(0.0000) =      0.973 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      6.431 ms/op
     p(99.9000) =     18.829 ms/op
     p(99.9900) =     25.751 ms/op
     p(99.9990) =     27.983 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


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
# Warmup Iteration   1: 7.465 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.620 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.358 ±(99.9%) 0.011 ms/op
Iteration   1: 3.396 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.378 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.977 ms/op
                 getUser·p0.95:   5.333 ms/op
                 getUser·p0.99:   6.914 ms/op
                 getUser·p0.999:  20.048 ms/op
                 getUser·p0.9999: 22.531 ms/op
                 getUser·p1.00:   23.134 ms/op

Iteration   2: 3.291 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.243 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   4.133 ms/op
                 getUser·p0.99:   6.177 ms/op
                 getUser·p0.999:  10.895 ms/op
                 getUser·p0.9999: 22.914 ms/op
                 getUser·p1.00:   23.757 ms/op

Iteration   3: 3.354 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.393 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   5.833 ms/op
                 getUser·p0.999:  16.564 ms/op
                 getUser·p0.9999: 22.494 ms/op
                 getUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 286801
  mean =      3.347 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14029 
    [ 2.500,  5.000) = 262333 
    [ 5.000,  7.500) = 8757 
    [ 7.500, 10.000) = 1191 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 174 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.393 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.439 ms/op
     p(99.9000) =     16.590 ms/op
     p(99.9900) =     22.807 ms/op
     p(99.9990) =     23.438 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


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
# Warmup Iteration   1: 9.679 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 4.226 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.996 ±(99.9%) 0.012 ms/op
Iteration   1: 3.870 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.628 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   8.159 ms/op
                 listUser·p0.999:  15.354 ms/op
                 listUser·p0.9999: 24.830 ms/op
                 listUser·p1.00:   25.723 ms/op

Iteration   2: 3.911 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.578 ms/op
                 listUser·p0.999:  14.352 ms/op
                 listUser·p0.9999: 26.051 ms/op
                 listUser·p1.00:   26.116 ms/op

Iteration   3: 3.970 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.875 ms/op
                 listUser·p0.99:   7.971 ms/op
                 listUser·p0.999:  17.433 ms/op
                 listUser·p0.9999: 19.268 ms/op
                 listUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 245122
  mean =      3.917 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56 
    [ 2.500,  5.000) = 235624 
    [ 5.000,  7.500) = 6586 
    [ 7.500, 10.000) = 1935 
    [10.000, 12.500) = 359 
    [12.500, 15.000) = 300 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.628 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      7.854 ms/op
     p(99.9000) =     15.542 ms/op
     p(99.9900) =     24.821 ms/op
     p(99.9990) =     26.083 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.830 ± 3.575  ops/ms
ClientPb.existUser                       thrpt       3   9.888 ± 3.437  ops/ms
ClientPb.getUser                         thrpt       3   9.738 ± 2.851  ops/ms
ClientPb.listUser                        thrpt       3   8.350 ± 0.340  ops/ms
ClientPb.createUser                       avgt       3   3.327 ± 1.242   ms/op
ClientPb.existUser                        avgt       3   3.164 ± 0.557   ms/op
ClientPb.getUser                          avgt       3   3.255 ± 0.458   ms/op
ClientPb.listUser                         avgt       3   3.817 ± 0.291   ms/op
ClientPb.createUser                     sample  291708   3.289 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.945           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.699           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.227           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.365           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.914           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.159           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.901           ms/op
ClientPb.existUser                      sample  301385   3.184 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.973           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.465           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.059           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.431           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.829           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.751           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.443           ms/op
ClientPb.getUser                        sample  286801   3.347 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.393           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.215           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.850           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.415           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.439           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.590           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.807           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.757           ms/op
ClientPb.listUser                       sample  245122   3.917 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.628           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.772           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.653           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.854           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.542           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.821           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.116           ms/op
