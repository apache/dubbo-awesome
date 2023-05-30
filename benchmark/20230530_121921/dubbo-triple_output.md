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
# Warmup Iteration   1: 2.185 ops/ms
# Warmup Iteration   2: 5.885 ops/ms
# Warmup Iteration   3: 8.580 ops/ms
Iteration   1: 9.236 ops/ms
Iteration   2: 9.420 ops/ms
Iteration   3: 9.687 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.448 ±(99.9%) 4.143 ops/ms [Average]
  (min, avg, max) = (9.236, 9.448, 9.687), stdev = 0.227
  CI (99.9%): [5.305, 13.591] (assumes normal distribution)


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
# Warmup Iteration   1: 3.144 ops/ms
# Warmup Iteration   2: 8.931 ops/ms
# Warmup Iteration   3: 9.291 ops/ms
Iteration   1: 9.605 ops/ms
Iteration   2: 9.210 ops/ms
Iteration   3: 10.048 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.621 ±(99.9%) 7.647 ops/ms [Average]
  (min, avg, max) = (9.210, 9.621, 10.048), stdev = 0.419
  CI (99.9%): [1.974, 17.268] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.318 ops/ms
# Warmup Iteration   2: 8.382 ops/ms
# Warmup Iteration   3: 9.022 ops/ms
Iteration   1: 9.423 ops/ms
Iteration   2: 9.115 ops/ms
Iteration   3: 9.371 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.303 ±(99.9%) 3.008 ops/ms [Average]
  (min, avg, max) = (9.115, 9.303, 9.423), stdev = 0.165
  CI (99.9%): [6.295, 12.311] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.692 ops/ms
# Warmup Iteration   2: 6.760 ops/ms
# Warmup Iteration   3: 7.967 ops/ms
Iteration   1: 8.154 ops/ms
Iteration   2: 7.975 ops/ms
Iteration   3: 8.020 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.050 ±(99.9%) 1.692 ops/ms [Average]
  (min, avg, max) = (7.975, 8.050, 8.154), stdev = 0.093
  CI (99.9%): [6.357, 9.742] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.975 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.684 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.501 ±(99.9%) 0.006 ms/op
Iteration   1: 3.434 ±(99.9%) 0.006 ms/op
Iteration   2: 3.391 ±(99.9%) 0.008 ms/op
Iteration   3: 3.285 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.370 ±(99.9%) 1.394 ms/op [Average]
  (min, avg, max) = (3.285, 3.370, 3.434), stdev = 0.076
  CI (99.9%): [1.976, 4.765] (assumes normal distribution)


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
# Warmup Iteration   1: 7.929 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.463 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.341 ±(99.9%) 0.005 ms/op
Iteration   1: 3.269 ±(99.9%) 0.007 ms/op
Iteration   2: 3.294 ±(99.9%) 0.008 ms/op
Iteration   3: 3.205 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.256 ±(99.9%) 0.840 ms/op [Average]
  (min, avg, max) = (3.205, 3.256, 3.294), stdev = 0.046
  CI (99.9%): [2.416, 4.096] (assumes normal distribution)


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
# Warmup Iteration   1: 9.062 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.605 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.551 ±(99.9%) 0.005 ms/op
Iteration   1: 3.456 ±(99.9%) 0.003 ms/op
Iteration   2: 3.285 ±(99.9%) 0.009 ms/op
Iteration   3: 3.307 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.349 ±(99.9%) 1.696 ms/op [Average]
  (min, avg, max) = (3.285, 3.349, 3.456), stdev = 0.093
  CI (99.9%): [1.654, 5.045] (assumes normal distribution)


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
# Warmup Iteration   1: 11.007 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.358 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.116 ±(99.9%) 0.009 ms/op
Iteration   1: 3.907 ±(99.9%) 0.010 ms/op
Iteration   2: 3.952 ±(99.9%) 0.011 ms/op
Iteration   3: 3.840 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.900 ±(99.9%) 1.025 ms/op [Average]
  (min, avg, max) = (3.840, 3.900, 3.952), stdev = 0.056
  CI (99.9%): [2.875, 4.924] (assumes normal distribution)


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
# Warmup Iteration   1: 9.276 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.056 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.348 ±(99.9%) 0.009 ms/op
Iteration   1: 3.384 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.570 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   4.149 ms/op
                 createUser·p0.99:   6.554 ms/op
                 createUser·p0.999:  21.299 ms/op
                 createUser·p0.9999: 29.148 ms/op
                 createUser·p1.00:   29.426 ms/op

Iteration   2: 3.366 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.392 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   6.054 ms/op
                 createUser·p0.999:  21.560 ms/op
                 createUser·p0.9999: 29.098 ms/op
                 createUser·p1.00:   30.900 ms/op

