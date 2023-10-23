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
# Warmup Iteration   1: 2.398 ops/ms
# Warmup Iteration   2: 5.515 ops/ms
# Warmup Iteration   3: 9.218 ops/ms
Iteration   1: 9.537 ops/ms
Iteration   2: 9.955 ops/ms
Iteration   3: 9.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.761 ±(99.9%) 3.841 ops/ms [Average]
  (min, avg, max) = (9.537, 9.761, 9.955), stdev = 0.211
  CI (99.9%): [5.920, 13.602] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.298 ops/ms
# Warmup Iteration   2: 9.156 ops/ms
# Warmup Iteration   3: 10.069 ops/ms
Iteration   1: 9.949 ops/ms
Iteration   2: 9.968 ops/ms
Iteration   3: 10.229 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.049 ±(99.9%) 2.856 ops/ms [Average]
  (min, avg, max) = (9.949, 10.049, 10.229), stdev = 0.157
  CI (99.9%): [7.193, 12.905] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.487 ops/ms
# Warmup Iteration   2: 9.133 ops/ms
# Warmup Iteration   3: 9.560 ops/ms
Iteration   1: 9.718 ops/ms
Iteration   2: 9.626 ops/ms
Iteration   3: 9.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.642 ±(99.9%) 1.269 ops/ms [Average]
  (min, avg, max) = (9.582, 9.642, 9.718), stdev = 0.070
  CI (99.9%): [8.373, 10.911] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.980 ops/ms
# Warmup Iteration   2: 7.817 ops/ms
# Warmup Iteration   3: 8.237 ops/ms
Iteration   1: 8.230 ops/ms
Iteration   2: 8.465 ops/ms
Iteration   3: 8.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.348 ±(99.9%) 2.143 ops/ms [Average]
  (min, avg, max) = (8.230, 8.348, 8.465), stdev = 0.117
  CI (99.9%): [6.205, 10.490] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.774 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.531 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.465 ±(99.9%) 0.006 ms/op
Iteration   1: 3.206 ±(99.9%) 0.003 ms/op
Iteration   2: 3.293 ±(99.9%) 0.002 ms/op
Iteration   3: 3.246 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.248 ±(99.9%) 0.790 ms/op [Average]
  (min, avg, max) = (3.206, 3.248, 3.293), stdev = 0.043
  CI (99.9%): [2.458, 4.039] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.704 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.374 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.229 ±(99.9%) 0.004 ms/op
Iteration   1: 3.245 ±(99.9%) 0.002 ms/op
Iteration   2: 3.181 ±(99.9%) 0.002 ms/op
Iteration   3: 3.157 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.194 ±(99.9%) 0.826 ms/op [Average]
  (min, avg, max) = (3.157, 3.194, 3.245), stdev = 0.045
  CI (99.9%): [2.368, 4.021] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.578 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.538 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.356 ±(99.9%) 0.002 ms/op
Iteration   1: 3.247 ±(99.9%) 0.004 ms/op
Iteration   2: 3.220 ±(99.9%) 0.003 ms/op
Iteration   3: 3.311 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.259 ±(99.9%) 0.853 ms/op [Average]
  (min, avg, max) = (3.220, 3.259, 3.311), stdev = 0.047
  CI (99.9%): [2.407, 4.112] (assumes normal distribution)


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
# Warmup Iteration   1: 9.520 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.918 ±(99.9%) 0.003 ms/op
Iteration   1: 3.910 ±(99.9%) 0.003 ms/op
Iteration   2: 3.847 ±(99.9%) 0.005 ms/op
Iteration   3: 3.945 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.901 ±(99.9%) 0.901 ms/op [Average]
  (min, avg, max) = (3.847, 3.901, 3.945), stdev = 0.049
  CI (99.9%): [2.999, 4.802] (assumes normal distribution)


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
# Warmup Iteration   1: 9.085 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.826 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.263 ±(99.9%) 0.008 ms/op
Iteration   1: 3.327 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.190 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   6.709 ms/op
                 createUser·p0.999:  17.291 ms/op
                 createUser·p0.9999: 20.624 ms/op
                 createUser·p1.00:   21.561 ms/op

Iteration   2: 3.266 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.026 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  13.282 ms/op
                 createUser·p0.9999: 22.839 ms/op
                 createUser·p1.00:   23.593 ms/op

