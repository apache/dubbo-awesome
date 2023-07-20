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
# Warmup Iteration   1: 2.522 ops/ms
# Warmup Iteration   2: 5.972 ops/ms
# Warmup Iteration   3: 8.985 ops/ms
Iteration   1: 9.529 ops/ms
Iteration   2: 9.731 ops/ms
Iteration   3: 10.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.791 ±(99.9%) 5.410 ops/ms [Average]
  (min, avg, max) = (9.529, 9.791, 10.113), stdev = 0.297
  CI (99.9%): [4.381, 15.201] (assumes normal distribution)


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
# Warmup Iteration   1: 3.810 ops/ms
# Warmup Iteration   2: 9.484 ops/ms
# Warmup Iteration   3: 9.683 ops/ms
Iteration   1: 10.273 ops/ms
Iteration   2: 10.044 ops/ms
Iteration   3: 9.962 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.093 ±(99.9%) 2.937 ops/ms [Average]
  (min, avg, max) = (9.962, 10.093, 10.273), stdev = 0.161
  CI (99.9%): [7.156, 13.030] (assumes normal distribution)


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
# Warmup Iteration   1: 3.209 ops/ms
# Warmup Iteration   2: 8.630 ops/ms
# Warmup Iteration   3: 9.782 ops/ms
Iteration   1: 9.927 ops/ms
Iteration   2: 9.857 ops/ms
Iteration   3: 9.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.919 ±(99.9%) 1.071 ops/ms [Average]
  (min, avg, max) = (9.857, 9.919, 9.974), stdev = 0.059
  CI (99.9%): [8.849, 10.990] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.342 ops/ms
# Warmup Iteration   2: 7.720 ops/ms
# Warmup Iteration   3: 8.201 ops/ms
Iteration   1: 8.619 ops/ms
Iteration   2: 8.578 ops/ms
Iteration   3: 8.516 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.571 ±(99.9%) 0.939 ops/ms [Average]
  (min, avg, max) = (8.516, 8.571, 8.619), stdev = 0.051
  CI (99.9%): [7.632, 9.510] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.948 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.507 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.362 ±(99.9%) 0.004 ms/op
Iteration   1: 3.129 ±(99.9%) 0.002 ms/op
Iteration   2: 3.223 ±(99.9%) 0.003 ms/op
Iteration   3: 3.179 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.177 ±(99.9%) 0.857 ms/op [Average]
  (min, avg, max) = (3.129, 3.177, 3.223), stdev = 0.047
  CI (99.9%): [2.320, 4.034] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.797 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.443 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.202 ±(99.9%) 0.003 ms/op
Iteration   1: 3.117 ±(99.9%) 0.006 ms/op
Iteration   2: 3.233 ±(99.9%) 0.006 ms/op
Iteration   3: 3.092 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.147 ±(99.9%) 1.372 ms/op [Average]
  (min, avg, max) = (3.092, 3.147, 3.233), stdev = 0.075
  CI (99.9%): [1.775, 4.520] (assumes normal distribution)


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
# Warmup Iteration   1: 7.955 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.537 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.326 ±(99.9%) 0.003 ms/op
Iteration   1: 3.241 ±(99.9%) 0.004 ms/op
Iteration   2: 3.288 ±(99.9%) 0.006 ms/op
Iteration   3: 3.272 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.267 ±(99.9%) 0.431 ms/op [Average]
  (min, avg, max) = (3.241, 3.267, 3.288), stdev = 0.024
  CI (99.9%): [2.836, 3.698] (assumes normal distribution)


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
# Warmup Iteration   1: 9.087 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.154 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.834 ±(99.9%) 0.007 ms/op
Iteration   1: 3.732 ±(99.9%) 0.011 ms/op
Iteration   2: 3.716 ±(99.9%) 0.009 ms/op
Iteration   3: 3.800 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.749 ±(99.9%) 0.811 ms/op [Average]
  (min, avg, max) = (3.716, 3.749, 3.800), stdev = 0.044
  CI (99.9%): [2.939, 4.560] (assumes normal distribution)


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
# Warmup Iteration   1: 7.679 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.937 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.281 ±(99.9%) 0.009 ms/op
Iteration   1: 3.211 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.196 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  10.469 ms/op
                 createUser·p0.9999: 19.924 ms/op
                 createUser·p1.00:   20.873 ms/op

Iteration   2: 3.400 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.438 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  20.036 ms/op
                 createUser·p0.9999: 32.473 ms/op
                 createUser·p1.00:   33.620 ms/op

