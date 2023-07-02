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
# Warmup Iteration   1: 2.439 ops/ms
# Warmup Iteration   2: 5.979 ops/ms
# Warmup Iteration   3: 8.818 ops/ms
Iteration   1: 10.058 ops/ms
Iteration   2: 9.638 ops/ms
Iteration   3: 10.050 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.915 ±(99.9%) 4.381 ops/ms [Average]
  (min, avg, max) = (9.638, 9.915, 10.058), stdev = 0.240
  CI (99.9%): [5.535, 14.296] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.271 ops/ms
# Warmup Iteration   2: 9.139 ops/ms
# Warmup Iteration   3: 10.398 ops/ms
Iteration   1: 10.586 ops/ms
Iteration   2: 10.116 ops/ms
Iteration   3: 10.357 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.353 ±(99.9%) 4.283 ops/ms [Average]
  (min, avg, max) = (10.116, 10.353, 10.586), stdev = 0.235
  CI (99.9%): [6.070, 14.636] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.346 ops/ms
# Warmup Iteration   2: 8.658 ops/ms
# Warmup Iteration   3: 9.790 ops/ms
Iteration   1: 9.936 ops/ms
Iteration   2: 10.357 ops/ms
Iteration   3: 9.981 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.091 ±(99.9%) 4.222 ops/ms [Average]
  (min, avg, max) = (9.936, 10.091, 10.357), stdev = 0.231
  CI (99.9%): [5.869, 14.313] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.170 ops/ms
# Warmup Iteration   2: 7.542 ops/ms
# Warmup Iteration   3: 8.230 ops/ms
Iteration   1: 8.151 ops/ms
Iteration   2: 8.134 ops/ms
Iteration   3: 8.303 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.196 ±(99.9%) 1.701 ops/ms [Average]
  (min, avg, max) = (8.134, 8.196, 8.303), stdev = 0.093
  CI (99.9%): [6.495, 9.897] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.196 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.624 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.345 ±(99.9%) 0.002 ms/op
Iteration   1: 3.234 ±(99.9%) 0.011 ms/op
Iteration   2: 3.191 ±(99.9%) 0.008 ms/op
Iteration   3: 3.309 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.244 ±(99.9%) 1.090 ms/op [Average]
  (min, avg, max) = (3.191, 3.244, 3.309), stdev = 0.060
  CI (99.9%): [2.155, 4.334] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.913 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.322 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.286 ±(99.9%) 0.004 ms/op
Iteration   1: 3.213 ±(99.9%) 0.006 ms/op
Iteration   2: 3.176 ±(99.9%) 0.005 ms/op
Iteration   3: 3.249 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.212 ±(99.9%) 0.669 ms/op [Average]
  (min, avg, max) = (3.176, 3.212, 3.249), stdev = 0.037
  CI (99.9%): [2.543, 3.882] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.271 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.695 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.315 ±(99.9%) 0.004 ms/op
Iteration   1: 3.109 ±(99.9%) 0.006 ms/op
Iteration   2: 3.163 ±(99.9%) 0.004 ms/op
Iteration   3: 3.251 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.174 ±(99.9%) 1.306 ms/op [Average]
  (min, avg, max) = (3.109, 3.174, 3.251), stdev = 0.072
  CI (99.9%): [1.868, 4.481] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.799 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.227 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.828 ±(99.9%) 0.008 ms/op
Iteration   1: 3.879 ±(99.9%) 0.009 ms/op
Iteration   2: 3.909 ±(99.9%) 0.006 ms/op
Iteration   3: 3.842 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.877 ±(99.9%) 0.621 ms/op [Average]
  (min, avg, max) = (3.842, 3.877, 3.909), stdev = 0.034
  CI (99.9%): [3.256, 4.497] (assumes normal distribution)


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
# Warmup Iteration   1: 8.389 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.623 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.229 ±(99.9%) 0.008 ms/op
Iteration   1: 3.235 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.749 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  20.124 ms/op
                 createUser·p0.9999: 24.234 ms/op
                 createUser·p1.00:   25.035 ms/op

Iteration   2: 3.431 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.145 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   4.063 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  18.769 ms/op
                 createUser·p0.9999: 23.189 ms/op
                 createUser·p1.00:   24.281 ms/op

