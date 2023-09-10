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
# Warmup Iteration   1: 2.444 ops/ms
# Warmup Iteration   2: 6.242 ops/ms
# Warmup Iteration   3: 8.931 ops/ms
Iteration   1: 9.558 ops/ms
Iteration   2: 9.928 ops/ms
Iteration   3: 9.507 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.664 ±(99.9%) 4.193 ops/ms [Average]
  (min, avg, max) = (9.507, 9.664, 9.928), stdev = 0.230
  CI (99.9%): [5.471, 13.858] (assumes normal distribution)


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
# Warmup Iteration   1: 3.325 ops/ms
# Warmup Iteration   2: 8.899 ops/ms
# Warmup Iteration   3: 9.575 ops/ms
Iteration   1: 10.193 ops/ms
Iteration   2: 10.287 ops/ms
Iteration   3: 10.023 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.168 ±(99.9%) 2.441 ops/ms [Average]
  (min, avg, max) = (10.023, 10.168, 10.287), stdev = 0.134
  CI (99.9%): [7.726, 12.609] (assumes normal distribution)


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
# Warmup Iteration   1: 3.600 ops/ms
# Warmup Iteration   2: 8.736 ops/ms
# Warmup Iteration   3: 9.168 ops/ms
Iteration   1: 9.593 ops/ms
Iteration   2: 9.597 ops/ms
Iteration   3: 9.634 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.608 ±(99.9%) 0.417 ops/ms [Average]
  (min, avg, max) = (9.593, 9.608, 9.634), stdev = 0.023
  CI (99.9%): [9.192, 10.025] (assumes normal distribution)


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
# Warmup Iteration   1: 3.042 ops/ms
# Warmup Iteration   2: 7.442 ops/ms
# Warmup Iteration   3: 8.183 ops/ms
Iteration   1: 7.952 ops/ms
Iteration   2: 8.123 ops/ms
Iteration   3: 8.331 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.135 ±(99.9%) 3.463 ops/ms [Average]
  (min, avg, max) = (7.952, 8.135, 8.331), stdev = 0.190
  CI (99.9%): [4.672, 11.598] (assumes normal distribution)


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
# Warmup Iteration   1: 8.834 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.640 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.385 ±(99.9%) 0.006 ms/op
Iteration   1: 3.281 ±(99.9%) 0.005 ms/op
Iteration   2: 3.336 ±(99.9%) 0.005 ms/op
Iteration   3: 3.386 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.334 ±(99.9%) 0.958 ms/op [Average]
  (min, avg, max) = (3.281, 3.334, 3.386), stdev = 0.053
  CI (99.9%): [2.376, 4.292] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.743 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.386 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.003 ms/op
Iteration   1: 3.045 ±(99.9%) 0.004 ms/op
Iteration   2: 3.140 ±(99.9%) 0.005 ms/op
Iteration   3: 3.067 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.084 ±(99.9%) 0.906 ms/op [Average]
  (min, avg, max) = (3.045, 3.084, 3.140), stdev = 0.050
  CI (99.9%): [2.179, 3.990] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.735 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.525 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.384 ±(99.9%) 0.003 ms/op
Iteration   1: 3.239 ±(99.9%) 0.007 ms/op
Iteration   2: 3.133 ±(99.9%) 0.005 ms/op
Iteration   3: 3.211 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.194 ±(99.9%) 1.003 ms/op [Average]
  (min, avg, max) = (3.133, 3.194, 3.239), stdev = 0.055
  CI (99.9%): [2.192, 4.197] (assumes normal distribution)


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
# Warmup Iteration   1: 9.778 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.340 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.009 ±(99.9%) 0.008 ms/op
Iteration   1: 3.912 ±(99.9%) 0.005 ms/op
Iteration   2: 3.924 ±(99.9%) 0.008 ms/op
Iteration   3: 3.914 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.917 ±(99.9%) 0.120 ms/op [Average]
  (min, avg, max) = (3.912, 3.917, 3.924), stdev = 0.007
  CI (99.9%): [3.797, 4.036] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.890 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.664 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.339 ±(99.9%) 0.010 ms/op
Iteration   1: 3.202 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.396 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   6.226 ms/op
                 createUser·p0.999:  19.005 ms/op
                 createUser·p0.9999: 21.168 ms/op
                 createUser·p1.00:   23.200 ms/op

Iteration   2: 3.268 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.645 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   5.904 ms/op
                 createUser·p0.999:  17.138 ms/op
                 createUser·p0.9999: 21.899 ms/op
                 createUser·p1.00:   22.938 ms/op

Iteration   3: 3.275 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.794 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   5.947 ms/op
                 createUser·p0.999:  17.203 ms/op
                 createUser·p0.9999: 23.903 ms/op
                 createUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295379
  mean =      3.248 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18623 
    [ 2.500,  5.000) = 270055 
    [ 5.000,  7.500) = 5081 
    [ 7.500, 10.000) = 1141 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 146 
    [20.000, 22.500) = 138 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      5.997 ms/op
     p(99.9000) =     18.317 ms/op
     p(99.9900) =     22.920 ms/op
     p(99.9990) =     24.183 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


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
# Warmup Iteration   1: 7.989 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.483 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.189 ±(99.9%) 0.008 ms/op
Iteration   1: 3.336 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.468 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.858 ms/op
                 existUser·p0.95:   4.440 ms/op
                 existUser·p0.99:   6.554 ms/op
                 existUser·p0.999:  10.519 ms/op
                 existUser·p0.9999: 20.723 ms/op
                 existUser·p1.00:   21.496 ms/op

