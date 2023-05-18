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
# Warmup Iteration   1: 2.040 ops/ms
# Warmup Iteration   2: 5.817 ops/ms
# Warmup Iteration   3: 8.370 ops/ms
Iteration   1: 8.990 ops/ms
Iteration   2: 9.434 ops/ms
Iteration   3: 9.181 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.202 ±(99.9%) 4.062 ops/ms [Average]
  (min, avg, max) = (8.990, 9.202, 9.434), stdev = 0.223
  CI (99.9%): [5.139, 13.264] (assumes normal distribution)


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
# Warmup Iteration   1: 2.814 ops/ms
# Warmup Iteration   2: 8.895 ops/ms
# Warmup Iteration   3: 9.218 ops/ms
Iteration   1: 9.820 ops/ms
Iteration   2: 10.053 ops/ms
Iteration   3: 10.043 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.972 ±(99.9%) 2.403 ops/ms [Average]
  (min, avg, max) = (9.820, 9.972, 10.053), stdev = 0.132
  CI (99.9%): [7.568, 12.375] (assumes normal distribution)


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
# Warmup Iteration   1: 3.390 ops/ms
# Warmup Iteration   2: 8.337 ops/ms
# Warmup Iteration   3: 9.219 ops/ms
Iteration   1: 9.462 ops/ms
Iteration   2: 8.908 ops/ms
Iteration   3: 9.692 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.354 ±(99.9%) 7.352 ops/ms [Average]
  (min, avg, max) = (8.908, 9.354, 9.692), stdev = 0.403
  CI (99.9%): [2.002, 16.706] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.225 ops/ms
# Warmup Iteration   2: 7.379 ops/ms
# Warmup Iteration   3: 7.784 ops/ms
Iteration   1: 8.134 ops/ms
Iteration   2: 8.001 ops/ms
Iteration   3: 8.368 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.168 ±(99.9%) 3.392 ops/ms [Average]
  (min, avg, max) = (8.001, 8.168, 8.368), stdev = 0.186
  CI (99.9%): [4.776, 11.560] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.689 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.705 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.517 ±(99.9%) 0.006 ms/op
Iteration   1: 3.291 ±(99.9%) 0.008 ms/op
Iteration   2: 3.362 ±(99.9%) 0.008 ms/op
Iteration   3: 3.387 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.347 ±(99.9%) 0.906 ms/op [Average]
  (min, avg, max) = (3.291, 3.347, 3.387), stdev = 0.050
  CI (99.9%): [2.441, 4.252] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 10.096 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.525 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.430 ±(99.9%) 0.005 ms/op
Iteration   1: 3.270 ±(99.9%) 0.008 ms/op
Iteration   2: 3.360 ±(99.9%) 0.010 ms/op
Iteration   3: 3.221 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.284 ±(99.9%) 1.287 ms/op [Average]
  (min, avg, max) = (3.221, 3.284, 3.360), stdev = 0.071
  CI (99.9%): [1.997, 4.571] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.465 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.759 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.497 ±(99.9%) 0.005 ms/op
Iteration   1: 3.394 ±(99.9%) 0.005 ms/op
Iteration   2: 3.328 ±(99.9%) 0.008 ms/op
Iteration   3: 3.486 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.403 ±(99.9%) 1.448 ms/op [Average]
  (min, avg, max) = (3.328, 3.403, 3.486), stdev = 0.079
  CI (99.9%): [1.955, 4.851] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.190 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.411 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.198 ±(99.9%) 0.009 ms/op
Iteration   1: 3.875 ±(99.9%) 0.010 ms/op
Iteration   2: 3.829 ±(99.9%) 0.012 ms/op
Iteration   3: 3.958 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.887 ±(99.9%) 1.189 ms/op [Average]
  (min, avg, max) = (3.829, 3.887, 3.958), stdev = 0.065
  CI (99.9%): [2.698, 5.076] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.146 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.894 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.479 ±(99.9%) 0.010 ms/op
Iteration   1: 3.264 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.473 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  11.796 ms/op
                 createUser·p0.9999: 23.186 ms/op
                 createUser·p1.00:   25.133 ms/op

Iteration   2: 3.384 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.384 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  20.937 ms/op
                 createUser·p0.9999: 24.433 ms/op
                 createUser·p1.00:   25.068 ms/op

