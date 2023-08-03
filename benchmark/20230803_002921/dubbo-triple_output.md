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
# Warmup Iteration   1: 1.419 ops/ms
# Warmup Iteration   2: 3.432 ops/ms
# Warmup Iteration   3: 6.848 ops/ms
Iteration   1: 7.070 ops/ms
Iteration   2: 6.978 ops/ms
Iteration   3: 7.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.049 ±(99.9%) 1.150 ops/ms [Average]
  (min, avg, max) = (6.978, 7.049, 7.098), stdev = 0.063
  CI (99.9%): [5.898, 8.199] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.060 ops/ms
# Warmup Iteration   2: 6.293 ops/ms
# Warmup Iteration   3: 7.730 ops/ms
Iteration   1: 7.747 ops/ms
Iteration   2: 7.812 ops/ms
Iteration   3: 7.482 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.681 ±(99.9%) 3.189 ops/ms [Average]
  (min, avg, max) = (7.482, 7.681, 7.812), stdev = 0.175
  CI (99.9%): [4.492, 10.869] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.076 ops/ms
# Warmup Iteration   2: 5.805 ops/ms
# Warmup Iteration   3: 6.980 ops/ms
Iteration   1: 6.941 ops/ms
Iteration   2: 7.198 ops/ms
Iteration   3: 7.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.247 ±(99.9%) 6.074 ops/ms [Average]
  (min, avg, max) = (6.941, 7.247, 7.602), stdev = 0.333
  CI (99.9%): [1.173, 13.321] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.726 ops/ms
# Warmup Iteration   2: 4.373 ops/ms
# Warmup Iteration   3: 5.971 ops/ms
Iteration   1: 5.554 ops/ms
Iteration   2: 5.524 ops/ms
Iteration   3: 5.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.533 ±(99.9%) 0.326 ops/ms [Average]
  (min, avg, max) = (5.522, 5.533, 5.554), stdev = 0.018
  CI (99.9%): [5.207, 5.859] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 14.764 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 6.372 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.099 ±(99.9%) 0.006 ms/op
Iteration   1: 4.729 ±(99.9%) 0.010 ms/op
Iteration   2: 4.627 ±(99.9%) 0.014 ms/op
Iteration   3: 4.599 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.652 ±(99.9%) 1.248 ms/op [Average]
  (min, avg, max) = (4.599, 4.652, 4.729), stdev = 0.068
  CI (99.9%): [3.403, 5.900] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 14.946 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.030 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.279 ±(99.9%) 0.008 ms/op
Iteration   1: 4.139 ±(99.9%) 0.007 ms/op
Iteration   2: 4.531 ±(99.9%) 0.008 ms/op
Iteration   3: 4.233 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.301 ±(99.9%) 3.733 ms/op [Average]
  (min, avg, max) = (4.139, 4.301, 4.531), stdev = 0.205
  CI (99.9%): [0.568, 8.035] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 16.151 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 5.339 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.701 ±(99.9%) 0.006 ms/op
Iteration   1: 4.418 ±(99.9%) 0.006 ms/op
Iteration   2: 4.132 ±(99.9%) 0.011 ms/op
Iteration   3: 4.448 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.333 ±(99.9%) 3.182 ms/op [Average]
  (min, avg, max) = (4.132, 4.333, 4.448), stdev = 0.174
  CI (99.9%): [1.151, 7.514] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 15.804 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 6.551 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.406 ±(99.9%) 0.008 ms/op
Iteration   1: 5.338 ±(99.9%) 0.006 ms/op
Iteration   2: 5.414 ±(99.9%) 0.008 ms/op
Iteration   3: 5.096 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.283 ±(99.9%) 3.025 ms/op [Average]
  (min, avg, max) = (5.096, 5.283, 5.414), stdev = 0.166
  CI (99.9%): [2.257, 8.308] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 14.587 ±(99.9%) 0.198 ms/op
# Warmup Iteration   2: 6.249 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.074 ±(99.9%) 0.025 ms/op
Iteration   1: 4.725 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.931 ms/op
                 createUser·p0.50:   4.342 ms/op
                 createUser·p0.90:   6.046 ms/op
                 createUser·p0.95:   7.348 ms/op
                 createUser·p0.99:   10.650 ms/op
                 createUser·p0.999:  16.876 ms/op
                 createUser·p0.9999: 27.827 ms/op
                 createUser·p1.00:   28.475 ms/op

