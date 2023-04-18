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
# Warmup Iteration   1: 2.227 ops/ms
# Warmup Iteration   2: 5.212 ops/ms
# Warmup Iteration   3: 8.796 ops/ms
Iteration   1: 9.374 ops/ms
Iteration   2: 9.405 ops/ms
Iteration   3: 9.335 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.372 ±(99.9%) 0.639 ops/ms [Average]
  (min, avg, max) = (9.335, 9.372, 9.405), stdev = 0.035
  CI (99.9%): [8.733, 10.010] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.185 ops/ms
# Warmup Iteration   2: 8.464 ops/ms
# Warmup Iteration   3: 9.293 ops/ms
Iteration   1: 10.263 ops/ms
Iteration   2: 9.810 ops/ms
Iteration   3: 9.567 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.880 ±(99.9%) 6.444 ops/ms [Average]
  (min, avg, max) = (9.567, 9.880, 10.263), stdev = 0.353
  CI (99.9%): [3.436, 16.323] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.993 ops/ms
# Warmup Iteration   2: 8.191 ops/ms
# Warmup Iteration   3: 9.366 ops/ms
Iteration   1: 9.558 ops/ms
Iteration   2: 9.416 ops/ms
Iteration   3: 9.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.541 ±(99.9%) 2.132 ops/ms [Average]
  (min, avg, max) = (9.416, 9.541, 9.648), stdev = 0.117
  CI (99.9%): [7.409, 11.673] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 3.079 ops/ms
# Warmup Iteration   2: 7.555 ops/ms
# Warmup Iteration   3: 8.010 ops/ms
Iteration   1: 8.544 ops/ms
Iteration   2: 8.375 ops/ms
Iteration   3: 8.324 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.414 ±(99.9%) 2.097 ops/ms [Average]
  (min, avg, max) = (8.324, 8.414, 8.544), stdev = 0.115
  CI (99.9%): [6.318, 10.511] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.220 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.756 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.556 ±(99.9%) 0.003 ms/op
Iteration   1: 3.281 ±(99.9%) 0.008 ms/op
Iteration   2: 3.491 ±(99.9%) 0.008 ms/op
Iteration   3: 3.229 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.334 ±(99.9%) 2.533 ms/op [Average]
  (min, avg, max) = (3.229, 3.334, 3.491), stdev = 0.139
  CI (99.9%): [0.800, 5.867] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.904 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.551 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.454 ±(99.9%) 0.005 ms/op
Iteration   1: 3.236 ±(99.9%) 0.006 ms/op
Iteration   2: 3.291 ±(99.9%) 0.008 ms/op
Iteration   3: 3.219 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.249 ±(99.9%) 0.686 ms/op [Average]
  (min, avg, max) = (3.219, 3.249, 3.291), stdev = 0.038
  CI (99.9%): [2.562, 3.935] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.821 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.677 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.594 ±(99.9%) 0.003 ms/op
Iteration   1: 3.333 ±(99.9%) 0.003 ms/op
Iteration   2: 3.378 ±(99.9%) 0.005 ms/op
Iteration   3: 3.297 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.336 ±(99.9%) 0.733 ms/op [Average]
  (min, avg, max) = (3.297, 3.336, 3.378), stdev = 0.040
  CI (99.9%): [2.602, 4.069] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.269 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.411 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.936 ±(99.9%) 0.010 ms/op
Iteration   1: 3.889 ±(99.9%) 0.012 ms/op
Iteration   2: 3.892 ±(99.9%) 0.005 ms/op
Iteration   3: 3.795 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.859 ±(99.9%) 1.007 ms/op [Average]
  (min, avg, max) = (3.795, 3.859, 3.892), stdev = 0.055
  CI (99.9%): [2.851, 4.866] (assumes normal distribution)


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
# Warmup Iteration   1: 9.502 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 4.132 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.547 ±(99.9%) 0.010 ms/op
Iteration   1: 3.306 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.772 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   6.499 ms/op
                 createUser·p0.999:  15.171 ms/op
                 createUser·p0.9999: 23.997 ms/op
                 createUser·p1.00:   25.035 ms/op

Iteration   2: 3.237 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.597 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  10.289 ms/op
                 createUser·p0.9999: 24.019 ms/op
                 createUser·p1.00:   24.773 ms/op

