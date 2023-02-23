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
# Warmup Iteration   1: 2.647 ops/ms
# Warmup Iteration   2: 6.353 ops/ms
# Warmup Iteration   3: 9.604 ops/ms
Iteration   1: 9.956 ops/ms
Iteration   2: 10.149 ops/ms
Iteration   3: 10.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.035 ±(99.9%) 1.843 ops/ms [Average]
  (min, avg, max) = (9.956, 10.035, 10.149), stdev = 0.101
  CI (99.9%): [8.192, 11.879] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.544 ops/ms
# Warmup Iteration   2: 9.443 ops/ms
# Warmup Iteration   3: 10.214 ops/ms
Iteration   1: 10.234 ops/ms
Iteration   2: 10.182 ops/ms
Iteration   3: 10.195 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.204 ±(99.9%) 0.489 ops/ms [Average]
  (min, avg, max) = (10.182, 10.204, 10.234), stdev = 0.027
  CI (99.9%): [9.714, 10.693] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.661 ops/ms
# Warmup Iteration   2: 9.240 ops/ms
# Warmup Iteration   3: 9.948 ops/ms
Iteration   1: 10.391 ops/ms
Iteration   2: 10.252 ops/ms
Iteration   3: 10.157 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.267 ±(99.9%) 2.151 ops/ms [Average]
  (min, avg, max) = (10.157, 10.267, 10.391), stdev = 0.118
  CI (99.9%): [8.116, 12.417] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 3.238 ops/ms
# Warmup Iteration   2: 7.986 ops/ms
# Warmup Iteration   3: 8.619 ops/ms
Iteration   1: 8.523 ops/ms
Iteration   2: 8.890 ops/ms
Iteration   3: 8.722 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.712 ±(99.9%) 3.352 ops/ms [Average]
  (min, avg, max) = (8.523, 8.712, 8.890), stdev = 0.184
  CI (99.9%): [5.360, 12.063] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.847 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.625 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.528 ±(99.9%) 0.005 ms/op
Iteration   1: 3.102 ±(99.9%) 0.007 ms/op
Iteration   2: 3.200 ±(99.9%) 0.003 ms/op
Iteration   3: 3.327 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.210 ±(99.9%) 2.058 ms/op [Average]
  (min, avg, max) = (3.102, 3.210, 3.327), stdev = 0.113
  CI (99.9%): [1.152, 5.268] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.231 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.231 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.002 ms/op
Iteration   1: 3.159 ±(99.9%) 0.008 ms/op
Iteration   2: 3.009 ±(99.9%) 0.007 ms/op
Iteration   3: 2.956 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.041 ±(99.9%) 1.922 ms/op [Average]
  (min, avg, max) = (2.956, 3.041, 3.159), stdev = 0.105
  CI (99.9%): [1.119, 4.963] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 6.899 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.325 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.202 ±(99.9%) 0.004 ms/op
Iteration   1: 3.198 ±(99.9%) 0.004 ms/op
Iteration   2: 3.331 ±(99.9%) 0.004 ms/op
Iteration   3: 3.329 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.286 ±(99.9%) 1.392 ms/op [Average]
  (min, avg, max) = (3.198, 3.286, 3.331), stdev = 0.076
  CI (99.9%): [1.894, 4.677] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 8.676 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.066 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.781 ±(99.9%) 0.007 ms/op
Iteration   1: 3.736 ±(99.9%) 0.004 ms/op
Iteration   2: 3.699 ±(99.9%) 0.004 ms/op
Iteration   3: 3.565 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.667 ±(99.9%) 1.647 ms/op [Average]
  (min, avg, max) = (3.565, 3.667, 3.736), stdev = 0.090
  CI (99.9%): [2.020, 5.313] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.468 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.688 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.008 ms/op
Iteration   1: 3.286 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.665 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   6.332 ms/op
                 createUser·p0.999:  13.561 ms/op
                 createUser·p0.9999: 19.562 ms/op
                 createUser·p1.00:   20.414 ms/op

Iteration   2: 3.120 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.206 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   5.174 ms/op
                 createUser·p0.999:  16.499 ms/op
                 createUser·p0.9999: 22.774 ms/op
                 createUser·p1.00:   23.265 ms/op

Iteration   3: 3.062 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.077 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.330 ms/op
                 createUser·p0.95:   3.551 ms/op
                 createUser·p0.99:   5.153 ms/op
                 createUser·p0.999:  16.294 ms/op
                 createUser·p0.9999: 20.647 ms/op
                 createUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 304350
  mean =      3.153 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14534 
    [ 2.500,  5.000) = 284410 
    [ 5.000,  7.500) = 4434 
    [ 7.500, 10.000) = 427 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 191 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     16.313 ms/op
     p(99.9900) =     22.201 ms/op
     p(99.9990) =     23.557 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 6.331 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.346 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.009 ms/op