Iteration   3: 3.205 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.464 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  16.810 ms/op
                 createUser·p0.9999: 38.077 ms/op
                 createUser·p1.00:   38.863 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293642
  mean =      3.269 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17649 
    [ 2.500,  5.000) = 269787 
    [ 5.000,  7.500) = 5279 
    [ 7.500, 10.000) = 359 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.196 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =     16.974 ms/op
     p(99.9900) =     37.004 ms/op
     p(99.9990) =     38.544 ms/op
     p(99.9999) =     38.863 ms/op
    p(100.0000) =     38.863 ms/op


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
# Warmup Iteration   1: 8.381 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.532 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.160 ±(99.9%) 0.007 ms/op
Iteration   1: 3.076 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.964 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  14.090 ms/op
                 existUser·p0.9999: 25.080 ms/op
                 existUser·p1.00:   25.526 ms/op

Iteration   2: 3.092 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.399 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.461 ms/op
                 existUser·p0.99:   5.014 ms/op
                 existUser·p0.999:  9.266 ms/op
                 existUser·p0.9999: 24.149 ms/op
                 existUser·p1.00:   25.035 ms/op

Iteration   3: 3.274 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.249 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.805 ms/op
                 existUser·p0.95:   4.055 ms/op
                 existUser·p0.99:   5.857 ms/op
                 existUser·p0.999:  14.937 ms/op
                 existUser·p0.9999: 26.139 ms/op
                 existUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305114
  mean =      3.145 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19930 
    [ 2.500,  5.000) = 280520 
    [ 5.000,  7.500) = 3802 
    [ 7.500, 10.000) = 357 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.964 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     14.107 ms/op
     p(99.9900) =     25.116 ms/op
     p(99.9990) =     26.477 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


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
# Warmup Iteration   1: 7.791 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.583 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.248 ±(99.9%) 0.011 ms/op
Iteration   1: 3.314 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.264 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   6.185 ms/op
                 getUser·p0.999:  16.503 ms/op
                 getUser·p0.9999: 33.686 ms/op
                 getUser·p1.00:   33.817 ms/op

Iteration   2: 3.281 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.466 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  11.699 ms/op
                 getUser·p0.9999: 24.544 ms/op
                 getUser·p1.00:   25.788 ms/op

Iteration   3: 3.276 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.231 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   5.784 ms/op
                 getUser·p0.999:  12.351 ms/op
                 getUser·p0.9999: 26.755 ms/op
                 getUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 291503
  mean =      3.290 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19181 
    [ 2.500,  5.000) = 264313 
    [ 5.000,  7.500) = 6993 
    [ 7.500, 10.000) = 649 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 125 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.231 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.931 ms/op
     p(99.9000) =     14.926 ms/op
     p(99.9900) =     27.997 ms/op
     p(99.9990) =     33.751 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


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
# Warmup Iteration   1: 8.659 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.110 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.809 ±(99.9%) 0.013 ms/op
Iteration   1: 3.748 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.430 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   6.893 ms/op
                 listUser·p0.999:  15.827 ms/op
                 listUser·p0.9999: 18.774 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   2: 3.749 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   7.197 ms/op
                 listUser·p0.999:  14.402 ms/op
                 listUser·p0.9999: 17.316 ms/op
                 listUser·p1.00:   18.285 ms/op

Iteration   3: 3.838 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  12.255 ms/op
                 listUser·p0.9999: 16.100 ms/op
                 listUser·p1.00:   16.138 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254136
  mean =      3.778 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 86 
    [ 2.500,  5.000) = 245608 
    [ 5.000,  7.500) = 6557 
    [ 7.500, 10.000) = 1276 
    [10.000, 12.500) = 225 
    [12.500, 15.000) = 228 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.430 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     13.875 ms/op
     p(99.9900) =     17.616 ms/op
     p(99.9990) =     20.147 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.791 ± 5.410  ops/ms
ClientPb.existUser                       thrpt       3  10.093 ± 2.937  ops/ms
ClientPb.getUser                         thrpt       3   9.919 ± 1.071  ops/ms
ClientPb.listUser                        thrpt       3   8.571 ± 0.939  ops/ms
ClientPb.createUser                       avgt       3   3.177 ± 0.857   ms/op
ClientPb.existUser                        avgt       3   3.147 ± 1.372   ms/op
ClientPb.getUser                          avgt       3   3.267 ± 0.431   ms/op
ClientPb.listUser                         avgt       3   3.749 ± 0.811   ms/op
ClientPb.createUser                     sample  293642   3.269 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.196           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.096           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.554           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.974           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.004           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.863           ms/op
ClientPb.existUser                      sample  305114   3.145 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.964           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.490           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.830           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.513           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.107           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.116           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.706           ms/op
ClientPb.getUser                        sample  291503   3.290 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.231           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.699           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.931           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.926           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.997           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.817           ms/op
ClientPb.listUser                       sample  254136   3.778 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.430           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.690           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.039           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.980           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.875           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.616           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.316           ms/op