Iteration   3: 3.171 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.415 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.621 ms/op
                 createUser·p0.999:  17.931 ms/op
                 createUser·p0.9999: 21.460 ms/op
                 createUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 292978
  mean =      3.276 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9225 
    [ 2.500,  5.000) = 278227 
    [ 5.000,  7.500) = 4733 
    [ 7.500, 10.000) = 299 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 155 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.749 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.153 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     18.875 ms/op
     p(99.9900) =     23.387 ms/op
     p(99.9990) =     24.747 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 9.071 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.673 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.007 ms/op
Iteration   1: 3.077 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.053 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   5.215 ms/op
                 existUser·p0.999:  8.852 ms/op
                 existUser·p0.9999: 22.514 ms/op
                 existUser·p1.00:   23.560 ms/op

Iteration   2: 3.174 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.214 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  11.928 ms/op
                 existUser·p0.9999: 23.328 ms/op
                 existUser·p1.00:   24.576 ms/op

Iteration   3: 3.149 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.081 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.437 ms/op
                 existUser·p0.99:   5.563 ms/op
                 existUser·p0.999:  16.823 ms/op
                 existUser·p0.9999: 21.458 ms/op
                 existUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306268
  mean =      3.133 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18865 
    [ 2.500,  5.000) = 282910 
    [ 5.000,  7.500) = 3496 
    [ 7.500, 10.000) = 515 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 163 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =     16.286 ms/op
     p(99.9900) =     22.512 ms/op
     p(99.9990) =     23.558 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.805 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.594 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.410 ±(99.9%) 0.010 ms/op
Iteration   1: 3.186 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.139 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.800 ms/op
                 getUser·p0.99:   5.947 ms/op
                 getUser·p0.999:  19.480 ms/op
                 getUser·p0.9999: 24.871 ms/op
                 getUser·p1.00:   26.280 ms/op

Iteration   2: 3.193 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.141 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   5.480 ms/op
                 getUser·p0.999:  12.466 ms/op
                 getUser·p0.9999: 24.609 ms/op
                 getUser·p1.00:   25.690 ms/op

Iteration   3: 3.271 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.975 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  10.208 ms/op
                 getUser·p0.9999: 23.641 ms/op
                 getUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298118
  mean =      3.216 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14105 
    [ 2.500,  5.000) = 277290 
    [ 5.000,  7.500) = 5760 
    [ 7.500, 10.000) = 582 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.975 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     17.724 ms/op
     p(99.9900) =     24.347 ms/op
     p(99.9990) =     25.699 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.894 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.196 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.826 ±(99.9%) 0.011 ms/op
Iteration   1: 3.907 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.587 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  19.661 ms/op
                 listUser·p0.9999: 26.470 ms/op
                 listUser·p1.00:   27.394 ms/op

Iteration   2: 3.856 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.163 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.153 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   7.230 ms/op
                 listUser·p0.999:  13.828 ms/op
                 listUser·p0.9999: 19.580 ms/op
                 listUser·p1.00:   19.792 ms/op

Iteration   3: 3.903 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   7.856 ms/op
                 listUser·p0.999:  16.271 ms/op
                 listUser·p0.9999: 21.864 ms/op
                 listUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 246747
  mean =      3.888 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 238242 
    [ 5.000,  7.500) = 5805 
    [ 7.500, 10.000) = 1771 
    [10.000, 12.500) = 371 
    [12.500, 15.000) = 225 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.587 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      7.615 ms/op
     p(99.9000) =     15.843 ms/op
     p(99.9900) =     25.460 ms/op
     p(99.9990) =     27.121 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.915 ± 4.381  ops/ms
ClientPb.existUser                       thrpt       3  10.353 ± 4.283  ops/ms
ClientPb.getUser                         thrpt       3  10.091 ± 4.222  ops/ms
ClientPb.listUser                        thrpt       3   8.196 ± 1.701  ops/ms
ClientPb.createUser                       avgt       3   3.244 ± 1.090   ms/op
ClientPb.existUser                        avgt       3   3.212 ± 0.669   ms/op
ClientPb.getUser                          avgt       3   3.174 ± 1.306   ms/op
ClientPb.listUser                         avgt       3   3.877 ± 0.621   ms/op
ClientPb.createUser                     sample  292978   3.276 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.749           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.153           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.546           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.875           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.387           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.035           ms/op
ClientPb.existUser                      sample  306268   3.133 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.053           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.396           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.690           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.407           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.286           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.512           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.576           ms/op
ClientPb.getUser                        sample  298118   3.216 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.975           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.125           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.576           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.985           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.833           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.724           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.347           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.280           ms/op
ClientPb.listUser                       sample  246747   3.888 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.587           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.752           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.202           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.615           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.843           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.460           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.394           ms/op