Iteration   3: 3.529 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.942 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   4.190 ms/op
                 createUser·p0.95:   4.751 ms/op
                 createUser·p0.99:   6.424 ms/op
                 createUser·p0.999:  20.218 ms/op
                 createUser·p0.9999: 25.158 ms/op
                 createUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280215
  mean =      3.425 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14937 
    [ 2.500,  5.000) = 256619 
    [ 5.000,  7.500) = 7271 
    [ 7.500, 10.000) = 807 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.392 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     20.269 ms/op
     p(99.9900) =     28.999 ms/op
     p(99.9990) =     29.588 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


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
# Warmup Iteration   1: 8.080 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.719 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.248 ±(99.9%) 0.007 ms/op
Iteration   1: 3.382 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.524 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.965 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  19.464 ms/op
                 existUser·p0.9999: 24.465 ms/op
                 existUser·p1.00:   24.904 ms/op

Iteration   2: 3.310 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.372 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  16.392 ms/op
                 existUser·p0.9999: 27.230 ms/op
                 existUser·p1.00:   28.803 ms/op

Iteration   3: 3.295 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.225 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   4.026 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  15.088 ms/op
                 existUser·p0.9999: 26.158 ms/op
                 existUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288330
  mean =      3.329 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9358 
    [ 2.500,  5.000) = 273827 
    [ 5.000,  7.500) = 4172 
    [ 7.500, 10.000) = 528 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 49 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      4.116 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     17.665 ms/op
     p(99.9900) =     26.444 ms/op
     p(99.9990) =     28.552 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


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
# Warmup Iteration   1: 9.123 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 3.780 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.497 ±(99.9%) 0.010 ms/op
Iteration   1: 3.511 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.567 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.850 ms/op
                 getUser·p0.99:   7.053 ms/op
                 getUser·p0.999:  19.264 ms/op
                 getUser·p0.9999: 22.541 ms/op
                 getUser·p1.00:   24.216 ms/op

Iteration   2: 3.325 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.260 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   5.226 ms/op
                 getUser·p0.999:  19.564 ms/op
                 getUser·p0.9999: 23.147 ms/op
                 getUser·p1.00:   23.560 ms/op

Iteration   3: 3.437 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.000 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   5.768 ms/op
                 getUser·p0.999:  23.036 ms/op
                 getUser·p0.9999: 25.892 ms/op
                 getUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280283
  mean =      3.423 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4935 
    [ 2.500,  5.000) = 266971 
    [ 5.000,  7.500) = 7241 
    [ 7.500, 10.000) = 685 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 133 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.000 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      6.267 ms/op
     p(99.9000) =     19.413 ms/op
     p(99.9900) =     25.362 ms/op
     p(99.9990) =     26.686 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


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
# Warmup Iteration   1: 11.056 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.418 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.019 ±(99.9%) 0.012 ms/op
Iteration   1: 3.999 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.101 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   7.807 ms/op
                 listUser·p0.999:  19.988 ms/op
                 listUser·p0.9999: 27.558 ms/op
                 listUser·p1.00:   30.409 ms/op

Iteration   2: 3.963 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.138 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  16.585 ms/op
                 listUser·p0.9999: 20.021 ms/op
                 listUser·p1.00:   20.808 ms/op

Iteration   3: 4.047 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.523 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  15.415 ms/op
                 listUser·p0.9999: 19.121 ms/op
                 listUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239857
  mean =      4.003 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 231173 
    [ 5.000,  7.500) = 6614 
    [ 7.500, 10.000) = 1274 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 189 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.101 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     16.581 ms/op
     p(99.9900) =     25.200 ms/op
     p(99.9990) =     30.120 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.448 ± 4.143  ops/ms
ClientPb.existUser                       thrpt       3   9.621 ± 7.647  ops/ms
ClientPb.getUser                         thrpt       3   9.303 ± 3.008  ops/ms
ClientPb.listUser                        thrpt       3   8.050 ± 1.692  ops/ms
ClientPb.createUser                       avgt       3   3.370 ± 1.394   ms/op
ClientPb.existUser                        avgt       3   3.256 ± 0.840   ms/op
ClientPb.getUser                          avgt       3   3.349 ± 1.696   ms/op
ClientPb.listUser                         avgt       3   3.900 ± 1.025   ms/op
ClientPb.createUser                     sample  280215   3.425 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.392           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.322           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.936           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.358           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.373           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.269           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.999           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.900           ms/op
ClientPb.existUser                      sample  288330   3.329 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.225           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.116           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.636           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.665           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.444           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.803           ms/op
ClientPb.getUser                        sample  280283   3.423 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.000           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.281           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.772           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.096           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.267           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.413           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.362           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.361           ms/op
ClientPb.listUser                       sample  239857   4.003 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.101           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.727           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.119           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.581           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.200           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.409           ms/op