Iteration   2: 4.681 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.272 ms/op
                 createUser·p0.50:   4.358 ms/op
                 createUser·p0.90:   5.964 ms/op
                 createUser·p0.95:   6.906 ms/op
                 createUser·p0.99:   9.437 ms/op
                 createUser·p0.999:  16.716 ms/op
                 createUser·p0.9999: 36.492 ms/op
                 createUser·p1.00:   38.863 ms/op

Iteration   3: 4.355 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.679 ms/op
                 createUser·p0.50:   4.026 ms/op
                 createUser·p0.90:   5.448 ms/op
                 createUser·p0.95:   6.398 ms/op
                 createUser·p0.99:   8.184 ms/op
                 createUser·p0.999:  18.860 ms/op
                 createUser·p0.9999: 32.185 ms/op
                 createUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 209567
  mean =      4.581 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 214 
    [ 2.500,  5.000) = 166959 
    [ 5.000,  7.500) = 35520 
    [ 7.500, 10.000) = 5167 
    [10.000, 12.500) = 1149 
    [12.500, 15.000) = 274 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      4.235 ms/op
     p(90.0000) =      5.833 ms/op
     p(95.0000) =      6.824 ms/op
     p(99.0000) =      9.650 ms/op
     p(99.9000) =     18.809 ms/op
     p(99.9900) =     35.914 ms/op
     p(99.9990) =     38.413 ms/op
     p(99.9999) =     38.863 ms/op
    p(100.0000) =     38.863 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.358 ±(99.9%) 0.222 ms/op
# Warmup Iteration   2: 4.953 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.629 ±(99.9%) 0.017 ms/op
Iteration   1: 4.280 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.405 ms/op
                 existUser·p0.50:   3.973 ms/op
                 existUser·p0.90:   5.431 ms/op
                 existUser·p0.95:   6.636 ms/op
                 existUser·p0.99:   8.913 ms/op
                 existUser·p0.999:  13.491 ms/op
                 existUser·p0.9999: 25.478 ms/op
                 existUser·p1.00:   26.051 ms/op

Iteration   2: 4.175 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.400 ms/op
                 existUser·p0.50:   3.871 ms/op
                 existUser·p0.90:   5.128 ms/op
                 existUser·p0.95:   5.997 ms/op
                 existUser·p0.99:   8.307 ms/op
                 existUser·p0.999:  13.792 ms/op
                 existUser·p0.9999: 35.870 ms/op
                 existUser·p1.00:   36.569 ms/op

Iteration   3: 4.068 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.021 ms/op
                 existUser·p0.50:   3.760 ms/op
                 existUser·p0.90:   4.751 ms/op
                 existUser·p0.95:   6.005 ms/op
                 existUser·p0.99:   8.158 ms/op
                 existUser·p0.999:  28.816 ms/op
                 existUser·p0.9999: 32.805 ms/op
                 existUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 229983
  mean =      4.172 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 179 
    [ 2.500,  5.000) = 204542 
    [ 5.000,  7.500) = 20578 
    [ 7.500, 10.000) = 3379 
    [10.000, 12.500) = 887 
    [12.500, 15.000) = 152 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 71 
    [30.000, 32.500) = 45 
    [32.500, 35.000) = 34 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.400 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      6.275 ms/op
     p(99.0000) =      8.503 ms/op
     p(99.9000) =     19.497 ms/op
     p(99.9900) =     33.620 ms/op
     p(99.9990) =     36.464 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


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
# Warmup Iteration   1: 13.982 ±(99.9%) 0.193 ms/op
# Warmup Iteration   2: 5.062 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.309 ±(99.9%) 0.015 ms/op
Iteration   1: 4.189 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.921 ms/op
                 getUser·p0.50:   3.953 ms/op
                 getUser·p0.90:   4.538 ms/op
                 getUser·p0.95:   5.931 ms/op
                 getUser·p0.99:   9.241 ms/op
                 getUser·p0.999:  22.438 ms/op
                 getUser·p0.9999: 25.059 ms/op
                 getUser·p1.00:   25.887 ms/op