Iteration   2: 3.170 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.026 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.743 ms/op
                 existUser·p0.999:  9.585 ms/op
                 existUser·p0.9999: 50.782 ms/op
                 existUser·p1.00:   51.315 ms/op

Iteration   3: 3.274 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.221 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   7.012 ms/op
                 existUser·p0.999:  19.087 ms/op
                 existUser·p0.9999: 27.303 ms/op
                 existUser·p1.00:   28.934 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294782
  mean =      3.258 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 286539 
    [ 5.000, 10.000) = 7739 
    [10.000, 15.000) = 252 
    [15.000, 20.000) = 46 
    [20.000, 25.000) = 151 
    [25.000, 30.000) = 32 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 8 
    [50.000, 55.000) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.026 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =     13.491 ms/op
     p(99.9900) =     27.722 ms/op
     p(99.9990) =     51.056 ms/op
     p(99.9999) =     51.315 ms/op
    p(100.0000) =     51.315 ms/op


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
# Warmup Iteration   1: 8.284 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.698 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.548 ±(99.9%) 0.010 ms/op
Iteration   1: 3.416 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.143 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   4.178 ms/op
                 getUser·p0.95:   5.382 ms/op
                 getUser·p0.99:   6.878 ms/op
                 getUser·p0.999:  14.434 ms/op
                 getUser·p0.9999: 24.248 ms/op
                 getUser·p1.00:   24.576 ms/op

Iteration   2: 3.250 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.640 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   5.489 ms/op
                 getUser·p0.999:  9.704 ms/op
                 getUser·p0.9999: 22.479 ms/op
                 getUser·p1.00:   23.298 ms/op

Iteration   3: 3.277 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.319 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   6.398 ms/op
                 getUser·p0.999:  18.985 ms/op
                 getUser·p0.9999: 34.947 ms/op
                 getUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 289504
  mean =      3.313 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9189 
    [ 2.500,  5.000) = 270827 
    [ 5.000,  7.500) = 7846 
    [ 7.500, 10.000) = 1158 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 145 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.520 ms/op
     p(99.9000) =     14.434 ms/op
     p(99.9900) =     33.620 ms/op
     p(99.9990) =     35.658 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


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
# Warmup Iteration   1: 9.530 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.331 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.980 ±(99.9%) 0.013 ms/op
Iteration   1: 3.868 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.124 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   7.496 ms/op
                 listUser·p0.999:  15.499 ms/op
                 listUser·p0.9999: 20.214 ms/op
                 listUser·p1.00:   20.939 ms/op

Iteration   2: 3.889 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.878 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   7.725 ms/op
                 listUser·p0.999:  14.455 ms/op
                 listUser·p0.9999: 18.088 ms/op
                 listUser·p1.00:   18.285 ms/op

Iteration   3: 3.934 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.907 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   8.002 ms/op
                 listUser·p0.999:  14.418 ms/op
                 listUser·p0.9999: 19.001 ms/op
                 listUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 246480
  mean =      3.897 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 94 
    [ 2.500,  5.000) = 234953 
    [ 5.000,  7.500) = 8632 
    [ 7.500, 10.000) = 2027 
    [10.000, 12.500) = 367 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      7.692 ms/op
     p(99.9000) =     15.122 ms/op
     p(99.9900) =     19.235 ms/op
     p(99.9990) =     20.906 ms/op
     p(99.9999) =     20.939 ms/op
    p(100.0000) =     20.939 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.664 ± 4.193  ops/ms
ClientPb.existUser                       thrpt       3  10.168 ± 2.441  ops/ms
ClientPb.getUser                         thrpt       3   9.608 ± 0.417  ops/ms
ClientPb.listUser                        thrpt       3   8.135 ± 3.463  ops/ms
ClientPb.createUser                       avgt       3   3.334 ± 0.958   ms/op
ClientPb.existUser                        avgt       3   3.084 ± 0.906   ms/op
ClientPb.getUser                          avgt       3   3.194 ± 1.003   ms/op
ClientPb.listUser                         avgt       3   3.917 ± 0.120   ms/op
ClientPb.createUser                     sample  295379   3.248 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.104           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.547           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.863           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.997           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.317           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.920           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.379           ms/op
ClientPb.existUser                      sample  294782   3.258 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.026           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.187           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.365           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.491           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.722           ms/op
ClientPb.existUser:existUser·p1.00      sample          51.315           ms/op
ClientPb.getUser                        sample  289504   3.313 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.143           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.678           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.391           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.520           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.434           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.620           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.783           ms/op
ClientPb.listUser                       sample  246480   3.897 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.124           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.707           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.260           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.801           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.692           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.122           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.235           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.939           ms/op
