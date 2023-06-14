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
# Warmup Iteration   1: 2.269 ops/ms
# Warmup Iteration   2: 5.587 ops/ms
# Warmup Iteration   3: 8.444 ops/ms
Iteration   1: 9.296 ops/ms
Iteration   2: 9.227 ops/ms
Iteration   3: 9.609 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.377 ±(99.9%) 3.716 ops/ms [Average]
  (min, avg, max) = (9.227, 9.377, 9.609), stdev = 0.204
  CI (99.9%): [5.661, 13.093] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.684 ops/ms
# Warmup Iteration   2: 8.908 ops/ms
# Warmup Iteration   3: 9.385 ops/ms
Iteration   1: 9.620 ops/ms
Iteration   2: 9.388 ops/ms
Iteration   3: 9.570 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.526 ±(99.9%) 2.228 ops/ms [Average]
  (min, avg, max) = (9.388, 9.526, 9.620), stdev = 0.122
  CI (99.9%): [7.298, 11.754] (assumes normal distribution)


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
# Warmup Iteration   1: 3.093 ops/ms
# Warmup Iteration   2: 8.447 ops/ms
# Warmup Iteration   3: 9.042 ops/ms
Iteration   1: 9.310 ops/ms
Iteration   2: 9.286 ops/ms
Iteration   3: 9.215 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.270 ±(99.9%) 0.896 ops/ms [Average]
  (min, avg, max) = (9.215, 9.270, 9.310), stdev = 0.049
  CI (99.9%): [8.374, 10.167] (assumes normal distribution)


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
# Warmup Iteration   1: 2.993 ops/ms
# Warmup Iteration   2: 7.438 ops/ms
# Warmup Iteration   3: 7.820 ops/ms
Iteration   1: 8.049 ops/ms
Iteration   2: 8.048 ops/ms
Iteration   3: 8.086 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.061 ±(99.9%) 0.396 ops/ms [Average]
  (min, avg, max) = (8.048, 8.061, 8.086), stdev = 0.022
  CI (99.9%): [7.665, 8.457] (assumes normal distribution)


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
# Warmup Iteration   1: 10.199 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.863 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.519 ±(99.9%) 0.007 ms/op
Iteration   1: 3.415 ±(99.9%) 0.006 ms/op
Iteration   2: 3.361 ±(99.9%) 0.010 ms/op
Iteration   3: 3.305 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.361 ±(99.9%) 1.001 ms/op [Average]
  (min, avg, max) = (3.305, 3.361, 3.415), stdev = 0.055
  CI (99.9%): [2.360, 4.362] (assumes normal distribution)


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
# Warmup Iteration   1: 8.370 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.557 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.235 ±(99.9%) 0.008 ms/op
Iteration   1: 3.345 ±(99.9%) 0.007 ms/op
Iteration   2: 3.240 ±(99.9%) 0.002 ms/op
Iteration   3: 3.384 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.323 ±(99.9%) 1.365 ms/op [Average]
  (min, avg, max) = (3.240, 3.323, 3.384), stdev = 0.075
  CI (99.9%): [1.958, 4.688] (assumes normal distribution)


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
# Warmup Iteration   1: 9.934 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.748 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.448 ±(99.9%) 0.003 ms/op
Iteration   1: 3.480 ±(99.9%) 0.006 ms/op
Iteration   2: 3.346 ±(99.9%) 0.008 ms/op
Iteration   3: 3.368 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.398 ±(99.9%) 1.312 ms/op [Average]
  (min, avg, max) = (3.346, 3.398, 3.480), stdev = 0.072
  CI (99.9%): [2.086, 4.710] (assumes normal distribution)


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
# Warmup Iteration   1: 10.349 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.336 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.070 ±(99.9%) 0.005 ms/op
Iteration   1: 3.998 ±(99.9%) 0.014 ms/op
Iteration   2: 3.912 ±(99.9%) 0.012 ms/op
Iteration   3: 3.977 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.962 ±(99.9%) 0.818 ms/op [Average]
  (min, avg, max) = (3.912, 3.962, 3.998), stdev = 0.045
  CI (99.9%): [3.145, 4.780] (assumes normal distribution)


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
# Warmup Iteration   1: 9.136 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.813 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.411 ±(99.9%) 0.010 ms/op
Iteration   1: 3.445 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.565 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.932 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   6.136 ms/op
                 createUser·p0.999:  19.994 ms/op
                 createUser·p0.9999: 22.797 ms/op
                 createUser·p1.00:   23.134 ms/op

Iteration   2: 3.408 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.691 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  23.183 ms/op
                 createUser·p0.9999: 27.303 ms/op
                 createUser·p1.00:   27.951 ms/op

