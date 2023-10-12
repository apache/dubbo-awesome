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
# Warmup Iteration   1: 2.306 ops/ms
# Warmup Iteration   2: 5.687 ops/ms
# Warmup Iteration   3: 8.945 ops/ms
Iteration   1: 9.449 ops/ms
Iteration   2: 9.568 ops/ms
Iteration   3: 9.494 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.504 ±(99.9%) 1.094 ops/ms [Average]
  (min, avg, max) = (9.449, 9.504, 9.568), stdev = 0.060
  CI (99.9%): [8.410, 10.597] (assumes normal distribution)


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
# Warmup Iteration   1: 3.499 ops/ms
# Warmup Iteration   2: 8.783 ops/ms
# Warmup Iteration   3: 9.956 ops/ms
Iteration   1: 9.857 ops/ms
Iteration   2: 9.710 ops/ms
Iteration   3: 9.944 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.837 ±(99.9%) 2.161 ops/ms [Average]
  (min, avg, max) = (9.710, 9.837, 9.944), stdev = 0.118
  CI (99.9%): [7.676, 11.998] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.168 ops/ms
# Warmup Iteration   2: 8.906 ops/ms
# Warmup Iteration   3: 9.833 ops/ms
Iteration   1: 9.604 ops/ms
Iteration   2: 9.764 ops/ms
Iteration   3: 9.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.694 ±(99.9%) 1.492 ops/ms [Average]
  (min, avg, max) = (9.604, 9.694, 9.764), stdev = 0.082
  CI (99.9%): [8.202, 11.185] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.184 ops/ms
# Warmup Iteration   2: 7.540 ops/ms
# Warmup Iteration   3: 7.852 ops/ms
Iteration   1: 8.080 ops/ms
Iteration   2: 8.195 ops/ms
Iteration   3: 8.248 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.174 ±(99.9%) 1.564 ops/ms [Average]
  (min, avg, max) = (8.080, 8.174, 8.248), stdev = 0.086
  CI (99.9%): [6.611, 9.738] (assumes normal distribution)


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
# Warmup Iteration   1: 8.731 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.630 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.399 ±(99.9%) 0.004 ms/op
Iteration   1: 3.297 ±(99.9%) 0.004 ms/op
Iteration   2: 3.346 ±(99.9%) 0.005 ms/op
Iteration   3: 3.210 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.284 ±(99.9%) 1.260 ms/op [Average]
  (min, avg, max) = (3.210, 3.284, 3.346), stdev = 0.069
  CI (99.9%): [2.024, 4.545] (assumes normal distribution)


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
# Warmup Iteration   1: 7.447 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.325 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.186 ±(99.9%) 0.004 ms/op
Iteration   1: 3.190 ±(99.9%) 0.002 ms/op
Iteration   2: 3.158 ±(99.9%) 0.005 ms/op
Iteration   3: 3.179 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.175 ±(99.9%) 0.299 ms/op [Average]
  (min, avg, max) = (3.158, 3.175, 3.190), stdev = 0.016
  CI (99.9%): [2.877, 3.474] (assumes normal distribution)


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
# Warmup Iteration   1: 7.271 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.479 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.348 ±(99.9%) 0.003 ms/op
Iteration   1: 3.313 ±(99.9%) 0.005 ms/op
Iteration   2: 3.266 ±(99.9%) 0.005 ms/op
Iteration   3: 3.312 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.297 ±(99.9%) 0.489 ms/op [Average]
  (min, avg, max) = (3.266, 3.297, 3.313), stdev = 0.027
  CI (99.9%): [2.808, 3.786] (assumes normal distribution)


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
# Warmup Iteration   1: 9.933 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.210 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.980 ±(99.9%) 0.005 ms/op
Iteration   1: 3.884 ±(99.9%) 0.005 ms/op
Iteration   2: 3.884 ±(99.9%) 0.006 ms/op
Iteration   3: 3.898 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.889 ±(99.9%) 0.151 ms/op [Average]
  (min, avg, max) = (3.884, 3.889, 3.898), stdev = 0.008
  CI (99.9%): [3.737, 4.040] (assumes normal distribution)


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
# Warmup Iteration   1: 8.706 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.893 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.315 ±(99.9%) 0.009 ms/op
Iteration   1: 3.340 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.516 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   6.881 ms/op
                 createUser·p0.999:  19.208 ms/op
                 createUser·p0.9999: 23.011 ms/op
                 createUser·p1.00:   26.837 ms/op

Iteration   2: 3.445 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.855 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   7.021 ms/op
                 createUser·p0.999:  20.026 ms/op
                 createUser·p0.9999: 22.568 ms/op
                 createUser·p1.00:   24.773 ms/op

