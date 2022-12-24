# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.123 ops/ms
# Warmup Iteration   2: 5.204 ops/ms
# Warmup Iteration   3: 8.471 ops/ms
Iteration   1: 8.937 ops/ms
Iteration   2: 9.581 ops/ms
Iteration   3: 9.287 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.268 ±(99.9%) 5.879 ops/ms [Average]
  (min, avg, max) = (8.937, 9.268, 9.581), stdev = 0.322
  CI (99.9%): [3.389, 15.148] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.892 ops/ms
# Warmup Iteration   2: 8.435 ops/ms
# Warmup Iteration   3: 9.469 ops/ms
Iteration   1: 9.781 ops/ms
Iteration   2: 9.387 ops/ms
Iteration   3: 9.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.582 ±(99.9%) 3.597 ops/ms [Average]
  (min, avg, max) = (9.387, 9.582, 9.781), stdev = 0.197
  CI (99.9%): [5.985, 13.179] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.430 ops/ms
# Warmup Iteration   2: 8.593 ops/ms
# Warmup Iteration   3: 8.727 ops/ms
Iteration   1: 9.471 ops/ms
Iteration   2: 9.703 ops/ms
Iteration   3: 9.341 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.505 ±(99.9%) 3.349 ops/ms [Average]
  (min, avg, max) = (9.341, 9.505, 9.703), stdev = 0.184
  CI (99.9%): [6.156, 12.853] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.524 ops/ms
# Warmup Iteration   2: 6.893 ops/ms
# Warmup Iteration   3: 7.424 ops/ms
Iteration   1: 7.874 ops/ms
Iteration   2: 8.049 ops/ms
Iteration   3: 7.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.851 ±(99.9%) 3.857 ops/ms [Average]
  (min, avg, max) = (7.628, 7.851, 8.049), stdev = 0.211
  CI (99.9%): [3.993, 11.708] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.944 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.800 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.545 ±(99.9%) 0.006 ms/op
Iteration   1: 3.433 ±(99.9%) 0.010 ms/op
Iteration   2: 3.336 ±(99.9%) 0.008 ms/op
Iteration   3: 3.289 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.353 ±(99.9%) 1.343 ms/op [Average]
  (min, avg, max) = (3.289, 3.353, 3.433), stdev = 0.074
  CI (99.9%): [2.010, 4.696] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 10.069 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.600 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.337 ±(99.9%) 0.010 ms/op
Iteration   1: 3.426 ±(99.9%) 0.011 ms/op
Iteration   2: 3.273 ±(99.9%) 0.006 ms/op
Iteration   3: 3.373 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.357 ±(99.9%) 1.419 ms/op [Average]
  (min, avg, max) = (3.273, 3.357, 3.426), stdev = 0.078
  CI (99.9%): [1.938, 4.776] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.070 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.747 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.722 ±(99.9%) 0.006 ms/op
Iteration   1: 3.532 ±(99.9%) 0.004 ms/op
Iteration   2: 3.454 ±(99.9%) 0.005 ms/op
Iteration   3: 3.350 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.445 ±(99.9%) 1.673 ms/op [Average]
  (min, avg, max) = (3.350, 3.445, 3.532), stdev = 0.092
  CI (99.9%): [1.772, 5.119] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 12.091 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.490 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.307 ±(99.9%) 0.006 ms/op
Iteration   1: 4.057 ±(99.9%) 0.008 ms/op
Iteration   2: 4.043 ±(99.9%) 0.014 ms/op
Iteration   3: 3.923 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.007 ±(99.9%) 1.335 ms/op [Average]
  (min, avg, max) = (3.923, 4.007, 4.057), stdev = 0.073
  CI (99.9%): [2.673, 5.342] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.861 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.023 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.561 ±(99.9%) 0.011 ms/op
Iteration   1: 3.466 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.677 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   4.006 ms/op
                 createUser·p0.95:   4.850 ms/op
                 createUser·p0.99:   6.103 ms/op
                 createUser·p0.999:  10.781 ms/op
                 createUser·p0.9999: 22.471 ms/op
                 createUser·p1.00:   22.938 ms/op

Iteration   2: 3.401 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.589 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  9.584 ms/op
                 createUser·p0.9999: 27.282 ms/op
                 createUser·p1.00:   29.721 ms/op

Iteration   3: 3.481 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.845 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.043 ms/op
                 createUser·p0.95:   4.465 ms/op
                 createUser·p0.99:   6.275 ms/op
                 createUser·p0.999:  16.189 ms/op
                 createUser·p0.9999: 25.520 ms/op
                 createUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278214
  mean =      3.449 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8930 
    [ 2.500,  5.000) = 261251 
    [ 5.000,  7.500) = 7105 
    [ 7.500, 10.000) = 518 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      1.589 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     11.264 ms/op
     p(99.9900) =     25.702 ms/op
     p(99.9990) =     29.487 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.004 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.556 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.375 ±(99.9%) 0.010 ms/op
