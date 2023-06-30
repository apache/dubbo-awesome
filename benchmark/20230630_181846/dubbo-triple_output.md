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
# Warmup Iteration   1: 2.495 ops/ms
# Warmup Iteration   2: 5.914 ops/ms
# Warmup Iteration   3: 9.052 ops/ms
Iteration   1: 9.365 ops/ms
Iteration   2: 9.716 ops/ms
Iteration   3: 9.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.679 ±(99.9%) 5.428 ops/ms [Average]
  (min, avg, max) = (9.365, 9.679, 9.956), stdev = 0.298
  CI (99.9%): [4.251, 15.107] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.158 ops/ms
# Warmup Iteration   2: 8.760 ops/ms
# Warmup Iteration   3: 9.925 ops/ms
Iteration   1: 10.135 ops/ms
Iteration   2: 9.757 ops/ms
Iteration   3: 10.110 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.001 ±(99.9%) 3.859 ops/ms [Average]
  (min, avg, max) = (9.757, 10.001, 10.135), stdev = 0.211
  CI (99.9%): [6.142, 13.859] (assumes normal distribution)


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
# Warmup Iteration   1: 3.348 ops/ms
# Warmup Iteration   2: 9.032 ops/ms
# Warmup Iteration   3: 9.564 ops/ms
Iteration   1: 9.736 ops/ms
Iteration   2: 9.761 ops/ms
Iteration   3: 9.629 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.709 ±(99.9%) 1.277 ops/ms [Average]
  (min, avg, max) = (9.629, 9.709, 9.761), stdev = 0.070
  CI (99.9%): [8.432, 10.986] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.973 ops/ms
# Warmup Iteration   2: 7.242 ops/ms
# Warmup Iteration   3: 8.411 ops/ms
Iteration   1: 8.413 ops/ms
Iteration   2: 8.382 ops/ms
Iteration   3: 8.622 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.472 ±(99.9%) 2.376 ops/ms [Average]
  (min, avg, max) = (8.382, 8.472, 8.622), stdev = 0.130
  CI (99.9%): [6.096, 10.849] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.917 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.005 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.387 ±(99.9%) 0.006 ms/op
Iteration   1: 3.195 ±(99.9%) 0.003 ms/op
Iteration   2: 3.291 ±(99.9%) 0.003 ms/op
Iteration   3: 3.182 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.222 ±(99.9%) 1.084 ms/op [Average]
  (min, avg, max) = (3.182, 3.222, 3.291), stdev = 0.059
  CI (99.9%): [2.138, 4.307] (assumes normal distribution)


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
# Warmup Iteration   1: 7.709 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.537 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.195 ±(99.9%) 0.004 ms/op
Iteration   1: 3.173 ±(99.9%) 0.009 ms/op
Iteration   2: 3.055 ±(99.9%) 0.006 ms/op
Iteration   3: 3.137 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.122 ±(99.9%) 1.106 ms/op [Average]
  (min, avg, max) = (3.055, 3.122, 3.173), stdev = 0.061
  CI (99.9%): [2.016, 4.227] (assumes normal distribution)


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
# Warmup Iteration   1: 8.809 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.537 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.324 ±(99.9%) 0.002 ms/op
Iteration   1: 3.142 ±(99.9%) 0.003 ms/op
Iteration   2: 3.181 ±(99.9%) 0.006 ms/op
Iteration   3: 3.206 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.176 ±(99.9%) 0.591 ms/op [Average]
  (min, avg, max) = (3.142, 3.176, 3.206), stdev = 0.032
  CI (99.9%): [2.586, 3.767] (assumes normal distribution)


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
# Warmup Iteration   1: 9.320 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.146 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.839 ±(99.9%) 0.009 ms/op
Iteration   1: 3.803 ±(99.9%) 0.006 ms/op
Iteration   2: 3.812 ±(99.9%) 0.010 ms/op
Iteration   3: 3.751 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.789 ±(99.9%) 0.597 ms/op [Average]
  (min, avg, max) = (3.751, 3.789, 3.812), stdev = 0.033
  CI (99.9%): [3.191, 4.386] (assumes normal distribution)


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
# Warmup Iteration   1: 8.369 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.735 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.270 ±(99.9%) 0.009 ms/op
Iteration   1: 3.262 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.235 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  18.743 ms/op
                 createUser·p0.9999: 24.982 ms/op
                 createUser·p1.00:   27.197 ms/op

Iteration   2: 3.311 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.235 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  18.599 ms/op
                 createUser·p0.9999: 23.342 ms/op
                 createUser·p1.00:   23.986 ms/op