Iteration   3: 3.392 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.311 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.119 ms/op
                 createUser·p0.99:   6.089 ms/op
                 createUser·p0.999:  15.958 ms/op
                 createUser·p0.9999: 22.498 ms/op
                 createUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283019
  mean =      3.392 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11944 
    [ 2.500,  5.000) = 263309 
    [ 5.000,  7.500) = 6248 
    [ 7.500, 10.000) = 564 
    [10.000, 12.500) = 494 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 190 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.516 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     18.416 ms/op
     p(99.9900) =     22.656 ms/op
     p(99.9990) =     24.365 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


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
# Warmup Iteration   1: 7.279 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.448 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.278 ±(99.9%) 0.010 ms/op
Iteration   1: 3.225 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.931 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.998 ms/op
                 existUser·p0.99:   6.153 ms/op
                 existUser·p0.999:  16.247 ms/op
                 existUser·p0.9999: 20.843 ms/op
                 existUser·p1.00:   21.758 ms/op

Iteration   2: 3.205 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.085 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   6.029 ms/op
                 existUser·p0.999:  13.807 ms/op
                 existUser·p0.9999: 22.056 ms/op
                 existUser·p1.00:   24.379 ms/op

Iteration   3: 3.198 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.098 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  12.894 ms/op
                 existUser·p0.9999: 63.832 ms/op
                 existUser·p1.00:   73.794 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 298603
  mean =      3.209 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 292237 
    [ 5.000, 10.000) = 5796 
    [10.000, 15.000) = 309 
    [15.000, 20.000) = 106 
    [20.000, 25.000) = 135 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 18 
    [65.000, 70.000) = 0 
    [70.000, 75.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     13.376 ms/op
     p(99.9900) =     24.515 ms/op
     p(99.9990) =     63.898 ms/op
     p(99.9999) =     73.794 ms/op
    p(100.0000) =     73.794 ms/op


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
# Warmup Iteration   1: 7.465 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.376 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.361 ±(99.9%) 0.012 ms/op
Iteration   1: 3.352 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.333 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   6.603 ms/op
                 getUser·p0.999:  18.317 ms/op
                 getUser·p0.9999: 24.310 ms/op
                 getUser·p1.00:   24.740 ms/op

Iteration   2: 3.221 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.061 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   6.029 ms/op
                 getUser·p0.999:  16.101 ms/op
                 getUser·p0.9999: 23.137 ms/op
                 getUser·p1.00:   24.445 ms/op

Iteration   3: 3.316 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.274 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   6.365 ms/op
                 getUser·p0.999:  16.555 ms/op
                 getUser·p0.9999: 28.913 ms/op
                 getUser·p1.00:   29.458 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 291197
  mean =      3.296 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7519 
    [ 2.500,  5.000) = 274930 
    [ 5.000,  7.500) = 7476 
    [ 7.500, 10.000) = 669 
    [10.000, 12.500) = 253 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      6.349 ms/op
     p(99.9000) =     17.131 ms/op
     p(99.9900) =     27.055 ms/op
     p(99.9990) =     29.166 ms/op
     p(99.9999) =     29.458 ms/op
    p(100.0000) =     29.458 ms/op


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
# Warmup Iteration   1: 8.460 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.151 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.952 ±(99.9%) 0.014 ms/op
Iteration   1: 3.850 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.579 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.174 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   7.534 ms/op
                 listUser·p0.999:  15.712 ms/op
                 listUser·p0.9999: 22.315 ms/op
                 listUser·p1.00:   27.197 ms/op

Iteration   2: 3.863 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.642 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   7.537 ms/op
                 listUser·p0.999:  13.861 ms/op
                 listUser·p0.9999: 23.485 ms/op
                 listUser·p1.00:   23.921 ms/op

Iteration   3: 3.825 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.708 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.108 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   7.725 ms/op
                 listUser·p0.999:  12.665 ms/op
                 listUser·p0.9999: 24.617 ms/op
                 listUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249674
  mean =      3.846 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 130 
    [ 2.500,  5.000) = 240721 
    [ 5.000,  7.500) = 6096 
    [ 7.500, 10.000) = 1854 
    [10.000, 12.500) = 380 
    [12.500, 15.000) = 333 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.579 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      7.627 ms/op
     p(99.9000) =     13.861 ms/op
     p(99.9900) =     23.495 ms/op
     p(99.9990) =     27.230 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.504 ± 1.094  ops/ms
ClientPb.existUser                       thrpt       3   9.837 ± 2.161  ops/ms
ClientPb.getUser                         thrpt       3   9.694 ± 1.492  ops/ms
ClientPb.listUser                        thrpt       3   8.174 ± 1.564  ops/ms
ClientPb.createUser                       avgt       3   3.284 ± 1.260   ms/op
ClientPb.existUser                        avgt       3   3.175 ± 0.299   ms/op
ClientPb.getUser                          avgt       3   3.297 ± 0.489   ms/op
ClientPb.listUser                         avgt       3   3.889 ± 0.151   ms/op
ClientPb.createUser                     sample  283019   3.392 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.516           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.273           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.840           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.416           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.656           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.837           ms/op
ClientPb.existUser                      sample  298603   3.209 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.931           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.154           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.478           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.801           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.038           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.376           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.515           ms/op
ClientPb.existUser:existUser·p1.00      sample          73.794           ms/op
ClientPb.getUser                        sample  291197   3.296 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.061           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.625           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.998           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.349           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.131           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.055           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.458           ms/op
ClientPb.listUser                       sample  249674   3.846 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.579           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.686           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.166           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.627           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.861           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.495           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.263           ms/op