Iteration   1: 3.257 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.542 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  9.840 ms/op
                 existUser·p0.9999: 27.832 ms/op
                 existUser·p1.00:   28.377 ms/op

Iteration   2: 3.347 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.470 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   4.084 ms/op
                 existUser·p0.99:   6.128 ms/op
                 existUser·p0.999:  22.106 ms/op
                 existUser·p0.9999: 25.688 ms/op
                 existUser·p1.00:   27.722 ms/op

Iteration   3: 3.289 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.198 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   5.612 ms/op
                 existUser·p0.999:  12.386 ms/op
                 existUser·p0.9999: 25.297 ms/op
                 existUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290758
  mean =      3.297 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10133 
    [ 2.500,  5.000) = 275241 
    [ 5.000,  7.500) = 4479 
    [ 7.500, 10.000) = 484 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 165 
    [25.000, 27.500) = 53 

  Percentiles, ms/op:
      p(0.0000) =      1.198 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     12.288 ms/op
     p(99.9900) =     27.031 ms/op
     p(99.9990) =     28.282 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.351 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.782 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.597 ±(99.9%) 0.011 ms/op
Iteration   1: 3.601 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.550 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   5.194 ms/op
                 getUser·p0.99:   7.578 ms/op
                 getUser·p0.999:  21.234 ms/op
                 getUser·p0.9999: 24.073 ms/op
                 getUser·p1.00:   25.625 ms/op

Iteration   2: 3.432 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.231 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   5.792 ms/op
                 getUser·p0.999:  21.885 ms/op
                 getUser·p0.9999: 29.284 ms/op
                 getUser·p1.00:   29.786 ms/op

Iteration   3: 3.723 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.516 ms/op
                 getUser·p0.50:   3.539 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   5.194 ms/op
                 getUser·p0.99:   6.627 ms/op
                 getUser·p0.999:  19.429 ms/op
                 getUser·p0.9999: 29.157 ms/op
                 getUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 267839
  mean =      3.581 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2638 
    [ 2.500,  5.000) = 253190 
    [ 5.000,  7.500) = 10277 
    [ 7.500, 10.000) = 1220 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.231 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     19.961 ms/op
     p(99.9900) =     28.974 ms/op
     p(99.9990) =     29.676 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.655 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 4.497 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.178 ±(99.9%) 0.013 ms/op
Iteration   1: 4.201 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.105 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.128 ms/op
                 listUser·p0.99:   8.315 ms/op
                 listUser·p0.999:  19.922 ms/op
                 listUser·p0.9999: 26.018 ms/op
                 listUser·p1.00:   26.477 ms/op

Iteration   2: 3.967 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  16.275 ms/op
                 listUser·p0.9999: 21.594 ms/op
                 listUser·p1.00:   23.593 ms/op

Iteration   3: 4.110 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.359 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.998 ms/op
                 listUser·p0.999:  18.645 ms/op
                 listUser·p0.9999: 23.993 ms/op
                 listUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234545
  mean =      4.091 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 224659 
    [ 5.000,  7.500) = 7174 
    [ 7.500, 10.000) = 1725 
    [10.000, 12.500) = 409 
    [12.500, 15.000) = 177 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 142 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      2.105 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      7.856 ms/op
     p(99.9000) =     18.612 ms/op
     p(99.9900) =     24.105 ms/op
     p(99.9990) =     26.431 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.268 ± 5.879  ops/ms
ClientPb.existUser                       thrpt       3   9.582 ± 3.597  ops/ms
ClientPb.getUser                         thrpt       3   9.505 ± 3.349  ops/ms
ClientPb.listUser                        thrpt       3   7.851 ± 3.857  ops/ms
ClientPb.createUser                       avgt       3   3.353 ± 1.343   ms/op
ClientPb.existUser                        avgt       3   3.357 ± 1.419   ms/op
ClientPb.getUser                          avgt       3   3.445 ± 1.673   ms/op
ClientPb.listUser                         avgt       3   4.007 ± 1.335   ms/op
ClientPb.createUser                     sample  278214   3.449 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.589           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.346           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.928           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.366           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.029           ms/op
ClientPb.createUser:createUser·p0.999   sample          11.264           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.702           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.721           ms/op
ClientPb.existUser                      sample  290758   3.297 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.198           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.203           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.617           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.912           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.693           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.288           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.031           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.377           ms/op
ClientPb.getUser                        sample  267839   3.581 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.231           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.400           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.735           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.955           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.961           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.974           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.786           ms/op
ClientPb.listUser                       sample  234545   4.091 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.105           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.841           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.856           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.612           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.105           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.477           ms/op