Iteration   1: 3.175 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.190 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  8.798 ms/op
                 existUser·p0.9999: 20.546 ms/op
                 existUser·p1.00:   21.266 ms/op

Iteration   2: 3.225 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.130 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   4.121 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  14.270 ms/op
                 existUser·p0.9999: 26.312 ms/op
                 existUser·p1.00:   27.230 ms/op

Iteration   3: 3.033 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.411 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.199 ms/op
                 existUser·p0.95:   3.342 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  11.026 ms/op
                 existUser·p0.9999: 20.561 ms/op
                 existUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305260
  mean =      3.142 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26879 
    [ 2.500,  5.000) = 273206 
    [ 5.000,  7.500) = 4468 
    [ 7.500, 10.000) = 274 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      5.267 ms/op
     p(99.9000) =     14.270 ms/op
     p(99.9900) =     25.050 ms/op
     p(99.9990) =     27.097 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 8.814 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.337 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.197 ±(99.9%) 0.008 ms/op
Iteration   1: 3.305 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.643 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.653 ms/op
                 getUser·p0.99:   5.915 ms/op
                 getUser·p0.999:  13.640 ms/op
                 getUser·p0.9999: 19.180 ms/op
                 getUser·p1.00:   19.595 ms/op

Iteration   2: 3.255 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.313 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   5.652 ms/op
                 getUser·p0.999:  16.274 ms/op
                 getUser·p0.9999: 25.494 ms/op
                 getUser·p1.00:   25.919 ms/op

Iteration   3: 3.270 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.239 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.943 ms/op
                 getUser·p0.99:   5.978 ms/op
                 getUser·p0.999:  13.247 ms/op
                 getUser·p0.9999: 20.717 ms/op
                 getUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292635
  mean =      3.277 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21702 
    [ 2.500,  5.000) = 261459 
    [ 5.000,  7.500) = 8572 
    [ 7.500, 10.000) = 450 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     13.584 ms/op
     p(99.9900) =     23.305 ms/op
     p(99.9990) =     25.697 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


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
# Warmup Iteration   1: 9.071 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.005 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.684 ±(99.9%) 0.011 ms/op
Iteration   1: 3.690 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.630 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.194 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  14.875 ms/op
                 listUser·p0.9999: 24.707 ms/op
                 listUser·p1.00:   25.592 ms/op

Iteration   2: 3.688 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.919 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  15.067 ms/op
                 listUser·p0.9999: 20.120 ms/op
                 listUser·p1.00:   21.561 ms/op

Iteration   3: 3.651 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.339 ms/op
                 listUser·p0.50:   3.523 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.121 ms/op
                 listUser·p0.99:   7.356 ms/op
                 listUser·p0.999:  13.812 ms/op
                 listUser·p0.9999: 17.596 ms/op
                 listUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 260887
  mean =      3.676 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 83 
    [ 2.500,  5.000) = 253136 
    [ 5.000,  7.500) = 5572 
    [ 7.500, 10.000) = 1403 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 304 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.630 ms/op
     p(50.0000) =      3.559 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     14.303 ms/op
     p(99.9900) =     23.313 ms/op
     p(99.9990) =     25.446 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.035 ± 1.843  ops/ms
ClientPb.existUser                       thrpt       3  10.204 ± 0.489  ops/ms
ClientPb.getUser                         thrpt       3  10.267 ± 2.151  ops/ms
ClientPb.listUser                        thrpt       3   8.712 ± 3.352  ops/ms
ClientPb.createUser                       avgt       3   3.210 ± 2.058   ms/op
ClientPb.existUser                        avgt       3   3.041 ± 1.922   ms/op
ClientPb.getUser                          avgt       3   3.286 ± 1.392   ms/op
ClientPb.listUser                         avgt       3   3.667 ± 1.647   ms/op
ClientPb.createUser                     sample  304350   3.153 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.665           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.584           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.489           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.313           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.201           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.757           ms/op
ClientPb.existUser                      sample  305260   3.142 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.130           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.510           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.883           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.267           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.270           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.050           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.230           ms/op
ClientPb.getUser                        sample  292635   3.277 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.643           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.719           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.317           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.865           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.584           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.305           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.919           ms/op
ClientPb.listUser                       sample  260887   3.676 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.630           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.559           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.932           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.186           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.111           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.303           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.313           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.592           ms/op
