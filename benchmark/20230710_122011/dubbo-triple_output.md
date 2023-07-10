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
# Warmup Iteration   1: 2.092 ops/ms
# Warmup Iteration   2: 5.334 ops/ms
# Warmup Iteration   3: 8.173 ops/ms
Iteration   1: 8.927 ops/ms
Iteration   2: 9.056 ops/ms
Iteration   3: 8.924 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.969 ±(99.9%) 1.377 ops/ms [Average]
  (min, avg, max) = (8.924, 8.969, 9.056), stdev = 0.075
  CI (99.9%): [7.592, 10.346] (assumes normal distribution)


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
# Warmup Iteration   1: 2.901 ops/ms
# Warmup Iteration   2: 8.333 ops/ms
# Warmup Iteration   3: 8.926 ops/ms
Iteration   1: 9.407 ops/ms
Iteration   2: 9.558 ops/ms
Iteration   3: 9.722 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.562 ±(99.9%) 2.872 ops/ms [Average]
  (min, avg, max) = (9.407, 9.562, 9.722), stdev = 0.157
  CI (99.9%): [6.690, 12.434] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.104 ops/ms
# Warmup Iteration   2: 8.077 ops/ms
# Warmup Iteration   3: 8.702 ops/ms
Iteration   1: 9.190 ops/ms
Iteration   2: 9.071 ops/ms
Iteration   3: 9.222 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.161 ±(99.9%) 1.452 ops/ms [Average]
  (min, avg, max) = (9.071, 9.161, 9.222), stdev = 0.080
  CI (99.9%): [7.708, 10.613] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.708 ops/ms
# Warmup Iteration   2: 6.416 ops/ms
# Warmup Iteration   3: 7.465 ops/ms
Iteration   1: 7.925 ops/ms
Iteration   2: 8.096 ops/ms
Iteration   3: 7.864 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.962 ±(99.9%) 2.194 ops/ms [Average]
  (min, avg, max) = (7.864, 7.962, 8.096), stdev = 0.120
  CI (99.9%): [5.767, 10.156] (assumes normal distribution)


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
# Warmup Iteration   1: 9.323 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.006 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.599 ±(99.9%) 0.003 ms/op
Iteration   1: 3.353 ±(99.9%) 0.012 ms/op
Iteration   2: 3.399 ±(99.9%) 0.009 ms/op
Iteration   3: 3.392 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.381 ±(99.9%) 0.457 ms/op [Average]
  (min, avg, max) = (3.353, 3.381, 3.399), stdev = 0.025
  CI (99.9%): [2.924, 3.839] (assumes normal distribution)


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
# Warmup Iteration   1: 10.008 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.770 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.467 ±(99.9%) 0.006 ms/op
Iteration   1: 3.323 ±(99.9%) 0.009 ms/op
Iteration   2: 3.315 ±(99.9%) 0.010 ms/op
Iteration   3: 3.331 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.323 ±(99.9%) 0.147 ms/op [Average]
  (min, avg, max) = (3.315, 3.323, 3.331), stdev = 0.008
  CI (99.9%): [3.176, 3.470] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 9.522 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.700 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.531 ±(99.9%) 0.005 ms/op
Iteration   1: 3.461 ±(99.9%) 0.009 ms/op
Iteration   2: 3.451 ±(99.9%) 0.007 ms/op
Iteration   3: 3.416 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.442 ±(99.9%) 0.434 ms/op [Average]
  (min, avg, max) = (3.416, 3.442, 3.461), stdev = 0.024
  CI (99.9%): [3.008, 3.877] (assumes normal distribution)


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
# Warmup Iteration   1: 10.182 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.425 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.251 ±(99.9%) 0.006 ms/op
Iteration   1: 4.142 ±(99.9%) 0.005 ms/op
Iteration   2: 3.966 ±(99.9%) 0.014 ms/op
Iteration   3: 4.008 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.038 ±(99.9%) 1.673 ms/op [Average]
  (min, avg, max) = (3.966, 4.038, 4.142), stdev = 0.092
  CI (99.9%): [2.365, 5.712] (assumes normal distribution)


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
# Warmup Iteration   1: 10.044 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.974 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.483 ±(99.9%) 0.010 ms/op
Iteration   1: 3.575 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.278 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   4.157 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   6.250 ms/op
                 createUser·p0.999:  21.305 ms/op
                 createUser·p0.9999: 27.431 ms/op
                 createUser·p1.00:   29.032 ms/op

Iteration   2: 3.584 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.827 ms/op
                 createUser·p0.50:   3.457 ms/op
                 createUser·p0.90:   4.096 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   6.144 ms/op
                 createUser·p0.999:  15.368 ms/op
                 createUser·p0.9999: 30.510 ms/op
                 createUser·p1.00:   31.228 ms/op

