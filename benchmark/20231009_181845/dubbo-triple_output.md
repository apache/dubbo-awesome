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
# Warmup Iteration   1: 2.080 ops/ms
# Warmup Iteration   2: 5.470 ops/ms
# Warmup Iteration   3: 8.753 ops/ms
Iteration   1: 9.743 ops/ms
Iteration   2: 9.478 ops/ms
Iteration   3: 9.624 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.615 ±(99.9%) 2.423 ops/ms [Average]
  (min, avg, max) = (9.478, 9.615, 9.743), stdev = 0.133
  CI (99.9%): [7.191, 12.038] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.069 ops/ms
# Warmup Iteration   2: 8.849 ops/ms
# Warmup Iteration   3: 9.822 ops/ms
Iteration   1: 10.020 ops/ms
Iteration   2: 10.115 ops/ms
Iteration   3: 9.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.967 ±(99.9%) 3.285 ops/ms [Average]
  (min, avg, max) = (9.767, 9.967, 10.115), stdev = 0.180
  CI (99.9%): [6.682, 13.252] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.212 ops/ms
# Warmup Iteration   2: 8.794 ops/ms
# Warmup Iteration   3: 9.529 ops/ms
Iteration   1: 9.715 ops/ms
Iteration   2: 9.629 ops/ms
Iteration   3: 9.656 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.667 ±(99.9%) 0.806 ops/ms [Average]
  (min, avg, max) = (9.629, 9.667, 9.715), stdev = 0.044
  CI (99.9%): [8.861, 10.473] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.341 ops/ms
# Warmup Iteration   2: 7.540 ops/ms
# Warmup Iteration   3: 7.847 ops/ms
Iteration   1: 8.149 ops/ms
Iteration   2: 8.045 ops/ms
Iteration   3: 8.112 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.102 ±(99.9%) 0.966 ops/ms [Average]
  (min, avg, max) = (8.045, 8.102, 8.149), stdev = 0.053
  CI (99.9%): [7.136, 9.068] (assumes normal distribution)


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
# Warmup Iteration   1: 8.396 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.598 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.411 ±(99.9%) 0.004 ms/op
Iteration   1: 3.309 ±(99.9%) 0.006 ms/op
Iteration   2: 3.352 ±(99.9%) 0.003 ms/op
Iteration   3: 3.313 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.325 ±(99.9%) 0.431 ms/op [Average]
  (min, avg, max) = (3.309, 3.325, 3.352), stdev = 0.024
  CI (99.9%): [2.894, 3.755] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.811 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.389 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.262 ±(99.9%) 0.004 ms/op
Iteration   1: 3.177 ±(99.9%) 0.004 ms/op
Iteration   2: 3.151 ±(99.9%) 0.004 ms/op
Iteration   3: 3.160 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.163 ±(99.9%) 0.239 ms/op [Average]
  (min, avg, max) = (3.151, 3.163, 3.177), stdev = 0.013
  CI (99.9%): [2.923, 3.402] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.487 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.478 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.364 ±(99.9%) 0.003 ms/op
Iteration   1: 3.312 ±(99.9%) 0.005 ms/op
Iteration   2: 3.326 ±(99.9%) 0.004 ms/op
Iteration   3: 3.296 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.311 ±(99.9%) 0.280 ms/op [Average]
  (min, avg, max) = (3.296, 3.311, 3.326), stdev = 0.015
  CI (99.9%): [3.032, 3.591] (assumes normal distribution)


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
# Warmup Iteration   1: 8.038 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.136 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.962 ±(99.9%) 0.004 ms/op
Iteration   1: 3.889 ±(99.9%) 0.007 ms/op
Iteration   2: 3.932 ±(99.9%) 0.005 ms/op
Iteration   3: 3.794 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.872 ±(99.9%) 1.296 ms/op [Average]
  (min, avg, max) = (3.794, 3.872, 3.932), stdev = 0.071
  CI (99.9%): [2.576, 5.167] (assumes normal distribution)


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
# Warmup Iteration   1: 9.060 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.855 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.396 ±(99.9%) 0.010 ms/op
Iteration   1: 3.390 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.284 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   6.898 ms/op
                 createUser·p0.999:  19.453 ms/op
                 createUser·p0.9999: 34.350 ms/op
                 createUser·p1.00:   36.438 ms/op

Iteration   2: 3.233 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.896 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   6.083 ms/op
                 createUser·p0.999:  20.449 ms/op
                 createUser·p0.9999: 26.021 ms/op
                 createUser·p1.00:   28.475 ms/op

Iteration   3: 3.365 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.969 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   6.586 ms/op
                 createUser·p0.999:  17.203 ms/op
                 createUser·p0.9999: 26.968 ms/op
                 createUser·p1.00:   28.049 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 288335
  mean =      3.328 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13814 
    [ 2.500,  5.000) = 266950 
    [ 5.000,  7.500) = 6084 
    [ 7.500, 10.000) = 657 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 42 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     19.245 ms/op
     p(99.9900) =     33.292 ms/op
     p(99.9990) =     34.629 ms/op
     p(99.9999) =     36.438 ms/op
    p(100.0000) =     36.438 ms/op


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
# Warmup Iteration   1: 7.684 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.413 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.188 ±(99.9%) 0.008 ms/op
Iteration   1: 3.208 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.114 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.921 ms/op
                 existUser·p0.99:   6.611 ms/op
                 existUser·p0.999:  18.230 ms/op
                 existUser·p0.9999: 20.447 ms/op
                 existUser·p1.00:   21.004 ms/op