Iteration   2: 4.336 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.249 ms/op
                 getUser·p0.50:   4.059 ms/op
                 getUser·p0.90:   5.202 ms/op
                 getUser·p0.95:   6.210 ms/op
                 getUser·p0.99:   8.798 ms/op
                 getUser·p0.999:  12.768 ms/op
                 getUser·p0.9999: 30.659 ms/op
                 getUser·p1.00:   30.999 ms/op

Iteration   3: 4.400 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.314 ms/op
                 getUser·p0.50:   4.129 ms/op
                 getUser·p0.90:   5.276 ms/op
                 getUser·p0.95:   6.627 ms/op
                 getUser·p0.99:   8.667 ms/op
                 getUser·p0.999:  15.985 ms/op
                 getUser·p0.9999: 31.261 ms/op
                 getUser·p1.00:   32.571 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 222720
  mean =      4.307 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 199671 
    [ 5.000,  7.500) = 17543 
    [ 7.500, 10.000) = 4276 
    [10.000, 12.500) = 829 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.921 ms/op
     p(50.0000) =      4.043 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      6.365 ms/op
     p(99.0000) =      8.946 ms/op
     p(99.9000) =     21.383 ms/op
     p(99.9900) =     30.629 ms/op
     p(99.9990) =     31.781 ms/op
     p(99.9999) =     32.571 ms/op
    p(100.0000) =     32.571 ms/op


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
# Warmup Iteration   1: 15.531 ±(99.9%) 0.220 ms/op
# Warmup Iteration   2: 6.298 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.495 ±(99.9%) 0.021 ms/op
Iteration   1: 5.268 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.060 ms/op
                 listUser·p0.50:   4.801 ms/op
                 listUser·p0.90:   6.513 ms/op
                 listUser·p0.95:   8.053 ms/op
                 listUser·p0.99:   11.223 ms/op
                 listUser·p0.999:  26.536 ms/op
                 listUser·p0.9999: 29.449 ms/op
                 listUser·p1.00:   30.507 ms/op

Iteration   2: 5.190 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.744 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   6.619 ms/op
                 listUser·p0.95:   8.126 ms/op
                 listUser·p0.99:   10.945 ms/op
                 listUser·p0.999:  24.581 ms/op
                 listUser·p0.9999: 28.094 ms/op
                 listUser·p1.00:   29.065 ms/op

Iteration   3: 4.929 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.800 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   5.456 ms/op
                 listUser·p0.95:   6.799 ms/op
                 listUser·p0.99:   9.880 ms/op
                 listUser·p0.999:  20.098 ms/op
                 listUser·p0.9999: 24.330 ms/op
                 listUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 187357
  mean =      5.124 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 126077 
    [ 5.000,  7.500) = 50504 
    [ 7.500, 10.000) = 8093 
    [10.000, 12.500) = 1923 
    [12.500, 15.000) = 282 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 101 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.800 ms/op
     p(50.0000) =      4.710 ms/op
     p(90.0000) =      6.193 ms/op
     p(95.0000) =      7.840 ms/op
     p(99.0000) =     10.755 ms/op
     p(99.9000) =     24.323 ms/op
     p(99.9900) =     29.065 ms/op
     p(99.9990) =     30.020 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.049 ± 1.150  ops/ms
ClientPb.existUser                       thrpt       3   7.681 ± 3.189  ops/ms
ClientPb.getUser                         thrpt       3   7.247 ± 6.074  ops/ms
ClientPb.listUser                        thrpt       3   5.533 ± 0.326  ops/ms
ClientPb.createUser                       avgt       3   4.652 ± 1.248   ms/op
ClientPb.existUser                        avgt       3   4.301 ± 3.733   ms/op
ClientPb.getUser                          avgt       3   4.333 ± 3.182   ms/op
ClientPb.listUser                         avgt       3   5.283 ± 3.025   ms/op
ClientPb.createUser                     sample  209567   4.581 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.679           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.235           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.833           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.824           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.650           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.809           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.914           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.863           ms/op
ClientPb.existUser                      sample  229983   4.172 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.400           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.867           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.112           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.275           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.503           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.497           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.620           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.569           ms/op
ClientPb.getUser                        sample  222720   4.307 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.921           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.043           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.038           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.365           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.946           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.383           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.629           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.571           ms/op
ClientPb.listUser                       sample  187357   5.124 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.800           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.193           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.840           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.755           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.323           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.065           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.507           ms/op
