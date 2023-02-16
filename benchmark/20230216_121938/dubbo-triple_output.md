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
# Warmup Iteration   1: 2.302 ops/ms
# Warmup Iteration   2: 5.325 ops/ms
# Warmup Iteration   3: 8.322 ops/ms
Iteration   1: 8.988 ops/ms
Iteration   2: 8.825 ops/ms
Iteration   3: 8.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.862 ±(99.9%) 2.040 ops/ms [Average]
  (min, avg, max) = (8.774, 8.862, 8.988), stdev = 0.112
  CI (99.9%): [6.822, 10.902] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.583 ops/ms
# Warmup Iteration   2: 8.145 ops/ms
# Warmup Iteration   3: 9.223 ops/ms
Iteration   1: 9.595 ops/ms
Iteration   2: 9.639 ops/ms
Iteration   3: 9.657 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.631 ±(99.9%) 0.582 ops/ms [Average]
  (min, avg, max) = (9.595, 9.631, 9.657), stdev = 0.032
  CI (99.9%): [9.048, 10.213] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.725 ops/ms
# Warmup Iteration   2: 8.168 ops/ms
# Warmup Iteration   3: 9.130 ops/ms
Iteration   1: 8.954 ops/ms
Iteration   2: 9.426 ops/ms
Iteration   3: 9.026 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.135 ±(99.9%) 4.643 ops/ms [Average]
  (min, avg, max) = (8.954, 9.135, 9.426), stdev = 0.255
  CI (99.9%): [4.492, 13.778] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.496 ops/ms
# Warmup Iteration   2: 7.161 ops/ms
# Warmup Iteration   3: 7.407 ops/ms
Iteration   1: 7.910 ops/ms
Iteration   2: 8.286 ops/ms
Iteration   3: 8.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.120 ±(99.9%) 3.491 ops/ms [Average]
  (min, avg, max) = (7.910, 8.120, 8.286), stdev = 0.191
  CI (99.9%): [4.629, 11.611] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.092 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.859 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.648 ±(99.9%) 0.005 ms/op
Iteration   1: 3.387 ±(99.9%) 0.009 ms/op
Iteration   2: 3.488 ±(99.9%) 0.008 ms/op
Iteration   3: 3.585 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.487 ±(99.9%) 1.801 ms/op [Average]
  (min, avg, max) = (3.387, 3.487, 3.585), stdev = 0.099
  CI (99.9%): [1.686, 5.287] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.434 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.639 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.381 ±(99.9%) 0.006 ms/op
Iteration   1: 3.311 ±(99.9%) 0.004 ms/op
Iteration   2: 3.303 ±(99.9%) 0.007 ms/op
Iteration   3: 3.520 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.378 ±(99.9%) 2.240 ms/op [Average]
  (min, avg, max) = (3.303, 3.378, 3.520), stdev = 0.123
  CI (99.9%): [1.138, 5.617] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.695 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.041 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.703 ±(99.9%) 0.004 ms/op
Iteration   1: 3.455 ±(99.9%) 0.007 ms/op
Iteration   2: 3.446 ±(99.9%) 0.008 ms/op
Iteration   3: 3.505 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.469 ±(99.9%) 0.589 ms/op [Average]
  (min, avg, max) = (3.446, 3.469, 3.505), stdev = 0.032
  CI (99.9%): [2.879, 4.058] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.746 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.320 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.076 ±(99.9%) 0.009 ms/op
Iteration   1: 4.022 ±(99.9%) 0.007 ms/op
Iteration   2: 4.070 ±(99.9%) 0.009 ms/op
Iteration   3: 3.946 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.013 ±(99.9%) 1.135 ms/op [Average]
  (min, avg, max) = (3.946, 4.013, 4.070), stdev = 0.062
  CI (99.9%): [2.878, 5.147] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 11.463 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.849 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 3.704 ±(99.9%) 0.013 ms/op
Iteration   1: 3.602 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.364 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   4.776 ms/op
                 createUser·p0.99:   6.472 ms/op
                 createUser·p0.999:  19.076 ms/op
                 createUser·p0.9999: 25.923 ms/op
                 createUser·p1.00:   27.034 ms/op

Iteration   2: 3.371 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.374 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   5.628 ms/op
                 createUser·p0.999:  19.765 ms/op
                 createUser·p0.9999: 22.266 ms/op
                 createUser·p1.00:   23.560 ms/op

