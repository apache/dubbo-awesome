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
# Warmup Iteration   1: 2.747 ops/ms
# Warmup Iteration   2: 6.001 ops/ms
# Warmup Iteration   3: 9.113 ops/ms
Iteration   1: 9.938 ops/ms
Iteration   2: 9.878 ops/ms
Iteration   3: 9.876 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.897 ±(99.9%) 0.646 ops/ms [Average]
  (min, avg, max) = (9.876, 9.897, 9.938), stdev = 0.035
  CI (99.9%): [9.251, 10.543] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.745 ops/ms
# Warmup Iteration   2: 9.222 ops/ms
# Warmup Iteration   3: 10.430 ops/ms
Iteration   1: 10.542 ops/ms
Iteration   2: 10.531 ops/ms
Iteration   3: 10.736 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.603 ±(99.9%) 2.102 ops/ms [Average]
  (min, avg, max) = (10.531, 10.603, 10.736), stdev = 0.115
  CI (99.9%): [8.501, 12.705] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.785 ops/ms
# Warmup Iteration   2: 9.735 ops/ms
# Warmup Iteration   3: 9.985 ops/ms
Iteration   1: 9.721 ops/ms
Iteration   2: 9.584 ops/ms
Iteration   3: 10.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.818 ±(99.9%) 5.389 ops/ms [Average]
  (min, avg, max) = (9.584, 9.818, 10.150), stdev = 0.295
  CI (99.9%): [4.429, 15.207] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.379 ops/ms
# Warmup Iteration   2: 7.881 ops/ms
# Warmup Iteration   3: 8.317 ops/ms
Iteration   1: 8.476 ops/ms
Iteration   2: 8.626 ops/ms
Iteration   3: 8.690 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.597 ±(99.9%) 1.999 ops/ms [Average]
  (min, avg, max) = (8.476, 8.597, 8.690), stdev = 0.110
  CI (99.9%): [6.598, 10.597] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.088 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.414 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.315 ±(99.9%) 0.007 ms/op
Iteration   1: 3.163 ±(99.9%) 0.004 ms/op
Iteration   2: 3.098 ±(99.9%) 0.005 ms/op
Iteration   3: 3.139 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.133 ±(99.9%) 0.598 ms/op [Average]
  (min, avg, max) = (3.098, 3.133, 3.163), stdev = 0.033
  CI (99.9%): [2.535, 3.731] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.109 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.375 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.114 ±(99.9%) 0.004 ms/op
Iteration   1: 3.030 ±(99.9%) 0.005 ms/op
Iteration   2: 3.139 ±(99.9%) 0.006 ms/op
Iteration   3: 3.029 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.066 ±(99.9%) 1.155 ms/op [Average]
  (min, avg, max) = (3.029, 3.066, 3.139), stdev = 0.063
  CI (99.9%): [1.911, 4.221] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.816 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.349 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.244 ±(99.9%) 0.004 ms/op
Iteration   1: 3.315 ±(99.9%) 0.003 ms/op
Iteration   2: 3.218 ±(99.9%) 0.003 ms/op
Iteration   3: 3.084 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.206 ±(99.9%) 2.119 ms/op [Average]
  (min, avg, max) = (3.084, 3.206, 3.315), stdev = 0.116
  CI (99.9%): [1.086, 5.325] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.630 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.925 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.700 ±(99.9%) 0.007 ms/op
Iteration   1: 3.627 ±(99.9%) 0.011 ms/op
Iteration   2: 3.711 ±(99.9%) 0.009 ms/op
Iteration   3: 3.694 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.677 ±(99.9%) 0.811 ms/op [Average]
  (min, avg, max) = (3.627, 3.677, 3.711), stdev = 0.044
  CI (99.9%): [2.867, 4.488] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.965 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.873 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.258 ±(99.9%) 0.008 ms/op
Iteration   1: 3.138 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.370 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  10.602 ms/op
                 createUser·p0.9999: 19.505 ms/op
                 createUser·p1.00:   20.185 ms/op

Iteration   2: 3.187 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.436 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.367 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  19.325 ms/op
                 createUser·p0.9999: 21.856 ms/op
                 createUser·p1.00:   22.249 ms/op

Iteration   3: 3.464 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.315 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   4.088 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  16.377 ms/op
                 createUser·p0.9999: 29.549 ms/op
                 createUser·p1.00:   29.950 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294567
  mean =      3.257 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17078 
    [ 2.500,  5.000) = 270690 
    [ 5.000,  7.500) = 5766 
    [ 7.500, 10.000) = 538 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.315 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =     17.269 ms/op
     p(99.9900) =     28.606 ms/op
     p(99.9990) =     29.695 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.690 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.452 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.247 ±(99.9%) 0.009 ms/op