Iteration   2: 3.282 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.292 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   6.169 ms/op
                 existUser·p0.999:  11.824 ms/op
                 existUser·p0.9999: 23.265 ms/op
                 existUser·p1.00:   24.576 ms/op

Iteration   3: 3.232 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.029 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   6.291 ms/op
                 existUser·p0.999:  19.990 ms/op
                 existUser·p0.9999: 34.820 ms/op
                 existUser·p1.00:   43.450 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 296039
  mean =      3.240 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 288354 
    [ 5.000, 10.000) = 7132 
    [10.000, 15.000) = 232 
    [15.000, 20.000) = 118 
    [20.000, 25.000) = 171 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 23 
    [35.000, 40.000) = 4 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.029 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      6.382 ms/op
     p(99.9000) =     16.155 ms/op
     p(99.9900) =     30.467 ms/op
     p(99.9990) =     40.852 ms/op
     p(99.9999) =     43.450 ms/op
    p(100.0000) =     43.450 ms/op


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
# Warmup Iteration   1: 8.788 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.579 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.486 ±(99.9%) 0.011 ms/op
Iteration   1: 3.320 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.579 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   6.693 ms/op
                 getUser·p0.999:  19.071 ms/op
                 getUser·p0.9999: 20.873 ms/op
                 getUser·p1.00:   22.577 ms/op

Iteration   2: 3.223 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.991 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   6.250 ms/op
                 getUser·p0.999:  21.381 ms/op
                 getUser·p0.9999: 27.266 ms/op
                 getUser·p1.00:   27.754 ms/op

Iteration   3: 3.309 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.174 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   4.166 ms/op
                 getUser·p0.99:   6.321 ms/op
                 getUser·p0.999:  17.834 ms/op
                 getUser·p0.9999: 29.568 ms/op
                 getUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292098
  mean =      3.283 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9670 
    [ 2.500,  5.000) = 273080 
    [ 5.000,  7.500) = 8148 
    [ 7.500, 10.000) = 601 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.991 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      6.513 ms/op
     p(99.9000) =     19.137 ms/op
     p(99.9900) =     28.108 ms/op
     p(99.9990) =     30.257 ms/op
     p(99.9999) =     32.408 ms/op
    p(100.0000) =     32.408 ms/op


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
# Warmup Iteration   1: 10.373 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.186 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.967 ±(99.9%) 0.012 ms/op
Iteration   1: 3.961 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.352 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   8.266 ms/op
                 listUser·p0.999:  17.745 ms/op
                 listUser·p0.9999: 31.485 ms/op
                 listUser·p1.00:   32.801 ms/op

Iteration   2: 3.889 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.575 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.149 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   7.807 ms/op
                 listUser·p0.999:  14.500 ms/op
                 listUser·p0.9999: 23.724 ms/op
                 listUser·p1.00:   35.979 ms/op

Iteration   3: 3.912 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.659 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  13.500 ms/op
                 listUser·p0.9999: 16.804 ms/op
                 listUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 244820
  mean =      3.921 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 135 
    [ 2.500,  5.000) = 235040 
    [ 5.000,  7.500) = 6880 
    [ 7.500, 10.000) = 1922 
    [10.000, 12.500) = 276 
    [12.500, 15.000) = 354 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.352 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      7.774 ms/op
     p(99.9000) =     14.680 ms/op
     p(99.9900) =     23.757 ms/op
     p(99.9990) =     32.713 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.615 ± 2.423  ops/ms
ClientPb.existUser                       thrpt       3   9.967 ± 3.285  ops/ms
ClientPb.getUser                         thrpt       3   9.667 ± 0.806  ops/ms
ClientPb.listUser                        thrpt       3   8.102 ± 0.966  ops/ms
ClientPb.createUser                       avgt       3   3.325 ± 0.431   ms/op
ClientPb.existUser                        avgt       3   3.163 ± 0.239   ms/op
ClientPb.getUser                          avgt       3   3.311 ± 0.280   ms/op
ClientPb.listUser                         avgt       3   3.872 ± 1.296   ms/op
ClientPb.createUser                     sample  288335   3.328 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.896           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.695           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.076           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.578           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.245           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.292           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.438           ms/op
ClientPb.existUser                      sample  296039   3.240 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.029           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.174           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.568           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.998           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.382           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.155           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.467           ms/op
ClientPb.existUser:existUser·p1.00      sample          43.450           ms/op
ClientPb.getUser                        sample  292098   3.283 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.991           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.596           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.055           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.513           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.137           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.108           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.408           ms/op
ClientPb.listUser                       sample  244820   3.921 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.352           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.785           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.227           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.774           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.680           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.757           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.979           ms/op
