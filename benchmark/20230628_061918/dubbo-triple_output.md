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
# Warmup Iteration   1: 2.344 ops/ms
# Warmup Iteration   2: 6.127 ops/ms
# Warmup Iteration   3: 9.159 ops/ms
Iteration   1: 9.730 ops/ms
Iteration   2: 10.012 ops/ms
Iteration   3: 9.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.798 ±(99.9%) 3.470 ops/ms [Average]
  (min, avg, max) = (9.650, 9.798, 10.012), stdev = 0.190
  CI (99.9%): [6.327, 13.268] (assumes normal distribution)


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
# Warmup Iteration   1: 3.709 ops/ms
# Warmup Iteration   2: 9.245 ops/ms
# Warmup Iteration   3: 10.380 ops/ms
Iteration   1: 10.017 ops/ms
Iteration   2: 10.252 ops/ms
Iteration   3: 10.504 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.258 ±(99.9%) 4.443 ops/ms [Average]
  (min, avg, max) = (10.017, 10.258, 10.504), stdev = 0.244
  CI (99.9%): [5.814, 14.701] (assumes normal distribution)


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
# Warmup Iteration   1: 3.160 ops/ms
# Warmup Iteration   2: 8.524 ops/ms
# Warmup Iteration   3: 9.872 ops/ms
Iteration   1: 9.636 ops/ms
Iteration   2: 10.021 ops/ms
Iteration   3: 9.933 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.863 ±(99.9%) 3.685 ops/ms [Average]
  (min, avg, max) = (9.636, 9.863, 10.021), stdev = 0.202
  CI (99.9%): [6.178, 13.548] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.375 ops/ms
# Warmup Iteration   2: 7.417 ops/ms
# Warmup Iteration   3: 8.669 ops/ms
Iteration   1: 8.239 ops/ms
Iteration   2: 8.719 ops/ms
Iteration   3: 8.686 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.548 ±(99.9%) 4.899 ops/ms [Average]
  (min, avg, max) = (8.239, 8.548, 8.719), stdev = 0.269
  CI (99.9%): [3.649, 13.447] (assumes normal distribution)


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
# Warmup Iteration   1: 8.527 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.544 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.454 ±(99.9%) 0.004 ms/op
Iteration   1: 3.159 ±(99.9%) 0.004 ms/op
Iteration   2: 3.200 ±(99.9%) 0.005 ms/op
Iteration   3: 3.107 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.155 ±(99.9%) 0.850 ms/op [Average]
  (min, avg, max) = (3.107, 3.155, 3.200), stdev = 0.047
  CI (99.9%): [2.305, 4.005] (assumes normal distribution)


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
# Warmup Iteration   1: 7.524 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.231 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.202 ±(99.9%) 0.007 ms/op
Iteration   1: 3.127 ±(99.9%) 0.004 ms/op
Iteration   2: 3.106 ±(99.9%) 0.003 ms/op
Iteration   3: 3.059 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.097 ±(99.9%) 0.633 ms/op [Average]
  (min, avg, max) = (3.059, 3.097, 3.127), stdev = 0.035
  CI (99.9%): [2.465, 3.730] (assumes normal distribution)


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
# Warmup Iteration   1: 9.068 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.601 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.430 ±(99.9%) 0.004 ms/op
Iteration   1: 3.350 ±(99.9%) 0.007 ms/op
Iteration   2: 3.202 ±(99.9%) 0.005 ms/op
Iteration   3: 3.295 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.282 ±(99.9%) 1.365 ms/op [Average]
  (min, avg, max) = (3.202, 3.282, 3.350), stdev = 0.075
  CI (99.9%): [1.918, 4.647] (assumes normal distribution)


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
# Warmup Iteration   1: 10.324 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.130 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.872 ±(99.9%) 0.005 ms/op
Iteration   1: 3.785 ±(99.9%) 0.003 ms/op
Iteration   2: 3.820 ±(99.9%) 0.004 ms/op
Iteration   3: 3.751 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.785 ±(99.9%) 0.622 ms/op [Average]
  (min, avg, max) = (3.751, 3.785, 3.820), stdev = 0.034
  CI (99.9%): [3.163, 4.408] (assumes normal distribution)


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
# Warmup Iteration   1: 8.935 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.952 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.245 ±(99.9%) 0.008 ms/op
Iteration   1: 3.177 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.007 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  14.680 ms/op
                 createUser·p0.9999: 20.702 ms/op
                 createUser·p1.00:   21.004 ms/op

Iteration   2: 3.276 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.386 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   4.182 ms/op
                 createUser·p0.99:   5.852 ms/op
                 createUser·p0.999:  16.876 ms/op
                 createUser·p0.9999: 23.076 ms/op
                 createUser·p1.00:   24.183 ms/op

