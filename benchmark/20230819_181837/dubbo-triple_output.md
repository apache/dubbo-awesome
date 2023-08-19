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
# Warmup Iteration   1: 2.183 ops/ms
# Warmup Iteration   2: 5.169 ops/ms
# Warmup Iteration   3: 8.368 ops/ms
Iteration   1: 8.847 ops/ms
Iteration   2: 9.209 ops/ms
Iteration   3: 9.436 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.164 ±(99.9%) 5.417 ops/ms [Average]
  (min, avg, max) = (8.847, 9.164, 9.436), stdev = 0.297
  CI (99.9%): [3.747, 14.581] (assumes normal distribution)


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
# Warmup Iteration   1: 3.233 ops/ms
# Warmup Iteration   2: 8.279 ops/ms
# Warmup Iteration   3: 9.443 ops/ms
Iteration   1: 9.278 ops/ms
Iteration   2: 9.557 ops/ms
Iteration   3: 9.313 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.383 ±(99.9%) 2.767 ops/ms [Average]
  (min, avg, max) = (9.278, 9.383, 9.557), stdev = 0.152
  CI (99.9%): [6.616, 12.150] (assumes normal distribution)


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
# Warmup Iteration   1: 3.031 ops/ms
# Warmup Iteration   2: 8.867 ops/ms
# Warmup Iteration   3: 9.026 ops/ms
Iteration   1: 9.294 ops/ms
Iteration   2: 9.213 ops/ms
Iteration   3: 9.351 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.286 ±(99.9%) 1.264 ops/ms [Average]
  (min, avg, max) = (9.213, 9.286, 9.351), stdev = 0.069
  CI (99.9%): [8.022, 10.550] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.654 ops/ms
# Warmup Iteration   2: 7.206 ops/ms
# Warmup Iteration   3: 8.012 ops/ms
Iteration   1: 7.804 ops/ms
Iteration   2: 7.757 ops/ms
Iteration   3: 7.899 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.820 ±(99.9%) 1.319 ops/ms [Average]
  (min, avg, max) = (7.757, 7.820, 7.899), stdev = 0.072
  CI (99.9%): [6.501, 9.139] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 10.337 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.824 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.614 ±(99.9%) 0.005 ms/op
Iteration   1: 3.404 ±(99.9%) 0.008 ms/op
Iteration   2: 3.442 ±(99.9%) 0.006 ms/op
Iteration   3: 3.484 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.443 ±(99.9%) 0.736 ms/op [Average]
  (min, avg, max) = (3.404, 3.443, 3.484), stdev = 0.040
  CI (99.9%): [2.707, 4.180] (assumes normal distribution)


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
# Warmup Iteration   1: 9.941 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.641 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.369 ±(99.9%) 0.003 ms/op
Iteration   1: 3.307 ±(99.9%) 0.003 ms/op
Iteration   2: 3.362 ±(99.9%) 0.004 ms/op
Iteration   3: 3.334 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.334 ±(99.9%) 0.501 ms/op [Average]
  (min, avg, max) = (3.307, 3.334, 3.362), stdev = 0.027
  CI (99.9%): [2.833, 3.835] (assumes normal distribution)


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
# Warmup Iteration   1: 9.218 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.682 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.566 ±(99.9%) 0.007 ms/op
Iteration   1: 3.572 ±(99.9%) 0.007 ms/op
Iteration   2: 3.441 ±(99.9%) 0.006 ms/op
Iteration   3: 3.435 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.483 ±(99.9%) 1.422 ms/op [Average]
  (min, avg, max) = (3.435, 3.483, 3.572), stdev = 0.078
  CI (99.9%): [2.060, 4.905] (assumes normal distribution)


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
# Warmup Iteration   1: 9.796 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.543 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.106 ±(99.9%) 0.010 ms/op
Iteration   1: 4.095 ±(99.9%) 0.008 ms/op
Iteration   2: 4.187 ±(99.9%) 0.004 ms/op
Iteration   3: 4.144 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.142 ±(99.9%) 0.839 ms/op [Average]
  (min, avg, max) = (4.095, 4.142, 4.187), stdev = 0.046
  CI (99.9%): [3.303, 4.981] (assumes normal distribution)


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
# Warmup Iteration   1: 10.050 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.186 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.602 ±(99.9%) 0.012 ms/op
Iteration   1: 3.664 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.370 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.448 ms/op
                 createUser·p0.95:   5.874 ms/op
                 createUser·p0.99:   7.640 ms/op
                 createUser·p0.999:  16.659 ms/op
                 createUser·p0.9999: 33.817 ms/op
                 createUser·p1.00:   35.127 ms/op

Iteration   2: 3.417 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.425 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.153 ms/op
                 createUser·p0.99:   6.701 ms/op
                 createUser·p0.999:  22.458 ms/op
                 createUser·p0.9999: 27.502 ms/op
                 createUser·p1.00:   28.180 ms/op