Iteration   3: 3.511 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.386 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   3.998 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   5.136 ms/op
                 createUser·p0.999:  19.207 ms/op
                 createUser·p0.9999: 24.730 ms/op
                 createUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 269869
  mean =      3.556 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4547 
    [ 2.500,  5.000) = 258826 
    [ 5.000,  7.500) = 5505 
    [ 7.500, 10.000) = 608 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.278 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     15.614 ms/op
     p(99.9900) =     29.361 ms/op
     p(99.9990) =     30.776 ms/op
     p(99.9999) =     31.228 ms/op
    p(100.0000) =     31.228 ms/op


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
# Warmup Iteration   1: 9.403 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.663 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.322 ±(99.9%) 0.008 ms/op
Iteration   1: 3.409 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.237 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   4.170 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  20.190 ms/op
                 existUser·p0.9999: 22.139 ms/op
                 existUser·p1.00:   24.117 ms/op

Iteration   2: 3.363 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.407 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   4.115 ms/op
                 existUser·p0.99:   5.849 ms/op
                 existUser·p0.999:  21.077 ms/op
                 existUser·p0.9999: 24.412 ms/op
                 existUser·p1.00:   25.854 ms/op

Iteration   3: 3.442 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.048 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.940 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   5.685 ms/op
                 existUser·p0.999:  8.880 ms/op
                 existUser·p0.9999: 23.986 ms/op
                 existUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281809
  mean =      3.404 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14013 
    [ 2.500,  5.000) = 260469 
    [ 5.000,  7.500) = 6352 
    [ 7.500, 10.000) = 622 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 147 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.048 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     11.651 ms/op
     p(99.9900) =     23.947 ms/op
     p(99.9990) =     25.145 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


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
# Warmup Iteration   1: 9.764 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 3.892 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.495 ±(99.9%) 0.009 ms/op
Iteration   1: 3.484 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.483 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   6.963 ms/op
                 getUser·p0.999:  19.530 ms/op
                 getUser·p0.9999: 21.561 ms/op
                 getUser·p1.00:   23.200 ms/op

Iteration   2: 3.512 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.769 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   7.102 ms/op
                 getUser·p0.999:  21.457 ms/op
                 getUser·p0.9999: 23.979 ms/op
                 getUser·p1.00:   32.014 ms/op

Iteration   3: 3.625 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.126 ms/op
                 getUser·p0.50:   3.461 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   4.776 ms/op
                 getUser·p0.99:   6.775 ms/op
                 getUser·p0.999:  17.907 ms/op
                 getUser·p0.9999: 25.657 ms/op
                 getUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271055
  mean =      3.539 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5476 
    [ 2.500,  5.000) = 255758 
    [ 5.000,  7.500) = 7807 
    [ 7.500, 10.000) = 1325 
    [10.000, 12.500) = 341 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 138 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     18.741 ms/op
     p(99.9900) =     24.372 ms/op
     p(99.9990) =     27.828 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


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
# Warmup Iteration   1: 10.815 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 4.513 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.087 ±(99.9%) 0.012 ms/op
Iteration   1: 4.111 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.731 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   7.832 ms/op
                 listUser·p0.999:  21.306 ms/op
                 listUser·p0.9999: 23.786 ms/op
                 listUser·p1.00:   24.412 ms/op

Iteration   2: 3.896 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.396 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   6.987 ms/op
                 listUser·p0.999:  16.937 ms/op
                 listUser·p0.9999: 22.777 ms/op
                 listUser·p1.00:   22.970 ms/op

Iteration   3: 4.032 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.179 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  13.926 ms/op
                 listUser·p0.9999: 15.450 ms/op
                 listUser·p1.00:   16.204 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239173
  mean =      4.011 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 230233 
    [ 5.000,  7.500) = 6596 
    [ 7.500, 10.000) = 1347 
    [10.000, 12.500) = 443 
    [12.500, 15.000) = 221 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.731 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =      7.373 ms/op
     p(99.9000) =     15.821 ms/op
     p(99.9900) =     22.976 ms/op
     p(99.9990) =     24.314 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.969 ± 1.377  ops/ms
ClientPb.existUser                       thrpt       3   9.562 ± 2.872  ops/ms
ClientPb.getUser                         thrpt       3   9.161 ± 1.452  ops/ms
ClientPb.listUser                        thrpt       3   7.962 ± 2.194  ops/ms
ClientPb.createUser                       avgt       3   3.381 ± 0.457   ms/op
ClientPb.existUser                        avgt       3   3.323 ± 0.147   ms/op
ClientPb.getUser                          avgt       3   3.442 ± 0.434   ms/op
ClientPb.listUser                         avgt       3   4.038 ± 1.673   ms/op
ClientPb.createUser                     sample  269869   3.556 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.278           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.432           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.358           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.947           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.614           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.361           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.228           ms/op
ClientPb.existUser                      sample  281809   3.404 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.048           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.342           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.211           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.759           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.651           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.947           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.854           ms/op
ClientPb.getUser                        sample  271055   3.539 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.126           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.375           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.030           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.473           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.939           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.741           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.372           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.014           ms/op
ClientPb.listUser                       sample  239173   4.011 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.731           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.825           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.373           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.821           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.976           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.412           ms/op
