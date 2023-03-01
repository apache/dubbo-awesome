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
# Warmup Iteration   1: 2.555 ops/ms
# Warmup Iteration   2: 5.659 ops/ms
# Warmup Iteration   3: 9.313 ops/ms
Iteration   1: 10.006 ops/ms
Iteration   2: 10.269 ops/ms
Iteration   3: 10.282 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.186 ±(99.9%) 2.848 ops/ms [Average]
  (min, avg, max) = (10.006, 10.186, 10.282), stdev = 0.156
  CI (99.9%): [7.338, 13.034] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.717 ops/ms
# Warmup Iteration   2: 9.420 ops/ms
# Warmup Iteration   3: 10.188 ops/ms
Iteration   1: 10.552 ops/ms
Iteration   2: 10.226 ops/ms
Iteration   3: 9.797 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.192 ±(99.9%) 6.914 ops/ms [Average]
  (min, avg, max) = (9.797, 10.192, 10.552), stdev = 0.379
  CI (99.9%): [3.278, 17.105] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.809 ops/ms
# Warmup Iteration   2: 8.251 ops/ms
# Warmup Iteration   3: 10.062 ops/ms
Iteration   1: 10.103 ops/ms
Iteration   2: 9.833 ops/ms
Iteration   3: 9.945 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.960 ±(99.9%) 2.474 ops/ms [Average]
  (min, avg, max) = (9.833, 9.960, 10.103), stdev = 0.136
  CI (99.9%): [7.486, 12.435] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 3.067 ops/ms
# Warmup Iteration   2: 7.767 ops/ms
# Warmup Iteration   3: 8.225 ops/ms
Iteration   1: 8.589 ops/ms
Iteration   2: 8.577 ops/ms
Iteration   3: 8.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.570 ±(99.9%) 0.422 ops/ms [Average]
  (min, avg, max) = (8.544, 8.570, 8.589), stdev = 0.023
  CI (99.9%): [8.148, 8.992] (assumes normal distribution)


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
# Warmup Iteration   1: 8.508 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.516 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.330 ±(99.9%) 0.007 ms/op
Iteration   1: 3.281 ±(99.9%) 0.010 ms/op
Iteration   2: 3.066 ±(99.9%) 0.004 ms/op
Iteration   3: 3.091 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.146 ±(99.9%) 2.140 ms/op [Average]
  (min, avg, max) = (3.066, 3.146, 3.281), stdev = 0.117
  CI (99.9%): [1.006, 5.286] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.522 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.001 ms/op
Iteration   1: 3.063 ±(99.9%) 0.004 ms/op
Iteration   2: 3.022 ±(99.9%) 0.005 ms/op
Iteration   3: 3.063 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.049 ±(99.9%) 0.432 ms/op [Average]
  (min, avg, max) = (3.022, 3.049, 3.063), stdev = 0.024
  CI (99.9%): [2.618, 3.481] (assumes normal distribution)


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
# Warmup Iteration   1: 7.308 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.484 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.311 ±(99.9%) 0.002 ms/op
Iteration   1: 3.279 ±(99.9%) 0.005 ms/op
Iteration   2: 3.281 ±(99.9%) 0.005 ms/op
Iteration   3: 3.210 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.257 ±(99.9%) 0.733 ms/op [Average]
  (min, avg, max) = (3.210, 3.257, 3.281), stdev = 0.040
  CI (99.9%): [2.524, 3.989] (assumes normal distribution)


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
# Warmup Iteration   1: 9.330 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.025 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.859 ±(99.9%) 0.005 ms/op
Iteration   1: 3.649 ±(99.9%) 0.011 ms/op
Iteration   2: 3.762 ±(99.9%) 0.009 ms/op
Iteration   3: 3.768 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.726 ±(99.9%) 1.216 ms/op [Average]
  (min, avg, max) = (3.649, 3.726, 3.768), stdev = 0.067
  CI (99.9%): [2.511, 4.942] (assumes normal distribution)


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
# Warmup Iteration   1: 8.257 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.668 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.198 ±(99.9%) 0.009 ms/op
Iteration   1: 3.218 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.260 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  19.028 ms/op
                 createUser·p0.9999: 21.266 ms/op
                 createUser·p1.00:   21.496 ms/op

Iteration   2: 3.140 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.007 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   5.210 ms/op
                 createUser·p0.999:  16.587 ms/op
                 createUser·p0.9999: 25.297 ms/op
                 createUser·p1.00:   25.723 ms/op

