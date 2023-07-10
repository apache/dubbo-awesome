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
# Warmup Iteration   1: 2.548 ops/ms
# Warmup Iteration   2: 6.613 ops/ms
# Warmup Iteration   3: 8.706 ops/ms
Iteration   1: 9.900 ops/ms
Iteration   2: 9.840 ops/ms
Iteration   3: 9.889 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.876 ±(99.9%) 0.581 ops/ms [Average]
  (min, avg, max) = (9.840, 9.876, 9.900), stdev = 0.032
  CI (99.9%): [9.295, 10.457] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.305 ops/ms
# Warmup Iteration   2: 9.308 ops/ms
# Warmup Iteration   3: 9.766 ops/ms
Iteration   1: 9.975 ops/ms
Iteration   2: 10.339 ops/ms
Iteration   3: 10.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.260 ±(99.9%) 4.656 ops/ms [Average]
  (min, avg, max) = (9.975, 10.260, 10.466), stdev = 0.255
  CI (99.9%): [5.604, 14.916] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.504 ops/ms
# Warmup Iteration   2: 9.124 ops/ms
# Warmup Iteration   3: 9.857 ops/ms
Iteration   1: 9.715 ops/ms
Iteration   2: 10.107 ops/ms
Iteration   3: 9.830 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.884 ±(99.9%) 3.672 ops/ms [Average]
  (min, avg, max) = (9.715, 9.884, 10.107), stdev = 0.201
  CI (99.9%): [6.212, 13.556] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.986 ops/ms
# Warmup Iteration   2: 7.722 ops/ms
# Warmup Iteration   3: 8.337 ops/ms
Iteration   1: 8.503 ops/ms
Iteration   2: 8.323 ops/ms
Iteration   3: 8.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.526 ±(99.9%) 3.921 ops/ms [Average]
  (min, avg, max) = (8.323, 8.526, 8.751), stdev = 0.215
  CI (99.9%): [4.605, 12.447] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.050 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 3.608 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.427 ±(99.9%) 0.002 ms/op
Iteration   1: 3.103 ±(99.9%) 0.006 ms/op
Iteration   2: 3.187 ±(99.9%) 0.003 ms/op
Iteration   3: 3.224 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.171 ±(99.9%) 1.128 ms/op [Average]
  (min, avg, max) = (3.103, 3.171, 3.224), stdev = 0.062
  CI (99.9%): [2.043, 4.299] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.960 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.410 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.130 ±(99.9%) 0.004 ms/op
Iteration   1: 3.066 ±(99.9%) 0.002 ms/op
Iteration   2: 3.091 ±(99.9%) 0.008 ms/op
Iteration   3: 3.043 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.067 ±(99.9%) 0.439 ms/op [Average]
  (min, avg, max) = (3.043, 3.067, 3.091), stdev = 0.024
  CI (99.9%): [2.628, 3.506] (assumes normal distribution)


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
# Warmup Iteration   1: 7.858 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.437 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.206 ±(99.9%) 0.004 ms/op
Iteration   1: 3.368 ±(99.9%) 0.005 ms/op
Iteration   2: 3.153 ±(99.9%) 0.008 ms/op
Iteration   3: 3.197 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.239 ±(99.9%) 2.065 ms/op [Average]
  (min, avg, max) = (3.153, 3.239, 3.368), stdev = 0.113
  CI (99.9%): [1.175, 5.304] (assumes normal distribution)


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
# Warmup Iteration   1: 9.637 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.350 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.851 ±(99.9%) 0.009 ms/op
Iteration   1: 3.752 ±(99.9%) 0.010 ms/op
Iteration   2: 3.754 ±(99.9%) 0.011 ms/op
Iteration   3: 3.717 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.741 ±(99.9%) 0.379 ms/op [Average]
  (min, avg, max) = (3.717, 3.741, 3.754), stdev = 0.021
  CI (99.9%): [3.362, 4.121] (assumes normal distribution)


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
# Warmup Iteration   1: 8.503 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.795 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.351 ±(99.9%) 0.010 ms/op
Iteration   1: 3.204 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.303 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.342 ms/op
                 createUser·p0.95:   3.543 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  19.825 ms/op
                 createUser·p0.9999: 24.282 ms/op
                 createUser·p1.00:   25.100 ms/op

Iteration   2: 3.325 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.597 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   6.456 ms/op
                 createUser·p0.999:  15.570 ms/op
                 createUser·p0.9999: 22.196 ms/op
                 createUser·p1.00:   22.643 ms/op