Iteration   3: 3.441 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.669 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   6.046 ms/op
                 createUser·p0.999:  15.844 ms/op
                 createUser·p0.9999: 22.545 ms/op
                 createUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 288402
  mean =      3.326 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12767 
    [ 2.500,  5.000) = 269428 
    [ 5.000,  7.500) = 5131 
    [ 7.500, 10.000) = 658 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 127 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.669 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     15.673 ms/op
     p(99.9900) =     23.888 ms/op
     p(99.9990) =     24.907 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


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
# Warmup Iteration   1: 8.701 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.633 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.448 ±(99.9%) 0.011 ms/op
Iteration   1: 3.235 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.956 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   5.849 ms/op
                 existUser·p0.999:  14.617 ms/op
                 existUser·p0.9999: 25.617 ms/op
                 existUser·p1.00:   26.214 ms/op

Iteration   2: 3.387 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.659 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.875 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   5.751 ms/op
                 existUser·p0.999:  19.606 ms/op
                 existUser·p0.9999: 22.825 ms/op
                 existUser·p1.00:   24.216 ms/op

Iteration   3: 3.231 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.384 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   5.304 ms/op
                 existUser·p0.999:  13.547 ms/op
                 existUser·p0.9999: 25.532 ms/op
                 existUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 292387
  mean =      3.282 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12282 
    [ 2.500,  5.000) = 274870 
    [ 5.000,  7.500) = 4420 
    [ 7.500, 10.000) = 311 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 119 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.956 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     13.763 ms/op
     p(99.9900) =     25.068 ms/op
     p(99.9990) =     26.184 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.902 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 3.835 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.734 ±(99.9%) 0.013 ms/op
Iteration   1: 3.498 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.493 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   4.116 ms/op
                 getUser·p0.95:   4.751 ms/op
                 getUser·p0.99:   7.053 ms/op
                 getUser·p0.999:  20.087 ms/op
                 getUser·p0.9999: 23.241 ms/op
                 getUser·p1.00:   23.626 ms/op

Iteration   2: 3.363 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.538 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  23.974 ms/op
                 getUser·p0.9999: 30.605 ms/op
                 getUser·p1.00:   31.752 ms/op

Iteration   3: 3.456 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.868 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   7.070 ms/op
                 getUser·p0.999:  20.234 ms/op
                 getUser·p0.9999: 28.606 ms/op
                 getUser·p1.00:   29.458 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279044
  mean =      3.438 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6979 
    [ 2.500,  5.000) = 261675 
    [ 5.000,  7.500) = 8457 
    [ 7.500, 10.000) = 1310 
    [10.000, 12.500) = 233 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.493 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     20.118 ms/op
     p(99.9900) =     29.763 ms/op
     p(99.9990) =     31.454 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


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
# Warmup Iteration   1: 10.113 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.376 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.973 ±(99.9%) 0.012 ms/op
Iteration   1: 3.857 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.166 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  21.124 ms/op
                 listUser·p0.9999: 25.137 ms/op
                 listUser·p1.00:   25.592 ms/op

Iteration   2: 4.115 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.413 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   8.209 ms/op
                 listUser·p0.999:  14.189 ms/op
                 listUser·p0.9999: 18.022 ms/op
                 listUser·p1.00:   18.088 ms/op

Iteration   3: 3.982 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.486 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  16.427 ms/op
                 listUser·p0.9999: 20.282 ms/op
                 listUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240979
  mean =      3.982 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 231176 
    [ 5.000,  7.500) = 7400 
    [ 7.500, 10.000) = 1558 
    [10.000, 12.500) = 296 
    [12.500, 15.000) = 182 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.413 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      7.479 ms/op
     p(99.9000) =     16.303 ms/op
     p(99.9900) =     23.348 ms/op
     p(99.9990) =     25.480 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.372 ± 0.639  ops/ms
ClientPb.existUser                       thrpt       3   9.880 ± 6.444  ops/ms
ClientPb.getUser                         thrpt       3   9.541 ± 2.132  ops/ms
ClientPb.listUser                        thrpt       3   8.414 ± 2.097  ops/ms
ClientPb.createUser                       avgt       3   3.334 ± 2.533   ms/op
ClientPb.existUser                        avgt       3   3.249 ± 0.686   ms/op
ClientPb.getUser                          avgt       3   3.336 ± 0.733   ms/op
ClientPb.listUser                         avgt       3   3.859 ± 1.007   ms/op
ClientPb.createUser                     sample  288402   3.326 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.669           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.232           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.723           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.035           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.964           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.673           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.888           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.035           ms/op
ClientPb.existUser                      sample  292387   3.282 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.956           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.211           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.944           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.726           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.763           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.068           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.214           ms/op
ClientPb.getUser                        sample  279044   3.438 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.493           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.252           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.981           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.694           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.857           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.118           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.763           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.752           ms/op
ClientPb.listUser                       sample  240979   3.982 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.413           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.801           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.479           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.303           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.348           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.592           ms/op