Iteration   3: 3.293 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.360 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.424 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  16.595 ms/op
                 createUser·p0.9999: 42.205 ms/op
                 createUser·p1.00:   47.579 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295558
  mean =      3.248 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 289736 
    [ 5.000, 10.000) = 5382 
    [10.000, 15.000) = 107 
    [15.000, 20.000) = 180 
    [20.000, 25.000) = 121 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 6 
    [40.000, 45.000) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.007 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     16.588 ms/op
     p(99.9900) =     39.511 ms/op
     p(99.9990) =     47.326 ms/op
     p(99.9999) =     47.579 ms/op
    p(100.0000) =     47.579 ms/op


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
# Warmup Iteration   1: 8.382 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.315 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.007 ms/op
Iteration   1: 3.180 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.992 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   5.374 ms/op
                 existUser·p0.999:  11.469 ms/op
                 existUser·p0.9999: 22.139 ms/op
                 existUser·p1.00:   23.429 ms/op

Iteration   2: 3.178 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.214 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.981 ms/op
                 existUser·p0.99:   5.506 ms/op
                 existUser·p0.999:  10.819 ms/op
                 existUser·p0.9999: 22.837 ms/op
                 existUser·p1.00:   23.626 ms/op

Iteration   3: 3.123 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.217 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  13.040 ms/op
                 existUser·p0.9999: 20.677 ms/op
                 existUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303697
  mean =      3.160 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18450 
    [ 2.500,  5.000) = 279706 
    [ 5.000,  7.500) = 4716 
    [ 7.500, 10.000) = 389 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.992 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     12.026 ms/op
     p(99.9900) =     22.467 ms/op
     p(99.9990) =     23.427 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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
# Warmup Iteration   1: 8.442 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.545 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.449 ±(99.9%) 0.011 ms/op
Iteration   1: 3.246 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.413 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   6.373 ms/op
                 getUser·p0.999:  19.052 ms/op
                 getUser·p0.9999: 23.115 ms/op
                 getUser·p1.00:   24.052 ms/op

Iteration   2: 3.233 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.699 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   5.333 ms/op
                 getUser·p0.999:  12.858 ms/op
                 getUser·p0.9999: 30.449 ms/op
                 getUser·p1.00:   31.752 ms/op

Iteration   3: 3.236 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.087 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   5.874 ms/op
                 getUser·p0.999:  10.420 ms/op
                 getUser·p0.9999: 22.381 ms/op
                 getUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296253
  mean =      3.238 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8318 
    [ 2.500,  5.000) = 280620 
    [ 5.000,  7.500) = 6371 
    [ 7.500, 10.000) = 472 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 139 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      6.087 ms/op
     p(99.9000) =     16.802 ms/op
     p(99.9900) =     29.037 ms/op
     p(99.9990) =     30.885 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


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
# Warmup Iteration   1: 9.646 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.263 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.884 ±(99.9%) 0.013 ms/op
Iteration   1: 3.840 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.011 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   7.512 ms/op
                 listUser·p0.999:  16.715 ms/op
                 listUser·p0.9999: 21.419 ms/op
                 listUser·p1.00:   22.315 ms/op

Iteration   2: 3.692 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.860 ms/op
                 listUser·p0.50:   3.584 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   6.238 ms/op
                 listUser·p0.999:  14.746 ms/op
                 listUser·p0.9999: 17.717 ms/op
                 listUser·p1.00:   18.579 ms/op

Iteration   3: 3.692 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.097 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.174 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  12.883 ms/op
                 listUser·p0.9999: 17.203 ms/op
                 listUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256758
  mean =      3.740 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 250534 
    [ 5.000,  7.500) = 4268 
    [ 7.500, 10.000) = 1172 
    [10.000, 12.500) = 240 
    [12.500, 15.000) = 272 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.011 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     14.303 ms/op
     p(99.9900) =     20.546 ms/op
     p(99.9990) =     21.870 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.798 ± 3.470  ops/ms
ClientPb.existUser                       thrpt       3  10.258 ± 4.443  ops/ms
ClientPb.getUser                         thrpt       3   9.863 ± 3.685  ops/ms
ClientPb.listUser                        thrpt       3   8.548 ± 4.899  ops/ms
ClientPb.createUser                       avgt       3   3.155 ± 0.850   ms/op
ClientPb.existUser                        avgt       3   3.097 ± 0.633   ms/op
ClientPb.getUser                          avgt       3   3.282 ± 1.365   ms/op
ClientPb.listUser                         avgt       3   3.785 ± 0.622   ms/op
ClientPb.createUser                     sample  295558   3.248 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.007           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.535           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.895           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.595           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.588           ms/op
ClientPb.createUser:createUser·p0.9999  sample          39.511           ms/op
ClientPb.createUser:createUser·p1.00    sample          47.579           ms/op
ClientPb.existUser                      sample  303697   3.160 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.992           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.490           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.957           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.382           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.026           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.467           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.626           ms/op
ClientPb.getUser                        sample  296253   3.238 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.699           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.125           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.568           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.912           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.087           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.802           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.037           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.752           ms/op
ClientPb.listUser                       sample  256758   3.740 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.011           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.596           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.071           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.808           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.303           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.546           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.315           ms/op
