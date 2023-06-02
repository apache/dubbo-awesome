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
# Warmup Iteration   1: 2.098 ops/ms
# Warmup Iteration   2: 4.745 ops/ms
# Warmup Iteration   3: 8.303 ops/ms
Iteration   1: 8.759 ops/ms
Iteration   2: 9.043 ops/ms
Iteration   3: 9.204 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.002 ±(99.9%) 4.112 ops/ms [Average]
  (min, avg, max) = (8.759, 9.002, 9.204), stdev = 0.225
  CI (99.9%): [4.890, 13.114] (assumes normal distribution)


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
# Warmup Iteration   1: 2.978 ops/ms
# Warmup Iteration   2: 9.092 ops/ms
# Warmup Iteration   3: 9.413 ops/ms
Iteration   1: 9.912 ops/ms
Iteration   2: 9.458 ops/ms
Iteration   3: 9.824 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.731 ±(99.9%) 4.390 ops/ms [Average]
  (min, avg, max) = (9.458, 9.731, 9.912), stdev = 0.241
  CI (99.9%): [5.342, 14.121] (assumes normal distribution)


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
# Warmup Iteration   1: 2.595 ops/ms
# Warmup Iteration   2: 7.904 ops/ms
# Warmup Iteration   3: 9.286 ops/ms
Iteration   1: 8.997 ops/ms
Iteration   2: 9.337 ops/ms
Iteration   3: 9.592 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.309 ±(99.9%) 5.450 ops/ms [Average]
  (min, avg, max) = (8.997, 9.309, 9.592), stdev = 0.299
  CI (99.9%): [3.859, 14.758] (assumes normal distribution)


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
# Warmup Iteration   1: 2.770 ops/ms
# Warmup Iteration   2: 7.012 ops/ms
# Warmup Iteration   3: 8.018 ops/ms
Iteration   1: 8.112 ops/ms
Iteration   2: 8.062 ops/ms
Iteration   3: 8.117 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.097 ±(99.9%) 0.555 ops/ms [Average]
  (min, avg, max) = (8.062, 8.097, 8.117), stdev = 0.030
  CI (99.9%): [7.542, 8.652] (assumes normal distribution)


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
# Warmup Iteration   1: 9.195 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.703 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.710 ±(99.9%) 0.004 ms/op
Iteration   1: 3.549 ±(99.9%) 0.008 ms/op
Iteration   2: 3.449 ±(99.9%) 0.009 ms/op
Iteration   3: 3.561 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.520 ±(99.9%) 1.127 ms/op [Average]
  (min, avg, max) = (3.449, 3.520, 3.561), stdev = 0.062
  CI (99.9%): [2.393, 4.646] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.660 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.567 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.473 ±(99.9%) 0.007 ms/op
Iteration   1: 3.503 ±(99.9%) 0.006 ms/op
Iteration   2: 3.312 ±(99.9%) 0.009 ms/op
Iteration   3: 3.255 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.357 ±(99.9%) 2.367 ms/op [Average]
  (min, avg, max) = (3.255, 3.357, 3.503), stdev = 0.130
  CI (99.9%): [0.989, 5.724] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.468 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.651 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.453 ±(99.9%) 0.004 ms/op
Iteration   1: 3.483 ±(99.9%) 0.006 ms/op
Iteration   2: 3.395 ±(99.9%) 0.005 ms/op
Iteration   3: 3.526 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.468 ±(99.9%) 1.220 ms/op [Average]
  (min, avg, max) = (3.395, 3.468, 3.526), stdev = 0.067
  CI (99.9%): [2.247, 4.688] (assumes normal distribution)


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
# Warmup Iteration   1: 10.217 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.411 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.229 ±(99.9%) 0.006 ms/op
Iteration   1: 4.009 ±(99.9%) 0.014 ms/op
Iteration   2: 4.034 ±(99.9%) 0.015 ms/op
Iteration   3: 4.006 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.017 ±(99.9%) 0.282 ms/op [Average]
  (min, avg, max) = (4.006, 4.017, 4.034), stdev = 0.015
  CI (99.9%): [3.735, 4.298] (assumes normal distribution)


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
# Warmup Iteration   1: 10.069 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 4.098 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.596 ±(99.9%) 0.010 ms/op
Iteration   1: 3.779 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.511 ms/op
                 createUser·p0.50:   3.490 ms/op
                 createUser·p0.90:   4.620 ms/op
                 createUser·p0.95:   5.964 ms/op
                 createUser·p0.99:   7.750 ms/op
                 createUser·p0.999:  14.041 ms/op
                 createUser·p0.9999: 22.446 ms/op
                 createUser·p1.00:   23.265 ms/op

Iteration   2: 3.505 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.681 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   4.002 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   6.242 ms/op
                 createUser·p0.999:  23.652 ms/op
                 createUser·p0.9999: 29.848 ms/op
                 createUser·p1.00:   30.048 ms/op