Iteration   3: 3.376 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.020 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.170 ms/op
                 createUser·p0.99:   6.291 ms/op
                 createUser·p0.999:  16.444 ms/op
                 createUser·p0.9999: 41.746 ms/op
                 createUser·p1.00:   42.598 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 288673
  mean =      3.322 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 282071 
    [ 5.000, 10.000) = 6114 
    [10.000, 15.000) = 166 
    [15.000, 20.000) = 155 
    [20.000, 25.000) = 135 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 13 
    [40.000, 45.000) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.020 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     16.444 ms/op
     p(99.9900) =     38.076 ms/op
     p(99.9990) =     42.475 ms/op
     p(99.9999) =     42.598 ms/op
    p(100.0000) =     42.598 ms/op


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
# Warmup Iteration   1: 8.176 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.550 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.246 ±(99.9%) 0.008 ms/op
Iteration   1: 3.214 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.251 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   5.906 ms/op
                 existUser·p0.999:  8.081 ms/op
                 existUser·p0.9999: 21.103 ms/op
                 existUser·p1.00:   21.889 ms/op

Iteration   2: 3.281 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.178 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  14.972 ms/op
                 existUser·p0.9999: 22.258 ms/op
                 existUser·p1.00:   22.839 ms/op

Iteration   3: 3.325 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.352 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   4.145 ms/op
                 existUser·p0.99:   7.324 ms/op
                 existUser·p0.999:  17.756 ms/op
                 existUser·p0.9999: 23.036 ms/op
                 existUser·p1.00:   24.773 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293286
  mean =      3.272 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10484 
    [ 2.500,  5.000) = 276272 
    [ 5.000,  7.500) = 5203 
    [ 7.500, 10.000) = 713 
    [10.000, 12.500) = 304 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 176 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.352 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      6.455 ms/op
     p(99.9000) =     12.861 ms/op
     p(99.9900) =     22.304 ms/op
     p(99.9990) =     23.302 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


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
# Warmup Iteration   1: 8.169 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.586 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.472 ±(99.9%) 0.012 ms/op
Iteration   1: 3.270 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.235 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   5.620 ms/op
                 getUser·p0.999:  14.153 ms/op
                 getUser·p0.9999: 23.961 ms/op
                 getUser·p1.00:   24.838 ms/op

Iteration   2: 3.309 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.274 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.817 ms/op
                 getUser·p0.999:  16.098 ms/op
                 getUser·p0.9999: 22.686 ms/op
                 getUser·p1.00:   23.036 ms/op

Iteration   3: 3.350 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.198 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   6.123 ms/op
                 getUser·p0.999:  14.257 ms/op
                 getUser·p0.9999: 21.379 ms/op
                 getUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 289983
  mean =      3.310 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6195 
    [ 2.500,  5.000) = 279043 
    [ 5.000,  7.500) = 3820 
    [ 7.500, 10.000) = 459 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 168 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.198 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     14.028 ms/op
     p(99.9900) =     22.938 ms/op
     p(99.9990) =     24.681 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


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
# Warmup Iteration   1: 9.421 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.208 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.974 ±(99.9%) 0.012 ms/op
Iteration   1: 3.914 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.915 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.282 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  15.214 ms/op
                 listUser·p0.9999: 23.541 ms/op
                 listUser·p1.00:   25.068 ms/op

Iteration   2: 3.855 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   6.686 ms/op
                 listUser·p0.999:  15.383 ms/op
                 listUser·p0.9999: 17.859 ms/op
                 listUser·p1.00:   21.463 ms/op

Iteration   3: 3.838 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.137 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  13.659 ms/op
                 listUser·p0.9999: 18.493 ms/op
                 listUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248073
  mean =      3.869 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 241201 
    [ 5.000,  7.500) = 5464 
    [ 7.500, 10.000) = 611 
    [10.000, 12.500) = 243 
    [12.500, 15.000) = 295 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.775 ms/op
     p(99.9000) =     14.778 ms/op
     p(99.9900) =     21.037 ms/op
     p(99.9990) =     24.956 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.761 ± 3.841  ops/ms
ClientPb.existUser                       thrpt       3  10.049 ± 2.856  ops/ms
ClientPb.getUser                         thrpt       3   9.642 ± 1.269  ops/ms
ClientPb.listUser                        thrpt       3   8.348 ± 2.143  ops/ms
ClientPb.createUser                       avgt       3   3.248 ± 0.790   ms/op
ClientPb.existUser                        avgt       3   3.194 ± 0.826   ms/op
ClientPb.getUser                          avgt       3   3.259 ± 0.853   ms/op
ClientPb.listUser                         avgt       3   3.901 ± 0.901   ms/op
ClientPb.createUser                     sample  288673   3.322 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.020           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.224           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.727           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.039           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.078           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.444           ms/op
ClientPb.createUser:createUser·p0.9999  sample          38.076           ms/op
ClientPb.createUser:createUser·p1.00    sample          42.598           ms/op
ClientPb.existUser                      sample  293286   3.272 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.352           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.166           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.617           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.990           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.455           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.861           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.304           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.773           ms/op
ClientPb.getUser                        sample  289983   3.310 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.198           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.224           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.658           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.800           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.028           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.938           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.838           ms/op
ClientPb.listUser                       sample  248073   3.869 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.915           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.752           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.211           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.775           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.778           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.037           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.068           ms/op