Iteration   3: 3.364 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.368 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   5.816 ms/op
                 createUser·p0.999:  23.362 ms/op
                 createUser·p0.9999: 31.490 ms/op
                 createUser·p1.00:   34.341 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275917
  mean =      3.477 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7990 
    [ 2.500,  5.000) = 256049 
    [ 5.000,  7.500) = 9829 
    [ 7.500, 10.000) = 1282 
    [10.000, 12.500) = 299 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.368 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     20.485 ms/op
     p(99.9900) =     31.490 ms/op
     p(99.9990) =     34.897 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


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
# Warmup Iteration   1: 7.582 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.555 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.456 ±(99.9%) 0.009 ms/op
Iteration   1: 3.428 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.640 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.961 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   6.021 ms/op
                 existUser·p0.999:  13.116 ms/op
                 existUser·p0.9999: 20.665 ms/op
                 existUser·p1.00:   21.004 ms/op

Iteration   2: 3.362 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.341 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   6.398 ms/op
                 existUser·p0.999:  19.726 ms/op
                 existUser·p0.9999: 22.348 ms/op
                 existUser·p1.00:   22.905 ms/op

Iteration   3: 3.309 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.624 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   6.226 ms/op
                 existUser·p0.999:  16.542 ms/op
                 existUser·p0.9999: 26.947 ms/op
                 existUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285022
  mean =      3.366 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18082 
    [ 2.500,  5.000) = 258572 
    [ 5.000,  7.500) = 6821 
    [ 7.500, 10.000) = 1046 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 137 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.341 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.218 ms/op
     p(99.9000) =     14.057 ms/op
     p(99.9900) =     24.510 ms/op
     p(99.9990) =     27.076 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


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
# Warmup Iteration   1: 9.717 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.699 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.580 ±(99.9%) 0.010 ms/op
Iteration   1: 3.545 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.622 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   8.004 ms/op
                 getUser·p0.999:  20.840 ms/op
                 getUser·p0.9999: 27.094 ms/op
                 getUser·p1.00:   29.065 ms/op

Iteration   2: 3.442 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.192 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   6.488 ms/op
                 getUser·p0.999:  21.861 ms/op
                 getUser·p0.9999: 24.656 ms/op
                 getUser·p1.00:   25.592 ms/op

Iteration   3: 3.524 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.751 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   6.773 ms/op
                 getUser·p0.999:  19.470 ms/op
                 getUser·p0.9999: 25.742 ms/op
                 getUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273875
  mean =      3.503 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2925 
    [ 2.500,  5.000) = 260830 
    [ 5.000,  7.500) = 7930 
    [ 7.500, 10.000) = 1465 
    [10.000, 12.500) = 319 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 112 
    [25.000, 27.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      1.192 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     20.087 ms/op
     p(99.9900) =     25.947 ms/op
     p(99.9990) =     27.488 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


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
# Warmup Iteration   1: 11.192 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 4.631 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.213 ±(99.9%) 0.015 ms/op
Iteration   1: 4.063 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.712 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   7.995 ms/op
                 listUser·p0.999:  20.916 ms/op
                 listUser·p0.9999: 24.626 ms/op
                 listUser·p1.00:   26.411 ms/op

Iteration   2: 4.276 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.972 ms/op
                 listUser·p0.50:   4.141 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.161 ms/op
                 listUser·p0.99:   8.225 ms/op
                 listUser·p0.999:  20.283 ms/op
                 listUser·p0.9999: 23.627 ms/op
                 listUser·p1.00:   24.838 ms/op

Iteration   3: 4.141 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   5.333 ms/op
                 listUser·p0.99:   8.143 ms/op
                 listUser·p0.999:  13.577 ms/op
                 listUser·p0.9999: 16.732 ms/op
                 listUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 230792
  mean =      4.158 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 218289 
    [ 5.000,  7.500) = 9183 
    [ 7.500, 10.000) = 2304 
    [10.000, 12.500) = 485 
    [12.500, 15.000) = 157 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.712 ms/op
     p(50.0000) =      3.985 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.104 ms/op
     p(99.0000) =      8.135 ms/op
     p(99.9000) =     17.341 ms/op
     p(99.9900) =     24.180 ms/op
     p(99.9990) =     25.685 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.164 ± 5.417  ops/ms
ClientPb.existUser                       thrpt       3   9.383 ± 2.767  ops/ms
ClientPb.getUser                         thrpt       3   9.286 ± 1.264  ops/ms
ClientPb.listUser                        thrpt       3   7.820 ± 1.319  ops/ms
ClientPb.createUser                       avgt       3   3.443 ± 0.736   ms/op
ClientPb.existUser                        avgt       3   3.334 ± 0.501   ms/op
ClientPb.getUser                          avgt       3   3.483 ± 1.422   ms/op
ClientPb.listUser                         avgt       3   4.142 ± 0.839   ms/op
ClientPb.createUser                     sample  275917   3.477 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.368           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.289           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.912           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.604           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.119           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.485           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.490           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.127           ms/op
ClientPb.existUser                      sample  285022   3.366 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.341           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.273           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.243           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.218           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.057           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.510           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.361           ms/op
ClientPb.getUser                        sample  273875   3.503 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.192           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.243           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.143           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.087           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.947           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.065           ms/op
ClientPb.listUser                       sample  230792   4.158 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.712           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.985           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.104           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.135           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.341           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.180           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.411           ms/op