Iteration   3: 3.399 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.329 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  18.052 ms/op
                 createUser·p0.9999: 24.314 ms/op
                 createUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280881
  mean =      3.417 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8632 
    [ 2.500,  5.000) = 266368 
    [ 5.000,  7.500) = 4733 
    [ 7.500, 10.000) = 741 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =     18.190 ms/op
     p(99.9900) =     25.881 ms/op
     p(99.9990) =     27.747 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


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
# Warmup Iteration   1: 8.555 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.686 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.334 ±(99.9%) 0.007 ms/op
Iteration   1: 3.528 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.021 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   4.366 ms/op
                 existUser·p0.95:   4.743 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  21.070 ms/op
                 existUser·p0.9999: 24.015 ms/op
                 existUser·p1.00:   24.248 ms/op

Iteration   2: 3.392 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.098 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   6.226 ms/op
                 existUser·p0.999:  22.860 ms/op
                 existUser·p0.9999: 25.787 ms/op
                 existUser·p1.00:   26.706 ms/op

Iteration   3: 3.370 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.918 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.949 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   5.693 ms/op
                 existUser·p0.999:  12.140 ms/op
                 existUser·p0.9999: 27.066 ms/op
                 existUser·p1.00:   28.049 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 279998
  mean =      3.429 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11430 
    [ 2.500,  5.000) = 262286 
    [ 5.000,  7.500) = 5284 
    [ 7.500, 10.000) = 591 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 125 
    [25.000, 27.500) = 66 

  Percentiles, ms/op:
      p(0.0000) =      0.918 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     12.845 ms/op
     p(99.9900) =     26.345 ms/op
     p(99.9990) =     27.643 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


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
# Warmup Iteration   1: 9.249 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.698 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.412 ±(99.9%) 0.010 ms/op
Iteration   1: 3.394 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.793 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   6.603 ms/op
                 getUser·p0.999:  20.572 ms/op
                 getUser·p0.9999: 23.488 ms/op
                 getUser·p1.00:   24.478 ms/op

Iteration   2: 3.353 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.233 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   5.875 ms/op
                 getUser·p0.999:  20.849 ms/op
                 getUser·p0.9999: 24.788 ms/op
                 getUser·p1.00:   25.854 ms/op

Iteration   3: 3.397 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.606 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   5.923 ms/op
                 getUser·p0.999:  17.264 ms/op
                 getUser·p0.9999: 28.416 ms/op
                 getUser·p1.00:   30.245 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 283770
  mean =      3.381 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5080 
    [ 2.500,  5.000) = 271517 
    [ 5.000,  7.500) = 5900 
    [ 7.500, 10.000) = 736 
    [10.000, 12.500) = 217 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 155 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.793 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      6.144 ms/op
     p(99.9000) =     17.364 ms/op
     p(99.9900) =     26.792 ms/op
     p(99.9990) =     29.595 ms/op
     p(99.9999) =     30.245 ms/op
    p(100.0000) =     30.245 ms/op


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
# Warmup Iteration   1: 10.516 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.320 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.032 ±(99.9%) 0.013 ms/op
Iteration   1: 4.087 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.360 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   7.881 ms/op
                 listUser·p0.999:  22.533 ms/op
                 listUser·p0.9999: 26.919 ms/op
                 listUser·p1.00:   28.639 ms/op

Iteration   2: 4.008 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.071 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   4.964 ms/op
                 listUser·p0.99:   7.356 ms/op
                 listUser·p0.999:  16.187 ms/op
                 listUser·p0.9999: 19.890 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   3: 3.970 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.038 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  16.499 ms/op
                 listUser·p0.9999: 21.037 ms/op
                 listUser·p1.00:   23.593 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238612
  mean =      4.021 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 86 
    [ 2.500,  5.000) = 229299 
    [ 5.000,  7.500) = 6919 
    [ 7.500, 10.000) = 1607 
    [10.000, 12.500) = 188 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 192 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.360 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      7.438 ms/op
     p(99.9000) =     16.548 ms/op
     p(99.9900) =     26.055 ms/op
     p(99.9990) =     28.077 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.377 ± 3.716  ops/ms
ClientPb.existUser                       thrpt       3   9.526 ± 2.228  ops/ms
ClientPb.getUser                         thrpt       3   9.270 ± 0.896  ops/ms
ClientPb.listUser                        thrpt       3   8.061 ± 0.396  ops/ms
ClientPb.createUser                       avgt       3   3.361 ± 1.001   ms/op
ClientPb.existUser                        avgt       3   3.323 ± 1.365   ms/op
ClientPb.getUser                          avgt       3   3.398 ± 1.312   ms/op
ClientPb.listUser                         avgt       3   3.962 ± 0.818   ms/op
ClientPb.createUser                     sample  280881   3.417 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.691           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.322           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.850           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.849           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.190           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.881           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.951           ms/op
ClientPb.existUser                      sample  279998   3.429 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.918           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.273           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.088           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.506           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.808           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.845           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.345           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.049           ms/op
ClientPb.getUser                        sample  283770   3.381 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.793           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.240           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.777           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.084           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.144           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.364           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.792           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.245           ms/op
ClientPb.listUser                       sample  238612   4.021 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.360           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.792           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.438           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.548           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.055           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.639           ms/op