Iteration   3: 3.085 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.831 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.228 ms/op
                 createUser·p0.95:   3.305 ms/op
                 createUser·p0.99:   5.005 ms/op
                 createUser·p0.999:  11.059 ms/op
                 createUser·p0.9999: 18.547 ms/op
                 createUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 304837
  mean =      3.147 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28077 
    [ 2.500,  5.000) = 272420 
    [ 5.000,  7.500) = 3564 
    [ 7.500, 10.000) = 225 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.831 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      5.235 ms/op
     p(99.9000) =     16.108 ms/op
     p(99.9900) =     24.643 ms/op
     p(99.9990) =     25.425 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.395 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.477 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.177 ±(99.9%) 0.008 ms/op
Iteration   1: 3.215 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.700 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  13.515 ms/op
                 existUser·p0.9999: 20.127 ms/op
                 existUser·p1.00:   22.282 ms/op

Iteration   2: 3.065 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.317 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.408 ms/op
                 existUser·p0.99:   4.932 ms/op
                 existUser·p0.999:  7.010 ms/op
                 existUser·p0.9999: 21.711 ms/op
                 existUser·p1.00:   22.675 ms/op

Iteration   3: 3.093 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.591 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   5.112 ms/op
                 existUser·p0.999:  12.157 ms/op
                 existUser·p0.9999: 20.228 ms/op
                 existUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307287
  mean =      3.123 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24966 
    [ 2.500,  5.000) = 278165 
    [ 5.000,  7.500) = 3438 
    [ 7.500, 10.000) = 213 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.317 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.371 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      5.210 ms/op
     p(99.9000) =     13.365 ms/op
     p(99.9900) =     21.350 ms/op
     p(99.9990) =     22.495 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


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
# Warmup Iteration   1: 7.569 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.442 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.279 ±(99.9%) 0.009 ms/op
Iteration   1: 3.303 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.589 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.866 ms/op
                 getUser·p0.99:   6.652 ms/op
                 getUser·p0.999:  15.430 ms/op
                 getUser·p0.9999: 26.411 ms/op
                 getUser·p1.00:   26.640 ms/op

Iteration   2: 3.265 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.313 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.657 ms/op
                 getUser·p0.95:   4.186 ms/op
                 getUser·p0.99:   5.464 ms/op
                 getUser·p0.999:  12.059 ms/op
                 getUser·p0.9999: 27.204 ms/op
                 getUser·p1.00:   27.722 ms/op

Iteration   3: 3.285 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.077 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   6.661 ms/op
                 getUser·p0.999:  13.840 ms/op
                 getUser·p0.9999: 22.979 ms/op
                 getUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292088
  mean =      3.284 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18824 
    [ 2.500,  5.000) = 264008 
    [ 5.000,  7.500) = 7888 
    [ 7.500, 10.000) = 867 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 60 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      6.316 ms/op
     p(99.9000) =     15.023 ms/op
     p(99.9900) =     26.575 ms/op
     p(99.9990) =     27.601 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


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
# Warmup Iteration   1: 9.021 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.202 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.946 ±(99.9%) 0.013 ms/op
Iteration   1: 3.721 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.524 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  16.663 ms/op
                 listUser·p0.9999: 22.047 ms/op
                 listUser·p1.00:   22.839 ms/op

Iteration   2: 3.875 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.122 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  13.246 ms/op
                 listUser·p0.9999: 18.167 ms/op
                 listUser·p1.00:   18.874 ms/op

Iteration   3: 3.698 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  13.624 ms/op
                 listUser·p0.9999: 17.007 ms/op
                 listUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254951
  mean =      3.763 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 63 
    [ 2.500,  5.000) = 247072 
    [ 5.000,  7.500) = 5963 
    [ 7.500, 10.000) = 1131 
    [10.000, 12.500) = 313 
    [12.500, 15.000) = 213 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.524 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     14.173 ms/op
     p(99.9900) =     20.595 ms/op
     p(99.9990) =     22.517 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.186 ± 2.848  ops/ms
ClientPb.existUser                       thrpt       3  10.192 ± 6.914  ops/ms
ClientPb.getUser                         thrpt       3   9.960 ± 2.474  ops/ms
ClientPb.listUser                        thrpt       3   8.570 ± 0.422  ops/ms
ClientPb.createUser                       avgt       3   3.146 ± 2.140   ms/op
ClientPb.existUser                        avgt       3   3.049 ± 0.432   ms/op
ClientPb.getUser                          avgt       3   3.257 ± 0.733   ms/op
ClientPb.listUser                         avgt       3   3.726 ± 1.216   ms/op
ClientPb.createUser                     sample  304837   3.147 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.831           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.342           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.654           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.235           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.108           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.643           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.723           ms/op
ClientPb.existUser                      sample  307287   3.123 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.317           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.371           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.210           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.365           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.350           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.675           ms/op
ClientPb.getUser                        sample  292088   3.284 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.077           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.703           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.375           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.316           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.023           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.575           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.722           ms/op
ClientPb.listUser                       sample  254951   3.763 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.524           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.633           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.092           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.906           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.173           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.595           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.839           ms/op