Iteration   3: 3.530 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.554 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.071 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   6.510 ms/op
                 createUser·p0.999:  19.217 ms/op
                 createUser·p0.9999: 26.014 ms/op
                 createUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283101
  mean =      3.389 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6148 
    [ 2.500,  5.000) = 270970 
    [ 5.000,  7.500) = 4856 
    [ 7.500, 10.000) = 725 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 128 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.384 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     19.137 ms/op
     p(99.9900) =     24.894 ms/op
     p(99.9990) =     26.291 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.920 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.615 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.297 ±(99.9%) 0.009 ms/op
Iteration   1: 3.405 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.219 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.949 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   5.792 ms/op
                 existUser·p0.999:  23.552 ms/op
                 existUser·p0.9999: 28.344 ms/op
                 existUser·p1.00:   29.295 ms/op

Iteration   2: 3.152 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.350 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  15.882 ms/op
                 existUser·p0.9999: 29.826 ms/op
                 existUser·p1.00:   30.310 ms/op

Iteration   3: 3.273 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.337 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   5.947 ms/op
                 existUser·p0.999:  12.698 ms/op
                 existUser·p0.9999: 25.501 ms/op
                 existUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293356
  mean =      3.274 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6386 
    [ 2.500,  5.000) = 280253 
    [ 5.000,  7.500) = 5565 
    [ 7.500, 10.000) = 646 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.219 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     15.884 ms/op
     p(99.9900) =     28.344 ms/op
     p(99.9990) =     30.057 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


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
# Warmup Iteration   1: 10.263 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.708 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.452 ±(99.9%) 0.011 ms/op
Iteration   1: 3.343 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.849 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  17.891 ms/op
                 getUser·p0.9999: 22.063 ms/op
                 getUser·p1.00:   23.134 ms/op

Iteration   2: 3.318 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.403 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   5.800 ms/op
                 getUser·p0.999:  11.171 ms/op
                 getUser·p0.9999: 23.048 ms/op
                 getUser·p1.00:   25.035 ms/op

Iteration   3: 3.376 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.509 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  18.031 ms/op
                 getUser·p0.9999: 29.022 ms/op
                 getUser·p1.00:   29.950 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 286814
  mean =      3.346 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1581 
    [ 2.500,  5.000) = 279827 
    [ 5.000,  7.500) = 4292 
    [ 7.500, 10.000) = 675 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.403 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     27.896 ms/op
     p(99.9990) =     29.803 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


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
# Warmup Iteration   1: 11.337 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.300 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.083 ±(99.9%) 0.013 ms/op
Iteration   1: 3.962 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.591 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   8.102 ms/op
                 listUser·p0.999:  18.717 ms/op
                 listUser·p0.9999: 24.082 ms/op
                 listUser·p1.00:   24.642 ms/op

Iteration   2: 3.914 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.665 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   7.708 ms/op
                 listUser·p0.999:  17.236 ms/op
                 listUser·p0.9999: 21.070 ms/op
                 listUser·p1.00:   22.381 ms/op

Iteration   3: 3.913 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.448 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  17.302 ms/op
                 listUser·p0.9999: 20.152 ms/op
                 listUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 244184
  mean =      3.930 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 235935 
    [ 5.000,  7.500) = 5596 
    [ 7.500, 10.000) = 1682 
    [10.000, 12.500) = 380 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 162 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.448 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      7.653 ms/op
     p(99.9000) =     17.498 ms/op
     p(99.9900) =     22.432 ms/op
     p(99.9990) =     24.388 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.202 ± 4.062  ops/ms
ClientPb.existUser                       thrpt       3   9.972 ± 2.403  ops/ms
ClientPb.getUser                         thrpt       3   9.354 ± 7.352  ops/ms
ClientPb.listUser                        thrpt       3   8.168 ± 3.392  ops/ms
ClientPb.createUser                       avgt       3   3.347 ± 0.906   ms/op
ClientPb.existUser                        avgt       3   3.284 ± 1.287   ms/op
ClientPb.getUser                          avgt       3   3.403 ± 1.448   ms/op
ClientPb.listUser                         avgt       3   3.887 ± 1.189   ms/op
ClientPb.createUser                     sample  283101   3.389 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.384           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.244           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.854           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.182           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.833           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.137           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.894           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.477           ms/op
ClientPb.existUser                      sample  293356   3.274 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.219           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.138           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.010           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.734           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.884           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.344           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.310           ms/op
ClientPb.getUser                        sample  286814   3.346 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.403           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.224           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.666           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.898           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.138           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.896           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.950           ms/op
ClientPb.listUser                       sample  244184   3.930 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.448           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.772           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.653           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.498           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.432           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.642           ms/op