Iteration   3: 3.563 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.354 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.137 ms/op
                 createUser·p0.95:   4.489 ms/op
                 createUser·p0.99:   7.037 ms/op
                 createUser·p0.999:  17.624 ms/op
                 createUser·p0.9999: 31.589 ms/op
                 createUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273624
  mean =      3.509 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5101 
    [ 2.500,  5.000) = 260152 
    [ 5.000,  7.500) = 6948 
    [ 7.500, 10.000) = 825 
    [10.000, 12.500) = 253 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.354 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =     18.358 ms/op
     p(99.9900) =     29.324 ms/op
     p(99.9990) =     32.754 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.694 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.563 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.525 ±(99.9%) 0.009 ms/op
Iteration   1: 3.400 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.567 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.867 ms/op
                 existUser·p0.95:   4.424 ms/op
                 existUser·p0.99:   5.609 ms/op
                 existUser·p0.999:  19.027 ms/op
                 existUser·p0.9999: 24.052 ms/op
                 existUser·p1.00:   25.100 ms/op

Iteration   2: 3.357 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.448 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  21.765 ms/op
                 existUser·p0.9999: 24.347 ms/op
                 existUser·p1.00:   24.936 ms/op

Iteration   3: 3.356 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.737 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   6.184 ms/op
                 existUser·p0.999:  18.401 ms/op
                 existUser·p0.9999: 26.296 ms/op
                 existUser·p1.00:   26.739 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284492
  mean =      3.371 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10430 
    [ 2.500,  5.000) = 268753 
    [ 5.000,  7.500) = 4175 
    [ 7.500, 10.000) = 617 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 137 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      1.448 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     18.711 ms/op
     p(99.9900) =     25.449 ms/op
     p(99.9990) =     26.484 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


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
# Warmup Iteration   1: 10.835 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.842 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.743 ±(99.9%) 0.012 ms/op
Iteration   1: 3.517 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.317 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   4.022 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  20.416 ms/op
                 getUser·p0.9999: 22.958 ms/op
                 getUser·p1.00:   23.495 ms/op

Iteration   2: 3.535 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.810 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   6.690 ms/op
                 getUser·p0.999:  21.536 ms/op
                 getUser·p0.9999: 24.898 ms/op
                 getUser·p1.00:   25.723 ms/op

Iteration   3: 3.421 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.926 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  19.514 ms/op
                 getUser·p0.9999: 27.448 ms/op
                 getUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274854
  mean =      3.491 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5676 
    [ 2.500,  5.000) = 261183 
    [ 5.000,  7.500) = 7033 
    [ 7.500, 10.000) = 536 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 65 

  Percentiles, ms/op:
      p(0.0000) =      0.926 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     20.457 ms/op
     p(99.9900) =     27.018 ms/op
     p(99.9990) =     28.166 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


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
# Warmup Iteration   1: 11.254 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 4.350 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.136 ±(99.9%) 0.013 ms/op
Iteration   1: 4.103 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.561 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   8.036 ms/op
                 listUser·p0.999:  17.871 ms/op
                 listUser·p0.9999: 25.973 ms/op
                 listUser·p1.00:   26.575 ms/op

Iteration   2: 4.115 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.191 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.339 ms/op
                 listUser·p0.99:   8.331 ms/op
                 listUser·p0.999:  15.794 ms/op
                 listUser·p0.9999: 17.452 ms/op
                 listUser·p1.00:   23.691 ms/op

Iteration   3: 4.009 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.874 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  15.319 ms/op
                 listUser·p0.9999: 18.121 ms/op
                 listUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235422
  mean =      4.075 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 226342 
    [ 5.000,  7.500) = 6439 
    [ 7.500, 10.000) = 1752 
    [10.000, 12.500) = 383 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 195 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.561 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      7.660 ms/op
     p(99.9000) =     15.778 ms/op
     p(99.9900) =     24.379 ms/op
     p(99.9990) =     26.421 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.862 ± 2.040  ops/ms
ClientPb.existUser                       thrpt       3   9.631 ± 0.582  ops/ms
ClientPb.getUser                         thrpt       3   9.135 ± 4.643  ops/ms
ClientPb.listUser                        thrpt       3   8.120 ± 3.491  ops/ms
ClientPb.createUser                       avgt       3   3.487 ± 1.801   ms/op
ClientPb.existUser                        avgt       3   3.378 ± 2.240   ms/op
ClientPb.getUser                          avgt       3   3.469 ± 0.589   ms/op
ClientPb.listUser                         avgt       3   4.013 ± 1.135   ms/op
ClientPb.createUser                     sample  273624   3.509 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.354           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.367           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.059           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.432           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.365           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.358           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.324           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.620           ms/op
ClientPb.existUser                      sample  284492   3.371 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.448           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.202           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.825           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.711           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.449           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.739           ms/op
ClientPb.getUser                        sample  274854   3.491 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.926           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.383           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.415           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.038           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.457           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.018           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.295           ms/op
ClientPb.listUser                       sample  235422   4.075 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.561           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.932           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.660           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.778           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.379           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.575           ms/op