Iteration   1: 3.011 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.303 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.416 ms/op
                 existUser·p0.99:   5.169 ms/op
                 existUser·p0.999:  9.313 ms/op
                 existUser·p0.9999: 20.242 ms/op
                 existUser·p1.00:   22.741 ms/op

Iteration   2: 3.123 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.130 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  15.499 ms/op
                 existUser·p0.9999: 24.379 ms/op
                 existUser·p1.00:   26.673 ms/op

Iteration   3: 3.146 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.675 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   5.956 ms/op
                 existUser·p0.999:  14.713 ms/op
                 existUser·p0.9999: 21.201 ms/op
                 existUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310356
  mean =      3.092 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21507 
    [ 2.500,  5.000) = 283139 
    [ 5.000,  7.500) = 4870 
    [ 7.500, 10.000) = 388 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 153 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     14.713 ms/op
     p(99.9900) =     22.478 ms/op
     p(99.9990) =     25.128 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 7.584 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.532 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.262 ±(99.9%) 0.009 ms/op
Iteration   1: 3.248 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.456 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   6.554 ms/op
                 getUser·p0.999:  12.256 ms/op
                 getUser·p0.9999: 21.937 ms/op
                 getUser·p1.00:   22.807 ms/op

Iteration   2: 3.187 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.571 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   5.636 ms/op
                 getUser·p0.999:  17.521 ms/op
                 getUser·p0.9999: 26.376 ms/op
                 getUser·p1.00:   27.918 ms/op

Iteration   3: 3.187 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.621 ms/op
                 getUser·p0.99:   5.374 ms/op
                 getUser·p0.999:  9.650 ms/op
                 getUser·p0.9999: 20.115 ms/op
                 getUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299194
  mean =      3.207 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7332 
    [ 2.500,  5.000) = 285079 
    [ 5.000,  7.500) = 5833 
    [ 7.500, 10.000) = 551 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 133 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =     15.706 ms/op
     p(99.9900) =     24.876 ms/op
     p(99.9990) =     26.871 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


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
# Warmup Iteration   1: 9.156 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.144 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.793 ±(99.9%) 0.011 ms/op
Iteration   1: 3.852 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.696 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   5.030 ms/op
                 listUser·p0.99:   7.700 ms/op
                 listUser·p0.999:  15.297 ms/op
                 listUser·p0.9999: 20.438 ms/op
                 listUser·p1.00:   21.201 ms/op

Iteration   2: 3.717 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.211 ms/op
                 listUser·p0.99:   6.781 ms/op
                 listUser·p0.999:  12.762 ms/op
                 listUser·p0.9999: 16.417 ms/op
                 listUser·p1.00:   16.679 ms/op

Iteration   3: 3.722 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   6.431 ms/op
                 listUser·p0.999:  12.712 ms/op
                 listUser·p0.9999: 14.074 ms/op
                 listUser·p1.00:   14.139 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254914
  mean =      3.763 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 67 
    [ 2.500,  5.000) = 246337 
    [ 5.000,  7.500) = 6415 
    [ 7.500, 10.000) = 1396 
    [10.000, 12.500) = 340 
    [12.500, 15.000) = 261 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.696 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     13.141 ms/op
     p(99.9900) =     18.827 ms/op
     p(99.9990) =     20.918 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.897 ± 0.646  ops/ms
ClientPb.existUser                       thrpt       3  10.603 ± 2.102  ops/ms
ClientPb.getUser                         thrpt       3   9.818 ± 5.389  ops/ms
ClientPb.listUser                        thrpt       3   8.597 ± 1.999  ops/ms
ClientPb.createUser                       avgt       3   3.133 ± 0.598   ms/op
ClientPb.existUser                        avgt       3   3.066 ± 1.155   ms/op
ClientPb.getUser                          avgt       3   3.206 ± 2.119   ms/op
ClientPb.listUser                         avgt       3   3.677 ± 0.811   ms/op
ClientPb.createUser                     sample  294567   3.257 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.315           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.157           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.407           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.269           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.606           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.950           ms/op
ClientPb.existUser                      sample  310356   3.092 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.130           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.359           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.415           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.713           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.478           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.673           ms/op
ClientPb.getUser                        sample  299194   3.207 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.936           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.518           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.777           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.882           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.706           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.876           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.918           ms/op
ClientPb.listUser                       sample  254914   3.763 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.696           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.670           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.059           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.127           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.141           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.827           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.201           ms/op