Iteration   3: 3.519 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.409 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   3.998 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  24.424 ms/op
                 createUser·p0.9999: 45.583 ms/op
                 createUser·p1.00:   46.465 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 266701
  mean =      3.597 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 255753 
    [ 5.000, 10.000) = 10429 
    [10.000, 15.000) = 223 
    [15.000, 20.000) = 19 
    [20.000, 25.000) = 138 
    [25.000, 30.000) = 103 
    [30.000, 35.000) = 8 
    [35.000, 40.000) = 4 
    [40.000, 45.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.409 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.145 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     20.663 ms/op
     p(99.9900) =     35.520 ms/op
     p(99.9990) =     46.421 ms/op
     p(99.9999) =     46.465 ms/op
    p(100.0000) =     46.465 ms/op


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
# Warmup Iteration   1: 9.972 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 3.916 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.458 ±(99.9%) 0.009 ms/op
Iteration   1: 3.424 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.718 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   6.144 ms/op
                 existUser·p0.999:  19.486 ms/op
                 existUser·p0.9999: 26.531 ms/op
                 existUser·p1.00:   27.460 ms/op

Iteration   2: 3.430 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.573 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   6.316 ms/op
                 existUser·p0.999:  20.801 ms/op
                 existUser·p0.9999: 26.647 ms/op
                 existUser·p1.00:   27.427 ms/op

Iteration   3: 3.442 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.849 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   4.022 ms/op
                 existUser·p0.99:   6.373 ms/op
                 existUser·p0.999:  10.576 ms/op
                 existUser·p0.9999: 25.297 ms/op
                 existUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 279403
  mean =      3.432 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4462 
    [ 2.500,  5.000) = 269744 
    [ 5.000,  7.500) = 3568 
    [ 7.500, 10.000) = 1156 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 59 

  Percentiles, ms/op:
      p(0.0000) =      1.573 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =     12.075 ms/op
     p(99.9900) =     25.860 ms/op
     p(99.9990) =     27.434 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


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
# Warmup Iteration   1: 11.452 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.084 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.608 ±(99.9%) 0.011 ms/op
Iteration   1: 3.667 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.761 ms/op
                 getUser·p0.50:   3.543 ms/op
                 getUser·p0.90:   4.112 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   7.283 ms/op
                 getUser·p0.999:  23.481 ms/op
                 getUser·p0.9999: 26.682 ms/op
                 getUser·p1.00:   28.443 ms/op

Iteration   2: 3.574 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.475 ms/op
                 getUser·p0.50:   3.494 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.186 ms/op
                 getUser·p0.99:   6.316 ms/op
                 getUser·p0.999:  23.169 ms/op
                 getUser·p0.9999: 36.776 ms/op
                 getUser·p1.00:   38.273 ms/op

Iteration   3: 3.780 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.829 ms/op
                 getUser·p0.50:   3.650 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   4.719 ms/op
                 getUser·p0.99:   6.472 ms/op
                 getUser·p0.999:  10.182 ms/op
                 getUser·p0.9999: 26.173 ms/op
                 getUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 261235
  mean =      3.672 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1361 
    [ 2.500,  5.000) = 252663 
    [ 5.000,  7.500) = 5503 
    [ 7.500, 10.000) = 1091 
    [10.000, 12.500) = 305 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 141 
    [25.000, 27.500) = 98 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.475 ms/op
     p(50.0000) =      3.547 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     22.807 ms/op
     p(99.9900) =     35.783 ms/op
     p(99.9990) =     38.207 ms/op
     p(99.9999) =     38.273 ms/op
    p(100.0000) =     38.273 ms/op


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
# Warmup Iteration   1: 13.385 ±(99.9%) 0.201 ms/op
# Warmup Iteration   2: 5.074 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.429 ±(99.9%) 0.016 ms/op
Iteration   1: 4.359 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.423 ms/op
                 listUser·p0.50:   4.235 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   7.807 ms/op
                 listUser·p0.999:  24.019 ms/op
                 listUser·p0.9999: 28.333 ms/op
                 listUser·p1.00:   28.770 ms/op

Iteration   2: 4.261 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.535 ms/op
                 listUser·p0.50:   4.092 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   7.840 ms/op
                 listUser·p0.999:  16.382 ms/op
                 listUser·p0.9999: 17.989 ms/op
                 listUser·p1.00:   18.317 ms/op

Iteration   3: 4.296 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.890 ms/op
                 listUser·p0.50:   4.174 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   8.222 ms/op
                 listUser·p0.999:  15.581 ms/op
                 listUser·p0.9999: 22.366 ms/op
                 listUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 222983
  mean =      4.305 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 212706 
    [ 5.000,  7.500) = 6930 
    [ 7.500, 10.000) = 2465 
    [10.000, 12.500) = 324 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 229 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      1.423 ms/op
     p(50.0000) =      4.174 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      7.913 ms/op
     p(99.9000) =     17.334 ms/op
     p(99.9900) =     26.739 ms/op
     p(99.9990) =     28.755 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.002 ± 4.112  ops/ms
ClientPb.existUser                       thrpt       3   9.731 ± 4.390  ops/ms
ClientPb.getUser                         thrpt       3   9.309 ± 5.450  ops/ms
ClientPb.listUser                        thrpt       3   8.097 ± 0.555  ops/ms
ClientPb.createUser                       avgt       3   3.520 ± 1.127   ms/op
ClientPb.existUser                        avgt       3   3.357 ± 2.367   ms/op
ClientPb.getUser                          avgt       3   3.468 ± 1.220   ms/op
ClientPb.listUser                         avgt       3   4.017 ± 0.282   ms/op
ClientPb.createUser                     sample  266701   3.597 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.409           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.420           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.145           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.710           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.889           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.663           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.520           ms/op
ClientPb.createUser:createUser·p1.00    sample          46.465           ms/op
ClientPb.existUser                      sample  279403   3.432 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.573           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.338           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.715           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.969           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.275           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.075           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.860           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.460           ms/op
ClientPb.getUser                        sample  261235   3.672 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.475           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.547           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.547           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.636           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.807           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.783           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.273           ms/op
ClientPb.listUser                       sample  222983   4.305 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.423           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.174           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.661           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.940           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.913           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.334           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.739           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.770           ms/op