Iteration   3: 3.431 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.620 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  16.299 ms/op
                 createUser·p0.9999: 19.666 ms/op
                 createUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 287789
  mean =      3.333 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24974 
    [ 2.500,  5.000) = 254800 
    [ 5.000,  7.500) = 7085 
    [ 7.500, 10.000) = 482 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 153 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.235 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =     17.760 ms/op
     p(99.9900) =     24.008 ms/op
     p(99.9990) =     26.478 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


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
# Warmup Iteration   1: 7.435 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.422 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.007 ms/op
Iteration   1: 3.112 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.188 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   5.689 ms/op
                 existUser·p0.999:  13.159 ms/op
                 existUser·p0.9999: 22.821 ms/op
                 existUser·p1.00:   23.822 ms/op

Iteration   2: 3.132 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.458 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  12.252 ms/op
                 existUser·p0.9999: 23.291 ms/op
                 existUser·p1.00:   23.757 ms/op

Iteration   3: 3.217 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.116 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  8.315 ms/op
                 existUser·p0.9999: 19.860 ms/op
                 existUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304276
  mean =      3.153 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22627 
    [ 2.500,  5.000) = 276879 
    [ 5.000,  7.500) = 4084 
    [ 7.500, 10.000) = 310 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.116 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     12.218 ms/op
     p(99.9900) =     22.970 ms/op
     p(99.9990) =     23.755 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


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
# Warmup Iteration   1: 9.085 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.548 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.242 ±(99.9%) 0.009 ms/op
Iteration   1: 3.277 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.391 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   4.166 ms/op
                 getUser·p0.99:   6.275 ms/op
                 getUser·p0.999:  17.367 ms/op
                 getUser·p0.9999: 26.983 ms/op
                 getUser·p1.00:   29.557 ms/op

Iteration   2: 3.339 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.040 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.751 ms/op
                 getUser·p0.99:   6.005 ms/op
                 getUser·p0.999:  19.840 ms/op
                 getUser·p0.9999: 22.221 ms/op
                 getUser·p1.00:   24.052 ms/op

Iteration   3: 3.166 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.198 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   5.472 ms/op
                 getUser·p0.999:  16.450 ms/op
                 getUser·p0.9999: 22.604 ms/op
                 getUser·p1.00:   23.134 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294263
  mean =      3.259 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15509 
    [ 2.500,  5.000) = 271310 
    [ 5.000,  7.500) = 6282 
    [ 7.500, 10.000) = 555 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 133 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.040 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     16.740 ms/op
     p(99.9900) =     23.734 ms/op
     p(99.9990) =     28.377 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


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
# Warmup Iteration   1: 9.993 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.129 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.864 ±(99.9%) 0.012 ms/op
Iteration   1: 3.897 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.888 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  14.534 ms/op
                 listUser·p0.9999: 20.433 ms/op
                 listUser·p1.00:   21.594 ms/op

Iteration   2: 3.774 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.474 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   6.924 ms/op
                 listUser·p0.999:  14.341 ms/op
                 listUser·p0.9999: 19.628 ms/op
                 listUser·p1.00:   19.759 ms/op

Iteration   3: 3.778 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.415 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  13.681 ms/op
                 listUser·p0.9999: 18.907 ms/op
                 listUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251468
  mean =      3.816 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 243904 
    [ 5.000,  7.500) = 5603 
    [ 7.500, 10.000) = 1236 
    [10.000, 12.500) = 267 
    [12.500, 15.000) = 254 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.415 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     14.238 ms/op
     p(99.9900) =     19.815 ms/op
     p(99.9990) =     21.042 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.679 ± 5.428  ops/ms
ClientPb.existUser                       thrpt       3  10.001 ± 3.859  ops/ms
ClientPb.getUser                         thrpt       3   9.709 ± 1.277  ops/ms
ClientPb.listUser                        thrpt       3   8.472 ± 2.376  ops/ms
ClientPb.createUser                       avgt       3   3.222 ± 1.084   ms/op
ClientPb.existUser                        avgt       3   3.122 ± 1.106   ms/op
ClientPb.getUser                          avgt       3   3.176 ± 0.591   ms/op
ClientPb.listUser                         avgt       3   3.789 ± 0.597   ms/op
ClientPb.createUser                     sample  287789   3.333 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.235           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.269           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.579           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.760           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.008           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.197           ms/op
ClientPb.existUser                      sample  304276   3.153 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.116           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.486           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.809           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.431           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.218           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.970           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.822           ms/op
ClientPb.getUser                        sample  294263   3.259 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.040           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.658           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.108           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.906           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.740           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.734           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.557           ms/op
ClientPb.listUser                       sample  251468   3.816 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.415           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.703           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.121           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.029           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.238           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.815           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.594           ms/op