Iteration   3: 3.219 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.505 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  13.413 ms/op
                 createUser·p0.9999: 19.038 ms/op
                 createUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295406
  mean =      3.249 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17833 
    [ 2.500,  5.000) = 271985 
    [ 5.000,  7.500) = 4651 
    [ 7.500, 10.000) = 522 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.303 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     15.774 ms/op
     p(99.9900) =     23.298 ms/op
     p(99.9990) =     25.003 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


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
# Warmup Iteration   1: 7.917 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.440 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.313 ±(99.9%) 0.007 ms/op
Iteration   1: 3.051 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.976 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.428 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  11.502 ms/op
                 existUser·p0.9999: 21.185 ms/op
                 existUser·p1.00:   22.643 ms/op

Iteration   2: 3.109 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.499 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  12.632 ms/op
                 existUser·p0.9999: 24.206 ms/op
                 existUser·p1.00:   24.936 ms/op

Iteration   3: 3.142 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.241 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   5.685 ms/op
                 existUser·p0.999:  15.153 ms/op
                 existUser·p0.9999: 22.637 ms/op
                 existUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309600
  mean =      3.100 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14856 
    [ 2.500,  5.000) = 289785 
    [ 5.000,  7.500) = 3880 
    [ 7.500, 10.000) = 533 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.314 ms/op
     p(95.0000) =      3.518 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     13.851 ms/op
     p(99.9900) =     23.202 ms/op
     p(99.9990) =     24.871 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


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
# Warmup Iteration   1: 7.939 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.526 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.271 ±(99.9%) 0.008 ms/op
Iteration   1: 3.417 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.280 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   6.472 ms/op
                 getUser·p0.999:  20.819 ms/op
                 getUser·p0.9999: 31.982 ms/op
                 getUser·p1.00:   32.408 ms/op

Iteration   2: 3.232 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.413 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   5.554 ms/op
                 getUser·p0.999:  11.456 ms/op
                 getUser·p0.9999: 23.433 ms/op
                 getUser·p1.00:   24.871 ms/op

Iteration   3: 3.305 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.061 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   5.934 ms/op
                 getUser·p0.999:  18.967 ms/op
                 getUser·p0.9999: 34.865 ms/op
                 getUser·p1.00:   35.914 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 289748
  mean =      3.316 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21115 
    [ 2.500,  5.000) = 261489 
    [ 5.000,  7.500) = 6069 
    [ 7.500, 10.000) = 612 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 173 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =     19.792 ms/op
     p(99.9900) =     33.363 ms/op
     p(99.9990) =     35.357 ms/op
     p(99.9999) =     35.914 ms/op
    p(100.0000) =     35.914 ms/op


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
# Warmup Iteration   1: 8.645 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.057 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.798 ±(99.9%) 0.010 ms/op
Iteration   1: 3.851 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.536 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   7.504 ms/op
                 listUser·p0.999:  15.922 ms/op
                 listUser·p0.9999: 31.068 ms/op
                 listUser·p1.00:   31.916 ms/op

Iteration   2: 3.789 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.956 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.092 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   6.848 ms/op
                 listUser·p0.999:  14.418 ms/op
                 listUser·p0.9999: 19.890 ms/op
                 listUser·p1.00:   21.889 ms/op

Iteration   3: 3.724 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.218 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  14.205 ms/op
                 listUser·p0.9999: 16.908 ms/op
                 listUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253542
  mean =      3.787 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 66 
    [ 2.500,  5.000) = 244894 
    [ 5.000,  7.500) = 6615 
    [ 7.500, 10.000) = 1204 
    [10.000, 12.500) = 215 
    [12.500, 15.000) = 316 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.536 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     14.622 ms/op
     p(99.9900) =     27.886 ms/op
     p(99.9990) =     31.833 ms/op
     p(99.9999) =     31.916 ms/op
    p(100.0000) =     31.916 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.876 ± 0.581  ops/ms
ClientPb.existUser                       thrpt       3  10.260 ± 4.656  ops/ms
ClientPb.getUser                         thrpt       3   9.884 ± 3.672  ops/ms
ClientPb.listUser                        thrpt       3   8.526 ± 3.921  ops/ms
ClientPb.createUser                       avgt       3   3.171 ± 1.128   ms/op
ClientPb.existUser                        avgt       3   3.067 ± 0.439   ms/op
ClientPb.getUser                          avgt       3   3.239 ± 2.065   ms/op
ClientPb.listUser                         avgt       3   3.741 ± 0.379   ms/op
ClientPb.createUser                     sample  295406   3.249 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.303           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.559           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.956           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.774           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.298           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.100           ms/op
ClientPb.existUser                      sample  309600   3.100 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.976           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.314           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.518           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.505           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.851           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.202           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.936           ms/op
ClientPb.getUser                        sample  289748   3.316 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.061           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.232           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.785           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.190           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.021           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.792           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.363           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.914           ms/op
ClientPb.listUser                       sample  253542   3.787 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.536           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.621           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.112           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.086           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.622           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.886           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.916           ms/op
